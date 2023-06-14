---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a Ph.D. student since 2022, advised by [Prof.Xuelong Li](https://scholar.google.com/citations?user=ahUibskAAAAJ&hl=zh-CN), at the School of Computer Science, [Fudan University](https://www.fudan.edu.cn/en/) (FDU), Shanghai, China. I'm also a trainee researcher of [Shanghai AI Lab](http://www.shlab.org.cn/). My research interests are in the area of 3D Vision include Low Level Vision, Rolling Shutter, 3D Vision and SLAM.

Previously I obtained my Bachelor’s degree in College of Computer Science and Electronic Engineering from [Hunan University](http://www-en.hnu.edu.cn/), 3.86/4.0, Changsha, China.


## News
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include news.html %}


## Publications
<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{ background: #ffffff; } /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publications.html %} {% endfor %}


## Teaching
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include teaching.html %}

## Map
{% _includes/news.html %}
