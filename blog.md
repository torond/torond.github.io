---
layout: page
title: "Blog"
permalink: /blog
---
Hey there!
When I cycled to Ireland from July to September 2022 I kept a blog in a Telegram channel.
This is a mirror of that channel for people who don't have access to Telegram.
Stay awesome! :)
David

---

{% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <!--<time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>-->
    {{ post.content }}
    <hr />
  </article>
{% endfor %}
