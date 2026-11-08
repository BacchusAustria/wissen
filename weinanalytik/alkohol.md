# Alkohol

Diese Datei beschreibt, wie ein Weingut den Alkoholgehalt selbst bestimmen kann: durch Destillation mit anschließender Dichtemessung (Referenzprinzip der OIV), mit dem Ebulliometer und mit einfachen Hilfsmitteln. Dazu kommen die Zusammenhänge zwischen Alkohol, Dichte und Extrakt, die Berechnung aus dem Zuckerabbau und die Toleranz für die Etikettangabe.

Grundlagen zu Probenahme, Volumenmessung und Sicherheit: [Laborpraxis: Grundlagen](grundlagen-labor.md). Mostgewicht und potenzieller Alkohol: [Zucker und Mostgewicht](zucker-mostgewicht.md).

## Kurzfassung

- **Referenzprinzip:** Wein mit Kalkmilch alkalisch machen, Alkohol abdestillieren, Destillat bei 20 °C auf das Ausgangsvolumen auffüllen und dessen Dichte messen [1]. Mit einem guten Alkoholometer (Teilung 0,1 % vol) ist das in einem Betriebslabor machbar und auch für Süßweine geeignet. Zeitbedarf etwa 1,5 Stunden.
- **Ebulliometer:** Misst den Siedepunkt; schnell (15 Minuten) und für trockene Weine laut Herstellerangaben auf etwa ± 0,1 % vol genau [13]. Zucker täuscht zu wenig Alkohol vor; süße Weine verdünnen oder destillieren. Der Nullpunkt hängt vom Luftdruck ab und muss bei jeder Messserie neu bestimmt werden.
- **Ungeeignet für genaue Werte:** Vinometer, Handrefraktometer [9] und tragbare Dichtemessgeräte mit ± 0,001 g/cm³. Die Berechnung aus dem Zuckerabbau ist nur auf ± 0,5–1 % vol genau.
- **Etikett:** Angabe in ganzen oder halben % vol; erlaubte Abweichung vom Analysenwert ± 0,5 % vol, für bestimmte Erzeugnisse ± 0,8 % vol (VO (EU) 2019/33, Art. 44) [5]. Für die Etikettangabe einen Laborwert verwenden.
- **Extrakt:** Aus Weindichte und Alkohol lässt sich der Gesamtextrakt berechnen (Formel nach Tabarié) [4]; das dient als Plausibilitätskontrolle.

## 1. Wozu?

- **Etikett und Prüfnummer:** Der vorhandene Alkoholgehalt muss auf dem Etikett stehen und zur amtlichen Analyse passen (Abschnitt 9).
- **Kategorien und Grenzen:** Landwein muss zum Beispiel mindestens 8,5 % vol vorhandenen Alkohol haben [8]. Für Kabinett gilt eine Obergrenze (Abschnitt 9).
- **Kellerentscheidungen:** Verschnitt auf einen Ziel-Alkoholgehalt, Kontrolle der Gärung, mikrobiologische Stabilität (Alkohol hemmt viele Mikroorganismen).
- **Plausibilität:** Alkohol, Restzucker und Dichte müssen zueinander passen (Abschnitt 8).

### Begriffe

| Begriff | Bedeutung |
|---|---|
| Vorhandener Alkoholgehalt | Volumen reinen Alkohols bei 20 °C in 100 Volumen Wein, angegeben in % vol [7, 23] |
| Potenzieller Alkoholgehalt | Alkohol, der aus dem vorhandenen Zucker noch entstehen könnte; 16,83 g/L Zucker = 1 % vol [7, 22] |
| Gesamtalkoholgehalt | vorhandener plus potenzieller Alkoholgehalt [7] |
| Alkohol in g/L | % vol × 7,89 (Dichte von Ethanol bei 20 °C: 0,78924 g/mL [20]); 12,5 % vol = 98,7 g/L |
| Massenprozent | % vol × 0,78924 : Dichte des Weines; 12 % vol entsprechen bei einer Weindichte von 0,9925 etwa 9,5 Massenprozent (eigene Rechnung) |

*Beispiel Gesamtalkohol (eigene Rechnung):* Ein Süßwein mit 11,5 % vol vorhandenem Alkohol und 60 g/L Restzucker hat einen Gesamtalkoholgehalt von 11,5 + 60 : 16,83 = 15,1 % vol.

## 2. Methoden im Überblick

Genauigkeitsangaben ohne Quellenangabe sind Abschätzungen und nicht belegt.

| Methode | Prinzip | Genauigkeit | Zeit | Kosten | Eignung im Betrieb |
|---|---|---|---|---|---|
| Destillation + Alkoholometer | Dichte des Destillats mit geeichtem Aräometer | etwa ± 0,1–0,2 % vol bei sorgfältiger Arbeit | ca. 1,5 h | €€ | **empfohlen**, auch für Süßweine |
| Destillation + Pyknometer | Dichte des Destillats durch Wägung [1] | sehr genau, aber nur mit Analysenwaage | ca. 2 h | €€ bis €€€ | nur mit Analysenwaage (0,1 mg) |
| Destillation + Biegeschwinger-Dichtemessgerät | elektronische Dichtemessung | sehr genau (Laborgerät) | ca. 1,5 h | €€€ | Labor, größere Betriebe |
| Ebulliometer | Siedepunkt von Wein und Wasser | ± 0,1 % vol bei trockenen Weinen laut Herstellerangabe [13] | 15 min | €€ | **empfohlen** für trockene Weine |
| Vinometer | Steighöhe in einer Kapillare | grob | 2 min | € | nur Orientierung bei trockenen Weinen |
| Handrefraktometer | Lichtbrechung | ungeeignet [9] | – | – | nein |
| Infrarot-Analysatoren (NIR, FTIR) | Spektrum, Kalibriermodell | gut, wenn gut kalibriert | Minuten | €€€ | Labor |
| Berechnung aus dem Zuckerabbau | Mostgewicht, Restzucker, Ausbeute | ± 0,5–1 % vol | – | – | nur Planung |

