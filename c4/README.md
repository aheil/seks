# C4 Software Dokumentation

##

## Lernziele

**Probleme** bei der Dokumentation von Software-Architekturen **verstehen**&#x20;

Die **vier Ebenen** des C4-Models **kennen**

Das C4 Modell auf Problemstellungen **anwenden können**

Software-Architekturen mit Hilfe des C4-Models **dokumentieren und kommunizieren können**

## Probleme bei der Dokumentation

Welches ist die beste/einfachste/verständlichste Art Software-Architekturen zu dokumentieren

So? Schnell und einfach aber klar und verständlich?

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Quelle: http://c4model.com/</p></figcaption></figure>

Besser so? Formal ja, aber genügend Detailgrad und unmißverständlich?

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

Noch besser so? Formal ja, mehr Detailgrad, aber genug Implementierungsetails? Was bedeuten die Pfeile?

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Oder seher so? Autoamtisiert ja, aber klar und verständlich?&#x20;

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Vielleicht aber doch so:&#x20;

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Twitter Architektur Zeichnung von Elon Musk, annotiert von Justin Hendrix, Luke Dubois and Mark Hansen. Original Miro board: <a href="https://miro.com/app/board/uXjVPBnTJmM=/">https://miro.com/app/board/uXjVPBnTJmM=/</a></p></figcaption></figure>

Ganz oft dann aber auch so, weil einfach und handhabbar und nicht formal:&#x20;

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

**Problem formaler Methoden**: Diese sind "synthetisch" und müssen gelernt werden. Sie müssen von beiden Seiten verstande n werden. Daher einigt man ich meistens pragmatisch auf die Ebene, die beide Seiten verstehen.&#x20;

## Motivation

Visuelle Kommunikation im Baugewerbe: Hier gibt es Lageplane, Raumpläne, Bebauungspläne, Querschnittsansichten, detaillierte Standardzeichnungen und technische Zeichnungen, die von den ausführenden Gewerken in der Regel ohne Probleme gelsen und (fehlerfrei) umgesetzt werden können.&#x20;



<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Querschnittsansicht</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Raumplan</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Elektroninstallation</p></figcaption></figure>

Wie sieht hingegen die Kommunikation in Software-Projekten aus?&#x20;

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

* Durcheinander von Boxen und Linien&#x20;
* Inkonsistente Notationen, Farben, Formen und Linien&#x20;
* Mehrdeutige Bezeichnungen
* Beziehungen nicht benannt
* Fehlende Technologieentscheidungen und Details
* Vermischte Abstraktionslevel

Aufgrund der Bewegung hin zu agilen Methoden wird weniger "Up Front Design" durchgeführt und es finden sich weniger Software-Diagramme in agilen Projekten.&#x20;

Wenn Diagramme genutzt werden sind diese oftmals&#x20;

* Unklar
* Mehrdeutig
* Verwirrend
* und haben vermischte Detailgrade

## C4 Modell&#x20;

