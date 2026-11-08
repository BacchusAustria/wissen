# Schweflige Säure (SO2): freie, gebundene und molekulare SO2

## Kurzfassung

- **Was:** Bestimmung der freien und der gesamten schwefligen Säure (SO2) in Most und Wein, Berechnung der molekularen SO2 aus freier SO2 und pH, Berechnung der SO2-Zugabe.
- **Wozu:** SO2 schützt vor Oxidation und vor Hefen und Bakterien. Antimikrobiell wirkt vor allem der kleine molekulare Anteil, und der hängt stark vom pH ab. Die Gesamt-SO2 ist rechtlich begrenzt (Kapitel 7).
- **Methode 1 – Iodometrie nach Ripper:** billig, rund 5 Minuten je Wert, für Weißwein und Rosé brauchbar. Bei Rotwein, bei Zusatz von Ascorbinsäure und in Grenzwertnähe ungenau.
- **Methode 2 – Aeration-Oxidation (A-O):** Prinzip der OIV-Referenzmethode, 20 bis 30 Minuten je Wert, Glasapparatur und Pumpe nötig. Deutlich weniger störanfällig, daher die Methode der Wahl für Rotwein.
- **Methode 3 – Schnelltests:** Teststreifen nur zur Grobkontrolle. Ampullen-Tests und Mini-Titratoren arbeiten nach dem Ripper-Prinzip und haben dessen Störungen. Ein Elektroden-Endpunkt löst nur das Farbproblem bei Rotwein.
- **Genauigkeit:** Im AOAC-Ringversuch hatte die Ripper-Methode systematische Fehler zwischen den Labors von etwa 3 bis 4 mg/L (freie SO2) und 15 bis 17 mg/L (Gesamt-SO2) [8]. In Grenzwertnähe gehört die Gesamt-SO2 ins Labor [3].

## 1 Wozu? Chemie und Bedeutung

### 1.1 Die drei Formen der gelösten SO2

Gelöstes Schwefeldioxid steht in Wasser und Wein über zwei Säure-Base-Gleichgewichte mit seinen Ionen im Gleichgewicht [14, 18]:

```
SO2·H2O  ⇌  H+ + HSO3⁻      pKa1 ≈ 1,8
HSO3⁻    ⇌  H+ + SO3²⁻      pKa2 ≈ 7,2
```

- **Molekulares SO2** (SO2·H2O, früher „H2SO3“): ungeladen, flüchtig und dadurch riechbar. Es dringt in Mikroorganismen ein und ist der antimikrobiell wirksame Teil.
- **Hydrogensulfit** (Bisulfit, HSO3⁻): beim pH des Weins die Hauptform. Es bindet Aldehyde und Ketone und trägt die antioxidative Wirkung.
- **Sulfit** (SO3²⁻): beim pH des Weins praktisch bedeutungslos.

Anteile der Formen an der freien SO2, berechnet mit pKa1 = 1,81 und pKa2 = 7,2:

| pH | molekulares SO2 | Hydrogensulfit | Sulfit |
|---|---|---|---|
| 3,0 | 6,1 % | 93,9 % | 0,006 % |
| 3,5 | 2,0 % | 98,0 % | 0,02 % |
| 4,0 | 0,6 % | 99,3 % | 0,06 % |

Analytisch werden alle Formen als „mg/L SO2“ angegeben.

### 1.2 Frei, gebunden, gesamt

- **Freie SO2** = molekulares SO2 + Hydrogensulfit + Sulfit.
- **Gebundene SO2** = Anlagerungsverbindungen (Hydroxysulfonate) des Hydrogensulfits an Carbonylverbindungen und Anthocyane.
- **Gesamt-SO2** = freie + gebundene SO2. Der Gesetzgeber begrenzt die Gesamt-SO2.

Die Bindungen sind Gleichgewichte. Wird freie SO2 verbraucht, etwa durch Oxidation oder bei der Analyse, zerfällt ein Teil der schwach gebundenen SO2 und liefert freie SO2 nach [14]. Für den Schutz zählt die freie SO2, genauer ihr molekularer Anteil. Die gebundene SO2 schützt kaum, zählt aber voll zum Grenzwert. Ziel ist deshalb: genug freie SO2 bei möglichst wenig gebundener SO2.

### 1.3 Bindungspartner

| Bindungspartner | Herkunft | Bindung | 1 mg/L bindet höchstens | Praxis |
|---|---|---|---|---|
| Acetaldehyd (Ethanal) | Hefestoffwechsel, Oxidation von Ethanol, Kahmhefen | sehr fest; bei üblichen SO2-Gehalten praktisch vollständig gebunden | 1,45 mg/L SO2 | wichtigster Bindungspartner trockener Weine |
| Brenztraubensäure (Pyruvat) | Hefe; mehr bei Thiaminmangel | mittel | 0,73 mg/L SO2 | Thiamin als Hefenährstoff senkt die Bildung, siehe [Stickstoff und YAN](stickstoff-yan.md) |
| 2-Oxoglutarsäure (α-Ketoglutarsäure) | Hefe | mittel | 0,44 mg/L SO2 | wie Pyruvat |
| Glucose und andere Zucker | Traube | schwach, aber hohe Konzentration | 0,36 mg/L SO2 (theoretisch) | wichtig in Süßweinen |
| Ketoverbindungen aus Botrytis und Essigbakterien | faule und edelfaule Trauben | fest | – | hoher SO2-Bedarf bei Botrytisweinen |
| Uronsäuren (z. B. Galacturonsäure) | Pektinabbau | schwach | – | gering |
| Anthocyane | Rotwein | schwach, umkehrbar; entfärbt den Wein | – | Puffer, der bei der Analyse SO2 nachliefert (Kapitel 3.7 und 4.7) |

Die Spalte „1 mg/L bindet höchstens“ ist die Stöchiometrie der 1:1-Bindung (molare Massen). Wie viel tatsächlich gebunden wird, hängt von der Dissoziationskonstante und von der freien SO2 ab [19, 29]. Qualitative Einstufung nach [14, 18, 19].

Für die Praxis heißt das: Gebundene SO2 entsteht zum größten Teil durch Acetaldehyd. Hefen bilden mehr Acetaldehyd, wenn der Most stark geschwefelt wurde [14]. Gesunde Trauben, eine ausreichend versorgte Gärung und Schutz vor Luft halten den Acetaldehyd niedrig. Dann braucht man für dieselbe freie SO2 weniger Gesamt-SO2.

### 1.4 Wirkungen

- **Antimikrobiell:** Molekulares SO2 hemmt Hefen (auch *Brettanomyces*), Milchsäure- und Essigsäurebakterien [14]. Ethanol verstärkt die Wirkung [13]. Wer einen biologischen Säureabbau will, darf vorher nur wenig schwefeln; siehe [Apfel-Milchsäure-Abbau](apfel-milchsaeure-bsa.md).
- **Antioxidativ:** SO2 reagiert kaum direkt mit Sauerstoff. Es fängt das Wasserstoffperoxid ab, das bei der Oxidation von Phenolen entsteht, und reduziert Chinone zu Phenolen zurück. Außerdem bindet es Acetaldehyd und verdeckt so den Oxidationston [18, 21].
- **Sauerstoffverbrauch:** Netto werden je Molekül O2 zwei Moleküle SO2 verbraucht. Deshalb kostet **1 mg/L aufgenommener Sauerstoff bis zu 4 mg/L SO2** (Stöchiometrie, [21]). Das zählt beim Umpumpen, Filtrieren und Füllen.
- **Antienzymatisch:** SO2 hemmt die Polyphenoloxidase der Traube. Die Laccase von *Botrytis cinerea* ist deutlich unempfindlicher. Deshalb bräunen Moste aus faulem Lesegut trotz Schwefelung [14].
- **Nebenwirkungen:** stechender Geruch bei viel molekularem SO2, Unverträglichkeit bei empfindlichen Menschen (Kennzeichnungspflicht, Kapitel 7.4), Hemmung des biologischen Säureabbaus.

### 1.5 Molekulare SO2 berechnen

Die molekulare SO2 wird nicht gemessen, sondern aus freier SO2 und pH berechnet:

```
molekulare SO2 (mg/L) = freie SO2 (mg/L) / (1 + 10^(pH − pKa))

benötigte freie SO2 (mg/L) = Zielwert molekular (mg/L) × (1 + 10^(pH − pKa))
```

**Welcher pKa?** Der Wert ist keine feste Konstante.

- Die AWRI rechnet mit pKa = 1,8 nach Margalit (1997). Dieser Wert stammt aus Daten für Wasser bei 25 °C und berücksichtigt den Alkohol nicht [6, 11]. Viele Lehrbücher verwenden 1,81 bei 20 °C [14, 15].
- Nach AWRI erhöhen Temperatur und Alkohol den molekularen Anteil, die Temperatur stärker als der Alkohol [6].
- Die OIV-Methode OIV-MA-AS323-04C rechnet den molekularen Anteil mit Tabellen aus pH, Alkoholgehalt und Temperatur. Sie verwendet eine thermodynamische Konstante pkT und eine „gemischte“ Konstante pkM für die Ionenstärke 0,038 [4]. Im online gesehenen Tabellenauszug steht für 0 % vol pkT = 1,798 bei 20 °C und 2,000 bei 25 °C. Die Tabellen gehen auf Messungen von Usseglio-Tomasset und Bosia (1984) zurück [10].
- **Widerspruch:** Für 25 °C liegt der OIV-Wert (2,00) deutlich über dem AWRI-Wert (1,8). Mit dem OIV-Wert ergibt sich bei gleicher freier SO2 mehr molekulare SO2.

> **Offen:** Die vollständigen OIV-Tabellen (pkT und pkM für verschiedene Alkoholgehalte) wurden nur auszugsweise gesehen. Temperatur- oder alkoholkorrigierte Werte vor Verwendung im Original von OIV-MA-AS323-04C nachlesen.

In der Kellerpraxis hat sich pKa = 1,81 als Konvention durchgesetzt. Die Zielwerte der Literatur (Kapitel 1.6) beziehen sich auf diese Rechenweise. Die folgende Tabelle ist damit berechnet und auf ganze mg/L gerundet.

