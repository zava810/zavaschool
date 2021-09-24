+++
# a prozekts section created with the portfolio widget.
widget = "portfolio"  # see https://sourcethemes.com/academic/docs/page-builder/
headless = true  # this file represents a page section.
active = true  # activate this widget? true/false
weight = 65  # order that this section will appear.

title = "prozekts"
subtitle = "all things are difficult before they are easy"

[content]
  # page type to display. e.g. project.
  page_type = "project"
  
  # filter toolbar (optional).
  # add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # to show all items, set `tag` to "*".
  # to filter by a specific tag, set `tag` to an existing tag name.
  # to remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "all"
    tag = "*"
  
  [[content.filter_button]]
    name = "deep learning"
    tag = "deep learning"
  
  [[content.filter_button]]
    name = "other"
    tag = "demo"
  
  [[content.filter_button]]
    name = "human"
    tag = "human"
  
  [[content.filter_button]]
    name = "robotics"
    tag = "robotics"

[design]
  # choose how many columns the section has. valid values: 1 or 2.
  columns = "2"

  # toggle between the various page layout types.
  #   1 = list
  #   3 = card
  #   5 = showcase
  view = 3

  # for showcase view, flip alternate rows?
  flip_alt_rows = false

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

