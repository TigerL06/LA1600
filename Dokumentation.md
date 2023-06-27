# LA1600
# Projekt-Dokumentation

Gruppe Pineapple: Koch, Grigioni, Hitz

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|    09.05.23   | 0.0.1   | Heute haben wir in der Dokumentation gearbeitet (1-3) und haben den ersten Prototyp fertiggestellt. |
|    16.05.23   | 0.1.1   |   Heute haben wir mit unseren Arbeitspacketen angefangen.                                                           |
|   23.05.2023    | 1.0.0   |              Heute haben wir an den Arbeitspacketen weitergearbeitet.                                                |
|   30.05.2023    | 1.1.0   |              Heute haben es Checkboxes erstellt mit denen man die Events sortieren kann, wir haben angefangen den Darkmode zu erstellen (wir sind aber noch nicht fertig) und passende Bilder für unsere Pop-ups zu finden (wir sind aber noch nicht fertig).          |
|   06.06.2023   | 1.1.1  |              Heute haben wir eine Thema für unsere Präsentation bestimmt, denn Darkmode fertig gestellt und Bilder hinzugefügt.      |
|   06.06.2023   | 1.1.2  |              Heute haben wir unsere Präsentation erstellt, die dazugehörige Seite und haben die Testfälle durchgeführt.      |

## 1 Informieren

### 1.1 Ihr Projekt

Unser Projekt ist eine Webseite, die Kulturliebhaberinnen und -liebhabern einen einfachen und schnellen Überblick über anstehende kulturelle Ereignisse wie Konzerte, Theateraufführungen, Ausstellungen und Festivals in ihrer Stadt oder Region bietet.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |        muss         |   funktional   |Als ein User möchte ich eine Seite, damit ich überhaupt was machen kann. |
| 2  |         muss        |    rand  |          Als ein Creator möchte ich, dass die Seite mit CSS gestaltet wird, damit die Seite übersichtlich aussieht.                         |
| 3  |         muss        |    funktional  |          Als ein User möchte ich das die Seite Events anzeigt wie Konzerte Theateraufführungen, Ausstellungen und Festivals, damit ich weiss welche Events noch kommen |
| 4  |         kann     |    funktional  |          Als ein User möchte ich, dass die Events nach dem Datum geordnet sind, damit ich die nächsten Events gleichsehe.                         |
| 5  |         muss        |    funktional  |         Als User möchte ich die Events nach Konzerten, Theateraufführungen, Ausstellungen und Festivals sortieren können, damit ich die Events sehen kann, die mich interessieren.  |
| 6 |         muss        |    funktional  | Als ein User möchte ich, dass wenn man auf das Event klickt, ein Pop-up aufgeht, dass die einzelnen Informationen zu diesem Event zeigen, damit ich mich besser über dieses Event informieren kann. |
| 7 |         kann      |    funktional  |  Als ein Creator möchte ich, dass wenn ein Pop-up aufgeht, die Events nach unten bewegen, damit die Pop-ups Platz haben. |
| 8 |         muss      |    funktional  |  Als ein Creator möchte ich, dass wenn es ein Darkmode gibt, damit ich die Seite selber gestallten kann. |
| 9 |         muss      |    funktional  |  Als ein Creator möchte ich, dass es Bilder in den Pop-ups hat und sie die richtige Grösse haben, damit ich die Seite selber gestallten kann. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Browser ist offen.             |Man gibt die URL ein der Webseite.         |Die Webseite öffnet sich.                  |
|3.1  |Die Homepage ist offen.              |Scrollen         |Es zeigt viele verschiedene Events an.                   |
| 4.1 |Die Homepage ist offen.              |Scrollen         |Die angezeigten Events sind dem Datum nach sortiert.               |
|5.1  |Die Homepage ist offen.              |Man linksklickt auf eine der 4 Kategorien oben.         |Es werden nur noch Events dieser Kategorie angezeigt.                 |
|6.1  |Die Homepage ist offen.              |Über ein Event hovern        |Es geht ein Pop-up auf               |
|7.1  |Das Pop-up ist offen.              |Über ein Event hovern      |Es werden mehr Informationen zum Event angezeigt                   |
|7.2  |Die Homepage ist offen.              |Auf ein Event ist geklickt worden     |Die Events verschieben sich.          |
|8.1  |Die Homepage ist offen.              |Man Clickt auf die Darkmode-Checkbox    |Die Seite bekommt ein schwarzes Design           |
|9.1  |Die Homepage ist offen.              |Man hovert über ein Event   | Ein Pop-up geht auf mit wichtigen Infos und einem Bild mit einer richtigen Grösse.          |

