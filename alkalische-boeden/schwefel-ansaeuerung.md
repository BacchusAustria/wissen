# Ansäuern alkalischer Böden: Schwefel, Gips und andere „saure“ Mittel

Lässt sich ein alkalischer Weingartenboden (pH über 7,5) mit Mitteln, die im biologischen Landbau zugelassen sind, ansäuern? Und bringt das mehr Phosphor, Eisen, Zink und Mangan für die Rebe? Diese Datei rechnet es durch, sammelt die Belege und gibt eine Anleitung für einen eigenen Versuch.

> **Offen:** Die Datei entstand mit sehr wenigen Online-Suchen. Quellen, die bei der Erstellung online gesehen wurden, tragen den Vermerk [online geprüft], alle anderen [nicht online geprüft]. Zahlen aus der Literatur, die nicht gegen die Originalquelle geprüft werden konnten, sind mit „(ungeprüft)“ markiert. Werte mit dem Zusatz „eigene Rechnung“ sind stöchiometrisch mit python3 nachgerechnet und hängen nicht von der Literatur ab.

## Kurzfassung

- **Nur elementarer Schwefel säuert nennenswert an.** Bodenmikroorganismen oxidieren ihn zu Schwefelsäure. 1 kg Schwefel liefert 62 mol Säure, löst 3,1 kg Kalk und bildet 5,4 kg Gips (eigene Rechnung). Elementarer Schwefel ist als Dünger im Bio-Landbau zugelassen [1].
- **Bei freiem Kalk ist eine flächige pH-Senkung praktisch unmöglich.** 1 % Kalk in 0–30 cm sind rund 42 t CaCO₃ je ha. Um sie aufzulösen, bräuchte man rund 13 t Schwefel je ha, bei 20 % Kalk rund 270 t (eigene Rechnung). Übliche Schwefelmengen von 20–60 kg/ha und Jahr verschwinden darin.
- **Realistisch sind nur saure Mikrozonen:** Schwefel örtlich konzentriert (Unterstockband, Pflanzloch), am besten mit Kompost gemischt. Labor-, Gefäß- und einzelne Feldversuche auf Kalkböden zeigen mehr lösliches Phosphat, Eisen, Mangan und Zink [2–4]. Versuche in Weingärten Mitteleuropas fehlen. Deshalb nur als eigener Streifenversuch.
- **Kalkfreie, aber alkalische Böden** sind die Ausnahme. Dort senkt Schwefel den pH-Wert wirklich, schon kleine Mengen reichen, und Überdosierung ist die größere Gefahr.
- **Gips senkt den pH-Wert kalkhaltiger Böden nicht.** Er hilft bei Natrium (Salzböden) und liefert Calcium und Schwefel [5, 6].
- **Trester, Nadelstreu, Torf, Kaffeesatz, Essig, Zitronensäure** taugen nicht zum Ansäuern: zu wenig Säure, schneller Abbau oder im Bio-Weingarten nicht zulässig.
- **Billigste wirksame Maßnahme:** kein hydrogencarbonatreiches Brunnenwasser in die Tropfbewässerung, wo Regenwasser verfügbar ist. 100 mm hartes Brunnenwasser bringen so viel Lauge in den Boden, wie 30–100 kg Schwefel ausgleichen könnten (eigene Rechnung).

## Hintergrund

### Warum der pH-Wert für die Nährstoffe zählt

Alkalische Böden enthalten meist freien Kalk (Calciumcarbonat, CaCO₃, teils Dolomit). Kalk und hoher pH-Wert legen mehrere Nährstoffe fest [7, 8]:

- **Phosphor (P):** Phosphat bildet mit Calcium schwer lösliche Calciumphosphate und wird an Kalkoberflächen gebunden. Je höher pH-Wert und Calciumgehalt, desto weniger Phosphat bleibt gelöst [8, 9].
- **Eisen (Fe):** Eisenoxide sind bei pH 7,5–8,5 kaum löslich. Bei Reben kommt die Kalkchlorose dazu: Hydrogencarbonat (HCO₃⁻) in der Bodenlösung stört Aufnahme und Verwertung des Eisens. Die Blätter vergilben, obwohl im Boden viel Eisen steckt [10, 11].
- **Zink (Zn) und Mangan (Mn):** Ihre Löslichkeit sinkt mit steigendem pH-Wert stark [7, 8].

Mehr dazu in [Grundlagen alkalischer Böden](grundlagen.md), [Phosphor](phosphor.md), [Eisen-Chlorose](eisen-chlorose.md) und [Weitere Nährstoffe](weitere-naehrstoffe.md).

### Warum kalkhaltige Böden ihren pH-Wert halten

Kalk ist ein Säurepuffer. Jede Säure, die in den Boden kommt, löst zuerst Kalk auf. Erst wenn der Kalk aufgebraucht ist, sinkt der pH-Wert deutlich. Die Bodenkunde nennt das den Carbonat-Pufferbereich (nach Ulrich etwa pH 8,6 bis 6,2) [12, 13].

Wo genau der pH-Wert eines kalkhaltigen Bodens liegt, bestimmt das Gleichgewicht zwischen Kalk, gelöstem Calcium und Kohlendioxid (CO₂) in der Bodenluft [8]:

CaCO₃ + 2 H⁺ ⇌ Ca²⁺ + CO₂ + H₂O

Mit der Gleichgewichtskonstante nach Lindsay ergibt sich (eigene Rechnung, gerundet):

| CO₂ in der Bodenluft | pH bei wenig gelöstem Calcium (Aktivität 0,001 mol/L) | pH bei viel gelöstem Calcium (Aktivität etwa 0,006 mol/L, wie bei Gipssättigung oder in der 0,01-M-CaCl₂-Messlösung) |
|---|---|---|
| 0,04 % (Außenluft, Labormessung) | 8,1 | 7,7 |
| 1 % (feuchter, belebter Boden) | 7,4 | 7,0 |
| 3 % (nasser, verdichteter Boden) | 7,1 | 6,7 |

Daraus folgen drei praktische Punkte:

1. Ein im Labor gemessener pH(CaCl₂) über etwa 7,3–7,5 zeigt fast immer freien Kalk an. Ist trotz so hohem pH-Wert kein Kalk nachweisbar, ist meist Natrium die Ursache (siehe Abschnitt Gips) [5, 13]. Messmethoden: [Kalkbestimmung](../boden/kalk.md) und [pH-Wert und Leitfähigkeit](../boden/ph-leitfaehigkeit.md).
2. Mehr CO₂ im Boden senkt den pH-Wert etwas, erhöht aber das Hydrogencarbonat in der Bodenlösung. Hydrogencarbonat ist der Hauptauslöser der Kalkchlorose. Deshalb ist Chlorose in nassen, kalten, verdichteten Böden im Frühjahr am stärksten [10, 11, 14]. Nicht der pH-Wert allein zählt, sondern die Chemie an der Wurzel.
3. Ein Mittel, das den pH-Wert „senkt“, muss den Kalk auflösen. Jede Rechnung beginnt deshalb mit dem Kalkgehalt.

## Prinzip: Wie Schwefel sauer wird

### Die Reaktionen

Elementarer Schwefel (S) ist selbst nicht sauer. Erst Mikroorganismen oxidieren ihn im Boden zu Schwefelsäure [15, 16]:

S + 1,5 O₂ + H₂O → H₂SO₄ → 2 H⁺ + SO₄²⁻

In kalkhaltigem Boden reagiert die Säure sofort mit dem Kalk. Es entstehen Gips und Kohlendioxid:

H₂SO₄ + CaCO₃ + H₂O → CaSO₄ · 2 H₂O (Gips) + CO₂

Je Kilogramm Schwefel (eigene Rechnung):

| Größe | Menge je kg S |
|---|---|
| gebildete Schwefelsäure | 3,06 kg H₂SO₄ |
| Säure (Protonen) | 62,4 mol H⁺ |
| aufgelöster Kalk | 3,12 kg CaCO₃ (umgekehrt 0,32 kg S je kg CaCO₃) |
| gebildeter Gips | 5,37 kg CaSO₄ · 2 H₂O |
| aus dem Kalk freigesetztes CO₂ | 1,37 kg |
| gebildetes Sulfat | 3,00 kg SO₄²⁻ |

