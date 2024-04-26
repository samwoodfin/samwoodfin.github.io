---
layout: post
title:  "Writing Jekyll Posts in iA Writer"
date:   2024-04-26 03:58:45 -0700
categories: Jekyll
---
You have to remember to delete the title!

Typically, the best way to start a text in iA Writer is with a hashtag/pound sign/number sign (```#```) followed by the title you want to give to whatever you're writing, like so:

```
# Title as You Want it to Appear on the Page
```

This not only starts whatever you're writing off with a nice ```h1```, it is also the simplest, easiest way to give the actual file you're creating a title.

When what you're writing happens to be a Jekyll post, though, the format for that first line has to change a bit:

```
# YYYY-MM-DD-Title-with-Dashes
```

The hashtag probably isn't necessary in this case, but starting iA Writer (and Obsidian) posts/notes/texts this way is a good habit to keep.

The main thing to remember is that once you've typed that title line and hit enter/return, and you can see in the iA Writer Library that the post has taken on your intended title, _you need to delete that entire line_. 

Jekyll posts have to start with front matter. That's the section that looks like it begins and ends with a horizontal rule in Markdown, but with information about your post stuck between the sets of dashes:

```
---
layout: post
title:  "Writing Jekyll Posts in iA Writer"
date:   2024-04-26 03:58:45 -0700
categories: Jekyll
---
```

If you forget to delete the title line in the text of your post,  that post can still be published, but it's not going to look the way that you intended for it to look. 