Preisklassen grob geschätzt, nicht geprüft: € unter 50 Euro, €€ 50–500 Euro, €€€ über 500 Euro.

## 3. Destillation mit Dichtemessung (Referenzprinzip)

### 3.1 Prinzip

Die OIV-Methode OIV-MA-AS312-01A bestimmt den Alkoholgehalt bei 20 °C über ein Destillat [1]: Der Wein wird mit einer Calciumhydroxid-Suspension (Kalkmilch) alkalisch gemacht, damit flüchtige Säuren und schweflige Säure als Salze im Kolben bleiben. Dann wird der Alkohol abdestilliert. Das Destillat wird mit Wasser auf das ursprüngliche Volumen aufgefüllt und ist dann ein reines Alkohol-Wasser-Gemisch mit demselben Alkoholgehalt wie der Wein. Zucker, Säuren und Extrakt stören nicht mehr. Aus der Dichte des Destillats ergibt sich der Alkoholgehalt über die internationalen Alkoholtafeln [1, 20]. Die OIV beschreibt die Messung des Destillats mit dem Pyknometer als Referenz; Aräometrie (Alkoholometer) und Refraktometrie des Destillats sind als einfachere Verfahren (Typ IV) beschrieben, mit Messung bei 20 °C oder Korrektur über Tabellen [2].

### 3.2 Material

| Artikel | Spezifikation | Hinweis |
|---|---|---|
| Rundkolben | 500 mL oder 1 L, Normschliff | |
| Destillationsaufsatz mit Tropfenfänger | passend zum Kolben | verhindert, dass Schaum und Spritzer übergehen |
| Liebigkühler | mindestens 30 cm | Kühlwasser im Gegenstrom |
| Vorstoß (Auslaufrohr) | lang genug, um in die Vorlage einzutauchen | |
| Heizpilz oder Heizplatte mit Sandbad | regelbar | offene Flammen vermeiden |
| Stativ, Klemmen, Schliffklemmen | | Apparatur spannungsfrei aufbauen |
| Messkolben | 200 mL Klasse A (oder 250 mL, wenn das Alkoholometer mehr Flüssigkeit braucht) | dient zum Abmessen und als Vorlage |
| Calciumhydroxid-Suspension 2 mol/L (Kalkmilch) | 10 mL je 200 mL Wein [1] | Herstellung siehe unten |
| Siedesteinchen | | gegen Siedeverzug |
| Antischaummittel (Silikonemulsion) | wenige Tropfen | nur bei stark schäumenden Proben (eigene Empfehlung) |
| Wasserbad 20 °C, Thermometer 0,1 °C | | |
| Eiswasser oder kaltes Wasser für die Vorlage | | verringert Alkoholverlust |
| Alkoholometer | Messbereich für Wein (z. B. 0–20 % vol oder 0–10 und 10–20 % vol), Teilung 0,1 % vol, Bezugstemperatur 20 °C, möglichst mit Prüfschein | Alkoholometer für Spirituosen (Teilung 1 % vol) sind ungeeignet |
| Standzylinder | passend zum Alkoholometer | Spindel muss frei schwimmen |
| alternativ: Pyknometer 50 mL und Analysenwaage 0,1 mg | | Abschnitt 3.6 |

**Kalkmilch herstellen:** Die OIV beschreibt die Herstellung aus etwa 120 g gebranntem Kalk (Calciumoxid), auf den vorsichtig 1 L Wasser von 60–70 °C gegossen wird [1]. Einfacher und sicherer ist es, 148 g Calciumhydroxid (gelöschter Kalk) mit Wasser auf 1 L aufzufüllen (eigene Rechnung: 2 mol/L × 74,09 g/mol). Calciumhydroxid löst sich kaum; die Suspension vor jeder Entnahme kräftig schütteln.

> **Achtung:** Gebrannter Kalk reagiert mit Wasser unter starker Erhitzung und kann spritzen. Kalk und Kalkmilch verursachen schwere Augenschäden. Schutzbrille und Handschuhe tragen.

### 3.3 Apparatur prüfen

Die OIV lässt jede Destillationsapparatur zu, die folgende Prüfung besteht: Ein Ethanol-Wasser-Gemisch mit 10 % vol wird fünfmal hintereinander destilliert. Nach der fünften Destillation muss das Destillat noch mindestens 9,9 % vol haben; je Destillation dürfen also höchstens 0,02 % vol verloren gehen [1].

Für ein Betriebslabor praktikabler (eigene Empfehlung): Einen Wein, dessen Alkoholgehalt ein akkreditiertes Labor bestimmt hat, dreimal destillieren und messen. Die Mittelwerte sollten höchstens 0,1 % vol vom Laborwert abweichen. Diese Prüfung bei jeder neuen Apparatur und einmal pro Saison wiederholen.

### 3.4 Durchführung

