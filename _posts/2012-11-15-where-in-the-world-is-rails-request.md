---
layout: post
title: "Where in the world is Rails request?"
description: ""
category: 
tags: []
---
{% include JB/setup %}

## It's very hard to find the full API for the *request* object ##

The RailsGuides [describe](http://guides.rubyonrails.org/action_controller_overview.html#the-request-object) a `domain` method. I want to find the API
for this and see if there are any other little-known but helpful
methods on request. But I've hit a dead end with the generated docs:

* [ActionDispatch::Request](http://api.rubyonrails.org/classes/ActionDispatch/Request.html)
  (linked from the Guides) doesn't list `domain`.
  
* [Rack::Request](http://rack.rubyforge.org/doc/classes/Rack/Request.html) 
  (the parent object) also does not mention the `domain` method.
  
Any feedback is appreciated; I want to add this to the [collection of good API links](/).