**Benötigte freie SO2 (mg/L) für einen Zielwert an molekularer SO2 (pKa 1,81):**

| pH | Anteil molekular | für 0,5 mg/L | für 0,6 mg/L | für 0,8 mg/L |
|---|---|---|---|---|
| 3,0 | 6,1 % | 8 | 10 | 13 |
| 3,1 | 4,9 % | 10 | 12 | 16 |
| 3,2 | 3,9 % | 13 | 15 | 20 |
| 3,3 | 3,1 % | 16 | 19 | 26 |
| 3,4 | 2,5 % | 20 | 24 | 32 |
| 3,5 | 2,0 % | 25 | 30 | 40 |
| 3,6 | 1,6 % | 31 | 38 | 50 |
| 3,7 | 1,3 % | 39 | 47 | 63 |
| 3,8 | 1,0 % | 49 | 59 | 79 |

**Wie stark der pKa das Ergebnis verschiebt** (pH 3,4, Ziel 0,8 mg/L): pKa 1,72 → 39 mg/L; pKa 1,81 → 32 mg/L; pKa 1,90 → 26 mg/L; pKa 2,00 → 21 mg/L.

**Wie stark der pH das Ergebnis verschiebt:** Bei pH 3,50 braucht man 40 mg/L. Liegt der wahre pH 0,05 höher (3,55), sind es 45 mg/L (+12 %). Bei 0,1 höher (3,60) sind es 50 mg/L (+25 %). Ein sauber kalibriertes pH-Meter ist für die SO2-Führung daher genauso wichtig wie die SO2-Messung selbst; siehe [Säure und pH](saeure-ph.md).

### 1.6 Zielwerte

| Wein | Ziel molekulare SO2 | Quelle und Bemerkung |
|---|---|---|
| Weißwein, Rosé, trocken | mindestens 0,8 mg/L | AWRI: „mehr als 0,8 mg/L“ [6]; klassischer Wert nach Beech et al. (1979) [20] |
| Rotwein, trocken | mindestens 0,5 bis 0,6 mg/L | AWRI: „mehr als 0,6 mg/L“ [6]; 0,5 mg/L in US-Beratungsliteratur [22] |
| Weine mit Restzucker | höher als bei trockenen Weinen | keine belastbare Zahl gefunden; Restsüße schützt man vor allem durch Sterilfiltration und saubere Füllung |

Die AWRI betont, dass der passende Wert vom Weintyp abhängt und davon, ob man vor Oxidation oder vor einem bestimmten Mikroorganismus schützen will [6].

> **Achtung:** Bei Rotwein überschätzen die üblichen Messverfahren (Ripper und A-O) die wirksame SO2, weil schwach an Anthocyane gebundene SO2 während der Analyse freigesetzt wird. Nach Howe et al. (2018) wirkt die so gemessene SO2 in Rotwein antimikrobiell schwächer als in Weißwein [12]. In einer Kopfraum-Methode lag die molekulare SO2 in Rotweinen im Mittel nur halb so hoch wie mit A-O gemessen [23]. Bei Rotweinen mit hohem pH und Brettanomyces-Risiko daher nicht allein auf 0,5 mg/L verlassen. Hygiene, niedrige Lagertemperatur, volle Gebinde und gegebenenfalls Filtration gehören dazu.

## 2 Welche Methode wofür?

| Methode | misst | Zeit je Wert | Investition | Hauptstörungen | geeignet für |
|---|---|---|---|---|---|
| Ripper (Iodometrie) | frei, gesamt | 5–15 min | gering: Bürette, Pipetten, 3 Lösungen | Ascorbinsäure, Phenole, Reduktone; Endpunkt bei Rotwein | Routine Weißwein, Rosé, Most |
| Aeration-Oxidation (A-O) | frei, gesamt | 20–30 min | mittel: Glasapparatur, Pumpe, Durchflussmesser, Heizquelle | flüchtige Säuren (nur bei gesamt), Temperatur, Durchfluss | Rotwein, Kontrolle der Ripper-Werte |
| Teststreifen | frei (grob) | 1 min | sehr gering | Farbe, Ablesestufen | nur Grobkontrolle |
| Ampullen-Tests, Mini-Titratoren | frei, teils gesamt | 2–10 min | gering bis mittel | wie Ripper | Routine, wenn regelmäßig gegengeprüft |
| Fotometer-Kits | frei, gesamt | 5–15 min | mittel (Fotometer) | je nach Reagenz; Farbe bei Rotwein | Betriebe mit Fotometer, siehe [Fotometrie und Enzymatik](fotometrie-enzymatik.md) |
| Labor (amtlich autorisiert) | frei, gesamt | Tage | Kosten je Probe | – | Grenzwertnähe, Prüfnummer, Streitfall |

Die OIV führt die A-O-Methode für die Gesamt-SO2 als Typ-II-Methode (Referenz). Freie SO2 nach A-O und die Iodometrie sind Typ-IV-Methoden (Schnell- bzw. Hilfsmethoden) [1–3].

### Probenahme für alle Methoden

1. Probe ohne Spritzen und Schäumen ziehen. Die Flasche bis zum Rand füllen und sofort verschließen.
2. Kühl lagern und möglichst am selben Tag messen. SO2 geht durch Luftkontakt verloren.
3. Vor der Messung auf etwa 20 °C bringen. Das Gleichgewicht zwischen freier und gebundener SO2 hängt von der Temperatur ab [1, 14].
4. Nach einer SO2-Zugabe den Tank gut mischen. Frühestens am nächsten Tag messen; die Bindungsreaktionen brauchen Stunden bis Tage [14].

## 3 Methode 1: Iodometrische Titration nach Ripper

### 3.1 Prinzip

Iod oxidiert SO2 in saurer Lösung zu Sulfat:

```
SO2 + I2 + 2 H2O  →  SO4²⁻ + 2 I⁻ + 4 H+
```

1 mol Iod entspricht 1 mol SO2. Am Endpunkt bildet der erste Iodüberschuss mit Stärke eine blaue Einschlussverbindung.

- **Freie SO2:** Den angesäuerten Wein direkt titrieren.
- **Gesamt-SO2:** Zuerst mit Natronlauge die gebundene SO2 freisetzen (alkalische Spaltung der Hydroxysulfonate). Danach ansäuern und sofort titrieren.

Die OIV beschreibt das Verfahren als OIV-MA-AS323-04B (Typ IV) [3]. Die OIV-Fassung verwendet:

- 50 mL Wein, 5 mL Stärkelösung, 30 mg EDTA und 3 mL verdünnte Schwefelsäure,
- Iodlösung 0,025 mol/L und Natronlauge 4 mol/L,
- zwei Spaltungsschritte (8 mL Natronlauge, 5 min; dann 20 mL Natronlauge, 5 min).

