---
title: Impact Map
permalink: /impact-map/
excerpt: “Lorem ipsum”
toc: true
---

## Einführung
Die Impact Map bildet die Brücke zwischen konkreten Liefergegenständen, z.B. Features eines Produkts, und taktischen Zielen. 
Damit schließt sie auch die Kommunikationslücke zwischen den Geschäfts- und Fachabteilungen und Software Teams.

![image-left]({{site.baseurl}}/assets/images/flag-warning.png){: .align-left} 
Gojko Adzic (2012) schreibt: „In essence, you should care about impact mapping because it can help you build products and deliver projects that make an impact, not just ship software.“
{: .notice--warning}

## Ziel
Durch die Impact Map kannst du Annahmen in Bezug auf die Wirkungen von Software Features auf dein Produktziel visualisieren. 
Sie unterstützt dich dabei, den Fokus beizubehalten und eine schleichende Erweiterung des Lieferumfangs (den sog. Scope Creep) deines Produkts zu unterbinden. 
Investitionen in nicht notwendige Features kannst du so durch die klare Ausrichtung auf messbare Ziele verhindern. 
Diese hilft dir auch bei der Priorisierung von Features. 

## Geschichte
Impact Maps wie wir sie dir hier vorstellen wurden 2012 von Gojko Adzic in seinem gleichnamigen Buch beschrieben. 
Sie basieren auf der InUse Effect Mapping Methode von Mijo Balic und Ingrid Domingues sowie Impact Maps von Robert O. Brinkerhoff die für Trainings und Lernen in Organisationen genutzt werden. 
Weitere Impulse lieferten die Feature Injection von Chris Matts und Ideen zur Messbarkeit und iterativer Entwicklung von Tom Gilb. 

## Funktionsweise
Eine Impact Map stellt dar, welche Auswirkungen (Impact) durch einen technischen Liefergegenstand (Deliverable) erreicht werden sollen. 
Der Impact entsteht dadurch, dass ein Akteur (Actor) durch das Deliverable sein Verhalten in eine bestimmte Richtung ändert. 
Eine Anzahl Impacts führt in Summe zum Erreichen eines Ziels (Goal).  
Die Elementgruppen Goal, Actors, Impacts und Deliverables sind in der Impact Map horizontal zueinander angeordnet: 

{% include figure image_path="assets/images/11-impact-map-structure-gojko-adzic.png" alt="Ableitung von User Stories aus der Impact Map, Darstellung von Gojko Adzic" %}

Durch diese Darstellung werden die Beziehungen der Elemente zueinander deutlich.
Nachfolgend beschreiben wir dir die Elementargruppen genauer:

### Goal bzw. Why?
Hier beantwortest du die Frage, was das (nächste) Ziel für dein Produkt ist.
Empfehlenswert ist es, ein messbares Ziel anzugeben. 
Das „Warum“ sorgt dafür, dass alle Beteiligten wissen, worauf es im Projekt wirklich ankommt. 
Du und dein Team können so auch bei unvorhergesehenen Problemen zielführende Entscheidungen treffen.

### Actors bzw. Who? 
Hier fragst du, wer zum Erreichen das Ziels beitragen kann. 
Wer kann im positiven Sinne beitragen? 
Wer kann den Erfolg verhindern? 
Wer wird beeinflusst? 
Hier solltest du so spezifisch sein wie möglich.

### Impacts bzw. How?
Hier beschreibst du, wie die Akteure die Zielerreichung beeinflussen (sollen).
Wie sollte sich ihr Verhalten ändern? 
Wie können sie uns helfen? 
Wie können sie uns behindern?

### Deliverables bzw. What?
Was kannst du mit deinem Team tun, um den Akteuren bei der erwünschten Verhaltensänderung zu helfen? 
Was musst du ihnen zur Verfügung stellen, um sie zu unterstützen? 
Was kannst du tun, um negative Impacts zu vermeiden?

Die Impact Map visualisiert Annahmen auf zwei Ebenen: 

* die Annahme, dass ein Deliverable zu einer Verhaltensänderung eines Akteurs führt und dadurch den Impact hervorbringt und 
* die Annahme, dass dieser Impact zum Erreichen des übergeordneten Ziels beiträgt

Durch das Liefern eines Deliverables kannst du validieren, ob die Annahmen zu Verhaltensänderung und dem Erreichen des übergeordneten Ziels richtig waren.
Stellst du z.B. fest, dass der Impact keine positive Auswirkung auf das Ziel hat, richtest du den Fokus auf einen anderen zu bearbeitenden Impact. 

## Einsatz
Die Impact Map kannst du für jeden Meilenstein in der Produktentwicklung erstellen. 
Auch wenn du für dein Produkt bisher keine Impact Maps genutzt hast, kannst du von ihnen profitieren. 

