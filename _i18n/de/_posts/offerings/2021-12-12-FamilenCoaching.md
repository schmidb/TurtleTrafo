---
layout: offerings
img: schmidberger2020_box.webp
category: [Services-Familie]
title: Neue Wege als Familie gehen - Familien Transformation
description: "Wir begleiten dich zu Deinen
Familienträumen und zeigen Dir mögliche Wege, wie Entspannung bei Dir und in
Deiner Familie ankommen kann."
angebot: 1 x Family-Zoom Call, 2 x Einzelcoachings und Telegram Gruppe
preis: 700€ pro Monat oder 3500€ für 6 Monate
anfrage: Familien-Transformations-Coaching - Monats Package
---

Wage Dich auf den Weg von 'Innen nach Aussen'.

Für uns sind die Menschen unserer Familie das Wichtigste was wir haben. Wäre ihr
Leben bedroht, würden wir alles tun, um es zu retten. Immer wieder fällt uns auf,
dass das alltägliche Miteinander dies nicht klar widerspiegelt. Unfreundliche
oder genervte Worte fallen, der Stress und damit aggressive Reaktionen nehmen zu
und abends im Bett, wenn Ruhe eingekehrt ist, fühlt sich unser Miteinander schrecklich
an. So begann und beginnt immer wieder der langsam aber stetig Kreise ziehende
Prozess in ein friedvolles Miteinander als Familie zu kommen.

Wir haben immer wieder die Erfahrung gemacht, dass unser Weg genau da lang geht, wo es scheinbar keinen Weg gibt. Im Halten der vermeintlichen Auswegslosigkeit und im Erforschen ihrer Grenzen und Wände haben wir erfahren, dass es möglich ist, mit Offenheit und kreativem Entdeckergeist ins Unsichere zu starten und dadurch für uns neue Wege zu finden.

Es gibt viele Punkte in Deinem Familienleben an dem Veränderungen anstehen. Mögliche Beispiele sind:
* Schulstart
* Umzug oder neuer Beruf
* Geburt eines weiteren Kindes
* Auswanderung

In unserer Beratung betrachten wir immer deine persönlichen Themen (z.B. *ich habe Angst vor der Abmeldung und weiß nicht ob ich das alles schaffe.*). Wir bieten auch Beratung zu technischen oder rechtlichen Prozessen (z.B. *wie melde ich mich in Deutschland ab?*, *wie umgehe ich die Schulpflicht? in Deutschland*).

Bei Interesse teilen wir Wege, die sich für uns bewährt haben, um als Familie friedvoll, entspannt und
genussreich miteinander zu sein. Wir begleiten dich wenn du magst zu deinen
Familienträumen und zeigen dir mögliche Wege, wie Entspannung bei dir und in
deiner Familie ankommen kann.


<br>
## Preise & Buchung
Wir empfehlen ein wöchentliches oder zweiwöchentliches Treffen. Ob diese Treffen nur für ein Elternteil, beide Eltern oder Eltern & Kinder ist entscheiden wir vor jeder Sitzung. Neben dem individuellen Coaching bieten wir drei verschiedene Pakete an:


<div class="panel panel-info">
<div class="panel-heading">Familien-Transformations-Coaching - <b>EINZEL</b></div>
<div class="panel-body">
  <p>Im Einzelcoaching betrachten wir deine aktuelle Lebenssituation und deine Wunschvorstellung vom Leben. Basierend darauf erarbeiten wir erste Schritte hin zu deiner Vision. Meist benötigen wir hierfür zwei bis drei 60-90 Minuten Gespräche.</p>
  <ul>
  <li>1h Einzelcoaching mit Miriam oder Markus</li>
  </ul>
  <b>150€ pro 1h Zoom Call</b>, Abrechnung erfolgt auf 30 Minuten Einheiten.
  <p><a href="mailto:{{ site.email }}?subject=Familien-Transformations-Coaching - Einzel" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>

<div class="panel panel-info">
<div class="panel-heading">Familien-Transformations-Coaching - <b>FAMILY</b></div>
<div class="panel-body">
  <p>Gemeinsam betrachten wir eure aktuelle Lebenssituation und eure Wunschvorstellung vom Leben. Basierend darauf erarbeiten wir erste Schritte hin zu eurer Vision. Meist benötigen wir hierfür zwei bis drei 90 Minuten Gespräche mit beiden Eltern.</p>
  <ul>
  <li>1.5h Family Zoom Coaching mit Miriam und Markus</li>
  </ul>
  <b>300€ pro 1.5h Zoom Call</b>, Abrechnung erfolgt auf 30 Minuten Einheiten
  <p><a href="mailto:{{ site.email }}?subject=Familien-Transformations-Coaching - Family" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>

<div class="panel panel-info">
<div class="panel-heading">Familien-Transformations-Coaching - <b>MONATS PACKET</b></div>
<div class="panel-body">
  <p>Gemeinsam betrachten wir eure aktuelle Lebenssituation und eure Wunschvorstellung vom Leben und wir arbeiten bedürfnisorientiert mit jedem Einzelnen von euch. Zusätzlich gibt es eine gemeinsame Telegram-Gruppe in der wir zeitnah eure aktuellen Fragen beantworten bzw. euch Inspirationen schicken.</p>
  <ul>
  <li>1 x 1.5h Family Zoom Coaching mit Miriam und Markus pro Monat</li>
  <li>2 x 1h Einzelcoaching mit Miriam oder Markus pro Monat</li>
  <li>Telegram Gruppe für tägliche Begleitung & Fragen & Inspirationen</li>
  </ul>
  <b>700€ pro Monat</b> oder <b>3500€ für 6 Monate</b>
  <p><a href="mailto:{{ site.email }}?subject=Familien-Transformations-Coaching - Monats Package" target="_blank" class="btn btn-primary">Jetzt buchen</a></p>
</div>
</div>


<br>
## FAQ
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
  {% for post in site.categories.offeringsFAQ reversed %}
    {% if post.tags contains "family" %}
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
