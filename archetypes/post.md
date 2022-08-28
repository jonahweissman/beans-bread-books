---
title: "{{ replace .Name "-" " " | title }}"
date: {{ time (getenv "HUGO_DATE") (getenv "HUGO_TZ")  }}
type: post
---

