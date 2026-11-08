# Zucker und Mostgewicht

Diese Datei behandelt alles rund um den Zucker: die Reifebeprobung im Weingarten, die Messung des Mostgewichts mit Refraktometer und Mostwaage, die Umrechnung zwischen °KMW, °Oechsle, °Brix, Dichte, Zuckergehalt und potenziellem Alkohol, die Gärkontrolle und die Bestimmung des Restzuckers. Am Ende stehen die Geschmacksangaben nach EU-Recht und die österreichischen Mindestmostgewichte.

Grundlagen zu Probenahme, Volumenmessung und Sicherheit stehen in [Laborpraxis: Grundlagen](grundlagen-labor.md).

## Kurzfassung

- **Was:** Mostgewicht (°KMW, °Oe, °Brix) bei Reifebeprobung, Lese und Gärung; Restzucker im Wein.
- **Geräte:** Refraktometer für Beeren und Most (Sekunden pro Messung), Mostwaage (Aräometer) für Most und Gärkontrolle. Sobald Alkohol entsteht, zeigt das Refraktometer zu viel Zucker an; für die Gärkontrolle deshalb die Mostwaage verwenden.
- **Umrechnung:** °Oe = °KMW × (0,022 × °KMW + 4,54). Faustregeln: 1 °KMW ≈ 5 °Oe ≈ 1,18 °Brix. Zuckergehalt und potenzieller Alkohol aus dem Mostgewicht sind **Schätzungen**: Je nach Formel weichen sie bei gleichem Mostgewicht um 10–20 g/L Zucker bzw. 0,6–1,2 % vol voneinander ab.
- **Restzucker:** Zahlen liefern die Kupfer-Iod-Methode nach Rebelein (Genauigkeit etwa ± 0,5 g/L, nicht belegt) oder der Enzymtest. Fehling-Probe und Clinitest sind nur grob. Glucose-Teststreifen erfassen keine Fructose und sind für das Gärende ungeeignet.
- **Recht:** Geschmacksangaben nach VO (EU) 2019/33 (trocken höchstens 4 g/L, mit Säureregel bis 9 g/L; halbtrocken bis 12 g/L bzw. 18 g/L; lieblich bis 45 g/L; süß ab 45 g/L). Mindestmostgewichte nach Weingesetz 2009: Landwein 14 °KMW, Qualitätswein 15 °KMW, Kabinett 17 °KMW, Spätlese 19 °KMW, Auslese 21 °KMW, Beerenauslese und Eiswein 25 °KMW, Ausbruch 27 °KMW, Trockenbeerenauslese 30 °KMW.
- **Aufwand und Kosten:** Refraktometer und Mostwaage sind günstig und in Minuten bedient. Die Rebelein-Methode braucht etwa 20–30 Minuten, Kochplatte und Bürette.

## 1. Wozu?

Der Zuckergehalt ist die wichtigste Messgröße zwischen Weingarten und Flasche:

- **Lesezeitpunkt:** Zusammen mit Säure, pH-Wert, Traubengesundheit und Beerenverkostung entscheidet das Mostgewicht über den Lesetermin (siehe [Säure und pH](saeure-ph.md)).
- **Qualitätsstufe:** Das österreichische Weingesetz legt Mindestmostgewichte in °KMW fest (Abschnitt 9).
- **Kellerentscheidungen:** Anreicherung (nur innerhalb der rechtlichen Grenzen und nicht bei Kabinett und Prädikatswein), Gärführung, Abschätzung des Alkoholgehalts.
- **Gärkontrolle:** Der tägliche Abfall des Mostgewichts zeigt, ob die Gärung gesund läuft oder stockt.
- **Restzucker:** Er bestimmt die Geschmacksangabe auf dem Etikett (Abschnitt 8) und das Risiko einer Nachgärung in der Flasche.

## 2. Begriffe und Einheiten

| Größe | Einheit | Bedeutung |
|---|---|---|
| Mostgewicht nach Klosterneuburger Mostwaage | °KMW | In Österreich gebräuchlich. Die Skala wurde 1861 von August Wilhelm Freiherr von Babo in Klosterneuburg auf Grundlage des Saccharometers nach Balling entwickelt [5]. Sie zeigt näherungsweise den Zuckergehalt in Gramm je 100 g Most (Massenprozent); ein pauschaler Anteil an Nichtzuckerstoffen ist dabei schon abgezogen. |
| Mostgewicht nach Oechsle | °Oe | Um wie viel Gramm ein Liter Most schwerer ist als ein Liter Wasser, bezogen auf 20 °C: °Oe = (relative Dichte d20/20 − 1) × 1000. In Deutschland und der Schweiz gebräuchlich. |
| Brix | °Brix | Gramm Saccharose in 100 g Lösung. Refraktometer messen die Lichtbrechung; die Brix-Skala beruht auf reinen Saccharoselösungen. Im Most erfasst sie alle gelösten Stoffe (Zucker, Säuren, Mineralstoffe) als „Saccharose-Gleichwert“. |
| Dichte | g/mL | ρ20 ist die Dichte bei 20 °C. Die relative Dichte d20/20 ist die Dichte geteilt durch die Dichte von Wasser bei 20 °C (0,99820 g/mL). |
| Zuckergehalt | g/L oder g/kg | Glucose und Fructose; g/L = g/kg × Dichte. |
| Potenzieller Alkoholgehalt | % vol | Volumen reinen Alkohols bei 20 °C, das bei vollständiger Vergärung des Zuckers in 100 Volumen des Erzeugnisses entstehen könnte [11]. Umrechnung: **16,83 g/L Zucker = 1 % vol** (Grundlage der OIV-Tabelle, z. B. 191,9 g/L = 11,40 % vol) [1]. |
| Vorhandener Alkoholgehalt | % vol | Tatsächlich enthaltener Alkohol (siehe [Alkohol](alkohol.md)). |
| Gesamtalkoholgehalt | % vol | Vorhandener plus potenzieller Alkoholgehalt [11]. |
| Natürlicher Alkoholgehalt | % vol | Gesamtalkoholgehalt vor einer Anreicherung [24]. |
| Restzucker | g/L | Im Wein verbliebener Zucker. Für die Geschmacksangaben zählt die Summe aus Glucose und Fructose [9]. |
| Reduzierende Zucker | g/L | Was Kupfer-Methoden erfassen: Glucose, Fructose, aber auch unvergärbare Zucker (Pentosen) und andere reduzierende Stoffe. Meist etwas höher als Glucose + Fructose. |

> **Achtung:** °KMW und °Brix sind nicht dasselbe. 20 °KMW entsprechen etwa 23,7 °Brix (Abschnitt 5). Die gelegentlich zu lesende Gleichsetzung „1 °KMW ≈ 1 °Brix“ ist falsch.

> **Achtung:** Tabellen geben die Dichte manchmal als ρ20 in g/mL an, nicht als relative Dichte. Beispiel: ρ20 = 1,0818 g/mL entspricht d20/20 = 1,0838 und damit 83,8 °Oe, nicht 81,8 °Oe (eigene Rechnung).

## 3. Reifebeprobung im Weingarten

### 3.1 Beerenprobe oder Traubenprobe?

| | Beerenprobe | Traubenprobe |
|---|---|---|
| Was | einzelne Beeren von vielen Trauben und Stöcken | ganze Trauben von mehreren Stöcken |
| Menge | 100–200 Beeren je Fläche und Sorte [16–18] | mehrere ganze Trauben (Praxisvorschlag: mindestens 10, nicht belegt) |
| Vorteile | wenig Traubenverlust, leicht zu tragen, schnell zu pressen | bildet das Lesegut besser ab, auch unreife und faule Beeren einer Traube |
| Nachteile | Gefahr, unbewusst die schönsten und reifsten Beeren zu pflücken | mehr Arbeit, mehr Ernteverlust, Pressen aufwendiger |
| Geeignet für | laufende Reifeverfolgung | Entscheidung kurz vor der Lese, Kontrolle der Beerenproben |

Ein Großteil der Unterschiede zwischen Proben kommt von der Lage der Traube am Stock und davon, ob sie in der Sonne oder im Schatten hängt [19].

### 3.2 Durchführung der Beerenprobe