Die Impact Map kann wichtige Informationen transparent darstellen, angefangen mit dem Ziel, die erreicht werden sollen. 
Das Formulieren eines Ziels ist der erste Schritt bei der Erstellung einer Impact Map. 
Lege dann fest, wie du das Erreichen des Ziels messen möchtest. 

<div markdown="1">
![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Gojko schreibt hierzu: „Ask: „If we achieve key targets for metrics with a completely different scope than planned, have we succeeded?” If the answer is “No”, go back to start: You don´t have the right metrics.”
</div>
{: .notice--primary}!


Im nächsten Schritt erstellst du ausgehend vom formulierten Ziel mit deeinen Metriken das Skelett der Impact Map durch hinzufügen von Akteuren, Impacts und Deliverables.
Auf dieser Basis formulierst du alternative Akteure, Impacts und Deliverables, die zur Zielerreichung beitragen könnten. 
Ziel ist es, potenziell einfachere oder günstigere Wege zum Ziel zu finden.
Schließlich markierst du auf der Map, welche Impacts mit welchen Deliverables priorisiert werden. Frage dich hierfür: 

* Was sind mögliche Blocker für das Erreichen des Ziels, die adressiert werden müssen? 
* Gibt es low-hanging fruits mit hohem Wert? 
* Welche Annahmen müssen getestet werden?

<div markdown="1">
![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
“Never aim to implement the whole map. Instead, find the shortest path through the map to the goal”. Gojko Adzic, 2012
</div>
{: .notice--primary}!

Die Struktur der Impact Map erleichtert dir außerdem das Formulieren von User Stories für das Product Backlog. 
Aus jedem Deliverable kannst du nach diesem Muster eine User Story zum weiteren Refinement ableiten: 

{% include figure image_path="assets/images/11-impact-map-user-stories-gojko-adzic.png" alt="Ableitung von User Stories aus der Impact Map, Darstellung von Gojko Adzic" %}

Am besten erstellst du sie in einem Workshop mit Stakeholdern und deinem Team.
Die Impact Map macht es dir durch ihre eingängige Struktur leicht, Menschen in verschiedenen Rollen und mit verschiedenen Hintergründen einzubinden.
Es kann hilfreich sein, zwei Workshops für eine Impact Map einzuplanen. 
Stelle sicher, dass zwischen den Terminen genügend Zeit ist, um eventuell fehlende Informationen einzuholen. 


## Beispiel

{% include figure image_path="assets/images/11-impact-map-example-gojko-adzic.png" alt="Beispiel einer Impact Map für ein Onlinespiel von Gojko Adzic" %}

Weitere Beispiele und umfangreiche Informationen zum Erstellen einer Impact Map findest du in Gojkos Buch „Impact Mapping“ und auf der Impact Mapping Website unter [Practical Usage](https://www.impactmapping.org/tips-and-tricks.html). 

## Tools
Mit genügend Wandfläche und Post-its könnt ihr die Impact Map wachsen lassen, diskutieren und priorisieren. 

Es gibt außerdem verschiedene Onlinetools, die du fürs kollaborative Impact Mapping nutzen kannst, z.B. [UXPressia](https://uxpressia.com/impact-map-online-tool).
Für miro gibt es ein Impact Mapping Template. 
Auch mit Gojko Adzics Tool [MindMup](https://www.mindmup.com/) kannst du Impact Maps erstellen.

## Fragen

* Welchen Nutzen kann die Impact Map für dein Projekt bringen?
* Was ist deiner Meinung nach die größte Herausforderung beim Erstellen einer Impact Map?
* Ab welchem Zeitpunkt merkst du, dass Annahmen deiner Impact Map überarbeitet werden sollten?

## Diskussionen
[Hier geht es zu den Diskussionen](https://www.oncampus.de/blocks/oc_mooc_nav/forum_view.php?showall=false&id=47546) zu den *Handbuchkapiteln* auf dem oncampus.

## Downloads
[Impact Mapping Cheat Sheet von Gojko Adzic](https://www.impactmapping.org/assets/cheatsheet.pdf)


## Links

* [Tipps und Tricks, Kombination mit anderen Tools und Papers](https://www.impactmapping.org/tips-and-tricks.html)
* Gojko Adzic (2012): Impact Mapping
* Brinkerhoff Robert O. and Apking, Anne M. High Impact Learning. Cambridge, MA: Perseus Publishing, 2001
* Mijo Balic, Ingrid Ottersten (2007): Effect Managing IT
* Robert O. Bringerhoff, Stephen J. Gill (1994): The Learning Alliance: Systems Thinking in Human Resource Development
* Tom Gilb (2005): Competitive Engineering
* Chris Matts, Gojko Adzic (2011): Feature injection: three steps to success


