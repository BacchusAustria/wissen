# Leitfaden für Beiträge

Dieses Repository sammelt Fachwissen für das Weingut: Anleitungen, Hintergrund und Entscheidungshilfen. Damit die Texte auch in einigen Jahren noch verlässlich sind, gelten für jede Datei die folgenden Regeln.

## Grundsätze

1. **Praxisnah.** Jede Anleitung muss sich in einem Familienweingut mit begrenztem Budget und ohne ausgebildetes Laborpersonal umsetzen lassen. Wo das nicht geht, steht es ausdrücklich dabei (zum Beispiel „nur im Labor sinnvoll“).
2. **Belegt.** Zahlen, Grenzwerte, Rezepturen, Umrechnungsfaktoren und Aussagen über Wirkungen haben eine Quelle.
3. **Ehrlich.** Unsicherheiten, widersprüchliche Studien und schwache Belege werden benannt und nicht geglättet. Eine Maßnahme ohne belastbaren Wirkungsnachweis wird als solche gekennzeichnet.
4. **Österreich zuerst.** Österreichische Normen (ÖNORM), Behörden, Rechtsvorschriften und Begriffe (°KMW, Weingarten, Gehaltsklassen nach den „Richtlinien für die sachgerechte Düngung“) stehen vorne. Deutsche und internationale Entsprechungen folgen dahinter.
5. **Bio mitdenken.** Bei jedem Betriebsmittel (Dünger, Bodenhilfsstoff, önologisches Mittel) steht, ob es nach EU-Bio-Recht (VO (EU) 2018/848, VO (EU) 2021/1165) zulässig ist und wo Verbandsrichtlinien strenger sind.

## Quellen

Zulässig sind:

- begutachtete wissenschaftliche Arbeiten: Zeitschriftenartikel, Übersichtsarbeiten, Metaanalysen,
- amtliche Methoden und Normen: OIV-Methodensammlung (*Compendium of International Methods of Analysis of Wines and Musts*), EU-Verordnungen, österreichische Gesetze und Verordnungen, ÖNORM, DIN, ISO, VDLUFA-Methodenbuch,
- Fachpublikationen von Forschungs-, Lehr- und Beratungseinrichtungen mit Praxisbezug, zum Beispiel HBLA und Bundesamt für Wein- und Obstbau Klosterneuburg, AGES, Landwirtschaftskammern, Bio Austria, FiBL, Agroscope, Hochschule Geisenheim, DLR Rheinpfalz, LWG Veitshöchheim, LTZ Augustenberg, AWRI, UC Davis, Cornell, Penn State, Washington State University,
- Fachbücher: Lehrbücher und Standardwerke.

Nicht zulässig als Beleg für fachliche Aussagen sind Werbetexte, Produktseiten, Foren, Blogs ohne Autorenangabe und KI-generierte Texte. Händler- und Herstellerseiten dürfen nur für Preise, Bezugsquellen und technische Gerätedaten genannt werden.

### Zitierweise

- Im Text mit Nummern in eckigen Klammern: [1], [2], [3–5].
- Am Ende jeder Datei ein Abschnitt **Quellen** mit durchnummerierten Einträgen:
  `Autor(en) (Jahr): Titel. Zeitschrift oder Herausgeber, Band, Seiten. DOI oder URL.`
- Hinter jedem Eintrag steht ein Prüfvermerk:
  - `[online geprüft]` – Existenz und zitierter Inhalt wurden bei der Erstellung online nachgesehen.
  - `[nicht online geprüft]` – Standardwerk oder Quelle aus dem Fachwissen; die zitierte Stelle vor Verwendung nachlesen.
- Keine Quelle erfinden, keine DOI und keine Seitenzahl raten. Eine Aussage ohne Beleg wird als „nicht belegt“ gekennzeichnet oder weggelassen.
- Rechtsvorschriften mit Fundstelle und Stand angeben, zum Beispiel „VO (EU) 2019/934, Anhang I Teil B, konsolidierte Fassung Stand 2025“. Rechtstexte ändern sich; vor rechtlich relevanten Entscheidungen den aktuellen Text bei EUR-Lex bzw. im RIS nachlesen und die Kontrollstelle fragen.

## Aufbau einer Methoden-Anleitung

1. **Kurzfassung** – 3 bis 6 Punkte: was, wozu, Aufwand, Genauigkeit.
2. **Wozu?** – Bedeutung der Messgröße, typische Werte, Zielbereiche.
3. **Prinzip** – kurz und verständlich.
4. **Material** – Geräte, Glaswaren, Chemikalien mit Konzentration und Reinheit, Verbrauch pro Analyse.
5. **Durchführung** – nummerierte Schritte, so genau, dass jemand ohne Laborausbildung sie befolgen kann.
6. **Berechnung** – Formel und durchgerechnetes Beispiel.
7. **Auswertung** – Tabelle mit Richt-, Ziel- und Grenzwerten und was daraus folgt.
8. **Fehlerquellen und Grenzen** – Genauigkeit, Störungen, Vergleich mit der Referenzmethode.
9. **Sicherheit und Entsorgung** – Gefahren (GHS), Schutzausrüstung, Entsorgung.
10. **Quellen**

Themen-Texte (etwa zur Bodenverbesserung) folgen sinngemäß: Kurzfassung, Hintergrund, Maßnahmen mit Wirkung, Beleglage, Aufwand und Kosten, Grenzen, Quellen.

## Form

- Deutsch, sachlich, kurze Sätze. Anleitungen im Imperativ: „Probe auf 20 °C temperieren.“
- Fachbegriffe beim ersten Auftreten erklären.
- Dezimalkomma und Leerzeichen vor Einheiten: 0,1 mol/L, 12,5 g/L, 20 °C, 1,5 % vol.
- Konzentrationen von Maßlösungen in mol/L. Die ältere Angabe in Normalität steht in Klammern, wo sie im Handel noch üblich ist: „Iodlösung 0,01 mol/L (0,02 N)“.
- Dateinamen in Kleinbuchstaben mit Bindestrichen und ohne Umlaute: `schweflige-saeure.md`.
- Warnungen als Zitatblock: `> **Achtung:** …`. Offene Fragen als `> **Offen:** …`.
- Querverweise relativ: `[Kalkbestimmung](../boden/kalk.md)`.
- Am Ende jeder Datei, vor den Quellen: `Stand: <Monat Jahr>`.

## Neue Themen anlegen

1. Ordner oder Datei nach den Regeln oben anlegen.
2. Im `README.md` des Ordners und im Haupt-`README.md` eintragen.
3. Offene Fragen im Abschnitt „Offene Punkte“ des Haupt-`README.md` festhalten.
