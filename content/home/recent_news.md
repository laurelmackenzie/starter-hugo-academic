---
widget: blank
headless: true
active: true

# ... Put Your Section Options Here (title etc.) ...
title: Recent news
subtitle: "[See all](/news)"
weight: 10  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '2'
---

{{< readfromfile "/content/newslist.dat" 5 >}} 
