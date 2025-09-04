---
layout: page
title: Games
permalink: "/games/"
image: assets/images/screenshot.png
---

58Mods has developed afew games that you can play.
The theme is compatible with Github pages. This demo is created with Github Pages and hosted with Github.

<section class="row">
    <div>
        {% for post in site.posts %}
            {% if post.featured == true %}
                <div class="col-md-4 mb-5">
                {% include postbox.html %}
                </div>
            {% endif %}
        {% endfor %}
  </div>
</section>
