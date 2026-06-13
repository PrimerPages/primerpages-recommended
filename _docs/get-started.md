---
title: "Get started"
order: 1
image: "https://raw.githubusercontent.com/PrimerPages/jekyll-theme-primerpages/main/screenshot.png"
---

This theme is based on GitHub's primer style. It supports both light and dark modes, and four style options: appbar, sidebar, stacked, and topbar.

![jekyll-theme-primerpages](https://raw.githubusercontent.com/PrimerPages/jekyll-theme-primerpages/main/screenshot.png)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-primerpages"
```

And then execute:

```shell
bundle install
```

Or install it yourself as:

```shell
gem install jekyll-theme-primerpages
```

## Configuration

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-primerpages
style: topbar # One of "stacked", "sidebar", "topbar", "appbar"
repository: PrimerPages/jekyll-theme-primerpages # for repository info to be included
repo_info: true # Show the information for the source of this project
user_metadata: true # Show the metadata associated with the user
profile_link: true # Show a link to the github profile for the user
```

## Building

Build the site and make it available on a local server

```shell
bundle exec jekyll serve
```