Annahme: 1 mol Schwefel löst 1 mol Kalk (2 H⁺ je CaCO₃). Wird ein Teil des gelösten Kalks als Calciumhydrogencarbonat ausgewaschen, verbraucht dieser Teil nur 1 H⁺; der Schwefelbedarf kann rechnerisch bis auf die Hälfte sinken. An den Größenordnungen unten ändert das nichts. Dolomit (CaMg(CO₃)₂) puffert je kg fast gleich stark (1 kg Dolomit entspricht 1,09 kg CaCO₃, eigene Rechnung), löst sich aber langsamer.

### Wer den Schwefel oxidiert

- **Spezialisierte Schwefelbakterien**, die aus der Oxidation Energie gewinnen. Früher hießen alle „Thiobacillus“; heute gehören dazu unter anderem *Thiobacillus thioparus* (neutraler Bereich), *Halothiobacillus neapolitanus* und das säureliebende *Acidithiobacillus thiooxidans* (früher *Thiobacillus thiooxidans*) [15, 17].
- **Heterotrophe Bakterien und Pilze**, die Schwefel nebenbei oxidieren. In landwirtschaftlichen Böden tragen sie oft einen großen Teil bei [15, 16].

In Kalkböden bleibt der Großteil des Bodens neutral bis alkalisch. Säureliebende Arten arbeiten dort nur in sauren Mikrozonen direkt an den Schwefelkörnern. Böden ohne Schwefel-Vorgeschichte oxidieren anfangs langsamer, weil sich die Oxidierer erst vermehren müssen [15, 18]. Weingärten, die seit Jahrzehnten Netzschwefel bekommen, dürften gut besiedelt sein. Eine Impfung mit „Thiobacillus“-Präparaten ist dort vermutlich überflüssig (Schlussfolgerung, im Weingarten nicht geprüft).

### Was die Geschwindigkeit bestimmt

| Einflussgröße | Wirkung | Praxisfolge | Quelle |
|---|---|---|---|
| Korngröße, Oberfläche | Die Oxidation läuft an der Kornoberfläche. Feiner Schwefel oxidiert viel schneller als grober. | Feines Pulver oder zerfallende Pastillen verwenden; grobe Körner wirken erst über Jahre. | [19–21] |
| Bodentemperatur | Im kalten Boden sehr langsam, im warmen Boden schnell. | Ausbringen, wenn der Boden noch einige Wochen warm und feucht bleibt. | [15, 22] |
| Bodenfeuchte | Am schnellsten bei mittlerer Feuchte (um Feldkapazität). Trockenheit stoppt, Staunässe (Sauerstoffmangel) bremst. | Nicht vor langen Trockenphasen ausbringen. | [15, 22] |
| Kontakt mit dem Boden | Schwefel an der Oberfläche oder als Klumpen oxidiert langsamer. | Flach einarbeiten (2–5 cm) oder mit Boden bzw. Kompost mischen. | [19, 21] |
| Organische Substanz | Fördert die Oxidation, vermutlich über mehr Aktivität heterotropher Mikroorganismen. | Mit Kompost kombinieren. | [23] |
| Vorgeschichte | Verzögerung in Böden ohne frühere Schwefelgaben. | In Weingärten mit Netzschwefel meist kein Problem. | [15, 18] |

> **Offen:** Konkrete Oxidationsraten werden bewusst nicht genannt. Sie hängen stark von Temperatur und Feuchte ab und sind aus den Originalarbeiten [15, 19, 21] zu übernehmen. Grobe Orientierung (ungeprüft): feines Pulver unter günstigen Bedingungen Wochen bis wenige Monate, Pastillen und grobe Körner Monate bis Jahre. In kalten Frühjahrsböden ändert eine Gabe zur Pflanzung den pH-Wert bis zum Bedarf der Jungpflanzen oft noch kaum.

## Rechenteil: Wie viel Schwefel bräuchte man?

Alle Zahlen dieses Abschnitts sind eigene Rechnungen. Sie gelten für den Feinboden. Ein hoher Steinanteil (Skelett) verringert die Bodenmasse entsprechend.

### Schritt 1: Bodenmasse je Hektar

Bodenmasse (t/ha) = 10.000 m² × Schichttiefe (m) × Lagerungsdichte (t/m³)

Die Lagerungsdichte (LD) ist die Masse trockenen Bodens je Volumen. 1,3–1,5 g/cm³ sind für Lehm- und Lössböden üblich (ungeprüft) [13].

| Schicht | LD 1,3 g/cm³ | LD 1,4 g/cm³ | LD 1,5 g/cm³ |
|---|---|---|---|
| 0–5 cm | 650 t | 700 t | 750 t |
| 0–10 cm | 1.300 t | 1.400 t | 1.500 t |
| 0–20 cm | 2.600 t | 2.800 t | 3.000 t |
| 0–30 cm | 3.900 t | 4.200 t | 4.500 t |

### Schritt 2 und 3: Kalkvorrat und Schwefelbedarf

Kalkvorrat (t CaCO₃/ha) = Bodenmasse × Carbonatgehalt (%) ÷ 100
Schwefelbedarf (t S/ha) = Kalkvorrat × 0,32

| Carbonat | 0–20 cm, LD 1,3 | 0–20 cm, LD 1,5 | 0–30 cm, LD 1,3 | 0–30 cm, LD 1,5 |
|---|---|---|---|---|
| 0,5 % | 13 t CaCO₃ → 4,2 t S | 15 t → 4,8 t S | 19,5 t → 6,2 t S | 22,5 t → 7,2 t S |
| 1 % | 26 t → 8,3 t S | 30 t → 9,6 t S | 39 t → 12,5 t S | 45 t → 14,4 t S |
| 5 % | 130 t → 41,6 t S | 150 t → 48,0 t S | 195 t → 62,5 t S | 225 t → 72,1 t S |
| 20 % | 520 t → 167 t S | 600 t → 192 t S | 780 t → 250 t S | 900 t → 288 t S |

Nebenprodukte bei LD 1,4 in 0–30 cm (eigene Rechnung):

| Carbonat | Schwefel | entstehender Gips | freigesetztes CO₂ | Schwefelkosten bei angenommenen 1 €/kg S |
|---|---|---|---|---|
| 0,1 % | 1,3 t | 7 t | 1,8 t | rund 1.300 € |
| 0,5 % | 6,7 t | 36 t | 9 t | rund 6.700 € |
| 1 % | 13,5 t | 72 t | 18 t | rund 13.500 € |
| 5 % | 67 t | 361 t | 92 t | rund 67.000 € |
| 20 % | 269 t | 1.445 t | 369 t | rund 269.000 € |

**Durchgerechnetes Beispiel:** Ein Lössboden mit 12 % Carbonat, 0–30 cm, LD 1,4 g/cm³:

1. Bodenmasse: 10.000 m² × 0,30 m × 1,4 t/m³ = 4.200 t
2. Kalkvorrat: 4.200 t × 12 ÷ 100 = 504 t CaCO₃
3. Schwefelbedarf: 504 t × 0,32 = 161 t S
4. Folgen: 867 t Gips im Boden, 222 t CO₂, Schwefelkosten von rund 160.000 € je ha.

Das ist offensichtlich unmöglich. Zum Vergleich: Für einen Boden mit 2,5 % Kalk (als Calciumcarbonat-Äquivalent) wird in US-amerikanischen Beratungsunterlagen ein Bedarf von etwa 16.000 lb/acre (rund 18 t S/ha) im Oberboden genannt und als unpraktikabel und zu teuer bewertet (Zuordnung laut Suchzusammenfassung, im Original prüfen) [4]. Das passt zur eigenen Rechnung.

### Schritt 4: Vergleich mit üblichen Schwefelmengen

Bezug: 1 % Kalk in 0–30 cm bei LD 1,4 (42 t CaCO₃ ≙ 13,5 t S je ha).

| Anwendung | kg S/ha und Jahr | aufgelöster Anteil des Kalkvorrats je Jahr | Jahre bis zur Neutralisation |
|---|---|---|---|
| Schwefeldüngung als Nährstoff | 20–40 (Annahme) | 0,15–0,30 % | 340–670 |
| Netzschwefel aus dem Pflanzenschutz | 10–60 (Schätzung, siehe unten) | 0,07–0,45 % | 220–1.350 |
| sehr hohe Ansäuerungsgabe | 200–500 (Annahme) | 1,5–3,7 % | 27–67 |

