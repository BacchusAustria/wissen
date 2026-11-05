# Fotometrie und enzymatische Analytik

> **Achtung:** Volumina, Wellenlängen und Reaktionszeiten der Testkits unterscheiden sich je nach Hersteller, Format und Charge. Maßgeblich ist immer der Beipackzettel der Packung, die Sie verwenden. Die Zahlenbeispiele in dieser Datei erklären die Rechnung, sie ersetzen den Beipackzettel nicht.

## Kurzfassung

- **Was:** Ein Fotometer misst, wie viel Licht einer bestimmten Wellenlänge eine Lösung schluckt. Mit Enzym-Testkits bestimmt man damit L-Äpfelsäure, L-Milchsäure, Glucose und Fructose, Essigsäure, Ammonium, Acetaldehyd und Gluconsäure. Mit einem OPA-Reagenz misst man den α-Aminostickstoff. Ohne Enzyme misst dasselbe Gerät Farbe, Gesamtpolyphenole und Anthocyane.
- **Wozu:** Gärende erkennen (Restzucker), BSA verfolgen (Äpfel- und Milchsäure), Hefenährstoffe planen (YAN), Fehler früh erkennen (Essigsäure, Gluconsäure, Acetaldehyd), Rotwein beurteilen (Farbe, Phenole).
- **Genauigkeit:** Enzymtests erfassen nur die gesuchte Substanz. Bei sauberem Pipettieren erreichen sie Laborqualität. Mehrere enzymatische Verfahren sind selbst OIV-Methoden [1]. Teststreifen mit Reflektometer messen nur orientierend.
- **Aufwand:** 20–40 Minuten für eine Serie aus Leerwert, Kontrollprobe und 4–10 Proben. Einstieg ab etwa 1.400 € (Reflektometer [22]) bzw. einigen tausend Euro (Spektralfotometer und Pipetten).
- **Empfehlung:** Wer nur wenige Proben im Jahr braucht, schickt sie ins Labor oder nimmt Teststreifen. Wer während Gärung und BSA laufend Äpfelsäure, Restzucker und Stickstoff messen will, fährt mit einem UV-fähigen Fotometer und Kits verschiedener Hersteller am flexibelsten.

## Wozu?

Ein Ergebnis am selben Tag ist im Herbst oft mehr wert als eine billige Analyse nach einer Woche. Die Tabelle zeigt, welche Messung bei welcher Frage hilft.

| Zeitpunkt | Frage | Messgröße | Mehr dazu |
|---|---|---|---|
| Vor und bei der Lese | Reicht der Stickstoff für die Gärung? | Ammonium + α-Aminostickstoff (NOPA) | [Stickstoff (YAN)](stickstoff-yan.md) |
| Most | Wie viel der Säure ist Äpfelsäure? | L-Äpfelsäure | [Säure und pH](saeure-ph.md) |
| Most | Wie gesund war das Lesegut? | D-Gluconsäure | diese Datei |
| Gärung | Ist der Wein durchgegoren? | Glucose + Fructose | [Zucker und Mostgewicht](zucker-mostgewicht.md) |
| BSA | Läuft die BSA, ist sie fertig? | L-Äpfelsäure, L-Milchsäure | [Äpfel-Milchsäure-Gärung](apfel-milchsaeure-bsa.md) |
| Ausbau | Beginnt ein Essigstich? | Essigsäure | [Flüchtige Säure](fluechtige-saeure.md) |
| Schwefelung | Warum bindet der Wein so viel SO2? | Acetaldehyd | [Schweflige Säure](schweflige-saeure.md) |
| Vor der Füllung | Kupfer nach Böckserbehandlung, Eisen | Kupfer, Eisen | [Stabilitätstests](stabilitaetstests.md), [Grenzwerte](grenzwerte-recht.md) |
| Rotwein | Farbe, Gerbstoff, Farbstoff | Farbintensität, Farbton, Polyphenole, Anthocyane | diese Datei |

Grundlagen zu Laborplatz, Wasserqualität und Pipettieren stehen in [Grundlagen Labor](grundlagen-labor.md). Die Einkaufsliste für alle Analysen steht in [Einkaufsliste](einkaufsliste.md).

## Prinzip

### Lambert-Beer-Gesetz

Licht der Stärke I₀ fällt in die Küvette, die Stärke I kommt heraus. Daraus ergeben sich zwei Größen:

- **Transmission** T = I / I₀ (Anteil des durchgelassenen Lichts, 0 bis 1 bzw. 0 bis 100 %)
- **Extinktion** E = log₁₀(I₀ / I) = −log₁₀ T (im Englischen „absorbance“, A)

Das Lambert-Beer-Gesetz verknüpft die Extinktion mit der Konzentration [8]:

**E = ε × c × d**

- ε = molarer Extinktionskoeffizient des Stoffes bei der gewählten Wellenlänge, in L/(mol·cm) oder L/(mmol·cm)
- c = Konzentration in der Küvette, in mol/L bzw. mmol/L
- d = Schichtdicke der Küvette in cm (meist 1 cm)

Die Extinktion ist logarithmisch. Die Tabelle zeigt, wie wenig Licht bei hohen Werten noch ankommt (eigene Rechnung):

| Extinktion E | 0,1 | 0,3 | 0,5 | 1,0 | 1,5 | 2,0 |
|---|---|---|---|---|---|---|
| Transmission | 79 % | 50 % | 32 % | 10 % | 3,2 % | 1,0 % |

Bei sehr kleinen Extinktionen überwiegt das Rauschen des Geräts. Bei hohen Extinktionen verfälscht Streulicht das Ergebnis, die Kurve wird flacher. Arbeiten Sie deshalb möglichst im Bereich E = 0,1 bis 1,0. Megazyme verlangt für seine Kits eine Extinktionsänderung von mindestens 0,100 [7].

> **Offen:** Die Obergrenze von etwa 1,0 ist eine Faustregel aus dem Fachwissen. Gute Geräte messen auch bis 2 noch linear. Die Grenze Ihres Geräts steht im Datenblatt.

### Küvetten

Die Küvette muss bei der Messwellenlänge durchlässig sein.

| Material | brauchbar ab etwa | Einsatz |
|---|---|---|
| Quarzglas (QS) | 190–200 nm | 280 nm (Gesamtphenole), alle Wellenlängen; teuer, wiederverwendbar |
| UV-durchlässiger Einmal-Kunststoff | 220–230 nm | 280 nm und 340 nm |
| PMMA (Acryl), Einmal | 280–300 nm | 340 nm (Enzymtests), sichtbarer Bereich |
| Polystyrol (PS), Einmal | 340 nm (Grenzbereich) | sichtbarer Bereich; für 340 nm nur, wenn der Hersteller es freigibt |
| Optisches Glas | 320–340 nm | sichtbarer Bereich |

> **Offen:** Die Grenzwellenlängen sind Richtwerte aus dem Fachwissen. Die gültige Angabe steht auf der Küvettenpackung.

Praxisregeln:

- Küvette nur an den geriffelten oder matten Seiten anfassen. Die klaren Fenster müssen sauber und trocken sein.
- Küvette immer gleich herum einsetzen (Markierung oben).
- Halbmikroküvetten (etwa 1,5 mL) brauchen eine Mindestfüllhöhe, damit der Lichtstrahl ganz durch die Flüssigkeit geht. Die Strahlhöhe Ihres Fotometers (oft 8,5 mm oder 15 mm) steht im Handbuch.
- Luftblasen durch leichtes Klopfen entfernen.
- Für Rotweinfarbe braucht man Küvetten mit 1 mm oder 2 mm Schichtdicke (Glas oder Quarz).

### Nullabgleich, Leerwert und Probenleerwert

