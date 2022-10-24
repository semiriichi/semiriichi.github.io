### Adding a post

To add a post to the homepage, go into the _posts folder and add a new file. The filename should follow the format

`year-month-day-title.md`

To the top of this markdown file, add the frontmatter text

```
---
layout: post
title: [Add title]
author: [Add name(s)]
---
```

This text tells Jekyll that it's a post so it knows how to format it.

### Editing a page

Editing any one of the non-post pages just requires editing the corresponding markdown file in the root directory. Just make sure to leave the frontmatter text alone.