> **Fazit des Rechenteils:** Auf Böden mit freiem Kalk lässt sich der pH-Wert der ganzen Fläche mit Schwefel nicht senken. Schon „fast kalkfreie“ Böden mit 0,1–0,5 % Carbonat binden 1–7 t Schwefel je ha. Eine flächige Ansäuerung ist nur auf praktisch kalkfreien Böden realistisch. Das bestätigen auch Beratungsunterlagen aus kalkreichen Gebieten der USA [4, 24].

### Kalkfreie, aber alkalische Böden

Ohne Kalk puffern nur Tonminerale, Humus und austauschbare Kationen. Die Pufferkapazität gibt an, wie viel Säure den pH-Wert um eine Einheit senkt. Sie liegt grob zwischen 5 mmol H⁺ je kg Boden (Sand, humusarm) und 30 mmol H⁺ je kg (Ton, humusreich) je pH-Einheit (Annahme, Größenordnung; im Einzelfall mit dem Inkubationstest unten bestimmen).

Schwefel je pH-Einheit Senkung (eigene Rechnung, LD 1,4):

| Bodenvolumen | Puffer 5 mmol/kg | Puffer 15 mmol/kg | Puffer 30 mmol/kg |
|---|---|---|---|
| ganze Fläche 0–10 cm | 110 kg S/ha | 340 kg S/ha | 670 kg S/ha |
| ganze Fläche 0–20 cm | 220 kg S/ha | 670 kg S/ha | 1.350 kg S/ha |
| ganze Fläche 0–30 cm | 340 kg S/ha | 1.010 kg S/ha | 2.020 kg S/ha |
| Unterstockband 0,5 m breit, 0–10 cm, Reihenabstand 2,5 m | 22 kg S/ha | 67 kg S/ha | 135 kg S/ha |

Diese Mengen gelten nur bei völliger Kalkfreiheit. Schon 0,1 % Carbonat in 0–20 cm binden rund 0,9 t S/ha – mehr als die Pufferung eines kalkfreien Bodens.

## Was trotzdem funktionieren kann

### 1. Saure Mikrozonen statt flächiger Ansäuerung

Schwefel oxidiert Korn für Korn. Rund um jedes Korn entsteht kurzzeitig eine kleine saure Zone, in der Calciumphosphate, Eisen-, Mangan- und Zinkverbindungen gelöst werden, auch wenn der Boden insgesamt alkalisch bleibt. Liegt viel Schwefel auf engem Raum, kann ein kleines Bodenvolumen ganz entkalkt werden. Wurzeln wachsen bevorzugt in solche nährstoffreichen Zonen ein [7, 9]. Die Wurzel muss also nicht den ganzen Boden saurer haben, sondern einige Stellen, an denen sie Nährstoffe holen kann. Utah State University empfiehlt deshalb, Schwefel in Bändern auszubringen, um den pH-Wert in einem kleinen Bodenvolumen zu senken, vor allem bei weniger als 2,5 % Kalk [24].

Wie viel Boden lässt sich örtlich entkalken? (Eigene Rechnung, Liter bei LD 1,4.)

| Schwefel je Stock | auflösbarer Kalk | kalkfrei werdender Boden bei 1 % Kalk | bei 5 % Kalk | bei 20 % Kalk |
|---|---|---|---|---|
| 25 g | 78 g CaCO₃ | 7,8 kg (5,6 L) | 1,6 kg (1,1 L) | 0,4 kg (0,3 L) |
| 50 g | 156 g | 15,6 kg (11 L) | 3,1 kg (2,2 L) | 0,8 kg (0,6 L) |
| 100 g | 312 g | 31 kg (22 L) | 6,2 kg (4,5 L) | 1,6 kg (1,1 L) |
| 200 g | 624 g | 62 kg (45 L) | 12,5 kg (9 L) | 3,1 kg (2,2 L) |

Bei 4.000 Stöcken je ha entsprechen 50 g je Stock 200 kg S/ha, 100 g je Stock 400 kg S/ha.

Im Unterstockband (0,5 m breit, 0–10 cm, 2,5 m Reihenabstand: 280 t Boden je ha, 70 kg je Laufmeter) gilt: 1 g Schwefel je kg Boden entspricht 280 kg S/ha bzw. 70 g S je Laufmeter (eigene Rechnung).

| Bandgabe | Schwefel je kg Bandboden | aufgelöster Anteil des Bandkalks bei 1 % | bei 5 % | bei 20 % |
|---|---|---|---|---|
| 200 kg S/ha | 0,71 g | 22 % | 4,5 % | 1,1 % |
| 400 kg S/ha | 1,43 g | 45 % | 8,9 % | 2,2 % |

Bei 5 % Kalk und mehr bleibt auch das gedüngte Band kalkhaltig. Dann wirkt nur noch das Mikrozonen-Prinzip an den einzelnen Körnern.

### 2. Was Versuche zeigen

| Arbeit | Versuchsart | Boden, Region | Maßnahme | Ergebnis | Übertragbarkeit auf österreichische Weingärten |
|---|---|---|---|---|---|
| North-Central-Tagungsband [4] | Feld | kalkhaltige Böden, nördliche Great Plains (USA) | bis 8.000 lb S/acre (≈ 9 t S/ha) | Bodentest-P in 0–7,5 cm von 27 auf 57 mg/kg, Zn von 1,57 auf 2,09 mg/kg, Fe von 28 auf 58 mg/kg (Zahlen aus der Suchzusammenfassung, im Original prüfen) | Wirkung nur bei extremen, unbezahlbaren Mengen |
| DeLuca & Skogley [3] | Versuch mit Bandapplikation | alkalische, calciumreiche Böden (USA) | Schwefel im Band, auch mit Superphosphat | Schwefel erhöht die P-Verfügbarkeit über mikrobiell gebildete Schwefelsäure | Prinzip übertragbar; Superphosphat im Bio-Landbau nicht zulässig |
| Weizenversuch [25] | Feld | Kalkboden (vermutlich Südasien) | Schwefel plus S-oxidierende Bakterien | steigende S-Gaben: pH nach der Ernte niedriger, mehr verfügbares P, S, Fe, Cu, Zn, Mn, B (ungeprüft, nur Kurzfassung gesehen) | arides Klima, Ackerbau |
| Modaihsh et al. [2] | Laborinkubation ohne Pflanzen | Kalkböden, Saudi-Arabien | steigende S-Gaben | pH nur wenig gesenkt, Leitfähigkeit erhöht, extrahierbares P, Fe, Mn, Zn erhöht (ungeprüft) | Labor, arides Klima |
| Cifuentes & Lindemann [23] | Laborinkubation | Kalkboden (USA) | Schwefel mit und ohne organische Substanz | organische Substanz förderte die Oxidation | Mechanismus übertragbar |
| Jaggi et al. [22] | Laborinkubation | saure, neutrale, alkalische Böden (Indien) | Schwefel bei verschiedener Temperatur und Feuchte | pH-Wirkung und P-Verfügbarkeit hängen stark von Temperatur und Feuchte ab (ungeprüft) | Mechanismus übertragbar |
| Kulczycki [26] | Übersichtsarbeit | viele Standorte | Schwefeldüngung | pH-Senkung vor allem auf leichten, schwach gepufferten Böden (ungeprüft) | Überblick |
| Tagliavini & Rombolà [11] | Übersichtsarbeit | Obst- und Weinbau | Maßnahmen gegen Kalkchlorose | Ansäuern stark kalkhaltiger Böden ist nicht wirtschaftlich; Unterlagenwahl, organische Substanz, Begrünung und Eisengaben stehen im Vordergrund (ungeprüft) | direkt relevant |

Lesehilfe:

- Mehr extrahierbares Phosphat oder Mangan im Bodentest heißt noch nicht, dass die Rebe mehr aufnimmt oder mehr Ertrag bringt.
- Feldwirkungen auf Kalkböden traten in den gesehenen Quellen bei sehr hohen Mengen auf. In einer weiteren Untersuchung stieg der pH-Wert in Feld und Gefäß im Lauf der Zeit wieder an (laut Suchergebnis; Quelle nicht eindeutig zugeordnet).
- Rebenversuche mit Schwefel gegen Kalkchlorose oder Phosphormangel in Mitteleuropa sind nicht bekannt.