1. **Fläche festlegen:** Je Sorte und einheitlicher Fläche eine eigene Probe. Unterschiedlich reifende Teile (Hangfuß, Kuppe, junge Anlage) getrennt beproben.
2. **Weg festlegen:** Randzeilen und die ersten Stöcke einer Zeile auslassen [17, 18]. In großen Flächen nach einem Raster vorgehen, zum Beispiel jeden 10. Stock in jeder 10. Zeile; dabei mindestens 10 % der Stöcke einbeziehen [16].
3. **Beeren auswählen:** Von mindestens 20 Trauben [18], abwechselnd von beiden Zeilenseiten (Sonnen- und Schattenseite) und aus dem oberen, mittleren und unteren Teil der Traube pflücken [17, 18]. Nicht nur die größten oder am leichtesten erreichbaren Beeren nehmen [17]. Beschädigte oder durch Regen aufgeplatzte Beeren auslassen [27].
4. **Menge:** 100 Beeren als Minimum, 200 bei ungleichmäßigen Anlagen (zum Beispiel nach Trockenstress oder Hagel) [16, 17]. Eine Schnellprobe mit 15–30 Beeren gibt nur eine grobe Orientierung [27].
5. **Zeitpunkt:** Möglichst immer zur gleichen Tageszeit und nicht direkt nach starkem Regen, wenn die Beeren Wasser aufgenommen haben.
6. **Transport:** In einen beschrifteten Gefrierbeutel geben, kühl und schattig transportieren und am selben Tag verarbeiten.
7. **Optional:** 100 Beeren wiegen. Das 100-Beeren-Gewicht zeigt, ob Beeren noch wachsen oder bereits schrumpfen.

### 3.3 Saft gewinnen und messen

1. Beeren im Beutel von Hand oder mit einem Nudelholz zerdrücken, bis alle Beeren geplatzt sind.
2. Saft durch ein Teesieb oder Gaze in ein Becherglas abgießen.
3. 10–15 Minuten absetzen lassen oder filtrieren (Abschnitt 4.1).
4. Sofort Mostgewicht messen, dann Gesamtsäure und pH ([Säure und pH](saeure-ph.md)). Der Saft bräunt und beginnt bald zu gären.

Von Hand gepresster Beerensaft stammt vor allem aus dem Fruchtfleisch; Säure und pH können vom Most aus der Kelter etwas abweichen.

### 3.4 Auswerten

- Werte jeder Fläche in eine Tabelle eintragen (Datum, °KMW, Gesamtsäure, pH, 100-Beeren-Gewicht, Gesundheit, Geschmack von Schale und Kernen) und als Reifekurve darstellen.
- Mit den Kurven der Vorjahre vergleichen.
- **Eigene Abweichung kennen:** Nach der Lese das Mostgewicht der letzten Beerenprobe mit dem des Mostes aus der Kelter vergleichen. Die Differenz ist eine wertvolle Betriebserfahrung, weil jede Person etwas anders pflückt.

## 4. Mostgewicht messen

### 4.1 Refraktometer

**Prinzip:** Licht wird beim Übergang in den Most gebrochen. Je mehr gelöste Stoffe, desto stärker die Brechung. Das Refraktometer misst die Brechzahl und zeigt sie als °Brix an; Skalen in °KMW oder °Oe sind daraus umgerechnet. Die OIV-Methode OIV-MA-AS2-02 ist eine Typ-I-Methode, verlangt eine Ablesbarkeit von 0,1 % Saccharose (Masse) oder vier Nachkommastellen der Brechzahl und bezieht alle Werte auf 20 °C [1, 2]. Eine Tabelle der OIV ordnet jeder Ablesung die Dichte, den Zuckergehalt in g/L und g/kg und den potenziellen Alkohol zu [1–3].

**Material:**

- Handrefraktometer (analog) mit Skala in °Brix und/oder °KMW und automatischer Temperaturkompensation (ATC), oder Digitalrefraktometer. Ablesbarkeit und Genauigkeit laut Herstellerangabe prüfen; üblich sind 0,1–0,2 °Brix.
- Pipette oder Tropfstab, Laborwasser, weiches Tuch.
- Kontrolllösung aus Saccharose (siehe [Laborpraxis](grundlagen-labor.md), Abschnitt 7.3).

**Durchführung:**

1. Nullpunkt prüfen: Laborwasser von etwa 20 °C auf das Prisma geben, Anzeige muss 0,0 °Brix zeigen. Sonst nach Anleitung justieren.
2. Prisma abtrocknen.
3. 2–3 Tropfen klaren Saft auftragen, sodass das Prisma ganz bedeckt ist; beim Handgerät die Deckplatte schließen (keine Luftblasen).
4. 30 Sekunden warten, damit Probe und Prisma die gleiche Temperatur haben.
5. Analoggerät gegen das Licht halten und die Grenzlinie zwischen hellem und dunklem Feld ablesen; Digitalgerät: Messtaste drücken.
6. Zweimal messen (neue Tropfen). Prisma mit Wasser reinigen und trocknen.

**Temperaturkompensation (ATC):** Sie rechnet die Anzeige auf 20 °C um, funktioniert aber nur in einem begrenzten Bereich (laut Herstellerangabe, häufig etwa 10–30 °C) und nur, wenn Probe und Gerät gleich warm sind. Gerät nicht in der prallen Sonne verwenden; kalte Morgenproben kurz angleichen lassen.

**Fehlerquellen:**

- Trüber Saft macht die Grenzlinie unscharf. Absetzen lassen oder filtrieren.
- Verdunstung auf dem warmen Prisma erhöht den Wert. Rasch ablesen.
- Zuckerreste der vorigen Probe. Zwischen den Proben reinigen.
- **Alkohol:** In gärendem Most und Wein ist das Ergebnis falsch (Abschnitt 6.4).
- Die °KMW-Skala eines Refraktometers ist aus der Brix-Skala umgerechnet. Kleine Unterschiede zur Mostwaage sind deshalb normal: Das Refraktometer misst die Lichtbrechung, die Mostwaage die Dichte, und Säuren und andere Nichtzuckerstoffe wirken auf beide Größen verschieden.

### 4.2 Mostwaage (Aräometer)

**Prinzip:** Ein Schwimmkörper aus Glas (Spindel, Aräometer) taucht umso weniger tief ein, je dichter die Flüssigkeit ist. Refraktometrie und Aräometrie gehören zu den Standardverfahren der Lehrbücher für Most- und Weinanalytik [20–22]. Die Skala im Hals zeigt die Dichte, °Oe oder °KMW an. Mostwaagen sind auf eine Bezugstemperatur justiert, heute meist 20 °C; sie steht auf der Spindel.

**Material:**

- Mostwaage mit °KMW-Skala (zum Beispiel 0–25 °KMW) oder Oechsle-Waage; für die Gärkontrolle zusätzlich eine Spindel, die unter den Nullpunkt reicht (zum Beispiel Dichte 0,980–1,040 oder ein Bereich bis −5 °KMW).
- Standzylinder (meist 250 mL), so weit, dass die Spindel frei schwimmt, ohne die Wand zu berühren.
- Thermometer (0,1 °C) oder Thermo-Aräometer mit eingebautem Thermometer und Korrekturskala.

**Durchführung:**

1. Klaren, entgasten Most verwenden (siehe [Laborpraxis](grundlagen-labor.md), Abschnitte 3.5 und 4).
2. Probe auf 20 °C bringen (Wasserbad). Das ist genauer als jede Korrektur.
3. Standzylinder ohne Schaum füllen (am Rand hinunterlaufen lassen).
4. Saubere, trockene Spindel am oberen Ende fassen, langsam eintauchen und loslassen, wenn sie schwimmt. Nicht fallen lassen.
5. Leicht andrehen, damit Luftbläschen abfallen und die Spindel frei schwimmt.
6. Augen auf Höhe der Flüssigkeitsoberfläche, ablesen. Bei klaren Flüssigkeiten gilt in der Regel der Wert an der Flüssigkeitsoberfläche (Unterkante des Meniskus); die Angabe auf der Spindel hat Vorrang.
7. Temperatur der Probe messen und notieren.
8. Spindel und Zylinder mit Wasser spülen.

**Temperaturkorrektur:** Warmer Most ist weniger dicht, die Spindel sinkt tiefer und zeigt zu wenig an. Über 20 °C wird deshalb zugezählt, unter 20 °C abgezogen. Die Korrekturtabelle des Herstellers verwenden.

> **Offen:** Als Größenordnung ergibt eine eigene Abschätzung aus der Wärmeausdehnung von Zuckerlösungen etwa 0,25–0,3 °Oe bzw. 0,05–0,06 °KMW je °C Abweichung von 20 °C. Der Wert ist nicht gegen eine Quelle geprüft. Bei Abweichungen über 5 °C lieber temperieren als korrigieren.

