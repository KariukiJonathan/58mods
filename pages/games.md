---
layout: page
title: Games by 58Mods
permalink: "/games/"
image: ../assets/images/screenshot.png
---

<section class="row">
        {% for post in site.posts %}
            {% if post.featured == true %}
                <div class="col-md-4 mb-5">
                {% include postbox.html %}
                </div>
            {% endif %}
        {% endfor %}
  </div>
</section>
