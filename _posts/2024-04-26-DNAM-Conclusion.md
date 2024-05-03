---
layout: post
title: Senior Design Project Presentation
date: 2024-04-26 16:00:00
description: Final presentation
tags: DNAM
categories: School
thumbnail: assets/img/DNAM/ArticleGroupPic.jpg
---

Today marked the conclusion of my senior design project at Auburn. Our project was the Distributed Network for Agricultural Monitoring (DNAM). If you're thinking that we missed out on a funny acronym, we know; the powers that be made us change it. The basic idea of the project is an Internet of Things agricultural monitor. Essentially, it's a box that you can set in a field or garden which is water proof and solar powered, and it collects data from your crops (such as soil moisture) and transmits that data via the LoRaWAN protocol to a gateway where it is processed and displayed on a website. From there, you could do lots more cool stuff such as notifications, AI insights, and more. 

One really cool thing about our project is that it was an international collaboration. Myself and another Auburn EE (Katie) collaborated with two EEs from THWS in Germany (Andreas and Felix) over the course of the nine month project. We visited Germany in early March, and for the last two weeks, Andreas and Felix have been here in Auburn helping us put the finishing touches on the project. 

Although we didn't accomplish absolutely everything we had hoped, we're really happy with what we did get done. Shortcomings included the notification system, the PCB, downlinking to the individual sensor boxes (this worked in Germany, but we had trouble in the US likely due to slightly different LoRaWAN characteristics), and one unintegrated sensor. Despite these issues, we were ultimately successful in our project as we demonstrated overall proof of concept of farming data being gathered remotely and transmitted to a website from a self-sustainable sensor box via LoRaWAN. 

Our capstone presentations went well, and the faculty chose us for the Outstanding Project Award. Also, Auburn wrote [this article](https://eng.auburn.edu/news/2024/04/students-in-electrical-and-computer-engineering-partner-with-international-students-on-senior-project.html) about our project! Lastly, here are some more pictures from the project.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/ArticleGroupPic.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Our picture from the article. Go read it!
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/Poster.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Our poster overview of the project
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/Website.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The website I built using Django. I did make a couple more modifications to make things look nicer, and this obviously isn't real data, but I'm really proud of how this looks and how functional it is!
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/BoxContents.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/Article.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/Aubie.JPG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DNAM/SignPic.JPG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