- **Nullabgleich:** Das Gerät wird auf E = 0 gestellt, meist gegen Luft oder Wasser. Was der Kit verlangt, steht im Beipackzettel [4].
- **Reagenzienleerwert (Leerwert):** Eine Küvette mit allen Reagenzien, aber Wasser statt Probe. Er erfasst, was die Reagenzien selbst beitragen, auch langsame Nebenreaktionen. Bei jeder Serie mitmessen.
- **Probenleerwert:** Die Eigenfarbe oder Trübung der Probe. Bei Enzymtests misst man ihn als erste Ablesung E₁ vor dem Start der Reaktion. Bei Farbtests ohne Enzym braucht man dafür eine eigene Küvette ohne Farbreagenz.

### Enzymatische Analytik

Enzyme setzen nur ihren eigenen Stoff um und meist nur eine Form davon. L-Malat-Dehydrogenase erkennt L-Äpfelsäure, aber nicht D-Äpfelsäure. Die meisten Wein-Kits koppeln die Reaktion an das Coenzym NAD⁺ oder NADP⁺. Die reduzierte Form NADH bzw. NADPH absorbiert UV-Licht mit einem Maximum bei 340 nm, die oxidierte Form nicht [8]. Pro Molekül Analyt entsteht (oder verschwindet) bei den üblichen Kits genau ein Molekül NAD(P)H. Die Extinktionsänderung ist daher ein direktes Maß für die Stoffmenge.

Beispiel L-Äpfelsäure [4]:

1. L-Malat + NAD⁺ → Oxalacetat + NADH + H⁺ (Enzym L-Malat-Dehydrogenase, L-MDH)
2. Oxalacetat + L-Glutamat → L-Aspartat + 2-Oxoglutarat (Enzym Glutamat-Oxalacetat-Transaminase, GOT)

Die zweite Reaktion entfernt das Oxalacetat. Dadurch läuft die erste Reaktion bis zum Ende (Endpunktmethode).

**Extinktionskoeffizienten von NADH** (Werte aus der Roche/R-Biopharm-Gebrauchsanweisung [4]; NADPH bei 365 nm nach [8]):

| Wellenlänge | ε NADH in L/(mmol·cm) | ε NADPH in L/(mmol·cm) | Lichtquelle |
|---|---|---|---|
| 340 nm | 6,3 | 6,3 | Spektralfotometer, Filterfotometer |
| 334 nm (Hg-Linie) | 6,18 | 6,18 | Quecksilberlampe |
| 365 nm (Hg-Linie) | 3,4 | 3,5 | Quecksilberlampe, 365-nm-LED |

Für NADH bei 340 nm ist in der Literatur auch 6,22 L/(mmol·cm) verbreitet [9]. Der Unterschied zu 6,3 beträgt gut 1 %. Verwenden Sie den Wert, den der Kit-Hersteller angibt, sonst passt die Kalibrierung nicht.

Bei 365 nm ist ε nur etwa halb so groß. Die Messung ist dann weniger empfindlich, aber möglich. Das ist der Ausweg für Geräte ohne 340-nm-Wellenlänge.

**Zwei Reaktionstypen:**

- NAD(P)H **entsteht** (Äpfelsäure, Milchsäure, Glucose/Fructose, Acetaldehyd, Gluconsäure, meist Essigsäure): ΔE = E₂ − E₁.
- NAD(P)H **wird verbraucht** (Ammonium mit Glutamat-Dehydrogenase): ΔE = E₁ − E₂.

### Farbtests im sichtbaren Bereich

Manche Kits wandeln das entstandene NAD(P)H mit dem Hilfsenzym Diaphorase und einem Tetrazoliumsalz (zum Beispiel INT, Iodnitrotetrazolium) in einen roten Farbstoff (Formazan) um. Gemessen wird dann im sichtbaren Bereich, beim INT-Formazan um 490–500 nm. Vorteil: Ein einfaches Fotometer ohne UV reicht. Nachteil: Rotwein absorbiert in diesem Bereich selbst stark und muss stärker verdünnt werden.

> **Offen:** R-Biopharm führt neben UV-Tests eine Farbtest-Linie („Enzytec Color“). Welche Weinparameter es so gibt und bei welcher Wellenlänge gemessen wird, konnte nicht geprüft werden. Vor dem Kauf im Katalog nachsehen. Auch Systemanbieter (siehe unten) arbeiten teils mit Farbreaktionen.

Nicht-enzymatische Farbreaktionen gehören ebenfalls hierher: Folin-Ciocalteu-Reagenz für Phenole (750 nm [2]), Farbkomplexe für Eisen (mit o-Phenanthrolin um 510 nm, mit Ferrozin um 562 nm) und für Kupfer (etwa mit Bathocuproin).

> **Offen:** Die Wellenlängen der Eisen- und Kupferkomplexe sind Fachwissen und wurden nicht gegen eine Quelle geprüft.

## Geräteklassen für den Kleinbetrieb

### (a) Spektralfotometer und Kits verschiedener Hersteller

Ein Spektralfotometer stellt jede Wellenlänge im Messbereich ein. Für Enzymtests muss es 340 nm können.

- **UV/VIS-Geräte** (Deuterium- oder Xenonblitzlampe, etwa 190–1100 nm) messen auch 280 nm (Gesamtphenole).
- **Einfache VIS-Geräte** mit Halogenlampe reichen teilweise bis in den nahen UV-Bereich. Beispiel: Thermo Scientific GENESYS 30, Messbereich 325–1100 nm, Wolfram-Halogenlampe, spektrale Bandbreite 5 nm, Wellenlängengenauigkeit ±2 nm [23]. Halogenlampen liefern bei 340 nm wenig Licht. Das Messsignal rauscht dort stärker. Prüfen Sie solche Geräte mit einem Kit-Standard, bevor Sie sich auf sie verlassen.
- **Filterfotometer** mit festem 340-nm-Filter sind eine billigere Alternative, wenn nur Enzymtests gemessen werden.

Kits bieten unter anderem Megazyme (Neogen), R-Biopharm (früher Boehringer Mannheim bzw. Roche) und BioSystems an. Die Packungen reichen typischerweise für 50 manuelle Tests, zum Beispiel R-Biopharm Enzytec Liquid L-Äpfelsäure (50 Tests, Messbereich 20–500 mg/L in der Probelösung) [5] oder Megazyme L-Äpfelsäure „Liquid Ready“ (50 manuelle Tests) [6]. Der Megazyme-L-Milchsäure-Kit enthält 50 manuelle Tests [28].

| Vorteile | Nachteile |
|---|---|
| Kits beliebiger Hersteller nutzbar, auch für seltene Parameter (Gluconsäure, Acetaldehyd) | Pipettieren kleiner Volumina muss man üben |
| Dasselbe Gerät misst Farbe, Phenole, Anthocyane, Eisen | Rechnen und Dokumentieren liegt beim Anwender |
| Ergebnisse auf OIV-Niveau möglich [1] | Ein Leerwert pro Serie verbraucht einen Test |
| Gebrauchtgeräte verfügbar (Beispiel: generalüberholtes UV/VIS-Gerät um 2.000 € [27]) | Kits sind teils nur Monate haltbar |

> **Offen:** Neupreise für einfache UV/VIS-Spektralfotometer wurden nicht verlässlich gefunden. Bitte zwei bis drei Angebote einholen und dabei nach der Genauigkeit bei 340 nm fragen.

### (b) Wein-Analysesysteme mit Fertigreagenzien

Diese Systeme kombinieren ein Fotometer mit vorbereiteten Reagenzien, festen Messprogrammen und oft vorbefüllten Küvetten. Man pipettiert weniger, das Gerät rechnet selbst.

