---
title: Site setup
date: 2021-10-24
stage: note
---

The site is built with [Jekyll](http://jekyllrb.com/). Content is edited within [Obsidian](https://obsidian.md/). Code is edited with [Sublime Text](https://www.sublimetext.com/).

My Jekyll theme is based on [Jekyll Garden](https://github.com/Jekyll-Garden/jekyll-garden.github.io), which has been developed to support  [[digital garden]]s using Obsidian markdown-style notes.

I have been refactoring code to make it better adhere to Jekyll standards (which also makes it easier to extend), and to make it better fit with my own needs. 
- I've added different [[note stages]] (note, draft, in-progress, finished) which are visualised in the note overview with icons. 
- I've changed the content parsing code so it looks at the slug (filename without extension) instead of the note title for internal linking.

Things I still want to improve, add, or fix:
- Filter out markdown comments between %% and %%
- Add alternative internal link names
- Tag support

