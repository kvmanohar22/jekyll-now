---
layout: default
---

<div class="posts">
    <h1>
    <a href="https://kvmanohar22.github.io/ins_init">INS initialization</a>
    </h1> 
    <div class="date">
         25 December 2020
    </div>

    <h1>
    <a href="https://kvmanohar22.github.io/controls">Linear Controls</a>
    </h1> 
    <div class="date">
         11 November 2019
    </div>

    {% for post in site.posts %}
    <article class="post">
        <h1>
            <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h1>
        <div class="date">
            {{ post.date | date_to_long_string }}
        </div>
    </article>
    {% endfor %}

</div>
