---
title: My comprehensive note management systems research
tags: [blog/note,blog/task,blog/obsidian,blog/pkm]
---
I have spent many hours over the past decade+ trying a host of note/knowledge and task management systems. The big ones everyone tried, like Evernote, OneNote, phone notes, markdown management apps, outliners, the list goes on. Three few years ago I was hypnotized, as many are, into thinking Notion would solve all my productivity problems, but found myself getting frustrated every time I used it. Whether it was a quick todo, or a seed of an idea that would need to be grown into a full doc, Notion was too heavy, sluggish, and relied on too many cloud integrations to get anywhere near the tool I wanted. 

As I decided to start researching for a solution, I also grew annoyed with the "productivity experts" in their videos spending 5 minutes clicking around inside of some note app and concluding with "this app is amazing but you need to figure out what works best for you". Or they had a massive video playlist informing you to "just need to download a thousand plugins/templates, spend 6 months fine tuning and then it will be good". Couldn't there be something already built?

Enter Amplenote a little over year ago. I thought I needed an all-in-one system that enabled my brain to empty itself quickly, and then transform the brain dump information rapidly and seamlessly to a useful task or note without friction. I had zero interest in multiple apps since I thought too much might get lost in the shuffle of multiple sources of information between note and tasks apps. So I started dumping information in, developing quite the effective workflow. And the Amplenote community was really great; small, growing, dev team and founder very responsive and helpful. And while it was initially a great Task+Note system, it quickly showed itself inadequate for my needs.

