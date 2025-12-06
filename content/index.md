---
title: Welcome to Quartz
---

This is a blank Quartz installation.
See the [documentation](https://quartz.jzhao.xyz) for how to get started.


```base
filters:
  and:
    - file.inFolder("content/published content")
views:
  - type: table
    name: Table
    order:
      - file.name
      - title

```