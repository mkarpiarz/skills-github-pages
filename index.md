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
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
