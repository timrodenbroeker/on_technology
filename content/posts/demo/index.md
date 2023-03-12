---
title: "Demo"
date: 2022-08-23T09:20:58+02:00
tags:
categories:
draft: true
featured_image: /images/demosw.gif
---

Das Design in Motion Festival in den Niederlanden ist ein einzigartiges Event. Anfang Oktober 2022 werden für 24 Stunden so gut wie alle Displays im öffentlichen Raum in den Niederlanden künstlerische Arbeiten von Designern aus der ganzen Welt zeigen. So wird der public space zu einer landesweiten, gigantischen Ausstellung, die sich der vorhandenen Infrastruktur in Flughäfen, Bahnhöfen, Einkaufszentren, auf Plätzen und auf Autobahnen bedient. Die Initiatoren, die bekannte Designagentur "Studio Dumbar" aus Rotterdam, haben dafür alle großen Betreiber von Out of Home Displays an einen Tisch bekommen und diese technische Mammutaufgabe zu bewältigen. 

Ich hatte dieses Jahr die Ehre, Teil des Kuratorinnenteams des DEMO-Festivals sein zu dürfen. Gemeinsam mit Liza Enebels, Connor Campbell, YONK und Koos Breen habe ich mich im Juli 2022 im Büro von Studio Dumbar im DEPT-office in Rotterdam getroffen, um an zwei intensiven tagen aus insgesamt 3600 zehnsekündigen Clips die besten auszuwählen. Das war sehr anstrengend aber total inspirierend. 

Ich wollte mir die Chance nicht entgehen lassen, auch selbst eine Serie einzureichen, die auf dem Festival gezeigt werden soll. Da ich am Tag des DEMO-Festivals auch einen kurzen Vortrag halten soll, habe ich mich entschieden, mal genau zu erklären, welche Gedanken und Ideen hinter der von mir eingereichten Serie steckt. Darum soll es hier gehen. 

Alle drei Videos haben ein Seitenverhältnis von 9:16 und zeigen jeweils eine Variante eines generativen Rasters aus fotografischen Fragmenten und geometrischen Formen. Zur Zeit der Planung des DEMO-Festivals habe ich mich intensiv mit Rastern beschäftigt, da ich zum Einen an meinem Kurs "Interactive Grid Systems" arbeitete, zum Anderen, weil ich im intensiven Austausch mit Martin Lorenz stehe, der in seinem Buch "Flexible Visual Systrems" eine Methodik zur Gestaltung von dynamischen Rastersystemen für visuelle Identitäten beschreibt. Das Buch kann ich absolut empfehlen!



## Komposition

Die Motive sind kaleidoskopartig gespiegelt, so dass jede Animation aus vier gleichen Teilen besteht. Durch diese regelmäßige Wiederholung entsteht eine symmetrische Ordnung und ein Fokus auf das Zentrum der Komposition. 



## Programm

Alle Animationen basieren auf einem in Processing entwickelten Programm. Der Algorithmus des Programms funktioniert folgendermaßen. 

Es gibt eine vordefinierte Auswahl von Komponenten, die in jeder Rasterzelle angezeigt werden können. Dies können Ausschnitte aus einem Foto oder eine gelb eingefärbte geometrische Form sein. Jede Komponente hat eine festgelegte Nummer. Beispiel: Die Zahl 1 zum Beispiel für einen Ausschnitt aus woman.jpg und 2 für einen Ausschnitt aus athens.jpg, die Zahl 3 für ein gelbes Dreieck. 

Das Programm verfügt über eine unsichtbare Tabelle aus Zahlen. Diese repräsentieren das sichtbare Raster und legen fest, welche Komponenten, also entweder ein bestimmtes Foto, oder eine geometrische Form, angezeigt werden soll. 

```
0 0 0 0
0 0 0 0
0 0 0 0
0 0 0 0
```

Jedes Mal, wenn ein neuer Frame in der Animaton angezeigt werden soll, in diesem Fall 10 Mal in der Sekunde, wird eine Entscheidung getroffen, nämlich welche der Zahlen in der Tabelle um den Wert 1 erhöht werden soll. Nach dem ersten Durchlauf des Programms sieht die Tabelle dann vielleicht so aus:

