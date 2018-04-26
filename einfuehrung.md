---
description: Hier findet ihr eine kleine Einfuehrung in den Datenlogger.
---

# Einfuehrung

## Datenlogger?

> Was ist eigentlich ein Datenlogger?

Falls ihr das nicht mehr so ganz auf dem Schirm habt hier einmal eine kurze Einfuehrung:

Der Datenlogger empfaengt die Signale der Sensoren. Er zeichnet diese auf und kann sie euch anzeigen. Dazu muss der Datenlogger mit einem Programm bespielt werden, dass ihm sagt auf welchen Anschluessen er welche Art von Signale gesendet bekommt und wie er diese zu verarbeiten hat. 

Man kann z.B. den zeitlichen Abstand in dem gemessen werden soll einstellen \(pro Sekunde, pro Minute, pro Stunde, usw.\). Doch damit nicht genug, der Datenlogger speichert nicht nur die einzelnen Messungen, sondern kann diese auch schon vorverarbeiten.   
Er kann z.B. 10-Minuten-Mittel bilden, was bedeutet, dass er die Werte aus den letzten 10 Minuten jeweils zusammenrechnet und einen Wert fuer jedes 10-Minuten-Intervall speichert. Der Wert kann das arithmetische Mittel der Werte aus dem Intervall sein oder auch die Summe aller Werte, das kommt ganz drauf an wie die Berechnung im Programm definiert ist. Wie sinnvoll so etwas ist muss sich der Klimatologe natuerlich selbst ueberlegen. Handelt es sich bspw. um das Phaenomen Niederschlag macht es Sinn die Werte zu addieren und so die Niederschlagsmenge ueber 10 Minuten zu erhalten, geht es aber um das Phaenomen Temperatur macht eine Addition keinen Sinn. In diesem Fall sollte man das arithmetische Mittel bilden und so die gemittelte Temperatur ueber 10 Minuten zu erhalten.

> Soviel zum Datenlogger an sich, aber muss ich jetzt selber programmieren?

Nein, programmieren muss du nicht selbst. Das wurde alles schon im Vorhinein erledigt und das Programm wurde auf den Datenlogger gespielt. Deine Aufgabe ist es, die Daten vom Datenlogger auszulesen, zu ueberpruefen ob alles in Ordnung ist und die Daten zu sichern. Um dir das noetige Wissen dazu zu vermitteln ist dieses Tutorial da.