Die OIV rechnet: freie SO2 = 32 · n und Gesamt-SO2 = 32 · (n + n' + n''), mit n, n', n'' in mL Iodlösung. Für Rotweine mit wenig SO2 darf die Iodlösung verdünnt werden, zum Beispiel auf 0,01 mol/L [3].

Die folgende Anleitung verwendet durchgehend Iodlösung 0,01 mol/L (0,02 N). Für die Gesamt-SO2 nutzt sie die einfache Spaltung mit Natronlauge 1 mol/L, wie sie in den Lehrbüchern von Zoecklein et al. und Iland et al. beschrieben ist [16, 17]. Das ist für einen kleinen Keller handlicher und mit weniger ätzender Lauge sicherer.

### 3.2 Material

| Material | Spezifikation | Verbrauch je Analyse |
|---|---|---|
| Bürette | 10 mL, Teilung 0,02 oder 0,05 mL, mit Stativ; alternativ Flaschenaufsatz- oder Digitalbürette | – |
| Vollpipetten | 50 mL und 25 mL, Klasse AS, mit Pipettierhilfe (Peleusball) | – |
| Erlenmeyerkolben | 250 mL, Weithals, 2–3 Stück | – |
| Messzylinder oder Dispenser | 10 mL und 25 mL (Dispenser für Säure und Lauge ist sicherer) | – |
| Stopfen oder Parafilm | für den Spaltungsansatz | – |
| weiße Unterlage, Lampe | für Rotwein Licht von unten (gelbes Licht nach OIV) [3] | – |
| Iodlösung 0,01 mol/L (0,02 N) | Maßlösung, fertig gekauft; alternativ Iodid-Iodat-Lösung (Kapitel 3.3) | 2–6 mL |
| Schwefelsäure ca. 25 % | fertig gekauft | 5 mL (frei), 10 mL (gesamt) |
| Natronlauge 1 mol/L | Maßlösung oder selbst angesetzt | 25 mL (nur gesamt) |
| Stärkelösung | 5–10 g/L, stabilisiert oder frisch | 5 mL |
| EDTA-Dinatriumsalz | p. a., Pulver | ca. 30 mg (optional, empfohlen [3]) |
| Für die Korrektur (Kapitel 3.7) | Propanal ≥ 97 % oder Ethanal; daraus Lösung 10 g/L bzw. 7 g/L | 5 mL Lösung |
| Für die Titerkontrolle (optional) | Natriumthiosulfat-Maßlösung 0,1 mol/L | 10 mL verdünnte Lösung |
| Schutzbrille, Nitrilhandschuhe | – | – |

Bezugsquellen und Preise: siehe [Einkaufsliste](einkaufsliste.md). Allgemeine Laborpraxis wie Pipettieren und Bürette-Ablesen: siehe [Grundlagen Labor](grundlagen-labor.md).

### 3.3 Reagenzien

**Iodlösung 0,01 mol/L (0,02 N):** Fertig als Maßlösung kaufen. In brauner Glasflasche kühl, dunkel und gut verschlossen lagern. Iod verdunstet und reagiert mit Verunreinigungen. Den Titer deshalb regelmäßig prüfen, etwa monatlich und vor wichtigen Messungen, und das Öffnungsdatum auf die Flasche schreiben.

**Iodid-Iodat-Variante:** Statt Iodlösung kann man eine Kaliumiodat-Kaliumiodid-Lösung verwenden. Erst in der sauren Probe entsteht daraus Iod:

```
IO3⁻ + 5 I⁻ + 6 H+  →  3 I2 + 3 H2O
```

1 mol Kaliumiodat liefert 3 mol Iod. Kaliumiodat ist eine Urtitersubstanz, die Lösung ist lange stabil. Ansatz für eine Lösung, die Iod 0,01 mol/L (0,02 N) entspricht:

- 20,0 mL Kaliumiodat-Maßlösung c(1/6 KIO3) = 0,1 mol/L (das sind 1/60 mol/L KIO3) mit Vollpipette in einen 100-mL-Messkolben geben,
- 1 g Kaliumiodid zugeben und mit Wasser zur Marke auffüllen.
- Alternativ 0,7133 g Kaliumiodat (getrocknet) und etwa 10 g Kaliumiodid in Wasser zu 1 L lösen.

Die Probe muss beim Titrieren deutlich sauer sein. Das ist mit der Schwefelsäure gegeben.

**Stärkelösung:** Stabilisierte Lösung kaufen oder selbst ansetzen. Dazu 1 g lösliche Stärke mit wenig kaltem Wasser anrühren, in 100 mL siedendes Wasser einrühren, 1 bis 2 Minuten kochen und abkühlen lassen. Im Kühlschrank einige Tage haltbar. Ist die Lösung trüb oder schimmelig, verwerfen. Die OIV setzt 5 g/L Stärke an und gibt 200 g/L Natriumchlorid zur Haltbarkeit zu [3].

**Schwefelsäure ca. 25 % (ca. 3 mol/L):** Fertig kaufen. Selbst verdünnen nur mit Erfahrung und Schutzausrüstung: immer Säure ins Wasser, nie umgekehrt.

**Natronlauge 1 mol/L:** Fertig kaufen oder 40,0 g Natriumhydroxid-Plätzchen unter Kühlung in Wasser lösen und auf 1 L auffüllen. Die Lösung wird dabei heiß. In Kunststoffflasche lagern.

**Titerkontrolle der Iodlösung (optional):** Natriumthiosulfat-Maßlösung 0,1 mol/L mit Wasser 1:5 auf 0,02 mol/L verdünnen. 10,00 mL Iodlösung vorlegen und mit der Thiosulfatlösung titrieren, bis die Lösung hellgelb ist. 1 mL Stärke zugeben und bis farblos weitertitrieren. Bei exakt 0,01 mol/L Iod beträgt der Verbrauch 10,00 mL (I2 + 2 S2O3²⁻ → 2 I⁻ + S4O6²⁻). Tatsächliche Konzentration = 0,01 mol/L × Verbrauch / 10,00 mL.

### 3.4 Durchführung: freie SO2

1. Probe auf 18 bis 22 °C bringen. Flasche nicht schütteln.
2. Bürette mit Iodlösung füllen, Luftblasen aus der Spitze ablassen, auf 0,00 mL einstellen.
3. 50 mL Wein mit der Vollpipette in einen 250-mL-Erlenmeyerkolben geben. Die Pipette an der Kolbenwand auslaufen lassen, nicht spritzen.
4. Eine kleine Spatelspitze EDTA-Dinatriumsalz (ca. 30 mg) zugeben. EDTA bindet Metallspuren, die sonst die Luftoxidation der SO2 während der Titration beschleunigen [3].
5. 5 mL Stärkelösung zugeben.
6. 5 mL Schwefelsäure ca. 25 % zugeben und **sofort** titrieren.
7. Iodlösung unter ständigem Schwenken zügig zulaufen lassen, gegen Ende tropfenweise.
8. Endpunkt: Die erste Blaufärbung (bei Rosé blauviolett) bleibt 10 bis 15 Sekunden bestehen [3]. Ein späteres Verblassen nicht nachtitrieren.
9. Verbrauch V(frei) auf 0,05 mL genau ablesen und notieren.
10. Eine zweite Bestimmung machen. Weichen beide um mehr als 0,1 mL ab, eine dritte machen und die beiden nächstliegenden Werte mitteln.

**Rotwein:** Der Umschlag geht von Rot nach einem dunklen Blauviolett bis Blaugrau und ist schwer zu sehen. Den Kolben von unten beleuchten; die OIV empfiehlt gelbes Licht [3]. Zum Vergleich einen zweiten Kolben mit unbehandeltem Wein daneben stellen. Besser: Redox-Endpunkt mit Platinelektrode (Kapitel 5) oder gleich die A-O-Methode.

### 3.5 Durchführung: gesamte SO2

1. 25 mL Wein mit der Vollpipette in einen 250-mL-Erlenmeyerkolben geben.
2. 25 mL Natronlauge 1 mol/L zugeben, umschwenken und den Kolben mit Stopfen oder Parafilm verschließen.
3. 10 Minuten bei Raumtemperatur stehen lassen. In dieser Zeit spaltet die Lauge die gebundene SO2 ab [16, 17].
4. 5 mL Stärkelösung und 10 mL Schwefelsäure ca. 25 % zugeben. Der Ansatz ist danach stark sauer: 10 mL Säure enthalten rund 60 mmol H+, die Lauge nur 25 mmol OH⁻. Beim ersten Mal mit pH-Papier prüfen (pH unter 2).
5. **Sofort** wie in 3.4 titrieren. Sonst bindet sich die freigesetzte SO2 wieder an den Acetaldehyd.
6. Verbrauch V(gesamt) notieren und eine Doppelbestimmung machen.

> **Achtung:** Natronlauge 1 mol/L und Schwefelsäure 25 % verätzen Haut und Augen. Schutzbrille und Handschuhe tragen. Beim Ansäuern wird der Ansatz warm.

### 3.6 Berechnung

Allgemein:

```
SO2 (mg/L) = V(Iod, mL) × c(Iod, mol/L) × 64,06 (mg/mmol) × 1000 / V(Probe, mL)
```

Faktoren für Iod 0,01 mol/L (0,02 N), also 0,6406 mg SO2 je mL Iodlösung:

| Probevolumen | Faktor (mg/L je mL Iodlösung) | Ablesefehler 0,05 mL entspricht |
|---|---|---|
| 50 mL (freie SO2) | 12,81 | 0,6 mg/L |
| 25 mL (gesamte SO2) | 25,62 | 1,3 mg/L |
| 20 mL | 32,03 | 1,6 mg/L |

Zum Vergleich mit der OIV-Fassung: Iod 0,025 mol/L und 50 mL Probe ergeben 32,03 mg/L je mL. Das ist der OIV-Faktor 32 [3].

```
freie SO2 (mg/L)      = V(frei) × 12,8
gesamte SO2 (mg/L)    = V(gesamt) × 25,6
gebundene SO2 (mg/L)  = gesamte SO2 − freie SO2
```

**Rechenbeispiel (Grüner Veltliner, pH 3,35):**

- freie SO2: V(frei) = 2,45 mL → 2,45 × 12,81 = **31,4 mg/L**
- gesamte SO2: V(gesamt) = 4,85 mL → 4,85 × 25,62 = **124,3 mg/L**
- gebundene SO2: 124,3 − 31,4 = **92,9 mg/L**

**Mit Blindwertkorrektur (Kapitel 3.7):** Der Blindwert auf 50 mL beträgt 0,20 mL, das sind 0,20 × 12,81 = 2,6 mg/L. Korrigiert: freie SO2 = 28,8 mg/L, gesamte SO2 = 121,7 mg/L. Molekulare SO2 bei pH 3,35: 28,8 / (1 + 10^(3,35 − 1,81)) = **0,81 mg/L**. Das genügt für einen Weißwein knapp.

**Titerkorrektur:** Hat die Iodlösung laut Kontrolle nur 0,0096 mol/L, sinken die Ergebnisse um 4 %. Aus den unkorrigierten Werten werden 30,1 mg/L (frei) und 119,3 mg/L (gesamt). Bei älteren Lösungen ist das ein häufiger, unbemerkter Fehler.

### 3.7 Störungen und Korrektur

Iod oxidiert nicht nur SO2. Alles, was Iod verbraucht, täuscht SO2 vor. Umgekehrt geht SO2 verloren, wenn man langsam arbeitet.

| Störung | Wirkung | Gegenmaßnahme |
|---|---|---|
| Ascorbinsäure (Vitamin C) | zu hoch: 1 mg Ascorbinsäure verbraucht so viel Iod wie 0,36 mg SO2 | Ripper bei Weinen mit Ascorbinsäure-Zusatz nicht verwenden; A-O nehmen |
| Phenole, Tannine, Reduktone | zu hoch, vor allem in Rotwein und Botrytisweinen | Blindwert (siehe unten) oder A-O |
| Zerfall schwach gebundener SO2 während der Titration (Anthocyane) | zu hoch bei freier SO2 in Rotwein | zügig titrieren, Endpunkt 10–15 s |
| Luftoxidation während der Titration, Metallkatalyse | zu niedrig | zügig arbeiten, EDTA zugeben [3] |
| schwer erkennbarer Endpunkt in Rotwein | meist zu hoch (Übertitrieren) | Licht von unten, Vergleichskolben, Redoxelektrode |
| gealterte Iodlösung | zu hoch (Titer niedriger als angenommen, Ergebnis wird mit falschem Faktor gerechnet) | Titer prüfen |

Rechenbeispiel Ascorbinsäure: Die EU erlaubt bis 250 mg/L L-Ascorbinsäure im Wein (Fundstelle siehe [Grenzwerte und Recht](grenzwerte-recht.md)). Schon 100 mg/L täuschen beim Ripper rund 36 mg/L SO2 vor, 250 mg/L sogar rund 91 mg/L.

**Korrektur mit Blindwert nach OIV [3]:** Man bindet die freie SO2 zuerst mit einem großen Überschuss an Aldehyd. Dann titriert man, was trotzdem noch Iod verbraucht. Diesen Blindwert zieht man von freier und gesamter SO2 ab.

1. Propanal-Lösung 10 g/L ansetzen: 1,24 mL Propanal (Dichte 0,807 g/mL) in einem 100-mL-Messkolben mit Wasser zur Marke auffüllen. Gut verschlossen und kühl lagern; nur wenige Tage haltbar. Die OIV nennt alternativ Ethanal (Acetaldehyd) 7 g/L [3]. Propanal ist leichter zu handhaben, weil Acetaldehyd schon bei etwa 20 °C siedet.
2. 50 mL Wein in einen Erlenmeyerkolben geben, 5 mL Propanal-Lösung zugeben, verschließen und mindestens 30 Minuten stehen lassen. 5 mL Propanal-Lösung enthalten rund 0,86 mmol Aldehyd. Das ist etwa das 18-Fache der freien SO2 in 50 mL Wein mit 60 mg/L.
3. Stärkelösung und 5 mL Schwefelsäure zugeben und wie in 3.4 bis zum Endpunkt titrieren. Der Verbrauch ist V(Blind).
4. Blindwert B (mg/L) = V(Blind) × 12,81. Von freier und gesamter SO2 abziehen (Rechenbeispiel in 3.6).

Für Weißweine ohne Zusätze ist der Blindwert meist klein, aber nicht null. Bei Rotweinen, Botrytisweinen und neuen Weinen den Blindwert einige Male bestimmen. Ist er hoch oder schwankt er, auf die A-O-Methode wechseln.

> **Offen:** Typische Größenordnungen des Blindwerts für österreichische Weiß- und Rotweine wurden nicht gefunden. Der AOAC-Ringversuch hat iodreaktive Stoffe außer SO2 mitbestimmt [8]; die Zahlen daraus sind noch nachzulesen.

### 3.8 Genauigkeit

- **Ringversuch (AOAC):** 23 Labors untersuchten Weine mit der Ripper-Methode. Der systematische Fehler zwischen den Labors betrug bei Weißwein etwa 2,7 mg/L (frei) und 16,6 mg/L (gesamt), bei Rotwein etwa 4,3 bzw. 15,1 mg/L. Die Wiederholpräzision in einem Labor lag je nach Fraktion und Weinart bei etwa 1,9 bis 10,4 mg/L. Die Autoren nannten die Methode schnell und bequem, aber durch geringe Präzision und große systematische Fehler stark eingeschränkt. Die AOAC übernahm sie nicht [8].
- **OIV:** Liegt die gefundene Gesamt-SO2 nahe am gesetzlichen Höchstwert oder darüber, ist die Gesamt-SO2 mit der Referenzmethode zu bestimmen [3].
- **Ablesung:** Mit einer 10-mL-Bürette (Teilung 0,05 mL) liegt der reine Ablesefehler bei rund 0,6 mg/L (freie SO2, 50 mL) bzw. 1,3 mg/L (gesamte SO2, 25 mL).
- **Empfehlung:** Für die Kellerführung bei Weißwein ist der Ripper ausreichend, wenn Titer und Blindwert bekannt sind. Mindestens ein- bis zweimal im Jahr dieselbe Probe parallel in einem Labor messen lassen und die Abweichung notieren.

## 4 Methode 2: Aeration-Oxidation (A-O)

### 4.1 Prinzip

Der Wein wird mit Phosphorsäure stark angesäuert. Dadurch liegt die freie SO2 fast vollständig molekular und flüchtig vor. Ein Luftstrom treibt sie aus und leitet sie durch eine neutrale Wasserstoffperoxid-Lösung. Dort entsteht Schwefelsäure, die man mit Natronlauge titriert [1, 2, 5]:

```
SO2 + H2O2            →  H2SO4
H2SO4 + 2 NaOH        →  Na2SO4 + 2 H2O
```

1 mol SO2 verbraucht 2 mol NaOH. 1 mL Natronlauge 0,01 mol/L entspricht 0,3203 mg SO2.

- **Freie SO2:** Bei Raumtemperatur austreiben. Die aktuelle OIV-Fassung (OIV-MA-AS323-04A1, seit 2018) arbeitet zwischen 18 und 24 °C, weil die ausgetriebene Menge stark temperaturabhängig ist. Die ältere Fassung arbeitete bei 10 °C [1].
- **Gesamte SO2:** Den Wein während des Austreibens sieden lassen (etwa 100 °C). Dabei zerfällt auch die gebundene SO2 (OIV-MA-AS323-04A2, Typ II) [2].

Die Methode heißt nach ihren Entwicklern auch Monier-Williams- oder Rankine-Pocock-Methode. In Australien ist sie das übliche Verfahren für freie und gesamte SO2 [5, 7]. Bis 2018 standen freie und gesamte SO2 gemeinsam in der Methode OIV-MA-AS323-04A. Mit der Resolution OIV-OENO 591A-2018 wurde sie in 04A1 und 04A2 geteilt [1, 2].

### 4.2 Aufbau

Saugend betrieben, in Strömungsrichtung:

```
Lufteinlass
   │
   ▼
Einleitrohr bis fast zum Boden
   │
   ▼
Rundkolben mit Wein + Phosphorsäure   ◄── Heizpilz oder kleiner Brenner (nur Gesamt-SO2)
   │
   ▼
Rückflusskühler (Wasserkühlung)
   │
   ▼
Vorlage: 10 mL H2O2 0,3 % + Indikator (Gaswaschflasche oder Birnenkolben mit Einleitrohr)
   │
   ▼
Durchflussmesser (ca. 1 L/min) mit Nadelventil
   │
   ▼
Vakuumquelle (Wasserstrahlpumpe oder Membranpumpe)
```

- **Saugend oder drückend:** Saugend ist günstiger. Dann zieht ein Leck Raumluft herein, statt SO2 hinauszudrücken. Mit einer drückenden Aquarienpumpe geht es auch, wenn alle Verbindungen dicht sind. Beide Varianten liefern bei einem Leck zu niedrige Werte.
- **Kolben:** 250 mL für 50 mL Probe (OIV) [1], 100 mL für 20 mL Probe.
- **Kühler:** Liebig- oder Dimrothkühler mit Leitungswasser. Er hält bei der Gesamt-SO2 Wasserdampf und flüchtige Säuren zurück. Die TTB kühlt mit etwa 5 °C kaltem Wasser [9].
- **Schliffe:** einheitliche Normschliffe (z. B. NS 19/26) mit Klemmen. Komplette A-O-Glassätze gibt es im Laborhandel.
- **Durchflussmesser:** Schwebekörper-Durchflussmesser, Messbereich etwa 0,2 bis 2 L/min.

### 4.3 Material und Reagenzien

| Material | Spezifikation | Verbrauch je Analyse |
|---|---|---|
| A-O-Apparatur | wie 4.2 | – |
| Bürette | 10 mL, Teilung 0,02 oder 0,05 mL | – |
| Vollpipetten | 50 mL, 20 mL, 10 mL | – |
| Phosphorsäure ca. 25 % | z. B. 300 mL Phosphorsäure 85 % mit Wasser auf 1 L verdünnen; Säure ins Wasser. Die OIV nennt diese Verdünnung „etwa 25,5 %“ [1]; gemeint ist offenbar 30 Volumenteile der 85-%-Säure. Die genaue Konzentration ist unkritisch, der Wein muss nur stark sauer werden | 10–15 mL |
| Wasserstoffperoxid 0,3 % | 3-%-Lösung aus der Apotheke 1:10 mit Wasser verdünnen (10 mL + 90 mL); täglich frisch [9] | 10 mL |
| Mischindikator Methylrot/Methylenblau | OIV: 100 mg Methylrot und 50 mg Methylenblau in 50 mL Ethanol (≥ 95 %) [1]; im Handel als Tashiro-Mischindikator | 3 Tropfen |
| Natronlauge 0,01 mol/L (0,01 N) | Maßlösung; OIV: 10,0 mL Natronlauge 1 mol/L mit Wasser auf 1 L [1] | 1–10 mL |
| Heizquelle | Heizpilz für den Kolben oder kleiner Brenner | nur gesamt |

Zur Konzentration des Peroxids gibt es unterschiedliche Angaben: Die TTB verwendet 0,3 % [9], die OIV „3 Volumen“, das sind 9,1 g/L oder etwa 0,9 % [1]. Beides funktioniert, weil das Peroxid weit im Überschuss vorliegt. 10 mL einer 0,3-%-Lösung enthalten 0,88 mmol H2O2. Aus 20 mL Wein mit 200 mg/L SO2 kommen nur 0,06 mmol SO2. Das ist ein 14-facher Überschuss, bei 400 mg/L noch ein 7-facher.

Natronlauge 0,01 mol/L nimmt Kohlendioxid aus der Luft auf. Flasche geschlossen halten und den Titer regelmäßig prüfen, siehe [Säure und pH](saeure-ph.md).

### 4.4 Durchführung: freie SO2

1. Apparatur aufbauen, Kühlwasser anstellen.
2. In die Vorlage 10 mL Wasserstoffperoxid 0,3 % und 3 Tropfen Mischindikator geben. Die Lösung ist meist violett. Mit Natronlauge 0,01 mol/L tropfenweise auf **olivgrün** einstellen [9]. Diesen Farbton merken; er ist auch der Endpunkt.
3. Vorlage anschließen.
4. Wein mit 18 bis 24 °C verwenden [1]. **50 mL** Wein in den 250-mL-Kolben pipettieren (OIV [1]). Alternativ 20 mL Wein in den 100-mL-Kolben.
5. 15 mL (bei 50 mL Wein) bzw. 10 mL (bei 20 mL Wein) Phosphorsäure ca. 25 % zugeben und den Kolben sofort anschließen.
6. Pumpe einschalten und den Luftstrom auf etwa 1 L/min einstellen. 15 Minuten durchsaugen. Der Wein darf nicht in den Kühler schäumen.
7. Pumpe abstellen. Vorlage abnehmen und das Einleitrohr mit wenig Wasser in die Vorlage abspülen.
8. Mit Natronlauge 0,01 mol/L bis zum selben Olivgrün wie in Schritt 2 titrieren. Verbrauch V notieren.
9. Gelegentlich einen Blindversuch mit Wasser statt Wein fahren. Der Verbrauch sollte unter 0,05 mL liegen.

> **Offen:** Die ältere, im Amtsblatt veröffentlichte Fassung der OIV-Referenzmethode (Mitteilung der Kommission, ABl. C 43 vom 19.2.2010, Kapitel 24) nennt einen Gasstrom von etwa 40 L/h (≈ 0,7 L/min), einen Unterdruck von 20–30 cm Wassersäule und 15 Minuten Austreiben, für die freie SO2 bei 50 mL Probe mit 15 mL Phosphorsäure 85 % [32]. Die 15 Minuten sind damit belegt; 1 L/min entspricht der Praxis nach AWRI und Iland et al. [5, 17]. Den Wortlaut der aktuellen Fassung OIV-MA-AS323-04A1 (Durchfluss, Säurekonzentration) vor der Einführung im Betrieb noch abgleichen.

### 4.5 Durchführung: gesamte SO2

1. Vorlage wie in 4.4 vorbereiten (frische Peroxidlösung, auf Olivgrün eingestellt).
2. **20 mL** Wein in den Kolben pipettieren. Die OIV nimmt 20 mL bei erwarteter Gesamt-SO2 ab 50 mg/L und 50 mL darunter [2]. Bei erwartet mehr als 150 mg/L und einer 10-mL-Bürette 10 mL Wein nehmen.
3. 10 mL Phosphorsäure ca. 25 % zugeben, Kolben anschließen und Kühlwasser prüfen.
4. Luftstrom auf etwa 1 L/min einstellen und den Kolben zum leichten Sieden bringen.
5. 15 Minuten unter Sieden durchsaugen.
6. Heizung ausschalten, dann die Pumpe. Vorlage abnehmen, Einleitrohr abspülen und wie in 4.4 titrieren.

> **Achtung:** Siedende Phosphorsäure-Weinmischung spritzt. Siedesteinchen verwenden, nie ein geschlossenes System heizen und die Heizung vor dem Lösen der Verbindungen abschalten.

### 4.6 Berechnung

```
SO2 (mg/L) = V(NaOH, mL) × c(NaOH, mol/L) × 32,03 (mg/mmol) × 1000 / V(Probe, mL)
```

| Probevolumen | Faktor bei NaOH 0,01 mol/L (mg/L je mL) | Ablesefehler 0,05 mL entspricht |
|---|---|---|
| 50 mL | 6,41 (OIV: 6,4) [1, 2] | 0,3 mg/L |
| 20 mL | 16,01 | 0,8 mg/L |
| 10 mL | 32,03 | 1,6 mg/L |

**Rechenbeispiel (Zweigelt, pH 3,55, 13 % vol):**

- freie SO2: 50 mL Wein, Verbrauch 4,30 mL → 4,30 × 6,41 = **27,5 mg/L**
- gesamte SO2: 20 mL Wein, Verbrauch 7,85 mL → 7,85 × 16,01 = **125,7 mg/L**
- gebundene SO2: 125,7 − 27,5 = **98,2 mg/L**
- molekulare SO2: 27,5 / (1 + 10^(3,55 − 1,81)) = **0,49 mg/L**. Für 0,6 mg/L wären bei diesem pH 33,6 mg/L freie SO2 nötig, also rund 6 mg/L mehr (Zugabe berechnen: Kapitel 6).
- Titerkorrektur: Hat die Natronlauge tatsächlich 0,0102 mol/L, wird aus 125,7 mg/L ein Wert von 128,2 mg/L.

### 4.7 Warum A-O bei Rotwein genauer ist und wo die Grenzen liegen

**Vorteile:**

- Titriert wird eine klare Vorlage. Die Weinfarbe stört den Endpunkt nicht.
- Ascorbinsäure, Phenole und Reduktone sind nicht flüchtig. Sie gelangen nicht in die Vorlage und stören deshalb nicht.
- Für die Gesamt-SO2 ist das Prinzip OIV-Referenzmethode (Typ II) [2].

**Grenzen:**

- **Rotwein, freie SO2:** Auch bei A-O zerfallen während des Austreibens schwache SO2-Anthocyan-Verbindungen. Die freie SO2 wird deshalb überschätzt [12, 23].
- **Temperatur:** Die freie SO2 nach A-O hängt stark von der Temperatur ab. Wärmerer Wein liefert höhere Werte [1].
- **Gesamt-SO2:** Beim Sieden können flüchtige Säuren, vor allem Essigsäure, in die Vorlage gelangen. Das ergibt zu hohe Werte, besonders bei Weinen mit viel flüchtiger Säure. Ein gut gekühlter Rückflusskühler hält das klein.
- **Technik:** Undichtigkeiten, zu schwacher oder zu starker Luftstrom, zu kurze Zeit und eine nicht neutral eingestellte Vorlage verfälschen das Ergebnis. Die OIV hat ihre Fassung 2021 in einem Ringversuch neu validiert (OIV-OENO 661-2021) [2].

## 5 Methode 3: Schnelltests

| Typ | Prinzip | Stärken | Grenzen |
|---|---|---|---|
| Teststreifen | Farbreaktion auf Sulfit, Ablesen an einer Farbskala | sehr schnell, billig | nur halbquantitativ in groben Stufen; Weinfarbe stört; für Dosierentscheidungen ungeeignet |
| Ampullen-Tests (z. B. Titrets) | Iodid-Iodat-Titration nach Ripper in einer Glasampulle, Stärke als Indikator | ohne Bürette, 2 Minuten | alle Störungen des Ripper (Kapitel 3.7); Ablesestufen; Rotwein-Endpunkt schwierig |
| Mini-Titratoren mit Elektrode | iodometrische oder iodatometrische Titration mit Redox-Endpunkt (Platinelektrode) | Endpunkt unabhängig von der Weinfarbe; gut reproduzierbar | chemische Störungen des Ripper bleiben (Ascorbinsäure, Phenole); Elektrodenpflege; Gerätekosten |
| Fotometer-Kits | Farbreaktion, z. B. mit Pararosanilin oder DTNB, bzw. Enzym-Kits | mit Fotometer gut reproduzierbar; automatisierte fotometrische Verfahren wurden gegen Referenzverfahren validiert [24] | Reagenzkosten; Rotwein braucht oft Probenleerwert; Fotometer nötig, siehe [Fotometrie und Enzymatik](fotometrie-enzymatik.md) |
| A-O-Komplettsätze | wie Kapitel 4 | Referenzprinzip | Aufbauzeit, Platzbedarf |

Die Produktbeschreibungen in der Tabelle folgen Herstellerangaben und wurden nicht online geprüft. Markennamen sind Beispiele, keine Empfehlung.

Zum Prinzip der Elektroden-Titratoren: Eine Platinelektrode misst das Redoxpotential. Sobald Iod im Überschuss vorliegt, steigt das Potential sprunghaft. Diesen Sprung erkennt das Gerät als Endpunkt.

**Einordnung:**

- Teststreifen eignen sich, um festzustellen, ob überhaupt nennenswert freie SO2 vorhanden ist. Mehr nicht.
- Ampullen und Elektroden-Titratoren liefern bei Weißwein brauchbare Routinewerte. Ihre Genauigkeit ist aber nicht besser als die der Ripper-Methode, deren Prinzip sie nutzen [8].
- Die Genauigkeitsangaben der Hersteller beziehen sich meist auf Standardlösungen, nicht auf Wein. Für die einzelnen Produkte wurde keine unabhängige Validierung an Wein gefunden.
- Jeden Schnelltest einführen, indem man dieselben Weine parallel mit A-O oder im Labor misst.

Eine Forschungsmethode misst die tatsächlich molekulare SO2 direkt im Kopfraum über dem Wein mit handelsüblichen Gasprüfröhrchen, ohne das Gleichgewicht zu stören [23]. Für die Routine im Kleinbetrieb ist sie bisher nicht etabliert.

## 6 SO2-Zugabe berechnen

### 6.1 Kaliumdisulfit (Kaliummetabisulfit, K2S2O5)

Kaliumdisulfit setzt in Wasser bzw. Wein Hydrogensulfit frei (K2S2O5 + H2O → 2 KHSO3). Ein Formelumsatz liefert 2 SO2:

```
M(K2S2O5) = 222,31 g/mol      M(SO2) = 64,06 g/mol
SO2-Anteil = 2 × 64,06 / 222,31 = 0,576  →  57,6 %
```

- 1 g Kaliumdisulfit liefert theoretisch 0,576 g SO2.
- Für 1 g SO2 braucht man theoretisch 1,735 g Kaliumdisulfit.
- 1 g Kaliumdisulfit je 100 L ergibt theoretisch 5,8 mg/L SO2. 10 g/hL ergeben 57,6 mg/L.

In der Praxis wird häufig mit 50 % gerechnet. Gründe: nicht vollständige Reinheit, Oxidation zu Sulfat bei feuchter oder offener Lagerung, Verluste beim Lösen und Einmischen.

> **Offen:** Für den Praxisfaktor 50 % wurde keine Primärquelle gefunden. Er ist eine verbreitete Faustregel. Besser ist es, nach jeder Zugabe nachzumessen und den betriebseigenen Faktor zu ermitteln.

**Handhabung:** Kaliumdisulfit in wenig Wasser oder Wein lösen (etwa 10 %, also 100 g/L). Langsam unter gutem Mischen zugeben, zum Beispiel beim Umpumpen oder mit Rührwerk. Örtliche Überdosierung vermeiden. Eine Lösung mit 100 g/L Kaliumdisulfit enthält theoretisch 57,6 g/L SO2. Sie verliert mit der Zeit SO2; daher frisch ansetzen. Aufgedruckte SO2-Gehalte fertiger Brausetabletten gelten nur bei trockener und geschlossener Lagerung.

**Bio:** Schwefeldioxid und Kaliumdisulfit sind für Bio-Wein zugelassen, aber mit niedrigeren Höchstwerten (Kapitel 7.2) [26]. Verbandsrichtlinien können strenger sein.

### 6.2 SO2-Lösungen

Wässrige Lösungen von Schwefeldioxid werden mit 5 bis 6 % SO2 und mehr gehandelt. Wichtig ist, ob die Angabe in Massenprozent (g je 100 g) oder in g je 100 mL gemeint ist.

- Bei g/100 mL ist es einfach: 6 % = 60 g/L, also 60 mg SO2 je mL.
- Bei Massenprozent ist der Gehalt je Liter etwas höher, weil die Lösung schwerer ist als Wasser. Beispiel mit einer angenommenen Dichte von 1,03 g/mL: 6 % (m/m) ≈ 62 g/L.

**Bio:** Schwefeldioxid ist für Bio-Wein zugelassen, also auch als wässrige Lösung; es gelten die niedrigeren Bio-Höchstwerte (Kapitel 7.2) [26].

**Gehalt selbst prüfen:** SO2-Lösungen verlieren SO2 durch Ausgasen. 1,00 mL der Lösung im 1-L-Messkolben mit Wasser zur Marke auffüllen. Bei 6 % (60 g/L) entstehen 60 mg/L SO2. 50 mL davon nach Kapitel 3.4 titrieren. Der erwartete Verbrauch an Iodlösung 0,01 mol/L ist 60 / 12,81 = 4,68 mL. Tatsächlicher Gehalt (g/L) = Verbrauch × 12,81.

### 6.3 Schwefelschnitten

Beim Verbrennen von Schwefel entsteht SO2: S + O2 → SO2. 1 g Schwefel liefert theoretisch 2,0 g SO2. Schwefelschnitten dienen zum Einbrennen leerer Holzfässer (Konservierung) und nicht zum Dosieren von Wein. Welcher Teil des SO2 im Fass bleibt und später in den Wein gelangt, ist nicht genau bestimmbar. Nach dem Befüllen eines eingebrannten Fasses daher die freie SO2 messen.

**Bio:** Schwefelschnitten setzen Schwefeldioxid frei. Nach Kenntnisstand ist das als Schwefelung zulässig. Ob die Bio-Vorschriften die Schnitten ausdrücklich nennen, wurde nicht geprüft. Mit der Kontrollstelle abklären, auch wegen strengerer Verbandsregeln.

> **Achtung:** Beim Einbrennen entsteht SO2-Gas in hoher Konzentration. Nicht in schlecht belüfteten Räumen arbeiten und nicht über die Fassöffnung beugen.

### 6.4 Verluste und Bindung neuer SO2

Nicht jede zugegebene SO2 bleibt frei:

- **Bindung:** Ein Teil der zugegebenen SO2 bindet sich an noch freie Carbonylverbindungen, vor allem an freien Acetaldehyd. Am stärksten ist das bei der ersten Schwefelung nach der Gärung. Bei einem schon geschwefelten, stabilen Wein bleibt der größte Teil einer Nachschwefelung frei [14].
- **Oxidation:** Je mg/L aufgenommenem Sauerstoff gehen bis zu 4 mg/L SO2 verloren (Kapitel 1.4).
- **Ausgasen:** beim Einmischen, Umpumpen, Filtrieren und in teilgefüllten Gebinden.

Wie groß der gebundene Anteil einer Zugabe ist, hängt vom Wein ab. Allgemeingültige Prozentwerte gibt es nicht. Vorgehen in der Praxis:

1. Zielwert festlegen (Tabelle in 1.5, pH messen).
2. Zugabe berechnen. Beim ersten Mal einen Zuschlag für die Bindung schätzen.
3. Nach 1 bis 2 Tagen messen und den Rest nachdosieren.
4. Aus Soll und Ist den Bindungsanteil für diesen Wein notieren. Er hilft bei der nächsten Zugabe.

### 6.5 Rechenbeispiel: Tank 1500 L von 18 auf 35 mg/L freie SO2

Ausgangslage: Weißwein, pH 3,40, freie SO2 18 mg/L (molekular 0,45 mg/L). Ziel 35 mg/L freie SO2 (molekular 0,88 mg/L, also über 0,8 mg/L).

**Schritt 1 – Bedarf ohne Bindung:**

- Erhöhung: 35 − 18 = 17 mg/L
- SO2-Menge: 17 mg/L × 1500 L = 25 500 mg = **25,5 g SO2**
- Kaliumdisulfit theoretisch: 25,5 g / 0,576 = **44,2 g**
- Kaliumdisulfit mit Praxisfaktor 50 %: 25,5 g / 0,50 = **51,0 g**

**Schritt 2 – Bindung berücksichtigen (angenommener Wert):** Angenommen, 30 % der Zugabe werden gebunden. Dieser Anteil ist eine Annahme für das Beispiel und muss im Betrieb ermittelt werden. Dann muss man 17 / 0,70 = 24,3 mg/L zugeben:

- SO2-Menge: 24,3 mg/L × 1500 L = **36,4 g SO2**
- Kaliumdisulfit theoretisch (57,6 %): 36,4 / 0,576 = **63,2 g**; mit Praxisfaktor 50 %: **72,9 g**
- als SO2-Lösung 6 % (60 g/L): 36,4 / 60 = 0,607 L = **607 mL**
- als Kaliumdisulfit-Lösung 100 g/L (57,6 g/L SO2): 36,4 / 57,6 = 0,632 L = **632 mL**

Zum Vergleich bei anderen Bindungsanteilen (Kaliumdisulfit, theoretisch 57,6 %): 20 % → 55,3 g; 40 % → 73,7 g.

**Schritt 3 – Grenzwert prüfen:** Die Gesamt-SO2 steigt um die gesamte zugegebene Menge, hier um etwa 24 mg/L. War die Gesamt-SO2 vorher 85 mg/L, liegt sie danach bei etwa 109 mg/L. Das ist unter den Höchstwerten (Kapitel 7), auch unter dem Bio-Wert für trockenen Weißwein (150 mg/L).

**Schritt 4 – Kontrolle:** Gut mischen. Nach 1 bis 2 Tagen freie und gesamte SO2 messen und bei Bedarf nachdosieren.

**Faustregel zum Überschlagen:** 1 g Kaliumdisulfit je 100 L Wein ergibt theoretisch knapp 6 mg/L SO2.

## 7 Auswertung: Höchstwerte und Kennzeichnung

Die ausführliche Übersicht mit Fundstellen steht in [Grenzwerte und Recht](grenzwerte-recht.md). Hier die SO2-Werte.

### 7.1 Höchstwerte für Gesamt-SO2 (EU)

Fundstelle: Delegierte Verordnung (EU) 2019/934, Anhang I Teil B, konsolidierte Fassung Stand 29.12.2024 [25]. Die Werte gelten zum Zeitpunkt des Inverkehrbringens zum unmittelbaren menschlichen Verbrauch. „Restzucker“ bedeutet hier die Summe aus Glucose und Fructose. Die Bio-Werte folgen aus der Regel in Kapitel 7.2.

| Erzeugnis | Restzucker | Höchstwert konventionell | Höchstwert Bio (EU) |
|---|---|---|---|
| Rotwein | unter 2 g/L | 150 mg/L | 100 mg/L |
| Rotwein | 2 bis unter 5 g/L | 150 mg/L | 120 mg/L |
| Rotwein | ab 5 g/L | 200 mg/L | 170 mg/L |
| Weißwein, Rosé | unter 2 g/L | 200 mg/L | 150 mg/L |
| Weißwein, Rosé | 2 bis unter 5 g/L | 200 mg/L | 170 mg/L |
| Weißwein, Rosé | ab 5 g/L | 250 mg/L | 220 mg/L |
| Spätlese (g. U.) | ab 5 g/L | 300 mg/L | 270 mg/L |
| Auslese (g. U.) | ab 5 g/L | 350 mg/L | 320 mg/L |
| Beerenauslese, Ausbruch, Trockenbeerenauslese, Strohwein, Schilfwein, Eiswein (g. U.) | ab 5 g/L | 400 mg/L | 370 mg/L |
| Qualitätsschaumwein | – | 185 mg/L | 155 mg/L |
| sonstiger Schaumwein | – | 235 mg/L | 205 mg/L |
| Likörwein | unter 5 g/L | 150 mg/L | 120 mg/L |
| Likörwein | ab 5 g/L | 200 mg/L | 170 mg/L |

(g. U. = geschützte Ursprungsbezeichnung)

Alle Zahlen sind gegen den konsolidierten Text geprüft [25]. Die Prädikatswerte stehen in Teil B Abschnitt A Nr. 2 Buchst. c bis e, also unter der Bedingung „Zuckergehalt von 5 g/L oder mehr“. Die Liste in Buchst. e nennt auch „Ausbruchwein“.

**Ausnahmen bei ungünstiger Witterung:** In Jahren, in denen die Witterung es ausnahmsweise erfordert, können die Mitgliedstaaten für Weine bestimmter Flächen zulassen, dass Höchstwerte unter 300 mg/L um höchstens 50 mg/L erhöht werden (Teil B Abschnitt A Nr. 4). Für Schaumweine ist eine Erhöhung um höchstens 40 mg/L möglich, wenn die Weine den Mitgliedstaat nicht verlassen (Abschnitt C Nr. 2). Die Mitgliedstaaten dürfen auch strengere Werte festlegen (Abschnitt A Nr. 5) [25].

Weitere Hinweise:

- Ein trockener Prädikatswein mit weniger als 5 g/L Restzucker fällt unter den normalen Wert für Weißwein bzw. Rotwein.
- Die Höchstwerte gelten für die Gesamt-SO2. Sie sind kein Zielwert. Hohe gebundene SO2 bei niedriger freier SO2 deutet auf viel Acetaldehyd oder Ketosäuren hin.
- Liegt der Ripper-Wert näher als etwa 20 mg/L am Höchstwert, die Gesamt-SO2 im Labor mit der Referenzmethode bestimmen lassen [3, 8].

### 7.2 Bio-Wein

Nach DVO (EU) 2021/1165, Anhang V Teil D, Eintrag Schwefeldioxid (konsolidiert Stand 01.01.2026) [26] gilt:

- Rotwein mit weniger als 2 g/L Restzucker: höchstens 100 mg/L (50 mg/L unter dem konventionellen Wert),
- Weißwein und Rosé mit weniger als 2 g/L Restzucker: höchstens 150 mg/L (50 mg/L unter dem konventionellen Wert),
- alle anderen Weine: konventioneller Höchstwert minus 30 mg/L.

Die Schwefelung als solche ist zugelassen (Schwefeldioxid, Kaliumbisulfit = Kaliumhydrogensulfit, Kaliummetabisulfit = Kaliumdisulfit) [26]. Verboten ist die Entschwefelung durch physikalische Verfahren (VO (EU) 2018/848, Anhang II Teil VI Nr. 3.2 Buchst. b) [26].

**Ausnahme im Katastrophenfall:** Erkennt der Mitgliedstaat förmlich einen Katastrophenfall an (z. B. widrige Witterung), kann die zuständige Behörde erlauben, dass Bio-Wein SO2 bis zum konventionellen Höchstwert enthält, wenn der Gesundheitszustand der Trauben im Vergleich zu früheren Jahren mehr SO2 erfordert. Die Ausnahme ist auf höchstens 12 Monate befristet (Delegierte VO (EU) 2020/2146, Art. 1, 2 und 3 Abs. 9, gestützt auf Art. 22 VO (EU) 2018/848) [31].

### 7.3 Strengere Verbandsrichtlinien

Bio-Verbände wie Bio Austria, Demeter, ECOVIN und Respekt-BIODYN setzen zum Teil niedrigere SO2-Höchstwerte fest als das EU-Bio-Recht.

> **Offen:** Die aktuellen Verbandswerte konnten in dieser Runde nicht belegt werden. Sie stehen in der jeweils gültigen Richtlinie des Verbands. Mitglieder sollten die Werte dort nachlesen und hier ergänzen.

### 7.4 Allergenkennzeichnung „Enthält Sulfite“

Schwefeldioxid und Sulfite sind ab einer Konzentration von **mehr als 10 mg/L** (gerechnet als SO2) als Allergen anzugeben [27]. Bei Wein geschieht das mit „Enthält Sulfite“ bzw. „Sulfite“ oder „Schwefeldioxid“ [28].

Hefen bilden bei der Gärung selbst SO2 [14]. Auch ein Wein ohne zugesetzte SO2 kann deshalb über 10 mg/L liegen und muss dann gekennzeichnet werden. Wer auf die Angabe verzichten will, braucht einen Laborbefund. Die Ripper-Methode ist im Bereich um 10 mg/L dafür zu ungenau.

## 8 Fehlerquellen und Qualitätssicherung

| Fehler | Folge | Abhilfe |
|---|---|---|
| Probe mit Luftkontakt oder zu lange gelagert | freie SO2 zu niedrig | volle, verschlossene Flasche; am selben Tag messen |
| Probe zu warm oder zu kalt | freie SO2 verschoben (bei A-O deutlich) [1] | auf etwa 20 °C temperieren |
| Iod- oder Natronlauge-Titer nicht bekannt | systematischer Fehler | Titer regelmäßig prüfen |
| langsame Ripper-Titration | freie SO2 zu niedrig (Oxidation) oder zu hoch (Nachlieferung aus Bindungen) | zügig, Endpunkt 10–15 s [3] |
| Ascorbinsäure im Wein (Ripper) | stark zu hohe Werte | A-O verwenden |
| Rotwein mit Ripper | Endpunkt unsicher, Phenole stören | A-O oder Elektroden-Endpunkt |
| A-O: Leck, falscher Durchfluss, zu kurze Zeit | zu niedrig | Dichtheit prüfen, Durchflussmesser, Zeit einhalten |
| A-O gesamt: flüchtige Säure | zu hoch | Kühler gut kühlen |
| pH-Messung ungenau | falsche molekulare SO2 | pH-Meter täglich kalibrieren |

**Qualitätssicherung im Kleinbetrieb:**

- Jede Messung als Doppelbestimmung machen.
- Ergebnisse mit Datum, Methode, Titer und Analysierender oder Analysierendem in ein Laborbuch eintragen.
- Ein- bis zweimal im Jahr Vergleichsproben an ein Labor geben, je eine Weiß- und eine Rotweinprobe.
- Bei regelmäßigen Abweichungen von mehr als etwa 5 mg/L (frei) bzw. 10 mg/L (gesamt) die Ursache suchen: Titer, Blindwert, Endpunkt, Temperatur. Diese Schwellen sind eine Empfehlung des Verfassers, keine Norm.

## 9 Sicherheit und Entsorgung

| Stoff | Gefahr (GHS) | Schutzmaßnahmen |
|---|---|---|
| Schwefeldioxid (Gas, verflüssigt) | giftig beim Einatmen, ätzend; Druckgas (GHS04, GHS05, GHS06) | nur mit Ausbildung und Gaswarngerät; Atemschutz mit Filter Typ E |
| Kaliumdisulfit | gesundheitsschädlich beim Verschlucken, schwere Augenschäden; setzt mit Säure giftiges Gas frei (EUH031) (GHS05, GHS07) | Schutzbrille; nie trocken mit Säuren (z. B. Zitronensäure) mischen; nicht im geschlossenen Eimer mit Säure ansetzen |
| Iodlösung 0,01 mol/L | je nach Hersteller kaum oder nicht eingestuft; färbt Haut und Kleidung (festes Iod: gesundheitsschädlich, reizend, Schilddrüse, umweltgefährlich) | Handschuhe, Sicherheitsdatenblatt beachten |
| Schwefelsäure ca. 25 % | verursacht schwere Verätzungen (GHS05) | Schutzbrille, Handschuhe; Säure ins Wasser |
| Phosphorsäure 85 % und ca. 25 % | ätzend (GHS05) | wie Schwefelsäure; heiße Säure spritzt |
| Natronlauge 1 mol/L | verursacht schwere Verätzungen, besonders der Augen (GHS05) | Schutzbrille; Natronlauge 0,01 mol/L ist nicht eingestuft |
| Wasserstoffperoxid 30 % | Augenschäden, gesundheitsschädlich (GHS05, GHS07) | besser 3 % aus der Apotheke kaufen; 0,3 % ist nicht eingestuft |
| Indikatorlösung (Ethanol) | entzündbar | von Flammen fernhalten |
| Propanal, Ethanal (Acetaldehyd) | leicht entzündbar, reizend; Ethanal zusätzlich Verdacht auf krebserzeugende Wirkung | nur kleine Mengen, gut lüften, kühl und verschlossen lagern |

> **Achtung:** SO2-Gas reizt schon in geringen Konzentrationen die Atemwege. Bei Menschen mit Asthma kann es Atemnot auslösen. Beim Schwefeln, beim Einbrennen von Fässern und beim Ansetzen von Kaliumdisulfit für gute Lüftung sorgen. Für Schwefeldioxid gelten in der EU Arbeitsplatzgrenzwerte von 0,5 ppm (8 Stunden) und 1 ppm (Kurzzeitwert) [30].

**Erste Hilfe:** Bei Augenkontakt sofort mindestens 10 Minuten unter fließendem Wasser spülen und ärztliche Hilfe holen. Nach Einatmen von SO2 an die frische Luft gehen; bei Atemnot Rettung unter 144 rufen. Bei Verschlucken von Chemikalien: Vergiftungsinformationszentrale (VIZ), Telefon 01 406 43 43. Eine Augendusche gehört an jeden Laborplatz.

**Entsorgung:**

- Titrationsreste der Ripper-Methode: Restiod mit einigen Tropfen Natriumthiosulfatlösung entfärben. Mit Natriumhydrogencarbonat (Natron) neutralisieren.
- A-O-Reste: Kolbeninhalt (Wein mit Phosphorsäure) und Vorlage neutralisieren.
- In Laborkleinmengen können neutralisierte, verdünnte Lösungen mit viel Wasser ins Abwasser, wenn die örtliche Kanalordnung das zulässt.
- Konzentrate (Säuren, Laugen, Iod-Stammlösung, Aldehyde, Reste von Kaliumdisulfit) im Altstoffsammelzentrum bzw. bei der Problemstoffsammlung der Gemeinde abgeben.

## 10 Einkaufsliste in Kürze

| Ausstattung | Ripper | A-O |
|---|---|---|
| Bürette 10 mL mit Stativ | ✔ | ✔ |
| Vollpipetten 10, 20, 25, 50 mL, Pipettierhilfe | ✔ (25, 50) | ✔ (10, 20, 50) |
| Erlenmeyerkolben 250 mL | ✔ | – |
| A-O-Glassatz (Rundkolben, Einleitrohr, Kühler, Vorlage), Klemmen, Stativ | – | ✔ |
| Vakuumquelle, Durchflussmesser mit Nadelventil, Schläuche | – | ✔ |
| Heizpilz oder kleiner Brenner, Siedesteinchen | – | ✔ (gesamt) |
| Iodlösung 0,01 mol/L oder Iodid-Iodat-Lösung | ✔ | – |
| Schwefelsäure ca. 25 % | ✔ | – |
| Natronlauge 1 mol/L | ✔ (gesamt) | – |
| Stärkelösung, EDTA-Dinatriumsalz | ✔ | – |
| Phosphorsäure 85 % oder ca. 25 % | – | ✔ |
| Wasserstoffperoxid 3 % (Apotheke) | – | ✔ |
| Mischindikator Methylrot/Methylenblau (Tashiro) | – | ✔ |
| Natronlauge 0,01 mol/L | – | ✔ |
| Propanal (für Blindwert), Natriumthiosulfat 0,1 mol/L (Titerkontrolle) | optional | – |
| Schutzbrille, Nitrilhandschuhe, Augendusche | ✔ | ✔ |

Preise und Bezugsquellen: siehe [Einkaufsliste](einkaufsliste.md).

Stand: November 2026

## Quellen

1. OIV (2018): Free sulphur dioxide. Methode OIV-MA-AS323-04A1 (Resolution OIV-OENO 591A-2018). In: Compendium of International Methods of Wine and Must Analysis. Internationale Organisation für Rebe und Wein. https://www.oiv.int/node/2088 – ältere Gesamtfassung: https://www.oiv.int/public/medias/2581/oiv-ma-as323-04a.pdf [online geprüft]
2. OIV (2018): Total sulphur dioxide. Methode OIV-MA-AS323-04A2 (Resolution OIV-OENO 591B-2018), Typ II; Validierung: Resolution OIV-OENO 661-2021. https://www.oiv.int/node/2089 und https://www.oiv.int/public/medias/6438/oiv-oeno-591b-2018-en.pdf [online geprüft]
3. OIV (2009): Sulfur dioxide (Iodometry). Methode OIV-MA-AS323-04B (A17, revidiert durch OIV/OENO 377/2009), Typ IV. https://www.oiv.int/node/2090 und https://www.oiv.int/public/medias/2582/oiv-ma-as323-04b.pdf [online geprüft – Reagenzien, Volumina, Faktoren und Anmerkungen zu Blindwert, Rotwein und Grenzwertnähe gesehen]
4. OIV (2009): Sulfur dioxide (molecular method). Methode OIV-MA-AS323-04C, Typ IV. https://www.oiv.int/node/2091 und https://www.oiv.int/public/medias/2583/oiv-ma-as323-04c.pdf [online geprüft – Tabellen nur auszugsweise gesehen]
5. AWRI (o. J.): Measurement of sulfur dioxide in wine. Australian Wine Research Institute, Adelaide. https://www.awri.com.au/industry_support/winemaking_resources/laboratory_methods/chemical/so2/ [online geprüft]
6. AWRI (o. J.): Hinweise zu Zielwerten für molekulare SO2 und zum SO2-Rechner (Seiten „Revisiting sulfur dioxide use“ und Rechnerhinweise). https://www.awri.com.au/industry_support/winemaking_resources/fining-stabilities/microbiological/avoidance/sulfur_dioxide/ und https://www.awri.com.au/s1886 [online geprüft]
7. Rankine, B. C., Pocock, K. F. (1970): Alkalimetric determination of sulphur dioxide in wine. Australian Wine, Brewing and Spirit Review 88 (8), 40, 42, 44. [online geprüft – Zitat auf der AWRI-Seite [5] gesehen, Original nicht]
8. Vahl, J. M., Converse, J. E. (1980): Ripper procedure for determining sulfur dioxide in wine: collaborative study. Journal of the Association of Official Analytical Chemists 63 (2), 194–199. DOI 10.1093/jaoac/63.2.194 [online geprüft]
9. TTB – Alcohol and Tobacco Tax and Trade Bureau (2016): Total Sulfur Dioxide by Aeration-Oxidation. Methode SSD:TM:500, Rev. 6. https://www.ttb.gov/images/pdfs/ssd/tm500.pdf [online geprüft]
10. Usseglio-Tomasset, L., Bosia, P. D. (1984): La prima costante di dissociazione dell'acido solforoso. Vini d'Italia 26, 7–14. [nicht online geprüft – Zitat in Sekundärquellen gesehen]
11. Margalit, Y. (1997): Concepts in Wine Chemistry. Wine Appreciation Guild, San Francisco. [nicht online geprüft – zitiert nach AWRI [6]]
12. Howe, P. A., Worobo, R., Sacks, G. L. (2018): Conventional measurements of sulfur dioxide (SO2) in red wine overestimate SO2 antimicrobial activity. American Journal of Enology and Viticulture. https://www.researchgate.net/publication/323478430 [online geprüft – Titel und Kernaussage; Autorenangabe aus Fachwissen]
13. Purdue University Extension (o. J.): Use of SO2 in High-pH Wines. Publikation FS-52-W. https://www.extension.purdue.edu/extmedia/fs/fs-52-w.pdf [online geprüft]
14. Ribéreau-Gayon, P., Dubourdieu, D., Donèche, B., Lonvaud, A. (2006): Handbook of Enology. Volume 1: The Microbiology of Wine and Vinifications. 2. Auflage. Wiley, Chichester. Kapitel 8 (Schwefeldioxid). [nicht online geprüft]
15. Boulton, R. B., Singleton, V. L., Bisson, L. F., Kunkee, R. E. (1996): Principles and Practices of Winemaking. Chapman & Hall, New York. [nicht online geprüft]
16. Zoecklein, B. W., Fugelsang, K. C., Gump, B. H., Nury, F. S. (1995): Wine Analysis and Production. Chapman & Hall, New York. [nicht online geprüft]
17. Iland, P., Bruer, N., Edwards, G., Weeks, S., Wilkes, E. (2004): Chemical Analysis of Grapes and Wine: Techniques and Concepts. Patrick Iland Wine Promotions, Adelaide. [nicht online geprüft]
18. Waterhouse, A. L., Sacks, G. L., Jeffery, D. W. (2016): Understanding Wine Chemistry. Wiley, Chichester. [nicht online geprüft]
19. Burroughs, L. F., Sparks, A. H. (1973): Sulphite-binding power of wines and ciders. I. Equilibrium constants for the dissociation of carbonyl bisulphite compounds. Journal of the Science of Food and Agriculture 24. [nicht online geprüft]
20. Beech, F. W., Burroughs, L. F., Timberlake, C. F., Whiting, G. C. (1979): Progrès récents sur l'aspect chimique et l'action antimicrobienne de l'anhydride sulfureux (SO2). Bulletin de l'OIV 52. [nicht online geprüft]
21. Danilewicz, J. C., Seccombe, J. T., Whelan, J. (2008): Mechanism of interaction of polyphenols, oxygen, and sulfur dioxide in model wine and wine. American Journal of Enology and Viticulture 59. [nicht online geprüft]
22. Iowa State University Extension and Outreach (o. J.): Publikation 16425 (Weinbereitung; Aussage zu 0,5–0,8 mg/L molekularer SO2 für Rot- und Weißwein). https://store.extension.iastate.edu/Product/16425-pdf [online geprüft – Aussage gesehen, Titel nicht erfasst]
23. Howe, P. A. (2015): Dissertation zur Kopfraum-Messung von SO2 mit Gasprüfröhrchen, Cornell University, Ithaca. https://ecommons.cornell.edu/entities/publication/7a66a7bb-69ee-4c57-ac81-0d23e6c83458 [online geprüft – Zusammenfassung gesehen, genauer Titel nicht erfasst]
24. N. N. (2024): Validation of a fast automated photometric method for the analysis of sulfur dioxide in wines. European Food Research and Technology. DOI 10.1007/s00217-024-04496-x [online geprüft – nur Titel und Fundstelle; Autorinnen und Autoren vor Verwendung ergänzen]
25. Delegierte Verordnung (EU) 2019/934 der Kommission zur Ergänzung der Verordnung (EU) Nr. 1308/2013 hinsichtlich der Anbaugebiete, in denen der Alkoholgehalt erhöht werden darf, der zugelassenen önologischen Verfahren und der Einschränkungen für die Erzeugung und Haltbarmachung von Weinbauerzeugnissen …, Anhang I Teil B. Konsolidierte Fassung auf EUR-Lex, Stand 29.12.2024. https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:02019R0934-20241229 [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 29.12.2024: Teil B Abschnitte A–C, alle Werte der Tabelle 7.1]
26. Verordnung (EU) 2018/848 über die ökologische/biologische Produktion, Anhang II Teil VI, und Durchführungsverordnung (EU) 2021/1165, Anhang V Teil D. Konsolidierte Fassungen auf EUR-Lex, Stand 25.03.2025 bzw. 01.01.2026. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex: SO2-Bedingungen in 2021/1165 Anhang V Teil D, Verbot der Entschwefelung in 2018/848 Anhang II Teil VI Nr. 3.2]
27. Verordnung (EU) Nr. 1169/2011 betreffend die Information der Verbraucher über Lebensmittel, Anhang II Nr. 12. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 01.04.2025: Anhang II Nr. 12 (mehr als 10 mg/L als insgesamt vorhandenes SO2) und Anhang XIV (Umrechnungsfaktoren)]
28. Delegierte Verordnung (EU) 2019/33 der Kommission (Kennzeichnung von Weinbauerzeugnissen), Art. 41 und Anhang I Teil A (Allergenbegriffe). Konsolidierte Fassung EUR-Lex, Stand 18.01.2025. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 18.01.2025: Art. 41; die Begriffsliste in Anhang I Teil A nicht einzeln gelesen]
29. Jackowetz, J. N., Mira de Orduña, R. (2013): Survey of SO2 binding carbonyls in 237 red and white table wines. Food Control 32. [nicht online geprüft]
30. Richtlinie (EU) 2017/164 der Kommission zur Festlegung einer vierten Liste von Arbeitsplatz-Richtgrenzwerten (Schwefeldioxid); in Österreich umgesetzt in der Grenzwerteverordnung (GKV) in der geltenden Fassung. [nicht online geprüft]

