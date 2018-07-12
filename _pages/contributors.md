---
permalink: /contributors/
title: "Contributors"
layout: splash
date: 2018-06-04T12:04:24-04:00
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row1:
  - image_path: /assets/images/contributors/salsa.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    width: "158px"
    padding: 10px;
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/contributors/mokoko.jpg
    image_caption: "Guilherme Mokoko Blaster [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/contributors/glauboy.jpg
    width: "100"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row width="100px" id="feature_row1" %}

<p float="left">
  <img src="/assets/images/contributors/mokoko.jpg" width="100" />
  <img src="/assets/images/contributors/mokoko.jpg" width="100" />
  <img src="/assets/images/contributors/mokoko.jpg" width="100" />
</p>


<figure style="width: 150px" class="align-left">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/contributors/mokoko.jpg" alt="">
  <figcaption>Itty-bitty caption.</figcaption>
  <url>#test-link</url>
    <btn_label>test-link</btn_label>
</figure>