- **CDR WineLab:** LED-Fotometer, Messzellen auf 37 °C temperiert, ab Werk kalibriert. Kits zu 10 oder 100 Tests. Messbereiche laut Anbieter unter anderem L-Äpfelsäure 0,05–2,9 g/L, L-Milchsäure 0,1–3,6 g/L, YAN 30–300 mg/L (anorganischer und organischer Stickstoff getrennt). Weitere Parameter: Essigsäure, Glycerin, Gluconsäure, Gesamtsäure, pH, Alkohol, Polyphenole. Der Anbieter berichtet eine gute Übereinstimmung mit OIV-Methoden, bei L-Milchsäure eine schwächere [19].
- **Steroglass:** Automaten der Reihe Hyperlab (Plus mit etwa 180 Analysen pro Stunde, Smart mit etwa 140 pro Stunde und rund 60 hinterlegten Methoden, Basic) und gebrauchsfertige Flüssigreagenzien. L-Äpfelsäure-Kits für 50/100 manuelle oder 200/300 automatische Analysen [20]. Die Automaten sind eher etwas für größere Betriebe und Labors.
- **Hanna Instruments:** Einzelparameter-Fotometer für Wein, zum Beispiel HI83748 für Weinsäure (0,0–5,0 g/L, Reagenzien für 20 Tests) und HI83746 für reduzierende Zucker (0,00–50,0 g/L). Einen Enzymtest für Äpfelsäure bietet Hanna nach den gefundenen Unterlagen nicht an. YAN misst Hanna mit einem Mini-Titrator nach der Formolmethode [21].
- **BioSystems:** bietet Reagenzien für manuelle Fotometer und Analysenautomaten an (zum Beispiel Y15). Ein Vollautomat lohnt sich nur für Labors oder sehr große Betriebe.

> **Offen:** Die BioSystems-Angaben stammen aus dem Fachwissen und wurden nicht online geprüft. Gerätepreise und Kosten pro Test für CDR und Steroglass wurden nicht gefunden; Angebote einholen.

| Vorteile | Nachteile |
|---|---|
| Wenig Pipettierschritte, fertige Rechnung | An einen Anbieter gebunden (Reagenzien, Service) |
| Kurze Einarbeitung | Nur die Parameter des Anbieters |
| Temperierte Messzellen | Kosten pro Test meist höher als bei offenen Kits |

### (c) Teststreifen mit Reflektometer (Merck RQflex 20)

Ein Teststreifen wird kurz in die verdünnte Probe getaucht. Das Handgerät misst die Farbe des Reaktionsfelds im Auflicht (Reflektometrie) und zeigt die Konzentration an. Das Gerät RQflex 20 kostet etwa 1.320–1.420 € [22]. Für Wein gibt es unter anderem diese Reflectoquant-Tests [22]:

| Test | Messbereich in der Messlösung | Packung, Preis |
|---|---|---|
| Äpfelsäure (1.16128) | 5,0–60,0 mg/L | 50 Tests, 146 € (Österreich-Preis, Abruf November 2026) |
| Milchsäure | 3,0–60,0 mg/L | – |
| Gesamtzucker Glucose + Fructose (1.16136) | 65–650 mg/L | – |
| Ammonium (1.16892) | 0,2–7,0 mg/L NH₄⁺ | – |

Die Messbereiche liegen weit unter den Gehalten im Wein. Ein Wein mit 2 g/L Äpfelsäure muss etwa 1:50 verdünnt werden. Jeder Verdünnungsfehler geht voll ins Ergebnis ein.

| Vorteile | Nachteile |
|---|---|
| Niedrige Einstiegskosten, kein Pipettieren kleiner Volumina | Nur orientierend, starke Verdünnung nötig |
| Ergebnis in wenigen Minuten | Streifen altern, Ablesezeit und Temperatur müssen genau stimmen |
| Gut für die laufende BSA-Kontrolle | Nur wenige Parameter |

> **Offen:** Eine unabhängige Prüfung der Genauigkeit der Reflectoquant-Tests in Wein wurde nicht gefunden. Vor dem Einsatz einige Proben parallel im Labor messen lassen.

## Parameter im Überblick

Die Verdünnungen sind Richtwerte. Ziel ist immer ΔE zwischen 0,1 und 1,0. Die Messbereiche der Kits stehen im Beipackzettel.

| Parameter | Wozu | Reaktion und Messgröße | Verdünnung (Richtwert) | Störungen |
|---|---|---|---|---|
| L-Äpfelsäure | BSA-Kontrolle, Säureplanung | L-MDH + GOT, NADH entsteht, 340 nm [4] | Most und Jungwein 1:10 bis 1:20; nach BSA unverdünnt bis 1:2 | Rotweinfarbe; D-Äpfelsäure wird nicht erfasst |
| L-Milchsäure | BSA-Fortschritt | L-LDH + Transaminase, NADH entsteht, 340 nm [8] | nach BSA 1:5 bis 1:10 | Nur L-Form; D-Milchsäure aus Bakterienverderb braucht einen eigenen Kit |
| Glucose + Fructose | Gärende, Restzucker | Hexokinase + G6P-DH (+ PGI für Fructose), NADPH entsteht, 340 nm [1, 8] | trockene Weine 1:5 bis 1:10; Most 1:500 bis 1:1000 in zwei Schritten | Saccharose nur mit Zusatzenzym |
| Essigsäure | Essigstich früh erkennen | je nach Kit Acetyl-CoA-Synthetase-System (NADH entsteht) oder Acetatkinase-System, 340 nm [8] | 1:5 bis 1:20 | Rotweinfarbe; beim ACS-System nichtlineare Rechnung laut Beipackzettel |
| Ammonium | Hefestickstoff (YAN) | Glutamat-Dehydrogenase, NAD(P)H wird verbraucht, 340 nm [8] | Most meist unverdünnt bis 1:5 | Ammoniak aus Raumluft und Reinigern; Trübung |
| α-Aminostickstoff (NOPA) | Hefestickstoff (YAN) | OPA/N-Acetylcystein bildet Isoindole, 335–340 nm, kein Enzym [7, 18] | meist unverdünnt; über 200 mg N/L verdünnen [30] | Prolin wird nicht erfasst; lichtempfindlich |
| Acetaldehyd | SO2-Bindung, Oxidation | Aldehyd-Dehydrogenase, NADH entsteht, 340 nm [8] | laut Kit | sehr flüchtig; im Wein großteils an SO2 gebunden |
| D-Gluconsäure | Botrytis und Sauerfäule anzeigen | Gluconatkinase + 6-Phosphogluconat-DH, NADPH entsteht, 340 nm [8] | gesundes Lesegut 1:5; faules 1:20 bis 1:50 | Gluconolacton zuvor alkalisch spalten (laut Kit) |
| Kupfer | Rückstand nach Kupferbehandlung | Farbkomplex im sichtbaren Bereich | laut Test | Weinfarbe, Phenole, SO2; Referenz ist AAS/ICP im Labor |
| Eisen | Eisenbruch-Risiko | Farbkomplex, Fe(III) vorher reduzieren | laut Test | Weinfarbe, Phenole |
| Gesamtpolyphenole | Pressfraktionen, Rotweinausbau | Folin-Ciocalteu 750 nm [2] oder Eigenabsorption 280 nm [15, 16] | Rotwein 1:5, Weißwein unverdünnt [2] | Zucker, SO2, Ascorbinsäure (Folin); bei 280 nm Quarz- oder UV-Küvette |
| Farbintensität, Farbton | Rotweinfarbe, Bräunung | E420, E520, E620 [3] | unverdünnt in 1-mm-Küvette | Verdünnen verändert die Farbe [17]; Trübung |
| Anthocyane | Farbstoffgehalt | SO2-Bleichung bei 520 nm [12] oder pH-Differenzmethode [14] | im Verfahren enthalten | Methoden liefern unterschiedliche Zahlen |

> **Offen:** Die Verdünnungsrichtwerte sind aus typischen Gehalten und den Faktoren unten abgeleitet, nicht aus einer Quelle übernommen.

### Hinweise zu einzelnen Parametern

