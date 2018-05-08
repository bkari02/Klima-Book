---
description: Hier wird dir erklärt wie du Daten vom Datenlogger ausliest.
---

# Daten auslesen

Um Daten vom Datenlogger auszulesen müsst Ihr den Logger mit einem Laptop verbinden. Allerdings braucht der Laptop die Software "LoggerNet", daher wird dem Kurs ein Laptop zur Verfügung gestellt. Diesen könnt Ihr entweder bei Carsten Schaller oder Bastian Paas im Büro abholen.

Um den Laptop mit dem Logger zu verbinden braucht Ihr ein Patchkabel. Das kennen die meisten unter den Begriffen "Netzwerkkabel" oder "LAN-Kabel", da es benutzt wird wenn Ihr euren PC per Kabel ans Internet anschließt. 

![Patchkabel fuer Verbindung zwischen Datenlogger und Laptop](.gitbook/assets/patchcable_black_20m.jpg)

Wenn ihr den Datenlogger und den Laptop verbunden habt könnt ihr auch schon mit Daten auslesen loslegen. 

Dazu öffnet ihr das Programm **LoggerNet**. Ihr bekommt eine Menü-Übersicht in der ihr mehrere Optionen zur Auswahl habt. Unter dem Menüpunkt **Main **klickt ihr nun auf **Connect.**

![Benutzeroberfl&#xE4;che LoggerNet](.gitbook/assets/gui.PNG)

Im Anschluss daran sollte sich ein neues Fenster öffnen, der **Connect Screen**. 

![](.gitbook/assets/connect.PNG)



Klickt nun oben links auf **Connect **und stellt sicher das bei den **Stations** _CR3000 _und **nicht** _CR3000\_Seriell _ausgewählt ist. Der Logger sollte nun verbunden sein.

{% hint style="info" %}
Sollten Probleme auftreten bei der Verbindung schaue auf die [Hilfe ](hilfe.md#was-mache-ich-wenn-sich-der-laptop-nicht-mit-dem-logger-verbinden-laesst)Seite.
{% endhint %}

Überprüft nun, ob rechts bei _Clocks_ die _Adjusted Server Date/Time_ und die _Station Date/Time_ übereinstimmen. 

{% hint style="warning" %}
Sollten die Zeiten mehr als 3 Minuten auseinanderliegen meldet euch bitte **direkt telefonisch** [hier](hilfe.md#wo-melde-ich-mich-wenn-es-ein-problem-gibt).
{% endhint %}

Jetzt klickt ihr auf **Num\_Display** und wählt **Display 1** aus.

![](.gitbook/assets/num_neu%20%281%29.png)

Hier findet ihr die Ausgabe der live gemessenen Werte. 

![](.gitbook/assets/log.PNG)

Überprüft nun, mit der unten stehenden Tabelle, ob die Werte Sinnvoll und somit auch im Toleranzbereich liegen 

## Toleranzbereiche der Messwerte 

| Temperatur in Kelvin |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Temperatur in Celsius |  |
| Langwellig |  |
| Kurzwellig  |  |
| Lufttemperatur |  |
| Luftdruck |  |
| Luftfeuchtigkeit  |  |
| Windgeschwindigkeit  |  |
| Windrichtung  |  |
| Niederschlagsmenge  |  |

{% hint style="info" %}
Stimmt etwas nicht mit den Werten, dann schaut in der [Hilfe](hilfe.md#was-mache-ich-wenn-die-werte-eines-sensors-unsinnig-sind-oder-gar-nicht-gemessen-werden) nach, was ihr tun könnt.
{% endhint %}

An die vom Logger intern gespeicherten Werte kommt ihr nun mit folgenden Schritten. Schließt oder minimiert das Fenster mit den Ausgabewerten. Jetzt klickt ihr im **Connect Screen** auf **File Control**. Es öffnet sich folgendes Fenster: 

![](.gitbook/assets/bildschirmfoto-zu-2018-05-03-16-29-49.png)

Stellt als erstes sicher, dass links **CRD** ausgewählt ist und klickt im Anschluss oben auf **Refresh. **Wählt nun den Datensatz mit dem _Datum vom Vortag_ aus und klickt dann auf **Retrieve**. 

Navigiert nun auf _Desktop_ und dann zum Ordner _U\_Klima\_SS18\_A _und klickt auf **Speichern**_. _

![](.gitbook/assets/file4.PNG)

Überprüft am besten noch einmal ob eurer Datensatz auch wirklich in dem Ordner gespeichert wurde.  
Befindet sich der Datensatz nun im richtigen Ordner, seid ihr mit dem Auslesen der Daten fertig. Ihr könnt nun alle Fenster schließen.

{% hint style="info" %}
Schaut euch bitte noch kurz den Niederschlagssensor an und stellt sicher, dass die Kippwage nicht verstopft ist.
{% endhint %}



