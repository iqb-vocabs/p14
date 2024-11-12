# Metadatenprofile für Testaufgaben: Deutsch Primar 2004

ID of profile-store: `adep`

Publisher: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

Maintainer: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Deutsch Primar 2004 - Aufgabe"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p14/master/unit.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler:in | Text |Einzeilig, Sprache(n): de | iqb_author |
| Für SPF geeignet | Ja/Nein |Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Kompetenzbereich | [Vokabular](https://w3id.org/iqb/v13/k1/) | url: 'https://w3id.org/iqb/v13/k1/', Einmalauswahl, Zeige nur erste Ebene | w8 |
| Aufgabenzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Quellenangaben | Text |Mehrzeilig, Sprache(n): de | iqb_copyright |
| Textsorte | [Vokabular](https://w3id.org/iqb/v28/ts/) | url: 'https://w3id.org/iqb/v28/ts/', Einmalauswahl | k8 |
| Wortanzahl | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_word_count |
| Stimuluszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Hörsequenz Transkript | Text |Mehrzeilig, Sprache(n): de | iqb_transcript |

## Profil "IQB Deutsch Primar 2004 - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p14/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/dp/) | url: 'https://w3id.org/iqb/v27/dp/', Einmalauswahl, Nummerierung unterdrückt | s3 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v13/a1/) | url: 'https://w3id.org/iqb/v13/a1/', Einmalauswahl, Nummerierung unterdrückt | s4 |
| Bildungsstandard primär | [Vokabular](https://w3id.org/iqb/v13/k1/) | url: 'https://w3id.org/iqb/v13/k1/', Einmalauswahl | s5 |
| Bildungsstandards sekundär | [Vokabular](https://w3id.org/iqb/v13/k1/) | url: 'https://w3id.org/iqb/v13/k1/', Mehrfachauswahl | s6 |
| Itemzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
| Geschätzte Schwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl | e4 |
