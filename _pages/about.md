---
layout: about
title: about
permalink: /
subtitle: "Email: li944104439@gmail.com"

profile:
  align: right
  image: Da_Li_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: ""

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

gallery:
  enabled: true
  images:
    - image: 1.jpg
      alt: research and life snapshot
      caption: visual notes
    - image: 2.jpg
      alt: portrait-oriented visual snapshot
      caption: field of view
    - image: 8.jpg
      alt: travel and city snapshot
      caption: spaces
    - image: 12.jpg
      alt: visual highlight snapshot
      caption: moments
---

I am currently a third-year master student at Shenzhen University. I spent years at [VCC](https://vcc.tech/index) and [GM lab](https://www.gml.ac.cn/) focusing on point cloud analysis, and served as an intern at [Intellidust](https://github.com/Intellindust-AI-Lab/) under the supervision of [Xi Shen](https://xishen0220.github.io/), working on human mesh and skeleton recovery.

My research interests include human modeling, human motion generation, and human–scene interaction, with a broader focus on 3D vision and end-to-end scene reconstruction.

<div class="research-focus" aria-label="Research focus areas">
  <span>human modeling</span>
  <span>motion generation</span>
  <span>human-scene interaction</span>
  <span>3D vision</span>
  <span>scene reconstruction</span>
</div>

I am especially interested in extending these capabilities toward virtual and augmented reality systems, and in building immersive digital worlds with coherent geometry, motion, and interaction.

{% if page.gallery and page.gallery.enabled %}
{% include home_gallery.liquid images=page.gallery.images title="visual highlights" subtitle="A small selected set of visual notes from research, travel, and everyday observation." %}
{% endif %}