> **Offen:** Effektgrößen der Laborarbeiten (wie stark P, Fe, Mn, Zn stiegen; wie stark der pH-Wert sank) aus den Originalen nachtragen. Eine gezielte Online-Suche (November 2026) fand keinen Feldversuch mit elementarem Schwefel bei Reben auf Kalkboden. Am nächsten kommen ein Gefäßversuch mit Schwefelsäure (nicht Schwefel) an Riesling-Pfropfreben auf kalkhaltigem Nachbauboden, in dem behandelte Reben keine Chlorose zeigten (ISHS Acta Horticulturae 477), sowie Versuche mit anderen Kulturen. Feld- oder Praxisversuche mit örtlicher Schwefelgabe bei Reben oder Obstbäumen bleiben gesucht.

### 3. Schwefel mit Kompost, Trester oder Rohphosphat kombinieren

- **Kompost:** Organische Substanz beschleunigt die Oxidation [23], bringt Phosphor und Mikronährstoffe mit und lockt Wurzeln in die behandelte Zone. Schwefel und reifen Kompost vor dem Ausbringen mischen. Siehe [Organische Substanz](organische-substanz.md).
- **Traubentrester:** Frisch oder kompostiert als Humusquelle sinnvoll. Als Säurequelle taugt er nicht (siehe unten).
- **Rohphosphat:** Weicherdiges Rohphosphat löst sich nur in saurem Boden. Bei pH-Werten über etwa 7 ist es nahezu wirkungslos [27]. Die Idee: Schwefel direkt neben dem Rohphosphatkorn liefert die Säure. Im Kalkboden verbraucht aber der Bodenkalk den größten Teil dieser Säure. Belege stammen überwiegend aus Gefäßversuchen in ariden Regionen. Ob ein Gemisch aus Schwefel, Rohphosphat und Kompost im Weingarten mehr Phosphor liefert als Kompost allein, ist nicht untersucht. Nur als Versuch, siehe [Phosphor](phosphor.md).

### 4. Schwefel-Bentonit-Produkte

Schwefel-Bentonit-Pastillen enthalten meist rund 90 % Schwefel und 10 % Bentonit, einen quellfähigen Ton (Zusammensetzung laut Etikett prüfen). Bei Nässe quillt der Ton, und die Pastille zerfällt in feine Teilchen. Erst danach oxidiert der Schwefel rasch. Entscheidend ist die dem Boden ausgesetzte Oberfläche [19, 21]. In trockenem Oberboden können Pastillen monatelang liegen bleiben.

- **Vorteil:** staubarm, mit dem Düngerstreuer ins Unterstockband streubar, mit dem Unterstockgerät einzuarbeiten.
- **Bio-Zulässigkeit:** Elementarer Schwefel sowie Gesteinsmehle und Tone stehen in Anhang II der VO (EU) 2021/1165 [1]. Das konkrete Produkt muss als Düngemittel in Verkehr gebracht und für den Bio-Landbau gelistet sein (in Österreich Betriebsmittelkatalog bei InfoXgen; Kontrollstelle fragen). Details: [Bio-Rechtsrahmen](bio-rechtsrahmen.md).

> **Achtung:** Netzschwefel ist ein Pflanzenschutzmittel. Er darf nur für die zugelassenen Anwendungen eingesetzt werden [28]. Als Bodendünger oder Ansäuerungsmittel ein Düngeprodukt mit elementarem Schwefel verwenden.

### 5. Schwefel als Nährstoff

Die Rebe braucht Schwefel für Eiweiß. Der Bedarf ist im Vergleich zu den Mengen aus dem Pflanzenschutz klein [29]. Im Bio-Weinbau mit regelmäßigem Netzschwefel ist Schwefelmangel daher sehr unwahrscheinlich. Betriebe mit pilzwiderstandsfähigen Sorten (PIWI), die kaum Schwefel spritzen, sollten die Schwefelversorgung von Leguminosen in der Begrünung im Blick behalten (nicht belegt; Blattanalyse). Zugelassene Sulfatquellen: Gips, Kaliumsulfat, Kieserit (natürlichen Ursprungs) [1]. Siehe [Weitere Nährstoffe](weitere-naehrstoffe.md).

## Netzschwefel aus dem Pflanzenschutz: säuert er den Boden an?

### Wie viel Schwefel kommt in den Boden?

Je Behandlung gegen Echten Mehltau werden in Europa sehr unterschiedliche Mengen ausgebracht. Eine Übersicht nennt 1,2 kg/ha (Schweiz) bis 12,5 kg/ha (Frankreich); in Deutschland liegen die zugelassenen Mengen je Bodenfläche zwischen 2,4 und 4,8 kg/ha [30]. Die EFSA rechnete in ihrer Risikobewertung mit Szenarien von 8, 19,7 und 29,5 kg Wirkstoff je ha (Bezug laut Suchergebnis unklar) [31].

Schätzung für einen Bio-Betrieb (eigene Rechnung, Annahmen: Netzschwefel mit 80 % S):

| Behandlungen je Jahr | 2 kg Präparat je Behandlung | 4 kg | 6 kg |
|---|---|---|---|
| 6 | 9,6 kg S/ha | 19 kg S/ha | 29 kg S/ha |
| 8 | 13 kg S/ha | 26 kg S/ha | 38 kg S/ha |
| 12 | 19 kg S/ha | 38 kg S/ha | 58 kg S/ha |

Größenordnung also 10–60 kg S je ha und Jahr. Den eigenen Wert aus den Spritzaufzeichnungen berechnen: Summe der ausgebrachten kg Netzschwefel × Schwefelgehalt laut Etikett. Ein Teil bleibt auf Blättern und Trauben, landet aber mit Regen und Laubfall großteils im Boden, vermutlich vor allem im Unterstockbereich (nicht belegt).

### Wirkung auf kalkhaltigen Böden

30 kg S/ha und Jahr lösen höchstens rund 94 kg CaCO₃ je ha und Jahr (eigene Rechnung). Bei 1 % Kalk in 0–30 cm sind das 0,2 % des Vorrats. Messbar ist das nicht. Anders in den obersten Zentimetern eines kalkarmen Bodens: Bei 1 % Kalk in 0–5 cm wäre dieser Vorrat nach rund 75 Jahren mit 30 kg S/ha verbraucht, wenn nicht gemischt würde. Auf schwach kalkhaltigen Böden kann jahrzehntelanger Schwefeleinsatz die oberste Schicht also entkalken.

### Wirkung auf kalkfreien Böden

Hier wirkt Netzschwefel deutlich. Höchstmögliche pH-Senkung je Jahr in 0–10 cm, wenn der gesamte Schwefel dort oxidiert und nichts gegenwirkt (eigene Rechnung):

| Eintrag | Puffer 5 mmol/kg | Puffer 15 mmol/kg | Puffer 30 mmol/kg |
|---|---|---|---|
| 10 kg S/ha und Jahr | 0,09 | 0,03 | 0,015 |
| 30 kg S/ha und Jahr | 0,27 | 0,09 | 0,045 |
| 60 kg S/ha und Jahr | 0,54 | 0,18 | 0,09 |

In Wirklichkeit ist die Senkung kleiner: Hydrogencarbonat im Bewässerungswasser, Staub, Verwitterung und die basisch wirkenden Pflanzenreste gleichen einen Teil aus. Auf kalkfreien, sandigen Weingartenböden alle 3–5 Jahre den pH-Wert messen. Auf einem kalkfreien, alkalischen Boden kann der Netzschwefel die gewünschte Ansäuerung schon allein bewirken – vor zusätzlichen Schwefelgaben deshalb den pH-Verlauf der letzten Jahre prüfen.

> **Achtung:** Weingartenböden enthalten oft viel Kupfer aus dem Pflanzenschutz. Kupfer wird mit sinkendem pH-Wert löslicher und giftiger für Wurzeln und Bodenleben [32, 33]. Kalkfreie, kupferreiche Böden nicht unter etwa pH 6 ansäuern (Vorsorgewert, eigene Festlegung).

## Gips (Calciumsulfat)

