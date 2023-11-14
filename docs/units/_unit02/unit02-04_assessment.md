---
title: P02 | Raummodellierung
toc: true
header:
  image: /assets/images/02-splash.jpg
  image_description: "Blick ins Lahntal mit Grünlandwirtschaft, Baustelle für Stromtrassen und Regenbogen."
  caption: "Foto: T. Nauss / CC0"

---

Ziel dieser Abgabe ist es, aus Ihren Modellergebnissen eine empirische evidenzbasierte valide Aussage abzuleiten.

## Benötigte Materialien für die Aufgaben
* Papier und Stifte
* Der Leitfaden [Creating Wildfire-Defensible Spaces
for Your Home and Property](https://cals.arizona.edu/extension/ornamentalhort/landscapemgmt/general/wildfire_defense.pdf)
* Die NetLogo Software [NetLogo](https://ccl.northwestern.edu/netlogo/6.2.0/)
* Das Modell [Fire2]({{ site.baseurl }}/assets/misc/Fire-Simulation-2.nlogo)

Alternativ können Sie das online Modell *Fire-Simulation-2* nutzen.

{% include media3 url="assets/misc/Fire-Simulation-2.html" %}

## Aufgabe P02-01 Simulationsbasierte Empfehlung für einen zonierten Feuerschutz

In den Hinweisen [Creating Wildfire-Defensible Spaces
for Your Home and Property](https://cals.arizona.edu/extension/ornamentalhort/landscapemgmt/general/wildfire_defense.pdf) hat die University of Arizona einen Anwendungsleitfaden zum Feuerschutz von bewaldetem Privateigentum auf der Grundlage einer Zonierungsstrategie erstellt. Es werden drei Zonen um brandgefährdes Eigentum identifiziert, deren Einrichtung einen effektiven  Feuerschutz sicherstellen sollen (Abbildung 1). 

{% capture Assignment-2-2 %}
Sie haben nun die Aufgabe für ein County in Arizona diese Empfehlung mit Hilfe einer geeigneten Simulation auf der Grundlage der obigen Vorgaben zu überprüfen und konkret festzulegen. Da es der Verwaltung um einen möglichst geringen Eingriff in das Privateigentum geht sollen folgende Bedingungen in die Simulation berücksichtigt werden:

* Die Ausdehnung der Pufferzonen 1  und 2 soll **minimal** sein
* Die Walddichte (Pufferzone 2 und 3) soll **maximal** sein
* Das Feuer soll auch unter veränderten meterologischen (Wind) und physikalischen Bedingungen (Duerre)  **verlässlich**  weniger als 5 % Brandschaden am Gebäude verursachen

Welche Baumdichten und Zonenabstände empfehlen Sie? 

Diskutieren Sie auf der Grundlage der von ihnen dokumentierten Simulationen  die Belastbarkeit Ihrer Empfehlungen. 



{: .notice--info}
{% endcapture %}
<div class="notice--success">
  {{ Assignment-2-2 | markdownify }}
</div> 


**Tipp**: Um eine systematische Untersuchung von wiederholten Simulationen durchführen zu können, stellt NetLogo das BehaviorSpace Werkzeug im Menu "Tools" zur Verfügung. Sie müssen hierzu NetLogo installiert haben und können nicht die Online Version nutzen. Sie finden unter [BehaviorSpace](https://ccl.northwestern.edu/netlogo/docs/behaviorspace.html) eine vollständige und unter [BehaviorSpace Tutorial](http://s3.amazonaws.com/complexityexplorer/IntroToComplexity/NetLogoDocuments/NetLogoBehaviorSpaceTutorial.pdf) ein einfaches und gut verständliches Tutorial.
{: .notice--info}

Umfang 1 Seite in Ihrem PDF-Dokument
