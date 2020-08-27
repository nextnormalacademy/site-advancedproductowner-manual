---
title: Feedback Loops
permalink: /feedback-loops/
excerpt: "Feedback Loops"
toc: true
---

**-- DRAFT --**
{: .notice--danger}

## Einführung

Feedback Loops sind ein wichtiges Werkzeug für Product Owner. Sie richtig einzusetzen ist allerdings nicht ganz einfach.

Dieses Kapitel soll die Grundlagen für einen effektiven Einsatz von Feedback Loops vermitteln.

![image-left]({{site.baseurl}}/assets/images/flag-warning.png){: .align-left} 
Es geht hier im Handbuch ausschließlich um Feedback und Feedbackmanagement als Bestandteil von Produktentwicklung und Produktmanagement.
Persönliches Feedback im Sinne der Gruppendynamik wird nicht betrachtet.
{: .notice--warning}

In der agilen Community ist der PDCA- oder Deming-Cycle wohl der bekannteste Feedback Loop.
PDCA steht für Plan, Do, Check, Act und beschreibt die Phasen eines kontinuierlichen Verbesserungsprozesses.

**-- DRAFT --**
{: .notice--danger}

## Elemente von Feedback Loops

<div markdown="1">
![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Feedback Loops bestehen aus vier Elementen, die jeweils für sich stehend betrachtet und verstanden werden müssen:
- einer Beobachtung des Gegenstands, zum dem das Feedback gegeben wird
- der Reaktion auf diese Beobachtung in Form von Input
- der Verknüpfung von Beobachtung und Reaktion
- der Verknüpfung des Inputs mit dem Gegenstand der Beobachtung
</div>
{: .notice--primary}

Um einen Feedback Loop zielgerichtet nutzen zu können, benötigst du einen *Gegenstand*, zu dem du Feedback aufnehmen möchtest.
Bei diesem Gegenstand wird es sich in den meisten Fällen um dein Produkt handeln.
Feedback zum gesamten Produkt ist ab einer gewissen Größe und Komplexität des Produkts schwierig zu handhaben.
Daher solltest du den Gegenstand des Feedback Loop einschränken.
Der betrachtete Gegenstand kann dann ein Produktinkrement sein oder auch ein neu hinzugekommenes Feature.

Die *Beobachtung* dieses Gegenstands führt zu Reaktionen, z.B. von Menschen oder technischen Systemen.
Einige dieser Reaktionen wirst Du in Form von *Input* wahrnehmen.
Der Input muss nicht zwangsläufig Feedback in deinem Sinne sein.
Häufig äußern Menschen auch Meinungen, die durch andere Aspekte  wie aktuelle Emotionen, Erlebnisse, Erwartungen oder Gruppendynamik geprägt sind.
Dieses *Rauschen* ist der größte Anteil des Inputs.
Für dich als Product Owner ist es wichtig, den Input auch nur als genau solchen zu betrachten: viel Rauschen, das ein wenig wertvolles Feedback enthält.

Der nächste Schritt besteht im Herausfiltern des Feedbacks aus dem Input.
Dazu bedarf es einer *Interpretation* des Inputs.
Für diese Interpretation musst du neben dem Gegenstand auch einiges über die Verknüpfung von Beobachtung und Input wissen.
Du musst den Kontext kennen, aus dem heraus der Input gegeben wurde.
Auch die Zugehörigkeit der Quelle des Inputs ist relevant.
Es ist ein Unterschied, ob ein Input von Betroffenen oder Beteiligten kommt, ob sie potentielle Nutzer:innen oder die Entwickler:innen eines Wettbewerbsproduktes gegeben haben.

Hast du das Feedback aus dem Input herausgefiltert, gilt es zu entscheiden, wie du darauf reagieren willst.
Du musst *Handlungen* ableiten.
Prinzipiell gibt es zwei Möglichkeiten: du kannst das Feedback berücksichtigen oder ignorieren.
Wenn du es berücksichtigen möchtest, gibt es wiederum mehrere Varianten, wie das passieren kann.
Du kannst das Feedback komplett berücksichtigen und die Veränderung am betrachteten Gegenstand umsetzen.
Manchmal willst du aber auch nur Teile des Feedbacks berücksichtigen oder Aspekte mehrerer Feedbacks kombinieren.
Und dann gibt es Feedback, bei dem du heute noch nicht sicher bist, wie und wann du darauf reagieren möchtest.
Solches Feedback solltest du als Backlog Item aufnehmen.

## Flight Level

Feedback Loops können auf drei verschiedenen Ebenen laufen:

* Strategische Ebene
* Taktische Ebene
* Operative Ebene

Die einfachsten und in der Regel schnellsten Feedback Loops findest du auf der operativen Ebene.
Diese Feedback Loops kannst du in den meisten Fällen allein mit deinem Team durchlaufen.
Feedback Loops auf der operativen Ebene helfen dir zu erkennen, wie gut dein Produkt Qualitätsmerkmale erfüllt.
Eine Daumenregel ist: wenn du ihn intern abbilden kannst, handelt es sich um einen Feedback Loop auf der operativen Ebene.

Auf der taktischen Ebene wird es spannend, denn hier kommt das Feedback von außerhalb deines Teams.
Die Feedback Loops auf dieser Ebene benötigen in den meisten Fällen Kontakt zu Kund:innen oder anderen Stakeholdern mit direktem Interesse an deinem Vorhaben.
Hier geht es nicht mehr darum, ob ein Qualitätsmerkmal erfüllt ist, sondern wie es aus Sicht deiner Nutzer:innen zu den anderen passt.

Die strategische Ebene beinhaltet die Feedback Loops, mit denen du den langfristigen Horizont im Auge behältst.
Hier geht es darum, ob die prinzipielle Ausrichtung stimmt, ob dein Business Model funktioniert und ob du bestimmte Nutzergruppen als Kunden gewinnen möchtest oder nicht.

Wenn du mit deinem Vorhaben startest, ist es wichtig, von Anfang an Feedback Loops auf allen drei Ebenen bewusst zu benutzen.
Häufig verlieren Product Owner die operative und die strategische Ebene zu schnell aus den Augen - weil sich das Team ums Operative kümmert und die Strategie im Tagesgeschäft zu selten betrachtet wird.
Erfolgreich wist du mit deinem Vorhaben aber nur sein können, wenn du auf allen drei Ebenen aktiv Feedback Loops nutzt.

<div markdown="1">
![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Feedback Loops können auf drei verschiedenen Flight Levels mit unterschiedlichen Feedbackgeber:innen laufen.
- Strategische Ebene: primär extern, Feedback von Stakeholdern oder durch Tests von Hypothesen zum Gesamtbild des Vorhabens
- Taktische Ebene: primär extern, Feedback von echten Nutzer:innen zu einem größeren Deliverable, das nicht mehr direkt beschrieben werden kann
- Operative Ebene: primär intern, Feedback zu einzelnen Qualitätsmerkmalen, die gut beschrieben werden können
</div>
{: .notice--primary}

## Latenz und Kadenz

Der Zeitbezug deines Feedback Loops wird durch *Latenz* und *Kadenz* beschrieben.

Die Latenz eines Feedback Loops bestimmt, wie lange es dauert, bis du nach dem Triggern des Feedback Loops das Feedback tatsächlich entgegennehmen kannst.

Die Kadenz eines Feedback Loops bestimmt, in welcher Frequenz du den Feedback Loop triggern kannst.

Latenz und Kadenz sind zwei völlig unabhängige Dimensionen.

Es gibt Feedback Loops, in denen du augenblicklich Feedback erhältst, die aber in großen Abständen getriggert werden.
Beispiele dafür sind der Sprint Review in Scrum oder die System Demo aus dem Scaled Agile Framework.

In anderen Fällen kannst du den Feedback Loop jederzeit triggern, erhältst das Feedback aber erst nach mehreren Wochen.
Ein Beispiel dafür sind Software-Lösungen, die dein Team via Continuous Delivery jederzeit ausliefern kann, die aber nicht direkt auf den Geräten der Nutzer:innen landen - vielleicht weil diese nur einmal pro Quartal ein Update erhalten.

Eine geringe Latenz ist nicht schlechter als eine hohe Latenz und eine niedrige Kadenz ist nicht schlechter ist eine hohe Kadenz.
Wichtig für dich ist, dass du weißt, mit welcher Latenz du in deinem Feedback Loop rechnen musst und mit welcher Kadenz du ihn triggern kannst.

<div markdown="1">
![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Der Zeitbezug von Feedback Loops drückt sich in einer Latenz und einer Kadenz aus:
- Latenz: Wie lange dauert es, bis ich nach dem Triggern des Feedback Loop Feedback erhalte?
- Kadenz: Wie häufig kann oder werde ich den Feedback Loop triggern?
</div>
{: .notice--primary}

Bei der Formulierung deiner Feedback Loops kannst du unser [Canvas für Feedback Loops]({{site.baseurl}}/assets/downloads/17-feedback-loop-canvas.pptx) nutzen.

{% include figure image_path="/assets/images/13-feedback-loop-canvas.png" alt="Feedback Loop Canvas von Gerrit Beine" caption="Feedback Loop Canvas von Gerrit Beine" %}

## Bewertung von Feedback Loops

* Welchen Nutzen ziehe ich aus einem Feedback Loop?
* Wann höre ich auf, bestimmte Feedback Loops zu nutzen?

**-- DRAFT --**
{: .notice--danger}

## Feedback Loops gestalten

### Den Gegenstand präsentieren

Es mag einfach klingen, aber die gut gemachte Präsentation des Gegenstands, zu dem du Feedback möchtest, ist eine Herausforderung.
Du solltest in der Lage sein, den Gegenstand abzugrenzen und klar zu benennen.
Dazu benötigst du hin und wieder etwas Abstand, denn als Product Owner kennst du viele Details, die dir den Blick verstellen können.

Auf keinen Fall solltest du den Gegenstand benennen oder beschreiben als:
* eine Liste von User Storys
* einen generischen Begriff wie "das Produkt"

Klar abgegrenzte Gegenstände, zu denen du nützliches Feedback erhalten kannst, sind:
* eine klare Visualisierung
* ein konkret benanntes Feature
* der Unterschied zur letzten Version deines Produkts

Es ist außerdem wichtig, dir bewusst zu machen, in welchem Kontext und Ambiente du den Gegenstand präsentierst.
Das beeinflusst stark, wie die Präsentation verläuft und hat damit Einfluss auf den Input.
Ob du in einem Meetingraum vor einem Lenkungsausschuss, auf einer Messe vor Kund:innen oder im Internet vor unbekannten Menschen präsentierst sollte ein deutlicher Unterschied sein.

![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Die mächtigste Möglichkeit, Input zu erhalten, besteht darin, andere Menschen den Gegenstand nutzen zu lassen.
{: .notice--primary}

### Input wahrnehmen

Unabhängig vor wem und wo du den Gegenstand präsentierst: du möchtest wissen, was die Menschen zu ihm zu sagen haben.
Manchmal erscheint dir das zu wenig, manchmal zu viel.
Deshalb musst du einen Weg finden, den Input wahrzunehmen.

Kontextabhängig kannst du dafür unterschiedliche Werkzeuge nutzen.
In einem Sprint Review kannst du ein Protokoll allen Inputs führen oder sie an einem Flipchart sammeln.
Auf einer Messe oder bei einer Präsentation im Internet wird das schon schwieriger.
Hier bieten sich Methoden wie Interviews, Fragebögen oder Foren an, über die du den Input wahrnehmen kannst.

Beachte: Je diffuser die Gruppe von Menschen ist, die dir Input gibt, desto schwieriger wird es, den Input wahrzunehmen.

![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Die wichtigste Regel beim Wahrnehmen von Input ist: sammle alles!
<br/><br/>
{: .notice--primary}

### Input interpretieren

Um Input zu interpretieren und das Rauschen vom wertvollen Feedback zu trennen, benötigst du die oben bereits erwähnte klare Vorstellung vom Gegenstand, zu dem du Feedback haben möchtest.

Die Differenzierung von Feedback und Rauschen erfordert einige Übung und ist kein wissenschaftlich exakter Vorgang.
Es gibt aber ein paar Heuristiken, die dir dabei helfen können, das wertvolle Feedback zu erkennen.

Input ist Feedback wenn:
* er den Unterschied zwischen einer Erwartung und dem Gegenstand benennt
* er ein neu identifiziertes Bedürfnis beschreibt, das ohne den Gegenstand nicht erkannt werden konnte
* er deutlich macht, dass der Gegenstand die Erwartungen erfüllt

Input ist Rauschen wenn:
* er unklar formuliert ist und in mehr als eine Richtung interpretiert werden kann
* er wenig handlungsleitend formuliert ist
* er nicht zum Gegenstand passt

Es ist hilfreich, wenn du die Interpretation der Rückmeldungen nicht allein machst, sondern dir eine:n Partner:in suchst.
Die Person sollte je nach betrachtetem Gegenstand passende Kenntnisse mitbringen.

![image-left]({{site.baseurl}}/assets/images/read-light-idea.png){: .align-left}
Dein Produkt entwickelt sich weiter:
Wenn ein Input heute Rauschen ist, kann es sein, dass der gleiche Input in einigen Wochen oder Monaten plötzlich Feedback ist, weil sich der Gegenstand verändert hat.
{: .notice--primary}

### Handlungen ableiten

Zu guter Letzt entscheidest Du, was du mit dem gesammelten Feedback anfangen möchtest.
Du wirst - wenn dein Gegenstand klar benannt ist - mehr wertvolles Feedback erhalten, als du umsetzen kannst.

Im Sinne eines guten Erwartungsmanagements solltest du deinen Feedbackgeber:innen transparent und zeitnah berichten, was du mit ihrem Feedback tun möchtest.
Je nach Kontext kannst du den Feedbackgebeer:innen sehr direkt antworten.
Zeige deinen Feedbackgeber:innen, wenn ihr Input zu direkten Veränderungen deines Produkts führen oder auch nur zu Backlog Items oder Einträgen auf einer Roadmap.

In jedem Fall ist es eine Motivation für deine Feedbackgeber:innen, wenn sie wissen, dass du ihr Input wertschätzt - auch wenn sie vielleicht nicht in dein Produkt einfließen.

Die Entscheidung, ein konkretes Feedback zu berücksichtigen oder nicht, ist die größte Macht und die größte Verantwortung, die du als Product Owner hast.
Mit dieser Entscheidung bestimmst du maßgeblich über die Weiterentwicklung deines Produkts, dein Verhältnis zu deinen Feedbackgebern und damit auch über den Erfolg deines Produkts.

## Downloads

* [Ein Canvas für Feedback Loops inkl. Hinweise als PDF]({{site.baseurl}}/assets/downloads/17-feedback-loop-canvas.pdf)
* [Ein Canvas für Feedback Loops inkl. Hinweise als .pptx]({{site.baseurl}}/assets/downloads/17-feedback-loop-canvas.pptx)

