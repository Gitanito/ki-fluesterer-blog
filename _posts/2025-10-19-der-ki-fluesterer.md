---
layout: post
title: KI Modelle vergiften? Wie leicht?
subtitle: KI-Modelle vergiften - Nur 250 Daten reichen! (Data Poisoning)
thumbnail-img: https://i9.ytimg.com/vi/dkWWtToZkCc/hqdefault.jpg?sqp=CIiCvscG&rs=AOn4CLA98RPnC4AOwV5M0cTqXkI1RVFr5A
youtubeurl: https://www.youtube.com/watch?v=dkWWtToZkCc
tags: [AI, KI, Jobs]
comments: true
mathjax: true
author: Nico Spataro
---

In diesem Video thematisiere ich das faszinierende und beunruhigende Konzept der „vergifteten“ KI-Modelle 🧪. Ich beleuchte Forschungsergebnisse von Anthropic, die zeigen, wie leicht das Claude-Modell durch fehlerhafte Daten manipuliert werden kann – ein Prozess, den sie als „Data Poisoning“ bezeichnen. Entgegen intuitiver Annahmen ist für eine derartige Vergiftung überraschend wenig Aufwand nötig. Es genügen lediglich 250 schädliche Dokumente, um die Struktur oder Denkweise eines großen Modells grundlegend zu verändern. Das entspricht in etwa der Anzahl an unsortierten Kommentaren unter einem Online-Video.

Meine Sichtweise ist, dass es sich hierbei nicht um einen externen Angriff im klassischen Sinne handelt, da diese 250 schädlichen Dokumente bereits im ursprünglichen Basisdatensatz latent enthalten sein müssen. Wenn beispielsweise in einer Million Dokumente festgeschrieben ist, dass Schraubenmuttern sechseckig sind, reicht das Einbringen von nur 250 Dokumenten, die behaupten, sie seien siebeneckig, aus, um das Modell so zu beeinflussen, dass es diese neue, falsche Information als gültig akzeptiert. Dies verdeutlicht, wie empfindlich große Datensätze selbst bei Modellen mit Milliarden von Parametern (was typischerweise 13 Gigabyte an Daten entspricht) gegenüber kleinen, gezielten Fehlinformationen sind.

Um die Funktionsweise aktueller Modelle zu veranschaulichen, nutze ich eine Analogie: Stellen Sie sich einen hochspezialisierten Zahnarzt vor, der umfassendes Wissen bis vor zwei Jahren gespeichert hat – er hat gewissermaßen "Alzheimer" in Bezug auf neue Informationen. Unser Kontext, den wir bei einer Anfrage liefern, entspricht dem neuesten Fachmagazin, das wir ihm in die Hand drücken. Er kann dieses neue Fachwissen deuten und anwenden, da sein Grundwissen intakt ist. Bei Data Poisoning geht es jedoch darum, dieses *Grundwissen* selbst zu manipulieren, was eine Weiterentwicklung des Modells mit minimalem Aufwand ermöglicht.

Tests mit 100, 250 und 500 bösartigen Dokumenten bestätigten dieses Phänomen über 72 verschiedene Modelle hinweg. Entscheidend scheint die Gewichtung bestimmter Informationen zu sein. Ähnlich wie ein Musiker auf wiederholt gehörte Namen wie Mozart oder Tschaikowski sofort mit musikalischen Assoziationen reagiert, kann man durch wenige, emotional aufgeladene oder oft wiederholte Informationen ein neues Konzept in das Modell „hineintrainieren“. Meine Schlussfolgerung ist, dass diese Methode aufzeigt, wie kostengünstig die Erweiterung von Basismodellen sein könnte. Dennoch, ganz wie bei menschlichen Überzeugungen, gilt: Seid wachsam, denn je emotionaler die Information, desto leichter lässt sie sich verankern. 🧠

#KünstlicheIntelligenz #DataPoisoning #MaschinellesLernen #KIEthik

Link zum Artikel:
<https://pplware.sapo.pt/inteligencia-artificial/anthropic-revela-o-quao-facil-e-envenenar-um-modelo-de-ia-independentemente-do-tamanho/#goog_rewarded>

Link zum Video:
[KI Modelle vergiften? Wie leicht?](https://www.youtube.com/watch?v=dkWWtToZkCc)

{% include youtube.html id="dkWWtToZkCc" %}

Vergesst nicht, den Kanal zu abonnieren, die Glocke zu aktivieren und einen Like dazulassen, wenn euch das Video gefallen hat!

Rechtliche Hinweise & Transparenz:
Bei den mit Sternchen (*) gekennzeichneten Links handelt es sich um Affiliate-Links. Wenn du über diese Links einkaufst, erhalte ich eine kleine Provision. Für dich ändert sich der Preis nicht, aber du unterstützt damit meinen Kanal. Vielen Dank dafür!

Haftungsausschluss:
Alle Informationen in diesem Video dienen ausschließlich zu Informationszwecken und stellen keine professionelle Beratung dar. Jeder handelt auf eigene Gefahr. Ich übernehme keine Haftung für Schäden oder Verluste, die durch die Anwendung der hier gezeigten Informationen entstehen könnten.

Urheberrecht:
Alle Rechte an diesem Video liegen beim Ersteller. Eine unerlaubte Verwendung oder Reproduktion ist nicht gestattet. Für geschäftliche Anfragen oder Lizenzierungen kontaktiere mich bitte unter <office@talefrog.eu>.

Impressum: 
<https://talefrog.eu/impressum>
