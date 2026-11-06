# Plankonzept

Ziel: Schemaplan (Gebäudeplan) für Rosenstraße 27, Köfering. Kein vermessener Bauplan.

## Phase 1: Modell

### Task 1.1: Koordinaten
- Einheit Meter. `x = 0` Westseite (Trennwand zur Nachbar-DHH, angenommen), `x` wächst nach Osten.
- `y = 0` Nordseite (Haustür), `y` wächst nach Süden (Garten/Balkon → Vorgarten → Straße).
- Darstellung: Norden oben, Osten rechts. SVG-Koordinate = `(x, y)`.
- Hülle für alle Geschosse: **6,6 × 10,6 m** (geschätzt).
- Wendeltreppe: Mitte `(1,35 | 3,9)`, Radius 1,0 m. In allen Geschossen gleich, daran hängt die Lage aller Räume.

### Task 1.2: Sicherheitsstufen
| Stufe | Bedeutung | Darstellung |
|---|---|---|
| sicher | Raum und Lage aus Fotos klar | durchgezogen |
| abgeleitet | Lage aus Blickrichtung, Türanschlag, Spiegelungen erschlossen | durchgezogen |
| unklar | Platzhalter, nicht fotografiert | gestrichelt + schraffiert |

Vermutete Türen sind orange gestrichelt.

### Task 1.3: Methode
1. Pro Foto Kamerablickrichtung bestimmen (welche Wand ist links/rechts/vorne).
2. Gemeinsame Merkmale zwischen Fotos verknüpfen (Bilder, Leuchten, Türblätter, Kleidung am Geländer).
3. Spiegelungen in Fenstern und Spiegeln für verdeckte Wände nutzen.
4. Ausrichtung mit den Angaben (Balkon Süd, Zimmer 2 Nord, Haustür Nord) festnageln.
5. Geschosse über Treppe und Leitungen (Bad über Gäste-WC) übereinanderlegen.
6. Ab v3: Handskizzen des Eigentümers sind Primärquelle für die Raumaufteilung, Fotos liefern Details.

## Phase 2: Umsetzung
- [x] 2.1 Fotos sichten (2 Batches, 31 Fotos)
- [x] 2.2 Version 1 (fehlerhaft, siehe `00-aufnahme.md` Phase 2)
- [x] 2.3 Version 2: Neuanalyse aller Fotos, Plan UG/EG/OG/DG/Schnitt
- [x] 2.4 Version 3: Raumaufteilung nach Handskizzen EG/OG/DG
- [ ] 2.5 Offene Fragen klären (`00-aufnahme.md` Phase 4)
- [ ] 2.6 Maße einarbeiten
- [ ] 2.7 UG fotografieren und zeichnen

## Bekannte Schwächen
- Alle Wände gleich dick, tragende Wände nicht unterschieden.
- Maße geschätzt, Raumgrenzen können um ± 0,5 m abweichen.
- Skizzen sind nicht maßstäblich; Proportionen sind auf die Hülle 6,6 × 10,6 m umgerechnet.
