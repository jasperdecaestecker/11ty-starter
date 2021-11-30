---
title: Auto build pagination
layout: "post.njk"
date: Last Modified
tags: 
    - post
---

# Auto build pagination

Pagination is automatically added. Using tags in posts can make collections of content that then can be looped over

1. add tag to post
```
tags: 
    - post
```
2. add pagination info to page where pagination is needed
```
pagination:
  data: collections.post
  size: 2
  alias: posts
  reverse: true
```
3. loop through collection in template
```
{%- for post in posts -%}
any html here
{%- endfor -%}
```

More options and info can be found here
https://www.11ty.dev/docs/pagination/

