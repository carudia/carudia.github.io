---
permalink: /CentOS7/
title: "CentOS7"
layout: archive
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.CentOS7 %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
