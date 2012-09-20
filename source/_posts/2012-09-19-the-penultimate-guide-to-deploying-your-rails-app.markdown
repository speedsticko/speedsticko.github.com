---
layout: post
title: "The Penultimate Guide to Deploying Your Rails App"
date: 2012-09-19 22:21
comments: true
categories: [rails, nginx]
published: false
---
This is the penultimate guide to deploying your super-duper rails app to the world. I'm spent more time than I'd like to admit figuring out rails deployment.

Know your options
rbenv, rvm
web server
app server
rack server
multiple ruby versions
- passenger phusion blog recommends essentially running a separate process for your other ruby
passenger
thin
mongrel
unicorn
capistrano
pow
jruby
- jruby is getting popular as a deployment target
PaaS: Heroku
VPS