### 1.4 Diagramme
Skizze:
![2023_05_09 10_02 Office Lens](https://user-images.githubusercontent.com/110893121/237035746-90f9abe2-f04f-4b13-bf64-f48c154cab99.jpg)
Use Case Diagramm:
![image](https://user-images.githubusercontent.com/110893121/237035294-9eb4c97d-55cd-4bf0-a78b-ff8f43e9d388.png)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A     |09.05.2023 | Grigioni  | Man soll eine Webseite erstellen, als Prototyp  | 20  |
| 3.A     | 16.05.2023      |     Koch      | Man muss Events suchen, die wir in unsere Webseite tuen können.   | 45           |
| 3.B   |   16.05.2023       |   Hitz        | Die Events als Bouton(oder änliches) einfügen. (Damit man auf sie klicken kann und etwas passieren kann)    | 45         |
| 3.C  |     16.05.2023     |    Koch      |Die Events werden als Liste dargestellt.     | 45         |
| 4.A    |   16.05.2023       |   Grigioni     | Die Events sind nach ihrem Datum sortiert.        |     2*45         |
| 5.A     |   16.05.2023       |    Hitz       |  Vier verschiedene Arten von Veranstalltungen(Konzerte Theateraufführungen, Ausstellungen und Festivals) als Bouton(oder änliches) einfügen. (Damit man auf sie klicken kann und etwas passieren kann)  |      45         |
| 5.B    |    23.05.2023      |     Grigioni      |  Wenn man auf eine Veranstalltung klickt, müssen nur noch diese Events von dieser Art von Veranstalltung angezeigt werden.         |      2*45        |
| 6.A     |   23.05.2023     |     Hitz      |        Wenn man auf ein Event klickt entsteht ein Pop-up.   |     2*45          |
| 6.B    |    23.05.2023    |      Koch     |        In einem Pop-up stehen die wichtigsten Informationen |    2*45          |
| 7.A     |   30.05.2023    |     Hitz, Koch, Grigioni     |    Wenn ein Pop-up aufgeht, verschiebt sich die Liste von Events nach links.          |         3*45     |
| 8.A     |   06.06.2023     |     Koch     |        Wenn man auf die Checkbox Darkmode klickt werden die Sachen schwarz die weiss sind und die Sachen weiss die schwarz sind.  |     2*45          |
| 9.A    |    06.0.2023    |      Hitz   |       Bilder in die Pop-ups einfügen und sie so formatieren, dass sie eine gute Grösse haben.|    2*45          |


Total: 645 Minuten

## 3 Entscheiden

Wir haben entschieden, dass wir Pop-ups verwenden werden, um Informationen und Bilder anzuzeigen, wenn ein Benutzer auf ein bestimmtes Ereignis auf der Seite klickt.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   09.05.2023    |   Grigioni     |        20    |    45               |
| 3.A |     16.05.2023    |    Hitz       |         45      |          3*45         |
| 3.B |    16.05.2023     |   Koch        |        45       |          45         |
| 3.C |    16.05.2023     |   Grigioni      |       45        |      45             |
| 5.B  |  16.05.2023    |  Koch, Grigioni|        2*45    |    2*45           |
| 5.A  |  23.05.2023    | Hitz|        45    |    2*45           |
| 5.B  |  23.05.2023    |  Grigioni, Koch|        2*45    |    2*45           |
| 6.A  |  23.05.2023    |  Koch|        2*45    |    2*45           |
| 6.B    |    23.05.2023    |     Hitz    |     2*45          |    2*45           |
| 4.A    |    23.05.2023    |     Grigioni   |     2*45          |    2*45           |
| 5.B  |  30.05.2023    | Hitz, Koch|        2*45    |    2*45           |
| 8.A  |  30.05.2023    |  Koch|        2*45    |    2*45           |
| 9.A  |  30.05.2023    |  Hitz|        2*45    |    2*45           |
| 7.A  |  30.05.2023    |  Koch|        2*45    |    45          |
| 8.A  |  06.06.2023    |  Koch, Hitz, Grigioni|        2*45    |    2*45           |
| 9.A  |  06.06.2023    |  Hitz, Koch, Grigioni|        2*45    |    2*45           |
Total: 1305 Minuten

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |   13.06.2023    |      okay    |     Koch   |
| 3.1  |   13.06.2023    |      okay    |     Koch   |
| 4.1  |   13.06.2023    |      okay    |     Koch   |
| 5.1  |   13.06.2023    |      okay    |     Koch   |
| 6.1  |   13.06.2023    |      okay    |     Koch   |
| 7.1  |   13.06.2023    |      okay    |     Koch   |
| 8.1  |   13.06.2023    |      okay    |     Koch   |
| 9.1  |   13.06.2023    |      okay    |     Koch   |

Fazit:
Alle Testfälle haben geklappt, die Website läuft ohne Probleme.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

Bie unserem Exploratives Testen ist nichts spezieles vorgefalle. Es hat alles funktioniert.

## 6 Auswerten

[Lernbericht](https://github.com/TigerL06/LA1600/blob/main/Lern-Bericht.md)
