---
layout: emptypage
title: nav.kompetenzen.business
subTitle: kompetenzen.business.subTitle
---

<div class="content-section-a">
  <div class="container">
    <div class="row">
      <div class="col-lg-12">
        <div class="lead">
        {% t kompetenzen.business.text %}
        </div>
        <div class="lead">
        {% t kompetenzen.business.ziele.text %}
        </div>

        <br>
        <div class="container lead">
          <div class="row">

          <div class="col-sm-3 col-md-3">
          <center>
          <i class="fa-solid {% t kompetenzen.business.ziele.ziel1fab %} fa-2xl"></i><br>
          <p style="margin-top: 0.25em;">{% t kompetenzen.business.ziele.ziel1 %}</p>
          </center>
          </div>

          <div class="col-sm-3 col-md-3">
          <center>
          <i class="fa-solid {% t kompetenzen.business.ziele.ziel2fab %} fa-2xl"></i>
          <p style="margin-top: 0.25em;">{% t kompetenzen.business.ziele.ziel2 %}</p>
          </center>
          </div>

          <div class="col-sm-3 col-md-3">
          <center>
          <i class="fa-solid {% t kompetenzen.business.ziele.ziel3fab %} fa-2xl"></i>
          <p style="margin-top: 0.25em;">{% t kompetenzen.business.ziele.ziel3 %}</p>
          </center>
          </div>

          <div class="col-sm-3 col-md-3">
          <center>
          <i class="fa-solid {% t kompetenzen.business.ziele.ziel4fab %} fa-2xl"></i><br>
          <p style="margin-top: 0.25em;">{% t kompetenzen.business.ziele.ziel4 %}</p>
          </center>
          </div>          

                </div>
          </div>

      </div>
    </div>
  </div>
</div>


<section id="angebote">
  	<div class="banner">
  		<div class="container">
  			<div class="row">
  				<div class="col-lg-12">
  					<h2>{% t nav.angebot %} {% t nav.kompetenzen.business %}</h2>
  				</div>
  			</div>
  		</div>
  	</div>
</section>

<div class="content-section-a">
<div class="container">
  <div class="row">
    {% for post in site.categories.Services-Firma %}
                <div class="col-sm-4 col-md-4">
                  <div class="thumbnail">
                    <img src="/img/services/{{ post.img }}" alt="{{ post.title }}" onerror="this.src='/img/services/{{post.img | replace: "webp", "jpg" }}'">
                    <div class="caption lead">
                      <h3><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title_kurz %}{{ post.title_kurz }}
                        {% else %}
                        {{ post.title }}
                        {% endif %}</a></h3>
                      <p>{{ post.description }}</p>
                      <p>{{ post.angebot }}</p>
                      <p><b>{{ post.preis }}</b></p>
                      <p>{% if post.digistore24 %}
                        <a href="{{post.digistore24}}" class="btn btn-primary" role="button">Jetzt buchen - Digistore24</a>
                          {% else %}
                        <a href="mailto:{{ site.email }}?subject={{post.anfrage}}" class="btn btn-primary" role="button">{% t JetztBuchen %}</a>
                        {% endif %}
                        <a href="{{ site.baseurl }}{{ post.url }}" class="btn btn-default" role="button">{% t mehrlink %}</a>
                      </p>
                    </div>
                  </div>
                </div>
      {% endfor %}
    </div>
  </div>
  </div>
