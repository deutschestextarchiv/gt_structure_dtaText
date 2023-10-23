# gt_structure_dtaText

The "gt_structure_dtaText" repository lists five corpora. These corpora refer to ground truth structure repositories (https://github.com/tboenig/gt_structure_all). 

The corpus consists in TXT file format and/or TEI-XML(DTABf) files.
The documents were created as a result of the DFG project DeutschesTextArchiv (DTA).

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
* Das Double-Keying-Verfahren wurde von nicht Muttersprachlern vorgenommen und ist sehr genau. Die Genauigkeit kann mit 99,99 %[^1] angesetzt werden.
* Die Erfassung im Double-Keying-Verfahren erfolgte nach den DTA-Richtlinien.
* Der Schwerpunkt der DTA-Richtlinen bildete die vorlagentreue Wiedergabe des analogen Textes in digitaler Form mit Übernahme aller vorhandener Druckfehler. Eine Normalisierung wurde nicht vorgenommen.
* Neben der Transkription wurde eine manuelle sematische Segmentierung vorgenommen. Die Segmentierung diente jedoch der manuellen und nicht der automatischen Text-Struktur-Erfassung.

![image](https://github.com/deutschestextarchiv/gt_structure_dtaText/assets/26142921/cbe87861-cea2-4585-9169-eabc36bad2bf)<br/>
Fig 1: Complex representation of the DTA data workflow

## Segmentierungdaten
- Dokumentation: Konkordanz zu Zonen und Regionen im DTA Zot-Format sowie DTABf (TEI) 
  -  Siehe https://tboenig.github.io/gt-guidelines/html/trans/structur_gtpageformat.html

- DTA-Repositorium Segmentierungsdaten im PAGE-Format
  -  https://github.com/tboenig/gt_structure_all  

Tab 1: Concordance between data repositories text and segmentation

|Text-Corpus       | Segmentation-Corpus|
| --------         | --------           | 
|[gt_structure_1](https://github.com/deutschestextarchiv/gt_structure_dtaText/tree/main/corpus/gt_structure_1)    | https://tboenig.github.io/gt_structure_1_1/|
|                  |https://ocr-d.github.io/gt_structure_1_2/|
|                  |https://ocr-d.github.io/gt_structure_1_3/|
|                  |https://ocr-d.github.io/gt_structure_1_4/|
|[gt_structure_2](https://github.com/deutschestextarchiv/gt_structure_dtaText/tree/main/corpus/gt_structure_2)    |https://tboenig.github.io/gt_structure_2_1/|
|                  |https://ocr-d.github.io/gt_structure_2_2/|
|                  |https://ocr-d.github.io/gt_structure_2_3/|
|                  |https://tboenig.github.io/gt_structure_2_4/|
|[gt_structure_3](https://github.com/deutschestextarchiv/gt_structure_dtaText/tree/main/corpus/gt_structure_3)    |https://tboenig.github.io/gt_structure_3_1/|
|                  |https://ocr-d.github.io/gt_structure_3_2/|
|                  |https://ocr-d.github.io/gt_structure_3_3/|
|[gt_structure_4](https://github.com/deutschestextarchiv/gt_structure_dtaText/tree/main/corpus/gt_structure_4)    |https://tboenig.github.io/gt_structure_4_1/|
|                  |https://ocr-d.github.io/gt_structure_4_2/|
|                  |https://tboenig.github.io/gt_structure_4_3/|
|[gt_structure_5](https://github.com/deutschestextarchiv/gt_structure_dtaText/tree/main/corpus/gt_structure_5)    |https://tboenig.github.io/gt_structure_5_1/|
|                  |https://tboenig.github.io/gt_structure_5_2/|
|                  |https://tboenig.github.io/gt_structure_5_3/|

## Textdaten

| Format           | Kommentar | 
| --------         | --------  | 
| txt              | vom Dienstleister gelieferte Daten, Transkriptionen (UTF8, Ansi-Format)                        | 
| txt.xml          | TEI-DTABf-Endversion                                                                          | 


* Dokumentation: Erfassungs- und Konvertierungsrichtline DTA
    * [Arbeitsanweisung zur manuellen Erfassung von Texten im DTAsimple-Format für das Deutsche Textarchiv](https://github.com/tboenig/gt_structure_dtaText/blob/main/docu/Arbeitsanweisung_Texterfassung_20190710.pdf)
    * [Dokumentation der Konvertierungsrichtline DTA](https://tboenig.github.io/ConversionDTABf/html/taskbook/konvertierung.html)

## Ground Truth
- [OCR-D GT-Guidelines](https://tboenig.github.io/gt-guidelines/html/trans/index.html)

## Footnotes
[^1]: Susanne Haaf, Frank Wiegand, Alexander Geyken: Measuring the Correctness of Double-Keying: Error Classification and Quality Control in a Large Corpus of TEI-Annotated Historical Text. In: Journal of the Text Encoding Initiative (jTEI) 4, 2013. [doi](https://doi.org/10.4000/jtei.739)
