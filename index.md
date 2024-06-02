---
title: Welcome to my blog
---

Hello **World**!

<!---
https://jekyllrb.com/docs/posts/#displaying-an-index-of-posts
--->

Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.url }}/{{ post.url }}">{{ post.title }}</a>
      <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
