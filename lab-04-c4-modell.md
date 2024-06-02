---
description: >-
  Das C4-Modell ermöglicht es einfach und unkompliziert die Architektur einer
  Software zu kommunizieren. In dieser Übung werden Sie ein C4-Modell mit
  PlantUML und der C4-PlantUML-Erweiterung erstellen.
---

# Lab 04: C4 Modell

## Vorbereitung

Folgen Sie den Installationsanleitungen unter [plantuml.com](https://plantuml.com/de/starting) als uch [https://github.com/RicardoNiepel/C4-PlantUML](https://github.com/RicardoNiepel/C4-PlantUML) um PlantUML zu installieren.&#x20;

Alternativ können Sie die [PlantUML Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) verwenden.

In beiden Fällen benötigen Sie [Graphviz](https://www.graphviz.org/download/).

Als Alternative können Sie den Online Server von PlantUML nutzen: [http://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000](http://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000)

## Aufgabe

Erstellen Sie ein C4 Level 1 Modell auf Basis der unten stehenden Beschreibung eines Kunden eines Systems:&#x20;

> We want a new insurance system which will be usually used directly by our employees. Access to the system will be granted only to internal employees, external staff will not be able to use the system. We will provide a web application based on Java SpringBoot which delivers a single page application (SPA) based on JavaScript and Vue.js. The users gain access to the web app as well as the single page application via HTTPS. The web app itself uses an API gateway via JSON/HTTPS. To manage the API gateway we use a K8s system, provided and managed not by the team responsible for the insurance system. We will use instead the K8s platform provided by our internal IT department. Also there will be a mail system we use to send out daily reports to our users. We decided not to host the mail system by ourselves, instead we will outsource this to a provider. The mail system is triggered by our company's ERP system hosted by SAP. To access the mail server, which will be a Microsoft exchange server, our ERP team will use a internal plugin using .NET WCF to connect the SAP system and the Exchange server. The SAP system also will be accessed by the API gateway using asynchronous JMS.

## Abgabe

Folgende Dateien sind einzureichen:&#x20;

* Die PlantUML Datei (.puml) mit Ihrem C4-Modell.&#x20;
* Ein Screenshot des gerenderten Modells (.png, .gif oder .jpg)
* Optional: Wenn Sie eine lokale Kopie der C4-Erweiterung verwenden diese in der genutzten Version beifügen