**Fehlerquellen:** CO2-Bläschen an der Spindel (Wert zu hoch), Trub und Fruchtfleisch (Wert zu hoch), fettige Spindel (Oberflächenspannung), Berührung der Zylinderwand, falsche Temperatur, ältere Spindeln mit anderer Bezugstemperatur.

### 4.3 Refraktometer und Mostwaage im Vergleich

| | Refraktometer | Mostwaage |
|---|---|---|
| Probenmenge | wenige Tropfen | ca. 250 mL |
| Messzeit | Sekunden | 2–5 Minuten |
| Reifebeprobung | sehr gut | nur bei großen Proben |
| Most | gut | gut |
| Gärung, Wein | **falsch** (Alkohol stört) | gut |
| Temperaturfehler | mit ATC gering | ohne Korrektur deutlich |
| Empfindlich auf | Trub, Verdunstung | CO2, Trub, Temperatur |

## 5. Umrechnungen

### 5.1 Formeln

1. **°KMW → °Oe:** °Oe = °KMW × (0,022 × °KMW + 4,54) [4, 5]. Die Formel liefert die bekannten Wertepaare der österreichischen Prädikatsstufen, zum Beispiel 19 °KMW = 94,2 °Oe, 25 °KMW = 127,2 °Oe, 30 °KMW = 156,0 °Oe (eigene Nachrechnung).
2. **°Oe → °KMW** (eigene Umformung): °KMW = (√(20,6116 + 0,088 × °Oe) − 4,54) : 0,044
3. **Dichte:** d20/20 = 1 + °Oe : 1000; ρ20 = d20/20 × 0,99820 g/mL.
4. **°Brix:** über die Dichte-Konzentrations-Beziehung von Saccharoselösungen (Saccharose- bzw. Plato-Tabelle) [26]. Im Bereich 13–30 °KMW gilt näherungsweise °Brix ≈ 1,18 × °KMW und °Oe ≈ 4,2 × °Brix (eigene Rechnung).
5. **Zuckergehalt (Variante A, nach der KMW-Definition):** Zucker (g/L) ≈ 10 × °KMW × ρ20. Diese Variante reproduziert die in österreichischen Produktspezifikationen genannte Gleichsetzung 15 °KMW = 9,5 % vol [8] (eigene Nachrechnung: 161 g/L : 16,83 = 9,56 % vol).
6. **Potenzieller Alkohol:** % vol = Zucker (g/L) : 16,83 [1, 11].

### 5.2 Umrechnungstabelle 13–30 °KMW

Berechnet mit den Formeln aus Abschnitt 5.1 (python3, eigene Rechnung). Die Spalte °Brix ist eine Näherung über die Saccharose-Tabelle; für Most weicht die OIV-Tabelle um etwa 0,2 °Brix ab (Abschnitt 5.3). Zucker und potenzieller Alkohol nach Variante A.

| °KMW | °Oe | ρ20 (g/mL) | °Brix (≈) | Zucker (g/L) | pot. Alkohol (% vol) |
|---|---|---|---|---|---|
| 13 | 62,7 | 1,0608 | 15,4 | 138 | 8,2 |
| 14 | 67,9 | 1,0659 | 16,6 | 149 | 8,9 |
| 15 | 73,0 | 1,0711 | 17,8 | 161 | 9,5 |
| 16 | 78,3 | 1,0763 | 18,9 | 172 | 10,2 |
| 17 | 83,5 | 1,0816 | 20,1 | 184 | 10,9 |
| 18 | 88,8 | 1,0869 | 21,3 | 196 | 11,6 |
| 19 | 94,2 | 1,0922 | 22,5 | 208 | 12,3 |
| 20 | 99,6 | 1,0976 | 23,7 | 220 | 13,0 |
| 21 | 105,0 | 1,1031 | 24,9 | 232 | 13,8 |
| 22 | 110,5 | 1,1085 | 26,1 | 244 | 14,5 |
| 23 | 116,1 | 1,1140 | 27,2 | 256 | 15,2 |
| 24 | 121,6 | 1,1196 | 28,4 | 269 | 16,0 |
| 25 | 127,2 | 1,1252 | 29,6 | 281 | 16,7 |
| 26 | 132,9 | 1,1309 | 30,8 | 294 | 17,5 |
| 27 | 138,6 | 1,1366 | 32,0 | 307 | 18,2 |
| 28 | 144,4 | 1,1423 | 33,1 | 320 | 19,0 |
| 29 | 150,2 | 1,1481 | 34,3 | 333 | 19,8 |
| 30 | 156,0 | 1,1539 | 35,5 | 346 | 20,6 |

**Kontrollpunkte (eigene Rechnung):** Eine Saccharoselösung mit 20,0 % (Masse) hat d20/20 = 1,0830 und zeigt auf der Mostwaage 83,0 °Oe bzw. 16,9 °KMW, eine 10-%-Lösung 40,0 °Oe bzw. 8,5 °KMW.

### 5.3 Wie viel Zucker steckt wirklich im Most?

Das Mostgewicht misst nicht den Zucker allein, sondern alle gelösten Stoffe. Most enthält neben Glucose und Fructose auch Säuren, Mineralstoffe, Phenole, Pektine und andere Stoffe; zusammen etwa 20–30 g/L [13]. Jede Umrechnungsformel setzt dafür einen anderen pauschalen Wert an. Das zeigt der Vergleich vier verbreiteter Ansätze (eigene Rechnung):

- **A:** Variante A aus Abschnitt 5.1 (KMW als Zucker-Massenprozent).
- **B:** OIV-Tabelle für Most [1], linear interpoliert zwischen den online geprüften Tabellenzeilen 20,0 % Saccharose (ρ20 1,0818 g/mL; 191,9 g/L Zucker; 11,40 % vol) und 25,0 % (ρ20 1,1047 g/mL; 249,5 g/L). Nur für etwa 17–21 °KMW berechnet.
- **C:** Zucker (g/L) ≈ 2,63 × °Oe − 22, Teil einer Schätzformel des DLR Rheinland-Pfalz für die Alkoholausbeute [14].
- **D:** Zucker (g/L) ≈ 2,6 × °Oe − 24, Variante in einer DLR-Tabelle, veröffentlicht von der LWG Bayern [15].

| °KMW | °Oe | Zucker A (g/L) | Zucker B (g/L) | Zucker C (g/L) | Zucker D (g/L) | pot. Alkohol A / B / C (% vol) |
|---|---|---|---|---|---|---|
| 15 | 73,0 | 161 | – | 170 | 166 | 9,6 / – / 10,1 |
| 17 | 83,5 | 184 | 191 | 198 | 193 | 10,9 / 11,4 / 11,8 |
| 19 | 94,2 | 208 | 218 | 226 | 221 | 12,3 / 13,0 / 13,4 |
| 20 | 99,6 | 220 | 232 | 240 | 235 | 13,0 / 13,8 / 14,3 |
| 21 | 105,0 | 232 | 245 | 254 | 249 | 13,8 / 14,6 / 15,1 |
| 25 | 127,2 | 281 | – | 313 | 307 | 16,7 / – / 18,6 |

Bei 20 °KMW reicht die Spanne von 220 bis 240 g/L Zucker, also von 13,0 bis 14,3 % vol potenziellem Alkohol. Die OIV-Tabelle (B) liegt zwischen der KMW-Variante (A) und den deutschen Praxisformeln (C, D). Aus den beiden OIV-Zeilen ergibt sich rechnerisch ein Nichtzuckeranteil von 24,5 bzw. 26,7 g/L.

Sigler zeigt den Einfluss an einem Beispiel: Ein Most mit 80 °Oe enthält etwa 200 g/L gelöste Stoffe. Bei 30 g/L Nichtzucker bleiben etwa 170 g/L Zucker, bei 20 g/L Nichtzucker (etwa in trockenen Jahren) ergeben sich rund 0,6 % vol mehr Alkohol [13]. Das passt zur eigenen Rechnung: 10 g/L Zucker entsprechen 10 : 16,83 = 0,59 % vol.

### 5.4 Warum Tabellen voneinander abweichen