- **Restzucker:** Der Enzymtest erfasst nur Glucose und Fructose. Das entspricht dem Zuckergehalt, den das Weinrecht meint. Kupferreduktionsverfahren (etwa Clinitest) erfassen auch andere reduzierende Stoffe (siehe [Zucker und Mostgewicht](zucker-mostgewicht.md)). Bei V = 2,220 mL und v = 0,100 mL entspricht ΔE = 1,0 rund 0,63 g/L Zucker in der Probelösung (eigene Rechnung mit der Formel unten). Ein trockener Wein mit 2 g/L Fructose wird daher 1:5 verdünnt.
- **Essigsäure:** Der Enzymtest misst nur Essigsäure. Die flüchtige Säure nach Wasserdampfdestillation enthält auch andere flüchtige Säuren und wird als Essigsäure angegeben. Beide Werte sind nicht identisch (siehe [Flüchtige Säure](fluechtige-saeure.md)).
- **α-Aminostickstoff und Ammonium:** Durchführung und Rechnung stehen in [Stickstoff (YAN)](stickstoff-yan.md).
- **Acetaldehyd:** 1 mg Acetaldehyd bindet rechnerisch 1,45 mg SO2 (Molmassen 44,05 und 64,06 g/mol; Bindung 1:1). Probe kühl, in vollem Gefäß und rasch messen. Ob der Kit gebundenes Acetaldehyd vollständig erfasst, steht im Beipackzettel.
- **Gluconsäure:** Botrytis cinerea und Essigsäurebakterien bilden Gluconsäure aus Glucose. Ein hoher Wert zeigt faules oder sauerfaules Lesegut an [13].
- **Kupfer und Eisen:** Fertige Küvettentests aus der Wasseranalytik sind nicht für Wein gemacht. Farbe, Phenole und SO2 stören. Ohne Prüfung mit Aufstockung (siehe Qualitätssicherung) sind die Werte nur grob. Rechtlich relevante Werte immer im Labor messen lassen (Atomabsorption oder ICP).

## Material

Für Variante (a), Spektralfotometer und Kits:

| Material | Menge | Hinweis |
|---|---|---|
| Spektralfotometer mit 340 nm (für 280 nm: UV/VIS) | 1 | Küvettenhalter 10 mm; optional Halter für 1-mm-Küvetten |
| Einmal-Halbmikroküvetten PMMA oder UV-Kunststoff, 10 mm | 100 Stück | 1 Stück je Messung |
| Kolbenhubpipetten 10–100 µL, 100–1000 µL, 0,5–5 mL | je 1 | regelmäßig wiegend prüfen (siehe Qualitätssicherung) |
| Pipettenspitzen passend | je 1 Packung | 3–5 Spitzen je Messung |
| Messkolben Klasse A, 10, 25, 50, 100 mL | je 2 | für Verdünnungen |
| Bechergläser 25–50 mL, Einwegspritzen, Spritzenfilter 0,45 µm, Faltenfilter | nach Bedarf | Probenvorbereitung |
| Küvettenspatel oder Parafilm | 1 Packung | zum Mischen in der Küvette |
| Kurzzeitwecker, Thermometer | je 1 | Reaktionszeit, Raumtemperatur 20–25 °C |
| Kühlschrank 2–8 °C, nur für Chemikalien | 1 | Kit-Lagerung, getrennt von Lebensmitteln |
| Demineralisiertes oder destilliertes Wasser in Laborqualität | 5 L | ohne Zusätze; kein „destilliertes Wasser“ für Bügeleisen mit Duftstoff |
| PVPP (Polyvinylpolypyrrolidon) | 100 g | Entfärben von Rotwein für einige Kits |
| Enzym-Kits je Parameter | je 1 | Haltbarkeit nach Öffnen beachten |
| Kontrollwein (siehe Qualitätssicherung) | 5 L | eingefroren in Portionen |
| Schutzbrille, Nitrilhandschuhe, Labormantel | – | – |

Verbrauch je Messung: ein Test aus dem Kit plus anteilig Leerwert und Kontrolle, eine Küvette, drei bis fünf Pipettenspitzen, wenige Milliliter Wasser.

## Durchführung: einen Enzym-Kit messen

Das Pipettierschema folgt dem Muster des Roche/R-Biopharm-Kits für L-Äpfelsäure. Das Gesamtvolumen von 2,220 mL und das Probevolumen von 0,100 mL stehen in der Gebrauchsanweisung [4]. Die Einzelvolumina sind hier aus dem Fachwissen eingesetzt.

> **Achtung:** Vor der ersten Messung die Einzelvolumina mit dem Beipackzettel Ihrer Packung abgleichen. Andere Hersteller und Formate arbeiten mit anderen Mengen (Megazyme „Liquid Ready“ zum Beispiel mit 2,60 mL Endvolumen [6]).

| In die Küvette pipettieren | Leerwert | Probe |
|---|---|---|
| Lösung 1 (Puffer mit L-Glutamat) | 1,000 mL | 1,000 mL |
| Lösung 2 (NAD⁺) | 0,200 mL | 0,200 mL |
| Wasser | 1,000 mL | 0,900 mL |
| Probelösung | – | 0,100 mL |
| Suspension 3 (GOT) | 0,010 mL | 0,010 mL |
| mischen, nach etwa 3 min E₁ ablesen | | |
| Suspension 4 (L-MDH), startet die Reaktion | 0,010 mL | 0,010 mL |
| mischen, nach Ende der Reaktion E₂ ablesen | | |
| Endvolumen V | 2,220 mL | 2,220 mL |

Schritte:

1. Kit 15–30 min vor Beginn aus dem Kühlschrank nehmen. Die Reagenzien sollen Raumtemperatur (20–25 °C) haben.
2. Fotometer einschalten und 15–30 min warmlaufen lassen. Wellenlänge 340 nm einstellen.
3. Probe entgasen: Jungwein und gärenden Most in einem Kolben 1–2 min kräftig schwenken oder einige Minuten ins Ultraschallbad stellen. Kohlensäure täuscht sonst ein größeres Volumen vor und bildet Blasen in der Küvette.
4. Trübe Proben durch einen Faltenfilter oder Spritzenfilter (0,45 µm) filtrieren oder zentrifugieren.
5. Rotwein verdünnen oder entfärben, wenn der Kit das verlangt. Übliches Vorgehen: etwa 0,2 g PVPP zu 10 mL Wein geben, 1 min schütteln, filtrieren. Menge laut Beipackzettel.
6. Probe so verdünnen, dass ΔE zwischen 0,1 und 1,0 liegt. Bei L-Äpfelsäure entspricht ΔE = 1,0 etwa 0,47 g/L in der Probelösung (siehe Berechnung). Most mit 5 g/L also 1:20 verdünnen: 5,0 mL Most in einen 100-mL-Messkolben, mit Wasser bis zur Marke auffüllen, mischen. Verdünnungsfaktor F notieren.
7. Küvetten oben am Rand beschriften: L (Leerwert), K (Kontrolle), P1, P2 …
8. Nach Schema pipettieren. Reihenfolge einhalten: Puffer, Coenzym, Wasser, Probe, Hilfsenzym. Enzymsuspensionen vor dem Entnehmen nur sanft schwenken, nicht schütteln. Für zähe Suspensionen umgekehrt pipettieren (siehe [Grundlagen Labor](grundlagen-labor.md)).
9. Mit dem Küvettenspatel mischen oder die Küvette mit Parafilm verschließen und zweimal langsam kippen. Keine Blasen erzeugen.
10. Etwa 3 min warten, bis die Anzeige ruhig ist. Nullabgleich nach Beipackzettel (gegen Luft oder Wasser). E₁ aller Küvetten ablesen und notieren.
11. Startreagenz in alle Küvetten geben, mischen, Kurzzeitwecker starten.
12. Nach der im Beipackzettel genannten Zeit E₂ ablesen. Nach 2 min nochmals ablesen. Steigt der Wert weiter (Schleichreaktion), nach Beipackzettel auf den Startzeitpunkt zurückrechnen.
13. ΔE berechnen und auf Plausibilität prüfen: ΔE der Probe zwischen 0,1 und 1,0? Kontrolle im Sollbereich? Wenn nicht, mit anderer Verdünnung wiederholen.
14. Ergebnisse mit Datum, Probe, Verdünnung, Kit-Charge und Kontrollwert in das Laborbuch eintragen.

