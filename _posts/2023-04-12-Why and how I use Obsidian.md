---
title: Why and how I use Obsidian
tags: [obsidian,pkm,note-management,task-management,]
---
UPDATE 11/2025: For 2 years I have been perfecting my vault use and maintanence. I will be writing a new guide on this soon, as well as how I use [Todoist](https://www.todoist.com) alongside Obsidian to manage/organize my life.

In my [previous post](/posts/My-comprehensive-note-management-systems-research/), I detailed all the research I have done over the last decade regarding note management systems. I have listed all the issues I found with them, and concluded in my choice of using [Obsidian](https://obsidian.md). This post will detail all the massive benefits of using Obsidian, including my personal workflow and mentality of PKM (Personal Knowledge Management).

## Here are some high level reasons I chose Obsidian
First, and most important, is my emphasis on local file control falls right in line with their ethos. Retaining ownership of my sensitive notes and hard work in crafting a second brain is super important. Obsidian is simply Markdown files, making this effortless. 

On their website, this quote really stands out to me that encapsulates what type of company I would like to support:
> Notes for your grandchildren. In our age when cloud services can shut down, get bought, or change privacy policy any day, the last thing you want is proprietary format and data lock-in. With Obsidian, your data sits in a local folder. Never leave your life's work held hostage in the cloud again.

Also, their UI design and messaging I personally really like. I don't think I would change a single thing. 

Lastly, they're free to use, which is amazing for software this powerful! But if you enjoy it, I would highly encourage you to support their work by purchasing the one-time payment, $25 Catalyst package. I believe the future of life enriching software lies on consumers supporting ventures like Obsidian.

## Further thoughts
- Since it's local, easy to sync all your devices via [Syncthing](https://github.com/canton7/SyncTrayzor). This is what I use by the way, couldn't recommend it enough.
- The flexibility of how I choose to organize my notes is the best I have seen.
- Their [Markdown implementation](https://help.obsidian.md/How+to/Format+your+notes) is hands down the best way to write, format and organize notes IMO. All of my blog posts are written inside Obsidian, and published via [GitHub pages and Jekyll](https://centifanto.net/posts/Easily-build-a-website-with-GitHub-pages/) I wrote about previously
- If I have a specific customization in mind, their [extensions/plugin library](https://obsidian.md/plugins) is excellent. Good example is [Readwise integration](https://help.readwise.io/article/125-how-does-the-readwise-to-obsidian-export-integration-work), where all my highlights can be pulled into my second brain in Obsidian. This is not just limited to articles or books. Anything that Readwise integrates with, such as podcasts or manual scanning of a physical books. I plan on writing a dedicated blog post about this
- [Graph view](https://help.obsidian.md/Plugins/Graph+view) is very useful in understanding how knowledge ties together
- The new [Canvas feature](https://obsidian.md/canvas) is really helpful in diagraming note structure visually

## Tags vs Backlinks vs Folders
The great debate. Which one should you use? There are no necessarily wrong answers, but I believe each one has it's strength if used properly. Here's my definition and use cases for each.

*Quick note: Obsidian really shines when backlinking is prioritized. I use the other two options  in moderation, but primarily lean on backlinks to write [Zettlekasten](https://zettelkasten.de/introduction/) style notes. Game changer with this mindset when crafting a second brain.*

#### Tags
*Example*: `#cloud`
- If it can group/bundle other notes, or a broad category
- Used sparingly, and never inline

#### Backlinks aka "tagnotes"
*Example*: `[[AWS]]`
- If a proper noun or a subject that can be referenced later and expounded upon. High probability they might become a MOC
- The forward and back links are very powerful when developing thoughts. Will have more content written on them in the future, good chance they might become a MOC

#### Folders
*Example*: `/Cloud project 1` or `/Inbox`
- High level process or pinned active project
- Have more than a couple notes that are related and are being actively worked on
- Try to move them into the `nodes` folder eventually after the project is finished

## Folder structure
Here is my current structure (obviously just a demo vault, I do not want to make my real vault public)
![Folder structure](/assets/img/obsidian_folder_structure.png)

Here is the explanation of each
- `0INBOX` = default location when note is created. I regularly clean this out and process each note
- `1PIN` = whether it's work or personal, any active project that I want to quickly bring up to resume work on goes here. After it's finished it will be tagged, backlinked and filed away
- `blog` = As I mentioned in my previous post, I organize my blog posts into three folders depending on their status
- `ingest` = This is where any outside data drops in, whether it's a Readwise highlight or a manual note with some relevant information, I can retrieve and reference it here
- `nodes` = The bulk of my collection, any random note that doesn't fall into the other categories goes in here
- `tagnotes` = Explained above
- `work` = Day job material, mostly documentation of things I've worked on that will be helpful in the future. Quite a few of my backlog/future planned blog posts have data that I will pull from here
- Finally, a single top level note `📝SCRATCHPAD` that is my quick jots area. I clean this out vigorously, and mostly use this on my Android for quick capture, and then organize later on desktop

## Other thoughts

#### Top-links
I have a template that I insert into every note that looks as follows:
```yaml
tags: #
##### tagnotes:
- [[]]
```

This gets inserted at the very top so I can prefill with my tags or tagnotes. The tagnotes field should only be a few that I know will pertain to the note I creating. Any passing mention/link to a note I leave inline of the paragraph it occurs in. 

#### I don't use the metadata field 
This is commonly used for tags, but I don't like it for the following reasons:
1. Tags don't highlight when searching
2. Tags are not clickable to filter with
3. Backlinks/tagnotes are not clickable to take you to that note

#### File deletion setting
- Mobile I have set to `confirm delete` and move to Obisidian .trash since it won't be as easily retrievable. Although rarely do I manage my notes from mobile, I am usually just adding or editing
- Desktop is opposite, since moving to the Recycle Bin is easily reversable

#### Workspaces
I use two separate workspaces since the Android version doesn't always play nice with community plugins, plus there are some shortcuts I have setup just for my phone. To change this, go to the following setting:
- Settings>About>Advanced>Override config folder
- Set obsidian workspace to `obsidian.mobile`

#### Ignore patterns for Syncthing
Speaking of workspaces, there are usually conflicts as Obsidian tries to update them so I don't back them up. The only bummer is that it doesn't keep open notes synced.
```
\.obsidian
\.obsidian.desktop
\.obsidian.mobile
```

As always, feel free to leave a comment or feedback.