1. **Nichtzuckerstoffe:** Ihr Anteil schwankt mit Sorte, Jahrgang, Reife und Gesundheit. Edelfäule (Botrytis) etwa erhöht Glycerin und Gluconsäure im Most [23]. Jede Tabelle unterstellt einen festen Wert.
2. **Messprinzip:** Refraktometer messen die Lichtbrechung, Mostwaagen die Dichte. Zucker, Säuren und andere Stoffe beeinflussen beide Größen unterschiedlich stark.
3. **Bezugsgrößen:** g/kg oder g/L; Dichte ρ20 oder relative Dichte d20/20; Bezugstemperatur 20 °C oder (bei alten Tabellen und Geräten) eine andere.
4. **Umrechnungsfaktor Zucker → Alkohol:** Rechtlich und in der OIV-Tabelle gilt 16,83 g/L je % vol [1]. Die tatsächliche Gärausbeute schwankt; die DLR-Formel etwa rechnet mit 0,475 g Alkohol je g Zucker, das entspricht 16,6 g/L je % vol (eigene Rechnung) [14]. Siehe [Alkohol](alkohol.md), Abschnitt 8.
5. **Säurekorrektur:** Manche Formeln korrigieren für die Gesamtsäure, das DLR etwa auf Basis einer angenommenen Gesamtsäure von 8 g/L [14].
6. **Rechtsstand:** In Deutschland wurde die amtliche Tabelle zur Ermittlung des natürlichen Alkoholgehalts aus dem Mostgewicht (Anlage 8 zu § 17 Weinverordnung) laut DLR ersatzlos gestrichen [14]. Ältere deutsche Tabellen sind daher nicht mehr amtlich.
7. **Rundung und Stützstellen:** Tabellen in ganzen Grad werden linear interpoliert.

**Was folgt daraus?**

- Für die österreichischen Qualitätsstufen zählt das Mostgewicht in °KMW selbst. Eine Umrechnung ist dafür nicht nötig.
- Der potenzielle Alkohol aus dem Mostgewicht ist eine Schätzung mit einer Unsicherheit von mindestens ± 0,5 % vol.
- Für die eigene Planung **immer dieselbe Formel** verwenden und sie mit Betriebsdaten eichen: Für jede Partie Mostgewicht, Restzucker und den im Labor gemessenen Alkohol notieren. Nach einigen Jahrgängen kennt man den eigenen Umrechnungsfaktor.

### 5.5 Faustregeln

- 1 °KMW ≈ 5 °Oe (genauer: 4,8–5,2 °Oe im Bereich 13–30 °KMW).
- °Brix ≈ 1,18 × °KMW; °Oe ≈ 4,2 × °Brix.
- 1 °KMW ≈ 11–12 g/L Zucker ≈ 0,65–0,7 % vol potenzieller Alkohol (Variante A).
- 10 g/L Zucker ≈ 0,6 % vol potenzieller Alkohol.

## 6. Gärkontrolle

### 6.1 Was und wie oft

- **Täglich, möglichst zur gleichen Uhrzeit:** Dichte bzw. °KMW, Temperatur im Gärbehälter, Geruch (Böckser, also Schwefelwasserstoff), Schaum und Gärgeräusch.
- **Zweimal täglich** in kritischen Phasen: Gärstart, stürmische Gärung mit Temperaturanstieg, Gärende.
- **Bei Auffälligkeiten:** Mikroskopie ([Mikrobiologie und Mikroskopie](mikrobiologie-mikroskopie.md)), hefeverwertbarer Stickstoff ([Stickstoff (YAN)](stickstoff-yan.md)), flüchtige Säure ([Flüchtige Säure](fluechtige-saeure.md)).

### 6.2 Durchführung

1. Behälter mischen und etwa 250 mL Probe nehmen ([Laborpraxis](grundlagen-labor.md), Abschnitt 3.4).
2. CO2 entfernen: Probe in einer verschlossenen Flasche kurz schütteln, Deckel lüften, wiederholen; oder zwischen zwei Bechergläsern hin und her gießen.
3. Temperatur der Probe messen. Wenn möglich auf 20 °C bringen, sonst korrigieren (Abschnitt 4.2).
4. Mit der Mostwaage messen (Abschnitt 4.2), Spindel kräftig andrehen, damit Gasbläschen abfallen, rasch ablesen.
5. In das Gärprotokoll eintragen.

### 6.3 Gärkurve

Die Werte als Kurve darstellen (Tabellenkalkulation: Tage auf der waagrechten Achse, °KMW oder Dichte auf der senkrechten). Eine gesunde Gärung zeigt nach einer kurzen Anlaufphase einen gleichmäßigen Abfall, der gegen Ende flacher wird.

**Vorlage Gärprotokoll (mit Beispieldaten zur Veranschaulichung):**

| Tag | Datum, Uhrzeit | Temperatur im Tank (°C) | Mostgewicht (°KMW, auf 20 °C korrigiert) | Abnahme seit Vortag | Geruch, Beobachtung | Maßnahme |
|---|---|---|---|---|---|---|
| 0 | 20.09., 08:00 | 15,0 | 19,0 | – | Hefe zugesetzt | – |
| 1 | 21.09., 08:00 | 15,5 | 18,8 | 0,2 | noch keine Gärung sichtbar | – |
| 2 | 22.09., 08:00 | 16,5 | 17,9 | 0,9 | Gärbeginn, Schaum | – |
| 3 | 23.09., 08:00 | 18,0 | 16,4 | 1,5 | stürmisch | Kühlung auf 17 °C |
| 4 | 24.09., 08:00 | 17,0 | 14,8 | 1,6 | sauber | – |
| … | … | … | … | … | … | … |
| 12 | 02.10., 08:00 | 16,0 | 0,5 | 0,8 | leichter Böckser | Belüften, siehe [Stickstoff (YAN)](stickstoff-yan.md) |
| 15 | 05.10., 08:00 | 16,0 | −1,4 | 0,1 | ruhig | Restzucker bestimmen |

**Abschätzung des noch vorhandenen Zuckers (eigene Rechnung):** Während der Gärung sinkt die Dichte durch den Zuckerabbau und zusätzlich, weil Alkohol leichter als Wasser ist. Eine Abnahme um 1 °Oe entspricht etwa 2 g/L vergorenem Zucker; zu Gärbeginn entspricht 1 °KMW Abnahme etwa 10 g/L. Restzucker ≈ (aktueller °Oe-Wert − erwarteter Endwert) × 2 g/L. Durchgegorene trockene Weine haben je nach Alkohol und Extrakt meist eine relative Dichte von etwa 0,989–0,996 (−11 bis −4 °Oe; rund −2,4 bis −0,9 °KMW). Die Abschätzung ersetzt keine Restzuckerbestimmung.

**Gärkurve lesen:**

- **Gleichmäßiger Abfall:** in Ordnung.
- **Kurve flacht ab, obwohl die Dichte noch deutlich über dem erwarteten Endwert liegt:** Verdacht auf Gärstockung. Temperatur prüfen, Mikroskopie (lebende Hefen?), Nährstoffversorgung prüfen. Früh handeln; eine stehende Gärung lässt sich schwer wieder starten.
- **Sehr schneller Abfall mit Temperaturanstieg:** kühlen; zu warme Gärung kostet Aroma und stresst die Hefe.
- **Böckser (Geruch nach faulen Eiern):** siehe [Stickstoff (YAN)](stickstoff-yan.md).

### 6.4 Warum das Refraktometer während der Gärung falsch misst

Alkohol bricht das Licht stärker als Wasser. Ein Zuckerrefraktometer ist deshalb für Restzucker in Wein und gärendem Most nicht geeignet [12]. Das Refraktometer zeigt in gärendem Most **zu viel** Zucker an.

*Abschätzung (eigene Rechnung aus Brechzahlen in Tabellenwerken [26]):* 10 Massenprozent Ethanol (rund 12,4 % vol) erhöhen die Brechzahl etwa so stark wie 4,4 % Saccharose. Dazu kommt der zuckerfreie Extrakt mit rund 2 °Brix. Ein trocken durchgegorener Wein mit 12–13 % vol zeigt am Refraktometer deshalb noch etwa 6–7 °Brix, obwohl kaum Zucker vorhanden ist.

**Korrekturformel?** Für Wein ist keine allgemein anerkannte und geprüfte Korrekturformel belegt. Formeln aus der Bierbrauerei, die Refraktometer- und Dichtewert kombinieren, sind für Bierwürze entwickelt und nicht ohne Weiteres auf Traubenmost übertragbar. Eine Untersuchung der steirischen Landwirtschaftsverwaltung kam zum Schluss, dass ein Handrefraktometer auch zur Alkoholbestimmung die üblichen Methoden nicht ersetzen kann [12]. **Empfehlung:** Ab Gärbeginn die Mostwaage verwenden.

