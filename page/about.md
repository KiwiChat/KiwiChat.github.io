---
layout: default
title: About
nav_order: 4
---

# Configuration

You can reference multiple collections.
This creates categories in the navigation with the configured names.
```yaml
collections:
  docs:
    permalink: "/:collection/:path/"
    output: true
  tutorials:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  collections:
    docs:
      name: Documentation
    tutorials:
      name: Tutorials
```
