---
layout: about
title: Home
permalink: /
subtitle:

profile:
  align: center
  image: avatar.jpg
  image_circular: true # crops the image to make it circular
  more_info: >


selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

images:
  compare: true
  slider: true

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div style="display: flex; flex-direction: column; align-items: center; gap: 5px;">

  <!-- Top: Intro Section -->
  <div style="width: 90%; max-width: 1000px;">
    <h5 style="text-indent: 0.7em; margin-bottom: 20px;">
      Hello! Welcome to my personal website!
    </h5>
    
    <h5 style="text-indent: 0.7em; margin-bottom: 20px;">
      I am a PhD student at the 
      <a href="https://www.unl.edu/">University of Nebraska-Lincoln</a>, 
      where I am conducting cutting-edge research in High-Throughput plant phenotyping, 
      particularly related to stomata, under the guidance of 
      <a href="https://bse.unl.edu/person/yufeng-ge/">Dr. Yufeng Ge</a>. 
      I hold a master's degree from the same department and previously earned my bachelor's degree in 
      Agricultural Engineering from 
      <a href="https://www.osu.edu/">The Ohio State University</a>.
    </h5>
    
    <h5 style="text-indent: 0.7em; margin-bottom: 20px;">
      My academic journey has been driven by a deep commitment to advancing agricultural sciences, 
      and I am excited to share my research and contributions with you. Welcome to my page, 
      where you can learn more about my work and academic pursuits.
    </h5>
  </div>

<!-- Bottom: Research Interests Section -->
<div style="width: 90%; max-width: 1000px; margin-top: 0px;">
  <h3 style="font-weight: bold; margin-bottom: 20px; font-size: 22px; color: #4aa3cf;">Research Interests:</h3>

  <div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
    <div style="width: 48%;">
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-leaf" style="margin-right: 8px; color: #4aa3cf;"></i>High-Throughput Plant Phenotyping</h5>
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-images" style="margin-right: 8px; color: #4aa3cf;"></i>Image Processing</h5>
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-eye" style="margin-right: 8px; color: #4aa3cf;"></i>Computer Vision</h5>
    </div>
    <div style="width: 48%;">
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-brain" style="margin-right: 8px; color: #4aa3cf;"></i>Machine / Deep Learning</h5>
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-database" style="margin-right: 8px; color: #4aa3cf;"></i>Data Science</h5>
      <h5 style="text-indent: 0.7em; margin-bottom: 15px;"><i class="fas fa-seedling" style="margin-right: 8px; color: #4aa3cf;"></i>Crop Modeling</h5>
    </div>
  </div>

<hr style="width: 99%; border-top: 2px solid #ccc; margin-top: 5px; margin-bottom: 15px;">

<center> <font color=red size=20>  </font> <center>

<div style="display: flex;justify-content: center; gap: 2%;">
  <div style="width: 48%;">
  <h3 style="font-weight: bold; font-size: 22px;"> Field </h3>
  <swiper-container
  effect="fade"
  fade-effect="crossFade: true"
  autoplay-delay="3000"
  autoplay-disable-on-interaction="false"
  speed="1000"
  loop="true"
  pagination-dynamic-bullets="true"
  pagination-clickable="true"
  pagination="true"
  navigation="true">
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/field1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/field3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/field2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/field4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  </swiper-container>
  </div>
  <div style="width: 48%;">
  <h3 style="font-weight: bold; font-size: 22px;"> Greenhouse </h3>
  <swiper-container
  effect="fade"
  fade-effect="crossFade: true"
  autoplay-delay="3000"
  autoplay-disable-on-interaction="false"
  speed="1000"
  loop="true"
  pagination-dynamic-bullets="true"
  pagination-clickable="true"
  pagination="true"
  navigation="true">
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/green3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/green1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
    <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/green2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>

  </swiper-container>
  </div>
</div>

<hr style="width: 99%; border-top: 2px solid #ccc; margin-top: 15px; margin-bottom: 10px;">

<h3 style="font-weight: bold; font-size: 24px;"> Presentations </h3>

<div style="width: 98%;">
<swiper-container effect="fade" fade-effect="crossFade: true" autoplay-delay="3000" autoplay-disable-on-interaction="false" loop="true" pagination-dynamic-bullets="true" pagination-clickable="true" pagination="true" navigation="true" speed="1000">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/pre2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/pre3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/pre4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/pre1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
</div>

