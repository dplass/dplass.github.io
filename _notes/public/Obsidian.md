---
title: Obsidian
stage: finished
created: 2021-10-26
date: 2021-10-31
---

There are many tools for digital [[personal knowledge management]]. I've used Evernote extensively, Google keep for a few months, Notion for a summer, OneNote for a day, I've watched videos on other note-taking apps, and even tried analog for a short while, but [Obsidian](https://obsidian.md/)  seems to be the one for me. Why?

## Key advantages of Obsidian
The key advantages of Obsidian for me, in order of importance:
- **Local-first with markdown text files** - The contents of your notes are yours. They are on your own computer, and they are not in some proprietary format. These text files you can open with any text editor. Future-proof. Another reason this is great is that with plain text files, it is very easy to change your organisation methods, such as moving certain files to folders, replacing tags with links, etc. As you are trying and learning what works for you, this is a huge benefit.
- **Easy linking with autocompletion** - Type `[[` and an autocompletion dropdown shows up, allowing you to search your vault using only parts of what you remember of the file name.
- **Speed** - It remains fast, even with thousands of notes (unlike Notion)
- **Many, many plug-ins** - If want Obsidian to be able to do something, somebody probably already made a plug-in for it. And if you are a programmer, you can also write anything you need yourself. Here are [[my favorite obsidian plugins]].
- **Automatic backlinks** - Like Notion and Roam, the application shows which notes are linking to the current note. This feature is not available in tools like Evernote and OneNote.
- **Viewing in parallel** - You can open many notes at the same time and view them next to each other. When you think of it, it is strange that many note-taking apps don't support this.
- **Graph view (network view)** - This panel provides a network overview of your vault, showing how the notes are linked to each other. You can color groups of notes based on specific filters, such as path or tags. It is an intuitive, associative way to look at your notes, which is a helpful tool to support your thinking.
- **Unlinked mentions** - If you use the name of a note without making an explicit link of it, it will show in the Unlinked mentions panel where you can link them explicitly with one click. This makes it easier to link notes together, even for notes you perhaps forgot existed. (Note: this does not work well if you use prefixes for specific note types)
- **Easy search with note creation** - When you hit cmd-o / ctrl-o, you can search your notes by (parts of the) file name. And when that file does not exist, you can simply hit enter to immediately create it.
- **Block transclusion** - I haven't used this much yet, but you can include parts of notes into other nodes, using `![[notename^blockid]]`. After typing the `^` it will show you a drop down so you can easily select the block you need.

Many of these points came from some youtube video I watched, but I cannot find it again. (Great example of why it is important to have good literature notes with information on the source ;) ) If somebody knows, please email me.
I've added some of my own key reasons to that list, and ordered it based on what contributed most to my own decision-making process.

## Why not Obsidian?
- **You have to set up syncing yourself** (can be done with e.g. dropbox) **or pay** a small monthly fee
- **Setting up any digital [[personal knowledge management]] system properly takes time** to figure out:  What are its features? What do you want to use it for? What then seems to be a functional setup that will work in the long-term? A system with less features like Evernote might therefore be easier -- less choices to make.
- **You can only edit in edit mode, in markdown** for now, not in preview mode. I work around this by using a theme that looks very similar in edit mode and in preview mode, and by using the [Ozan's plugin](https://github.com/ozntel/oz-image-in-editor-obsidian) that transcludes (previews) images, pdfs, iframes, and other transclusions when in edit mode. Only for rendering things like in-note dataview and task queries I still need preview mode.
- **This system is quite text-oriented** - Although you can add pictures, graphs, etc. The system still feels much more text-oriented than say Notion ([aw](https://www.reddit.com/r/Notion/comments/i8tz0p/notion_dashboard/), and this also affects its ease of use, especially for non-programmers. It is probably possible to create plugins to make it feel more visual. Perhaps with specifying a background image and icon to generate a nice visual header? Hmm...
- **It is still in beta?** - It is less polished than some other solutions. That being said, It does not feel very beta to me at this stage.
- **Quick capture** - For many other tools like Evernote many integrations with other tools already exist, making quick capture from things like mail, ebooks, task managers is readily available. But good news: Readwise now has an Obsidian plug-in!