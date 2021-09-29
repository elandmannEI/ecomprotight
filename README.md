# ecomprotight
Magento Ecompro Tight Admin Theme

Maintainer: Eric Landmann, eric@ecompro.tech

Created: 10/1/21

### Description

This is an alternate admin theme for Magento 2. It has been tested on Community Edition v. 2.3.5-p1. It requires a fully functional Magento 2 installation.

### Features

**Alternate color scheme** – Tired of the same old stock Magento admin theme and colors? This theme uses a green navbar, orange links, light green footer.

**Color variables** – There is a color reference found in docs/tight_color_names.html that shows the color variable names and their hex values.

**Tighter spacing** – The stock Magento admin theme is very airy with a lot of wasted screen space that forces the user to do unnecessary scrolling. The Tight theme tightens up some of that spacing to make it easier for the admin to navigate.

**Admin nav** – The spacing on the admin nav columns has been tightened up. If subnav has with many columns it will be more easierto see them without
scrolling sideways.

**Feature or pull requests** are welcome, please open a pull request.

### Installation
Download a zip file of the codebase and manually move the code to the folders. In the future there may be a composer install available.

Register the theme by these steps:

```
rm -rf pub/static/adminhtml/*
rm -rf var/view_preprocessed/*
bin/magento cache:clean
bin/magento setup:upgrade
bin/magento setup:static-content:deploy -f -a adminhtml
```

### Documentation

**Magento admin theme development links**

Here are some helpful links if you are interested in modifying or extending this theme.

[Magento Dev Docs: Create an Admin theme](https://devdocs.magento.com/guides/v2.4/frontend-dev-guide/themes/admin_theme_create.html)

[Magento Dev Docs: Apply an Admin theme](https://devdocs.magento.com/guides/v2.4/frontend-dev-guide/themes/admin_theme_apply.html)
