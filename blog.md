---
layout: offerings
title: Blog
subTitle:
---

{% t blog.intro %}

<!-- Page Content Individuals-->
  <div class="content-section-b">
      <div class="container">

        {% for post in site.categories.blog %}
                    <div class="row">
                       {% if post.img %}
                        <div class="col-lg-8 col-sm-8">
                      {% else %}
                        <div class="col-lg-12 col-sm-12">
                      {% endif %}

                            <h3 class="section-heading">{{ post.title }}</h3>
                            Tags: <span style="text-transform:uppercase">{{post.tag | join: " & " | prepend: "" | append: ""}}</span>
                            <div class="lead">
                            {% if post.description %}
                            {{ post.description }}<br>
                            {% else %}
                            {{ post.excerpt }}
                            {% endif %}
                            <a href="{{ site.baseurl }}{{ post.url }}">{% t mehrlink %}</a>
                            </div>
                        </div>
                        {% if post.img %}
                        <div class="col-lg-3 col-lg-offset-1 col-sm-3">
                            <img class="img-responsive thumbnail" alt="{{ post.title }}" src="{{ post.img }}" onerror="this.src='{{post.img | replace: "webp", "jpg" }}'">
                        </div>
                        {% endif %}
                    </div>
                    <br>
          {% endfor %}


      </div>
  </div>
