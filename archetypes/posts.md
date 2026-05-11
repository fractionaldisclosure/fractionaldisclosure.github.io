---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: false
authors:
  - "author1"
  - "author2"
  - "author3"
---

This is the first paragraph. It is quite a good paragraph. 
{{< sidenote image="/bipartite.png" caption="A cool chart" >}}
And this is the next paragraph...
