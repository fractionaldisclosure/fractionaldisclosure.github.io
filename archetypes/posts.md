---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true
authors:
  - "author1"
  - "author2"
  - "author3"
attachments:
  - image: "/bipartite.png"
    margin: "256px"
---

This is the first paragraph. It's quite a good paragraph. To adjust gaps between attachments, specify the margins in the Hugo template file. Don't forget to edit authors, title, and date as well.

<p style="margin-top:14em">&hellip;And this is a paragraph with an attachment next to it.</p>
