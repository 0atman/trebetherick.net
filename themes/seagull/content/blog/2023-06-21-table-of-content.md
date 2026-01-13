+++
title = "Table of <i>content</i>"
description = "This blog post shows the table of content feature and also the infobox shortcodes."

extra.thumbnail = "/img/bird-3.jpg"
taxonomies.authors = ["You"]
taxonomies.tags = ["TOC", "box"]
taxonomies.category = ["blog"]
+++

# Title

You can introduce your subject.

Then insert your table of content below:

[TOC]

## Subtitle

Section

{% note(type="info") %}
Blue info box with an icon
{% end %}

## Other subtitle

Content

{% note(type="warning", size="large", markdown=true) %}
Yellow warning box with a **large** icon and *Markdown* content.  
Useful for multiline info box.  
Like this  
...
{% end %}