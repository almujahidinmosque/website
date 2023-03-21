---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
# page title background image
bg_image: "images/blog/{{ .Name }}.png"
# meta description
description: "This is meta description"
# post thumbnail
image: "images/blog/{{ .Name }}.png"
# post author
author: "Takmir Al-Mujahidin"
categories:
    - masjid
tags:
    - artikel
# type
type: "post"
---
