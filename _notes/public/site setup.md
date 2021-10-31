---
title: Site setup
created : 2021-10-24
date: 2021-10-24
stage: in-progress
---

The site is built with [Jekyll](http://jekyllrb.com/). Content is edited within [[Obsidian]]. Code is edited with [Sublime Text](https://www.sublimetext.com/).

The original website is hosted on Versio: [dannyplass.nl](http://dannyplass.nl/).
The github pages copy is hosted on [dplass.github.io](https://dplass.github.io/).
If you are interested in my source code, you can get it via [github](https://github.com/dplass/dplass.github.io).

## The theme
My Jekyll theme is based on [Jekyll Garden](https://github.com/Jekyll-Garden/jekyll-garden.github.io), which has been developed to support  [[digital garden]]s using Obsidian markdown-style notes.

I have been refactoring code to make it better adhere to Jekyll standards (which also makes it easier to extend), and to make it better fit with my own needs. 
- I've added different [[note stages]] (note, draft, in-progress, finished) which are visualised in the note overview with icons. In the note page, the icon is shown on the right of the title header.
- I've changed the content parsing code so it looks at the slug (filename without extension) instead of the note title for internal linking.
- Fixed the image urls in mode switcher, so now it also works correctly in subfolders (e.g. for a page of a note in the notes folder)
- Show created and last updated dates in page with backlink
- Added a mail me + page-specific mail subject title to the footer
- Optimized Backlinks code. Stop looping once identified there is at least one link. And use site.documents to go through all collections. 
- Header image support for pages with backlink (notes, projects, ...). Specify image and image-alt in the yaml. 

For notes on what I still want to fix, see [[site to do]].



