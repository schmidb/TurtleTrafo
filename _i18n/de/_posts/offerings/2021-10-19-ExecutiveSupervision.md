---
layout: offerings
img: businessman_box.jpg
category: [Services-Firma]
title: Klarheit und Freude für Manager - Führungskräfte Supervision
description: "Als Manager musst Du täglich viele Entscheidungen treffen. Wir bieten
Dir eine ganzheitliche Supervision an und betrachten das Zusammenspiel all Deiner
Themen."
angebot: 1 Stunde Einzelcoaching mit Miriam oder Markus
preis: 300€ für 1h Call
anfrage: Deine Führungskräfte Supervision
---

<!-- ToDo MUss Packet werden -->

Führungskräfte haben eine komplexe Aufgabe, zu der es gehört täglich viele Entscheidungen zu treffen. Kollegen, Teammitglieder, interne Coaches und HR-Business-Partner sind gute Sparing-Partner. Meist sind diese aber an die gleichen Prozesse, die gleiche Businessidee, die gleiche Strategie oder Vision gebunden. Die Supervision mit einem externen Coach gibt die Möglichkeit sich zu fokussieren und eine qualitativ hochwertige Ausführung aller Aufgaben zu erreichen ohne sich überfordert zu fühlen.

Unsere Führungskräftesupervision umfasst Themen wie das persönliches Leben, persönliche Entwicklung, C-Level-Beziehungen, Schlüsselmitarbeiter, Organisationsstrukturen, organisatorische
Strategien & Dynamiken & Entscheidungen, Transformationsprozesse und Kulturveränderungen.
Wir betrachten immer das Zusammenspiel aller Themen und verfolgen eine ganzheitliche
Betrachtung der Situation. Unser Ziel ist der Führungskraft Klarheit in allen Lebensbereichen
zu ermöglichen und die effiziente Erfüllung der beruflichen und privaten Ziele
zu unterstützen.

<br>
## Preise & Buchung
Wir empfehlen eine zweiwöchentliche oder monatliche Einzelsupervision. Unsere Startrate
für "Supervision für Geschäftsführer und Manger" beträgt 300 Euro pro 60 Minuten Sitzung.

<a href="mailto:{{ site.email }}?subject=Anfrage Führungskräfte Supervision" target="_blank" class="btn btn-primary">Jetzt anfragen via Email</a>

Für spezielle Angebote für Ihr komplettes Führungsteam melden Sie sich bitte per Email
an {{ site.email }}.


<br>
## FAQ
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
  {% for post in site.categories.offeringsFAQ reversed %}
    {% if post.tags contains "execSupervision" %}
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
