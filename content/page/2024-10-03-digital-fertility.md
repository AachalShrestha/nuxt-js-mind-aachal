---
layout: default
title: Digital Fertility
date: 2024-10-03T13:10:35.858Z
description: What effects do our phones hav on the fertility on women?
imagegallery:
  showgallery: true
  carouselgrid: grid
  galleryImages:
    - /img/tdmovieout.0.gif
    - /img/main.png
    - /img/genmo.gif
thumbnail: /img/tdmovieout.0.gif
included: true
promoted: "0"
---

<template>
  <div class="chicken-swag-container">
    <p>This question guided my exploration in the Generative Motion class. Through various animal studies, researchers have observed different impacts of phone radiation on female fertility, which could potentially affect humans as well. In my project, I investigated these potential effects and their implications.

The final visual is a point cloud model shaped like a uterus, constructed from images of flowers. Flowers have historically symbolized female sexuality in many cultures, making them a fitting medium for this representation. Given the lack of readily available data such as APIs or CSV files, I analyzed various studies on animal fertility and integrated their findings into my work. I used Agisoft Metashape to create the point cloud from numerous photographs. To dynamically illustrate the impact of phone usage, I employed YOLOv5 for phone detection via webcam. This data was sent through OSC to TouchDesigner, which triggered different effects based on the duration of the phone’s presence. The intensity of these effects correlates with the duration, mirroring how prolonged phone proximity could potentially influence fertility and related issues.</p>
    <MyComponent />
  </div>
</template>

