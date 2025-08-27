---
title: A02 | Raummodellierung
toc: true
header:
  image: /assets/images/02-splash.jpg
  image_description: "Blick ins Lahntal mit Grünlandwirtschaft, Baustelle für Stromtrassen und Regenbogen."
  caption: "Foto: T. Nauss / CC0"

---

In Aufgabe 02 beschäftigen Sie sich mit der Modellierung (also der zielführenden Abstraktion) von Raumeigenschaften. Sie üben die erforderliche Abstraktionsleistung zunächst indem Sie einen einfachen Modellsimulator nutzen und sich mit ihm vertraut machen. Anschließend führen Sie selbst Experimente durch und stellen zum Abschluss ihre Ergebnisse in einer kartenähnlichen Skizze dar.

## Benötigte Materialien für die Aufgaben
* Papier und Stifte
* Die NetLogo Software [NetLogo](https://ccl.northwestern.edu/netlogo/6.2.0/)
* Der Artikel [Applications of simulation-based burn probability](https://www.publish.csiro.au/wf/Fulltext/WF19069)
* Das Modell [Fire]({{ site.baseurl }}/assets/misc/Fire.nlogo)

Bitte beachten Sie die bindenden [formalen Anforderungen](https://geomoer.github.io/moer-meko//unit00/unit00-03_assignments.html#formale-anforderungen).
{: .notice--danger}



### Die NetLogo Modellierungssoftware
Sie benötigen die Modellierungs-Software `NetLogo`. Falls `NetLogo` auf Ihrem Rechner nicht installiert ist (was sehr wahrscheinlich der Fall ist), können Sie die aktuelle Version der freien Software für ihr Betriebssystem von der [Download-Seite](https://ccl.northwestern.edu/netlogo/6.2.0/) herunterladen und installieren. 
Das Modell [*Fire-Simulation-1*]({{ site.baseurl }}/assets/misc/Fire-Simulation-1.nlogo) das wir verwenden müssen Sie separat herunterladen und mit Netlogo öffnen.

Alternativ können Sie auch mit der  nachfolgend eingebetteten Online-Version arbeiten. 
  
{% include media3 url="assets/misc/Fire-Simulation-1.html" %}

## A02-1 Lesen, exzerpieren des Artikels 

In dem Artikel [Applications of simulation-based burn probability](https://www.publish.csiro.au/wf/Fulltext/WF19069) werden Sie auf einer wissenschaftlichen Basis mit den wichtigsten Konzepten zur anwendungsorientierten Simulation von Flächenbränden vertraut gemacht. Da der Artikel als sogenannter "Review" Artikel den Stand der Forschung zusammenstellt, ist er durchaus anspruchsvoll und bietet ihnen in kompakter Weise den Wissenstand zu diesem Thema. Wir erwarten natürlich nicht, dass Sie sich nun zu Flächenbrand-Expert:innen ausbilden. Wichtig ist jedoch, dass Sie vertraut werden mit Verfügbarkeit und Einschätzung von evidenzbasierten wissenschaftlichen Methoden. Insbesondere bietet Ihnen der Artikel eine wertvollen Überblick darüber was zu bedenken ist, wenn sie sich dem System Flächenbrand in Raum und Zeit annähern. 

{% capture Assignment-2-1 %}
1. Legen Sie zunächst eine Tabelle mit vier Spalten an, diese Spalten werden Sie in dieser und der nächsten Aufgabe füllen.
1. Bitte identifizieren Sie die zentralen Elemente, die für die Entstehung und den Verlauf von Flächenbränden von elementarer Bedeutung sind. Tragen Sie diese Elemente in die erste Spalte Ihrer Tabelle ein (Spaltenüberschrift "Elemente").
1. Identifizieren Sie die Prozesse, die auf der räumlichen Skala von Bedeutung sind. Welchen Elemente sind in Prozesse zugeordnet? Tragen Sie die Prozesse (Stichwort) in Ihre Tabelle ein (Spaltenüberschrift "Prozesse").
1. Sind diese Prozesse skalenabhägig? Verlaufen sie also in direkter Nachbarschaft anders als großräumig? Markieren Sie auch diese Einschätzung in der Tabelle (x= ja, leer = nein, Spaltenüberschrift "Skalenabhägigkeit").

{: .notice--info}
{% endcapture %}
<div class="notice--success">
  {{ Assignment-2-1 | markdownify }}
</div> 

Umfang 1 Seite in ihrem PDF-Dokument

## A02-2 Modellbeschreibung Netlogo lesen und exzerpieren
Lesen Sie nun den **Info Text** des NetLogo-Modells. Welche Elemente der im zuvor beschriebenen Artikel finden sie wieder und welche Elemente scheinen zu fehlen?

Tragen Sie in die Tabelle aus A02-1 ein (x= ja, leer = nein), welche Elemente im NetLogo Modell abgebildet werden (Spaltenüberschrift "NetLogo vorhanden"). 
{: .notice--success}

Umfang **keine eigene Seite**, die Ergebnisse werden in der Tabelle aus A02-1 eingetragen.

## A02-3 Experimentieren Sie mit dem Modell 

Untersuchen Sie, wie das Verhältnis des verbrannten Waldes mit den verschiedenen Dichteeinstellungen zusammenhängt. 
Gibt es einen Dichte-Schwellenwert ab welchem fast der gesamte Wald verbrennt?
Untersuchen Sie, ob der Wald identisch abbrennt indem Sie den Wald in den Ausgangszustand zurückzusetzen und die Ergebnisse qualitativ vergleichen. Verbrennen die gleichen Teile des Waldes? Sind die Muster in dichtem oder lichtem Wald ähnlicher oder anders?
Untersuchen Sie, ob eine unterschiedliche Anordnung von initialen Zündpunkten Auswirkungen auf den die räumliche Ahnlichkeit bzw. Quantität des Abbrands haben.
Untersuchen Sie die obigen Experimente mit unterschiedlichen Wind-Einstellungen. Gibt es Abweichungen?

Fassen Sie ihre Ergebnisse in **geeigneter** Weise in einer *neuen* Tabelle zusammen. Bewerten Sie im Kontext des zuvor gelesenen Artikels wie realitätsnah das NetLogo Modell ist. Welche Aspekte werden berücksichtigt? Welche Aspekte fehlen? (max 5 Sätze)
{: .notice--success}

Umfang 1 Seite in Ihrem PDF-Dokument


