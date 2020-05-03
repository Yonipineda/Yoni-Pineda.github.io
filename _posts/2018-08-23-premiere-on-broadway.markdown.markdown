---
layout: post
title:  Twittoff
date:   2020-05-03 16:04:00 +0300
image:  twitter_birdy.png
tags:   Rest
---
<small>[Github Repo](https://github.com/Yonipineda/Twittoff_App)</small>
<small>[Twittoff](https://twittoff-brawl.herokuapp.com/)</small>


![]({{site.baseurl}}/img/twittoff.png)

Twittoff is a machine learning application. You select two Twitter users, type in a message, it can be whatever you want and, the algorithm does its best to predict which of the two individuals chosen is most likely to say the given text.

You also have the option to add a User, so long as their account is not on private. You can also read their current tweets and, delete them from the site.

Below is a quick demo of the app!

![]({{site.baseurl}}/img/twittoff_demo2.gif)

### A quick guide on how to set up the environment


Feel free to clone the app and try it out locally!

1. Clone the repo
> git clone <git.repo>

2. Install requirements
> pipenv install -r requirements.txt

3. Activate shell
> pipenv shell

4. Set the FLASK_APP environment variable
> export FLASK_RUN=twittoff:APP

5. Run the app locally
> flask run
