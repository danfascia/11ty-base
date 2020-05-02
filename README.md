# 🚀 11ty base

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

## Getting Started

Clone or fork repository then install relevant node_modules using yarn or NPM

```
yarn
```

### Dev mode
To run a local development server based on 11ty's built in `--serve` parameter
```
yarn dev
```
To build to production set `NODE_ENV=production` in your `.env` file (hint: you'll need to create one in your project root)
```
yarn build
```
Build will not run a local server but will minify the HTML in the `dist` folder ready for deployment

Deploy the `dist` folder to a host of choice.

[Daniel Fascia](https://twitter.com/danfascia)