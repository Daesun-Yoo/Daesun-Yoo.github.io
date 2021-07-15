---
title : "AI 기초"
layout : archive
permalink : categories/AIBasic
author_profile : true
sidebar_main : true
---

{% assign posts = site.categories.AIBasic %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}