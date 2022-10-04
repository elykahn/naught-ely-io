# 🪐naught_ely_io

A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://getnaught-ely-io.com](https://getnaught-ely-io.com)!

## What is naught_ely_io?

### For new users

_naught_ely_io_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. naught_ely_io makes it easy to "get up to zero" and start building your site.

### For experienced developers

_naught_ely_io_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _naught_ely_io_ as your Jamstack starter:

* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the naught_ely_io name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/elykahn/naught_ely_io/blob/master/README.naught_ely_io.md) to help you take the next steps and launch your project!
* Sass for CSS
* Javascript compilation and minification
* Browsersync to preview your work

## Get started: Use This Template

Get started with naught_ely_io one of the following ways:

<details open>
 <summary>Start with GitHub</summary>

Create a new project using naught_ely_io and add it to your GitHub account

<a href="https://github.com/elykahn/naught_ely_io/generate">
  <img src="https://img.shields.io/badge/use%20this-template-blueviolet?logo=github&style=for-the-badge">
</a>
 </details>

<details open>
 <summary>Start with Netlify</summary>

Create a copy of naught_ely_io and deploy it straight to [Netlify](https://netlify.com) for **free**!

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/elykahn/naught_ely_io/)

 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

Get started from your command line

 ```sh
  gh repo create example.com --template elykahn/naught_ely_io
 ```

</details>

## Get to Know naught_ely_io

Ready to go deeper? Here's how naught_ely_io is laid out:

```sh
example.com                 # → Root of your naught_ely_io-based project
├── src/                    # → Source directory
│   ├── assets/             # → Site assets
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── scripts/
│   │   ├── styles/
│   │   ├── views/
│   │   │   └── layouts/
│   │   │   └── partials/
│   │   └── assets.json     # → Shared attributes for files in the assets directory
│   ├── config/             # → Eleventy configuration
│   │   ├── collections.js  # → Add and configure collections (https://www.11ty.dev/docs/collections/)
│   │   ├── filters.js      # → Add and configure filters (https://www.11ty.dev/docs/filters/)
│   │   ├── passthroughs.js # → Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
│   │   ├── plugins.js      # → Add and configure plugins (https://www.11ty.dev/docs/plugins/)
│   │   ├── shortcodes.js   # → Add and configure shortcodes (https://www.11ty.dev/docs/shortcodes/)
│   │   ├── templateLanguages.js   # → Configure custom template languages (HINT: this is where naught_ely_io's Sass and Javascript pipelines are set up!) (https://www.11ty.dev/docs/languages/custom/)
│   │   ├── watchtargets.js # → Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
│   │   └── config.json     # → Shared attributes for files in the config directory
│   ├── content             # → A nice, organized, recommended place for all site content
│   │   └── pages           # → Add "pages" collection items here
│   └── data                # → Customize site data (https://www.11ty.dev/docs/data/)
│       ├── navigation.json # → Site navigation configuration
│       └── site.json       # → Site branding configuration
├── .eleventy.js            # → Core Eleventy config file
├── netlify.toml            # → Netlify deployment and plugin configuration (optional)
├── README.template.md      # → naught_ely_io readme
└── README.md               # → Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration

Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.

## Install project dependencies

```bash
npm i
```

## Run the project locally

```bash
npm run dev
```

## Build for staging

(The same as production except every page is flagged `noindex`)

```bash
npm run staging
```

## Build for production

```bash
npm run production
```
