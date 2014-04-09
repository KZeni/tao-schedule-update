tao-scheduled-update
====================

A simple Wordpress Plugin to Schedule Content Updates

Motivation
----------

These days Wordpress is scarcely used as a pure blog. Most of the time it is used as a full blown CMS with many additional requirements. Especially the publishing workflow for posts and pages as well as their changes becomes demanding. Using plugins like visual composer or advaced custom fields with their flexbox addon it becomes common to build huge startpages, subsites and langpages using a simple, understandable visual editor insted of bolting them together using custom post types.
If this is a good and DRY way to go is not to discuss here :) 

A Problem arises as soon as you try updating such a complex single page at a specific date in the future - there is no easy way so schedule changes to already published wordpress pages inside the wordpress core functionality and there are only a few, not feature complete plugins to tackle this problem.

These are the main reasons for us to brew our own solution.

Features
--------

TAO Scheduled change is a really small plugin. It only does one thing, but tries to do this the right way: Take a copy of an arbitrary post/page/cpt, change it and make it replace the original post at a given date and time in the future.

Installation 
------------

Like every Wordpress plugin either place it in wp-content/plugins or use the integrated plugin installer.


