---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# About Me
My name is Yaxin Zheng, an undergraduate student in Finance at Australian National University. My research interests include:

- **Empirical Asset Pricing**, Factor Models, and Financial Econometrics  
- **Credit Risk**, Corporate Bonds, and Financial Intermediation  
- **Macro-Finance**, Monetary Policy Transmission, and Machine Learning Forecasting
