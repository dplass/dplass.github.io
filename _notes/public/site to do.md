---
title: Site To Do
stage: draft
created: 2021-10-24
date: 2021-10-24
image: /assets/img/checklist_1920.jpg
image-alt: Checklist - Image by StockSnap from Pixabay
---

Things I still want to improve, add, or fix:

**Should have**
- Finish the final refactoring of the original theme in terms of separating layouts and making file and folder names lowercase
- Filter out markdown comments between %% and %%
- Add alternative internal link names with pipe syntax - tried to work on this, but there is some additional processing going on somewhere in the background that makes it more difficult than I thought.
- Get rid of the public/private folder structure, as it makes permalinks unnecessarily long

**Could have**
- Support for different types of document listings, with or without images, also smaller like the backlinks listing
- Decrease h2 (and h3?) size, or use a different color
- Graph view showing the links between notes
- Tag support (I don't use tags that much, aside from indicating note status and note type)
- Improve the content parsing code, as it is now pretty inefficient going through arrays multiple times unnecessarily. Not a problem right now, but could be problematic when the digital garden gets larger? Yey for pre-building ;)
- Make the backbutton just go back one step using browser history. Makes the behaviour more as expected when going through different notes via internal links.
- Adjust responsiveness widths. It gets very narrow before moving to mobile full width mode.

For more information on the full setup for my site, see [[site setup]].