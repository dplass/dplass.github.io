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
- Filter on notes with specific tags (key areas)
- Use the backlinks listing style also for the other listings, as this way more notes can be shown in a smaller space, allowing for discovery and wandering
- Extend the backlinks listing to show note status icon if information is present, perhaps just before the note title like in the normal listing. - perhaps not as an icon, but as a word, which is easier to interpret in this case
- Extend the backlinks listing to show a small part of the header image to make everything a bit more visual, perhaps as a narrow slice at the top of the note block, more for aesthetics than for actually showing the contents of the picture?
- Finish the final refactoring of the original theme in terms of separating layouts and making file names lowercase
- Filter out markdown comments between %% and %%
- Dealing with aliases – aliases can perhaps be used as an alternative to alternative internal links (see item below)
- Add alternative internal link names with pipe syntax - tried to work on this, but there is some additional processing going on somewhere in the background that makes it more difficult than I thought.

**Could have**
- Support for different types of document listings, with or without images, also smaller like the backlinks listing
- Graph view showing the links between notes
- Tag support (I don't use tags that much, aside from indicating note status and note type)
- Improve the content parsing code, as it is now pretty inefficient going through arrays multiple times unnecessarily. Not a problem right now, but could be problematic when the digital garden gets larger? Yey for pre-building ;)
- Make the back button just go back one step using browser history. Makes the behavior more as expected when going through different notes via internal links.

For more information on the full setup for my site, see [[site setup]].