## Berechnung

### Formel

Für Endpunkttests mit einem Molekül NAD(P)H je Molekül Analyt gilt [4, 8]:

**c = (V × MG × ΔE) / (ε × d × v × 1000)**

| Größe | Bedeutung | Einheit |
|---|---|---|
| c | Konzentration in der Probelösung (verdünnte Probe) | g/L |
| V | Endvolumen in der Küvette | mL |
| MG | Molare Masse des Analyten (L-Äpfelsäure 134,09; L-Milchsäure 90,08; Glucose und Fructose 180,16; Essigsäure 60,05; Acetaldehyd 44,05; NH₃ 17,03) | g/mol |
| ΔE | Extinktionsdifferenz: ΔE Probe − ΔE Leerwert | – |
| ε | Extinktionskoeffizient von NAD(P)H (Tabelle oben) | L/(mmol·cm) |
| d | Schichtdicke | cm |
| v | Probevolumen in der Küvette | mL |
| 1000 | Umrechnung von mg/L in g/L | – |

Konzentration im Wein = c × F (F = Verdünnungsfaktor).

**Herleitung in drei Schritten:**

1. Lambert-Beer: In der Küvette sind ΔE / (ε × d) mmol/L NADH entstanden.
2. Gleiche Stoffmenge Analyt, aber verteilt auf V statt auf v: In der Probelösung sind es ΔE × V / (ε × d × v) mmol/L.
3. Mal molare Masse (mg/mmol) ergibt mg/L, geteilt durch 1000 ergibt g/L.

Bei Kits, die NAD(P)H verbrauchen (Ammonium), ist ΔE = E₁ − E₂. Bildet ein Kit zwei Moleküle NAD(P)H je Molekül Analyt, ist das Ergebnis durch 2 zu teilen. Das steht dann im Beipackzettel.

### Beispiel L-Äpfelsäure (Roche/R-Biopharm-Volumina [4])

Wein 1:10 verdünnt (F = 10). Ablesungen bei 340 nm:

| | E₁ | E₂ | E₂ − E₁ |
|---|---|---|---|
| Leerwert | 0,105 | 0,121 | 0,016 |
| Probe | 0,142 | 0,792 | 0,650 |

ΔE = 0,650 − 0,016 = 0,634

c = (2,220 × 134,09 × 0,634) / (6,3 × 1 × 0,100 × 1000) = 188,7 / 630 = 0,2996 g/L in der Probelösung

L-Äpfelsäure im Wein = 0,2996 × 10 = **3,0 g/L**

Für diesen Kit gilt also kurz: c = 0,4725 × ΔE (g/L in der Probelösung, 340 nm). Megazyme gibt für sein Format mit 2,60 mL Endvolumen den Faktor 0,5534 an [6]. Die eigene Rechnung bestätigt beide Faktoren (2,60 × 134,09 / 630 = 0,5534).

**Gleiche Probe bei 365 nm:** ΔE ist dann nur 0,634 × 3,4 / 6,3 = 0,342. Mit ε = 3,4 ergibt sich c = (2,220 × 134,09 × 0,342) / (3,4 × 0,1 × 1000) = 0,299 g/L – dasselbe Ergebnis bei halbem Signal.

### Beispiel mit Verdünnungskorrektur (Megazyme „Liquid Ready“)

Wird das Startreagenz in größerem Volumen zugegeben, verdünnt es die Küvette. Dann wird E₁ mit dem Faktor df korrigiert [6]:

ΔE = (E₂ − df × E₁)Probe − (E₂ − df × E₁)Leerwert

df = Volumen vor Zugabe des Startreagenzes / Endvolumen. Megazyme nennt für sein Format df ≈ 0,808 bei 2,60 mL Endvolumen [6]; das entspricht 2,10 mL vor der letzten Zugabe (eigene Rückrechnung).

Beispiel: Probe E₁ = 0,412, E₂ = 1,004; Leerwert E₁ = 0,398, E₂ = 0,335.
ΔE = (1,004 − 0,8077 × 0,412) − (0,335 − 0,8077 × 0,398) = 0,6712 − 0,0135 = 0,6577
c = 0,5534 × 0,6577 = 0,364 g/L in der Probelösung.

### Kontrolle mit Standard (Wiederfindung)

Eine Standardlösung mit bekanntem Gehalt wird wie eine Probe gemessen. Wiederfindung = gemessen / Sollwert × 100 %.

Beispiel: Sollwert 0,400 g/L, gemessen 0,392 g/L → Wiederfindung 98 %.

> **Offen:** Welche Wiederfindung noch akzeptabel ist, legt der Kit-Hersteller fest. Ohne Herstellerangabe ist 95–105 % eine verbreitete Laborpraxis (Fachwissen, nicht gegen Quelle geprüft).

## Farbe, Gesamtpolyphenole und Anthocyane

Diese Messungen brauchen kein Enzym, nur das Fotometer.

### Farbintensität und Farbton (Rotwein)

Prinzip nach der OIV-Methode [3]: Man misst die Extinktion des unverdünnten Weins bei 420 nm (gelb-braun), 520 nm (rot) und 620 nm (blau).

1. Wein filtrieren oder zentrifugieren, Kohlensäure entfernen. Nicht verdünnen: Verdünnen löst Farbstoffkomplexe (Kopigmentierung) und verfälscht die Farbe [17].
2. 1-mm-Küvette (Glas oder Quarz) füllen. Nullabgleich gegen Wasser in derselben Küvettenart.
3. E420, E520 und E620 ablesen.
4. Werte auf 10 mm Schichtdicke umrechnen: bei 1-mm-Küvette × 10, bei 2-mm-Küvette × 5.

Farbintensität = E420 + E520 + E620
Farbton = E420 / E520

Beispiel (1-mm-Küvette): E420 = 0,312; E520 = 0,498; E620 = 0,091
Farbintensität = (0,312 + 0,498 + 0,091) × 10 = 9,01
Farbton = 0,312 / 0,498 = 0,63

Der Farbton steigt mit der Alterung, weil Rot abnimmt und Gelb-Braun zunimmt [12]. Bei Weißwein dient E420 in der 10-mm-Küvette als einfaches Maß für Bräunung.

> **Offen:** Code und Wortlaut der OIV-Methode (OIV-MA-AS2-07B) wurden nicht online geprüft. Typische Zahlenwerte für österreichische Rotweinsorten wurden nicht gefunden.

### Gesamtpolyphenole nach Folin-Ciocalteu (OIV-Methode)

Folin-Ciocalteu-Reagenz wird von Phenolen reduziert und färbt sich blau. Die Farbe bei 750 nm ist der Phenolmenge proportional [2, 10].

Reagenzien: Folin-Ciocalteu-Reagenz (gebrauchsfertig gekauft), Natriumcarbonatlösung 20 % (m/V) aus wasserfreiem Na₂CO₃ [2].

1. In einen 100-mL-Messkolben in genau dieser Reihenfolge geben: 1 mL Probe (Rotwein vorher 1:5 verdünnt, Weißwein unverdünnt), 50 mL Wasser, 5 mL Folin-Ciocalteu-Reagenz, 20 mL Natriumcarbonatlösung [2].
2. Mit Wasser bis zur Marke auffüllen, mischen, 30 min stehen lassen [2].
3. Extinktion bei 750 nm in 10-mm-Küvette gegen einen Blindwert messen (Wasser statt Wein) [2].
4. Folin-Index = E × 100 bei Rotwein (1:5 verdünnt), E × 20 bei Weißwein [2].

Beispiel: Rotwein 1:5, E750 = 0,52 → Index 52. Weißwein unverdünnt, E750 = 0,38 → Index 7,6.

