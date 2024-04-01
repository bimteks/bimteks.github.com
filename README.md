---
permalink: /index.html
title: Home 😢
robots: noindex
sitemap: false
description: This is the homepage.
reload: true
---



<div class="alert alert-primary lead text-center" role="alert">
  The page you are trying to view does not exist. <br />
  <strong>Perhaps you're looking for <span id="four-oh-four-suggestion"></span>?</strong>
</div>



#### Recent posts

<!-- markdownlint-disable MD032 -->

{% for post in site.posts limit: 10 %}

* [{{ post.title }}]({{ post.url }}) {%- endfor -%}

<!-- markdownlint-enable MD032 -->
