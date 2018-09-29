---
layout: post
title:  "Troubleshooting Jekyll page"
date: '2018-07-06 12:00:00'
---

I learn that using netlify helps you to identity the cause if your website unbale to update due to "does not have a valid date in the YAML front matter"

I also need to include `exclude: [vendor]` in my `_config.yml`  as [suggested on GitHub](https://github.com/jekyll/jekyll/issues/2938) 