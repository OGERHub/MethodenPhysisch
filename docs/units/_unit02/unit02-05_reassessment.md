---
title: NP02 | Raummodellierung
toc: true
header:
  image: /assets/images/02-splash.jpg
  image_description: "Blick ins Lahntal mit Grünlandwirtschaft, Baustelle für Stromtrassen und Regenbogen."
  caption: "Foto: T. Nauss / CC0"

---


## Benötigte Materialien für die Aufgaben
* Papier und Stifte
* Der Leitfaden [Creating Wildfire-Defensible Spaces
for Your Home and Property](https://cals.arizona.edu/extension/ornamentalhort/landscapemgmt/general/wildfire_defense.pdf)
* Die NetLogo Software [NetLogo](https://ccl.northwestern.edu/netlogo/6.2.0/) alternativ die in dieser Übung verlinkte Webbasierte Version *Fire2*.
* Das Modell [Fire2]({{ site.baseurl }}/assets/misc/Fire2.nlogo)
### Fire2 Webversion

{% include media3 url="assets/misc/Fire2.html" %}

## Aufgabe NP02-01 Simulationsbasierte Empfehlung für einen zonierten Feuerschutz

In den Hinweisen [Creating Wildfire-Defensible Spaces
for Your Home and Property](https://cals.arizona.edu/extension/ornamentalhort/landscapemgmt/general/wildfire_defense.pdf) hat die University of Arizona einen Anwendungsleitfaden zum Feuerschutz von bewaldetem Privateigentum auf der Grundlage einer Zonierungsstrategie erstellt. Es werden drei Schutzzonen um brandgefährdetes Eigentum benannt, deren Einrichtung einen effektiven Feuerschutz sicherstellen soll (Abbildung 1). 

{% capture NP02-01 %}

Sie haben nun die Aufgabe anhand dieser Empfehlung ein geeignetes Vorgehen zu entwickeln, um auf der Grundlage geeigneter Simulationen die obigen Vorgaben zu überprüfen. Da es der Verwaltung um einen möglichst geringen Eingriff in das Privateigentum geht, sollen folgende Bedingungen in den Simulation berücksichtigt werden:

* Die Ausdehnung der Pufferzone 1  und 2 soll **minimal** sein
* Die Walddichte in Pufferzone 2 und 3 soll **maximal** sein
* Das Feuer soll auch unter veränderten meterologischen (Wind) und physikalischen Bedingungen (Branddauer)  **verlässlich** in der **Zone 2** gestoppt werden

Welche Baumdichten und Zonenabstände empfehlen Sie aufgrund ihrer Simulationen? 

Diskutieren Sie in maximal 3 Sätzen auf der erabeiteten Grundlage die Belastbarkeit Ihrer Empfehlungen. 

**Hinweis:** Führen Sie eine ausreichende Anzahl von Wiederholungungen der jeweiligen Simulation durch um stochastische Zufallseffekte auszuschliessen  (kurze Begründung). Falls dies durch mehrere Häuser/Simulationen erreciht werden soll, müssen diese so plaziert werden, dass sich die Häuser nicht gegenseitig beeinflussen.  
{: .notice--info}
{% endcapture %}
<div class="notice--success">
  {{ NP02-01 | markdownify }}
</div> 


**Tipp**: Um eine systematische Untersuchung von wiederholten Simulationen durchführen zu können, stellt NetLogo das BehaviorSpace Werkzeug im Menu "Tools" zur Verfügung. Sie müssen hierzu NetLogo installiert haben und können nicht die Online Version nutzen. Sie finden unter [BehaviorSpace](https://ccl.northwestern.edu/netlogo/docs/behaviorspace.html) eine vollständige und unter [BehaviorSpace Tutorial](http://s3.amazonaws.com/complexityexplorer/IntroToComplexity/NetLogoDocuments/NetLogoBehaviorSpaceTutorial.pdf) ein einfaches und gut verständliches Tutorial.
{: .notice--info}

_**Umfang: 2 Seiten in Ihrem PDF-Dokument**_
