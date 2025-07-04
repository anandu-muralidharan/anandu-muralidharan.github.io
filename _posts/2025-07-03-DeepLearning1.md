---
layout: post
title: DeepLearning-1
date: 2025-07-03 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
categories: sample-posts
giscus_comments: true
related_posts: false
---

This is the first post in the series where i will be triying to recreate the mini-projects given in fast.ai website

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/DeepLearning1.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/DeepLearning1.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

Note that the jupyter notebook supports both light and dark themes.
