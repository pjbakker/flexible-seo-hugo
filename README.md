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
* Easily switching navigation, header and footer templates
* SEO friendly list pages (No auto-generated lists!)
* Auto generated breadcrumbs (both visible and structured data)

## Switching navigation, header or footer

Within your `config.toml` add the according parameter you want the theme to use. By default, the theme uses 'simples' for navigation, header and footer.

~~~
[Params]
  nav = "simple"
  header = "simple"
  footer = "simple"
~~~

The theme will look for the theme parts in *layouts/partials/navs/*, *layouts/partials/headers/*, and *layouts/partials/footers/* accordingly. For instance, with `nav = "simple"`, it will look for *layouts/partials/navs/simple.html*.

### Supported footer styles

The following footer styles are included:

* `simple`, just a copyright statement and the option to have a limited number of links in the footer. Links are taken from .Params.footerLinks.
* `bar_with_2_columns`, a gray bar at the bottom with two columns (left aligned and right aligned). Links are taken from .Params.footerLinksColumn1 and .Params.footerLinksColumn2.

## Breadcrumbs

By default a breadcrumb bar is shown at the top of each page other than Home. You can disable showing the breadcrumb bar at a site or page level by setting `showBreadcrumbs` to `false`.

## Enabling Analytics

Assuming you already signed up for [Google Analytics](https://www.google.com/analytics/), you can add your Google Tracking ID to the `googleAnalytics` parameter in `config.toml`. It will then automatically include Google Analytics code in your site.

## License

MIT Licensed, see [LICENSE](https://github.com/pjbakker/flexible-seo-hugo/blob/master/LICENSE).
