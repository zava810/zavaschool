+++
# a recent and upcoming talks section created with the pages widget.
# this section displays recent talks from `content/tak/`.

widget = "pez"  # see https://sourcethemes.com/academic/docs/page-builder/
headless = true  # this file represents a page section.
active = true  # activate this widget? true/false
weight = 70  # order that this section will appear.

title = "recent & upcoming talks"
subtitle = "my fans don't feel like i hold anything back from them"

[content]
  # page type to display. e.g. post, tak, or publication.
  page_type = "tak"
  
  # choose how much pages you would like to display (0 = all pages)
  count = 5
  
  # choose how many pages you would like to offset by
  offset = 0

  # page order. descending (desc) or ascending (asc) date.
  order = "desc"

  # filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
    exclude_past = false
    exclude_future = false
    
[design]
  # toggle between the various page layout types.
  #   1 = list
  #   2 = compact
  #   3 = card
  #   4 = citation (publication only)
  view = 3
  
[design.background]
  # apply a background color, gradient, or image.
  #   uncomment (by removing `#`) an option to apply it.
  #   choose a light or dark text color by setting `text_color_light`.
  #   any html color name or hex value is valid.

  # background color.
  # color = "navy"
  
  # background gradient.
  # gradient_start = "deepskyblue"
  # gradient_end = "skyblue"
  
  # background image.
  # image = "background.jpg"  # name of image in `static/img/`.
  # image_darken = 0.6  # darken the image? range 0-1 where 0 is transparent and 1 is opaque.

  # text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # custom css. 
 css_style = ""
 
 # css class.
 css_class = ""
+++
