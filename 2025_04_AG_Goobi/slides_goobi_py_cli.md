---
author: Christian Erlinger
title: Goobi pyCLI Metadaten-Editor
urlcolor: white
institute: <img src="img/ZHB_Luzern_Logo_negativ.svg.png" height="60"/><br/><small>AG Goobi, 01. April 2025</small><br/><img src="img/CC_BY_icon.svg.png" width="100px"/>
---

## Massenhaft Metadaten

* GoobiScripts (metadataAdd, metadataReplace) können viele Vorgänge bearbeiten, aber keine individuellen Werte je Vorgang
* Metadatenkorrekturen
  * Abfrage in Goobi Worfklow
  * Bearbeitung in Excel, OpenRefine
  * Upload nach Goobi
=> https://gitlab.com/zhbluzern/goobi-pycli-mods-editor

## <small>Goobi pyCLI-METS/MODS-Editor</small>

* Dateninput mit *.xls, Konfiguration als JSON
* Metadaten hinzufügen (Dublettenkontrolle)
* Metadaten überschreiben 
* Metadaten löschen (kontrolliert)
* Personen, Körperschaften hinzufügen
* Metadaten an beliebigen Punkten hinzufügen
* DocStrctType hinzufügen
* (Strukturelemente hinzufügen)

## <small>Konfiguration im GoobiStyle</small>
```json
{
    "inputFileName" : "InputFileName.xlsx",
    "metadataDir" : "metadata/",
    "startRow" : 2,
    "endRow" : 300,
    "processIdHeader" : "VorgangID",
    "metaFile" : "meta",    
    "mapping":
    [
        {
            "ugh": "RestrictionOnAccessLicense",
            "header": "RestrictionOnAccessLicense",
            "replaceExisting": True
        }
    ]
}
```

## Nachbearbeitung

* GoobiScript `updateCache`
* (`meta.xml` wird im Goobi-Stil gesichert.)