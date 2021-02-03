---
layout: page
title: OFFENSIVE
published: true
---
                                
<a href="{{ site.baseurl }}/2021-01-30-OSINT.md">OSINT</a><br>
<a href="{{ site.baseurl }}/_posts/2021-01-30-OSINT.md">OSINT</a><br>
<a href="{{ site.baseurl }}/0ffSecVault.github.io/_posts/2021-01-30-OSINT.md">OSINT</a><br>

<a href="{{ site.baseurl }}{{ post.url }}/_posts/2021-01-30-OSINT.md">OSINT</a>

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>