### 6.5 Gärende erkennen

1. Die Dichte bleibt 2–3 Tage gleich **und** liegt im erwarteten Endbereich (etwa 0,989–0,996).
2. Dann den Restzucker bestimmen (Abschnitt 7).
3. Bleibt die Dichte bei einem höheren Wert stehen (etwa um 1,000 oder darüber), ist das kein Gärende, sondern eine Gärstockung. Der Restzucker kann dann noch 10–20 g/L oder mehr betragen (eigene Abschätzung nach Abschnitt 6.3).

## 7. Restzucker bestimmen

### 7.1 Methoden im Überblick

Die Lehrbücher der Weinanalytik beschreiben Kupfer-Reduktionsverfahren (Fehling-Varianten, Tabletten-Schnelltests) und enzymatische Verfahren für Zucker [20–22]. Die Angaben zu Bereich und Genauigkeit in der Tabelle sind Größenordnungen aus dem Fachwissen und nicht gegen eine Quelle geprüft.

| Methode | Was wird erfasst | Genauigkeit | Aufwand | Eignung |
|---|---|---|---|---|
| Rebelein (Kupfer-Iod-Methode) | reduzierende Zucker | etwa ± 0,5 g/L | 20–30 min; Heizplatte, Bürette | Zahlenwert im Betriebslabor |
| Enzymtest mit Fotometer | Glucose und Fructose, getrennt | genau, auch unter 1 g/L | ca. 30 min; Fotometer, Kolbenhubpipetten | beste Betriebsmethode, siehe [Fotometrie und Enzymatik](fotometrie-enzymatik.md) |
| Fehling-Probe | reduzierende Zucker | grob (Farbvergleich) | 10 min | Orientierung |
| Clinitest-Tabletten | reduzierende Zucker | grob (Farbstufen) | 5 min | Orientierung; Verfügbarkeit unsicher |
| Glucose-Teststreifen | nur Glucose | ungeeignet am Gärende | 1 min | nicht empfohlen |
| Dichte | Summe aus Alkohol und Extrakt | keine Aussage über Restzucker | 2 min | nur Gärverlauf |
| Externes Labor (z. B. Enzymatik, Infrarot-Analytik, Chromatographie) | Glucose + Fructose | genau | Tage | Etikett, Grenzfälle |

### 7.2 Rebelein-Methode (Kupfer-Iod-Methode)

**Prinzip:** In alkalischer Lösung reduzieren Zucker zweiwertige Kupferionen (Cu²⁺) zu einwertigen. Kupfer wird im Überschuss vorgelegt. Nach dem Kochen wird das übrig gebliebene Cu²⁺ bestimmt: Nach Ansäuern und Zugabe von Kaliumiodid setzt es Iod frei (2 Cu²⁺ + 4 I⁻ → 2 CuI + I₂). Das Iod wird mit Natriumthiosulfat gegen Stärke titriert (I₂ + 2 S₂O₃²⁻ → 2 I⁻ + S₄O₆²⁻). Ein Blindwert mit Wasser statt Wein zeigt die gesamte vorgelegte Kupfermenge. Je mehr Zucker, desto größer die Differenz zwischen Blindwert und Probe. Weil die Reaktion des Zuckers mit Kupfer nicht streng stöchiometrisch verläuft, wird die Differenz über einen empirischen Faktor in g/L umgerechnet. Die OIV beschreibt für reduzierende Substanzen ein Verfahren nach demselben Grundprinzip [25].

**Material:**

- Reagenziensatz für die Rebelein-Methode aus dem Kellereibedarf: Kupfer(II)-sulfat-Lösung, alkalische Kalium-Natrium-Tartrat-Lösung, Kaliumiodid-Lösung, verdünnte Schwefelsäure, Stärkelösung, Natriumthiosulfat-Maßlösung. Fertig kaufen ist für Kleinbetriebe die sichere Wahl.
- Erlenmeyerkolben 250–300 mL (Weithals), Vollpipetten (laut Anleitung, meist 2, 5, 10 mL), Bürette 25 mL, Heizplatte, Stoppuhr, kaltes Wasserbad.
- Für Rotwein: Aktivkohle oder ein anderes Entfärbemittel laut Anleitung, Faltenfilter.
- Zur Kontrolle: Glucose und Fructose (Reinheit „zur Analyse“) für Standardlösungen.

> **Offen:** Die genauen Konzentrationen der Reagenzien, Probenvolumen und Kochzeit wurden bei der Erstellung nicht gegen eine Quelle geprüft. Die Anleitung des Reagenziensatzes ist maßgeblich.

**Durchführung (allgemeiner Ablauf, Mengen laut Anleitung):**

1. Probe entgasen. Zuckerreiche Weine nach Anleitung verdünnen (Verdünnung notieren).
2. Rotwein entfärben (Aktivkohle zugeben, schütteln, filtrieren), weil Farb- und Gerbstoffe Kupfer ebenfalls reduzieren.
3. Kupferlösung und alkalische Lösung mit Vollpipetten in den Erlenmeyerkolben geben, dann die Probe.
4. Auf der vorgeheizten Platte zum Sieden bringen und **genau** die vorgeschriebene Zeit kochen lassen. Die Kochzeit beeinflusst das Ergebnis.
5. Sofort im kalten Wasserbad abkühlen.
6. Kaliumiodid, Schwefelsäure und Stärke in der vorgeschriebenen Reihenfolge zugeben. Die Lösung wird dunkelblau.
7. Mit Natriumthiosulfat titrieren, bis die blaue Farbe verschwindet (die Lösung wird durch das ausgefallene Kupferiodid hell, cremefarben).
8. Blindwert: genauso, mit Laborwasser statt Probe.
9. Doppelbestimmung.

**Berechnung:** Zucker (g/L) = (V_Blindwert − V_Probe) × F × Verdünnungsfaktor. Den Faktor F aus der Anleitung nehmen und mit eigenen Standardlösungen prüfen.

*Kontrolle mit eigenen Standards:* 0,500 g Glucose und 0,500 g Fructose im 100-mL-Messkolben lösen (10,0 g/L Zucker). Daraus durch Verdünnen 2,0 und 5,0 g/L herstellen (20 bzw. 50 mL auf 100 mL). Die Messwerte der Standards zeigen, ob F stimmt, und eignen sich als Kontrolle bei jeder Serie.

**Fehlerquellen:**

- Kochzeit und Heizleistung: immer gleich arbeiten.
- Unvergärbare Zucker (Pentosen) und andere reduzierende Stoffe werden mitgemessen. In trockenen Weinen liegt das Ergebnis deshalb meist etwas über der Summe aus Glucose und Fructose (Größenordnung bis etwa 1 g/L; nicht belegt). Für die Grenze „trocken“ ist die Methode damit eher vorsichtig.
- Farb- und Gerbstoffe im Rotwein: entfärben.
- CO2 und schweflige Säure stören wenig, CO2 trotzdem entfernen.

**Sicherheit und Entsorgung:** Die alkalische Lösung ist ätzend, Kupfersulfat gesundheitsschädlich und gewässergefährdend. Schutzbrille und Handschuhe tragen. Alle kupferhaltigen Reste sammeln und als Problemstoff entsorgen ([Laborpraxis](grundlagen-labor.md), Abschnitt 10).

### 7.3 Fehling-Probe (qualitativ bis halbquantitativ)

**Prinzip:** Wie bei Rebelein reduzieren Zucker in alkalischer Kupferlösung Cu²⁺ zu Cu⁺. Es fällt rotes Kupfer(I)-oxid aus. Die Farbe ändert sich mit zunehmendem Zucker von Blau über Grün und Gelb nach Orange-Rot.

**Material:** Fehling-Lösung I (Kupfersulfat) und II (alkalische Kalium-Natrium-Tartrat-Lösung), fertig gekauft; Reagenzgläser, Reagenzglashalter, Heizplatte mit Wasserbad, Glucose-Standards (0, 2, 5, 10 g/L).

> **Offen:** Die klassische Zusammensetzung (Fehling I: etwa 69 g/L Kupfersulfat-Pentahydrat; Fehling II: etwa 346 g/L Kalium-Natrium-Tartrat und 100 g/L Natriumhydroxid) stammt aus dem Fachwissen und ist nicht online geprüft. Fertige Lösungen kaufen.

**Durchführung:**

