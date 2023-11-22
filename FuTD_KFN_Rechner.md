# Tilgungsrechner - Klimafreundliches Bauen (KFN)

## KfW Bankengruppe

**Dokumentinformation**
<a id="tab1"></a>

| Dokumentname                                  | Stand (Datum) | Autor | Überprüfung | Vertraulichkeit |
| --------------------------------------------- | ------------- | ----- | ----------- | --------------- |
| Gemeinsames Fachliches und Technisches Design | 21.11.2023    |       | intern      |

Tabelle 1: Dokumenteninformationen

**Dokumenthistorie**
<a id="tab2"></a>

| Datum      | Status¹        | Überarbeitet von | Beschreibung                                                                                      |
|------------|----------------|------------------|---------------------------------------------------------------------------------------------------|
| 06.07.2023 | In Bearbeitung | N.Nguyen         | Initiale Erstellung                                                                               |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36756 Kapitel 4 - FRONTEND - Form 1 - Implementierung der Form 1                                 |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36758 Kapitel 4 - Implementierung der Validierung des "Weiter" & "Jetzt berechnen"-Buttons       |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36760 Kapitel 4 - FRONTEND - Form 2 - Implementierung der Form 2: Auswahl Kreditart              |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36761 Kapitel 4 - Implementierung "Bearbeiten"- Funktion des Accordions + zugehörigem Verhalten  |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36763 Kapitel 4 - FRONTEND - Form 2a - Implementierung der Form 2a                               |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36765 Kapitel 4 - FRONTEND - Form 3 -Implementierung der Form 3: Vergleich zur Hausbank          |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36766 Kapitel 4 - FRONTEND - Form 2b - Implementierung der Form 2b                               |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36768 Kapitel 4 - FRONTEND - Form 4b -Implementierung der Form 4b: Tilgungsdaten                 |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36770 Kapitel 4 - FRONTEND - Form 4d -Implementierung der Form 4d: Tabelle Vorteilsberechnung    |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36771 Kapitel 4 - FRONTEND - Form 4a - Implementierung der Form 4a: Ihre Angaben auf einen Blick |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36772 Kapitel 4 - FRONTEND - Form 4c  -Implementierung der Form 4c: Tabellarischer Tilgungsplan  |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36775 Kapitel 4 - FRONTEND - Umsetzung Responsives Verhalten (inkl. mobile View)                 |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36767 Kapitel 4.2 - SST - Implementierung Aufruf des VSP Rechenkerns                             |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36762 Kapitel 4.3 - SST - Einbindung interne Produkt-API                                         |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36764 Kapitel 4.3 - SST - Produkt- und Zinskonditionen aus der internen und externen Produkt-API |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34110 Kapitel 4.4 - Routing / URL                                                                |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36774 Kapitel 4.4 - Overlay Verhalten & iframe Einbindung (entwicklungstechnisch)                |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34029 Kapitel 5 - Bereitstellung Infrastruktur für KFN-Rechner                                   |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34273 Kapitel 8.1 - Umgebungsvariablen setzen                                                    |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34124 Kapitel 8.5.2 - Bereitstellung Pipeline KfN - Alles Stages (DEV, Test, Pre, Prod)          |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34098 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34116 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34125 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34128 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34129 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34132 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34272 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34778 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #34786 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #35213 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #35214 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #35683 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #35695 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36755 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36777 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36807 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36808 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36826 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36827 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #36896 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #37290 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #37858 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #38460 - Keine Doku notwendig                                                                     |
| 16.11.2023 | In Bearbeitung | N.Nguyen         | #38534 - Keine Doku notwendig                                                                     |
| 20.11.2023 | In Bearbeitung | N.Nguyen         | Freigabe RM0010365                                                                                |

Tabelle 2: Dokumenthistorie

**Begriffe, Abkürzung, Definition**
<a id="tab3"></a>

| Abkürzung |         Begriffe         | Definition     |
|-----------|:------------------------:|----------------|
| KFN       | Klimafreundlicher Neubau | Förderprogramm |

Tabelle 3: Begriffe, Abkürzungen, Definitionen

**Relevante Dokumente**
<a id="tab4"></a>

