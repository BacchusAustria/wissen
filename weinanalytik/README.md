# Weinanalytik im eigenen Keller

Welche Analysen ein kleines Weingut selbst machen kann, was sie bringen, wie genau sie sind und wann ein externes Labor besser ist. Jede Methode hat eine eigene Anleitung mit Material, Schritten, Rechenbeispiel und Quellen.

## Kurzfassung

- **Unverzichtbar und billig:** Mostgewicht (Refraktometer, Mostwaage), Gesamtsäure und pH (pH-Meter, Titration), freie und gesamte SO2 (Titration nach Ripper), BSA-Kontrolle (Papierchromatographie), Eiweißstabilität (Wärmetest mit Bentonit-Vorversuch). Damit sind die meisten Entscheidungen im Keller abgesichert.
- **Lohnt sich bei mehreren Weinen:** Alkohol (Ebulliometer oder Destillation), flüchtige Säure (Wasserdampfdestillation), SO2 nach der Belüftungsmethode (genauer bei Rotwein), Weinsteinstabilität (Leitfähigkeit), Mikroskop für Gärung und Hefe.
- **Erst bei vielen Proben:** Fotometer mit Enzymtests (Äpfel- und Milchsäure, Glucose/Fructose, hefeverwertbarer Stickstoff, Essigsäure).
- **Immer ins Labor:** Werte für die staatliche Prüfnummer, Export, Streitfälle und alles in Grenzwertnähe. Eigene Analysen dienen der Steuerung, nicht dem amtlichen Nachweis.
- **Wichtigste Regel:** Die meisten Fehler entstehen bei Probe, Titer und Kalibrierung, nicht bei der Messung. Ein- bis zweimal im Jahr dieselbe Probe parallel im Labor messen lassen.

## Welche Analyse wofür?

