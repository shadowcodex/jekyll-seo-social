![Release Status]
(https://img.shields.io/badge/Release%20Status-W.I.P.-red.svg)

# jekyll-seo-social
A way to easily import social media information from YAML Front matter or other site information. Also imports specific information for SEO purposes.

This is meant to be a very simple page partial, and thus not very feature rich.




## Install
To install this partial, just drop social-graph.html into your _includes folder.

Then referrence the file in your head element of the site like so: `{% include social-graph.html %}`


## Configure
To configure each page, you have two options. Leave it blank and it will use your site's default information for the social media information. Or you can fill out the items on each of your posts like so to override the defaults (These are all optional):

```
---
seodescription: "Description to use in search engine"
seokeyword: "Keyword or words to use in search engine"
ogtype: "website"
ogtitle: "Title of the page here"
ogdescription: "Description to use on social media"
ogimg: "http://linktoimage.com/img.png"
twittercard: true  //(Leave this out if you want to use summary only, put this in to make it summary with large image)
twittersite: "Your twitter handle without the @ sign"
twitterdescription: "Description to use on social media"
twittertitle: "Title of the page here"
twitterimage: "http://linktoimage.com/img.png"
---
```

The following should be set in your site `_config.yml`:

```
seokeyworddefault: "Set this as your default keyword incase you are lazy and forget to put one"
title: "set your default site title"
description: "set your default site description"
ogim: "Set your default image link to use on social media"
twitter_username: "Set your default twitter handle without the @ sign"
```
