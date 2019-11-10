---
layout: default
---

<div class="posts">
    <h1>
    <a href="https://kvmanohar22.github.io/controls">Linear Controls</a>
    </h1> 
    <div class="date">
         11 Nov 2019
    </div>

    {% for post in site.posts %}
    <article class="post">
        <h1>
            <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} </a>
            <!-- <p align="center"><img width="30%" height="30%" src="{{ post.image }}"/></p> -->
            <!-- ![img]({{ post.image }}) -->
            <!-- <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} </a> -->
            <!-- <img src= "{{ post.image }}" height="20%" width="20%"> -->
        </h1>
        <div class="date">
            {{ post.date | date_to_long_string }}
        </div>
            <!-- <div class="fig figcenter fighighlight"> -->
        <!-- </div> -->
    </article>
    {% endfor %}
</div>
