# tipsy

Tipsy is a simple jQuery plugin for generating Facebook-style tooltips.

It's used by Twitter, Github, Slideshare and Bitbucket, amongst others.

## Homepage:

http://onehackoranother.com/projects/jquery/tipsy

## Source:

Hosted at GitHub; browse at https://github.com/wikimedia/jquery-tipsy

Or clone from:

`https://github.com/wikimedia/jquery-tipsy.git`

## Usage:

1. Copy the contents of src/ to the corresponding asset directories in your project.

2. Insert the neccesary elements in your document's `<head>` section, e.g.:
 ```html
 <link rel="stylesheet" href="/src/jquery.tipsy.css">
 <script src="/src/jquery.tipsy.js"></script>
 ```

 Remember to include jquery.tipsy.js *after* including the main jQuery library.

3. Initialise Tipsy in your document ready handler, e.g.:
 ```html
 <script>
 jQuery(function ($) {
     $('a[rel="tipsy"]').tipsy({ fade: true, gravity: 'n' });
 });
 </script>
 ```

Please refer to the docs directory for more examples and documentation.

## License

(c) 2008-2010 Jason Frame (jason@onehackoranother.com)

Released under The [MIT License](LICENSE).