| Name                         | Ablageort im DMS                                                                                                                                                 |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FD Zins und Tilgungsplan [1] | [Link DMS](https://kfw-f-dmswebp.kfw.kfwgruppe.net/dms_kfw/exe/eb.exe?cfgs=../cfgs/dmsapi.cfg&p=d&MaskName=dopendoc&docid=d3055b413-b01f-11e8-80c1-c72ae4ede186) |
| FD Produktdefinition [2]     | [Link DMS](https://kfw-f-dmswebp.kfw.kfwgruppe.net/dms_kfw/exe/eb.exe?cfgs=../cfgs/dmsapi.cfg&p=d&MaskName=dopendoc&docid=dd484e526-6b00-11e8-aa60-de25ddd59a9f) |
| FD Kalkulationsservice [3]   | [Link DMS](https://kfw-f-dmswebp.kfw.kfwgruppe.net/dms_kfw/exe/eb.exe?cfgs=../cfgs/dmsapi.cfg&p=d&MaskName=dopendoc&docid=d5ddbd4bb-021f-11e6-ae69-c72ae4ede186) |
| aBK                          | [Link DMS](https://kfw-f-dmswebp.kfw.kfwgruppe.net/dms_kfw/exe/eb.exe?cfgs=../cfgs/dmsapi.cfg&p=d&MaskName=dopendoc&docid=d4b161487-3c2e-11ee-837c-a7ae5024b6d7) |
| SiKon                        | wird nachgereicht |

Tabelle 4: Übersicht Referenzdokumente

**Mitgeltende Dokumente**
<a id="tab5"></a>

| Name | Ablageort im DMS |
| ---- | ---------------- |
|      |                  |

Tabelle 5: Mitgeltende Dokumente

**Verantwortliche / Ersteller / Mitwirkende**
<a id="tab6"></a>

| Name, OE             |   Funktion    |
|----------------------|:-------------:|
| Annemarie Kern, ITe7 | IT-Consultant |
| Nam Nguyen, ITe7     | IT-Consultant |
| Elisa Schwaab, ITe7  |      PO       |

Tabelle 6: Verantwortliche / Ersteller / Mitwirkende

**Qualitätssicherung**
<a id="tab7"></a>

| Name, OE             |   Funktion    |
|----------------------|:-------------:|
| Elisa Schwaab, ITe7  |      PO       |
| Annemarie Kern, ITe7 | IT-Consultant |
| Nam Nguyen, ITe7     | IT-Consultant |

Tabelle 7: Qualitätssicherung

[[_TOC_]]

# Tabellenverzeichnis

[Tabelle 1: Dokumenteninformationen](#tab1)<br>
[Tabelle 2: Dokumenthistorie](#tab2)<br>
[Tabelle 3: Begriffe, Abkürzungen, Definitionen](#tab3)<br>
[Tabelle 4: Übersicht Referenzdokumente](#tab4)<br>
[Tabelle 5: Mitgeltende Dokumente](#tab5)<br>
[Tabelle 6: Verantwortliche / Ersteller / Mitwirkende](#tab6)<br>
[Tabelle 7: Qualitätssicherung](#tab7)<br>
[Tabelle 8: Überblick über den Bildschirmablauf](#tab8)<br>
[Tabelle 9: Angezeigte Elemente - Sektion "Angaben zum Wohngebäude"](#tab9)<br>
[Tabelle 10: Angezeigte Elemente - Sektion "Angaben zum Kredit"](#tab10)<br>
[Tabelle 11: Angezeigte Elemente - Sektion "Vergleich zur Hausbank"](#tab11)<br>
[Tabelle 12: Angezeigte Elemente - Sektion "Ergebnis - Ihre Angaben"](#tab12)<br>
[Tabelle 13: Angezeigte Elemente - Sektion "Ergebnis - Ihre Angaben"](#tab13)<br>
[Tabelle 14: Angezeigte Elemente - Sektion "Ergebnis - Tabellarischer Tilgungsplan"](#tab14)<br>
[Tabelle 15: Angezeigte Elemente - Sektion "Ergebnis - Vorteilsrechner"](#tab15)<br>
[Tabelle 16: Enthaltene Komponente im Frontend](#tab16)<br>

# Abbildungsverzeichnis


# 1	Zielsetzung, Abhängigkeiten und Randbedingungen gemäß Fachvorgabe
Der Rechner „Klimafreundliches Bauen“ ist eine Ausprägung der Applikation „Tilgungsrechner Wohnen/Bauen/Sanieren“ in Form eines Internet Web-Rechners, welcher auf Basis der eingegeben Kredithöhe und Auswahl des Verwendungszweckes und Kreditparameter (Zins, Laufzeit & Freijahre) einen Tilgungsplan sowie Vergleichszins eines potenziellen Kredits anzeigt. Er ist somit ein Tilgungs- sowie Vorteilsrechner in einem. 

Der Rechner zeigt dem Nutzer somit an, wie hoch die monatliche Belastung und wie hoch der finanzielle Vorteil aus den Förderprodukten sind.
Folgende Produkte sind im Förderprogramm enthalten:

-	Klimafreundlicher Neubau Wohngebäude – private Selbstnutzung (297) [(KFW-Produktseite 297)](kfw.de/297)
-	Klimafreundlicher Neubau Wohngebäude (298) [(KFW-Produktseite 297)](kfw.de/297)

Je nach Produkt und Förderstufe ergeben sich unterschiedliche Implikationen für maximale Kreditbeträge, Zinsen und andere Parameter. Der Rechner zeigt je nach Auswahl der Eingabeparameter einen entsprechenden Tilgungsplan sowie einen Vergleichszins eines branchenüblichen Kredits an.

## 1.1	Zielsetzung und Auswirkungen
Im Auftrag des BMWSB (Bundesministerium für Wohnen, Stadtentwicklung und Bauwesen) wurde zum 01.03.2023 ein neues Förderprogramm aufgesetzt mit den oben genannten Produkten.
Das Förderziel besteht im Neubau klimafreundlicher Gebäude. Das heißt, gefördert wird der Neubau oder Ersterwerb (innerhalb von 12 Monaten nach Bauabnahme) neu errichteter klimafreundlicher Wohn- und Nichtwohngebäude. 

## 1.2	Ausgangssituation und Auslöser
Im Auftrag des BMWSB übernimmt die KfW im Rahmen der Bundesförderung effiziente Gebäude - Klimafreundlicher Neubau (KFN) die Finanzierung und Förderung des Neubaus sowie Ersterwerbs von klimafreundlichen Wohngebäuden in Deutschland.
In diesem Zusammenhang soll ein zugehöriger Rechner als Teil der Applikation Tilgungsrechner Wohnen/Bauen/Sanieren aufgesetzt werden.

## 1.3	Leistungsabgrenzung
Die nachstehenden Informationen beziehen sich ausschließlich auf den Rechner „Klimafreundliches Bauen“ der Applikation „Tilgungsrechner Wohnen/Bauen/Sanieren“, nicht jedoch auf die Rechner bzw. weiteren Programme der Applikation. 
Im ersten Release werden nur die Programme zur Kreditförderung mit Zinsverbilligung, kein Tilgungszuschuss (297, 298) berücksichtigt. Die Programme 498, 499 sind aktuell nicht enthalten.

Dieses FuTD beschreibt nicht:
-	die Berechnung von Tilgungsplänen für Bildungsdarlehen. Diese werden in Fachliches Design_BK_Tilgungsrechner beschrieben.
-	die Berechnung von zu zahlende Vorfälligkeitsentschädigungsbeträge für KfW-Darlehen. Diese werden im FK VFE-Rechner beschrieben.
-	die Berechnung der Tilgungszuschüsse für Investitionen ist aktuell noch nicht im KFN vorgesehen. Diese werden in Fachliches Design und Pflichtenheft_Zuschussrechner beschrieben.

## 1.4	Abhängigkeiten
Die Berechnung der Tilgungsparameter erfolgt über die Tilgungsrechnerschnittstelle. Ist diese nicht verfügbar, so kann auch keine Berechnung stattfinden.
Weiterhin werden die Produktkonditionen sowie der aktuelle Zins via der internen bzw. der externen Produkt-API bezogen. Ist diese nicht verfügbar, so kann nur mit einem alten Stand berechent werden.

## 1.5	Annahmen
Nicht relevant.

## 1.6	Rahmenbedingungen
Es ist der Styleguide der KfW und die weiteren Regelungen zur Webentwicklung und Barrierefreiheit einzuhalten. Des Weiteren hat sich der Tilgungsrechner in das aktuelle Design und die User Experience der meine.kfw.de und kfw.de eingefügt.

### 1.6.1	Mengengerüst
Als Mengengerüst basierend auf Click-Zahlen für die KFW Produktseite kfw.de/297 werden maximal 50-100 Nutzer stündlich erwartet.

### 1.6.2	Kapazität / Verbrauchsverhalten
Wie in 1.6.1 beschrieben. 

### 1.6.3	Gesetzliche Grundlagen
Nicht relevant.

## 1.7	Nicht-funktionale Anforderungen
### 1.7.1	Benutzeroberfläche
#### 1.7.1.1	Styleguide 
Das neue KfW Basis-Design (wie es vom Projekt "KfW goes mobile" verwendet wird) muss konsistent angewendet werden. Basis ist der Styleguide von kfw.de für Onlineauftritte.

#### 1.7.1.2	Web-Zugangsleitlinien
Die Applikation unterliegt strikt den Zugangsstandards der Verordnung zur Schaffung barrierefreier Informationstechnik nach dem Behindertengleichstellungsgesetz BITV 2.0 (Ordiance on the Creation of Barrier-Free InFormation Technology 2.0: BITV) Prioritätsstufe I, in dem im weiten Teilen Äquivalenz zu den Webinhaltszugangsleitlinien (Web Content Accessibility Guidelines: WCAG) Stufe A und AA des W3C herrscht.
•	BITV 2.0 https://www.gesetze-im-internet.de/bitv_2_0/BJNR184300011.html
•	WCAG: http://www.w3.ODERg/TR/WCAG20/ [English]

#### 1.7.1.3	Webbrowser
Die gängigen Browser (Chrome, Safari, Edge) in der aktuellen Version werden von der Applikation unterstützt. 

#### 1.7.1.4	Mobile Geräte / Responsive Design 
Die Applikation beinhaltet ein Responsive Design, das auch auf mobilen Endgeräten wiedergegeben werden kann. 
Für Testzwecke werden folgende Geräteansichten im Entwicklermodus des Browsers verwendet.
 
- Viewport XL - Standardmodus Microsoft Edge Browser
- Viewport S - Geräteemulation-Modus Microsoft Edge Browser - Format iPhone 12 Pro

### 1.7.2	Effizienz und Performance
Der KFN soll bei jeder Aktion, die mit dem Rechner durchgeführt wird, keine sichtbaren Wartezeiten erkennen. Insbesondere bei den Dropdown-Auswahlen zur Bestimmung der Krediteigenschaften. Da die anzuzeigenden Dropdown-Felder und deren Befüllung durch eine Anfrage an das neue Produktmodell gesteuert wird, ist hier besonderer Wert darauf zu legen das dem Nutzer keine Wartezeiten entstehen. Die Dropdown-Auswahl muss augenblicklich möglich sein. Unter der Berücksichtigung, dass jede Auswahl per Dropdown zu einer weiteren Anfrage an die Produktmodell-Schnittstelle führt, ist sicherzustellen, dass die Schnittstelle auch mehrere 1000 Anfrage pro Sekunde verarbeiten kann ohne Performanceeinbußen.

### 1.7.3	Zuverlässigkeit
Die Applikation hat eine erweiterte Verfügbarkeit von 24x7. Microsoft Azure garantiert eine Verfügbarkeit ihrer Infrastruktur von 99,9%. Die Verfügbarkeit der restlichen Komponenten richtet sich nach der KfW.de-Seite und der aus der VSP genutzten Backend-Services aus.
Service	Verfügbarkeit
Servicezeit der Applikation	Mo – So 0:00 – 24:00
Support Zeit UHD	Mo – Fr 7:00 – 19:45
Allgemeine IT-Servicezeit	Mo – Do 8:15 – 17:00 Fr 8:15 – 15:45
Tabelle 8 Servicezeiten und Verfügbarkeit

### 1.7.4	Änderbarkeit
Nicht relevant.

### 1.7.5	Sicherheit
Siehe Sicherheitskonzept für KFN-Rechner.
 
### 1.7.6	Anforderungen an die technische Realisierung
Nicht relevant.

### 1.7.7	Anforderungen an das Deployment
Nicht relevant.

### 1.7.8	Gesetzliche Grundlagen
Nicht relevant.

### 1.7.9	Datenschutz
Es werden keine Daten erfasst oder gespeichert.
 
### 1.7.10	Skalierbarkeit
Eine Skalierung der Nutzungslast soll möglich sein. Das Azure Framework bietet hier die relevanten Möglichkeiten zur Skalierung.

### 1.7.11	Stabilität
Keine gesonderten Anforderungen. Stabilität des produktiven Systems durch Staging der Umgebung wird sichergestellt.

### 1.7.12	Verfügbarkeit/Wiederherstellbarkeit/Wiederanlaufklasse
Eine 24x7 Azure Umgebung wird genutzt. Längere Downtimes in Produktion sind nicht geplant. Die Verfügbarkeit richtet sich darüber hinaus an den Backend-Services der VSP.
Außerplanmäßige Downtimes sind möglich und müssen angekündigt sein. 

### 1.7.13	Konfigurierbarkeit
Nicht relevant.

### 1.7.14	Kompatibilität
HTML-Oberflächen müssen mind. HTML5 und CSS 3 erfüllen. Java Script muss unterstützt und im Browseraktiviert sein. Weitere gesonderten Anforderungen sind nicht formuliert.

### 1.7.15	Testbarkeit
Nicht relevant.

## 1.8	Sicherheitsbezogene Anforderungen
### 1.8.1	Schutzbedarf
Die Anwendung wurde als VIV 1-2-2 klassifiziert. 

Vertraulichkeit: 1
Integrität: 2
Verfügbarkeit: 2

### 1.8.2	Authentifizierung
Nicht relevant.

### 1.8.3	Autorisierung: Benutzergruppen/Rollen/Rechte
Nicht relevant. 

### 1.8.4	Verschlüsselung
Die Applikation benutzt und speichert keine Daten. Sämtliche Kommunikation ist verschlüsselt.

### 1.8.5	Signierung
Nicht relevant. 

## 1.9	Anforderungen an die Datenmodellierung
### 1.9.1 Mandantenfähigkeit
Nicht relevant.

### 1.9.2 Historisierung
Nicht relevant. 

### 1.9.3 Stichtagsfähigkeit
Nicht relevant.

# 2 Allgemeine Übersicht

## 2.1 Funtionale Beschreibung

Der Rechner „Klimafreundliches Bauen“ ist ein Internet-Web-Rechner, welcher auf Basis der eingegeben Kredithöhe und Auswahl des Verwendungszweckes und Produktprogramms Kreditparameter (Zins, Laufzeit & Freijahre), Tilgungsplan sowie Vergleichzins eines potenziellen Kredits anzeigt.

Der Rechners zeigt dem Nutzer somit an, wie hoch die monatliche Belastung und wie hoch der finanzielle Vorteil aus den Förderprodukten sind.

## 2.2 Integration der Applikation in die Systemlandschaft der KfW

Die Applikation wird als iFrame Overlay auf der Produktdetailseite kfw.de/297 eingebunden.
Die eigenständige URL des iframes lautet: foerderservices.kfw.de/297-298

![KFN_2.2_Screenshot_Overlay](./../Dokumentation/img/KFN_2.2_Screenshot_Overlay.png)

# 3 Rahmenablauf der Applikation

Der Nutzer ruft über die KfW.de-Homepage den KFN-Online-Rechner auf und gibt in der dem Programm entsprechenden Oberfläche alle relevanten und notwendigen Details der geplanten Produktart Kredit ein (Kapitel 4.1).
Die zur Auswahl stehenden Produktvarianten werden von der internen und externen Produkt API bezogen (siehe Kapitel 4.3)
Die Benutzereingaben und weitere programmspezifischen Daten werden an den REST Webservice „Tilgungsrechner“ weitergegeben (Kapitel 4.2). 

# 4 Funktionales Design

In folgenden Unterkapiteln wird das Funktionale Design aus der Nutzer/Frontend-Perspektive beschrieben.
Die technologische Beschreibung der verwendeten Komponenten findet im Kapitel 5 statt.

## 4.1 Interaktionsschicht

**Maskenfolge**

<a id="tab8"></a>

| Screennr | Screenname                                       | Kapitel |
|:--------:|:-------------------------------------------------|:--------|
|    1     | Sektion "Angaben zum Wohngebäude"                | 4.1.1   |
|    2     | Sektion "Angaben zum Kredit"                     | 4.1.2   |
|    3     | Sektion "Vergleich zur Hausbank"                 | 4.1.3   |
|    4     | Sektion "Ergebnis - Ihre Angaben"                | 4.1.4   |
|    5     | Sektion "Ergebnis - Ihr KFW-Kredit"              | 4.1.5   |
|    6     | Sektion "Ergebnis - Tabellarischer Tilgungsplan" | 4.1.6   |
|    7     | Sektion "Ergebnis - Vergleich zur Hausbank"      | 4.1.7   |

Tabelle 8: Überblick über den Bildschirmablauf

Hinweis: Die Screenshots sind exemplarischer Natur und können von Kreditprogramm zu Kreditprogramm abweichen. So können angezeigte Auswahlmöglichkeiten oder Labels je nach Programm verschieden sein. Die Screenshots sollen lediglich das Look & Feel der Screensektion zeigen.

### 4.1.1 Sektion "Angaben zum Wohngebäude"

#### 4.1.1.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.1](./../Dokumentation/img/KFN_Sektion_4.1.1.png)

Abbildung 3: Layout - Sektion "Angaben zum Wohngebäude"

#### 4.1.1.2 Eingabe Elemente

| Nr  | Name des Attributs   | Geschäftsobjekt Attribut | Beschreibung | Art des Inputs | Vorbelegung | Validierung   | Quelle Validierung | Pflichtfeld? | Kommentar                                     | Anzeigereihenfolge |
|-----|----------------------|:-------------------------|:-------------|----------------|-------------|---------------|--------------------|--------------|-----------------------------------------------|--------------------|
| 1.1 | Nutzungsart          | productnumber            | -            | Radio          | keine       |               | -                  | ja           | 297 = private Selbstnutzung, 298 = Vermietung | 1                  |
| 1.2 | Förderstufe          | purpose                  | -            | Radio          | keine       |               | -                  | ja           |                                               | 1                  |
| 1.3 | Anzahl Wohneinheiten | residentialUnits         | -            | Freifeld       | keine       | bei 297 max 2 | -                  | ja           |                                               | 2                  |

Tabelle 11: Eingabeelemente - Sektion "Angaben zum Wohngebäude"

#### 4.1.1.3 Angezeigte Elemente

<a id="tab9"></a>

| Bereich                 | Quelle Inhalt      | Sektion      | Statisch / Dynamisch |
|-------------------------|--------------------|--------------|----------------------|
| Titel, Untertitel, Text | kfnLabelService.ts | Wohngebaeude | Statisch             |

Tabelle 9: Angezeigte Elemente - Sektion "Angaben zum Wohngebäude"

### 4.1.2 Sektion "Angaben zum Kredit"

#### 4.1.2.1 Layout

Layout Auswahl - Annuitätsdarlehen

<a id="abb3"> </a>

![KFN_Sektion.4.1.2.1](./../Dokumentation/img/KFN_Sektion_4.1.2.1.png)

Abbildung 3: Layout - Sektion "Angaben zum Kredit - Annuitätsdarlehen"

Layout Auswahl - Endfälliges Darlehen

<a id="abb3"> </a>

![KFN_Sektion.4.1.2.2](./../Dokumentation/img/KFN_Sektion_4.1.2.2.png)

Abbildung 3: Layout - Sektion "Angaben zum Kredit - Endfälliges Darlehen"

#### 4.1.2.2 Eingabe Elemente

| Nr     | Name des Attributs       | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung                                          | Quelle Validierung | Pflichtfeld? | Kommentar                     | Anzeigereihenfolge |
|--------|--------------------------|:-------------------------|----------------|-------------|------------------------------------------------------|--------------------|--------------|-------------------------------|--------------------|
| 2.1    | Kreditbetrag             | max amount limit         | Freifeld       | keine       | maximal Anzahl WE x 100k€ (150k€) ohne QNG (mit QNG) | kfnLabelService.ts | Ja           | -                             | 1                  |
| 2.2    | Kreditart                | repaymentMethod          | Radio          | keine       |                                                      | -                  | Ja           | -                             | 1                  |
| 2.3    | Laufzeit in Jahren       | loanTerm                 | Auswahl        | keine       |                                                      | -                  | Ja           | -                             | 2                  |
| 2.4    | Tilgungsfreie Anlaufzeit | gracePeriod              | Auswahl        | keine       |                                                      | -                  | Ja           | nur bei Kreditart = monatlich | 3                  |
| 2.5    | Zinsbindung              | fixedInterestRatePeriod  | Radio          | keine       |                                                      | -                  | Ja           | nur bei Kreditart = monatlich | 3                  |
| 2.6    | KfW-Sollzins             | ekn-interest-nominal     | Freifeld       | keine       |                                                      | -                  | Ja           |                               | 3                  |
| 2.7    | Flag_Sollzins            | chosenInterestRate       | Radio          | keine       |                                                      | -                  | Ja           | Eingabe eigener Sollzins      | 3                  |
| 2.8    | Sollzins in %            | chosenInterestRateAmount | Freifeld       | keine       |                                                      | -                  | Ja           | nur bei Flag_Sollzins = ja    | 4                  |
 
Tabelle 11: Eingabeelemente - Sektion "Angaben zum Kredit"

#### 4.1.2.3 Angezeigte Elemente

<a id="tab10"></a>

| Bereich                  | Quelle Inhalt                    | Sektion / Wert          | Statisch / Dynamisch |
|--------------------------|----------------------------------|-------------------------|----------------------|
| Titel, Untertitel, Text  | kfnLabelService.ts               | -                       | Statisch             |
| Laufzeit in Jahren       | interne Produkt-API, Kapitel 4.4 | loanTermMin(Max)        | dynamisch            |
| Tilgungsfreie Anlaufzeit | interne Produkt-API, Kapitel 4.4 | gracePeriod(Max)        | dynamisch            |
| Zinsbindung              | interne Produkt-API, Kapitel 4.4 | fixedInterestRatePeriod | dynamisch            |
| KfW-Sollzins             | externe Produkt-API, Kapitel 4.4 | ekn-interest-nominal    | dynamisch            |

Tabelle 10: Angezeigte Elemente - Sektion "Angaben zum Kredit"

### 4.1.3 Sektion "Vergleich zur Hausbank"

#### 4.1.3.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.3](./../Dokumentation/img/KFN_Sektion_4.1.3.png)

Abbildung 3: Layout - Sektion "Vergleich zur Hausbank"

#### 4.1.3.2 Eingabe Elemente

| Nummer | Name des Attributs | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung | Quelle Validierung | Pflichtfeld? | Kommentar | Anzeigereihenfolge |
|--------|--------------------|:-------------------------|----------------|-------------|-------------|--------------------|--------------|-----------|--------------------|
| 3.1    | Flag_Vergleich     | -                        | Radio          | keine       |             |                    | Ja           | -         | 1                  |
| 3.2    | Vergleichszins     | -                        | Freifeld       | keine       |             | -                  | Ja           | -         | 1                  |

 
Tabelle 11: Eingabeelemente - Sektion "Vergleich zur Hausbank"

#### 4.1.3.3 Angezeigte Elemente

<a id="tab11"></a>

| Bereich                  | Quelle Inhalt                | Sektion                 | Statisch / Dynamisch |
|--------------------------|------------------------------|-------------------------|----------------------|
| Titel, Untertitel, Text  | kfnLabelService.ts           | Kredit                  | Statisch             |

Tabelle 11: Angezeigte Elemente - Sektion "Vergleich zur Hausbank"

### 4.1.4 Sektion "Ergebnis - Ihre Angaben"

#### 4.1.4.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.4](./../Dokumentation/img/KFN_Sektion_4.1.4.png)

Abbildung 3: Layout - Sektion "Ergebnis - Ihre Angaben"

#### 4.1.4.2 Eingabe Elemente

| Nummer | Name des Attributs | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung | Quelle Validierung | Pflichtfeld? | Kommentar | Anzeigereihenfolge |
|--------|--------------------|:-------------------------|----------------|-------------|-------------|--------------------|--------------|-----------|--------------------|
| keine  |                    |                          |                |             |             |                    |              |           |                    |

 
Tabelle 11: Eingabeelemente - Sektion "Ergebnis - Ihre Angaben"

#### 4.1.4.3 Angezeigte Elemente

<a id="tab12"></a>

| Bereich                  | Quelle Inhalt                                                                                            | Sektion | Statisch / Dynamisch |
|--------------------------|----------------------------------------------------------------------------------------------------------|---------|----------------------|
| Titel, Untertitel, Text  | kfnLabelService.ts                                                                                       | -       | Statisch             |
| Nutzungsart              | Entsprechend Eingabe aus Kapitel 4.1.1                                                                   | -       | dynamisch            |
| Förderstufe              | Entsprechend Eingabe aus Kapitel 4.1.1                                                                   | -       | dynamisch            |
| Geförderte Wohneinheiten | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Kreditbetrag             | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Kreditart                | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Laufzeit in Jahren       | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Tilgungsfreie Anlaufzeit | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Zinsbindung              | Entsprechend Eingabe aus Kapitel 4.1.2                                                                   | -       | dynamisch            |
| Sollzins in %            | bei Auswahl "KfW-Zins" ekn-interest-nominal, bei "eigenem Zins" der in  2.8 gewählte Wert                | -       | dynamisch            |
| Vergleichszins           | erscheint nur bei Auswahl  "Vergleich zur Hausbank" ja - Entsprechend Eingabe aus Kapitel 4.1.3 Wert 3.2 | -       | dynamisch            |
Tabelle 12: Angezeigte Elemente - Sektion "Ergebnis - Ihre Angaben"

### 4.1.5 Sektion "Ergebnis - Ihr KFW-Kredit"

#### 4.1.5.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.5](./../Dokumentation/img/KFN_Sektion_4.1.5.png)

Abbildung 3: Layout - Sektion "Ergebnis - Ihr KFW-Kredit"

#### 4.1.5.2 Eingabe Elemente

| Nummer | Name des Attributs | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung | Quelle Validierung | Pflichtfeld? | Kommentar | Anzeigereihenfolge |
|--------|--------------------|:-------------------------|----------------|-------------|-------------|--------------------|--------------|-----------|--------------------|
| keine  |                    |                          |                |             |             |                    |              |           |                    |

 
Tabelle 11: Eingabeelemente - Sektion "Ergebnis - Ihr KFW-Kredit"

#### 4.1.5.3 Angezeigte Elemente

<a id="tab13"></a>

| Bereich                              | Quelle Inhalt                                                                                       | Sektion | Statisch / Dynamisch |
|--------------------------------------|-----------------------------------------------------------------------------------------------------|---------|----------------------|
| Titel, Untertitel, Text              | kfnLabelService.ts                                                                                  | -       | Statisch             |
| Kreditbetrag                         | Entsprechend Eingabe aus Kapitel 4.1.2                                                              | -       | dynamisch            |
| Tilgungsfreie Anlaufzeit             | Berechnung: {akt. Monat}{akt. Jahr} - {akt.Monat - 1 Monat}{akt. Jahr + "Wert Tilgungsfreie Jahre"} | -       | dynamisch            |
| Monatliche Rate (tilgungsfreie Zeit) | Tilgungsrechner REST Response Array: repaymentPlan.repayments[0].amount                             | -       | dynamisch            |
| Monatliche Rate (ab Tilgungsbeginn)  | Tilgungsrechner REST Response Array: erste Amount suchen der <> repaymentPlan.repayments[0].amount  | -       | dynamisch            |
| Effektiver Jahreszins                | Tilgungsrechner REST Response: interestRate                                                         | -       | dynamisch            |
| Anfänglicher Tilgungssatz            | Tilgungsrechner REST Reponse: initialRepaymentRate                                                  | -       | dynamisch            |
| Zinsbindung                          | Entsprechend Eingabe aus Kapitel 4.1.2                                                              | -       | dynamisch            |
| Restschuld                           | Kreditbetrag - Getilgter Betrag                                                                     | -       | dynamisch            |
| Getilgter Betrag                     | Tilgungsrechner REST Response Array: Summe aller repaymentPlan.repayments[0].amount                 | -       | dynamisch            |
| Geleistete Zinszahlungen             | Tilgungsrechner REST Response: totalInterestCost                                                    | -       | dynamisch            |

Tabelle 13: Angezeigte Elemente - Sektion "Ergebnis - Ihre Angaben"

### 4.1.6 Sektion "Ergebnis - Tabellarischer Tilgungsplan"

#### 4.1.6.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.6](./../Dokumentation/img/KFN_Sektion_4.1.6.png)

Abbildung 3: Layout - Sektion "Ergebnis - Tabellarischer Tilgungsplan"

#### 4.1.6.2 Eingabe Elemente

| Nummer | Name des Attributs | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung | Quelle Validierung | Pflichtfeld? | Kommentar | Anzeigereihenfolge |
|--------|--------------------|:-------------------------|----------------|-------------|-------------|--------------------|--------------|-----------|--------------------|
| keine  |                    |                          |                |             |             |                    |              |           |                    |

 
Tabelle 11: Eingabeelemente - Sektion "Ergebnis - Tabellarischer Tilgungsplan"

#### 4.1.6.3 Angezeigte Elemente

<a id="tab14"></a>

| Bereich                 | Quelle Inhalt                                     | Sektion | Statisch / Dynamisch |
|-------------------------|---------------------------------------------------|---------|----------------------|
| Titel, Untertitel, Text | kfnLabelService.ts                                | -       | Statisch             |
| Zeitraum                | Tilgungsrechner REST Response: date               | -       | dynamisch            |
| Rate                    | Tilgungsrechner REST Response: amount             | -       | dynamisch            |
| Zinsanteil              | Tilgungsrechner REST Response: interestRateAmount | -       | dynamisch            |
| Tilgung                 | Tilgungsrechner REST Response: repaymentAmount    | -       | dynamisch            |
| Restschuld              | Tilgungsrechner REST Response: balance            | -       | dynamisch            |

Tabelle 14: Angezeigte Elemente - Sektion "Ergebnis - Tabellarischer Tilgungsplan"

### 4.1.7 Sektion "Ergebnis - Vergleich zur Hausbank"

#### 4.1.7.1 Layout

<a id="abb3"> </a>

![KFN_Sektion.4.1.7](./../Dokumentation/img/KFN_Sektion_4.1.7.png)

Abbildung 3: Layout - Sektion "Ergebnis - Vergleich zur Hausbank"

#### 4.1.7.2 Eingabe Elemente

| Nummer | Name des Attributs | Geschäftsobjekt Attribut | Art des Inputs | Vorbelegung | Validierung | Quelle Validierung | Pflichtfeld? | Kommentar | Anzeigereihenfolge |
|--------|--------------------|:-------------------------|----------------|-------------|-------------|--------------------|--------------|-----------|--------------------|
| keine  |                    |                          |                |             |             |                    |              |           |                    |

 
Tabelle 11: Eingabeelemente - Sektion "Ergebnis - Vergleich zur Hausbank"

#### 4.1.7.3 Angezeigte Elemente

<a id="tab15"></a>

| Bereich                                                | Quelle Inhalt                                                    | Sektion | Statisch / Dynamisch |
|--------------------------------------------------------|------------------------------------------------------------------|---------|----------------------|
| Titel, Untertitel, Text                                | kfnLabelService.ts                                               | -       | Statisch             |
| Gesamtersparnis                                        | Tilgungsrechner REST SST Kap 4.2                                 | -       | dynamisch            |
| Sollzins p.a. (KfW-Kredit)                             | Wert aus Kapitel 4.1.2                                           | -       | dynamisch            |
| Sollzins p.a. (Kredit der Hausbank)                    | Wert aus Kapitel 4.1.3                                           | -       | dynamisch            |
| Effektiver Jahreszins (KfW-Kredit)                     | Tilgungsrechner REST Response 1: interestRate                    | -       | dynamisch            |
| Effektiver Jahreszins (Kredit der Hausbank)            | Tilgungsrechner REST Response 2: interestRate                    | -       | dynamisch            |
| Tilgungsfreie Anlaufzeit Jahre (KfW-Kredit)            | Wert aus Kapitel 4.1.2                                           | -       | dynamisch            |
| Tilgungsfreie Anlaufzeit (Kredit der Hausbank)         | Wert aus Kapitel 4.1.2 (identisch)                               | -       | dynamisch            |
| Anfänglicher Tilgungssatz (KfW-Kredit)                 | Tilgungsrechner REST SST Kap 4.2                                 | -       | dynamisch            |
| Anfänglicher Tilgungssatz (Kredit der Hausbank)        | Tilgungsrechner REST SST Kap 42                                  | -       | dynamisch            |
| Restschuld nach Zinsbindungsende (KfW-Kredit)          | Tilgungsrechner REST Response 1: Kreditbetrag - getilgter Betrag | -       | dynamisch            |
| Restschuld nach Zinsbindungsende (Kredit der Hausbank) | Tilgungsrechner REST Response 2: Kreditbetrag - getilgter Betrag | -       | dynamisch            |
| Verwendete Zinsbindung (KfW-Kredit)                    | Wert aus Kapitel 4.1.2                                           | -       | dynamisch            |
| Verwendete Zinsbindung (Kredit der Hausbank)           | Wert aus Kapitel 4.1.2                                           | -       | dynamisch            |

Tabelle 15: Angezeigte Elemente - Sektion "Ergebnis - Vorteilsrechner"

### 4.1.8 Berechnung Ergebnisausgabe

Für die Ergebnisausgabe in den Sektionen 4.1.4 bis 4.1.7 wird der Tilgungsrechner FS angesprochen.

Folgender Input wird von der Schnittstelle erwartet (InputRequestParametersDTO.java):

| Format                             | Parameter Name                   | Bedeutung                                                 | Überlieferter Wert                                                              |
|------------------------------------|----------------------------------|-----------------------------------------------------------|---------------------------------------------------------------------------------|
| private BigDecimal                 | loanAmount                       | Kreditbetrag                                              | 2.1 Kreditbetrag                                                                |
| private Date                       | disbursementDate                 | Auszahlungsdatum                                          | Aktuelles Datum (der FS arbeitet dann mit dem nächsten Monat)                   |
| private Date                       | firstRepaymentDate               | Datum erster Tilgungszahlung                              | Aktuelles Datum + 2.4 Tilgungsfreie Anlaufzeit + 1 Monat                        |
| private Date                       | firstInterestRateDate            | Datum erster Zinstermin                                   | = disbursementDate                                                              |
| private Date                       | endDateOfFixedInterestRatePeriod | Datum Zinsbindungsende                                    | Aktuelles Datum + 2.5 Zinsbindung + 1 Monat                                     |
| private Date                       | endDateOfLoanCall                | Datum Laufzeitende                                        | Aktuelles Datum + 2.3 Laufzeit + 1 Monat                                        |
| private int                        | repaymentProcess                 | Tilgungsverfahren (Schluessel 1522)                       | wenn Laufzeit == Tilgungsfreie Anlaufzeit -> 1 = endfällig sonst 2 annuitätisch |
| private int                        | interestRateDueDateCycle         | Faelligskeitsturnus (Schluessel 76)                       | 4 (monatlich)                                                                   |
| private List<InterestRateValues>   | interestRates                    | Wiederholungsgruppe Zins ({validFrom; interestRateValue}) | {firstInterestRateDate; gemäß Produktconfig "ekn-interest-nominal" }            |
| private Integer                    | repaymentGrantCalculationType    | Tilgungszuschuss Typ Berechnung                           | = 1 (dummywert, da kein Zuschuss)                                               |
| private List<RepaymentGrantValues> | repaymetGrants                   | Wiederholungsgruppe Tilgungszuschüsse                     | dummywerte, da kein Zuschuss                                                    |

Folgender Output wird geliefert (InterestRateAndRepaymentScheduleDTO.java):

| Format                      | Parameter Name          | Bedeutung                                   | Mapping                                                |
|-----------------------------|-------------------------|---------------------------------------------|--------------------------------------------------------|
| private BigDecimal          | interestRate            | Effektivzins                                | 4.1.5 Sektion "Ergebnis - Ihr KFW-Kredit"              |
| private BigDecimal          | initialRepaymentRate    | anfaenglicher Tilgungssatz                  | 4.1.5 Sektion "Ergebnis - Ihr KFW-Kredit"              |
| private RepaymentRate       | percentageRate          | anfaenglicher Tilgungssatz pro Jahr         |                                                        |
| private Date                | firstRepayment;         | Datum erster Tilgungszahlung                | 4.1.6 Sektion "Ergebnis - Tabellarischer Tilgungsplan" |
| private Date                | lastRepayment;          | Datum letzte Tilgungszahlung (Laufzeitende) |                                                        |
| private Integer             | numberOfRepayments;     | Anzahl an Zahlungen                         |                                                        |
| private BigDecimal          | totalLoanCost;          | Gesamtbetrag (Zins+Tilgung)                 |                                                        |
| private BigDecimal          | totalRepaymentCost      | Summe Tilgungen                             | 4.1.5 Sektion "Ergebnis - Ihr KFW-Kredit"              |
| private BigDecimal          | totalExtraRepaymentCost | Summe Sondertilgungen                       |                                                        |
| private BigDecimal          | totalInterestCost       | Summe Zinsen                                | 4.1.5 Sektion "Ergebnis - Ihr KFW-Kredit"              |
| private BigDecimal          | lastAnnuity             | Letzte Rate                                 |                                                        |
| private BigDecimal          | lastRepaymentPercentage | Letzter Tilgungssatz                        |                                                        |
| private List<RepaymentData> | repayments              | Array der Zahlungen                         | 4.1.6 Sektion "Ergebnis - Tabellarischer Tilgungsplan" |

RepaymentData (Array der Zahlungen)

| Format             | Parameter Name      | Bedeutung         |
|--------------------|---------------------|-------------------|
| private Date       | firstRepayment;     | Datum der Zahlung |
| private BigDecimal | amount;             | Gesamtzahlung     |
| private BigDecimal | balance;            | Restschuld        |
| private BigDecimal | repaymentAmount;    | Tilgung           |
| private BigDecimal | interestRateAmount; | Zins              |

### 4.1.9 Produkt- und Zinskonditionen

Für die Anzeige in 4.1.2 Sektion "Angaben zum Kredit" werden die Produkt- und Zinskonditionen von der internen und externe Produkt API bezogen.

Als mögliche Produktvariante gilt hierbei das Datenset aus Kreditart, Laufzeit, Tilgungsfreie Anlaufzeit, Zinsbindung. Zu jeder Produktvariante gibt es einen entsprechenden nominal und Effektivzins.
Die Produktvarianten werden aus der internen Produkt API bezogen, der zu der Produktvariante gehörige Zinssatz aus der externen Produkt API.

Weitere Informationen zu den Produkt APIs sind in Kapitel 6.1

Iterative Einschränkung via Auswahl

| Nr Attribut | Attribut                  | Logik                                                                                             |
|-------------|---------------------------|---------------------------------------------------------------------------------------------------|
| 2.2         | Kreditart                 | repaymentMethod (1=endfällig,2=annuitätisch)                                                      |
| 2.3         | Laufzeit                  | kompletter verfügbarer Bereich (Minimum von allen LoanTermMin und Maximum über alle LoanTermMax)  |
| 2.4         | Tilgungsfreie Anlaufjahre | entsprechend über die Laufzeit eingeschränkte Auswahl an Tilgungsfreien Anlaufjahren              |
| 2.5         | Zinsbindung               | entsprechend der durch die 3 vorherigen Attribute eingeschränkten nun eindeutigen Produktvariante |

### 4.1.10 Aufruf auf kfw.de

Die Anwendung wird als Overlay auf kfw.de dargestellt (siehe Screenshot Kapitel 2.2)
Dafür wird die Anwendung als iframe wiefolgt aufgerufen:

```
<iframe
        src="https://foerderservices.kfw.de/rechner/297-298"
        style="min-width: 100%; height: 70vh;"
      />
      `
```

# 5 Fremd- und Standardsoftwarekomponenten 

## 5.1 	Customizing
Nicht relevant

## 5.2	Fehlerhandling
Nicht relevant

## 5.3	Komponentensicht: Frontend
### 5.3.1 Enthaltene Komponenten

Die folgende Komponenten sind Teil des Moduls:

<a id="tab16"></a>

| Name                      | Verantwortlich                                                                                                                           | Intern¹ | Referenz                                                                                                      |
|---------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------|:-------:|:--------------------------------------------------------------------------------------------------------------|
| Azure Application Gateway | Application Gateway stellt dem Nutzer das Frontend bereit                                                                                |  Nein   | [Azure Application Gateway webpage](https://azure.microsoft.com/en-us/products/application-gateway/#overview) |
| Webpage Content           | Die Webseite besteht aus HTML und Javascript (inklusiv relevante Frameworks) Datein und andere statische Inhalte                         |   Ja    | [frontend code](https://dev.azure.com/3adev/Meine-KfW/_git/Meine-KfW?path=/app/frontend)                      |
| React                     | Javascript UI Framework ist für die Erstellung von dynamischen Webseiten relevant                                                        |  Nein   | [React webpage](https://reactjs.org/)                                                                         |
| MaterialUI                | Javascript Frontend rendert Framework für React                                                                                          |  Nein   | [Material UI webpage](https://material-ui.com/)                                                               |
| final-form                | Javascript Framework für die Verwaltung des Formularstatus                                                                               |  Nein   | [Final Form webpage](https://github.com/final-form/final-form)                                                |
| axios                     | Javascript Framework für die HTTP Kommunikation                                                                                          |   No    | [Axios webpage](https://github.com/axios/axios)                                                               |

Tabelle 16: Enthaltene Komponente im Frontend

\*: zeigt an welche Komponente öffentlich/intern verfügbar ist

### 5.3.2 Ressourcen

| NAME                                                     | TYPE                           | RESOURCE GROUP     | CREATEDBY (TAG) |
|----------------------------------------------------------|--------------------------------|--------------------|-----------------|
| Application Insights Smart Detection                     | Action group                   | rg-kfnrechner-test |                 |
| as-kfnrechner-test-001                                   | App Service                    | rg-kfnrechner-test | Terraform       |
| plan-kfnr-test-001                                       | App Service plan               | rg-kfnrechner-test | Terraform       |
| agw-kfnrechner-test                                      | Application gateway            | rg-kfnrechner-test | Terraform       |
| waf-kfnrechner-test                                      | Application Gateway WAF policy | rg-kfnrechner-test | Terraform       |
| appi-kfnrechner-test                                     | Application Insights           | rg-kfnrechner-test |                 |
| tilgungsrechner-wbs.test.3adev.net                       | DNS zone                       | rg-kfnrechner-test |                 |
| kv-kfnrechner-test                                       | Key vault                      | rg-kfnrechner-test | Terraform       |
| log-kfnr-test                                            | Log Analytics workspace        | rg-kfnrechner-test | Terraform       |
| id-kfnrechner-test-agw-kv                                | Managed Identity               | rg-kfnrechner-test | Terraform       |
| id-kfnrechner-test-st-kv                                 | Managed Identity               | rg-kfnrechner-test | Terraform       |
| id-kfnrechner-test-webapp-001                            | Managed Identity               | rg-kfnrechner-test | Terraform       |
| pe-kfn-test-001.nic.080169ba-026d-4005-a1ea-cc926829a7ae | Network Interface              | rg-kfnrechner-test | Terraform       |
| pe-kfn-test-002.nic.0e0d836b-1084-4cc3-a6b5-3fe2f13d7bf8 | Network Interface              | rg-kfnrechner-test | Terraform       |
| pe-kfn-test-003.nic.3a353a3a-853a-4d0e-a53a-963874968e9e | Network Interface              | rg-kfnrechner-test | Terraform       |
| nsg-kfnrechner-test-backend-tier-endpoints               | Network security group         | rg-kfnrechner-test |                 |
| nsg-kfnrechner-test-front-tier                           | Network security group         | rg-kfnrechner-test |                 |
| nsg-kfnrechner-test-middle-tier-endpoints                | Network security group         | rg-kfnrechner-test |                 |
| nsg-kfnrechner-test-middle-tier-server-farms             | Network security group         | rg-kfnrechner-test |                 |
| tilgungsrechner-wbs.test.azn.kfwbank.cloud               | Private DNS zone               | rg-kfnrechner-test |                 |
| pe-kfn-test-001                                          | Private endpoint               | rg-kfnrechner-test | Terraform       |
| pe-kfn-test-002                                          | Private endpoint               | rg-kfnrechner-test | Terraform       |
| pe-kfn-test-003                                          | Private endpoint               | rg-kfnrechner-test | Terraform       |
| pip-kfnrechner-test                                      | Public IP address              | rg-kfnrechner-test | Terraform       |
| rt-kfnrechner-test-front-tier                            | Route table                    | rg-kfnrechner-test |                 |
| rt-kfnrechner-test-spoke                                 | Route table                    | rg-kfnrechner-test |                 |
| Failure Anomalies - appi-kfnrechner-test                 | Smart detector alert rule      | rg-kfnrechner-test |                 |
| sakfwtrwbstest                                           | Storage account                | rg-kfnrechner-test | Terraform       |
| sakfwtrwbstestmgnt                                       | Storage account                | rg-kfnrechner-test |                 |
| stkfwtrwbstestmgnt                                       | Storage account                | rg-kfnrechner-test |                 |
| vnet-kfnrechner-test-spoke                               | Virtual network                | rg-kfnrechner-test |                 |
| flow-log-nsg-kfnrechner-test-backend-tier-endpoints      | Flow log                       | networkwatcherrg   |                 |
| flow-log-nsg-kfnrechner-test-front-tier                  | Flow log                       | networkwatcherrg   |                 |
| flow-log-nsg-kfnrechner-test-middle-tier-endpoints       | Flow log                       | networkwatcherrg   |                 |
| flow-log-nsg-kfnrechner-test-middle-tier-server-farms    | Flow log                       | networkwatcherrg   |                 |
| NetworkWatcher_westeurope                                | Network Watcher                | networkwatcherrg   |                 |



# 6	Schnittstellenbeschreibung und Anforderungen an andere Funktionen 

| Name der Schnittstelle | In | Out | Zweck              | Referenz                                                                            |
|------------------------|----|-----|--------------------|-------------------------------------------------------------------------------------|
| interne Produkt API    | x  |     | Produktkonditionen | NICHT SCOPE DES MVPS - [Swagger](https://services-vsp.kfw.kfwgruppe.net/produktdefinition-rest/index.html) |
| externe Produkt API    | x  |     | Zinskonditionen    | NICHT SCOPE DES MVPS - [Swagger](https://public.kfw.de/produktdefinition-rest/index.html)               |
| Tilgungsrechner REST   | x  |     | Tilgungsplan       |                                                                                     |

Schnittstellenübersicht
<a id="tab15"> </a>

## 6.1	Schnittstelle interne Produkt API
Für jedes Produkt werden die Produktkonditionen und Produktvarianten (verschiedene Kombinationen aus Laufzeit (loanTerm), Tilgungsfreie Jahre (GracePriod) und Kreditart (repaymentMethod)) ausgelesen.
Die API ist hier zu finden https://services-vsp.kfw.kfwgruppe.net/produktdefinition-rest/index.html

(Die API wird täglich durch eine Azure Function abgerufen- NICHT SCOPE DES MVPs, aktuell noch manuelle Ablage). Die Response wird in einem Blob-Storage abgelegt und dem Frontend zur Verfügung gestellt.

Beispiel Response für Programm 297

```
{
  "productnumber": 297,
  "name": "KFN Wohngebäude - private Selbstnutzung",
  "status": "open",
  "max amount limit": 150000,
  "purposes": [
    {
      "vsp code": 569,
      "name": "Klimafreundliches Wohngebäude"
    },
    {
      "vsp code": 570,
      "name": "Klimafreundliches Wohngebäude QNG"
    }
  ],
  "variants": [
    {
      "interestConditionId": 245096750432214,
      "loanTermMin": 11,
      "loanTermMax": 25,
      "gracePeriodMin": 1,
      "gracePeriodMax": 3,
      "fixedInterestRatePeriod": 10,
      "onLending": 1,
      "investmentPlace": 3,
      "fixedInterestRateType": 1,
      "repaymentSchedule": 4,
      "interestSchedule": 4,
      "repaymentMethod": 2,
      "stateAid": 3,
      "commitmentCommission": 1.8,
      "commissionFreeMonths": 12,
      "unscheduledRepaymentPossibility": 3,
      "disbursementRate": 100
    },
    {
      "interestConditionId": 452808750432202,
      "loanTermMin": 26,
      "loanTermMax": 35,
      "gracePeriodMin": 1,
      "gracePeriodMax": 5,
      "fixedInterestRatePeriod": 10,
      "onLending": 1,
      "investmentPlace": 3,
      "fixedInterestRateType": 1,
      "repaymentSchedule": 4,
      "interestSchedule": 4,
      "repaymentMethod": 2,
      "stateAid": 3,
      "commitmentCommission": 1.8,
      "commissionFreeMonths": 12,
      "unscheduledRepaymentPossibility": 3,
      "disbursementRate": 100
    },
  ]
}
```

Diese Abfrage wird für Programm 297 und 298 durchgeführt und in einem JSON vereint.

## 6.2	Schnittstelle externe Produkt API
Zu jeder Produktvariante werden die tagesaktuellsten Zinskonditionen ausgelesen. Der Identifier für den zu einer Produktvariante gehörigen Zinssatz ist die interestConditionId.
Die API ist hier zu finden: https://public.kfw.de/produktdefinition-rest/index.html

Beispiel Response für die Produktvariante (Laufzeit 26-35 Jahre, Tilgungsfreie Anlaufzeit 1-5, monatliche Rückzahlung) 452808750432202 für den 2023-10-26

```
{
  "ekn-interest-nominal": 1.23,
  "ekn-interest-effective": 1.24
}
```

Für jede interestConditionId wird der entsprechende Zinsatz abgefragt und in einem JSON in der Reihenfolge der Abfrage vereint

## 6.3	Tilgungsrechner REST Schnittstelle
Der Zinstilgplan zur Anzeige der Ergebnisse (Kapitel 4.1.4 - 4.1.7) wird von der Tilgungsrechner REST Schnittstelle bezogen. 

Responseformat:

```
export interface MainResultForm {
activeStep: string;
stepOneCompleted: boolean;
stepTwoCompleted: boolean;
stepThreeCompleted: boolean;
resultProgram: string;
resultFunding: string;
resultResidentialUnits: number;
resultCreditAmount: number;
resultCreditType: 'Annuitätendarlehen' | 'Endfällig';
resultDuration: string;
resultFreeYears: string;
resultFixedInterestRates: string;
resultCreditProvider: string;
resultInterestRates: string;
resultInterestRatesAmount: number;
resultCompare: string;
resultCompareInterestRatesAmount: string;
}
```

# 7	Jobkomplexe und Batches/Jobs

Nicht relevant.

# 8	Applikationsbetrieb

## 8.1	Konfiguration

Alle Komponenten in der Cloud werden mit Terraform erstellt/konfiguriert. Die wenigen zusätzlichen Konfigurationen werden mit Bash und Powershell Scripts durchgeführt. 
Für eine detaillierte Übersicht der Konfigurationsmöglichkeiten s. Terraform.


KFN_INFRASTRUCTURE_DEV

| Name                     | Value                                                                                 | Beschreibung |
|--------------------------|---------------------------------------------------------------------------------------|--------------|
| BLOB_CONTAINER_NAME      | st-con-kfnrechner-products                                                            | -            |
| EXTERNAL_PRODUCT_API_URL | https://public-ent07.kfw.kfwgruppe.net/produktdefinition-rest/index.html              | -            |
| INTERNAL_PRODUCT_API_URL | https://kfw-f-vm3vspwas-le01.kfw.kfwgruppe.net:7443/produktdefinition-rest/index.html | -            |
| STORAGE_ACCOUNT_ENDPOINT | https://sakfwtrwbsdev.blob.core.windows.net/                                          | -            |
| TILGUNGSRECHNER_API_URL  | https://public.kfw.de                                                                 | -            |

KFN_INFRASTRUCTURE_TEST

| Name                     | Value                                                                                 | Beschreibung |
|--------------------------|---------------------------------------------------------------------------------------|--------------|
| BLOB_CONTAINER_NAME      | st-con-kfnrechner-products                                                            | -            |
| EXTERNAL_PRODUCT_API_URL |                                                                                       | -            |
| INTERNAL_PRODUCT_API_URL |                                                                                       | -            |
| STORAGE_ACCOUNT_ENDPOINT | https://sakfwtrwbstest.blob.core.windows.net/                                         | -            |
| TILGUNGSRECHNER_API_URL  | https://public.kfw.de                                                                 | -            |

KFN_INFRASTRUCTURE_PROD
| Name                     | Value                                                                    | Beschreibung |
|--------------------------|--------------------------------------------------------------------------|--------------|
| BLOB_CONTAINER_NAME      | st-con-kfnrechner-products                                               | -            |
| EXTERNAL_PRODUCT_API_URL | https://public.kfw.de/produktdefinition-rest/index.html                  | -            |
| INTERNAL_PRODUCT_API_URL | https://services-vsp.kfw.kfwgruppe.net/produktdefinition-rest/index.html | -            |
| STORAGE_ACCOUNT_ENDPOINT | https://sakfwtrwbstest.blob.core.windows.net/                            | -            |
| TILGUNGSRECHNER_API_URL  | https://public.kfw.de                                                    | -            |

Konfiguration <Bezeichnung Komponente>
<a id="tab16"> </a>

## 8.2	Configuration Items
Nicht relevant, da alle Infrastruktur-Konfigurationen in Terraform vorgenommen werden.

## 8.3	Deployment
Die Deploymentanweisung [LINK Deploymentanweisung](https://kfw-f-dmswebp.kfw.kfwgruppe.net/dms_kfw/exe/eb.exe?cfgs=../cfgs/dmsapi.cfg&p=d&MaskName=dopendoc&docid=d3be8fe6a-848b-11ee-8b51-ba4d577a6b9a)
Weitere Informationen sind im Betriebshandbuch, den README Dateien in den Repositories oder dem Azure DevOps Wiki des Projektes zu finden.

## 8.4	Logging/Error-Codes
Logging innerhalb des KFN-Rechners erfolgt mittels Azure App Insights. Die Protokolle werden entweder direkt von Azure Gateway, Azure App Service oder anderen Azure-Diensten gesammelt. Diese Log-Dateien werden in einem Azure Analytics Log-Workspace und einem Azure Blob-Storage gespeichert.

| Komponente | Logging-Mechanismus   |
|------------|-----------------------|
| Alle       | Azure Monitor/Insight |

Übersicht Logging der Komponenten
<a id="tab17"> </a>

### 8.4.1	Übersicht

Nicht relevant.

### 8.4.2	Applikation/Funktion/Batch 

Nicht relevant.

## 8.5	Infrastruktur Beschreibung

Die Cloud-Infrastruktur der Applikation liegt in der Landing Zone KFN Rechner <STAGE> und besteht aus einer Resource-Gruppen:
- rg-kfnrechner-<stage>: alle Resourcen der Applikation, wie die App Services für Frontend, Middleware und Backend, das Application Gateway und der Storage Accounts etc.

Des Weiteren werden folgende Resourcengruppen automatisch angelegt, um den Compliance Standards der KfW zu genügen:
-	NetworkWatcherRG: automatisch angelegte Resourcengruppe. Sie beinhaltet alle Resourcen zu Networkwatchern z.B. Flow Logs
-	DefaultResourceGroup-WEU: automatisch angelegte Resourcengruppe. Sie beinhaltet alle Resourcen zu Security z.B. ThreatProtection

Alle Resourcen sind an einem VNet verbunden (anhand VNet Integration und/oder Private Endpoints/Links). Das VNet enthält 5 Subnets um die Ressourcen von jedem Teil der Applikation entsprechend aufteilen zu können (Frontend, Backend, Middleware, Application Gateway, Private Endpoints). 
Jedes Subnet hat eine Network Security Group die standardmäßig die Kommunikation zwischen Subnets im VNet erlaubt aber blockiert Inbound-Netzwerk-Verkehr aus dem Public-Internet. Die einzige Ausnahme ist das subnet-sanr-dev-004 an dem die Applikation Gateway verbunden ist, von daher werden die nötigen Ports entsprechend eingestellt.
Eine dedizierte Key-Vault pro Umgebung speichert Secrets und Zertifikate der Applikation (z.B. TLS-Zertifikate für die Applikation Gateway werden in der Key-Vault von rg-sanr-dev Resource-Gruppe abgelagert).
Alle Cloud-Resourcen verweigern Inbound-Netzwerk-Verkehr aus dem Public-Internet anhand Private Endpoints und/oder Private Links. Die einzigen Ausnahmen sind:
-	Application Gateway, die erlaubt dem User Zugriff auf das Frontend der Applikation (und indirekt auch auf die Middleware, mit Anfragen durch das Frontend.)

Das Frontend der Applikation ist eine React-App die in einem App Service ausgeführt wird und den Nutzern durch das Application Gateway zur Verfügung gestellt wird. 

Die Applikation besteht aus den folgenden Einzelkomponenten:
-	Applikation Gateway
-	Frontend

Des Weiteren gibt es eine umfangreiche Buildstrecke bestehend aus:
- Frontend Codebase & Pipeline (MeineKFW Portal DevOps https://dev.azure.com/3adev/_git/Meine-KfW-Portal)
- IaC Codebase & Pipeline (Tilgungsrechner-WBS DevOps https://dev.azure.com/3adev/Tilgungsrechner-WBS/_git/KfN-Rechner-Infrastructure)

### 8.5.1	Run

#### 8.5.1.1	Applikation Gateway

Das Applikation Gateway dient als Single Entry Point für die Applikation. Die Anwendung ist in Produktion lediglich über diesen Endpunkt erreichbar. Anfragen an das Application Gateway werden an das Frontend weitergeleitet.
Der Nutzer greift auf die Applikation mittels HTTPS zu und erhält eine Website im Browser.

#### 8.5.1.2	Frontend

Das Frontend läuft innerhalb des Azure App Services. Das Frontend ist eine auf Node.js basierende React Webanwendung, die über Azure DevOps deployed wird. Die notwendigen Daten nach Absenden einer Anfrage im Web Frontend werden an die Middleware gesendet, die diese an das Backend weiterleitet. 


 ### 8.5.2	Deployment

Infrastruktur:

- KfN-Rechner-Infrastructure DEV
- KfN-Rechner-Infrastructure TEST

Frontend:

- KfN-Rechner Frontend Build
- KfN-Rechner Frontend Release

Codebase:
- 3adev/Tilgungsrechner-WBS/Repos/Files/KfN-Rechner-Infrastructure
- 3adev/Tilgungsrechner-WBS/Repos/Files/KfN-Rechner-Pipelines


# 9	Querschnittsthemen

| Kapitel | Bereich/ Fachverfahren                                                                                    | Relevanz |
|---------|-----------------------------------------------------------------------------------------------------------|----------|
| 9.1     | Berechtigungskonzept                                                                                      | 1        |
| 9.2     | Datenschutz und IT Sicherheit* *(Wie von IT-Sicherheit gewünscht, erfolgte Abstimmung mit Cloud Security) | 1        |
| 9.3     | Auditing                                                                                                  | 1        |

<a id="tab20"> </a>
Übersicht der übergreifenden Anforderungen


## 9.1	Berechtigungskonzept

Bezüglich des Berechtigungskonzepts ist das aBK führend und die folgenden Daten sind hier nur ergänzend zu sehen.
Es gibt keine Benutzeridentifizierung bzw. Authentifizierung. Die Anwendung ist durch jede Person aufrufbar, welche über die Sanierungsrechner-URL verfügt. Die URL wird über das KfW-Partnerportal für die Bankpartner der KfW zur Verfügung gestellt. 

### 9.1.1	Angaben zur Benutzeridentifizierung bzw. –authentifizierung
Nicht relevant

### 9.1.2	Prozess der Provisionierung der Berechtigungen
Nicht relevant

### 9.1.3	Namenskonventionen für Kennungen
Nicht relevant

### 9.1.4	Beschreibung der Einzelberechtigungen, technischen Berechtigungen und Rollen
Nicht relevant

### 9.1.5	Besondere Kennungen
Nicht relevant

### 9.1.6	Prozess der Berechtigungsvergabe
Nicht relevant

### 9.1.7	Angabe toxischer Berechtigungskombinationen
Nicht relevant

### 9.1.8	Privilegierte Berechtigungen
Nicht relevant

## 9.2	Datenschutz und IT Sicherheit

### 9.2.1	Datenschutz
Es werden keine personenbezogenen Daten (i.S. des Art. 4 EU-DSGVO) abgefragt, verwendet oder gespeichert.
Die Datenverarbeitung in der Applikation dient ausschließlich der Erfüllung des Anwendungszwecks. 
Nutzer geben im Frontend Daten zu ihrem Kredit ein, die über eine sichere Verbindung (HTTPS) an das Backend übertragen werden. 

### 9.2.2	IT-Sicherheit
Die folgenden Aspekte sind im Kontext der IT-Sicherheit relevant: 
•	Nur über Gateway erreichbar
•	Web Application Firewall (WAF) des Application Gateways
•	Private Endpoints sichern Azure Services
•	NSGs (Network Security Groups)
•	RBAC (Role Based Access Control)
•	KfW Cloud Compliance Policies
•	HTTPS
•	Standardsecurity Azure
•	Keine Abhängigkeit zu anderen Systemen
•	Keine OnPremise Verbindungen
•	Keine kritische Datenverarbeitung

#### 9.2.2.1	Allgemein
Die Anwendung verarbeitet keine personenbezogenen Daten und keine Unternehmensdaten, sondern lediglich die Eingabedaten ohne Metadaten (IP, Absender, Kunde, etc). Des Weiteren hat das System keine Schnittstellen oder Abhängigkeiten zu anderen Systemen sowohl innerhalb der KfW als auch außerhalb. Es ist bereits out-of-the-box eine sehr geringe Angriffsfläche gegeben, da die Applikation (und APIs) aus dem Public Internet durch die Application Gateway + Web Application Firewall aufgerufen wird.

#### 9.2.2.2	Plattform

Um das Angriffsfeld weiter zu reduzieren, ist das System lediglich über das Applikation Gateway erreichbar, welches mit dem Frontend kommuniziert. Die restlichen Systeme (Backend, Datenhaltung, etc…) sind nicht direkt ansprechbar.
Entsprechend den modernen Standards und den Anforderungen an moderne KfW Applikationen erfolgt die Kommunikation nach außen wie auch innerhalb der Services stehts mittels HTTPS.
Die notwendigen Anforderungen entsprechend der VIV Einstufung von 1-2-2 sind berücksichtigt worden und entsprechend umgesetzt.
Durch das Deployment in Azure ist natürlich auch bereits durch die Plattform ein hoher Sicherheitsstandard gegeben, da in den SLAs der Plattform die Sicherheit der Einzelnanwendungen berücksichtigt ist.

#### 9.2.2.3	Anwendung
Die Entwicklung der Anwendung erfolgt in getrennten Repositories auf die nur die relevanten Entwickler Zugriff erhalten. In der ersten Releaseversion, wurden keine eigenen Entwicklungen durchgeführt, sondern nur bestehende Codebasen externer Dienstleister internalisiert. Lediglich kleinere optische Anpassungen sowie die Entfernung des Logins, da dieser nicht den KfW Standards genügte, wurden vorgenommen. Um hier das Thema Sicherheit tiefer zu beleuchten, wird im Rahmen der für Cloudanwendungen notwendigen Pen-Tests auch ein Codereview aller installierten Anwendungsbibliotheken durch externe Experten beantragt und die Optimierungsbefunde in die Applikation integriert.
Bei jedem Build wird ein bestimmter Schritt ausgeführt, um sicherzustellen, dass die Infrastruktur auf bekannte Sicherheitsprobleme geprüft werden (Checkov). Werden kritische Probleme entdeckt, wird die Build-Pipeline mit einer Fehlermeldung gestoppt, wodurch das Entwicklungsteam sofort alarmiert wird. Auf diese Weise wird sichergestellt, dass bekannte Schwachstellen nicht in der Produktion eingesetzt werden.
HTTP response headers Die Web Application Firewall von der Application Gateway implementiert den OWASP 3.1 Standard der 181 Regeln enthaltet um die Anwendung vor Angriffe entsprechend zu schützen.
NSGs - Netzwerksicherheitsgruppen Azure-Netzwerksicherheitsgruppen werden verwendet, um den Netzwerkverkehr zu und von Azure-Ressourcen in einem virtuellen Azure-Netzwerk zu filtern. Eine Netzwerksicherheitsgruppe enthält Sicherheitsregeln, die eingehenden Netzwerkverkehr zu bzw. ausgehenden Netzwerkverkehr von verschiedenen Arten von Azure-Ressourcen zulassen oder verweigern. Die Netzwerksicherheitsgruppe wird von Terraform eingerichtet.

## 9.3	Auditing
Gegenwärtig können die folgenden Informationen für die Prüfung verwendet werden:
Azure Application Insights dienen als zentrale Protokollierungs- und Überwachungslösung zum Sammeln aller Anwendungsprotokolle und enthalten auch mehrere Dashboards zur Überwachung der Benutzeraktivitäten (wie Anfragen usw.). In den Protokollanforderungen werden keine persönlichen Informationen gespeichert.
Entsprechend der Anforderungen der KfW an Cloud Applikationen wird die Anwendung einem Pen-Test unterzogen.

### 9.3.1 Datenmigration
Nicht relevant.

# 10	Offene Punkte und Entscheidungsbedarf
|Nr.|	Offener Punkt|	eingestellt am|	Lösung|	Verantwortlicher|
|----------------------|-------------|----------------------|-------------|-------------|					

<a id="tab22"> </a>
Offene Punkte