Doppelbestimmungen sollen um höchstens eine Indexeinheit voneinander abweichen [2]. Viele Labors geben stattdessen Gallussäure-Äquivalente in mg/L an und kalibrieren mit Gallussäure [11]. Index und Gallussäure-Äquivalente sind nicht direkt vergleichbar. Zucker, SO2 und Ascorbinsäure reduzieren das Reagenz ebenfalls und erhöhen den Wert, besonders bei süßen Weinen [10, 11].

Vereinfacht ohne Reagenz: Die Extinktion bei 280 nm (verdünnter Wein, Quarz- oder UV-Küvette) dient als Gesamtphenol-Index [15, 16].

> **Offen:** Verdünnungsmedium und Korrekturglied der 280-nm-Methode vor Verwendung in [15] oder [16] nachlesen.

### Anthocyane

**SO2-Bleichung (nach Ribéreau-Gayon und Stonestreet):** Anthocyane werden durch Hydrogensulfit entfärbt, andere rote Pigmente kaum. Der Unterschied der Extinktion bei 520 nm mit und ohne Hydrogensulfit ergibt den Anthocyangehalt [12].

1. 1 mL Wein mit 1 mL Ethanol (mit 0,1 % HCl) und 20 mL Salzsäure 2 % mischen.
2. Zwei Röhrchen mit je 10 mL dieser Mischung füllen. Ins erste 4 mL Wasser, ins zweite 4 mL Natriumhydrogensulfit-Lösung 15 % geben.
3. Nach 20 min E520 beider Röhrchen in 10-mm-Küvette messen.
4. Anthocyane (mg/L) = 875 × (E520 Wasser − E520 Hydrogensulfit)

Beispiel: ΔE = 0,420 → 875 × 0,420 = 368 mg/L.

**pH-Differenzmethode (AOAC 2005.02):** Monomere Anthocyane sind bei pH 1,0 farbig und bei pH 4,5 fast farblos. Man misst den verdünnten Wein in beiden Puffern bei 520 nm und 700 nm. Berechnung als Cyanidin-3-glucosid mit MG 449,2 g/mol und ε = 26.900 L/(mol·cm) [14].

A = (E520 − E700) pH 1,0 − (E520 − E700) pH 4,5
Anthocyane (mg/L) = A × MG × Verdünnung × 1000 / (ε × d)

Beispiel: Verdünnung 1:10, A = 0,491 → 0,491 × 449,2 × 10 × 1000 / 26.900 = 82 mg/L (als Cyanidin-3-glucosid).

Beide Methoden messen Verschiedenes und liefern unterschiedliche Zahlen. Vergleichen Sie nur Werte derselben Methode.

> **Offen:** Rezeptur und Faktor 875 der SO2-Bleichung sind Fachwissen und vor Verwendung in [12] nachzulesen.

## Auswertung

| Messgröße | Richt- oder Grenzwert | Was folgt daraus |
|---|---|---|
| Glucose + Fructose | „trocken“ bis 4 g/L, unter Bedingungen bis 9 g/L (Bezeichnungsrecht [29]) | Rechtliche Details in [Grenzwerte](grenzwerte-recht.md); Gärende in [Zucker und Mostgewicht](zucker-mostgewicht.md) |
| L-Äpfelsäure | BSA in der Praxis bei einem Rest in der Größenordnung von 0,1 g/L als abgeschlossen betrachtet | Einzelheiten in [Äpfel-Milchsäure-Gärung](apfel-milchsaeure-bsa.md) |
| L-Milchsäure | aus 1 g Äpfelsäure entstehen 0,67 g Milchsäure (90,08 / 134,09) | Milchsäure deutlich über diesem Wert: Verdacht auf Zuckerabbau durch Bakterien, D-Milchsäure prüfen |
| Essigsäure | EU-Höchstgehalt flüchtige Säure: 18 meq/L (≈ 1,08 g/L als Essigsäure) bei Weiß- und Roséwein, 20 meq/L (≈ 1,20 g/L) bei Rotwein [24] | Steigt der Wert zwischen zwei Messungen deutlich, Ursache suchen; siehe [Flüchtige Säure](fluechtige-saeure.md) |
| YAN (Ammonium-N + NOPA) | Mindestwert etwa 140 mg N/L, Zielwert zuckerabhängig | Nährstoffgabe nach [Stickstoff (YAN)](stickstoff-yan.md) |
| Acetaldehyd | 1 mg/L bindet 1,45 mg/L SO2 | Hoher Wert erklärt hohen SO2-Bedarf; siehe [Schweflige Säure](schweflige-saeure.md) |
| Kupfer | nach Behandlung mit Kupfersalzen höchstens 1 mg/L im Wein [24, 25] | Bei Werten nahe 1 mg/L Labormessung |
| Farbton | junge Rotweine deutlich unter 1; steigt mit dem Alter [12] | Verlauf je Wein über die Zeit verfolgen |

> **Offen:** Der Restgehalt an L-Äpfelsäure, ab dem die BSA als abgeschlossen gilt, wird unterschiedlich angegeben (Fachwissen, nicht gegen Quelle geprüft). Die Rechtswerte für flüchtige Säure, Kupfer und Restzucker wurden bei der Erstellung nicht im Wortlaut geprüft; maßgeblich ist [Grenzwerte](grenzwerte-recht.md) bzw. der aktuelle Text in EUR-Lex.

> **Offen:** Richtwerte für Gluconsäure (gesund oder faul), Eisen (Bruchgefahr) und Kupfer (Kupferbruch bei Weißwein) sind aus dem Fachwissen bekannt, wurden aber nicht gegen eine Quelle geprüft und fehlen deshalb hier.

## Qualitätssicherung

1. **Leerwert in jeder Serie.** Ein ungewöhnlich hoher Leerwert zeigt verdorbene Reagenzien oder verschmutztes Wasser an.
2. **Kontrollwein in jeder Serie.** 5 L eines stabilen, filtrierten Weins in 50-mL-Röhrchen abfüllen und bei −18 °C einfrieren. Zwei Röhrchen von einem akkreditierten Labor analysieren lassen. Bei jeder Serie ein aufgetautes Röhrchen mitmessen und das Ergebnis in eine Kontrollkarte eintragen (Mittelwert, Warngrenze ± 2 Standardabweichungen, Eingriffsgrenze ± 3 Standardabweichungen). Die Standardabweichung ergibt sich nach etwa zehn eigenen Messungen.
3. **Standards.** Viele Kits enthalten eine Standardlösung, zum Beispiel der NOPA-Kit eine Isoleucinlösung mit 140 mg N/L [7]. Bei jeder neuen Kit-Charge und mindestens monatlich mitmessen. Eigener Standard für L-Äpfelsäure: 2,00 g L-Äpfelsäure (Reinheit mindestens 99 %) mit einer Waage mit 0,01 g Auflösung einwiegen, in 1 L Wasser lösen (2,00 g/L), dann 20,0 mL auf 100 mL verdünnen (0,400 g/L). Portionsweise einfrieren.
4. **Doppelbestimmung** bei wichtigen Entscheidungen (Abbruch der BSA, Füllfreigabe). Weichen die Werte um mehr als etwa 5 % voneinander ab, Ursache suchen und wiederholen.
5. **Aufstockung (Standardaddition)** bei unsicheren Proben, etwa Kupfer oder Eisen mit Wasser-Küvettentests: Probe einmal pur und einmal mit bekannter Zugabe messen. Die Zugabe muss sich im Ergebnis wiederfinden. Sonst stört die Weinmatrix.
6. **Pipetten prüfen.** Zehnmal 1000 µL Wasser auf eine Analysenwaage (Auflösung 0,1 mg) pipettieren und wiegen. Bei 20 °C zeigt die Waage für 1000 µL rund 0,997 g an (Dichte 0,998 g/mL, abzüglich Luftauftrieb). Das Verfahren und die Umrechnung mit dem Z-Faktor sind in ISO 8655 beschrieben [26].
7. **Vergleich mit dem Labor.** Zwei- bis dreimal pro Saison dieselbe Probe selbst messen und ins Labor schicken. Die Unterschiede in einer Tabelle sammeln. Weichen die eigenen Werte systematisch in eine Richtung ab, Kit, Pipetten und Fotometer prüfen.

