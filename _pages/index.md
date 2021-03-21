---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Sean's home!
---

## Post

머신러닝을 알아가면서 벌어지는 이야기들
## Projects

머신러닝을 공부한 흔적들

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


