---
slug: book
title: Demo Book
abstract: An example book for showcasing the Jekyll Chapterbook theme.
---

{% include copyright-vars.html %}

{% if copyright_link or author_link -%}
  {{ author_link }} {{ copyright_link }}
{%- endif %}

Last updated: {{ "now" | date: "%B %e, %Y" }}

{% if site.baseurl_canonical %}
  The latest version of this book can always be found at  
  <a href="{{site.baseurl_canonical}}{{page.url}}">{{site.baseurl_canonical}}{{page.url}}</a>.
{% endif %}
