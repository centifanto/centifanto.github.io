---
title: Easily build a website with GitHub pages
tags: [blog/website,blog/github,blog/obsidian,blog/jekyll]
---
This is my walkthrough of how to easily publish a site with GitHub pages and Jekyll. I am using the [Chirpy-starter](https://github.com/cotes2020/chirpy-starter/), which is just based off of the Chirpy Jekyll theme. There are a lot of Jekyll themes out there, but this one I picked for the clean styling, and also the blog centric focus. The starter version is not as customizable, but easier to get up and going. I might in the future use something more extensible, but this offered everything I need at the moment.

As I mentioned in my [previous post](/posts/new-website), I was using a static Google Site for my CV type of homepage, and then Blogger for blog posts...obviously. Both were very rigid, and also I did not like how I had to use a proprietary system to publish, especially Blogger. I wanted to write my blog posts in Markdown for two reasons. Main reason was so my posts could be easily written and linkable within my note/knowledge system of choice, Obsidian. Also, ownership of the publishing and files was important to me. I have written previously about this journey of finding a knowledge management system alongside a task management system. I will refactor these out of date posts and republish here shortly (and update this article with links once I do).

### Create the repo
For now, let me focus on the title of this post. First step was to use the template above, and name the repo `<GitHub_username>.io` in my account. Mine looks like this --> `centifanto.github.io`.

Then cloned my repo locally to customize and create posts. Here are a couple customizations I did that might be helpful for you.

NOTE: the instructions say to install all of the [dependencies/prerequisites](https://github.com/cotes2020/chirpy-starter#prerequisites), such as Ruby, but this is not needed. Installing these are just for previewing the site locally. 

### Custom domain
Pretty simple, but you just go to the repo's Pages settings to enable this. See [the docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain) for more info, but essentially I just needed a TXT record to verify domain ownership, and then A records pointing to GitHub pages endpoints

### Remove categories from tabs
Modified the `config.yml` from this:
```yaml
jekyll-archives:
  enabled: [categories,tags]
  layouts:
    tag: tag
    category: category
  permalinks:
    tag: /tags/:name/
    category: /categories/:name/
```

to this:
```yaml
jekyll-archives:
  enabled: [tags]
  layouts:
    tag: tag
  permalinks:
    tag: /tags/:name/
```

Then, deleted  `_tabs/categories.md`.

### Other config updates
- Updated all of the appropriate title, description, and social fields. 
- Updated the avatar to my Twitter profile picture
- Modified `theme_mode: [light|dark]` to just `[dark]` to nuke light mode (I hate glaring white)

### Comments
I enabled Disqus to test and it worked fine, but removed as I didn't care for the styling, not to mention their questionable privacy policies. I instead configured [utterances](https://utteranc.es/), an open source and lightweight commenting app that uses GitHub Issues to store the comments. There is no tracking, no ads, and no data lock-in. Beings this is a technical blog, I would imagine most readers will have a GitHub account. If this was a different genre of blog, maybe Disqus would be more appropriate.

### Change favicon
Go to [this page](https://chirpy.cotes.page/posts/customize-the-favicon/) for instructions

### Further customizations
Go to the [demo site](https://chirpy.cotes.page), as it contains everything else needed.

### Posts
Now onto the reason to do all of this: posting content. [This page](https://chirpy.cotes.page/posts/write-a-new-post/) has great info on all the options for the markdown files. The basics are:
- Title of markdown file needs this format of date+title --> `2023-03-10-new-post.md`
- Metadata needs `title`
- Tags need to be lowercase, and can be Obsidian nested style with a `/`, or just single string. I prefix all of my tags with `blog`, so in Obsidian my blog post tags don't clutter up my personal note tags.

Example:
```yaml
---
title: New post
tags: [blog/obsidian_nested,regular_tag]
---
Content of blog post....
```

Placed my files in the `_posts` dir.

# That's it!
Pushed all of these changes and the blog was live. You can watch the pipeline build the site in the Actions tab. Feel free to comment below if you have questions or run into issues.

