---
widget: blank
headless: true
active: true

# ... Put Your Section Options Here (title etc.) ...
title: Recent News
subtitle: Link to more news here
weight: 10  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '2'
---

{{< readfromfile "/content/newslist.dat" 5 >}} 
