---
title: "Welcome"
layout: splash
permalink: # /splash-page/
date: # 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/image2.png
  actions:
    - label: "Learn More"
      url: "/_pages/mission.html"
  caption: # "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "This is where it all begins"
intro: 
  - excerpt: #'We are excited to be here!'
feature_row:
  - image_path: /assets/images/image3.png
    alt: "Title 1"
    title: "Title 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/image2.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Title image 2"
    title: "Title 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/image3.png
    title: "Title 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/image2.png
    alt: "Title image 2"
    title: "Title Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/image3.png
    alt: "Title image 2"
    title: "Title Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/image2.png
    alt: "Title image 2"
    title: "Title Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# <center>We're Excited to be here!</center>

***

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}