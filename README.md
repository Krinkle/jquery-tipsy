# tipsy

Facebook-style tooltip plugin for jQuery

(c) 2008-2010 Jason Frame (jason@onehackoranother.com)

Released under The MIT License.

## Description:

tipsy is a simple jQuery plugin for generating Facebook-style tooltips.

It's used by Twitter, Github, Slideshare and Bitbucket, amongst others.

## Homepage:

http://onehackoranother.com/projects/jquery/tipsy

## Source:

Hosted at GitHub; browse at https://github.com/wikimedia/jquery-tipsy

Or clone from:

`https://github.com/wikimedia/jquery-tipsy.git`

## Usage:

1. Copy the contents of src/{images,javascripts,stylesheets} to the corresponding asset directories in your project. 
   If the relative path of your images directory from your stylesheets directory is not "../images", you'll need to adjust tipsy.css appropriately.

2. Insert the neccesary elements in your document's `<head>` section, e.g.:
 ```html
 <script src="/resources/jquery.tipsy.js"></script>
 <link rel="stylesheet" href="/stylesheets/tipsy.css"/>
 ```

 Remember to include jquery.tipsy.js *after* including the main jQuery library.

3. Initialise Tipsy in your document ready handler, e.g.:
 ```html
 <script>
 jQuery(document).ready(function ($) {
     $('a[rel="tipsy"]').tipsy({ fade: true, gravity: 'n' });
 });
 </script>
 ```

Please refer to the docs directory for more examples and documentation.

## A note on forking:

By forking this project you hereby grant permission for any commits to your fork to be
merged back into this repository and, with attribution, be released under the terms of
the MIT License.
