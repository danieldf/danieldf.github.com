---
layout: page
title: Daniel Ferrante
tagline: Free Science 2.0
---
{% include JB/setup %}

My name is Daniel Doro Ferrante... testing MathJax: \\( a\, x^2 + b\, x + c = 0 \\) .

And, some more: $$ \mathscr{Z}(J) = \int_{\mathcal{C}} e^{i\, S(\varphi)}\, e^{i\, J\, \varphi}\, \mathcal{D}\varphi = \mathrm{Tr}(e^{i\, S})\;. $$

<!--
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Surname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
-->
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
