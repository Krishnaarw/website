---
layout: default
title: Articles
css-file: posts.css
---

<section class='all-posts'>
        <h1>All posts</h1>
        <div class="posts">
            {% for post in site.posts %}
                <a href='{{ post.url }}' class="post">
                    <h2 class="title">{{ post.title }}</h2>
                    <p class="preview">{{ post.excerpt }}</p>
                </a>
            {% endfor %}
        </div>
    </section>