1. Wein entgasen (Vakuum, siehe [Laborpraxis](grundlagen-labor.md), Abschnitt 4) und auf 20 °C temperieren.
2. Messkolben 200 mL bei 20 °C genau bis zur Marke füllen.
3. Wein in den Rundkolben gießen. Den Messkolben viermal mit je 5 mL Laborwasser ausspülen und das Spülwasser ebenfalls in den Rundkolben geben [24].
4. 10 mL gut geschüttelte Kalkmilch und einige Siedesteinchen zugeben; bei schäumenden Weinen 1–2 Tropfen Antischaummittel.
5. Apparatur zusammenbauen. Das Destillat wird im selben 200-mL-Messkolben aufgefangen, mit dem der Wein abgemessen wurde. In diesen Kolben (Vorlage) einige Milliliter Laborwasser geben (z. B. 10 mL); das Auslaufrohr muss bis zum Boden reichen und eintauchen [24]. Die Vorlage in kaltes Wasser oder Eiswasser stellen.
6. Kühlwasser **vor** dem Heizen aufdrehen.
7. Gleichmäßig erhitzen und zügig, aber ohne Überschäumen destillieren.
8. Destillieren, bis drei Viertel des Ausgangsvolumens (rund 150 mL) übergegangen sind [24]. Der Alkohol geht zuerst über; danach ist der Rückstand praktisch alkoholfrei.
9. Heizung abschalten, Vorlage abnehmen, das Auslaufrohr mit wenig Laborwasser in die Vorlage abspülen.
10. Vorlage 30 Minuten im Wasserbad auf 20 °C temperieren.
11. Mit Laborwasser von 20 °C genau bis zur Marke auffüllen, verschließen und gründlich mischen.
12. Dichte messen: mit dem Alkoholometer (Abschnitt 3.5) oder dem Pyknometer (Abschnitt 3.6).
13. Doppelbestimmung: zweite Destillation mit neuer Probe.

Die Schritte 3, 5 und 8 sind gegen die frühere EU-Referenzmethode geprüft (VO (EWG) Nr. 2676/90, Anhang Kapitel 3, Nr. 3.4), auf die die Kommission 2010 für die OIV-Methode OIV-AS-312-01 verwiesen hat [24]. Dort steht außerdem: Die Temperatur des aufgefüllten Destillats soll höchstens ± 2 °C von der Ausgangstemperatur des Weins abweichen.

> **Offen:** Ob die aktuelle OIV-Fassung OIV-MA-AS312-01A in diesen Einzelheiten von der Fassung 2676/90 abweicht, wurde nicht im OIV-Original gelesen (oiv.int war nicht erreichbar) [1].

### 3.5 Messen mit dem Alkoholometer

1. Standzylinder mit etwas Destillat ausspülen, dann ohne Schaum füllen.
2. Sauberes, trockenes Alkoholometer am oberen Ende fassen und langsam eintauchen; leicht andrehen.
3. Temperatur im Zylinder messen.
4. In Augenhöhe an der Flüssigkeitsoberfläche ablesen (Angabe auf der Spindel beachten).
5. Ergebnis: Alkoholgehalt des Destillats = Alkoholgehalt des Weines, weil das Destillat auf das Ausgangsvolumen aufgefüllt wurde.

**Temperatur:** Alkoholometer sind auf 20 °C justiert. Bei anderer Temperatur die Korrekturtabelle verwenden (Tabelle des Herstellers oder die von der OIV vorgesehenen Tabellen für Alkohol-Wasser-Gemische [2, 3]). Die OIV verlangt für die Messung bei Umgebungstemperatur ein Thermometer mit einer Auflösung von mindestens 0,05 °C [2].

> **Offen:** Eigene Abschätzung aus der Wärmeausdehnung: Die Anzeige ändert sich um rund 0,2 % vol je °C (wärmer = Anzeige zu hoch). Schon 1 °C Abweichung ist für die Etikettangabe relevant. Am besten bei 20,0 ± 0,5 °C messen.

### 3.6 Messen mit dem Pyknometer

Ein Pyknometer ist ein Glasgefäß mit genau reproduzierbarem Volumen.

1. Leeres, trockenes Pyknometer wiegen: m0.
2. Mit Laborwasser von 20 °C füllen, verschließen, außen trocknen, wiegen: m1.
3. Leeren, mit Destillat spülen, mit Destillat von 20 °C füllen, wiegen: m2.
4. Dichte des Destillats: ρ = (m2 − m0) : (m1 − m0) × 0,99820 g/mL.
5. Alkoholgehalt aus der Dichte über die Alkoholtafel ablesen [1, 20].

**Wie genau muss die Waage sein? (eigene Rechnung)** Die Dichte des Destillats ändert sich im Bereich 10–14 % vol um etwa 0,00117 g/mL je % vol.

| Pyknometer | Waage (Teilung) | Unsicherheit der Dichte | entspricht |
|---|---|---|---|
| 50 mL | 0,0001 g | ± 0,000002 g/mL | vernachlässigbar |
| 50 mL | 0,001 g | ± 0,00002 g/mL | ± 0,02 % vol |
| 100 mL | 0,01 g | ± 0,0001 g/mL | ± 0,09 % vol |
| 50 mL | 0,01 g | ± 0,0002 g/mL | ± 0,17 % vol |

Ein Messkolben als Ersatz-Pyknometer ist ungeeignet: Schon 0,02 mL Abweichung beim Einstellen der Marke auf 100 mL ergeben ± 0,0002 g/mL bzw. ± 0,17 % vol.

**Orientierungswerte Dichte → Alkohol:**

| % vol | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
|---|---|---|---|---|---|---|---|---|---|
| ρ20 Destillat (g/mL) | 0,9872 | 0,9860 | 0,9848 | 0,9836 | 0,9824 | 0,9812 | 0,9801 | 0,9790 | 0,9779 |

> **Offen:** Diese Werte sind eigene Umrechnungen aus Tabellenwerten für Ethanol-Wasser-Gemische (Dichte nach Massenprozent [19], aus dem Fachwissen, nicht online geprüft). Sie können in der vierten Nachkommastelle abweichen, das sind bis zu 0,2 % vol. Für Ergebnisse die amtlichen Alkoholtafeln (OIML R 22, OIV) verwenden [1, 20].

