---
title: "Flexible SEO Hugo theme"
page_title: "Flexible SEO-friendly Hugo theme"
subtitle: "Makes life easier"
---

## Flexible SEO Hugo theme

flexible-seo-hugo is a Bootstrap 4 based theme built for Hugo. The design is thus based on Hugo. And the main strength is the flexilibity of switching between different headers, footers and navigation bars, and the inclusion of structured data for SEO purposes. For documentation and the full feature list, check out the [README](https://github.com/pjbakker/flexible-seo-hugo/blob/master/README.md).

## Installation

This theme requires Hugo. If you don't already have Hugo on your system, follow the [official installation instructions](https://gohugo.io/getting-started/installing/).

### Create a new Hugo site

If you don't already have one, create a new site structure with `hugo`:

{{< highlight bash >}}
$ hugo new site MY_SITE_NAME
{{< /highlight >}}

Hugo will create a fresh hugo structure in *MY_SITE_NAME*.

### Set-up theme

Copy or use git to add this theme to the themes folder `MY_SITE_NAME/themes`

#### Install with Git submodule

If you already use git for your site, as a git submodule.

{{< highlight bash >}}
$ cd MY_SITE_NAME
$ git submodule add https://github.com/pjbakker/flexible-seo-hugo.git themes/flexible-seo-hugo
{{< /highlight >}}

#### Install with Git clone

Otherwise you can add the theme with `git clone`.

{{< highlight bash >}}
$ cd MY_SITE_NAME
$ git clone https://github.com/pjbakker/flexible-seo-hugo.git themes/flexible-seo-hugo
{{< /highlight >}}

### Add example content

If you don't want to start from scratch, you can copy our example site and build from there.

If you are on Mac OS, or Linux, you can copy the entire contents of our exampleSite, like this:

{{< highlight bash >}}
$ cd MY_SITE_NAME
$ cp -a themes/flexible-seo-hugo/exampleSite/. .
{{< /highlight >}}

### Configuration

If you start with our example site, you will need to adjust at least the `baseURL` value in `MY_SITE_NAME/config.toml`

{{< highlight toml >}}
baseURL = "/"
{{< /highlight >}}

### Viewing the site

With hugo it's easy to view the live site without a webserver by running `hugo server`.

You have to run this command from the root folder of your site.

{{< highlight bash >}}
$ cd MY_SITE_NAME
$ hugo server
{{< /highlight >}}

You can now go to [`localhost:1313`](http://localhost:1313) in your browser to view the site and see all changes happen as you save them

## License

This theme is licensed under the [MIT LICENSE](https://github.com/pjbakker/flexible-seo-hugo/blob/master/LICENSE). If you fork or copy this theme, you must keep the LICENSE file and the copyright notice on line 3 (where I am listed as the author). You cannot just replace the copyright line with your own name. Attribution in your README.md or on your site is also welcome but not required.
