# Simple Social Sharing Buttons

An often overlooked method of implementing social sharing buttons (without counters) on your site. Super lightweight without any external loading or JavaScript, fully customisable using CSS alone. WordPress plugin also included.

**[Check out the demo](http://builtbyboon.com/posed/Simple-Social-Sharing-Buttons/)** or **[Read all about it](http://builtbyboon.com/blog/simple-social-sharing-buttons/)**

[built by Boon](here: http://builtbyboon.com/) - given away free

If you have questions or put this to use then [hit me up on Twitter](http://twitter.com/mattberridge)

## Using the WordPress plugin

Download `simple-social-sharing.php`, upload it into your plugins folder and activate it. To call the buttons anywhere in your theme, use the function `<?php simple_social_sharing('mattberridge'); ?>` including your Twitter username.

If you wish to show/hide any of the buttons individually, add a further attribute e.g. `<?php simple_social_sharing('mattberridge', '0,1,0'); ?>`

These are toggles for each button in the order Facebook, Twitter, Google+. `1` means show, `0` means hide.

I have also created a shortcode (to be used in the content body) which follows the same form e.g. `[simple-social-sharing twitter="mattberridge" display="0,1,0"]`