### 3.7 Fehlerquellen

| Fehler | Wirkung | Abhilfe |
|---|---|---|
| Alkoholverlust (undichte Schliffe, warme Vorlage, Auslauf nicht eingetaucht) | zu wenig Alkohol | Apparatur prüfen (3.3), Vorlage kühlen |
| Schaum oder Spritzer gehen über | Extrakt im Destillat, Dichte zu hoch, Alkohol zu niedrig | Tropfenfänger, langsamer heizen, Antischaummittel |
| Zu wenig destilliert | Alkohol bleibt im Kolben | mindestens drei Viertel abdestillieren |
| Volumen nicht bei 20 °C eingestellt | Fehler bei Auffüllen und Messen | Wasserbad 20 °C |
| Kalkmilch vergessen | flüchtige Säure und SO2 im Destillat | 10 mL Kalkmilch |
| CO2 in der Probe | Volumenfehler beim Abmessen | entgasen |
| Alkoholometer schmutzig oder fettig, Luftbläschen | Anzeige falsch | reinigen, andrehen |

## 4. Ebulliometer

### 4.1 Prinzip

Ein Alkohol-Wasser-Gemisch siedet tiefer als Wasser, und zwar umso tiefer, je mehr Alkohol es enthält. Das Ebulliometer misst den Siedepunkt von Wasser (Nullpunkt) und den des Weines. Eine Rechenscheibe ordnet der Differenz den Alkoholgehalt zu. Ein Rückflusskühler verhindert, dass beim Sieden Alkohol entweicht [15–17].

Der Siedepunkt von Wasser hängt vom Luftdruck ab: rund 0,28 °C je 10 hPa (eigene Rechnung nach Clausius-Clapeyron). Deshalb muss der Nullpunkt bei jeder Messserie neu bestimmt werden [14].

> **Offen:** Nach eigener Abschätzung aus Siedediagrammen von Ethanol-Wasser-Gemischen sinkt der Siedepunkt im Weinbereich um etwa 0,45–0,5 °C je % vol. Ein Wetterumschwung um 10 hPa ohne neuen Nullpunkt würde dann etwa 0,6 % vol Fehler verursachen. Werte nicht gegen eine Quelle geprüft.

### 4.2 Material

- Ebulliometer (Siedekessel, Rückflusskühler, Thermometer mit 0,05–0,1 °C Teilung oder Digitalthermometer, Spiritusbrenner oder elektrische Heizung, Rechenscheibe), zum Beispiel nach Dujardin-Salleron.
- Messzylinder oder Pipetten für Probe und Verdünnungswasser, Laborwasser, kaltes Kühlwasser.

### 4.3 Durchführung

Die Anleitung des Herstellers ist maßgeblich; der folgende Ablauf zeigt die Grundschritte.

1. **Nullpunkt:** Kessel mit der vorgeschriebenen Menge Laborwasser füllen, Thermometer einsetzen, heizen. Ablesen, sobald die Temperatur 30 Sekunden lang unverändert bleibt. Die Rechenscheibe auf diesen Siedepunkt einstellen [14].
2. Kessel entleeren, mit wenig Wein ausspülen.
3. Vorgeschriebene Menge entgasten Wein einfüllen, Kühler mit kaltem Wasser füllen, heizen.
4. Ablesen, sobald die Temperatur stabil ist.
5. Alkoholgehalt an der Rechenscheibe ablesen.
6. Doppelbestimmung. Den Nullpunkt mindestens zu Beginn jeder Messserie und bei Wetterumschwung neu bestimmen.

### 4.4 Süße Weine

Gelöster Zucker und Extrakt erhöhen den Siedepunkt; das Ebulliometer zeigt dann zu wenig Alkohol an. Herstellerangaben und Nachschlagewerke nennen unterschiedliche Regeln:

- Sehr süße Weine 1 : 1 mit Wasser verdünnen und das Ergebnis verdoppeln [14].
- So weit verdünnen, dass der Zuckergehalt unter 2 % (20 g/L) liegt [12].
- Ein elektronisches Gerät rechnet mit Korrekturen für Zuckerklassen (trocken bis 5 g/L, süß bis 200 g/L) [13].

*Größenordnung (eigene Abschätzung, ideale Siedepunkterhöhung):* 20 g/L Zucker erhöhen den Siedepunkt um etwa 0,06 °C, das sind rund 0,1 % vol zu wenig Alkohol; 50 g/L um etwa 0,15 °C, rund 0,3 % vol. Verdünnen halbiert den Zuckereinfluss, verdoppelt aber den Ablesefehler. Für Weine mit deutlicher Restsüße ist die Destillation (Abschnitt 3) die bessere Methode; auch ein Händler weist darauf hin, dass Ebulliometer bei hohem Restzucker ungenau sind [12, 13].

### 4.5 Genauigkeit und Fehlerquellen

- Herstellerangabe für ein elektronisches Gerät: ± 0,1 % vol im Bereich 0–15 % vol, ± 0,2 % vol im Bereich 15–25 % vol [13]. In der Praxis hängen die Werte stark von Nullpunkt und Sorgfalt ab.
- Fehlerquellen: alter Nullpunkt (Luftdruck), Zucker und Extrakt, Schaum und Trub, warmes Kühlwasser (Alkoholverlust), Thermometer nicht geprüft.
- Kontrolle: regelmäßig einen Wein mit Laborwert mitmessen ([Laborpraxis](grundlagen-labor.md), Abschnitt 7.6).

## 5. Vinometer

