---
title : "클라우드 기초"
layout : archive
permalink : categories/CloudBasic
author_profile : true
sidebar_main : true
---

{% assign posts = site.categories.CloudBasic %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}