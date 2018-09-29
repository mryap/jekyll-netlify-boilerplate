---
layout: post
title:  "Troubleshooting Jekyll page"
date: '2018-07-06 12:00:00'
---

If your website are unable to reflect the new changes to your website content, check it out under Netlify's  Deploy Log. It might display error message "does not have a valid date in the YAML front matter", 

To rectify the error, I  learn there a need to include `exclude: [vendor]` in  `_config.yml`  as [suggested on GitHub](https://github.com/jekyll/jekyll/issues/2938) 