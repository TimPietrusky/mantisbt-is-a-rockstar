# mantisbt is a ☆ ✪ ★ rockstar

Just another `☆ ✪ ★ rockstar` theme for [MantisBT](http://www.mantisbt.org/), the free web-based bugtracking system.

> This theme just uses the magic power of CSS to transform something old into something awesome.


2012 by http://tim-pietrusky.de

## Version

Public beta*

**Elvis has not left the building ♦ Please report bug's so he can go*



## In Action

### The so called "header"
![intro](http://tim-pietrusky.de/img/mantisbt_is_a_rockstar_intro.png)

### Issues (visual enhanced)
![visual enhanced issues](http://tim-pietrusky.de/img/mantisbt_is_a_rockstar_visual_enhanced_issues.png?VERSION=3)

### Clean and high-contrast forms
![visual enhanced issues](http://tim-pietrusky.de/img/mantisbt_is_a_rockstar_form.png)

### Lovely buttons (+1)
![buttons](http://tim-pietrusky.de/img/mantisbt_is_a_rockstar_buttons.png)


## Attributes

 * Just 1 x .css & 2 x images
 * Super old CSS3
 * No HTML5 (since there is just CSS, but it should be powered by [HTML5 ★ Boilerplate](http://html5boilerplate.com))
 * Fancy gradients (powered by [Ultimate CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/))
 * +1 buttons (powered by [CSS Button Generator](http://cssbuttongenerator.com) with default settings)
 * And there is a minified version, too (powered by [CSS Compressor & Minifier](http://www.minifycss.com/css-compressor))


## Install

### With MantisBT ThemeManager

[MantisBT Theme Manager](http://github.com/TimPietrusky/MantisThemeManager)

1. [Download](http://github.com/TimPietrusky/MantisThemeManager/zipball/master)
2. Unpack
3. Rename the unpacked folder `TimPietrusky-MantisThemeManager-xxxxxxx` to `MantisThemeManager`
4. Copy the `MantisThemeManager` folder to `<mantis-root>/plugins/`
5. Go to *Manage / Manage Plugins* and hit the *Install* action for **MantisBT Theme Manager**
6. Click on the **MantisBT Theme Manager x.x.x** link to open the *choose a theme* page

### By hand

1. [Download](http://github.com/TimPietrusky/mantisbt-is-a-rockstar/zipball/master)
2. Unpack
3. Create a **rockstar** folder: `<mantis-root>/css/rockstar`
4. Copy all files from the unpacked folder `rockstar/*` to `<mantis_root>/css/rockstar/`
5. Add the following line to your `config_inc.php` to change the css file included into MantisBT: `$g_css_include_file = "/css/rockstar/default.css";`

**Your done! Go and play!**

## Tested

### MantisBT

 * 1.2.10

### Browser

 * Chrome 19
 * Firefox 12
 * Safari 5.1.5
 * Internet Explorer 9.0


## ToDo

 * Add live preview
 * Detailed optimization for Microsoft Internet Explorer
 * Test more MantisBT-Versions
 * Test more browsers

## License

Licensed under [VVL 1.33b7](http://tim-pietrusky.de/license) which means this **work** is free for all, so use it as you like.