Das Vinometer ist ein Glasröhrchen mit Trichter und feiner Kapillare. Man füllt Wein ein, bis er unten austritt, dreht das Röhrchen um und liest ab, wo die Flüssigkeitssäule stehen bleibt. Die Steighöhe hängt von Oberflächenspannung und Zähigkeit ab, die der Alkohol verändert. Zucker und Extrakt verändern beide Größen ebenfalls; das Vinometer funktioniert deshalb nur bei trockenen Weinen halbwegs und liefert auch dort nur eine grobe Orientierung (Genauigkeit nicht belegt). Für Etikett, Prüfnummer oder Verschnittberechnungen ist es ungeeignet.

## 6. Elektronische Geräte und Infrarot

- **Biegeschwinger-Dichtemessgeräte** messen die Dichte über die Schwingungsfrequenz eines mit Probe gefüllten U-Rohres. Laborgeräte sind genau genug, um den Alkohol im Destillat zu bestimmen (nicht online geprüft). **Tragbare Geräte** mit einer Genauigkeit von ± 0,001 g/cm³ (typische Herstellerangabe, nicht geprüft) sind dafür zu ungenau: 0,001 g/cm³ entsprechen rund 0,85 % vol (eigene Rechnung). Sie eignen sich aber gut für die Gärkontrolle.
- **Infrarot-Analysatoren** (Nahinfrarot, Fourier-Transform-Infrarot) messen Alkohol und weitere Größen in Minuten. Sie brauchen eine Kalibrierung mit Referenzwerten und kosten so viel, dass sie sich für ein Familienweingut kaum lohnen. Viele Weinlabore arbeiten damit; ihre Ergebnisse sind für die Betriebsplanung gut geeignet.
- **Enzymatische Ethanolbestimmung** ist mit Testkits und Fotometer möglich, erfordert aber starke Verdünnung (siehe [Fotometrie und Enzymatik](fotometrie-enzymatik.md)).

**Wann lohnt sich was?** Für die meisten Kleinbetriebe genügen Ebulliometer oder Destillation mit Alkoholometer für die eigene Kontrolle, und für Etikett und Prüfnummer ein externes Labor.

## 7. Alkohol aus dem Zuckerabbau berechnen

**Formel:** Alkohol (% vol) ≈ (Zucker im Most − Restzucker) in g/L : Ausbeutefaktor in g/L je % vol.

**Ausbeute (eigene Rechnung):**

| Annahme | g Zucker je 1 % vol | Anteil der theoretischen Ausbeute |
|---|---|---|
| Theorie nach der Gärgleichung (180,16 g Zucker → 2 × 46,07 g Ethanol) | 15,4 | 100 % |
| Konvention in EU-Recht und OIV-Tabelle [7, 22] | 16,83 | 91,7 % |
| DLR-Schätzformel: 0,475 g Alkohol je g Zucker [10] | 16,6 | 93 % |

Die tatsächliche Ausbeute ist geringer als die theoretische, weil die Hefe einen Teil des Zuckers für Wachstum, Glycerin und andere Nebenprodukte verwendet und weil mit dem Gärgas etwas Alkohol entweicht [18]. Wie viel, hängt von Hefe, Temperatur, Nährstoffen und Gärführung ab.

*Rechenbeispiel (eigene Rechnung):* Most mit 19,5 °KMW (96,9 °Oe), vergoren bis 3 g/L Restzucker.

| Zuckerschätzung (siehe [Zucker und Mostgewicht](zucker-mostgewicht.md), Abschnitt 5.3) | Faktor 16,0 | Faktor 16,83 | Faktor 18,0 |
|---|---|---|---|
| Variante A: 213 g/L | 13,2 % vol | 12,5 % vol | 11,7 % vol |
| Variante C: 233 g/L | 14,4 % vol | 13,7 % vol | 12,8 % vol |

Schon der Nichtzuckeranteil des Mostes schwankt zwischen Jahrgängen so stark, dass bei gleichem Mostgewicht rund 0,6 % vol Unterschied entstehen können [11]. Die Spanne von 11,7 bis 14,4 % vol zeigt: Die Berechnung taugt zur Planung (Verschnitt, Anreicherung, Sortenvergleich), nicht für das Etikett. Wer Mostgewicht, Restzucker und gemessenen Alkohol jeder Partie notiert, kennt nach einigen Jahrgängen den eigenen Faktor. Eine Anreicherung muss in der Rechnung zusätzlich berücksichtigt werden. In Deutschland wurde die amtliche Tabelle zur Ermittlung des natürlichen Alkoholgehalts aus dem Mostgewicht gestrichen [10].

## 8. Alkohol, Dichte und Extrakt

### 8.1 Gesamtextrakt nach Tabarié

Die Dichte eines Weines setzt sich zusammen aus der Dichte seines Alkohol-Wasser-Anteils (kleiner als 1) und dem Beitrag der gelösten Stoffe (Extrakt; größer als 1). Die Formel nach Tabarié trennt beide [4]:

d_R = d_W − d_A + 1,000

- d_W: relative Dichte des Weines bei 20 °C (Pyknometer, Biegeschwinger oder genaues Aräometer),
- d_A: relative Dichte eines Alkohol-Wasser-Gemisches mit dem Alkoholgehalt des Weines (Alkoholtafel oder Destillat aus Abschnitt 3),
- d_R: relative Dichte des „entalkoholisierten“ Weines.

Aus d_R ergibt sich der Gesamtextrakt in g/L über eine Tabelle der OIV [4]. Die OIV-Methode korrigiert zusätzlich für die flüchtige Säure (nicht online geprüft). **Näherung (eigene Rechnung aus der Saccharose-Tabelle [19]):** je 0,001 über 1,000 etwa 2,58 g/L Extrakt; d_R = 1,010 entspricht etwa 25,8 g/L.