| Analyse | Wozu im Betrieb | Methode im Betrieb | Aufwand je Probe | Genauigkeit (Richtwert) | Empfehlung | Anleitung |
|---|---|---|---|---|---|---|
| Mostgewicht, Zucker | Lesezeitpunkt, Gärkontrolle, potenzieller Alkohol | Refraktometer, Mostwaage | 1–5 min | ±0,2–0,5 °KMW | Grundausstattung | [zucker-mostgewicht.md](zucker-mostgewicht.md) |
| Restzucker | Gärende, Geschmacksangabe | Rebelein (Kupfer-Iod), enzymatisch; Teststreifen nur grob | 20–30 min | Rebelein etwa ±0,5 g/L (nicht belegt) | bei halbtrockenen und süßen Weinen | [zucker-mostgewicht.md](zucker-mostgewicht.md), [fotometrie-enzymatik.md](fotometrie-enzymatik.md) |
| Gesamtsäure | Lese, Säurekorrektur, Stil | Titration mit NaOH bis pH 7,0 | ~10 min | ±0,05–0,15 g/L | Grundausstattung | [saeure-ph.md](saeure-ph.md) |
| pH-Wert | SO2-Wirkung, mikrobielle Stabilität, Weinstein | pH-Meter, Zwei-Punkt-Kalibrierung | ~5 min | ±0,02–0,05 | Grundausstattung; wichtigstes Gerät | [saeure-ph.md](saeure-ph.md) |
| Freie und gesamte SO2 | Schutz vor Oxidation und Mikroben, Grenzwert | Ripper (Iod) für Weißwein; Belüftung (A-O) für Rotwein | 5–15 min bzw. 20–30 min | Ripper im Ringversuch ±3–4 mg/L frei | Grundausstattung (Ripper), A-O bei Rotwein | [schweflige-saeure.md](schweflige-saeure.md) |
| BSA-Verlauf | Äpfelsäure abgebaut? | Papierchromatographie; enzymatisch | 30 min Arbeit, 1 Tag Laufzeit | qualitativ, Nachweisgrenze grob 0,1–0,2 g/L | bei jedem Wein mit BSA | [apfel-milchsaeure-bsa.md](apfel-milchsaeure-bsa.md) |
| Flüchtige Säure | Frühwarnung Essigstich, Grenzwert | Wasserdampfdestillation | 30–45 min | etwa ±0,03 g/L | ab mehreren Rotweinen oder Holzfässern | [fluechtige-saeure.md](fluechtige-saeure.md) |
| Alkohol | Etikett, Gärkontrolle | Ebulliometer; Destillation mit Dichtemessung | 15–30 min | Ebulliometer ±0,2–0,3 % vol | sinnvoll ab mehreren Weinen | [alkohol.md](alkohol.md) |
| Hefeverwertbarer Stickstoff (YAN) | Hefenährstoffe gezielt dosieren, Böckser vermeiden | NOPA + Ammonium (Fotometer); Formoltitration nur mit Schutzmaßnahmen | 30–45 min je Serie | gut (enzymatisch) | bei Gärproblemen, Böckser-Neigung | [stickstoff-yan.md](stickstoff-yan.md) |
| Eiweißstabilität | Bentonitbedarf | Wärmetest 80 °C/2 h, Bentonit-Reihe, Trübungsmessung | 1 Tag | gut mit Trübungsmessgerät | jeder Weiß- und Roséwein | [stabilitaetstests.md](stabilitaetstests.md) |
| Weinsteinstabilität | Kristalle in der Flasche vermeiden | Kältetest, Mini-Kontakttest mit Leitfähigkeit | 30 min bis 6 Tage | mittel | vor der Füllung | [stabilitaetstests.md](stabilitaetstests.md) |
| Böckser-Diagnose | H2S, Mercaptane, Disulfide unterscheiden | Kupfer-Vorversuch in Gläsern | 15 min | sensorisch | bei Verdacht | [stabilitaetstests.md](stabilitaetstests.md), [../weinfehler/boeckser.md](../weinfehler/boeckser.md) |
| Hefen, Bakterien | Gärstart, Gärstockung, Verderb | Mikroskop 400–1000×, Zählkammer, Methylenblau | 15–20 min | ab etwa 10⁶ Zellen/mL | sinnvoll bei Spontangärung | [mikrobiologie-mikroskopie.md](mikrobiologie-mikroskopie.md) |
| Füllkontrolle | Keimfreiheit nach Sterilfiltration | Membranfiltration, Nährkarton, Brutschrank | 20 min + 3–14 Tage | qualitativ | bei Weinen mit Restzucker | [mikrobiologie-mikroskopie.md](mikrobiologie-mikroskopie.md) |
| Äpfel-/Milchsäure, Glucose/Fructose, Essigsäure, Acetaldehyd | quantitative Kontrolle | Fotometer und Enzymtests | 20–40 min je Serie | Laborqualität bei sauberem Pipettieren | erst bei vielen Proben | [fotometrie-enzymatik.md](fotometrie-enzymatik.md) |

Die Genauigkeitsangaben sind Richtwerte aus den einzelnen Anleitungen; Belege und Grenzen stehen dort.

## Ausbaustufen

| Stufe | Ausstattung | Analysen |
|---|---|---|
| 1 – Grundausstattung | Refraktometer, Mostwaage, pH-Meter, Bürette und Pipetten, Magnetrührer, Titrationslösungen, Papierchromatographie, Wasserbad und Trübungsbeurteilung | Mostgewicht, Gesamtsäure, pH, freie und gesamte SO2 (Ripper), BSA, Eiweißstabilität |
| 2 – erweitert | Ebulliometer, Wasserdampfdestillation, A-O-Apparatur, Trübungsmessgerät, Leitfähigkeitsmessgerät, Mikroskop | zusätzlich Alkohol, flüchtige Säure, SO2 in Rotwein, Weinsteinstabilität, Hefekontrolle |
| 3 – Fotometrie | UV-fähiges Fotometer, Kolbenhubpipetten, Enzymtests | zusätzlich Äpfel- und Milchsäure, Restzucker, YAN, Essigsäure, Acetaldehyd |

Preise und Bezugsquellen: [einkaufsliste.md](einkaufsliste.md).

