---
title: Real Options
permalink: /real-options/
excerpt: Real Options sind ein Weg, im agile Produktmanagement Entscheidungen zur Priorisierung zu treffen.
toc: true
---

Die Real Option Theory ist ein Konzept, mit dem die Idee der Finanzmarktoptionen auf unternehmerische Entscheidungen übertragen wird. Als Product Owner kannst Du Real Options für die Priorisierung von Backlogs verwenden.

## Thales von Milet und die Buddenbrooks
In Thomas Manns Roman *Buddenbrooks: Verfall einer Familie* wird eine Begebenheit geschildert, die die Familie fast in den Ruin trieb. Es handelt sich um die *Pöppenrader Ernte*, bei der Thomas Buddenbrook die vollständige Jahresernte eines Getreidebauern abkauft, während diese noch auf dem Feld steht. Kurz vor der Ernte wird das gesamte Getreide von einem Hagelschlag vernichtet. Die Familie Buddenbrook verliert nicht nur den erhofften Gewinn aus dem entgangenen Geschäft, sondern auch die komplette Investition.

Die unternehmerische Entscheidung von Thomas Buddenbrook ist im nachhinein offensichtlich spekulativ. Entscheidungen in Unternehmen treffen wir dennoch häufig nach genau der gleichen Logik: Wir sichern uns einen Gewinn in der Zukunft durch eine Investition. Das Risiko, das damit einhergeht, ist ein vollständiger Verlust durch Unvorhersehbares, wie er bei den Buddenbrooks eingetreten ist.

Das genau Gegenteil der unternehmerischen Entscheidung beschreibt Aristoteles in seinen Berichten über Thales von Milet. Die Region um Milet prosperierte zu Thales’ Lebzeiten durch den Handel mit Oliven und Olivenöl. Thales selbst hatte als Philosoph und Mathematiker keinen großen Reichtum angehäuft, was ihm den Vorwurf einbrachte, einer brotlosen Kunst nachzugehen.

Thales schloss daraufhin Verträge mit den Besitzern von Olivenpressen, durch die er gegen einen kleinen Obolus das Vormietrecht an den Pressen zum Zeitpunkt der Ernte erwarb. Als die Olivenernte kam, mietete Thales die Pressen. Er gewann auf diesem Weg ein Monopol durch das er innerhalb kurzer Zeit einen beträchtlichen Reichtum ansammelte. 

Im Nachhinein war Thales’ Vorgehen sehr geschickt, denn der Mietpreis, den er für die Pressen verlangen konnte, hing direkt vom Erfolg der Ernte ab. Der mögiliche Verlust im Falle einer schlechten Ernte war auf den Obolus für das Vormietrecht begrenzt. 

Die Geschichte von Thales und den Olivenpressen ist der erste dokumentierte Optionshandel in der Geschichte der Menschheit. Durch so einen Optionshandel hätten sich die Buddenbrooks auch vor dem großen Verlust der Pöppenrader Ernte bewahrt. Der “Kauf” einer Option ist offensichtlich etwas, das unternehmerisch sinnvoll ist. Dennoch fühlt es sich seltsam an, etwas zu kaufen, dessen Wert zum Zeitpunkt des Kaufes noch nicht feststeht - und das unter Umständen nie zum Einsatz kommt.

![image-left][image-1]{: .align-left}
Je größer die Ungewissheit ist, unter der Du Entscheidungen triffst, desto wertvoller wird das Denken in Optionen. Das macht die Real Option Theory für Dich als Product Owner intereressant.
{: .notice--primary}

## Was ist eine Option?
Das Ziel einer Option ist sehr einfach: Sie begrenzt einen möglichen Verlust.

Jede Option hat drei grundlegende Eigenschaften. Willst Du eine Option haben, zahlst Du für die Option einen Preis (cost). Du kannst die Option dann später einlösen, wenn für Dich durch das Einlösen ein Nutzen oder Wert (value) entsteht. Eine Option hat auch immer ein Verfallsdatum (expiration date), nach dessen Ablauf Du sie nicht mehr einlösen kannst.

