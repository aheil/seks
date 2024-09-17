# Einheit 01: Komplexität

## Lernziele dieser Einheit

* Den Unterschied zwischen kompliziert und komplex **kennen lernen**
* **Verstehen**, was ein System ausmacht und welche unterschiedlichen Arten von Systemen es gibt
* Sie **verstehen** welche Ursachen es für organisatorische als auch technische Komplexität geben kann
* Sie **lernen kennen** welche Maßnahmen es gibt, um diesen Arten von Komplexität entgegen zu wirken

## Was ist ein komplexes System?

> Komplexe Systeme enthalten eine **Vielzahl von Komponenten**, die zusammenwirken und damit eine Funktionseinheit bilden. Dabei selbstorganisiert sich die »emergente« Funktion des Systems **ohne jede übergeordnete Kontrollinstanz**. - Forschungsperspektiven der Max-Planck-Gesellschaft, 2010, S. 56ff.

> Ein komplexes System trägt die **Anlage zur chaotischen Entartung** in sich. - Unbekannt

> Komplexe Systeme sind Systeme, welche sich der Vereinfachung verwehren und vielschichtig bleiben. - Wikipedia[^1]

***

## Ein Beispiel

Wenn Sie heute eine Single Page Application bestellen, kann es schnell passieren, dass Sie so etwas erhalten:

<figure><img src="../.gitbook/assets/seks.01.tech_stack.png" alt=""><figcaption><p>Beispiel Stackein "einfache" Anwendung</p></figcaption></figure>

***

## Definitorisches

* **Software Engineering**
  * Bekannt aus Grundlagen Software Engineering 1 + 2 Sommerville \[1], Balzert \[2,3]
* **komplexer**
  * Unterschied zwischen komplex und kompliziert?
* **Systeme**
  *   Ein System ist eine **Gesamtheit von Komponenten**, die so aufeinander bezogen oder miteinander verbunden sind und in einer Weise **interagieren**, dass sie als eine **aufgaben-, sinn-, oder zweckgebundene Einheit** angesehen werden können.



      <figure><img src="../.gitbook/assets/seks.01.system.png" alt=""><figcaption></figcaption></figure>

## Einfach vs. kompliziert vs. komplex

<figure><img src="../.gitbook/assets/seks.01.kompliziert-komplex.png" alt=""><figcaption><p>Abgrenzung von Einfach, kompliziert und komplex</p></figcaption></figure>

## Definitorisches - Software Engineering

* Software Engineering ist eine **empirische Disziplin**
  * Beruht auf **Beobachtungen und Erfahrungen**
* Weiterentwicklung des Software Engineering
  * Ist **durch die Praxis getrieben**
* Achtung!
  * Es gibt **in den meisten Fällen kein »Richtig« oder »Falsch«.**
  * Was in dem eine Projekt oder Team funktioniert, kann in einem anderen Projekt oder einem anderen Team Probleme verursachen
* Wahl der Methode, Architektur, Projektmanagement
  * Immer abhängig vom Kontext

## Wie entstehen komplexe Systeme?

Komplexe Systeme entstehen durch die Zusammenarbeit vieler Beteiligter, den Einsatz unterschiedlicher Technoligien über einen längeren Zeitraum.

<figure><img src="../.gitbook/assets/seks.01.idea.de.png" alt=""><figcaption><p>Entstehung komplexer Systeme</p></figcaption></figure>

## Merkmale organisatorischer Komplexität

* Anzahl Team Mitglieder
* Beziehungen zwischen Teammitgliedern
* Anzahl der Teams
* Interne vs. externe Teammitglieder
* Geographische Verteilung der Teammitglieder
* Interkulturelle Unterschiede
* Reputation des Projekts in der Organisation
* Anzahl Zulieferer und externer Firmen
* Kundenprojekt vs. Standard Software
* Beziehung zum Kunden
* Anzahl der Stakeholder
* Beziehung zu anderen Projekten

## Merkmale technischer Komplexität

* Art, Anzahl und Eindeutigkeit der Anforderungen
* Anzahl Komponenten und Schnittstellen
* Benutzer Interface
* Menge und Art der Daten
* Code Basis (Lines of Code)
* Brownfield vs. Greenfield Projekt
* Legacy Code
* Bekannte vs. neue Technologien
* Anzahl Programmiersprachen
* Verteilte Systeme
* Parallelität im Code
* Security

## Anmerkung zu organisatorischen Systemen

In organisatorischen Systemen existieren **offizielle Beziehungen**

* Projektmanager gibt Inhalte dem Team vor
* Teamleiter ist disziplinarisch Vorgesetzter
* Entwicklungsleiter ist fachlicher Entscheidungsträger
* Projektleiter gibt Termine vor
* Entwickler entscheiden über Code

Und es gibt **inoffizielle Beziehungen**

* Teamleiter ist mit einem Teammitglied im gleichen Fußballverein
* Entwicklungsleiter „kann nicht“ mit Entwickler A
* Entwickler B ist bester Freund von Entwickler C
* Externer Berater ist Bruder des Schwagers von Entwickler D

## Wie also Komplexität in den Griff bekommen?

**Organisatorische** Komplexität reduzieren

* Projektmanagement
* Vorgehensmodelle
* Schätzen und Schätztechniken
* Anforderungsanalyse

**Technische** Komplexität reduzieren

* Software Architekturen
* Code Metriken
* Testen
* Test Driven Development
* Clean Code

##

## Beispielvideos&#x20;

Bei den Videos ist es erlaub "out-of-the-box" zu denken. Hier einige sehr gut gelungene Beispiele aus vorherigen Kursen:

{% embed url="https://youtu.be/d81UadVzEEk?si=nCyteo_fo5O0H-Sw" %}
Rootkits (SoSe 23)
{% endembed %}

{% embed url="https://youtu.be/6ZGG2hruA9c?si=hhG4h26t0CcKGRl3" %}
Go Programmierung (WiSe 23)
{% endembed %}

## Referenzen

\[1] I. Sommerville, Software Engineering, Pearson, 2018&#x20;

\[2] I. Sommerville, Modernes Software-Engineering: Entwurf und Entwicklung von Softwareprodukten, Pearson, 2020&#x20;

\[3] H. Balzert, Lehrbuch der Softwaretechnik: Entwurf, Implementierung, Installation und Betrieb, Spektrum Akademischer Verlag, 2011

[^1]: https://de.wikipedia.org/wiki/Komplexes\_System
