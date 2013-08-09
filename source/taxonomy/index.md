# Taxonomy, Vocabulary and Terms
Drupal provides a generic means for categorizing content called Taxonomy. This entails Terms which are grouped into Vocabularies. You can use these tools to make things like tags or categories for blogs as well as more interesting things. Here is a list of Vocabularies used on [antiochcollege.org](http://antiochcollege.org) and how they are used.

## Course Terms 

This vocabulary is set on Course Offerings so that they may be filtered and sorted chronologically on the [course page](http://antiochcollege.org/academics/courses).


## Department

This vocabulary is what dictates how staff and faculty are sorted on the [college directory](http://antiochcollege.org/college-directory). It is set on each users general profile.

## Division

Divisions are the various schools of study that Faculty belong to. This Vocabulary is used in [Faculty Profiles](http://antiochcollege.org/academics/faculty).

## Electronic Resources

These terms are used to filter and sort [Electronic Resources](http://antiochcollege.org/about/electronic-resources) added for the self study project, and others.

## Slideshows 

The Slideshows vocabulary controls which slideshow a particular External Slide will appear in. Currently when creating or editing a piece of content of type "External Slide" you may choose "Front" (displayed on [antiochcollege.org](http://antiochcollege.org)) or "Prospective Student"(displayed on [antiochcollege.org/potential-student](http://antiochcollege.org/potential-student)). If you'd like more banner style slideshows like those, simply add a new term to this vocabulary and duplicate one of the formentiond views. Then change the new view's filter setting to match the new term that you created.

Once you've created the new view block, configure it to show up on the proper page via the [Blocks administration page](http://antiochcollege.org/admin/structure/block). 

You'll also want to duplicate this file and rename appropriately /sites/all/themes/antioch_v1/page--node--3811.tpl.php. Once you've duplicated that page you'll need to clear the drupal cache for your change to take effect.


## Tags

This term is used to categorize content of type "Image". These are mostly generated automatically via Flickr. They can be used to filter out images for particular image galleries (eg [antiochcollege.org/campus_life/farm](http://antiochcollege.org/campus_life/farm)).