Weiterführend (nicht im Text zitiert): OIV (2021): OIV Collective Expertise Document – SO2 and wine: a review. https://www.oiv.int/public/medias/7840/oiv-collective-expertise-document-so2-and-wine-a-review.pdf [online geprüft – nur Existenz und Inhaltsverzeichnis gesehen]
31. Delegierte Verordnung (EU) 2020/2146 der Kommission vom 24. September 2020 bezüglich Ausnahmen von den Produktionsvorschriften für die ökologische/biologische Produktion. ABl. L 428 vom 18.12.2020, S. 5. https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32020R2146 [online geprüft – Originaltext EUR-Lex: Art. 1, 2, 3 Abs. 9]
32. Europäische Kommission (2010): Liste und Beschreibung der Analysemethoden gemäß Artikel 120g Absatz 1 der Verordnung (EG) Nr. 1234/2007, Kapitel 24 „Schwefeldioxid (OIV-AS-323-04-DIOSU)“. Amtsblatt der EU C 43 vom 19.2.2010, S. 58–60. https://eur-lex.europa.eu/legal-content/DE/TXT/PDF/?uri=OJ:C:2010:043:FULL [online geprüft – Wortlaut: Gasstrom etwa 40 L/h, 15 Minuten, 50 mL Probe + 15 mL Phosphorsäure 85 %, Berechnung 6,4 n bzw. 16 n]
