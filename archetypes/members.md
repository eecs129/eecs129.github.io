---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: "members"
layout: "member"
resources:
    - src: photo.jpg
      params:
          weight: -100
draft: true
---

