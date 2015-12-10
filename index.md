---
layout: page
title: 欢迎来到UrbanDream！
tagline: 神秘盒子带来美妙的惊喜
---
{% include JB/setup %}

## 我们上线了！

网站现在刚刚上线，请稍等。我们会立马把内容搬上来的！

-俞逸尧，UrbanDream技术支持

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
