# Plankonzept

Ziel: Schemaplan (Gebäudeplan) für Rosenstraße 27, Köfering. Kein vermessener Bauplan.

## Phase 1: Modell

### Task 1.1: Koordinaten
- Einheit Meter. `x = 0` Westseite (Trennwand zur Nachbar-DHH, angenommen), `x` wächst nach Osten.
- `y = 0` Nordseite (Haustür), `y` wächst nach Süden (Garten/Balkon → Vorgarten → Straße).
- Darstellung: Norden oben, Osten rechts. SVG-Koordinate = `(x, y)`.
- Hülle für alle Geschosse: **6,6 × 10,6 m** (geschätzt).
- Wendeltreppe: Mitte `(1,05 | 5,3)`, Radius 0,9 m. In allen Geschossen gleich, daran hängt die Lage aller Räume.

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

## Phase 2: Umsetzung
- [x] 2.1 Fotos sichten (2 Batches, 31 Fotos)
- [x] 2.2 Version 1 (fehlerhaft, siehe `00-aufnahme.md` Phase 2)
- [x] 2.3 Version 2: Neuanalyse aller Fotos, Plan UG/EG/OG/DG/Schnitt
- [ ] 2.4 Offene Fragen klären (`00-aufnahme.md` Phase 4)
- [ ] 2.5 Maße einarbeiten
- [ ] 2.6 UG fotografieren und zeichnen

## Bekannte Schwächen
- Alle Wände gleich dick, tragende Wände nicht unterschieden.
- Maße geschätzt, Raumgrenzen können um ± 0,5 m abweichen.
- OG-Fläche östlich vom Podest und DG-Fläche südlich vom Treppenloch sind unbekannt.