*Rechenbeispiel (eigene Rechnung):* Wein mit d_W = 0,9925 und 12,5 % vol. d_A ≈ 0,9836 (Orientierungswert aus Abschnitt 3.6, als relative Dichte). d_R = 0,9925 − 0,9836 + 1,000 = 1,0089. Gesamtextrakt ≈ 8,9 × 2,58 ≈ 23,0 g/L.

### 8.2 Zuckerfreier Extrakt

Zuckerfreier Extrakt = Gesamtextrakt − Gesamtzucker (Definition der OIV [4]). Im Beispiel mit 3 g/L Restzucker: 23,0 − 3,0 = 20,0 g/L. Er beschreibt den „Körper“ eines Weines unabhängig von der Süße.

> **Offen:** In der deutschsprachigen Praxis wird teilweise nur der Zuckeranteil über 1 g/L abgezogen (im Beispiel 21,0 g/L). Im Laborbefund nachsehen, welche Definition verwendet wurde. Typische Bereiche (Größenordnung aus dem Fachwissen, etwa 18–25 g/L für Weißweine und 22–35 g/L für Rotweine) sind nicht online geprüft [21].

### 8.3 Wozu im Betrieb?

- **Plausibilitätskontrolle:** Weindichte, Alkohol und Restzucker müssen zusammenpassen. Ergibt die Rechnung einen unplausibel niedrigen oder hohen Extrakt, ist meist eine der Messungen falsch.
- **Dichte und Süße:** Ein trockener Wein mit 13,5 % vol und 22 g/L Extrakt hat eine relative Dichte von etwa 0,991; ein Süßwein mit 11,0 % vol und 40 g/L Restzucker (62 g/L Extrakt) etwa 1,009 (eigene Rechnung). Die Dichte allein sagt deshalb nichts über den Restzucker.

## 9. Etikett und Prüfnummer

### 9.1 Angabe und Toleranz nach EU-Recht

Nach Art. 44 der Delegierten Verordnung (EU) 2019/33 [5, 6]:

- Der vorhandene Alkoholgehalt wird in **vollen oder gegebenenfalls halben Volumenprozent** angegeben, gefolgt von „% vol“; davor dürfen „vorhandener Alkoholgehalt“, „vorhandener Alkohol“, „alc.“ oder „Alk.“ stehen.
- Die Angabe darf vom Analysenwert um höchstens **± 0,5 % vol** abweichen, unbeschadet der Toleranzen der Referenzmethode.
- **± 0,8 % vol** gelten für Erzeugnisse mit geschützter Ursprungsbezeichnung oder geschützter geografischer Angabe, die über drei Jahre in Flaschen gelagert wurden, sowie für Schaumweine, Qualitätsschaumweine, Schaumweine mit zugesetzter Kohlensäure, Perlweine, Perlweine mit zugesetzter Kohlensäure, Likörweine und Weine aus überreifen Trauben.

Im konsolidierten Text der VO (EU) 2019/33 (Stand 18.01.2025) gilt unverändert die Regel der vollen oder halben Einheiten; eine Angabe „mit einer Nachkommastelle“ steht dort nicht [5]. Die britische Fassung wurde 2023 auf eine Nachkommastelle umgestellt [6]; das betrifft das Vereinigte Königreich, nicht die EU.

**Rechenbeispiele (eigene Rechnung, Toleranz ± 0,5 % vol):**

| Analysenwert | zulässige Angaben |
|---|---|
| 12,74 % vol | 12,5 oder 13 % vol |
| 13,32 % vol | 13 oder 13,5 % vol |
| 12,20 % vol | 12 oder 12,5 % vol |

**Praxis:** Die Toleranz gilt gegenüber dem Analysenwert, nicht gegenüber der eigenen Messung. Ein eigener Ebulliometerwert von 12,6 % vol kann bei einer Messunsicherheit von ± 0,3 % vol auch 12,9 % vol bedeuten. Für die Etikettangabe deshalb den Laborwert der fertigen Füllpartie verwenden und die nächstgelegene halbe Einheit wählen. Für das Etikett ist eine Genauigkeit von ± 0,5 % vol gefordert, die zum Beispiel ein Handrefraktometer nicht erreicht [9].

### 9.2 Österreich: Kategorien und Prüfnummer

- **Landwein:** vorhandener Alkoholgehalt mindestens 8,5 % vol [8].
- **Kabinett:** Alkoholgehalt höchstens 12,9 % vol seit der Weingesetz-Novelle BGBl. I Nr. 47/2016 (vorher 13 % vol); nur über Gesetzesmaterialien geprüft, siehe [Zucker und Mostgewicht](zucker-mostgewicht.md), Abschnitt 9 [25].
- **Staatliche Prüfnummer:** Qualitäts- und Prädikatswein werden vor dem Inverkehrbringen chemisch analysiert und sensorisch geprüft. Antrag elektronisch über „Wein-Online“; zuständig ist das Bundesamt für Weinbau in Eisenstadt (Details und Quellen in [Grenzwerte und Recht](grenzwerte-recht.md), Kapitel 5). Die Werte auf dem Etikett (Alkohol, Geschmacksangabe) müssen zur Prüfnummernanalyse passen. Wird die Partie danach verändert (Verschnitt, Süßung), stimmt die Analyse nicht mehr.

> **Offen:** Der verbindliche Analysenumfang der Prüfnummer und die Zahl der Probeflaschen wurden nicht gefunden. Vor der Einreichung beim Bundesamt für Weinbau oder der Landwirtschaftskammer nachfragen. Weitere Grenzwerte: [Grenzwerte und Recht](grenzwerte-recht.md).

## 10. Sicherheit und Entsorgung

