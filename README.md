# mustard-ui-starter-wordpress-theme
A starter theme for WordPress based off [Automattic's _s](https://underscores.me/) and uses the 
[Mustard UI CSS framework](https://mustard-ui.com/). The intention is to make a very simple, 
easy-to-setup WordPress theme to begin building off of. There are no npm packages or Gulp
files so this theme is easy to use with tools like [CodeKit](https://codekitapp.com/) and [Prepros](https://prepros.io/).

### Setting Up###
To begin, clone this repo into your WordPress install's _themes_ folder. This theme uses Sass files and they 
have been compiled from the _scss_ folder into _css_. The main Sass file is `scss/theme.scss` and this 
includes the other Sass files. So you will need to set `scss/theme.scss` into `css/theme.css`. There is also 
a separate file for WooCommerce support at `scss/woocommerce.scss`.

### Additional Information ### 
Inside of the `scss` folder, there is a folder called `mustard-ui` that contains the Sass files from 
Mustard UI. I kept those separate so that if there were to be changes to Mustard UI, these files can be 
easily updated. The Sass files outside of this folder can be used to override styles in 
Mustard UI.
