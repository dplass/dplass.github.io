---
title: Site setup
date: 2021-10-24
stage: in-progress
---

The site is built with [Jekyll](http://jekyllrb.com/). Content is edited within [Obsidian](https://obsidian.md/). Code is edited with [Sublime Text](https://www.sublimetext.com/).

The original website is hosted on Versio: [dannyplass.nl](http://dannyplass.nl/).
The github pages copy is hosted on [dplass.github.io](https://dplass.github.io/).
If you are interested in my source code, you can get it via [github](https://github.com/dplass/dplass.github.io).

## The theme
My Jekyll theme is based on [Jekyll Garden](https://github.com/Jekyll-Garden/jekyll-garden.github.io), which has been developed to support  [[digital garden]]s using Obsidian markdown-style notes.

I have been refactoring code to make it better adhere to Jekyll standards (which also makes it easier to extend), and to make it better fit with my own needs. 
- I've added different [[note stages]] (note, draft, in-progress, finished) which are visualised in the note overview with icons. 
- I've changed the content parsing code so it looks at the slug (filename without extension) instead of the note title for internal linking.
- Fixed the image urls in mode switcher, so now it also works correctly in subfolders (e.g. for a page of a note in the notes folder)

## To do
Things I still want to improve, add, or fix:

**Should have**
- Also show note stage in single note view
- Finish the final refactoring of the original theme in terms of separating layouts and making file and folder names lowercase
- Filter out markdown comments between %% and %%
- Add alternative internal link names

**Could have**
- Tag support (I don't use tags that much, aside from indicating note status and note type)
- Improve the content parsing code, as it is now pretty inefficient going through arrays multiple times unnecessarily. Not a problem right now, but could be problematic when the digital garden gets larger.

