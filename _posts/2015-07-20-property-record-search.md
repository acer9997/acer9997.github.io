---
layout: post
title: Property Record Search Database
categories: []
tags: ['data', 'sql', 'python', 'leaflet', 'heroku', 'postgre']
published: True
---
![Screenshot of map](/images/property_record_search.jpg)

Using the property records used through the investigative piece on homeowner's exemptions, [The Midwest Center for Investigative Reporting](http://apps.investigatemidwest.org/propertyrecords) sponsored the build for a [searchable database](http://apps.investigatemidwest.org/propertyrecords/) to accompany the story.

This application is bulit using Python and GeoDjango. Records and map points are served up from a PostgreSQL database and presented using leaflet.js. Search queries are handled by Elastic Search. The application is hosted on Heroku.com.   
