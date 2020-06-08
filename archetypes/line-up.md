---
title: "{{ lower .Name }}"
categories: []
tags: []
promoted: 0
banner: images/artists/{{ replace .Name "-" " " | lower }}/banner.jpg
draft: false
gallery: {{ lower .Name }}
social:
  - icon : "ion-social-facebook-outline"
    link : "#"
  - icon : "ion-social-twitter-outline"
    link : "#"
---

# Biography
---

**{{ replace .Name "-" " " | title }}**
