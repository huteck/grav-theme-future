# v1.0.5
## 04/17/2023

1.  [](#bugfix)
    * Fixed raw filter in several templates.
    * Fixed pagination in blog
2.  [](#improved)
    * Updated translations.
    * Updated css styles.
    * Improved author styles in blog items.
3.  [](#new)
    * Added support for Owl Carousel plugin
    * Added support for Reading time plugin in blog
    * Added option to enable or disable primary image in pages

# v1.0.4
## 02/27/2023

1.  [](#bugfix)
    * Fixed Spanish translation for custom menu items.
    * Fixed support for the twig-extensions plugin in blog posts.
    * Fixed issues with login [#27](https://github.com/pmoreno-rodriguez/grav-theme-future2021/issues/27)
2.  [](#improved)
    * Updated translations.
    * Updated css styles.
    * Optimized js loading for sidebar menu.
    * Improved loading of FontAwesome styles with the `preload` option
    * Improved `aria-label` attribute in all templates
3.  [](#new)
    * New styles for login forms.
    * New option to show icons in the top menu.
    * Added option on blog posts to choose to share on social media. (thanks to [b.da](https://discourse.getgrav.org/u/b.da))
    * Added body classes to default template.
    * Added option to show custom menu items.
    * New options in portofolio template.
    * Added OpenGraph metadata
    * Added `decoding=async` option for all images.
    * Added quick README instructions for configuring Future2021
# v1.0.3
## 02/08/2023

1.  [](#bugfix)
    * Fixed logo display when only mobile logo is chosen.
    * Fixed bug in simplesearch item (added `striptags` filter in page.summary)[#26](https://github.com/pmoreno-rodriguez/grav-theme-future2021/issues/26).
    * Fixed demo content removing .es prefix [#1](https://github.com/pmoreno-rodriguez/grav-theme-future2021/issues/1).
    * Fixed search results image with `|raw` filter.
    * Fixed display of svg in search results.
2.  [](#improved)
    * Autoformatted some twigs (thanks to [@pikim](https://github.com/pikim)).
    * Improved the definition of variables in twig templates.
    * Minimal options in future2021.yaml file.
    * Added German translation (thanks to [@pikim](https://github.com/pikim)).
    * Renamed custom.css to misc.css.
    * Update author and avatar variables in blog.
3.  [](#new)
    * Added filter by URI on results page by taxonomy.
    * Added support for translate-date (thanks to [@pikim](https://github.com/pikim)) and twig-extensions plugins.
    * Allow disabling sidebar in all pages.
    * Added support to Login Form
# v1.0.2
## 11/08/2022

1.  [](#bugfix)
    * Fixed code in sidebar_navigation.html.twig and topmenu.html.twig
    * Fixed code to choose columns number in portfolio and features templates.
2.  [](#improved)
    * Updated header.class to header.layout in several blueprints
    * Updated CSS and SCSS assets
    * Updated languages.yaml
    * Improved several templates to include subtitle and primary image.
3.  [](#new)
    * Added centered alignment for images in portfolio template.
    * Added option in theme to choose the miniposts category name.
    * New logo twig template
# v1.0.1
## 02/05/2022

1.  [](#bugfix)
    * Updated CSS Styles to show FontAwesome 5

# v1.0.0
## 02/04/2022

1.  [](#new)
    * Drop down menu functionality
    * Fixed autoescaping in all twig templates
    * Added slidedown functionality for sidebar menu with JQuery
    * Full translation English and Spanish for administration and frontend
    * Added Back-to-Top button
    * Added Offline template
    * Added option to choose the number of miniposts will be showed in sidebar (in Theme options)
    * Added the order option in the blog item to order the miniposts as you want
    * Add shadown to header
    * Added avatarImage and subtitle options in blueprints