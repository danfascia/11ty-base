# 11ty base

This is an unstyled starter for [Eleventy](https://11ty.dev) which implements a lot of technical good practices but imposes no opinions on the CSS or JS build chains. It aims to offer a good folder structure and baseline build to start a project from.

It has the following feature set

* [Eleventy Navigation](https://github.com/11ty/eleventy-navigation) plugin module included
* .env file support to change build environment locally
* Good baseline SEO headers (meta tags, schema.org, twitter cards, facebook openGraph)
* Global `site.json` data file for sitewide defaults and parameters
* `<body class="home $bodyClass">` implementation
* Eleventy Config defaults
  - Default layout alias for `base.njk` master template
  - A well formatted readable date filter
  - Conditional HTML minification for `NODE_ENV='production'` environment

Please feel free to fork and mutate / improve.

[Daniel Fascia](https://twitter.com/danfascia)