> **Offen:** Die Annahmegrenze von 5 % für Doppelbestimmungen ist eine betriebliche Festlegung aus dem Fachwissen. Kits nennen teils eigene Grenzen in Extinktionseinheiten.

## Wirtschaftlichkeit

Ob sich eigene Analysen lohnen, hängt von drei Größen ab: Fixkosten pro Jahr, Kosten pro Probe und Preis des Labors. Die Gewinnschwelle (Analysen pro Jahr) ist:

**N = Fixkosten pro Jahr / (Laborpreis pro Analyse − eigene Kosten pro Analyse)**

> **Offen:** Österreichische Laborpreise für Einzelparameter konnten bei der Erstellung nicht recherchiert werden. Bitte Preislisten anfordern, etwa beim Bundesamt für Weinbau, an der HBLA und BA für Wein- und Obstbau Klosterneuburg, bei Landwirtschaftskammern und privaten Weinlabors. Labors bieten oft günstige Pakete an, weil sie viele Parameter gleichzeitig mit FTIR-Geräten messen.

Die folgende Rechnung arbeitet deshalb mit Annahmen:

| Annahme | Fotometer + Kits (a) | RQflex (c) |
|---|---|---|
| Anschaffung | 3.000 € Fotometer + 750 € Pipetten + 250 € Zubehör (Annahme) | 1.400 € Gerät [22] |
| Nutzungsdauer | 8 Jahre, Wartung 100 € pro Jahr (Annahme) | 7 Jahre (Annahme) |
| Fixkosten pro Jahr | 600 € | 200 € |
| Material pro Probe | Kit 3,00 € (Annahme) + 0,30 € Küvette und Spitzen; Serie aus 4 Proben + Leerwert + Kontrolle → 4,95 € | Streifen 2,92 € [22] + Kleinmaterial + 20 % Kontrollen → 3,60 € |
| Arbeitszeit pro Probe | 12 min zu 25 €/h = 5,00 € | 5 min = 2,08 € |

Gewinnschwelle in Analysen pro Jahr (eigene Rechnung):

| Laborpreis pro Analyse | (a) ohne Arbeitszeit | (a) mit Arbeitszeit | (c) ohne Arbeitszeit | (c) mit Arbeitszeit |
|---|---|---|---|---|
| 10 € | 119 | lohnt praktisch nicht | 32 | 47 |
| 15 € | 60 | 119 | 18 | 22 |
| 20 € | 40 | 60 | 13 | 14 |
| 25 € | 30 | 40 | 10 | 11 |

Was die Tabelle zeigt:

- Ein Fotometer lohnt sich rein rechnerisch ab einigen Dutzend bis über hundert Analysen pro Jahr. Die Zahl gilt für alle Parameter zusammen, denn das Gerät misst alle.
- Kleine Serien sind teuer: Bei einer einzigen Probe pro Serie kostet das Material 9,90 € statt 4,95 € (Leerwert und Kontrolle fallen trotzdem an). Proben sammeln und gemeinsam messen.
- Kits verfallen. Ein halb verbrauchter Kit, der abläuft, verdoppelt die Kosten pro Test.
- Teststreifen rechnen sich früh, liefern aber nur Orientierungswerte.
- Der größte Nutzen ist oft nicht die Ersparnis, sondern die Zeit: In der BSA- und Gärphase kann man täglich messen und sofort handeln.

## Fehlerquellen und Grenzen

- **Probevolumen v:** Es geht direkt ins Ergebnis ein. 1 % Fehler beim Pipettieren der Probe ergibt 1 % Fehler im Ergebnis. Die kleinen Enzymvolumina sind unkritisch, solange sie im Überschuss vorliegen.
- **Verdünnung:** Fehler beim Verdünnen multiplizieren sich. Messkolben statt Becher verwenden.
- **Temperatur und Zeit:** Zu kalte Reagenzien verlangsamen die Reaktion. E₂ zu früh abgelesen ergibt zu niedrige Werte.
- **Farbe und Trübung:** Rotwein absorbiert bei 340 nm stark. Ist E₁ schon über etwa 1, ist die Messung unsicher. Stärker verdünnen oder entfärben.
- **Kohlensäure:** Blasen in der Küvette streuen Licht.
- **Spezifität:** Kits erfassen nur die L- bzw. D-Form, für die sie gebaut sind.
- **Gerät:** Lampenalterung und Drift verschieben den Nullpunkt. Vor jeder Serie neu abgleichen.
- **Referenzmethoden:** Für Glucose und Fructose ist die enzymatische Methode selbst eine OIV-Methode [1]. Flüchtige Säure (Destillation) und Kupfer (Atomabsorption) haben andere Referenzverfahren; dort ist der Enzym- oder Farbtest nur eine Näherung.

## Sicherheit und Entsorgung

- Kit-Reagenzien enthalten meist geringe Mengen Konservierungsmittel. Manche enthalten Natriumazid. Azidhaltige Lösungen nicht in größeren Mengen in Abflüsse aus Metall gießen, weil sich mit Kupfer oder Blei explosive Azide bilden können. Hinweise im Sicherheitsdatenblatt (SDB) des Kits befolgen.
- OPA-Reagenz (NOPA-Test) ist giftig und kann Allergien auslösen; Ethanol ist entzündlich. SDB beachten.
- Folin-Ciocalteu-Reagenz und Salzsäure sind ätzend bzw. reizend. Natriumcarbonatlösung reizt die Augen. Natriumhydrogensulfit setzt mit Säuren Schwefeldioxid frei.
- Immer Schutzbrille und Nitrilhandschuhe tragen. Nicht mit dem Mund pipettieren. Im Laborbereich nicht essen und trinken.
- Kleine Mengen verbrauchter Testlösungen in einem beschrifteten Sammelkanister sammeln. Betriebe übergeben gefährliche Abfälle einem befugten Sammler; Fragen dazu beantwortet die Abfallberatung des Landes oder der Gemeinde.
- Küvetten und Spitzen nach Gebrauch in den Restmüll, sofern sie keine giftigen Reste enthalten.

> **Offen:** Die GHS-Einstufung der einzelnen Kit-Reagenzien hängt vom Hersteller ab und wurde nicht geprüft. Sie steht im SDB, das jeder Lieferant mitliefern muss.

Stand: November 2026

## Quellen

