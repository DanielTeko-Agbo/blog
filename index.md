---
layout: home
title: Home
---

#### The meaning of a few things:

```python

import requests

res = requests.get("https://letsgo.com/here")
res.status_code

```
Number of posts: {% raw %}{{ site.posts.size }}{% endraw %}
- Current page URL: {% raw %}{{ page.url }}{% endraw %}

{% raw %}{% for post in site.posts %}
  {{ post.title }}
{% endfor %}{% endraw %}