---
title: test page
summary: useful commands in markdown
author:
tags: ["tag1", "tag2"]
categories: ["Art"]

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2


# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "Photo by [Geo](https://github.com/gcushen/)"
  focal_point: "Right"
  preview_only: false
  alt_text: An optional description of the image for screen readers.
---

Here are some useful commands

{{< toc >}}

## Headers
### and subheaders

## Highlighted text

> This is a blockquote.

This is a {{< hl >}}highlighted quote{{< /hl >}}.

## Lists 

1. First item
   1. A sub-item
2. Another item

- First item
  - A sub-item
- Another item

- [x] Write math example
  - [x] Write diagram example
- [ ] Do something else


  
  
## Article citations

To cite a page or publication, you can use the cite shortcode, referencing a folder and page name that you created:

Style 1 Stream
{{< cite page="/publication/2021-chitarra" view="1" >}}

Style 2 Compact
{{< cite page="/publication/2021-chitarra" view="2" >}}

Style 3 Card
{{< cite page="/publication/2021-chitarra" view="3" >}}

Style 4 Traditional academic citation, configured by the citation_style setting in params.yaml
{{< cite page="/publication/2021-chitarra" view="4" >}}

where view corresponds to one of the available listing views used throughout Wowchemy:

If you don’t specify a view, it will default to the compact view.


## Figures

gallery:
{{< gallery album="gallery" >}}


gallery_item:
- album: gallery
  image: IMG_20210505_101014.jpg
  caption: caption of the figure
  
To cross-reference a figure, provide it with an ID, for example: {{< figure src="gallery/IMG_20210505_101014.jpg" id="wowchemy" >}}.

The figure can now be cross-referenced with a link in the form [my Figure](#figure-wowchemy).
