---
title: A Spoonful of Hugo
description: |
  A forking fun new feature for series.
author: Alison Hill
show_post_thumbnail: false
show_author_byline: true
show_post_date: true
# for series listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Blue Mountains
  author: 
  description: |
    The Blue Mountains is an incredible part of the world, in Sydney's backyard.
    Some of my favourite activities here are camping, canyoning and hiking. 
    
    Check out the _index.md file in the /blog/spoonful-series
    folder to edit this content.
  text_link_label: ""
  text_link_url: ""
  show_sidebar_adunit: false # show ad container

# set up common front matter for all individual pages in series
cascade:
  layout: single-series       # for a series, do not change
  series: Blue Mountains  # name your series
  author: 
  show_author_byline: true
  show_post_date: true
  sidebar:
    text_link_label: ""
    text_link_url: ""
    show_sidebar_adunit: false # show ad container
    text_series_label: "In this series" 
    text_contents_label: "On this page" 
  tags:
  - hugo-site
  categories:
  - canyoning
  - hiking
---

** No content below YAML for the series _index. This file is a leaf bundle, and provides settings for the listing page layout and sidebar content.**
