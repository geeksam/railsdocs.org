---
layout: page
title: Rails API
verbose_title: Rails Docs - Wikified Tutorials and API Listing
tagline: Hand-picked links
filename: index.md
description: "A community-edited list of the most useful API docs."
---
{% include JB/setup %}



## Models ##

<div class="alert alert-success" style="float: right; width: 40%;">
  <h4>Heads up!</h4>
  These are reference docs.
  <!-- How do we do an internal page link in Jekyll? -->
  Looking for <strong><a href="/pages/tutorials.html">tutorials</a></strong>?
</div>


[Persistence](http://api.rubyonrails.org/classes/ActiveRecord/Persistence.html)  
<small>save, new_record?, toggle...</small>

[Migrations](http://api.rubyonrails.org/classes/ActiveRecord/Migration.html)  
<small>add_index, rename_table, add_column...</small>

[Associations](http://api.rubyonrails.org/classes/ActiveRecord/Associations/ClassMethods.html)  
<small>belongs_to, has_one, has_many...</small>

[Validations](http://api.rubyonrails.org/classes/ActiveModel/Validations/ClassMethods.html)  
<small>validates :acceptance, validates :presence...</small>



## Controllers ##

[Redirects](http://rubydoc.info/docs/rails/ActionController/Redirecting)  
<small>redirect_to hash, record, string, proc...</small>


## Important Classes ##
[Request](http://api.rubyonrails.org/classes/ActionDispatch/Request.html)  
<small>get?, post?, ip...</small>  
<small>CAVEAT: there are apparently more methods which aren't listed here, such as request.domain.</small>

[DateTime](http://api.rubyonrails.org/classes/DateTime.html)  
<small>beginning_of_day, past?, in_time_zone...<br>
See also: <a href="http://api.rubyonrails.org/classes/ActionView/Helpers/DateHelper.html#method-i-time_ago_in_words">DateHelper.time_ago_in_words</a>
</small>


## RSpec ##
[Core Matchers](https://www.relishapp.com/rspec/rspec-expectations/v/2-11/docs/built-in-matchers)  
<small>should, should be, should include...</small>

[Rails](https://www.relishapp.com/rspec/rspec-rails/docs)  
<small>Request specs, model specs, controller specs...</small>


## Git ##
[Think Like (a) Git](http://think-like-a-git.net), a guide to help advanced beginners internalize Git's weird but powerful way of looking at the world.
(Need a git link or two here!)   
<small>Reverting, Branching, Cherry-picking... </small>