### Was Gips nicht kann

Gips (CaSO₄ · 2 H₂O) ist ein Neutralsalz. Er enthält keine Säure und bildet im Boden auch keine. Er löst deshalb keinen Kalk auf und senkt den pH-Wert kalkhaltiger Böden nicht [5, 13].

Das zusätzliche Calcium verschiebt allerdings das Kalk-Kohlensäure-Gleichgewicht: Der pH-Wert in Wasser kann um wenige Zehntel sinken (Tabelle oben: von 8,1 auf 7,7 bei Außenluft; eigene Rechnung nach [8]). Im pH(CaCl₂), wie er in Österreich gemessen wird, ändert sich praktisch nichts, weil die Messlösung schon viel Calcium enthält. Ein Vorteil für die Eisen- oder Phosphorversorgung ist nicht belegt. Beim Phosphor ist eher ein Nachteil zu erwarten: Mehr gelöstes Calcium begünstigt die Fällung von Calciumphosphaten [8].

### Wo Gips hilft: Natriumböden

In natriumhaltigen Böden (Fachbegriff: sodische Böden) besetzt Natrium einen großen Teil der Austauscherplätze. Der Boden verschlämmt, der pH-Wert liegt oft über 8,5. Als Grenze gilt ein Anteil austauschbaren Natriums (ESP) von 15 % [5]. Gips liefert gelöstes Calcium, das Natrium verdrängt. Das Natrium wird als Natriumsulfat ausgewaschen; dafür braucht es durchlässigen Boden und Sickerwasser [6, 34]. In Österreich kommen natriumhaltige Salzböden vor allem im Seewinkel vor (Bodenkarte eBOD prüfen) [35].

**Rechenbeispiel Gipsbedarf** (eigene Rechnung, 0–20 cm, 2.800 t Boden/ha): Je 1 cmol(+)/kg auszutauschendem Natrium braucht man 2,4 t Gips je ha. Bei einer Kationenaustauschkapazität (KAK) von 15 cmol(+)/kg und einer Senkung des ESP von 20 % auf 10 % sind 1,5 cmol(+)/kg zu ersetzen: rund 3,6 t Gips je ha, plus einen Zuschlag für unvollständigen Austausch (Größe laut Fachberatung).

Ein Sonderfall: Auf kalkhaltigen Natriumböden wirkt auch Schwefel. Die gebildete Säure löst den Bodenkalk, und das frei werdende Calcium verdrängt das Natrium. 1 t Gips entspricht dabei 0,19 t Schwefel [5] (eigene Rechnung: 0,186).

> **Achtung:** Die Salzlacken des Seewinkels und ihre Umgebung stehen großteils unter Naturschutz (Nationalpark, Natura 2000). Vor Gips- oder Schwefelgaben in Lackennähe die Naturschutzbehörde fragen.

### Weitere Eigenschaften

- **Struktur:** Auf Böden ohne Natriumproblem bringt Gips wenig, weil kalkhaltige Böden ohnehin calciumgesättigt sind.
- **Nährstoffe:** Gips enthält 18,6 % Schwefel und 23,3 % Calcium (eigene Rechnung, reiner Gips).
- **Löslichkeit:** rund 2 g/L (ungeprüft). Gips wirkt deshalb über mehrere Jahre.
- **Bio-Zulässigkeit:** Calciumsulfat (Gips) ist nur natürlichen Ursprungs zugelassen [1]. Naturgips ja; Gips aus der Rauchgasentschwefelung (REA-Gips) und Phosphogips nein.

## Andere „saure“ Materialien

Säurewirkung je kg ist bei Reinstoffen eigene Rechnung, bei Torf und Trester eine grobe Annahme.

| Material | Säure je kg (theoretisch) | Was im Boden passiert | Bio-Zulässigkeit nach VO (EU) 2021/1165 | Bewertung |
|---|---|---|---|---|
| Elementarer Schwefel | 62 mol H⁺ (Schwefel-Bentonit 90 %: 56 mol) | wird mikrobiell zu Schwefelsäure | zugelassen [1] | einziges wirksames Mittel |
| Eisen(II)-sulfat (Heptahydrat) | 7 mol (ein Neuntel von Schwefel) | Eisen fällt als Oxid aus, dabei wird Säure frei | als Spurennährstoff, Bedingungen siehe [Bio-Rechtsrahmen](bio-rechtsrahmen.md) | als Säurequelle teuer; Eisenwirkung kurz, siehe [Eisen-Chlorose](eisen-chlorose.md) |
| Frischer Traubentrester | grob 0,05–0,15 mol (Annahme) | Fruchtsäuren werden in Wochen abgebaut; der Abbau verbraucht die Säure wieder; Kalium wirkt danach eher basisch [36] | betriebseigenes Pflanzenmaterial bzw. Kompost; Kontrollstelle fragen | Humus ja, Ansäuerung nein |
| Nadelstreu | gering | langsamer Abbau, kaum freie Säure | Pflanzenmaterial; Entnahme aus dem Wald mit Eigentümer bzw. Forstbehörde klären | nein |
| Torf | grob 1–1,5 mol je kg Trockenmasse (Annahme) | puffert, wird langsam abgebaut; für 1 % Kalk in 0–20 cm wären 370–560 t nötig | nur für Gartenbauzwecke (laut Wortlaut: Gemüsebau, Ziergartenbau, Gehölze, Baumschulen); im Ertragsweingarten nicht zulässig [1] | nein; Moorzerstörung, CO₂ |
| Kaffeesatz | gering | frisch ausgebracht wachstumshemmend [37] | pflanzliches Nebenerzeugnis, Kontrollstelle fragen; besser kompostieren | nein |
| Speiseessig (5 %) | 0,8 mol | Essigsäure wird in Tagen abgebaut, Säure verbraucht | als Dünger nicht gelistet, für Boden und Bewässerung nicht zulässig | nein |
| Zitronensäure | 14 mol | Citrat wird rasch abgebaut; der Abbau verbraucht die Säure [36] | nicht gelistet, nicht zulässig | nein |
| Schwefelsäure (96 %) | 20 mol | wirkt sofort | nicht gelistet, nicht zulässig | nein |
| Ammoniumsulfat | bis 30 mol über Nitrifikation | säuert über Umwandlung zu Nitrat | mineralischer Stickstoffdünger, verboten [38] | nein |
| Gips | 0 | Neutralsalz | zugelassen (natürlich) | kein Säuremittel |
| Holzasche, Pflanzenkohle | negativ (basisch) | heben den pH-Wert eher an | zugelassen mit Bedingungen [1] | auf Kalkböden kein Säuremittel |

Zwei Rechnungen zeigen, warum Säuren aus der Flasche nichts bringen: Um 100 mm Bewässerungswasser mit 6 mmol/L Hydrogencarbonat zu neutralisieren, bräuchte man rund 420 kg Zitronensäure oder 7.200 kg Speiseessig je ha (eigene Rechnung) – und den Bodenkalk berührt das noch gar nicht.

## Bewässerungswasser: Hydrogencarbonat vermeiden

Hartes Brunnenwasser enthält viel Hydrogencarbonat. Jedes Millimol davon bringt Lauge in den Boden, und Hydrogencarbonat ist der Hauptauslöser der Kalkchlorose [10, 14]. Bei Tropfbewässerung konzentriert sich das unter dem Tropfer, also genau im Hauptwurzelraum.

Laugeneintrag (eigene Rechnung; 1 mm auf 1 ha = 10 m³):

| Hydrogencarbonat im Wasser | 50 mm Bewässerung | 100 mm Bewässerung |
|---|---|---|
| 2 mmol/L (122 mg/L) | ≙ 50 kg CaCO₃ bzw. 16 kg S | ≙ 100 kg CaCO₃ bzw. 32 kg S |
| 4 mmol/L (244 mg/L) | ≙ 100 kg CaCO₃ bzw. 32 kg S | ≙ 200 kg CaCO₃ bzw. 64 kg S |
| 6 mmol/L (366 mg/L) | ≙ 150 kg CaCO₃ bzw. 48 kg S | ≙ 300 kg CaCO₃ bzw. 96 kg S |