![image-left][image-2]{: .align-left}
Optionen sollen Verluste begrenzen und besitzen drei wesentliche Eigenschaften: einen Preis (cost), einen Wert (value) und ein Verfallsdatum (expiration date).
{: .notice--primary}

Die bekannteste Variante von Optionen sind die *Call-Optionen*, bei Du das Recht hast, aber nicht die Pflicht, eine Ware zu einem bestimmten Preis zu kaufen. *Put-Optionen* funktionieren genau anders herum. Bei diesen hast Du das Recht, aber nicht die Pflicht, eine Ware zu einem bestimmten Preis zu verkaufen.

Ein anderes Merkmal zur Unterscheidung von Optionen ist der Zeitpunkt der Ausübung. *Amerikanischen Optionen* darfst Du zu jedem Zeitpunkt bis zu ihrem Verfallsdatum ausüben, während Du *europäischen Optionen* nur zum Ende ihrer Laufzeit ausüben darfst.

![image-left][image-3]{: .align-left}
Es gibt zwei grundlegende Arten von Optionen: Kaufoptionen (Call) und Verkaufsoptionen (Put). Für beide Arten gibt es die Ausprägungen in amerkanische Option  (Ausübung jederzeit) und europäische Option (Ausübung zum Laufzeitende). 
{: .notice--primary}

## Was sind Real Options?
Die Real Options gehen einen Schritt weiter und sind nicht auf das oben beschriebene Kaufen von Waren begrenzt. Du kannst sie für unternehmerische Entscheidungen benutzen.

Um die Wirkung von Real Options zu vestehen, ist es hilfreich, sie mit klassischen Backlog Items zu vergleichen. Ein klassisches Backlog Item hat ebenso wie eine Option einen Preis (cost), ist aber vorab auf einen Nutzen oder Wert (value) festgelegt. Der Nutzen oder Wert, den Du aus dem klassischen Backlog Item ziehen kannst, ist über dessen gesamte Lebenszeit konstant.

{% include figure image_path="/assets/images/real-options.png" alt="Guarantees vs. Options" caption="Guarantees vs. Options" %}

Du kannst Dein Product Backlog mit klassischen Backlog Items aufbauen. Damit begrenzt Du allerdings den Entscheidungsraum, der Dir zur Verfügung steht. Sollte der Wert eines Back Items tatsächlich geringer sein, als zum Zeitpunkt der Erstellung vermutet (siehe Hypothesen), verlierst Du neben dem nicht eingetroffenen Wert auch die Investition in das Backlog Item.

Verwendest Du statt der klassischen Backlog Items Optionen, kannst Du Entscheidungen über die Priorisierung in die Zukunft verschieben. Das hat einen Preis, der ist aber über alle Backlog Items betrachtet, geringer als die Kosten, die durch die Arbeit an den falschen Themen entstehen.

## Fragen

* Wo hast Du schon einmal —  bewusst oder unbewusst — Optionen eingesetzt?
* Hast Du schon einmal Backlog Items umgesetzt, deren Nutzen zweifelhaft war?   

## Diskussionen

[Hier geht es zur den Diskussionen][1] über *Real Options* auf dem oncampus.

## Links, Literatur & Quellen

* Mann, Thomas: Buddenbrooks
* Aristoteles: Dialoge
* Wikipedia: [Kaufoptionen][2]
* Wikipedia: [Verkaufsoption][3]

[1]:	https://www.oncampus.de/course/weiterbildung/moocs/apomooc/section-2/47432-handbuch-real-options "oncampus Forum zu Real Options"
[2]:	https://de.wikipedia.org/wiki/Kaufoption "Kaufoption"
[3]:	https://de.wikipedia.org/wiki/Verkaufsoption "Verkaufsoption"

[image-1]:	/assets/images/read-light-idea.png
[image-2]:	/assets/images/read-light-idea.png
[image-3]:	/assets/images/read-light-idea.png