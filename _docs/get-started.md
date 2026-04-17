---
title: "Get started"
order: 1
image: "https://raw.githubusercontent.com/PrimerPages/jekyll-theme-profile/main/screenshot.png"
---

This theme is based on GitHub's primer style. It supports both light and dark modes, and four style options: appbar, sidebar, stacked, and topbar.

![jekyll-theme-profile](https://raw.githubusercontent.com/PrimerPages/jekyll-theme-profile/main/screenshot.png)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-profile"
```

And then execute:

```shell
bundle install
```

Or install it yourself as:

```shell
gem install jekyll-theme-profile
```

## Configuration

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-profile
style: topbar # One of "stacked", "sidebar", "topbar", "appbar"
repository: PrimerPages/jekyll-theme-profile # for repository info to be included
repo_info: true # Show the information for the source of this project
user_metadata: true # Show the metadata associated with the user
profile_link: true # Show a link to the github profile for the user
```

## Building

Build the site and make it available on a local server

```shell
bundle exec jekyll serve
```
