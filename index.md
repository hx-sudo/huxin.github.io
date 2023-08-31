**Hello, this is my site.**

---
layout: home
title: Welcome to My Blog!
---

## About Me

123

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Connect with Me

You can find me on [GitHub](https://github.com/hx-sudo) and [Google Scholar](https://scholar.google.com/citations?user=123). Feel free to reach out if you have any questions or collaboration opportunities!
