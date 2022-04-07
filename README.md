# lemmy-ui-themes
custom lemmy themes for lemmy-ui

## Minty Bubble
Based on the default lemmy theme minty
![](https://github.com/2xx04/lemmy-ui-themes/raw/main/screenshots/mintybubble.jpg)

### FOR INSTANCE OWNERS:

#### How to install theme:
<sub>from https://github.com/LemmyNet/lemmy-docs/blob/main/src/en/administration/theming.md</sub>

> If you installed Lemmy with Docker, save your theme file to ./volumes/lemmy-ui/extra_themes. For native installation (without Docker), themes are loaded by lemmy-ui from ./extra_themes folder. A different path can be specified with LEMMY_UI_EXTRA_THEMES_FOLDER environment variable.

##### install wallpaper image:

Copy the images from pictrs/image/ to the same directory of your instance

### FOR LOCAL USERS:

You can use [Stylus](https://add0n.com/stylus.html) to customize your instance theme, at the time of writing custom css isn't supported in Lemmy. You can sometimes get away with a {theme-name}.diff.css if it was based on another theme and you used that as a canvas, otherwise use the normal {theme-name}.css.
