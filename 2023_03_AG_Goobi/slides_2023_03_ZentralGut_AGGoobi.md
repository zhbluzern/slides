---
author: Christian Erlinger
title: <img src="img/ZentralGut_Logo.png" height="200"/><br/><small>ZentralGut.ch - Zentralschweizer OpenGLAM-Portal</small>
urlcolor: white
institute: <img src="img/ZHB_Luzern_Logo_negativ.svg.png" height="60"/><br/><small>AG Goobi - 23.03.2023</small><br/><img src="img/CC_BY_icon.svg.png" width="100px"/>
---

## <small>(Zentral)Schweizer (Portal-)Landschaft</small>
 <img src="img/2023_03_ZentralSchweiz.jpg"/>

## <small>(Zentral)Schweizer (Portal-)Landschaft</small>

* Zentral- und Hochschulbibliothek Luzern
  * Grösste Bibliothek der Zentralschweiz
  * übernimmt bspw. innerhalb von SLSP regionale Koordination
* Aufbau eines kantonsübergreifenden Kulturgutportals
  * Gemeinsamer Raum und Geschichte – getrennte Sammlungen - im Portal vereint
  * Archive, Bibliotheken und Museen personell mit wenig Ressourcen ausgestattet

## <small>(Zentral)Schweizer (Portal-)Landschaft</small>
 <img src="img/2023_03_Portale.jpg"/>

## Wie nutzen wir Goobi?

* Schriften der ZHB Luzern
  * Alte Drucke und Handschriften
  * Zeitungsdigitalisate (Mikrofilmscans)
* Urkunden, Protokolle, Amtsdruckschriften aus den Staatsarchiven
* Bildmaterial
  * Graphiksammlung der ZHB Luzern
  * Glasplatten und Postkartensammlungen
* Videomaterial
* Museale Objekte

## Wie kommt Material nach ZentralGut

* Bibliographie-Import aus Alma
* Import via OAI-PMH (E-Rara, E-Manuscripta)
* Excel-Import
  * Die "kleinen" Partner verfügen nicht über Programme mit standardisierten Schnittstellen
  * Erlaubt Normalisierung der Daten

## Neue Sicht aufs Material
 <img src="img/2023_03_Menuplan.png"/>

## Neu in Workflow - ARK

* Neues Plugin für ARK-Identifier  <img src="img/2023_03_ARK.png" style="float:right;"/>
  * Dezentral(e Community)
  * Kosten(frei|günstig)
  * Semantik in der PID
  * Seitengenaue Adressierung ist Standard

## Neu in Workflow - Zeitungssplitting

* Automatische Ausgabenerkennung auf S/W erweitert
<img src="img/2023_03_Tagblatt.JPG"/>

## Neu in Viewer

* Kommentargruppen
  * Benutzer können zu «Gruppen» zur Bearbeitung von bestimmten Kommentaren (basierend auf SOLR-Queries) berechtigt werden.
* Upload-Formular
  * Benutzer können Material im Viewer hochladen -> mit Anbindung an Goobi Workflow 

## Ökosystem ZentralGut
<img src="img/2023_03_ZentralGutEcoSystem.png"/>

## Vernetzung – «Portalkreisläufe»
<img src="img/2023_03_ZentralGutCommons.png"/>

## Selbstgestricktes - nachnutzbar
* Wikimedia Commons Upload mit Open Refine
* [python CLI Mods-Editor](https://gitlab.com/zhbluzern/goobi-pycli-mods-editor) auf xls-Basis
* Zenodo-Upload "public archive"

## Entwicklungswünsche und -pfade
* Wikidata als "Normdatei" einbetten [Präsentation Goobi Days 22](https://zhbluzern.github.io/slides/2022_09_Goobi_Days_Wikidata)
* ARK-Identifier-Service muss übernommen werden
* ... vieles kleineres und grösseres am Viewer