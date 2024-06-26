---
layout: post
title: Resources.Solar
date: "2018-07-23  07:40"
description: Vue.js application that queries sorts, and filters completed projects by Solar Innovations
category: blog
client: Solar Innovations
---

Throughout the years Solar Innovations has collected a decently large database of projects they've completed. This data has always been collected and stored in an Excel spreadsheet and goes back 20 years. 

Earlier this year I developed a theme gem for Jekyll. I setup a Jekyll site using that theme and integrated Vue.js with it. 

I took the data and exported it as a CSV document. From there I converted it into an array of JSON objects and cleaned up many inconsistencies; variations in units of measure, locations, removed duplicated entries, converted some strings to arrays, etc...

So I had an empty site and data to work with but needed a layout, interface, and user experience to establish. I took out a tablet of grid paper and a stack of large sticky notes. I worked out basic wireframe ideas and took mental notes on how the UX should feel. 

![alt text](/assets/img/wireframe.jpg){: class="img-thumbnail float-right w-50 ml-3" }

Following that, I took to code. I mocked up a how the interface would look statically and ran it by a few managers and administrators. From there I started to add reactivity to the features with Vue.js.

I quickly ran into an issue with the images, only about half of them were where they were suppose to be. I tracked down the problem images and continued to develop the application. 

As of writing this, the first major milestone of this build was accomplished: an application that'll query, sort, and filter completed projects.

To come is a lightbox feature for the images, image gallery objects that can also be categorized and searched, a listing of all pertinate technical documentation such as product data sheets, spec sheets, brochures, etc... 