Umrechnung: Die Karbonathärte in °dH geteilt durch 2,8 ergibt Hydrogencarbonat in mmol/L (eigene Rechnung). 17 °dH Karbonathärte sind also rund 6 mmol/L. Die FAO-Richtwerte zur Wasserqualität bewerten Hydrogencarbonat unter 1,5 mmol/L als unproblematisch (dort für Überkopfberegnung) [39] (ungeprüft).

Was tun:

- **Wasseranalyse** mit Säurekapazität bis pH 4,3 (≈ Hydrogencarbonat), Calcium, Natrium und Leitfähigkeit.
- **Regenwasser sammeln.** Ein Dach mit 500 m² liefert bei 550 mm Niederschlag und 80 % Abfluss rund 220 m³ im Jahr, das sind 22 mm auf 1 ha (eigene Rechnung). Für Junganlagen und Chlorose-Nester reicht das oft.
- **Ansäuern des Wassers mit Säuren** ist im Bio-Landbau nicht vorgesehen: Säuren stehen nicht in Anhang II [1]. Auch das Spülen von Tropfleitungen mit Säure vorher schriftlich mit der Kontrollstelle klären.

## Praxisempfehlung

### Schritt 1: Ausgangslage messen

1. Carbonatgehalt im Labor bestimmen lassen (Scheibler-Methode), getrennt für 0–30 cm und 30–60 cm. Feldtest mit Salzsäure: siehe [Kalkbestimmung](../boden/kalk.md).
2. pH(CaCl₂) und Leitfähigkeit messen, siehe [pH-Wert und Leitfähigkeit](../boden/ph-leitfaehigkeit.md).
3. Bei Chlorose zusätzlich Aktivkalk bestimmen lassen, siehe [Eisen-Chlorose](eisen-chlorose.md).
4. Bei pH(CaCl₂) über 7,5 ohne nachweisbaren Kalk: austauschbares Natrium (ESP) bestimmen lassen.
5. Bewässerungswasser auf Hydrogencarbonat untersuchen lassen.
6. Netzschwefel-Menge der letzten Jahre aus den Spritzaufzeichnungen berechnen.

### Schritt 2: Einordnen

| Befund | Bewertung | Empfehlung |
|---|---|---|
| Carbonat 1 % und mehr | Flächige Ansäuerung aussichtslos | Kein Schwefel „zum Ansäuern“. Andere Maßnahmen, siehe [Maßnahmenplan](massnahmenplan.md). Höchstens Streifenversuch „saure Mikrozonen“. |
| Carbonat 0,1–1 % | Flächig unwirtschaftlich | Inkubationstest; danach eventuell Streifenversuch im Band |
| kein Carbonat nachweisbar, pH(CaCl₂) über 7,5 | Ursache klären | Bei Natrium: Gips oder Schwefel (siehe Gips). Sonst Inkubationstest, dann kleine Bandgaben. |
| kein Carbonat, pH(CaCl₂) 7,0–7,5 | Ansäuern meist unnötig | Netzschwefel-Wirkung beobachten, pH-Wert alle 3–5 Jahre messen |

### Schritt 3: Inkubationstest (Topftest)

Der Test zeigt, wie stark der eigene Boden auf Schwefel reagiert. Er kostet wenig und lässt sich ohne Labor durchführen (Vorschlag, eigene Ableitung; nicht als Norm geprüft).

**Material:** 5 Schraubgläser (1 L), Küchenwaage (0,01 g), fein gemahlener Schwefel (Schwefelblüte), Sprühflasche mit Regen- oder destilliertem Wasser, pH-Meter mit 0,01-M-CaCl₂-Lösung.

1. Bodenprobe aus der späteren Behandlungszone (z. B. Unterstock, 0–10 cm) nehmen, lufttrocknen, sieben (2 mm).
2. Je Glas 500 g Boden einwiegen.
3. Schwefel zugeben und gründlich mischen: 0 / 0,1 / 0,25 / 0,5 / 1,0 g. Das entspricht 0 / 0,2 / 0,5 / 1 / 2 g S je kg Boden bzw. 0 / 56 / 140 / 280 / 560 kg S/ha im Unterstockband (0,5 m × 0–10 cm, 2,5 m Reihenabstand).
4. Boden anfeuchten, bis er krümelig feucht ist, aber nicht klebt. Glas samt Inhalt wiegen und das Gewicht notieren.
5. Gläser bei Zimmertemperatur (20–25 °C) dunkel stellen. Deckel nur lose auflegen; einmal pro Woche öffnen, umrühren und Wasserverlust nach Gewicht ersetzen.
6. Nach 4 und nach 8 Wochen je eine kleine Teilprobe entnehmen, trocknen und pH(CaCl₂) sowie Leitfähigkeit messen.

**Auswertung:**

- pH-Wert gegen Schwefelmenge auftragen.
- Sinkt der pH-Wert selbst bei 2 g S/kg um weniger als 0,2 Einheiten, ist eine Ansäuerung auch im Band aussichtslos.
- Senkt eine Stufe den pH-Wert um die gewünschte Größe, diese Menge mit dem Bandfaktor umrechnen: 1 g S/kg ≙ 280 kg S/ha (bei anderer Bandbreite oder Tiefe neu rechnen).
- Der Test läuft warm und feucht. Im Freiland dauert dieselbe Wirkung deutlich länger (ungeprüft).

### Schritt 4: Streifenversuch „Schwefel im Unterstockband“

