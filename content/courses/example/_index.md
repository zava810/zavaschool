---
# course title, summary, and position.
linktitle: an example course
summary: learn how to use academia's docs layout for publishing online courses, softveyr documentation, and tutorials.
weight: 1

# page metadata.
title: overview
date: "2018-09-09t00:00:00z"
lastmod: "2018-09-09t00:00:00z"
draft: false  # is this a draft? true/false
toc: true  # show table of contents? true/false
type: docs  # do not modify.

# add menu entry to sidebar.
# - name: declare this menu item as a parent with id `name`.
# - weight: position of link in menu.
menu:
  example:
    name: overview
    weight: 1
---

## flexibility

this feature can be used for publishing content such as:

* **online courses**
* **project or software documentation**
* **tutorials**

the `courses` folder may be renamed. for example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## delete tutorials

**to remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## update site menu

after renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

for example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "courses"
  url = "courses/"
  weight = 50
```

or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *courses* menu configuration to:

```toml
[[main]]
  name = "docs"
  url = "docs/"
  weight = 50
```

## update the docs menu

if you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.x]` where `x` is the folder name. hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<newfoldername>]`.