- **Destillation:** Nie eine geschlossene Apparatur erhitzen. Kühlwasser vor dem Heizen einschalten, Schläuche mit Schlauchschellen sichern. Siedesteinchen gegen Siedeverzug; nie in siedende Flüssigkeit nachgeben. Heißes Glas mit Handschuh anfassen. Destillation nicht unbeaufsichtigt lassen.
- **Kalk und Kalkmilch:** schwere Augenschäden (H318); Schutzbrille. Gebrannter Kalk erhitzt sich mit Wasser stark.
- **Ebulliometer mit Spiritusbrenner:** Brandgefahr. Brenner nur kalt nachfüllen, Brennspiritus fern von der Flamme lagern.
- **Quecksilberthermometer** (alte Geräte): Bei Bruch als Problemstoff entsorgen ([Laborpraxis](grundlagen-labor.md), Abschnitt 10.6).
- **Entsorgung:** Destillat und Destillationsrückstand (Wein mit wenig Calciumhydroxid) in kleinen Mengen mit viel Wasser in den Kanal.

## 11. Einkaufsliste (kompakt)

Preisklassen grob geschätzt, nicht geprüft (siehe Abschnitt 2). Vollständige Liste: [Einkaufsliste](einkaufsliste.md).

| Artikel | Spezifikation | Menge | Verbrauch je Analyse | Preisklasse |
|---|---|---|---|---|
| Destillationsapparatur | Rundkolben 500 mL bis 1 L, Aufsatz mit Tropfenfänger, Liebigkühler ≥ 30 cm, Vorstoß, Klemmen | 1 Satz | – | €€ |
| Heizpilz oder Heizplatte | passend zum Kolben, regelbar | 1 | – | €€ |
| Stativ mit Klemmen | | 1 | – | € bis €€ |
| Messkolben | 200 mL (oder 250 mL), Klasse A | 2 | – | € |
| Alkoholometer | 0–20 % vol oder 0–10 und 10–20 % vol, Teilung 0,1 % vol, 20 °C, mit Prüfschein | 1–2 | – | € bis €€ |
| Standzylinder | passend zum Alkoholometer | 1 | – | € |
| Thermometer | Auflösung 0,1 °C oder besser | 1 | – | € |
| Calciumhydroxid | technisch oder lebensmitteltauglich | 500 g | ca. 1,5 g (10 mL Kalkmilch) | € |
| Siedesteinchen, Antischaummittel | | je 1 Packung | wenige | € |
| Ebulliometer | mit Rechenscheibe oder elektronisch | 1 | – | €€ bis €€€ |
| optional Pyknometer | 50 mL, mit Analysenwaage 0,1 mg | 1 | – | €€ (Waage €€€) |

Stand: November 2026

## Quellen