1. OIV – Internationale Organisation für Rebe und Wein (laufende Ausgabe): Compendium of International Methods of Wine and Must Analysis. OIV, Paris. https://www.oiv.int/node/1975 [online geprüft]
2. OIV: Methode OIV-MA-AS2-10, Folin-Ciocalteu index (Typ IV). In: Compendium of International Methods of Wine and Must Analysis. OIV, Paris. https://www.oiv.int/public/medias/2477/oiv-ma-as2-10.pdf [online geprüft]
3. OIV: Methode OIV-MA-AS2-07B, Chromatic characteristics (Typ I). In: Compendium of International Methods of Wine and Must Analysis. OIV, Paris. [nicht online geprüft]
4. Roche/R-Biopharm (2017): L-Malic acid, UV-method, Art.-Nr. 10139068035, Gebrauchsanweisung. R-Biopharm AG, Darmstadt. https://food.r-biopharm.com/wp-content/uploads/2012/06/roche_ifu_malic-acid-l_en_10139068035_2017-08.pdf – Herstellerangabe, nur technische Daten [online geprüft]
5. R-Biopharm (2026): Enzytec Liquid L-Malic acid, Art.-Nr. E8280, Gebrauchsanweisung (EN, Version 2026-04). R-Biopharm AG, Darmstadt. https://food.r-biopharm.com/wp-content/uploads/E-Liquid_IFU_E8280_L-Malic-acid_EN_2026-04_V3-1.pdf – Herstellerangabe [online geprüft]
6. Megazyme/Neogen: L-Malic Acid Assay Kit (Liquid Ready), K-LMLQR, Assay Protocol. https://www-docs.megazyme.com/documents/Assay_Protocol/K-LMLQR_DATA.pdf – Herstellerangabe [online geprüft]
7. Megazyme/Neogen: Primary Amino Nitrogen Assay Kit (PANOPA), K-PANOPA, Assay Protocol. https://www-docs.megazyme.com/documents/Assay_Protocol/K-PANOPA_DATA.pdf – Herstellerangabe [online geprüft]
8. Bergmeyer, H. U. (Hrsg.) (1983–1986): Methods of Enzymatic Analysis. 3. Auflage, 12 Bände. Verlag Chemie, Weinheim. [nicht online geprüft]
9. Horecker, B. L.; Kornberg, A. (1948): The extinction coefficients of the reduced band of pyridine nucleotides. Journal of Biological Chemistry 175, 385–390. [nicht online geprüft]
10. Singleton, V. L.; Rossi, J. A. (1965): Colorimetry of total phenolics with phosphomolybdic-phosphotungstic acid reagents. American Journal of Enology and Viticulture 16, 144–158. [nicht online geprüft]
11. Waterhouse, A. L. (2002): Determination of total phenolics. In: Current Protocols in Food Analytical Chemistry, Unit I1.1. John Wiley & Sons, New York. [nicht online geprüft]
12. Ribéreau-Gayon, P.; Glories, Y.; Maujean, A.; Dubourdieu, D. (2006): Handbook of Enology, Volume 2: The Chemistry of Wine – Stabilization and Treatments. 2. Auflage. John Wiley & Sons, Chichester. [nicht online geprüft]
13. Ribéreau-Gayon, P.; Dubourdieu, D.; Donèche, B.; Lonvaud, A. (2006): Handbook of Enology, Volume 1: The Microbiology of Wine and Vinifications. 2. Auflage. John Wiley & Sons, Chichester. [nicht online geprüft]
14. Lee, J.; Durst, R. W.; Wrolstad, R. E. (2005): Determination of total monomeric anthocyanin pigment content of fruit juices, beverages, natural colorants, and wines by the pH differential method: collaborative study. Journal of AOAC International 88(5), 1269–1278. [nicht online geprüft]
15. Somers, T. C.; Evans, M. E. (1977): Spectral evaluation of young red wines: anthocyanin equilibria, total phenolics, free and molecular SO2, "chemical age". Journal of the Science of Food and Agriculture 28, 279–287. [nicht online geprüft]
16. Iland, P.; Bruer, N.; Edwards, G.; Weeks, S.; Wilkes, E. (2004): Chemical Analysis of Grapes and Wine: Techniques and Concepts. Patrick Iland Wine Promotions, Campbelltown (Australien). [nicht online geprüft]
17. Boulton, R. (2001): The copigmentation of anthocyanins and its role in the color of red wine: a critical review. American Journal of Enology and Viticulture 52(2), 67–87. [nicht online geprüft]
18. Dukes, B. C.; Butzke, C. E. (1998): Rapid determination of primary amino acids in grape juice using an o-phthaldialdehyde/N-acetyl-L-cysteine spectrophotometric assay. American Journal of Enology and Viticulture 49(2), 125–133. https://www.ajevonline.org/content/49/2/125 [online geprüft]
19. Gusmer Enterprises / CDR: CDR WineLab – Produktbeschreibung und Kitübersicht; CDR Correlation to Reference Laboratories (Abstract, 2022). https://gusmerenterprises.com/catalog/wine/wine-lab-analytical-products/gusmer-labs-services/cdr-winelab und https://www.gusmerenterprises.com/wp-content/uploads/2022/04/CDR-Correlation-to-Reference-Laboratories-Abstract.pdf; Messbereiche laut Vertriebspartner https://claudiovignoli.com/cdr-winelab-touch – Hersteller- und Händlerangaben [online geprüft]
20. Steroglass: HYPERLAB PLUS and basic wine analyzers; Enzymatic and colorimetric kits. https://www.steroglass.it/en/hyperlab-plus-and-basic-wine-analyzers und https://www.steroglass.it/en/enzymatic-and-colorimetric-kits – Herstellerangaben [online geprüft]
21. Hanna Instruments: HI83748 Photometer for the determination of tartaric acid in wine, https://www.hannainstruments.co.uk/food-and-drink/2892-hi-83748-photometer-for-the-determination-of-tartaric-acid-in-wine; Wine Testing Catalog, https://pdf.directindustry.com/pdf/hanna-instruments/hanna-instruments-wine-testing-catalog/9073-29955.html; Determination of Yeast Assimilable Nitrogen, https://blog.hannainst.com/determination-of-yeast-assimilable-nitrogen – Herstellerangaben [online geprüft]
22. Merck/Sigma-Aldrich und Avantor: Reflectoquant Malic Acid Test 1.16128 (Österreich, https://sigmaaldrich.com/AT/de/product/mm/116128), Ammonium Test 1.16892 (https://www.sigmaaldrich.com/product/mm/116892), Total Sugar Test 1.16136 (https://sigmaaldrich.com/BD/en/product/mm/116136), Reflektometer RQflex 20, 1.17246 (https://www.sigmaaldrich.com/FI/en/product/mm/117246; https://www.avantorsciences.com/be/nl/product/23970939/handreflectometer-reflectoquant-rqflex-20). Preise abgerufen November 2026 – Händlerangaben [online geprüft]
23. Thermo Fisher Scientific: GENESYS 30 Visible Spectrophotometer, Broschüre BR52794. https://assets.thermofisher.com/TFS-Assets/MSD/brochures/BR52794-genesys-30-spectrophotometer.pdf – Herstellerangabe [online geprüft]
24. Delegierte Verordnung (EU) 2019/934 der Kommission vom 12. März 2019 (önologische Verfahren), konsolidierte Fassung vom 29.12.2024. https://eur-lex.europa.eu/eli/reg_del/2019/934/2024-12-29/eng [nicht online geprüft] – Fundstelle online gesehen, die hier zitierten Werte (flüchtige Säure, Kupfer) nicht.
25. OIV: International Code of Oenological Practices, Annex „Maximum acceptable limits“. https://www.oiv.int/standards/international-code-of-oenological-practices/annexes/maximum-acceptable-limits [nicht online geprüft] – Seite gesehen, Inhalt nicht.
26. ISO 8655 (Teile 1–7): Piston-operated volumetric apparatus (Kolbenbetätigte Volumenmessgeräte). ISO, Genf. [nicht online geprüft]
27. Galileo Equipos: Refurbished UV/Vis spectrophotometers (Preisbeispiel Gebrauchtgerät). https://www.galileoequipos.com/en/93-used-uv-vis – Händlerangabe [online geprüft]
28. Megazyme/Neogen: L-Lactic Acid Assay Kit, Produktseite (Packungsgrößen). https://secure.megazyme.com/L-Lactic-Acid-Assay-Kit – Herstellerangabe [online geprüft]
29. Delegierte Verordnung (EU) 2019/33 der Kommission vom 17. Oktober 2018 (Bezeichnung und Aufmachung von Weinbauerzeugnissen), Anhang III Teil B (Angaben zum Zuckergehalt), konsolidierte Fassung. EUR-Lex. [nicht online geprüft]
30. Purdue University Cooperative Extension: Concentration of primary amino acids in grape juice (NOPA-Verfahren nach Dukes und Butzke), Arbeitsanleitung. https://ag.purdue.edu/department/hla/extension/winegrapeteam/_docs/nopa98.pdf [online geprüft]
