# imacros_wordpress

Helping migrate from mQtranslate/qTranslate plugin onto Polylang.

## Overview

Macro created for migrating a WordPress site from QTranslate/mQtranslate plugin onto Polylang. 

## Prerequisites

CSV in a specific format ("post_url","title_in_new_language","N/A","year","month","day","hour","minute"); 
having Polylang plugin activated; 
being logged in to the WordPress site. 

## What it does

Traverses a CSV file with URLs, opens them, clicks on "edit" in WP admin bar (so need to be logged in to the site), copies the post content, yanks out the two language versions (English and French, but this can be easily changed to any two - or more - languages), posts back the English version, creates a translation of the post (clicking on the 'plus' sign), pastes back the French (or whatever), fills out the post Publish date, saves new post.

## More Info

For more information check the iMacros [site](http://imacros.net/overview) and [wiki](http://wiki.imacros.net/Main_Page).