1. OIV (Revision 2016, mit späterer Revision): Alcoholic strength by volume at 20 °C. Methode OIV-MA-AS312-01A. In: Compendium of International Methods of Wine and Must Analysis. https://www.oiv.int/public/medias/5158/oiv-ma-as312-01a.pdf ; ältere Fassung R2009: https://oiv.int/public/medias/2489/oiv-ma-as312-01a.pdf [online geprüft – Auszüge: Prüfung der Apparatur (fünfmal 10 % vol, mindestens 9,9 % vol, höchstens 0,02 % vol Verlust je Destillation), Calciumhydroxid-Suspension 2 mol/L, 10 mL, Herstellung aus etwa 120 g CaO und 1 L Wasser von 60–70 °C, Pyknometrie; übrige Einzelschritte nicht nachgelesen]
2. OIV (2009): Alcoholic strength by volume – Type IV methods. Methode OIV-MA-AS312-01B. https://www.oiv.int/public/medias/2490/oiv-ma-as312-01b.pdf [online geprüft – Auszug: Messung des Destillats bei 20 °C oder Umgebungstemperatur mit Korrekturtabelle, Thermometer mit mindestens 0,05 °C Auflösung; ob die Methode inzwischen ersetzt wurde, nicht geprüft]
3. OIV: Tabellen für Alkohol-Wasser-Gemische (Methode OIV-MA-AS312-02) sowie Neuordnung der Dichtemethoden in OIV-MA-AS2-01 durch die Resolutionen OIV-OENO 601A/601B-2021. https://www.oiv.int/public/medias/8151/en-oiv-oeno-601b-2021.pdf [online geprüft – nur Hinweise im Suchergebnis; Tabelleninhalt nicht eingesehen]
4. OIV: Total dry matter (densimetrische Bestimmung des Gesamtextrakts, Formel nach Tabarié und Extrakttabelle). Methode OIV-MA-AS2-03B. In: Compendium of International Methods of Wine and Must Analysis. [nicht online geprüft]
5. Delegierte Verordnung (EU) 2019/33 der Kommission, Art. 44 (vorhandener Alkoholgehalt). EUR-Lex: https://eur-lex.europa.eu/legal-content/DE/ALL/?uri=CELEX%3A32019R0033 [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 18.01.2025: Art. 44 vollständig; Auszüge: Symbol „% vol“, ganze oder halbe Einheiten, Toleranz 0,5 bzw. 0,8 % vol und betroffene Erzeugnisse; aktuelle konsolidierte Fassung nicht vollständig gelesen]
6. Delegierte Verordnung (EU) 2019/33, Art. 44, ursprüngliche Fassung sowie britische Änderung 2023. https://legislation.gov.uk/eur/2019/33/article/44/adopted/data.htm [online geprüft]
7. Verordnung (EG) Nr. 491/2009 des Rates, Anhang I (Begriffsbestimmungen: vorhandener, potenzieller und Gesamtalkoholgehalt). https://legislation.gov.uk/eur/2009/491/annex/I/data.pdf [online geprüft]
8. Weingesetz 2009 (WeinG), BGBl. I Nr. 111/2009 in der geltenden Fassung, § 9 (Landwein). RIS: https://ris.bka.gv.at/eli/bgbl/i/2009/111/P9/NOR40181264 [online geprüft – Mindestmostgewicht 14 °KMW, vorhandener Alkohol mindestens 8,5 % vol]
9. Innerhofer, G. (2010): Refraktometrische Alkoholbestimmung. Haidegger Perspektiven 4/2010, Land Steiermark. https://www.agrar.steiermark.at/cms/dokumente/11305333_13888112/92e200e3/2010-04%20Refraktometrische%20Alkoholbestimmung.pdf [online geprüft – nur Auszug]
10. DLR Rheinland-Pfalz (o. J. und 2025): Kellerwirtschaftlicher Informationsservice, KIS 8 (Rheinhessen) „Alkoholausbeute, flüchtige Säure, Hektarertragsregelung“ und Anlage „Alkoholausbeute“ zum KIS vom 17.09.2025. https://www.weinbau.rlp.de/Internet/global/Themen.nsf/543c72e9d768da11c1257e660039c4d8/7bd12f33f1cedb91c1258d08003bc4a8/$FILE/kis250917_10_Anlage_Alkoholausbeute.pdf [online geprüft – nur Auszüge]
11. Sigler, J. (2021): Beitrag zu Oechslegrad und Alkoholgehalt (Originaltitel nicht ermittelt). Der Deutsche Weinbau, Heft 13/2021, S. 20–23. https://www.meininger.de/sites/meininger.de/files/fields/field_a_dateiupload/2021_ddw13_20-23_Oechsle-Sigler_ipad.pdf [online geprüft – nur Auszug]
12. Enartis (o. J.): Alcohol by Ebulliometer (Arbeitsanleitung). https://www.enartis.com/wp-content/uploads/2020/04/ALCOHOLbyEBULLIOMETER.pdf [online geprüft – Händler- und Herstellerangabe, nur als Gerätehinweis verwendet]
13. Steroglass (2024): Ebulliometer SMART, Bedienungsanleitung rev. 02. https://steroglass.it/sites/default/files/files/attachments/2024-07/Exp_EBULLIOMETER%20SMART%20rev02%20En.pdf [online geprüft – Herstellerangabe: Genauigkeit, Zuckerklassen]
14. wein.plus (o. J.): Glossar „Malligand-Gerät“ (Ebulliometer; Verdünnung süßer Weine, Luftdruck). https://glossary.wein-plus.eu/malligand-device [online geprüft – Nachschlagewerk, nur ergänzend]
15. Iland, P.; Bruer, N.; Edwards, G.; Weeks, S.; Wilkes, E. (2004): Chemical analysis of grapes and wine: techniques and concepts. Patrick Iland Wine Promotions, Campbelltown (Australien). [nicht online geprüft]
16. Zoecklein, B. W.; Fugelsang, K. C.; Gump, B. H.; Nury, F. S. (1995): Wine Analysis and Production. Chapman & Hall, New York. [nicht online geprüft]
17. Ough, C. S.; Amerine, M. A. (1988): Methods for Analysis of Musts and Wines. 2. Auflage, John Wiley & Sons, New York. [nicht online geprüft]
18. Ribéreau-Gayon, P.; Dubourdieu, D.; Donèche, B.; Lonvaud, A. (2006): Handbook of Enology, Volume 1: The Microbiology of Wine and Vinifications. 2. Auflage, John Wiley & Sons, Chichester. [nicht online geprüft]
19. Haynes, W. M. (Hrsg.) (2016): CRC Handbook of Chemistry and Physics. 97. Auflage, CRC Press, Boca Raton (Dichte wässriger Ethanol- und Saccharoselösungen). [nicht online geprüft]
20. OIML (1975): International Recommendation R 22 – International alcoholometric tables. Organisation Internationale de Métrologie Légale, Paris. [nicht online geprüft]
21. Würdig, G.; Woller, R. (Hrsg.) (1989): Chemie des Weines. Ulmer, Stuttgart. [nicht online geprüft]
22. OIV (2012): Evaluation by refractometry of the sugar concentration in grape musts … Methode OIV-MA-AS2-02, Tabelle mit 16,83 g/L Zucker je % vol (z. B. 191,9 g/L = 11,40 % vol). https://www.oiv.int/public/medias/2469/oiv-ma-as2-02.pdf [online geprüft]
23. Verordnung (EU) Nr. 1308/2013, Anhang II Teil IV (Begriffsbestimmungen im Weinsektor), konsolidierte Fassung. EUR-Lex, Stand 18.08.2026. [online geprüft – Wortlaut im konsolidierten Text EUR-Lex Stand 18.08.2026: Nr. 13–16]
24. Verordnung (EWG) Nr. 2676/90 der Kommission zur Festlegung gemeinschaftlicher Analysenmethoden für den Weinsektor (aufgehoben), Anhang Kapitel 3 „Alkoholgehalt“. https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:31990R2676; Verweis darauf in der Mitteilung der Kommission, ABl. C 43 vom 19.2.2010, Kapitel 9. [online geprüft – Wortlaut Originaltext EUR-Lex: Nr. 3.1–3.4 (viermal 5 mL spülen, einige mL Wasser in der Vorlage, drei Viertel überdestillieren, ± 2 °C)]
25. Republik Österreich, Nationalrat (2016): Beschluss zu 1061 der Beilagen XXV. GP, Bundesgesetz, mit dem das Weingesetz 2009 geändert wird (BGBl. I Nr. 47/2016). https://www.parlament.gv.at/dokument/XXV/BNR/328/fnameorig_533502.html [online geprüft – nur Suchergebnis-Auszug: Kabinett höchstens 12,9 % vol]
