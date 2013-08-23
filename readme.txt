=== imaGenius ===
Contributors: iGenius 
Tags: images, filters, frames, animations
Requires at least: 2.8
Tested up to: 3.6
Stable tag: 1.6
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

The plugin allows you to add a frame, a filter or an animation effect to any image, even external to WP, by inserting the link in between two tags.

== Description ==

The short-code consists of three main parts:

• Frame (the only mandatory part)

• Photographic filter

• Effect/ Animation


**Instance:** [imagenius size="300" link="http://www.wordpress.org" filter=”saturated” effect="zoom"]imagelink.jpg[/imagenius]


[English documentation here](https://docs.google.com/file/d/0BwWjGErK0rRIbzBMcmdZRzNnTVE/edit?usp=sharing)

[Italian documentation here](https://docs.google.com/document/d/1FynGAcac_d3qFkEfbDU4cieszbB9yP35JTngHfSZ7QQ/edit?usp=sharing)

[WordPress Italian Google Plus Community](https://plus.google.com/communities/109254048492234113886)

== Installation ==

1. Upload imaGenius folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place the short-code in your posts or pages

**For Multisite installation do not activate the plugin in the network, do it from every single site's administration panel.**

**Read the documentation:** [English version](https://docs.google.com/file/d/0BwWjGErK0rRIbzBMcmdZRzNnTVE/edit?usp=sharing) - [Italian version](https://docs.google.com/document/d/1FynGAcac_d3qFkEfbDU4cieszbB9yP35JTngHfSZ7QQ/edit?usp=sharing) 

== Frequently asked questions ==

= Can I use my own texture with this plugin? =

Easy peasy! I encourage you to experiment and modify every single part of the frames, so you can put your texture in the `/wp-content/plugins/imagenius/images/` folder; name it as you want, but remember that only .png files are accepted, your image must end with this extension. Now you can put the name of your texture in the `texture=""` parameter of [framegenius] shortcode and look at the fancy result!

**Instance:**[framegenius texture="my-fancy-texture"]imagelink.jpg[/framegenius]

= Can I set different default values, size value for example? =

As you learned from [documentation](https://docs.google.com/file/d/0BwWjGErK0rRIbzBMcmdZRzNnTVE/edit?usp=sharing), default size value is setted to 225px, find 225 number in the imaGenius.php file and change it as you want. In this way, if you know what size fits well in your site, you'll be able to recall the function without specify the size value! Same process for effects, filters and textures.

**IMPORTANT:** At moment there are four functions in the file, so you have to apply changes singularly for every frame kind you want set default values. Don't panic, it's easy, every function name recall the frame type that change (Instance: polaroid_shortcode values influences polaroid frame default parameters).

**EVEN MORE IMPORTANT:** This kind of modding, at moment, refresh every time the plugin will be updated. Be patient, soon I will be able to store all your modifications, I'm working on this way! :)

= I've installed and activated the plugin in a Multisite WordPress installation, but I'm not able to see it in the single's site administration, why? =

If you install the plugin in the Network DON'T ACTIVATE IT DIRECTLY FROM THERE. Go in every single's site administration panel and activate the plugin from there.

== Screenshots ==

1. An example using `[imagenius]` shortcode

2. An animated example using `[polagenius]` shortcode

3. An example using `[roundpolagenius]` shortcode

4. A fancy animated gallery obtained via `[framegenius]` shortcode

5. Another animated gallery obtained via `[framegenius]` shortcode

6. An animated gallery obtained via `[framegenius]` shortcode


== Changelog ==

1.1 - All CSS and Textures fixed

1.2 - CSS file name/path changed

1.3 - Path issues fixed

1.4 - [framegenius] texture path issues fixed

1.5 - Autolocate /images/ path for better texture usage

1.6 - Corrected Enqueue errors

== Upgrade notice ==