1. In jedes Reagenzglas je 2 mL Fehling I und 2 mL Fehling II geben (frisch mischen).
2. 1 mL Probe bzw. Standard zugeben.
3. 2 Minuten im kochenden Wasserbad erhitzen.
4. Farbe der Probe mit den Standards vergleichen.

**Auswertung:** Bleibt die Probe ähnlich wie der 2-g/L-Standard, ist der Wein annähernd trocken. Für eine Zahl ist die Methode zu grob.

### 7.4 Clinitest-Tabletten

Clinitest-Tabletten wurden für den Harnzucker-Nachweis entwickelt. Sie enthalten Kupfersulfat und Natriumhydroxid und erhitzen sich in Wasser selbst. Kellereien nutzten sie für einen schnellen Trockenheitstest: wenige Tropfen Wein, Wasser und eine Tablette in ein Reagenzglas, Farbe nach Ablauf der Reaktion mit der Farbkarte vergleichen (Stufen in Prozent; 0,25 % entsprechen 2,5 g/L).

> **Offen:** Ob Clinitest-Tabletten noch hergestellt und verkauft werden, konnte nicht geprüft werden (nach Fachwissen wurde die Herstellung eingestellt). Vor einem Kauf beim Kellereibedarf nachfragen. Die Tabletten sind ätzend und werden beim Lösen heiß.

### 7.5 Glucose-Teststreifen

Teststreifen aus der Diabetes-Diagnostik messen mit dem Enzym Glucoseoxidase **nur Glucose**. Weinhefen bauen Glucose schneller ab als Fructose; am Ende der Gärung bleibt vor allem Fructose übrig [23]. Ein Teststreifen zeigt deshalb „kein Zucker“, obwohl noch mehrere Gramm Fructose je Liter vorhanden sein können. Für die Kontrolle der Endvergärung sind Glucose-Teststreifen ungeeignet.

### 7.6 Enzymatische Bestimmung

Enzymtests bestimmen Glucose und Fructose getrennt und genau; sie messen damit genau die Größe, auf die sich die Geschmacksangaben beziehen (Abschnitt 8). Sie brauchen ein Fotometer (340 nm), Kolbenhubpipetten und gekühlt gelagerte Testkits. Anleitung: [Fotometrie und Enzymatik](fotometrie-enzymatik.md).

### 7.7 Restzucker aus der Dichte?

Nein. Die Dichte eines Weines hängt von Alkohol und Extrakt gleichzeitig ab. Rechenbeispiele (eigene Rechnung, Verfahren in [Alkohol](alkohol.md), Abschnitt 9):

- Trockener Wein, 13,5 % vol, 22 g/L Extrakt: relative Dichte etwa 0,991.
- Süßer Wein, 11,0 % vol, 40 g/L Restzucker (62 g/L Extrakt): relative Dichte etwa 1,009.

Nur eine **stabile, niedrige** Dichte zeigt das Ende der Gärung an. Den Restzucker muss man danach messen.

### 7.8 Externes Labor

Für die Etikettangabe, für Grenzfälle (Abschnitt 8) und für Weine mit Restsüße vor der Füllung ein Labor beauftragen, das Glucose und Fructose bestimmt.

## 8. Geschmacksangaben nach EU-Recht

Die Angaben für Weine (nicht Schaumwein) sind in VO (EU) 2019/33, Anhang III Teil B, festgelegt [9, 10]. Maßgeblich ist der Zuckergehalt als Summe aus Glucose und Fructose. Die Gesamtsäure wird als Weinsäure in g/L gerechnet.

| Angabe | Zuckergehalt | Bedingung |
|---|---|---|
| trocken | höchstens 4 g/L | – |
| trocken | höchstens 9 g/L | Gesamtsäure liegt höchstens 2 g/L unter dem Zuckergehalt |
| halbtrocken | über dem Wert für trocken, höchstens 12 g/L | – |
| halbtrocken | höchstens 18 g/L | Gesamtsäure liegt höchstens 10 g/L unter dem Zuckergehalt |
| lieblich | über dem Wert für halbtrocken, höchstens 45 g/L | – |
| süß | mindestens 45 g/L | – |

**Rechenbeispiele (eigene Rechnung):**

| Restzucker (g/L) | Gesamtsäure (g/L) | Differenz Zucker − Säure | Ergebnis |
|---|---|---|---|
| 3,5 | 5,0 | −1,5 | trocken (unter 4 g/L) |
| 7,5 | 6,0 | 1,5 | trocken (Differenz ≤ 2) |
| 8,5 | 6,0 | 2,5 | **halbtrocken** (Differenz > 2) |
| 9,5 | 8,0 | 1,5 | halbtrocken (über 9 g/L, Säure hilft nicht) |
| 16,0 | 6,5 | 9,5 | halbtrocken (Differenz ≤ 10) |
| 17,5 | 7,0 | 10,5 | **lieblich** (Differenz > 10) |
| 50 | 7,0 | – | süß |

**Höchster Zuckergehalt für eine Angabe bei gegebener Gesamtsäure (eigene Rechnung):**

| Gesamtsäure (g/L) | 4,5 | 5,0 | 5,5 | 6,0 | 6,5 | 7,0 und mehr |
|---|---|---|---|---|---|---|
| höchstens „trocken“ (g/L) | 6,5 | 7,0 | 7,5 | 8,0 | 8,5 | 9,0 |
| höchstens „halbtrocken“ (g/L) | 14,5 | 15,0 | 15,5 | 16,0 | 16,5 | 17,0 (ab 8,0 g/L Säure: 18,0) |

**Hinweise:**

- Wer die Gesamtsäure als Schwefelsäure angegeben bekommt (in Frankreich üblich), multipliziert mit 1,53 (75,04 : 49,04), um auf Weinsäure umzurechnen.
- Nahe an einer Grenze die Messunsicherheit beachten ([Laborpraxis](grundlagen-labor.md), Abschnitt 7.9). Kupfer-Methoden messen eher etwas mehr als Glucose + Fructose; Enzymtest oder Labor schaffen Klarheit.
- Für die Gesamtsäure gilt der Wert des fertigen Weines, nicht des Mostes.

- **Toleranz:** Der tatsächliche Zuckergehalt darf höchstens 1 g/L von der Angabe auf dem Etikett abweichen, unbeschadet der Verwendungsbedingungen in Anhang III Teil B (VO (EU) 2019/33, Art. 52; bei Schaumwein Art. 47: 3 g/L) [9]. Die Grenzen selbst (z. B. 4 g/L für „trocken“) werden dadurch nicht erweitert.
- **Genau 45 g/L:** „lieblich“ gilt bis „nicht mehr als 45 g/L“, „süß“ ab „mindestens 45 g/L“. Bei genau 45 g/L sind damit beide Begriffe zulässig; Art. 52 bestimmt für diesen Fall, dass nur einer der beiden gewählt wird [9].
- Die Geschmacksangabe ist bei Stillwein nach EU-Recht freiwillig („kann … angegeben werden“, Art. 52) [9].

Rechtliche Details und weitere Grenzwerte: [Grenzwerte und Recht](grenzwerte-recht.md).

## 9. Österreichische Mindestmostgewichte

Das Weingesetz 2009 legt die Mindestmostgewichte in °KMW fest [6, 7]. °Oe und potenzieller Alkohol sind nur zur Orientierung umgerechnet (Formeln aus Abschnitt 5.1, Zucker nach Variante A; eigene Rechnung).

| Kategorie | Mindestmostgewicht | ≈ °Oe | ≈ pot. Alkohol | weitere Bedingungen (Auswahl) | Fundstelle |
|---|---|---|---|---|---|
| Landwein | 14 °KMW | 68 | 8,9 % vol | vorhandener Alkohol mindestens 8,5 % vol | § 9 WeinG [6, 7] |
| Qualitätswein | 15 °KMW | 73 | 9,5 % vol | staatliche Prüfnummer | § 10 WeinG [6–8] |
| Kabinett | 17 °KMW | 84 | 10,9 % vol | keine Anreicherung, keine Süßung, höchstens 12,9 % vol Alkohol (seit 2016) | § 10 Abs. 5 WeinG [6, 7, 28] |
| Spätlese | 19 °KMW | 94 | 12,3 % vol | vollreif gelesene Trauben | § 11 WeinG [6] |
| Auslese | 21 °KMW | 105 | 13,8 % vol | sorgfältig ausgelesene Trauben | § 11 WeinG [6] |
| Beerenauslese | 25 °KMW | 127 | 16,7 % vol | überreife oder edelfaule Beeren | § 11 WeinG [6] |
| Eiswein | 25 °KMW | 127 | 16,7 % vol | Trauben bei Lese und Kelterung gefroren | § 11 WeinG [6] |
| Strohwein / Schilfwein | 25 °KMW | 127 | 16,7 % vol | Trauben vor dem Pressen mindestens drei Monate auf Stroh oder Schilf gelagert oder aufgehängt | § 11 WeinG [6] |
| Ausbruch | 27 °KMW | 139 | 18,2 % vol | edelfaule oder überreife, natürlich eingetrocknete Beeren | § 11 WeinG [6] |
| Trockenbeerenauslese | 30 °KMW | 156 | 20,6 % vol | überwiegend edelfaule, weitgehend eingeschrumpfte Beeren | § 11 WeinG [6] |