Das [C4 Modell](https://c4model.com) nutzt so.g Code-Landkarten zum verschiedene Sichten (Detaillevel) auf eine Software-Architektur zu modellieren. Jede Sicht kann für einen ganz unterschiedlichen Zweck und eine unterschiedliche Zielgruppe genutzt werden.

**Context**

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Bildquelle https://maps.google.com</p></figcaption></figure>

In welchem Gesamtkontext befindet sich das System, an welche externen Systeme grenzt es an?&#x20;

Das Kontextdiagram beschreibt das Big Picture. Wie passen die Teile in den Gesamtkontext?&#x20;

**Container**

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption><p>Bildquelle https://maps.google.com</p></figcaption></figure>

Aus welchen Bestandeilen besteht das System. Im C4 Model sind hierbei Einheiten beschrieben, die Code hosten. Es kann sich dabei z.B. um auch einen Appliation Server handeln.

**Component**

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption><p>Bildquelle https://maps.google.com</p></figcaption></figure>

Wie sind die einzelnen Bestandteile aufgebaut. In der Regel sind dies Gruppen von zusammengehörigen Funktionen, die hinter einer wohldefinierten Schnittstelle verborgen sind.

**Code**

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p>Bildquelle Peter Schmelzle - Self-photographed, CC BY-SA 3.0</p></figcaption></figure>

Wie sehen die Bestandtiel des Systems im Detil aus. Hier werden Klassen, Schnittstelle, Objekte, Funktionen, Tabellen etc. innerhalb einer Komponente beschrieben.

Das C4 Model ist gedacht, um Software-Architekturen zu modellieren und zu kommunizieren. Es unterstützt einen “Abstraction First“ Ansatz und reflektiert die Denkweise von Entwicklern und Software-Architekten&#x20;

Es ist auch geeignet um Architekturen “Up Front” oder im Nachhinein zu dokumentieren.&#x20;



## C4 Metamodell

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption><p>C4 Sichten</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Elemente und Bezeiheungen</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption><p>Diagrammelemente</p></figcaption></figure>

## Level 1: System Context Diagram

* Scope: Ein einzelnes Software System Primäre&#x20;
* Elemente: Das im Scope befindliche Software System Unterstützende&#x20;
* Elemente: Personen und Software Systeme, die direkt mit dem im Scope befindlichen Software System in Verbindung&#x20;
* Zielgruppe: Technische und nicht-technische Personen innerhalb und außerhalb des Entwicklungs-Teams

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

## Level 2: Container Diagram

* Scope: Ein einzelnes Software System Primäre&#x20;
* Elemente: Der im Scope befindliche Container Unterstützende Elemente: Personen und Software System, die mit dem im Scope befindlichen Container in Verbindung stehen&#x20;
* Zielgruppe: Technische Personen innerhalb und außerhalb des Software Entwicklungs-Teams; einschließlich Software Architekten, Entwickler und Betriebs- und Supportpersonal #
* Hinweis: Container Diagramme treffen keine Aussage über die Deployment Szenarien, eventuelles Clustering, Replikations- und/oder Failover-Szenarien etc.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

## Level 3: Component Diagram&#x20;

* Scope: Ein einzelner Container Primäre Elemente: Komponenten innerhalbs des im Scope befindlichen Containers Unterstützende&#x20;
* Elemente: Containers (innerhalb des im Scope befindlichen Software Systems) + Personen und Software Systeme, die direkt mit den Komponenten in Verbindung stehen&#x20;
* Zielgruppe: Software Architekten and Entwickler

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

## Level 4 Code Diagram

* Scope: Eine einzelne Komponente Primäre Elemente: Code&#x20;
* Elemente (z.B. Klassen, Interfaces, Objekte, Methoden und Funktionen, Datenbanken und Tabellen etc.) innerhalb der im Scope befindlichen Komponente&#x20;
* Zielgruppe: Software-Architekten und Entwickler

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

## Zusätzliche Diagramme

Die 4 Level sind nicht immer ausreichend Wo nötig mit Komplementären ergänzen. Beispiele hierfür sind:

* Systemlandschaft: In der echten Welt sind Software Systeme schon lange nicht mehr voneinander isolier und zeigen z.B. wie Systeme innerhalb eines Unternehmen zusammenspielen&#x20;
* Dynamische Diagramme: UML Kollaborationsdiagramme, UML Sequenzdiagamme&#x20;
* Deployment Diagramme: UML Deployment Diagramme einschließlich Containers and Deployment Nodes

## Praxisbeispiel

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption><p>Quelle: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/scalable-web-app</p></figcaption></figure>

Anhand der Microsoft Referenz Architektur für Microsoft Azure App Service ist es schwer, die exkaten Komponenten und das Zusammenspiel der Systembestandteile zu verstehen und letztendlich umzusetzen.

Anhand eines Level 2 Diagrams lässt sich dies wesentlich klarer ausdrücken:&#x20;

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption><p>Quelle: https://azure-development.com/1918/09/11/save-the-world-from-powerpoint-cloud-solution-architects/</p></figcaption></figure>
