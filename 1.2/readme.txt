=== Plugin Name ===
Contributors: Giusta Julien
Donate link: http://www.giallozafferano.it/
Tags: date, calendar, style
Requires at least: 2.0.2
Tested up to: 1.2
Stable tag: 1.2

== Description ==

Here for you a simple plugin for your Blog WordPress, that will allow you to differentiate you from the other Blogs; 
This Plugin allows to visualize the date of publication of your Post / Article, with the aspect of a traditional calendar, 
with Month / Year in the superior part and the number of the Day in the inferior part.

== Installation ==

To install the plugin GZ Calendar Style, follows these 4 simple footsteps:

   1. download the file zip-archive containing the files of the Plugin and extract them on your computer. Upload the extracted directory gz-datestyle with all of his content in the directory wp-content/plugins of your WordPress installation ;
   2. from the panel of administration of WordPress, under the voice Plugin, activates the plugin GZ Calendar Date Style;
   3. modify the files under listed of your Theme WordPress that is found in the directory wp-content/themes of your WordPress installation: List of the 4 files of the Theme in which to effect the change: - index.php - archive.php - archives.php - single.php insert this code under writing as soon as before the <h2> tag container the principal information of the Post / Article (Title, date, author, etc … ) of your theme (this is the only change that is necessary to introduce to the theme); Add:

      <?php if(function_exists("draw_calendar")) draw_calendar(); ?>

      Remove:

      <?php the_time('F jS, Y') ?>

   4. To this point the date of your Post / Articles should appear in the form of calendar in your site.


== Screenshots ==

1. Screenshot of the Calendar (You can change color)


== Uninstallation ==

For uninstallation deactivate the plungin through the 'Plugins' menu in WordPress


== A brief Markdown Example ==

Ordered list:

1. Multilanguage explanation

[markdown syntax]: http://wordpress.org/extend/plugins/google-code-prettify-for-wordpress/other_notes/
            "Google Code Prettify For WordPress"

`<?php code(); // goes in backticks ?>`