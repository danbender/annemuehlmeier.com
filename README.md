Jekyll Photo Grid Gallery
=========

Jekyll theme based on [Blueprint: Google Grid Gallery](http://tympanus.net/codrops/?p=18699)

## How to use
1. Place a large image in `/img/large/`
2. Place a thumbnail version of the same image in `/img/thumb/`. _Remember to use the same file name_
3. Construction a post to display the image. Use the follow as an example:
```txt
---
layout: default
date:   2014-04-06 23:26:12
photo: 1.png
caption_header: Sample header
caption: sample caption
---
```
4. And finally, serve Jekyll source as you would normally.

Localhost deployment
=========
`jekyll build` followed by `jekyll serve`

For more details, read [documentation](http://jekyllrb.com/)
