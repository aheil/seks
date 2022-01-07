---
layout: slide
title: Komplexität
---

## Software Engineering komplexer Systeme
### Einheit 01: Komplexität

Prof. Dr.-Ing. Andreas Heil

<small>Dieses Werk ist lizensiert unter einer [Creative Commons Namensnennung 4.0 International Lizenz](http://creativecommons.org/licenses/by/4.0/).</small>

<small>v.1.2<small>

---

### Lernziele dieser Einheit

* Sie lernen den Unterschied zwischen *kompliziert* und *komplex* **kennen**

* Sie **verstehen**, was ein System ausmacht und welche unterschiedlichen Arten von Systemen es gibt

---
### Lernziele dieser Einheit (Forts.)

* Sie **verstehen** welche Ursachen es für organisatorische als auch technische Komplexität geben kann
* Sie **lernen kennen** welche Maßnahmen es gibt, um diesen Arten von Komplexität entgegen zu wirken

---

## Teil 1: Einführung

---

### Was ist ein komplexes System?

> Komplexe Systeme enthalten eine **Vielzahl von Komponenten**, die zusammenwirken und damit eine Funktionseinheit bilden. Dabei selbstorganisiert sich die »emergente« Funktion des Systems **ohne jede übergeordnete Kontrollinstanz**. 

<p align="right">
<small>Forschungsperspektiven der Max-Planck-Gesellschaft, 2010, S. 56ff.</small>
</p>

---

### Was ist ein komplexes System?


> Komplexe Systeme sind Systeme, welche sich der Vereinfachung verwehren und vielschichtig bleiben.

<p align="right">
<small><a href="https://de.wikipedia.org/wiki/Komplexes_System">Wikipedia</a></small>
</p>

---

### Was ist ein komplexes System? 

> Ein komplexes System trägt die **Anlage zur chaotischen Entartung** in sich.

<p align="right">
<small>Unbekannt</small>
</p>

---

### Ein Beispiel 

Wenn Sie heute eine Single Page Application bestellen, kann es durchaus passieren, dass Sie so etwas erhalten: 

![](../../img/slides/komplexitaet/tech_stack.png)

---

## Teil 2: Definitorisches

---

### Definitorisches: Software Engineering

* Software Engineering ist eine empirische Disziplin
    * Beruht auf Beobachtungen und Erfahrungen 
* Weiterentwicklung des Software Engineerings 
    * Ist durch die Praxis getrieben

---

### Hinweis 

* Es gibt in den meisten Fällen kein »Richtig« oder »Falsch«
* Was in dem eine Projekt oder Team funktioniert, kann in einem anderen Projekt oder einem anderen Team Probleme verursachen 
* Wahl der Methode, Architektur, Projektmanagement etc. ist immer abhängig vom Kontext

---

### Definitorisches: Einfach - Kompliziert - Komplex
![](../../img/slides/komplexitaet/def_komplex.png)

---

### Definitorisches: System

Ein System ist eine **Gesamtheit von Komponenten**, die so aufeinander bezogen oder miteinander verbunden sind und in einer Weise **interagieren**, dass sie als eine **aufgaben-, sinn-, oder zweckgebundene Einheit** angesehen werden können.  

---

### Systeme

![](../../img/slides/komplexitaet/systeme.png)

---

## Teil 3: Entstehung von Komplexität 

---

### Wie entstehen komplexe Systeme?

![](../../img/slides/komplexitaet/idee.png)


---

### Merkmale organisatorischer Komplexität 

* Anzahl Team Mitglieder
* Beziehungen zwischen Teammitgliedern
* Anzahl der Teams
* Interne vs. externe Teammitglieder
* Geographische Verteilung der Teammitglieder
* Interkulturelle Unterschiede

---

### Merkmale organisatorischer Komplexität (Forts.)

* Reputation des Projekts in der Organisation
* Anzahl Zulieferer und externer Firmen
* Kundenprojekt vs. Standard Software
* Beziehung zum Kunden
* Anzahl der Stakeholder
* Beziehung zu anderen Projekten

---

### Merkmale technischer Komplexität 

* Art, Anzahl und Eindeutigkeit der Anforderungen
* Anzahl Komponenten und Schnittstellen
* Benutzer Interface
* Menge und Art der Daten
* Code Basis (Lines of Code)

---

### Merkmale technischer Komplexität (Forts.)

* Brownfield vs. Greenfield Projekt
* Legacy Code
* Bekannte vs. neue Technologien
* Anzahl Programmiersprachen
* Verteilte Systeme
* Parallelität im Code
* Security

---

### Anmerkung zu organisatorischen Systemen

In organisatorischen Systemen existieren **offizielle Beziehungen**
* Projektmanager gibt Inhalte dem Team vor
* Teamleiter ist disziplinarisch Vorgesetzter
* Entwicklungsleiter ist fachlicher Entscheidungsträger
* Projektleiter gibt Termine vor
* Entwickler entscheiden über Code

---

### Anmerkung zu organisatorischen Systemen (Forts.)

Und es gibt **inoffizielle Beziehungen**

* Teamleiter ist mit einem Teammitglied im gleichen Fußballverein
* Entwicklungsleiter „kann nicht“ mit Entwickler A
* Entwickler B ist bester Freund von Entwickler C
* Externer Berater ist Bruder des Schwagers von Entwickler D

---

### Wie also Komplexität in den Griff bekommen?

**Organisatorische** Komplexität reduzieren
* Projektmanagement
* Vorgehensmodelle
* Schätzen und Schätztechniken
* Anforderungsanalyse

---

### Wie also Komplexität in den Griff bekommen? (Forts.)

**Technische** Komplexität reduzieren
* Software Architekturen
* Code Metriken
* Testen
* Clean Code

