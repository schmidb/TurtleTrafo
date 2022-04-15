---
layout: offerings
category: [Services-Familie]
img: space-shuttle-box.jpg
title: Radical Transformation - direkt ran an den Kern der Sache
title_kurz: Radical Transformation - direkt ran an den Kern
description: Ein Coaching das Dich ohne Gesäusel und ohne Weichspüler direkt mit dem Kern der Sache konfrontiert.<br>Es gibt niemanden, den Du beschuldigen kannst. Alles liegt in Dir und ermöglicht Dir eine Horizonterweiterung.
angebot: 1 Stunde Einzelcoaching mit Miriam
preis: ab 250€ für 1h Gespräch
anfrage: Dein-Radical-Transformation-Coaching
---

Ich finde wenig nerviger als das Getanze um den heißen Brei und Wegschauen von dem worum es wirklich geht. Deswegen biete und begleite ich einen Weg, der ohne Gesäusel und ohne Weichspüler Dich direkt mit dem Kern der Sache konfrontiert.

## Voraussetzung:
* Du musst die Verantwortung für Dein Leben zu 100% übernehmen wollen.
* Du musst zu 100% mit Dir in Frieden leben wollen.
* Du musst Dich gänzlich vom Konzept der Schuld verabschieden. Es gibt niemanden, den Du beschuldigen kannst. Alles liegt in Dir.

## Was du bekommst:
* Einen Weg (mit vielen Variationen), um in jeder Situation Dein "Silver Lining" - "Dein Licht am Ende des Tunnels" zu finden.
* Einen Weg hinein in ein Dir gemäßes Leben in allen Bereichen.
* Mehr als nur Coaching & Beratung: eine Horizonterweiterung.

## Wie viel Aufwand ist es für Dich?
* maximalen Effekt hast Du, wenn Du zusätzlich zu den Sessions, alle in der Sitzung erarbeiteten Übungen in Deinem Alltag einbaust. Circa 10-30 Minuten täglich.

<br>
## Preise & Buchung
<div class="panel panel-info">
<div class="panel-heading">Dein-Radical-Transformation-Coaching</div>
<div class="panel-body">

  <ul>
  <li>1h Einzelcoaching mit Miriam</li>
  </ul>
  <b>ab 250€ für 1h Gespräch</b>
  <br>Unsere Preise richten sich nach Deinem jährlichen Gesamteinkommen. Hier findest Du bald eine Übersicht wie sich unsere Preise abhängig von Deinem Gehalt verändern.
  <p><a href="mailto:{{ site.email }}?subject=Dein-Radical-Transformation-Coaching" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>


<br>
## FAQ
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
  {% for post in site.categories.offeringsFAQ reversed %}
    {% if post.tags contains "radicaltransformation" %}
    <div class="panel-heading" role="tab" id="{{post.anker}}Head">
      <h4 class="panel-title">
        <a rclass="collapsed" ole="button" data-toggle="collapse" data-parent="#accordion" href="#{{post.anker}}Role" aria-expanded="false" aria-controls="{{post.anker}}">
          {{post.title}}
        </a>
      </h4>
    </div>
    <div id="{{post.anker}}Role" class="panel-collapse collapse" role="tabpanel" aria-labelledby="{{post.anker}}Head">
      <div class="panel-body">
        {{post.content}}
      </div>
    </div>
    {% endif %}
  {% endfor %}
  </div>
</div>
