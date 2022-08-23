---
layout: page
title: "Blog"
permalink: /blog
---

Hey there! Thanks for checking out my blog. Currently, this is a simple mirror of a Telegram channel documenting my cycling tour from Leipzig, Germany to Cork, Ireland. Currently, I haven't implemented any type of image galleries so posts can be quite long. I'll change that some time down the road.
Also, I'll be updating this page whenever I have access to a desktop computer, so the next update will be some time after I have arrived in Cork.
In the meantime, check out the Telegram channel for frequent updates: [https://t.me/+5E1wU-ja1r4wNTMy](https://t.me/+5E1wU-ja1r4wNTMy)

Stay awesome! :)
David

{% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <!--<time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>-->
    {{ post.content }}
  </article>
{% endfor %}
