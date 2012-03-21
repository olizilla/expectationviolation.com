=== Simple Slideshow ===
Contributors: dlanger
Donate link: http://daniellanger.com/blog/simple-slideshow
Tags: slideshow, jquery, cycle, photos, photographs
Requires at least: 3.0
Tested up to: 3.2
Stable tag: 1.0

Easily add a clean jQuery-powered slideshow to your site. Integrates well into any theme, easy to configure.

== Description ==

I was looking for a simple way to add a [jQuery Cycle Lite](http://jquery.malsup.com/cycle/lite/) slideshow to my posts. Something clean,
that takes advantage of WordPress' built-in file-management system, and doesn't require learning all sorts of new templating
and organization systems. I couldn't find one, so I wrote my own.

Simple Slideshow is exactly what it says on the box. It's a plugin that's simple to deal with, and when used, produces a simple-looking
slideshow that integrates well into any theme, and won't clash with other plugins. 

If you have any problems with it, check out the [issue tracker](https://github.com/dlanger/simple-slideshow/issues) or 
post something in the WordPress [forums](http://wordpress.org/support/) and I'll try and help you figure it out. Most are
caused by other incorrectly-coded themes or plugins, and can be easily solved. 

== Installation ==

1. Unzip `simple_slideshow.zip` into its own folder within the `wp-content/plugins/` folder of your Wordpress installation. If you install
Simple Slideshow through the administration menu of your blog, this step is done automatically for you. 

2. Under the *Installed Plugins* menu (under *Plugins*), click *Activate* in the Simple Slideshow section - 
this enables the plugin, and tells Wordpress that the shortcode you'll use to place a slideshow means something.

3. That's it! Check out the *Instructions* tab on the Simple Slideshow menu (which you'll find in the *Settings*
section of Wordpress' admin menu) for easy instructions (with screenshots) on how to insert a slideshow in a post. 

== Frequently Asked Questions ==

= How do I add a slideshow to a page? =

First, you need to upload the images that you'd like in your slideshow. Use the built-in *media uploader* to do this; 
while editing the post, click the small picture icon above the post you're editing to open it. From this screen you can add, edit, rename, and 
delete the photos that will be in the slideshow. Once they're uploaded, add `[simples_slideshow]` where you'd like the 
slideshow to appear in the page.

There's no need to add the images individually to the post; Simple Slideshow automatically grabs all the images you've attached
to the post and puts them in the show.

= Where are the menu and settings for Simple Slideshow? = 

Under the *Settings* section of the Administration section, on the page entitled *Simple Slideshow*.

= How do I make the images change faster or slower? =

The slideshow will advance when the forwards/backwards arrows are clicked. If you'd like to make the transition between images
faster or slower, you can pass attributes to the shortcode - for example, `[simple_slideshow time="1000"]`. For full documentation on this, 
check out the *Attributes* tab in the Simple Slideshow menu.

= How do I change the order of images in the slideshow? =

In the *media uploader*, go to the *Gallery* tab. There, drag the images up and down to put them in 
the order you'd like them to be shown in (top to bottom). When you're done, press *Save all changes*,
and the new order will be shown when you reload the post containing the slideshow.

= I want to improve/change/work on/modify Simple Slideshow =

That's great! This plugin is licensed under the [FreeBSD license](http://www.freebsd.org/copyright/freebsd-license.html), which means that you're free to 
do pretty much anything you'd like with it. If you've got some changes you'd like to merge back into the plugin (for which I'll be grateful, and
will send you a postcard as thanks), development is being hosted at [github](https://github.com/dlanger/simple-slideshow/) - grab the most up-to-date source from there and send me a pull
request with your change.

== Screenshots ==

1. The Simple Slideshow control panel - documentation on how to change the individual shows on tabs, and contextual
help on the meaning of each option from the drop-down at the top.

2. A snippet from the step-by-step instructions (with screenshots) on how to use Simple Slideshow, found on the
<em>Instructions</em> tab.

3. An example slideshow - <code>[simple_slideshow size="medium" link_click="1"]</code>. Fonts, colors, and
link decorations are all styled by the theme that's in use.

== Changelog ==

= 1.0 =
* First public release.

== Upgrade Notice ==

= 1.0 =
Initial upload to Wordpress.org.