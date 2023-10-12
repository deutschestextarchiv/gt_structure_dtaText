# gt_structure_dtaText

The "gt_structure_dtaText" repository lists five corpora. These corpora refer to ground truth structure repositories (https://github.com/tboenig/gt_structure_all). 

The corpus consists in TXT file format and/or TEI-XML(DtaBf) files.
The documents were created as a result of the DFG project DeutschesTexteArchiv (DTA).

# Documentation
## DTA Workflow
**Datengrundage DTA**
Der Datenerfassungsworkflow des DTA zeigt, dass auf dem Weg zum TEI verschiedene Datenerstellungsetappen zu erreichen waren.
In jeder dieser Etappen wurde ein bestimmter Datenzustand mit einem entsprechenden Datenformat erstellt.
Zur Datenerfassung nutzte das DTA folgende Methoden:
* das Double Keying und 
* OCR (automatisierte Transkription).

Für die Nutzung von Ground Truth (GT) ist der Bestand, der im Double Keying-Verfahren erstellten Daten, am interessantesten.
* Diese Daten betreffen den größten Teil des DTA-Bestandes.
* Mit OCR wurden vor allem nur Titel des 19. und Mitte des 18. Jahrhunderts erfasst. Für dieses Schrifttum exitieren gute und stabile OCR-Modelle sowie sind die OCR-Engines im Umgang mit diesen Dokumenten optimiert. Aus diesem Grund ist der Bedarf nach GT für diese Dokumente nicht schwerpunktmäßig zu betrachten. Die Dokumente die aus dem Zeitraum Ende 17. Jh. und des 16. Jh. stammen, wurden ausschließlich mit dem Double-Keying-Verfahren erfasst.
* Das Double-Keying-Verfahren wurde von nicht Muttersprachlern vorgenommen und ist sehr genau. Die Genauigkeit kann mit 99,99 % angesetzt werden.
* Die Erfassung im Double-Keying-Verfahren erfolgte nach den DTA-Richtlinien.
* Der Schwerpunkt der DTA-Richtlinen bildete die vorlagentreue Wiedergabe des analogen Textes in digitaler Form mit Übernahme aller vorhandener Druckfehler. Eine Normalisierung wurde nicht vorgenommen.
* Neben der Transkription wurde eine manuelle sematische Segmentierung vorgenommen. Die Segmentierung diente jedoch der manuellen und nicht der automatischen Text-Struktur-Erfassung.

![image](https://github.com/tboenig/gt_structure_dtaText/assets/26142921/d9b8edde-1fd9-4823-8a40-23bc9ea968d1)<br/>
Fig 1: Complex representation of the DTA data workflow

## Segmentierungdaten
- Dokumentation: Konkordanz zu Zonen und Regionen im DTA Zot-Format sowie DTABf (TEI) 
  -  Siehe https://tboenig.github.io/gt-guidelines/html/trans/structur_gtpageformat.html

- DTA-Repositorium Segmentierungsdaten im PAGE-Format
  -  https://github.com/tboenig/gt_structure_all  


## Textdaten

| Format           | Kommentar | 
| --------         | --------  | 
| txt              | vom Dienstleister kommenden Daten, Transkriptionen (UTF8, Ansi-Format)                        | 
| txt.xml          | TEI-DTABf-Endversion                                                                          | 


* Dokumentation: Erfassungs- und Konvertierungsrichtline DTA
    * Dokumentation der zur manuellen Erfassung: https://kaskade.dwds.de/~matthias/DTA4doc/docu_transcription/Arbeitsanweisung_Texterfassung_20190710.pdf 
    * Dokumentation der Konvertierungsrichtline DTA: https://tboenig.github.io/ConversionDTABf/html/taskbook/konvertierung.html

## Ground Truth
- OCR-D GT-Guidelines
-   https://tboenig.github.io/gt-guidelines/html/trans/index.html
