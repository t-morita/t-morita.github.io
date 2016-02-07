---
layout: ja_page
ja_title: ニュース
permalink: /ja/news/
---

<ul>
{% for post in site.posts %}
    <li>
        {{ post.date | date_to_string }} : <a href="{{ post.url }}">{{ post.ja_title }} </a>
    </li>
{% endfor %}
</ul>