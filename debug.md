---
layout: page
title: Debug
---

## Jekyll version

<pre>{{ jekyll.version }}</pre>

## Jekyll environment

<pre>{{ jekyll.environment }}</pre>

## Site Variables

<pre>{{ site | inspect }}</pre>

## Page Variables

<pre>{{ page | inspect }}</pre>

{% if paginator %}
## Paginator Variables

<pre>{{ paginator | inspect }}</pre>
{% endif %}