**Versuchsanlage:** Mindestens 6 Paare aus benachbarten Streifen (je 3 Reihen, gemessen wird nur die mittlere). In jedem Paar per Münzwurf festlegen, welcher Streifen behandelt wird. Der andere bleibt unbehandelt (Kontrolle), bekommt aber dieselben übrigen Arbeiten. Planung, Auswertung und Statistik wie in [Mikroorganismen und Biostimulanzien](mikroorganismen.md#eigenen-streifenversuch-anlegen) beschrieben.

**Mengen (Vorschlag, im Weingarten nicht geprüft):**

| Boden | Schwefel je Jahr | Hinweis |
|---|---|---|
| Kalkhaltig (1 % und mehr) | 200 kg S/ha im Band (50 g je Laufmeter bei 2,5 m Reihenabstand), nur als Mikrozonen-Versuch | Gips bildet sich; Leitfähigkeit messen |
| Kalkfrei, alkalisch | Menge aus dem Inkubationstest für höchstens 0,5 pH-Einheiten Senkung; typischerweise 10–70 kg S/ha im Band | Lieber zweimal klein als einmal groß |

**Ausbringung:**

- Zeitpunkt: Ende August bis Mitte September oder April bis Mai, wenn der Boden warm ist und Regen zu erwarten ist. Nicht vor längeren Trockenphasen.
- Schwefel-Bentonit oder feines Schwefelpulver mit reifem Kompost (z. B. 5–10 t/ha im Band) mischen, ins Unterstockband streuen, 2–5 cm einarbeiten.
- Pulver nur bei Windstille und mit Staubmaske ausbringen.

**Kontrolle – pH im Band messen:**

1. Vor der Behandlung und nach 3, 6 und 12 Monaten, danach jährlich, je Streifen 10–15 Einstiche genau im behandelten Band (0–10 cm) zu einer Mischprobe vereinen. Kontrollstreifen gleich beproben.
2. pH(CaCl₂) und Leitfähigkeit messen. Bei Kalkböden zusätzlich den Salzsäuretest am Bandboden wiederholen.
3. Pflanze: Chlorose-Bonitur im Mai bis Juli, Blattanalyse zur Blüte, Ertrag und Schnittholzgewicht je Streifen.
4. Erwartung: Auf kalkhaltigen Böden ändert sich der Band-pH-Wert kaum (wenn überhaupt um 0,1–0,3, ungeprüft). Entscheidend sind Pflanzenwerte. Auf kalkfreien Böden sollte der Band-pH-Wert innerhalb eines Jahres messbar sinken.

**Abbruchkriterien:**

- pH(CaCl₂) im Band unter 6,0 (Kupfer!) – keine weitere Gabe.
- Leitfähigkeit im Band deutlich über der Kontrolle (z. B. doppelt so hoch) – Pause. Reben sind salzempfindlich; als Schwelle für Ertragsverluste nennt die FAO eine Leitfähigkeit des Sättigungsextrakts von 1,5 dS/m [39] (ungeprüft). Salz aus Gips wird besser vertragen.
- Wuchsdepression oder geschädigte Wurzeln in der behandelten Zone – Versuch beenden.

### Schritt 5: Pflanzloch und Nachpflanzung (Versuchsvorschlag)

Beim Nachpflanzen in Chlorose-Nestern lässt sich die saure Mikrozone am einfachsten anlegen:

1. Kalkverträgliche Unterlage wählen (siehe [Eisen-Chlorose](eisen-chlorose.md)). Das ist die wichtigste Maßnahme.
2. Aushub mit 3–5 L reifem Kompost mischen.
3. In jedes zweite Pflanzloch zusätzlich 25–50 g feinen Schwefel gleichmäßig in den Aushub mischen, nicht als Klumpen an die Wurzeln. Die anderen Pflanzlöcher bleiben Kontrolle.
4. Anwuchs, Triebwachstum und Chlorose der Jungreben in beiden Gruppen vergleichen.

Auf kalkarmen, sandigen Böden die Schwefelmenge halbieren (Gefahr zu starker Ansäuerung).

## Risiken

| Risiko | Ursache | Vorbeugung |
|---|---|---|
| Wurzelschäden, Kupfer-, Aluminium- und Manganvergiftung | Überdosierung auf kalkarmen Böden; pH-Wert fällt örtlich stark | Inkubationstest, kleine Gaben, Schwefel gut verteilen, Band-pH messen [32, 33] |
| Salz | Aus 200 kg S/ha im Band entstehen rund 1,1 t Gips; die Bodenlösung im Band wird gipsgesättigt (eigene Rechnung) | Leitfähigkeit kontrollieren; keine Gaben bei Trockenheit kumulieren |
| Sulfat im Sickerwasser | Sulfat wird ausgewaschen | 200 kg S/ha bei 100 mm Sickerwasser ergeben bis zu 600 mg/L Sulfat, 500 kg S/ha bis zu 1.500 mg/L (eigene Rechnung, wenn alles in einem Jahr ausgewaschen wird). Der Trinkwasser-Indikatorwert liegt bei 250 mg/L [40]. In Wasserschutz- und Schongebieten keine hohen Gaben. |
| CO₂ aus Kalk | 1,37 kg CO₂ je kg S | bei Versuchsmengen unbedeutend; bei großflächiger Kalkauflösung nicht |
| keine Wirkung | Trockenheit, Kälte, grobe Körner, zu viel Kalk | Zeitpunkt, feines Material, Erwartungen nach dem Rechenteil |
| Wiederanstieg des pH-Werts | Kalk aus tieferen Schichten, hartes Bewässerungswasser | Bewässerungswasser prüfen; Wirkung mehrere Jahre messen |
| Schwefelwasserstoff | Unter Staunässe kann Schwefel zu giftigem Sulfid reduziert werden | nicht in staunassen oder verdichteten Zonen ausbringen |
| Rechtsfehler | Netzschwefel als Dünger, nicht gelistete Säuren | nur gelistete Düngeprodukte; Kontrollstelle fragen |

## Aufwand und Kosten

Preise sind Annahmen. Vor dem Kauf aktuelle Angebote einholen.

| Posten | Annahme | Kosten bzw. Aufwand |
|---|---|---|
| Schwefel-Bentonit (90 % S) | 0,8–1,5 € je kg Produkt (Annahme) | 200 kg S/ha ≈ 220 kg Produkt ≈ 180–330 €/ha |
| Ausbringen und Einarbeiten im Band | mit Düngerstreuer und Unterstockgerät, 1–2 h/ha (Annahme) | Maschinen- und Arbeitskosten des Betriebs |
| Punktgabe je Stock | 0,5–1 min je Stock | 33–67 h/ha bei 4.000 Stöcken – nur für Teilflächen und Nachpflanzungen sinnvoll |
| Inkubationstest | Gläser, Schwefelpulver, pH-Meter vorhanden | unter 50 € (Annahme) |
| Laboranalysen | Carbonat, pH, Natrium, Wasseranalyse | Laborpreis erfragen |
| Zum Vergleich: Neutralisation von 1 % Kalk in 0–30 cm | 13,5 t S/ha | rund 13.500 € je ha nur für Schwefel |

## Sicherheit

- Schwefelstaub reizt Augen, Atemwege und Haut. Beim Umgang mit Pulver Schutzbrille, Handschuhe und Staubmaske (FFP2) tragen.
- Schwefel ist brennbar. Beim Brand entsteht giftiges Schwefeldioxid. Trocken, kühl und getrennt von Oxidationsmitteln lagern, nicht rauchen. Schwefelstaub kann explosionsfähig sein.
- Sicherheitsdatenblatt des Produkts beachten; Reste nicht ins Gewässer.

## Grenzen dieses Textes

- Für Reben auf österreichischen Kalkböden gibt es keine bekannten Versuche mit örtlicher Schwefelgabe. Die Empfehlungen sind aus Chemie, Laborversuchen und Feldversuchen im Ackerbau abgeleitet.
- Die meisten Versuchsdaten stammen aus ariden Gebieten (USA, Saudi-Arabien, Südasien) oder aus Laborinkubationen.
- Die Pufferwerte für kalkfreie Böden und alle Preise sind Annahmen.

> **Offen:** Online prüfen (eine Suche im November 2026 fand keinen Rebenfeldversuch, siehe oben): Feld- oder Praxisversuche mit Schwefel bei Reben und Obstbäumen auf Kalkböden (Suchbegriffe: „elemental sulfur grapevine lime-induced chlorosis field“, „Schwefel Kalkchlorose Rebe Versuch“, „localized soil acidification orchard calcareous“); Oxidationsraten von Schwefel-Bentonit unter mitteleuropäischen Bedingungen; Netzschwefel-Jahresmengen im österreichischen Bio-Weinbau (Pflanzenschutzmittelregister des BAES, Spritzfolgen der Beratung).

## Siehe auch

- [Grundlagen alkalischer Böden](grundlagen.md)
- [Bio-Rechtsrahmen](bio-rechtsrahmen.md) – vollständige Tabelle der zugelassenen Mittel
- [Phosphor](phosphor.md)
- [Eisen-Chlorose](eisen-chlorose.md)
- [Organische Substanz](organische-substanz.md)
- [Begrünung](begruenung.md)
- [Weitere Nährstoffe](weitere-naehrstoffe.md)
- [Mikroorganismen und Biostimulanzien](mikroorganismen.md)
- [Maßnahmenplan](massnahmenplan.md)
- [Kalkbestimmung](../boden/kalk.md), [pH-Wert und Leitfähigkeit](../boden/ph-leitfaehigkeit.md)

Stand: November 2026

## Quellen

1. Durchführungsverordnung (EU) 2021/1165 der Kommission vom 15. Juli 2021 zur Zulassung bestimmter Erzeugnisse und Stoffe zur Verwendung in der ökologischen/biologischen Produktion und zur Erstellung entsprechender Verzeichnisse. Anhang II (Düngemittel, Bodenverbesserer und Nährstoffe), konsolidierte Fassung Stand 01.01.2026. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 01.01.2026: Einträge Elementarer Schwefel, Calciumsulfat, Torf, Steinmehl und Tonminerale, Holzasche, Pflanzenkohle, mineralische Spurennährstoffdünger; für Schwefel, Gips und Pflanzenkohle gelten seit 16.07.2022 die Kontaminanten-Grenzen der VO (EU) 2019/1009]
2. Modaihsh, A. S.; Al-Mustafa, W. A.; Metwally, A. I. (1989): Effect of elemental sulphur on chemical changes and nutrient availability in calcareous soils. Plant and Soil 116, 95–101. [nicht online geprüft]
3. DeLuca, T. H.; Skogley, E. O. et al.: Band-applied elemental sulfur to enhance the phytoavailability of phosphorus in alkaline calcareous soils. Biology and Fertility of Soils (Jahr, Band, Seiten nicht geprüft). DOI 10.1007/BF00257831. [online geprüft] (Titel, DOI und Kernaussage der Zusammenfassung)
4. North Central Extension-Industry Soil Fertility Conference, Tagungsband: Influence of Elemental Sulfur on Soil pH and Soil Test Levels. https://northcentralfertility.com/proceedings/?action=download&item=3691 [online geprüft] (Autoren und Jahr nicht gesehen; Zahlen aus der Suchzusammenfassung, im Original prüfen)
5. U.S. Salinity Laboratory Staff (1954): Diagnosis and Improvement of Saline and Alkali Soils. Agriculture Handbook No. 60. United States Department of Agriculture, Washington D.C. [nicht online geprüft]
6. Qadir, M.; Oster, J. D. (2004): Crop and irrigation management strategies for saline-sodic soils and waters aimed at environmentally sustainable agriculture. Science of the Total Environment 323, 1–19. [nicht online geprüft]
7. Marschner, P. (Hrsg.) (2012): Marschner's Mineral Nutrition of Higher Plants. 3. Auflage. Academic Press, London. [nicht online geprüft]
8. Lindsay, W. L. (1979): Chemical Equilibria in Soils. John Wiley & Sons, New York. [nicht online geprüft]
9. Hinsinger, P. (2001): Bioavailability of soil inorganic P in the rhizosphere as affected by root-induced chemical changes: a review. Plant and Soil 237, 173–195. [nicht online geprüft]
10. Mengel, K. (1994): Iron availability in plant tissues – iron chlorosis on calcareous soils. Plant and Soil 165, 275–283. [nicht online geprüft]
11. Tagliavini, M.; Rombolà, A. D. (2001): Iron deficiency and chlorosis in orchard and vineyard ecosystems. European Journal of Agronomy 15, 71–92. [nicht online geprüft]
12. Ulrich, B. (1981): Ökologische Gruppierung von Böden nach ihrem chemischen Bodenzustand. Zeitschrift für Pflanzenernährung und Bodenkunde 144. [nicht online geprüft]
13. Amelung, W.; Blume, H.-P.; Fleige, H.; Horn, R.; Kandeler, E.; Kögel-Knabner, I.; Kretzschmar, R.; Stahr, K.; Wilke, B.-M. (2018): Scheffer/Schachtschabel – Lehrbuch der Bodenkunde. 17. Auflage. Springer Spektrum, Berlin. [nicht online geprüft]
14. Lucena, J. J. (2000): Effects of bicarbonate, nitrate and other environmental factors on iron deficiency chlorosis. A review. Journal of Plant Nutrition 23. [nicht online geprüft]
15. Germida, J. J.; Janzen, H. H. (1993): Factors affecting the oxidation of elemental sulfur in soils. Fertilizer Research 35, 101–114. [nicht online geprüft]
16. Wainwright, M. (1984): Sulfur oxidation in soils. Advances in Agronomy 37. [nicht online geprüft]
17. Kelly, D. P.; Wood, A. P. (2000): Reclassification of some species of Thiobacillus to the newly designated genera Acidithiobacillus gen. nov., Halothiobacillus gen. nov. and Thermithiobacillus gen. nov. International Journal of Systematic and Evolutionary Microbiology 50, 511–516. [nicht online geprüft]
18. Lawrence, J. R.; Germida, J. J. (1988): Relationship between microbial biomass and elemental sulfur oxidation in agricultural soils. Soil Science Society of America Journal 52. [nicht online geprüft]
19. Boswell, C. C.; Friesen, D. K. (1993): Elemental sulfur fertilizers and their use on crops and pastures: factors affecting agronomic effectiveness. Fertilizer Research 35, 127–149. [nicht online geprüft]
20. Lindemann, W. C. et al. (1991): Effect of sulfur source on sulfur oxidation. Soil Science Society of America Journal 55, 85–90. [nicht online geprüft] (Autorenliste prüfen)
21. Degryse, F. et al. (2016): Oxidation of elemental sulfur in granular fertilizers depends on the soil-exposed surface area. Soil Science Society of America Journal 80. [nicht online geprüft] (Titel prüfen)
22. Jaggi, R. C.; Aulakh, M. S.; Sharma, R. (2005): Impacts of elemental S applied under various temperature and moisture regimes on pH and available P in acidic, neutral and alkaline soils. Biology and Fertility of Soils 41. [nicht online geprüft]
23. Cifuentes, F. R.; Lindemann, W. C. (1993): Organic matter stimulation of elemental sulfur oxidation in a calcareous soil. Soil Science Society of America Journal 57, 727–731. [nicht online geprüft]
24. Utah State University Extension: Managing Soil pH for Crop Production in Calcareous-Alkaline Soil. Logan, Utah. https://extension.usu.edu/crops/research/managing-soil-ph-for-crop-production [online geprüft] (Autor und Jahr nicht gesehen)
25. N. N. (2022): Elemental sulphur with sulphur oxidizing bacteria enhances phosphorus availability and improves growth and yield of wheat in calcareous soil. Zeitschrift nicht gesehen (Eintrag auf ResearchGate, Nr. 361989937). [online geprüft] (nur Titel und Kurzfassung)
26. Kulczycki, G. (2021): The effect of elemental sulfur fertilization on plant yields and soil properties. Advances in Agronomy 167. [nicht online geprüft] (Titel prüfen)
27. Rajan, S. S. S.; Watkinson, J. H.; Sinclair, A. G. (1996): Phosphate rocks for direct application to soils. Advances in Agronomy 57. [nicht online geprüft]
28. Verordnung (EG) Nr. 1107/2009 des Europäischen Parlaments und des Rates vom 21. Oktober 2009 über das Inverkehrbringen von Pflanzenschutzmitteln. [nicht online geprüft]
29. Keller, M. (2020): The Science of Grapevines. 3. Auflage. Academic Press, London. [nicht online geprüft]
30. N. N. (2024): Sulfur – a potential additive to increase the efficacy of copper-based fungicides against grapevine downy mildew. Short communication. OENO One. https://oeno-one.eu/article/view/7429 [online geprüft] (Autoren nicht gesehen; Angaben zu Aufwandmengen aus der Suchzusammenfassung)
31. EFSA (2009): Conclusion regarding the peer review of the pesticide risk assessment of the active substance sulphur. EFSA Scientific Report 221. [online geprüft] (nur Suchzusammenfassung)
32. Komárek, M.; Čadková, E.; Chrastný, V.; Bordas, F.; Bollinger, J.-C. (2010): Contamination of vineyard soils with fungicides: A review of environmental and toxicological aspects. Environment International 36, 138–151. [nicht online geprüft]
33. Mackie, K. A.; Müller, T.; Kandeler, E. (2012): Remediation of copper in vineyards – a mini review. Environmental Pollution 167, 16–26. [nicht online geprüft]
34. Oster, J. D.; Frenkel, H. (1980): The chemistry of the reclamation of sodic soils with gypsum and lime. Soil Science Society of America Journal 44. [nicht online geprüft]
35. Bundesforschungszentrum für Wald (BFW): eBOD – Digitale Bodenkarte von Österreich (Online-Kartendienst). [nicht online geprüft]
36. Yan, F.; Schubert, S.; Mengel, K. (1996): Soil pH increase due to biological decarboxylation of organic anions. Soil Biology and Biochemistry 28, 617–624. [nicht online geprüft]
37. Hardgrove, S. J.; Livesley, S. J. (2016): Applying spent coffee grounds directly to urban agriculture soils greatly reduces plant growth. Urban Forestry & Urban Greening 18, 1–8. [nicht online geprüft]
38. Verordnung (EU) 2018/848 des Europäischen Parlaments und des Rates vom 30. Mai 2018 über die ökologische/biologische Produktion und die Kennzeichnung von ökologischen/biologischen Erzeugnissen. ABl. L 150 vom 14.6.2018. Anhang II Teil I Nr. 1.9 (Bodenbewirtschaftung und Düngung). [online geprüft] (Nummerierung 1.9.1–1.9.9 über eine Textkopie auf legislation.gov.uk geprüft; konsolidierte Fassung bei EUR-Lex prüfen)
39. Ayers, R. S.; Westcot, D. W. (1985): Water quality for agriculture. FAO Irrigation and Drainage Paper 29, Rev. 1. FAO, Rom. [nicht online geprüft]
40. Richtlinie (EU) 2020/2184 des Europäischen Parlaments und des Rates vom 16. Dezember 2020 über die Qualität von Wasser für den menschlichen Gebrauch, Anhang I Teil C (Indikatorparameter Sulfat 250 mg/L). [nicht online geprüft]
