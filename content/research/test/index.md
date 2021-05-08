---
title: test page

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

We are interested in rotationally-resolved spectroscopy mainly, but only, in the low-frequency part of the electromagnetic spectrum.

[Scroll down to a page section with heading another](#exp)

{{< toc >}}


## HR spectroscopy mm to FIR

## Exp devlpment

> This is a blockquote.

This is a {{< hl >}}highlighted quote{{< /hl >}}.

1. First item
   1. A sub-item
2. Another item

- First item
  - A sub-item
- Another item

- [x] Write math example
  - [x] Write diagram example
- [ ] Do something else


{{< gallery album="gallery" >}}
gallery_item:
- album: gallery
  image: IMG_20210505_101014.jpg
  caption: test
  
  
## Whatever

To cite a page or publication, you can use the cite shortcode, referencing a folder and page name that you created:

{{< cite page="/publication/2021-chitarra" view="1" >}}

{{< cite page="/publication/2021-chitarra" view="2" >}}

{{< cite page="/publication/2021-chitarra" view="3" >}}

{{< cite page="/publication/2021-chitarra" view="4" >}}

where view corresponds to one of the available listing views used throughout Wowchemy:

1 Stream
2 Compact
3 Card
4 Traditional academic citation, configured by the citation_style setting in params.yaml

If you don’t specify a view, it will default to the compact view.


To cross-reference a figure, provide it with an ID, for example: {{< figure src="IMG_20210505_101014.jpg" id="wowchemy" >}}.
Assets images library {{< figure src="icon.png" id="wowchemy" >}}

The figure can now be cross-referenced with a link in the form [my Figure](#figure-wowchemy).
