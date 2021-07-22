---
layout: default
title: Home
nav_order: 1
description: "KiwiChat NextClient WordPress Plugin."
permalink: /
---

# KiwiChat NextClient WordPress plugin
{: .fs-9 }

Try the new IRC KiwiChat WordPress plugin that works! based on kiwiirc nexclient, with 6 new themes

KiwiChat is an online chat client, your IRC client based on kiwiirc Add your networks. Join your channels.
{: .fs-6 .fw-300 }

[[View it on GitHub](https://github.com/KiwiChat/wp-kiwichat){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on WordPress](https://wordpress.org/plugins/kiwichat/){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Description

How to use KiwiChat…
Finally there is an IRC plugin for WordPress that works!
KiwiChat is an online chat client, your IRC client based on kiwiirc Add your networks. Join your channels.
To use this plugin:
1. simply download and extract it into your plugins folder
2. configure your settings in the WordPress dashboard
3. then drop the short tag ```[kiwichat]``` into your page or post.
Instantly your users will be able to stay connected via IRC.

## Installation

1. Upload the "kiwichat" folder to the "/wp-content/plugins/" directory.
1. Activate the plugin through the "Plugins" menu in WordPress.
1. Place "[kiwichat]" shortcode in your pages or posts.

## Download

[![alt text][image]][hyperlink]

  [hyperlink]: https://wordpress.org/plugins/kiwichat/
  [image]: https://kiwichat.github.io/kiwichat-300x150.png
  
  
  ## Screenshots

![Plugin configuration](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-1.png "Plugin configuration options page")

![Capture KiwiChat Home Screen](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-2.png "Capture KiwiChat Home Screen")

![Capture KiwiChat Online Chat](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-3.png "Capture KiwiChat Online Chat")

![KiwiChat Connected In Chat](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-4.png "KiwiChat Connected In Chat")
  
  
3. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2019-{{ "now" | date: "%Y" }} by [BaiatRau](http://showchat.tk).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/KiwiChat/KiwiChat#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
