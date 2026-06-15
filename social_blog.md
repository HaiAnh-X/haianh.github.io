---
layout: post
title: "Blog"
---
<ul class="post-list" style="list-style: none; padding-left: 0;">
  {% for post in site.posts %}
    {% if post.categories contains 'social' %}
      <li style="margin-bottom: 30px; border-bottom: 1px solid #eee; padding-bottom: 20px;">
        
        <span class="post-meta" style="font-size: 10pt; color: #888; display: block; margin-bottom: 5px;">
          {{ post.date | date: "%b %-d, %Y" }}
        </span>
        
        <h3 style="margin-top: 0; font-size: 16pt; margin-bottom: 10px;">
          <a class="post-link" href="{{ post.url | relative_url }}" style="color: #111; text-decoration: none; font-weight: 600;">
            {{ post.title }}
          </a>
        </h3>
        
        <div class="post-excerpt" style="font-size: 11pt; color: #555; line-height: 1.6;">
          {{ post.excerpt | strip_html | truncatewords: 40 }}
        </div>
        
      </li>
    {% endif %}
  {% empty %}
    <li><em style="color: #888;">Chưa có bài viết nào trong danh mục này.</em></li>
  {% endfor %}
</ul>