## Wann welche Analyse im Weinjahr?

| Zeitpunkt | Analysen |
|---|---|
| Reifebeprobung (ab etwa 4 Wochen vor der Lese) | Mostgewicht, Gesamtsäure, pH; Beerenprobe nach Schema |
| Lese, Most | Mostgewicht, Gesamtsäure, pH, YAN; freie SO2 bei Maischeschwefelung |
| Gärung | Dichte bzw. Mostgewicht täglich, Temperatur, Geruch (Böckser!), bei Bedarf Mikroskop |
| Gärende | Restzucker, flüchtige Säure, freie SO2 nach dem ersten Schwefeln |
| BSA | Papierchromatographie wöchentlich bis zum Abbau der Äpfelsäure |
| Ausbau | freie SO2 und pH monatlich, flüchtige Säure bei Holzfässern, Geruch und Verkostung |
| Vor der Füllung | Eiweiß- und Weinsteinstabilität, freie und gesamte SO2, Alkohol, Restzucker, Gesamtsäure, pH; Laboranalyse für die Prüfnummer |
| Nach der Füllung | Füllkontrolle (Keime), freie SO2 in der Flasche |

Die Laborgrundlagen (Probenahme, Pipettieren, Titer, Laborjournal, Sicherheit) stehen in [grundlagen-labor.md](grundlagen-labor.md). Grenzwerte, Prüfnummer und Bio-Regeln stehen in [grenzwerte-recht.md](grenzwerte-recht.md) und [../kellerwirtschaft/bio-weinbereitung.md](../kellerwirtschaft/bio-weinbereitung.md).

## Dateien

| Datei | Inhalt |
|---|---|
| [grundlagen-labor.md](grundlagen-labor.md) | Laborplatz, Probenahme, Volumenmessung, Maßlösungen und Titer, Qualitätssicherung, Laborjournal, Analysenplan, Sicherheit |
| [zucker-mostgewicht.md](zucker-mostgewicht.md) | Reifebeprobung, Refraktometer, Mostwaage, Umrechnung °KMW/°Oe/°Brix, Gärkontrolle, Restzucker, Geschmacksangaben, Mindestmostgewichte |
| [alkohol.md](alkohol.md) | Ebulliometer, Destillation mit Dichtemessung, Vinometer, Extrakt, Etikettentoleranz |
| [saeure-ph.md](saeure-ph.md) | Gesamtsäure, pH, Pufferkapazität, Säurekorrektur mit Vorversuch, Rechtsrahmen |
| [fluechtige-saeure.md](fluechtige-saeure.md) | Wasserdampfdestillation, Korrekturen, Grenzwerte |
| [apfel-milchsaeure-bsa.md](apfel-milchsaeure-bsa.md) | Papierchromatographie, enzymatische Kontrolle des BSA |
| [schweflige-saeure.md](schweflige-saeure.md) | Ripper, Belüftungsmethode, molekulare SO2, Zugabe berechnen, Höchstwerte |
| [stickstoff-yan.md](stickstoff-yan.md) | Hefeverwertbarer Stickstoff, Formoltitration, NOPA, Nährstoffgabe |
| [fotometrie-enzymatik.md](fotometrie-enzymatik.md) | Fotometer, Enzymtests, Wirtschaftlichkeit |
| [mikrobiologie-mikroskopie.md](mikrobiologie-mikroskopie.md) | Mikroskop, Hefezählung, Vitalität, Bakterien, Füllkontrolle |
| [stabilitaetstests.md](stabilitaetstests.md) | Eiweiß-, Weinstein-, Metall-, Oxidations- und Farbstoffstabilität, Schönungsvorversuche, Kupfer-Vorversuch |
| [grenzwerte-recht.md](grenzwerte-recht.md) | Rechtlich relevante Analysenwerte, Weinkategorien, Prüfnummer, Bio, Kennzeichnung |
| [einkaufsliste.md](einkaufsliste.md) | Geräte, Glas, Chemikalien nach Ausbaustufen mit Preisrahmen |

Stand: November 2026
