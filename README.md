[![Slack Status](https://uc-slack.herokuapp.com/badge.svg)](https://uc-slack.herokuapp.com) ![Release Status]
(https://img.shields.io/badge/Release%20Status-W.I.P.-red.svg)

# jekyll-seo-social
A way to easily import social media information from YAML Front matter or other site information. Also imports specific information for SEO purposes.

This is meant to be a very simple page partial, and thus not very feature rich.




## Install
To install this partial, just drop social-graph.html into your _includes folder.

Then referrence the file in your head element of the site like so: `{% include social-graph.html %}`


## Configure
To configure each page, you have two options. Leave it blank and it will use your site's default information for the social media information. Or you can fill out the items on each of your posts like so to override the defaults:

```
---
ogtype: "website"
ogtitle: "Title of the page here"
ogdescription: "Description to use on social media"
ogimg: "http://linktoimage.com/img.png"
---
```