Nachgeprüft (November 2026, über Gesetzesmaterialien und Suchergebnisse, nicht im RIS-Wortlaut): Kabinett darf nicht angereichert und nicht gesüßt werden, Süßung ist auch bei Prädikatswein unzulässig (§ 5 Abs. 2 WeinG), und der Alkoholgehalt von Kabinett ist seit der Novelle BGBl. I Nr. 47/2016 auf höchstens 12,9 % vol begrenzt (vorher 13 % vol) [7, 28]. Strohwein/Schilfwein: 25 °KMW und mindestens drei Monate Trocknung; die Fassung von 2009 nannte zwei Monate [6].

> **Offen:** Weiter im RIS zu prüfen: ob die Kabinett-Restzuckergrenze von 9 g/L (BMLUK-Übersicht [7], Stand vor 2016) noch gilt; ob „Ausbruch“ (27 °KMW) außerhalb von Rust noch verwendet werden darf; Mindestmostgewicht für „Wein“ ohne geschützte Herkunft (Sekundärquellen nennen 10,6 bzw. 10,7 °KMW); Melde- und Nachweispflichten bei der Lese von Prädikatsweinen. Das RIS war bei der Nachprüfung nicht erreichbar.

- Die Fassungen der §§ 9 und 11 gelten laut Rechtsdatenbank seit 14.06.2016 [6]. Das Gesetz wurde seither mehrfach geändert; vor rechtlich relevanten Entscheidungen den aktuellen Text im RIS lesen und bei der Bundeskellereiinspektion oder der Landwirtschaftskammer nachfragen.
- Für DAC-Weine können die Verordnungen der einzelnen Gebiete strengere Vorgaben enthalten.
- Das Mindestmostgewicht bezieht sich auf das tatsächlich gemessene Mostgewicht der Trauben. Die Messung bei der Übernahme sorgfältig dokumentieren (Datum, Partie, °KMW, Messgerät).

## 10. Fehlerquellen und Grenzen (Zusammenfassung)

| Messung | typische Fehler | Größenordnung | Abhilfe |
|---|---|---|---|
| Beerenprobe | Auswahl zu reifer Beeren, zu kleine Probe | systematisch, mehrere Zehntel °KMW und mehr (nicht belegt) | Abschnitt 3.2; mit Lesegut vergleichen |
| Refraktometer im Most | Trub, Verdunstung, Temperatur | 0,1–0,3 °Brix (nicht belegt) | Nullpunkt, Kontrolllösung, klarer Saft |
| Refraktometer in Gärung oder Wein | Alkohol | mehrere °Brix | nicht verwenden |
| Mostwaage | Temperatur, CO2, Trub | bis über 1 °Oe | 20 °C, entgasen, klären |
| Umrechnung in Zucker und Alkohol | Annahme über Nichtzucker, Gärausbeute | 10–20 g/L bzw. 0,6–1,2 % vol | Betriebsdaten sammeln |
| Restzucker mit Kupfer-Methoden | Pentosen, Phenole, Kochzeit | bis etwa 1 g/L (nicht belegt) | Standards mitführen; Enzymtest |
| Glucose-Teststreifen | Fructose wird nicht erfasst | mehrere g/L | nicht verwenden |

## 11. Sicherheit und Entsorgung

- **Refraktometer und Mostwaage:** keine Chemikalien. Glasspindeln brechen leicht; Bruch sofort aufsammeln. Alte Thermo-Aräometer können Quecksilber enthalten: Bruch als Problemstoff entsorgen.
- **Rebelein und Fehling:** Alkalische Lösungen sind ätzend (Schutzbrille, Handschuhe). Kupfersalze sind gesundheitsschädlich und gewässergefährdend: Reste sammeln und als Problemstoff abgeben, nicht in den Kanal.
- **Clinitest:** Tabletten ätzend, Reaktion heiß; nicht anfassen, Reagenzglas nur am oberen Ende halten.
- **Kochen:** Siedeverzug vermeiden (Siedesteinchen bei Bedarf), Kolben mit Klammer oder Handschuh anfassen.
- Allgemeine Regeln: [Laborpraxis](grundlagen-labor.md), Abschnitt 10.

## 12. Einkaufsliste (kompakt)

Preisklassen grob geschätzt und nicht geprüft: € unter 50 Euro, €€ 50–500 Euro, €€€ über 500 Euro. Vollständige Liste: [Einkaufsliste](einkaufsliste.md).

| Artikel | Spezifikation | Menge | Verbrauch je Analyse | Preisklasse |
|---|---|---|---|---|
| Handrefraktometer | °Brix und/oder °KMW, ATC, Teilung 0,2 °Brix oder feiner | 1 | – | € bis €€ |
| oder Digitalrefraktometer | Auflösung 0,1 °Brix, ATC | 1 | – | €€ |
| Mostwaage | °KMW (z. B. 0–25), Bezugstemperatur 20 °C | 1 | – | € |
| Gärspindel | Bereich unter 0 °KMW bzw. Dichte ab 0,980 | 1 | – | € |
| Standzylinder | 250 mL, Glas oder Kunststoff | 2 | – | € |
| Digitalthermometer | Auflösung 0,1 °C | 1 | – | € |
| Gefrierbeutel, Kühlbox, Teesieb, Gaze | für Beerenproben | nach Bedarf | 1 Beutel | € |
| Saccharose (Haushaltszucker) | für Kontrolllösungen | 1 kg | 10–20 g | € |
| Reagenziensatz Rebelein | laut Hersteller | 1 | laut Anleitung | €€ |
| Bürette 25 mL, Klasse A | oder Flaschenaufsatz-Bürette | 1 | – | € bis €€ |
| Erlenmeyerkolben Weithals | 250–300 mL, Borosilikatglas | 4 | – | € |
| Heizplatte | regelbar | 1 | – | €€ |
| Fehling I und II | fertige Lösungen, je 100–250 mL | je 1 | je 2 mL | € |
| Glucose und Fructose | Reinheit „zur Analyse“ | je 100 g | je 0,5 g für Standards | € |
| Enzymtest Glucose/Fructose | siehe [Fotometrie und Enzymatik](fotometrie-enzymatik.md) | – | – | €€ |

Stand: November 2026

## Quellen

