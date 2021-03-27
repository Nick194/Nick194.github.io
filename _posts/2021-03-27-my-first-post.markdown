---
layout: post
title:  "First Post, My New Github Site!"
date:   2021-03-27 17:02:22 +0000
categories: jekyll update
---
My Aim with creating this site is to force myself to do a bit of self improvement as a developer. I often find that the only time I do programming is at the day job, I don't give my self any time to do it outside of work.
This often means I miss out on looking up the latest trends or frameworks and languages. 

In this first post I'll talk about how I made this site! It was pretty easy actually.
This is a github-pages site, in other words its the free site github allow you to create which is hosted by them. 
All you do to get started is create a new repo and call it: `USERNAME.github.io`


Following that I cloned the repo to my machine and added an index page, I then saw you could add a template to the site using jekyll.
To do that I did the following:

Installed ruby from here: [https://www.ruby-lang.org/en/documentation/installation/](https://www.ruby-lang.org/en/documentation/installation/)

Installed bundler: `$ gem install bundler`

Installed Jekyll: `$ gem install jekyll`

Created a new jekyll project: `$ jekyll new .`

Added this line to the newly created `Gemfile`: 

`gem "github-pages", group: :jekyll_plugins`

And that was pretty much it!
