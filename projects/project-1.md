---
layout: project
type: project
image: images/cuponerapp-square.png
title: Cuponerapp
permalink: projects/cuponerapp
# All dates must be YYYY-MM-DD format!
date: 2017-07-01
labels:
  - PHP
  - jQuery
  - MongoDB
  - GIT
  - MySQL
summary: A web page / admin panel / customer panel for one of the fastest growing digital agencies in Mexico.
---

<img class="ui medium right floated rounded image" src="../images/cuponerapp-home.jpg">

Cuponerapp has a range of web pages and panel I created when I was the sole developer. It helped me to understand how a bussiness flow can be optimized with web technologies and a different range of technologies, since most of the solutions were developed in-house.

The [web page](https://www.cuponerapp.com) is implement with native PHP code, as requested by the founder, it uses htaccess rules to handle pretty urls and redirect to correct file. It was updated to match functionality of our native apps for iOS and Android, allowing users to redeem coupons and buy tickets.
SEO was key in this project and optimizations were made to the web page, ranging from minification to image optimization with Imagemagick. 

The **admin panel** was created from zero, with users and permission system implemented in native PHP. Besides allowing basic CRUD operations it displays:

 - Analytics implemented with MongoDB.  
 - Purchase history
 - Predictions of inventory availability
 - Tracking of brand performance
 - Provides html for our custom marketing mailing format
 - Send push notification with iOS and Android native functions (later moved to Firebase)
 - Heat maps of users
 - 
Similarly the **Clients panel** was made from scratch in native PHP, it enables our associated brands to check on the marketing campaigns performance, allowing to check the latest redemptions or sales, stats and demography ouf the users reached.

In Cuponerapp I also perform devops functions, implementing security measures and automated deployment. Anti-fraud filters made with machine learning are about to be send to productions server.

Source: No public repository exists.