1. OIV (2012): Evaluation by refractometry of the sugar concentration in grape musts, concentrated grape musts and rectified concentrated grape musts. Methode OIV-MA-AS2-02 (Typ I), Revision 2012. In: Compendium of International Methods of Wine and Must Analysis. https://www.oiv.int/public/medias/2469/oiv-ma-as2-02.pdf [online geprüft – Methodenbeschreibung und Tabellenzeilen 20,0 % und 25,0 %]
2. OIV (2012): Resolution OIV-OENO 466/2012 (Revision der Tabellen zur refraktometrischen Zuckerbestimmung). https://www.oiv.int/public/medias/1448/oiv-oeno-466-2012-en.pdf [online geprüft]
3. OIML (1997): OIML R 124 – Refractometers for the measurement of the sugar content of grape musts. Organisation Internationale de Métrologie Légale, Paris. https://www.oiml.org/en/files/pdf_r/r124-e97.pdf [online geprüft – Tabellenzeile 20,0 %: 1,36383; 1,0817; 191,9 g/L; 177,4 g/kg]
4. Hanna Instruments (o. J.): HI96814 – Digital refractometer for Brix, Oechsle and KMW analysis in wine (Datenblatt mit Umrechnungsformel °KMW → °Oe). https://pages.hannainst.com/hi96814-digital-refractometer-for-brix-oechsle-and-kmw-analysis-in-wine.html [online geprüft – Herstellerangabe, nur als technische Gerätedaten verwendet]
5. wein.plus (o. J.): Glossar „Klosterneuburger Mostwaage“ (Entstehung 1861 durch Babo, Umrechnungsformel). https://glossary.wein.plus/klosterneuburger-mostwaage-2 [online geprüft – Nachschlagewerk, nur ergänzend]
6. Weingesetz 2009 (WeinG), BGBl. I Nr. 111/2009 in der geltenden Fassung, § 9 (Landwein), § 10 (Qualitätswein, Kabinett), § 11 (Prädikatswein). RIS: https://ris.bka.gv.at/eli/bgbl/i/2009/111/P9/NOR40181264 und https://ris.bka.gv.at/eli/bgbl/i/2009/111/P11/NOR40181266 ; konsolidiert auch https://www.jusline.at/gesetz/weing/paragraf/11 [online geprüft – Auszüge; Mindestmostgewichte 14, 15, 17, 19, 21, 25 (Beerenauslese, Eiswein), 27 und 30 °KMW, Landwein mindestens 8,5 % vol]
7. BMLUK (o. J.): Weingesetz 2009 (Informationsseite des Bundesministeriums). https://www.bmluk.gv.at/themen/landwirtschaft/gemeinsame-agrarpolitik-foerderungen/gmo-rechtsinfo/gmo-wein/Weingesetz.html [online geprüft – Landwein 14 °KMW, Qualitätswein 15 °KMW]
8. BML (o. J.): Produktspezifikationen österreichischer Weine mit geschützter Ursprungsbezeichnung, z. B. Wagram: https://info.bml.gv.at/dam/jcr:7c2e6fda-1e08-47ff-bebd-dabdfe539bef/Wagram%20Produktspezifikation.pdf und Kärnten: https://info.bml.gv.at/dam/jcr:c93ae92a-09ea-4e06-95cd-6714cdc13d1f/K%C3%A4rnten%20Produktspezifikation.pdf [online geprüft – Angabe „15° KMW (= 9,5 % vol.)“ in einer dieser Spezifikationen gesehen]
9. Delegierte Verordnung (EU) 2019/33 der Kommission, Art. 47, Art. 52 und Anhang III Teil B (Angaben zum Zuckergehalt). Konsolidierte Fassung EUR-Lex, Stand 18.01.2025. https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:02019R0033-20250118 [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 18.01.2025: Anhang III Teil B, Toleranz 1 g/L, Wahl eines Begriffs bei Überschneidung]
10. Österreich Wein Marketing (o. J.): Residual sugar content (Restzuckergehalt). https://www.austrianwine.com/our-wine/wine-law/residual-sugar-content [online geprüft]
11. Verordnung (EG) Nr. 491/2009 des Rates, Anhang I (Begriffsbestimmungen: potenzieller und Gesamtalkoholgehalt). https://legislation.gov.uk/eur/2009/491/annex/I/data.pdf [online geprüft]. Heute geregelt in Verordnung (EU) Nr. 1308/2013, Anhang II Teil IV Nr. 13–16 (siehe [24]).
12. Innerhofer, G. (2010): Refraktometrische Alkoholbestimmung. Haidegger Perspektiven 4/2010, Land Steiermark. https://www.agrar.steiermark.at/cms/dokumente/11305333_13888112/92e200e3/2010-04%20Refraktometrische%20Alkoholbestimmung.pdf [online geprüft – nur Auszug]
13. Sigler, J. (2021): Beitrag zu Oechslegrad und Alkoholgehalt (Originaltitel nicht ermittelt). Der Deutsche Weinbau, Heft 13/2021, S. 20–23. https://www.meininger.de/sites/meininger.de/files/fields/field_a_dateiupload/2021_ddw13_20-23_Oechsle-Sigler_ipad.pdf [online geprüft – nur Auszug]
14. DLR Rheinland-Pfalz (o. J. und 2025): Kellerwirtschaftlicher Informationsservice: KIS 8 (Rheinhessen) „Alkoholausbeute, flüchtige Säure, Hektarertragsregelung“ und KIS vom 17.09.2025, Anlage „Alkoholausbeute“. https://www.dlr.rlp.de/Internet/global/Themen.nsf/(DLR_RLP_Aktu_Wb_XP)/D7DA955C09D41DD0C1258A2F0044205F/$FILE/KIS%208%20(Rhh)%20Alkoholausbeute,%20fl%C3%BCchtige%20S%C3%A4ure,%20Hektarertragsregelung.pdf und https://www.weinbau.rlp.de/Internet/global/Themen.nsf/543c72e9d768da11c1257e660039c4d8/7bd12f33f1cedb91c1258d08003bc4a8/$FILE/kis250917_10_Anlage_Alkoholausbeute.pdf [online geprüft – nur Auszüge; Formel und Streichung der Anlage 8 WeinV dort gesehen, Zuordnung zum jeweiligen Dokument nicht gesichert]
15. LWG Bayern (2025): Tabelle Federweißer – Brennwert (Tabelle des DLR), Stand 04.09.2025. https://www.lwg.bayern.de/mam/cms06/weinbau/dateien/20250904_federwei%C3%9Fer_tabellebrennwert_dlr.pdf [online geprüft – nur Auszug]
16. Ohio State University Extension (o. J.): Factsheet HYG-1436 (Probenahme von Beeren zur Reifebestimmung). Ohioline. https://ohioline.osu.edu/factsheet/HYG-1436 [online geprüft]
17. Iowa State University Extension and Outreach (o. J.): Merkblatt zur Beerenprobenahme (Produkt 16073). https://store.extension.iastate.edu/product/16073-pdf [online geprüft]
18. eXtension Grapes (o. J.): Collecting Berry Samples to Assess Grape Maturity. https://grapes.extension.org/?p=555 [online geprüft]
19. University of Maryland Extension (o. J.): Timely Viticulture Timeline: Pre-Harvest. https://extension.umd.edu/resource/crop-development-sampling [online geprüft]
20. Iland, P.; Bruer, N.; Edwards, G.; Weeks, S.; Wilkes, E. (2004): Chemical analysis of grapes and wine: techniques and concepts. Patrick Iland Wine Promotions, Campbelltown (Australien). [nicht online geprüft]
21. Zoecklein, B. W.; Fugelsang, K. C.; Gump, B. H.; Nury, F. S. (1995): Wine Analysis and Production. Chapman & Hall, New York. [nicht online geprüft]
22. Ough, C. S.; Amerine, M. A. (1988): Methods for Analysis of Musts and Wines. 2. Auflage, John Wiley & Sons, New York. [nicht online geprüft]
23. Ribéreau-Gayon, P.; Dubourdieu, D.; Donèche, B.; Lonvaud, A. (2006): Handbook of Enology, Volume 1: The Microbiology of Wine and Vinifications. 2. Auflage, John Wiley & Sons, Chichester. [nicht online geprüft – Glucophilie der Hefe, Botrytis-Inhaltsstoffe]
24. Verordnung (EU) Nr. 1308/2013 über eine gemeinsame Marktorganisation für landwirtschaftliche Erzeugnisse, Anhang II Teil IV (Begriffsbestimmungen im Weinsektor), konsolidierte Fassung. EUR-Lex, Stand 18.08.2026. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 18.08.2026: Nr. 13–16 vorhandener, potenzieller, Gesamt- und natürlicher Alkoholgehalt]
25. OIV: Reducing substances. Methode OIV-MA-AS311-01A. In: Compendium of International Methods of Wine and Must Analysis. [nicht online geprüft – Prinzip aus dem Fachwissen]
26. Haynes, W. M. (Hrsg.) (2016): CRC Handbook of Chemistry and Physics. 97. Auflage, CRC Press, Boca Raton (Dichte und Brechzahl wässriger Saccharose- und Ethanollösungen). [nicht online geprüft]
27. University of Minnesota Extension (2024): Beitrag im Fruit and Vegetable IPM Blog zur Beerenprobenahme. https://blog-fruit-vegetable-ipm.extension.umn.edu/2024/08/madeline-wimmer-extension-educator-and.html [online geprüft]
28. Republik Österreich, Nationalrat (2016): Beschluss zu 1061 der Beilagen XXV. GP, Bundesgesetz, mit dem das Weingesetz 2009 geändert wird (BGBl. I Nr. 47/2016). https://www.parlament.gv.at/dokument/XXV/BNR/328/fnameorig_533502.html [online geprüft – nur Suchergebnis-Auszug: Kabinett 17 °KMW, höchstens 12,9 % vol, keine Süßung; § 5 Abs. 2]
