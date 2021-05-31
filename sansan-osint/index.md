---
title: Sansan-OSINT
layout: page
---

All about infosec related stuff at our _"prestigious"_ university: Universidad Técnica Federico Santa María.

From ownages and defacements of local servers that haven't been disclosed or breaches that remain in the dark to insecure configs that **shouldn't** exist in the first place somewhere at our campus,
this is your place for info about events happening at our uni that aren't being properly reported nor covered.

_(currently accepting submissions and tips for future research)_

<br/>

{% assign filt_posts = site.posts | where: "categories","sansan-osint" %}
{% include display_posts.html site_posts=filt_posts %}
