---
title: How I write blog posts
tags: [obsidian,website,github]
---
UPDATE 11/2025: I will eventually be migrating this blog to [Astro](https://astro.build). I built my company website with it, [Integritas Cloud Solutions](https://integritascloud.solutions).

Now that I've [migrated to GitHub Pages](/posts/Easily-build-a-website-with-GitHub-pages/), here is my process for writing blog posts.

I have a folder in Obsidian that house my blog posts. Contains the following sub folders:
- Backlog = single ideas, half written/shelved posts
- In progress = actively writing
- Published = finished and pushed to GitHub

If I have a new idea, I create a note and put it in the `backlog` folder. If I want to start writing right away, and hit `Ctrl+p`, then "Insert template>blog template", and move to `in progress` folder. This my template that contains the metadata fields needed, along with the `{ { date } }` field that auto populates and is needed in the title for the blogging system. It looks like this
```yaml
---
title: 
tags: [template]
---

{ { date } }-title
```

I then cut the populated date and add a headline to the title i.e. `2023-03-22-How I write blog posts`, and add appropriate tags. Note, I prefix all of my blog tags with `blog`, so that they stay separate from my main tag set. In Obsidian, I don't use tags like I do on the website. So for instance the tag `Obsidian` would not be a tag inside of Obsidian, it would instead be it's own note, which I call a tagnote. You can read my how I use Obsidian post to learn more about this. Anyways, it'd look like this:
```yaml
2023-03-22-How I write blog posts
---
title: How I write blog posts
tags: [obsidian,website,github]
---
```

Then I write the post content, add links to other applicable blog posts with `Ctrl+k`, tidy up structure and headings, and I'm finished.

Next I copy the file from my Obsidian vault to my local repo `_posts` dir. Commit and push, GitHub builds the page. Done

Note, I do the above copy step so I can have my blog content searchable within my Vault for backlinking, knowledge management, and ownership of my content. You can have your vault live in your local repo, and add dirs to the `.gitignore` so they don't get pushed, but that is too risky for me, as I do not ever want my personal notes accidently committed to version control history. There is a couple alternatives I found that add local watcher scripts to monitor your specific blog folder in your vault that then copies over, but it's a fair amount of work to setup, plus I like to have control over every step, and copying a single markdown file is quick and easy. Less things to break IMO. I am DevOps engineer during the day, I don't need my blogging process overly complicated. 