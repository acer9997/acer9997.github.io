---
layout: post
title: Restaurant Inspection Search
categories: []
tags: ['data', 'sql', 'python', 'heroku', 'postgre']
published: True
---
![Screenshot of map](/images/food_health_inspections.jpg)

This is an ongoing project for [CU-CitizenAccess.org](http://resturants.cu-citizenaccess.org) to track health inspections for local area restaurants. 

The application is built using Python, GeoDjango, PostGres, and hosted on Heroku.

A Python script runs weekly to update our database using a scraper that pulls data from the local public health department website. 