Long story short, I am now all in on [Obsidian](https://obsidian.md) for my notes/knowledge management, and [Todoist](https://todoist.com/) for my tasks. I will be writing separate blog posts for my reasons on using both. This current post is just to detail some of the issues I have found with the other note apps out there, and since everyone has different requirements, you might disagree or maybe find it helpful.

I have realized while having my notes and tasks in one place seems like a good idea, it actually often confuses my brain. Is it a project note or a small note? Personal or work? If a project note, do I put the tasks in the note or create a separate task note for the project note? How will I find the tasks if they're buried a large note? What if I moved that note and forget my tasks are in there? I am sure to others it's not a brain breaking issue, but it got overwhelming for me.

Also, in the list below, you will see some apps that try to do both and fail miserably, making them worse than just a pen and paper IMO. And some of them don't even have E2EE on the notes, so all my sensitive notes/data is potentially exposed if a hacker or disgruntled employee wanted to take a peek. Hence I am now strongly convinced in the separation of my sensitive/valuable notes and my relatively non-sensitive tasks.

Lastly, I realized how much I appreciated local file control of these sensitive and valuable notes, which really cuts out a lot of the apps below.

So anyways, onto the list.

*NOTE: Anything idiotically restricted to Apple, e.g. Drafts, Craft, Roam, Bear etc, I automatically ignore*

# Previous two note apps I used

### [Amplenote](https://www.amplenote.com)

##### No trash can
If I am writing important notes or content in my knowledge management system, and accidently delete it, it's gone forever. There are a couple workarounds, but that is unacceptable to the value I place on my notes, especially my personal writing and longform content. Priceless amount of time and energy put into them, and the fact I wouldn't be able to recover them was too much for me to compromise on.

##### No local file control
I realized how much this meant to me when using Obsidian. The security of having my own backups and control of my data is massive. Also, Amplenote would auto archive notes past 30 days. This was very frustrating. There was an option to check "do not archive" on a single note, but there is no way I am doing that for all of my notes. It should be a global option.

##### Search is completely useless IMHO. 
Search is the lifeline of a productivity app, especially in regards to knowledge management. But no matter how I searched for a keyword, I inevitably either couldn't get the exact match I was looking for, causing me to manually try and remember which note I put the item in, or even more aggravating, when it did happen to find the keyword, it wouldn't highlight or take you to that section in the note. I would have to manually read through the whole note to find it. 

##### Task management is severely lacking
At first I didn't think this was a big deal, as they have the task score system, and also the idea of putting ideas into daily-jots and then transitioning them to full blown projects or simple todos seemed powerful. In practice though, really frustrating. Here are the issues:
- There was no legitimate way to tag someone. There are hacks, like creating a file with a persons name, backlinking tasks with this named note, and then sharing that note with the person, and then having them check the backlinks, or just send the tasks to that note. But wow, way too much work, not to mention the issues that would arise if you forgot to share the project file that you would backlink, or the fact there is no notification for this person to know there are items they are assigned. Inefficient and not friendly for collaborative task management.
- The notifications worked maybe 50% of the time. And when they did, if you clicked on it you wouldn't be taken to the actual task, just to the top of the note that contained the task. Completely useless. Goes back to the search issue of not being able to find stuff.
- No task hierarchy in Task view, only flat list. Really important for context when viewing subtasks of a project.
- No widget to see a list of tasks, you have to open the app.
- You can move the tasks, but only by pressing the "up" button above the keyboard. Wish it was more intuitive by just holding on a task and moving with my thumb either up OR down. 
- The UI of the tasks was not great. Especially compared to a dedicated task management app like Todoist.
	- It does not feel intuitive to me when editing a task, and the information fields are not easily recognizable at a glance, seem jumbled together.
	- Fair amount of small glitches when editing tasks. Example is if you checked a task off that was on the bottom of a note, it would scroll you to the top. Very frustrating!
	- No way to reorder tasks by drag and drop on mobile: you had to press an arrow button repeatedly to move it up or down. Very frustrating, and sometimes didn't even work. 
	- This is subjective as I know a lot of people like it, but I realized I didn't like the auto scoring system. It was constantly modifying the values based on time, priority and urgency and trying to shove them up to the top. I had to keep fighting the app due to this. I prefer a manual approach, where I can set due date and priority once, and then use the UI to filter to a view of my tasks in the way I want to see them.

It's more that Todoist addresses everything above that I complained about, but then also does it extremely well with more features. Feels frictionless when using. I will explain all of these points in a later blog post.

##### No multi pane
Very essential for writers/researchers to have multiple notes open for context and reference. Seems they've implemented sort of one recently, but IMO it's half baked two window only. No where near the functionality of Obsidian where I can tile or canvas an insane amount of notes while multitasking.

##### Subjective items
- Lack of good themes. I dislike any colors besides grays and blacks in my software, however all of Amplenote's themes are littered with different colors. 
- Calendar integration is a feature they advertise, but not only was it useless for me since I don't use Google or Outlook calendars, but the UI in Amplenote was not pleasant to use if I want to use that by itself. Just recently (May of 2022), they finally updated the mobile app to have a month view, but it is barely useable. I realized I actually dislike combing tasks with appointments in a calendar. I want those separate. Example task would be doing dishes. And example appointment would be going to the dentist. Having both of these types smashed into one calendar and micromanaging my day down to 15 minute blocks is claustrophobic for me. I prefer keeping my Exchange calendar for hard appointments, and then in a separate system have tasks I schedule for days, not specific times. This enables me to be flexible with my tasks, knowing I can do them anytime doing the day, and if I need to I can push to tomorrow. Instead of times, I use Todoist's 4 levels or priority. I feel this is a better way to slot tasks into my day around my hard appointments.
- This item is a bit hard to explain and very subjective, but the reliance on traditional tagging in the side bar is limiting IMO. It forces you to categorize notes (especially since their search doesn't work well). This makes you constantly worried about having created something but forgot to tag it for later use. They call backlinking, "inline tags", where a note is the tag. In Obsidian, backlinks are the focus instead of traditional tags. In fact you don't even need to use traditional tags in Obsidian. This is really important for the concept of linking information, and it shines in the graph view. You can then take highly backlinked notes and create MOCs. You can pin notes as MOCs in Amplenote, but really the system is encouraging you to tag/categorize instead of backlink. 
	- In [[Obsidian]] you can either search for note titles, or an exact and comprehensive search. And this enables you to just dump all your files in a massive folder without trying to organize, as the search or backlinking will enable you to quickly find what you need. 
	- Obsidian title search has most recent titles which is awesome when moving between notes.
- No native desktop apps, only PWA
- No multi/bulk select of notes
- No automatic scheduled backup to email (big deal since these notes are not local)
- No 24 hour/military time was a big issue for me personally

### [Notion](https://www.notion.so) 
Only online. Bloated and slow. Zero task management option without extensive, janky, manually built, sluggish database templates. Database exports not usable outside Notion. No E2EE option. Android data manipulation/editing severely limited in functionality. No MFA/2FA/TOTP

# Outliner/bullet based apps. 
No pure text, always tied to a bullet. These always feels cluttered/messy to me (especially annoying when trying to write a longform document but are broken up by endless bullets). Instant no go for me. If this happens to be your preference, there were still some issues with  that I noticed

#### [Logseg](https://logseq.com/) 
If wasn't an outliner, I would have given it more time. Also, no mobile app, which is a big deal for me as I write and edit notes on my phone constantly.

#### [Workflowy](https://workflowy.com/b/) 
Tries to be a outliner note and task app, but essentially non existent task management (no unified task view, no auto clearing of tasks after checking)

#### [Dynalist](https://dynalist.io/) 
This app is similar to Workflowy, with some additional cons.
-   Encourages folder organization instead of tags for grouping notes (vastly inferior, and rigid, way of grouping notes). Dynalist tags are half-baked inclusion into the system IMO
-   Tasks do not clear when checked
-   Plain text and OPML for export instead of Markdown and YAML like Amplenote

# Others

#### [Notesnook](https://notesnook.com)
- Notebook/folder based structure instead of tags
- No MFA/2FA/TOTP
- Instability of product, feels beta, customer data durability in question
- Sluggish interface
- Slow sync
- No unified task view - more of a notes app than a task management app

#### [Supernotes](https://supernotes.app)
- No mobile apps, does not work offline
- No unified task view - more of a notes app than a task management app
- Personal preference: card [hierarchy](https://youtu.be/Vj6MkLc8utI) does not feel intuitive to me. Friction/confusion just to find the parent cards, and their restricting of allowing cards to stay in sidebar without opening said card is constricting to me. In fact, Tobias even says "this is annoying" in a [YouTube walkthrough video](https://youtu.be/Vj6MkLc8utI?t=185) (timestamped to comment in video) but justifies this by saying it keeps the sidebar from being cluttered. I completely disagree and dislike function restrictions like this: if I want all of my parent cards "cluttering" (IMO this is not true) my sidebar, I should be able to. Especially considering the price they are asking
- Above average monthly price for "Unlimited", "Starter" only allows a measly 40 cards.
- No E2EE

#### [Walling](https://walling.app) 
- No unified task view. Unique design/function of walls>bricks>sections but feels beta IMO, I am personally not a fan of the design (too busy), different size and color bricks with image previews distract my brain from actual data. Cannot drag and drop bricks to new walls (have to use menu). No backlinking or tagging to tie different bricks/walls together. Does not seem to work offline very well. Slow Android app. No indication of E2EE

#### [Upnote](https://getupnote.com)
- "Task view" is a not very useful, just a static list of notes with tasks that you have to go into each note to view tasks
- Does not seem like it is designed to work offline as company has very few FAQs
- Notebook/folder based structure instead of tags silos/restricts note's flexibility
- Runs on Google's Firebase servers (migrating my data away from the big companies)
- No dev visibility, no company story, I don't even know who the team is behind the application
- Notebook based structure instead of tags
- No E2EE option
- No MFA/2FA/TOTP

#### [Organizedly](https://www.organized.ly) 
- Online only with no apps kept me from even trying/considering

#### [Evernote](https://evernote.com/) 
- I don't trust the company due to past decisions, online only unless paying for the product, too expensive for "Personal" plan, cluttered/sluggish design IMO, duplicate "tasks" and "checklists" are confusing

#### [Clickup](https://clickup.com) 
- Too many animations and color, cluttered and busy design, did not feel intuitive during demo. Relies too heavily on outside tools to be a complete solution. Too much social emphasis (just wanted a notes app, not a social network)

####  [Taskade](https://www.taskade.com) 
- Too many animations and color, cluttered and busy design, slow, did not feel intuitive during demo. Can't turn of stupid annoying "Social" sidebar (just wanted a notes app, not a social network)

####  [NimbusNotes](https://nimbusweb.me/note.php) 
- Data captivity, instant nope for me (Export notes only to PDF and HTML, import only from Evernote). No unified task view (only task list per note). They now have a task view, but it is only currently supported in the web client, making it useless to me personally. Also, even worse, they have "Tasks" as totally separate from checkboxes. Evernote is another offender in this regard. The idea of checkboxes being different than tasks makes zero sense to me. Didn't waste anymore time reviewing 

####  [Standard Notes](https://standardnotes.com) 
- Less powerful knockoff of Obsidian

#### [Joplin](https://joplinapp.org) 
- Ugly beta knockoff of Obsidian

#### [Simplenotes](https://simplenote.com) 
- Way too simple
