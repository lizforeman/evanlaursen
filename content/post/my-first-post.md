---
title: "Hello world, I'm Evan"
date: 2019-11-07T07:13:19+01:00
draft: false
tags: ["first post"]
categories: ["evan", "age4", "Halloween"]
---

And this is my website. 

I'm a huge fan of Legos, both Duplo and small. The 11th Doctor (Doctor Who) is my favorite and my Halloween costume this year.

![Me as the 11th Doctor](https://live.staticflickr.com/65535/49013608491_7c2abcb564_b.jpg)

{{range .Site.Data.netflix.json}}
{{.show}}<br>{{.date}}
{{end}}

{{range .Data.netflix.json}}
{{.show}}<br>{{.date}}
{{end}}

{{range Data.netflix}}
{{.show}}<br>{{.date}}
{{end}}
