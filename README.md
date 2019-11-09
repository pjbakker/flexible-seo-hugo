# Flexible SEO Hugo - A flexible configurable SEO-minded theme

![Flexible SEO Hugo Theme Screenshot](https://github.com/pjbakker/flexible-seo-hugo/blob/master/images/screenshot.png)

## Installation

    $ mkdir themes
    $ git submodule add https://github.com/pjbakker/flexible-seo-hugo.git themes/flexible-seo-hugo

## About

This theme has been built upon Bootstrap 4. It allows you to easily switch between different Navigation bars, Page Headers and Footers using configuration. And of course you can add your own as well.

All core pages have been optimized for SEO-friendliness.

Of course there is also support for:

* Google Analytics

## Switching navigation, header or footer

Within your `config.toml` add the according parameter you want the theme to use. By default, the theme uses 'simples' for navigation, header and footer.

~~~
[Params]
  nav = "simple"
  header = "simple"
  footer = "simple"
~~~

The theme will look for the theme parts in *layouts/partials/navs/*, *layouts/partials/headers/*, and *layouts/partials/footers/* accordingly. For instance, with `nav = "simple"`, it will look for *layouts/partials/navs/simple.html*.

## Enabling Analytics

Assuming you already signed up for [Google Analytics](https://www.google.com/analytics/), you can add your Google Tracking ID to the `googleAnalytics` parameter in `config.toml`. It will then automatically include Google Analytics code in your site.

## License

MIT Licensed, see [LICENSE](https://github.com/pjbakker/flexible-seo-hugo/blob/master/LICENSE).
