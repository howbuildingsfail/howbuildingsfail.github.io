---
layout: post
title:  "How I got started with Jekyll"
date:   2017-01-02 17:46 +0000
categories: jekyll update
---

#System Issues

I followed this tutorial to sort Ruby out on my Lubuntu 14.04 rig (couldn't figure out how to update it from version 1.9): 

http://ryanbigg.com/2014/10/ubuntu-ruby-ruby-install-chruby-and-you

#First build

http://stackoverflow.com/questions/39384024/jekyll-cannot-find-gem-after-bundle-install

gem install jekyll bundler 
jekyll new my-awesome-site 
cd my-awesome-site 
bundle install

#Serving

 
bundle exec jekyll serve
# => Now browse to http://localhost:4000

...So I ended up doing: 


 2020  jekyll new . --force
 2021  bundle install
 2022  bundle exec jekyll serve

