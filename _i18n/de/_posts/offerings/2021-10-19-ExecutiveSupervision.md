---
layout: offerings
img: businessman_box.jpg
category: [Services-Firma]
title: Klarheit und Freude für Manager - Führungskräfte Supervision
description: "Als Manager musst Du täglich viele Entscheidungen treffen. Wir bieten
Dir eine ganzheitliche Supervision an und betrachten das Zusammenspiel all Deiner
Themen."
angebot: 45 min Einzelcoaching mit Miriam oder Markus
preis: ab 300€ für 45 min Coaching oder 1800€ für 3 Monate
anfrage: Deine Führungskräfte Supervision
---

Führungskräfte haben eine komplexe Aufgabe, zu der es gehört täglich viele Entscheidungen zu treffen. Kollegen, Teammitglieder, interne Coaches und HR-Business-Partner sind gute Sparing-Partner. Meist sind diese aber an die gleichen Prozesse, die gleiche Businessidee, die gleiche Strategie oder Vision gebunden. Die Supervision mit einem externen Coach gibt die Möglichkeit sich zu fokussieren und eine qualitativ hochwertige Ausführung aller Aufgaben zu erreichen ohne sich überfordert zu fühlen.

<br>
<div class="container">
  <div class="row">

  <div class="col-sm-3 col-md-3">
  <center>
  <i class="fa-solid fa-glasses fa-2xl"></i><br>
  <p style="margin-top: 0.25em;">mehr Klarheit für dich</p>
  </center>
  </div>

  <div class="col-sm-3 col-md-3">
  <center>
  <i class="fa-solid fa-bullseye fa-2xl"></i>
  <p style="margin-top: 0.25em;">bessere Zielerreichung für dich und deine Teams</p>
  </center>
  </div>

  <div class="col-sm-3 col-md-3">
  <center>
  <i class="fa-solid fa-route fa-2xl"></i>
  <p style="margin-top: 0.25em;">authentischeres & menschlicheres Führen von Mitarbeitern</p>
  </center>
  </div>

  <div class="col-sm-3 col-md-3">
  <center>
  <i class="fa-solid fa-scale-balanced fa-2xl"></i><br>
  <p style="margin-top: 0.25em;">bessere Work-Life-Balance</p>
  </center>
  </div>          

        </div>
  </div>
<br>

Unsere Führungskräftesupervision umfasst Themen wie das persönliches Leben, persönliche Entwicklung, C-Level-Beziehungen, Schlüsselmitarbeiter, Organisationsstrukturen, organisatorische
Strategien & Dynamiken & Entscheidungen, Transformationsprozesse und Kulturveränderungen.
Wir betrachten immer das Zusammenspiel aller Themen und verfolgen eine ganzheitliche
Betrachtung der Situation. Unser Ziel ist der Führungskraft Klarheit in allen Lebensbereichen
zu ermöglichen und die effiziente Erfüllung der beruflichen und privaten Ziele
zu unterstützen.

<br>
## Mögliche Schwerpunkte:
* Übersicht im Arbeitsumfeld und im Privaten gewinnen & behalten
* Strategische Fragen für Firma, Leben, Familie
* Berufliche Kompetenzen entdecken und entwickeln
* Personalfragen
* Konflikte auf Personen-, Team- und Organisationsebene
* Gefahren & Ängste erkennen und vermeiden
* Überlastung und Überforderung - Burnout?
* Unverstandenes oder unerwartetes Feedback
* Sicherheit und Authentizität aufbauen

<br>
## Für wen ist Führungskräfte Supervision?
Der Einfachheit halber wird hier nur die männliche Rolle verwendet. Frauen und andere Geschlechter sind auch herzlich abgesprochen:
* Vorstände, Geschäftsführer, Gremienmitglieder
* C-Level Manager
* Fach- und Führungskräfte, Teamleiter
* Mediatoren und Konfliktmanager
* Projektleiter
* Lehrer

<br>
## Preise & Buchung

<div class="panel panel-info">
<div class="panel-heading">Führungskräfte Supervision - <b>EINZEL</b></div>
<div class="panel-body">
  <p>Im Einzelcoaching betrachten wir die aktuelle Führungssituation und Wunschvorstellung von Arbeit & Leben. Basierend darauf erarbeiten wir erste Schritte hin zu der persönlichen Vision. Meist benötigen wir hierfür zwei bis drei, 60-90 Minuten Gespräche. Als Coaches stehen Miriam oder Markus auf Anfrage zur Verfügung.</p>
  <b>300€ pro 45 min Zoom Call</b>, Abrechnung erfolgt auf 15 Minuten Einheiten.
  <p><a href="mailto:{{ site.email }}?subject=Führungskräfte Supervision - Einzel" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>


<div class="panel panel-info">
<div class="panel-heading">Führungskräfte Supervision - <b>3 MONATE</b></div>
<div class="panel-body">
  <p>Im Packet erarbeiten wir anfangs deine Vision und arbeiten uns dann Schritt für
  Schritt an Hand deiner täglichen Führungssituationen hin zu deinem Ziel. Unterstützt werden
  die Coachings durch wöchentliche Check-Ins via Messenger. Als Coaches stehen Miriam oder Markus auf Anfrage zur Verfügung.</p>
  <ul>
  <li>6 * 45 Minuten Einzelcoaching via Zoom mit Miriam oder Markus</li>
  <li>1 mal pro Woche Check-In via Telegram Kanal mit Miriam oder Markus</li>
  </ul>
  <b>1800€ für 3 Monate</b>
  <p><a href="mailto:{{ site.email }}?subject=Führungskräfte Supervision - 3 Monate" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>



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