```
0 0 0 0
0 0 0 0
0 1 0 0
0 0 0 0
```

Hier wurde die Zahl 0 in der dritten Zeile und der zweiten Reihe um 1 erhöht. Wenn der Algotithmus dann mehrfach ausgeführt wurde, ergibt sich ein chaotisches Raster aus Zahlen. 

```
4 2 0 1
0 1 2 0
0 5 1 1
3 0 3 0
```

Jede dieser Zahlen steht für eine bestimmte Kachel im Raster und je nach Wert wird dann ein bestimmtes Motiv, bzw. eine Komponente angezeigt. Das ganz läuft natürlich irrsinnig schnell, so dass man nur schwer erkennen kann, was da vor sich geht. 



## Bildmotive

Auch wenn die Bildmotive nicht gut zu erkennen sind, haben sie doch vermutlich großen Einfluss auf die Wirkung der Animationen. Deshalb würde ich gern kurz etwas zur Auswahl meiner Bildvorlagen sagen. 

Ich pflege seit vielen Jahren ein großes Archiv aus verschiedensten Fotografien, die ich im Internet gefunden habe. Kriterium um in dieses Archiv zu kommen ist, dass das Bild in der so genannten Public Domain liegt, das bedeutet, dass der Urheber mindestens 70 Jahre tot ist. Das Recht der Public Domain kann je nach Land leicht abweichen, aber grundsätzlich ist es so, dass es Archive im Internet gibt, die Bilder aktiv als Public Domain markieren und auf die freie Verwendbarkeit  hinweisen. Das ist großartig, denn so können wir uns an einem gigantischen Schatz an interessanten und aussagekräftigen Bildmotiven bedienen, die wir für unsere eigene Arbeit nutzen können. 

Neben meinem großen Archivordner auf meiner Festplatte habe ich noch einen zweiten, den ich "selection" nenne. Darin speichere eine streng kuratierte Auswahl der Motive, die ich für meine experimentelle Arbeit nutze. Darin finden sich Abbildungen von Bauwerken, Portraits von Personen  des öffentlichen Lebens, frühe Fotgrammme, Bilder der NASA, Abbildungern von Skulpturen und auch Malereien. Am liebsten nutze ich das Online-Archiv des Metropolitan Museum of Art oder Wikimedia Commons für meine Bildrecherchen, die klar und deutlich die Lizenz des jeweilige Werkes auszeichnen. Für mich ist es extrem wichtig, dass das Bild lupenrein geklärt ist.



## Farbigkeit

In meiner experimentellen Arbeit beschränke ich mich bei Fotografien konsequent auf eine schwarz-weisse Farbigkeit. Dafür gibt es einige Gründe. 

- Alte Fotos in der Public Domain sind in der Regel Schwarz Weiss
- Bildserien wirken köhärent und zusammengehörig
- Die symbolische Bildwirkung wird verstärkt
- Motive werden leicht verfremdet und bekommen etwas geheimnisvolles
- Der Eindruck von Zeitlosigkeit entsteht 

Da ich bei der Entwicklung meiner Lehnmaterialien keinen Auftraggeber habe, der mir ein Farbschema vorgibt, hat sich meine Farbsystematik mit Schwarzweissen Fotografien und geometrischen, so wie typografischen Elementen in RGB-Reintönen zu einer Art visueller Identität  entwickelt. Dieses Regelwerk ermöglicht es mir, effizient zu arbeiten und wiedererkannt zu werden. 



## Wrapping Up

Ich bin sehr zufrieden mit der Serie. Sie wirkt interessant, nutzt und zeigt die Vorzüge der programmierten Gestaltung, hat ein stark reduziertes Farbschema und wirkt nicht zu technisch. Ich bin sehr gespannt wie die Arbeiten im öffentlichen Raum wirken und freue mich sehr auf das Event und natürlich auch meinen Vortrag im Oktober!

