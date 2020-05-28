---
layout: post
title:  Optimal Airbnb
date:   2020-05-03 16:04:55 +0300
image:  Airbnb_logo.png
tags:   airbnb
---
<small>[Github Repo](https://github.com/Build-Wweek-AirBnB-Optimal-Price-1)</small>
<small>[Airbnb App](https://build-wweek-airbnb-optimal-price-1.github.io/Marketing-Page/index.html)</small>

![]({{site.baseurl}}/img/airbnb/Optimal_Air.png)


Optimal Airbnb was a Build-Week project I took part in for Unit 3. Along with two other
Data-Scientist, [Benjamin Bishop](https://github.com/Benjamin1118) and [Celeste Griffin](https://github.com/celestebgriff), we created a REST API that sent jsonified data to the front-end.

We were provided with data from Berlin, Germany in particular and our job was to create an endpoint that would return
a prediction of the price of a room depending on the what features the user gave.

For example, Users have these options to choose from:

 ![]({{site.baseurl}}/img/airbnb/airbnb_opt.png)


Depending on what they give, our Xgboost trained model will return a price:

![]({{site.baseurl}}/img/airbnb/airbnb_pred.png)
