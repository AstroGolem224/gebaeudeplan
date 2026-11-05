# Plankonzept

Ziel: Schemaplan (Gebäudeplan) für Rosenstraße 27, Köfering. Kein vermessener Bauplan.

## Phase 1: Modell

### Task 1.1: Koordinaten
- Einheit Meter. Modell: `x = 0` ist Ostseite, `y = 0` ist Nordseite.
- Darstellung: Norden oben, Osten rechts. SVG-Koordinate = `(W − x, y)`.
- Hüllmaß für alle Geschosse: **7,2 × 9,4 m** (geschätzt). Alle Ebenen teilen sich dieselbe Hülle, die Treppe sitzt bei `(4,85 | 3,6)` mit Radius 0,85 m.

### Task 1.2: Sicherheitsstufen
| Stufe | Bedeutung | Darstellung |
|---|---|---|
| sicher | Raum und Lage klar aus Fotos | durchgezogene Linie |
| plausibel | Lage aus Nachbarschaft abgeleitet | durchgezogene Linie |
| unklar | Platzhalter, nicht fotografiert | gestrichelt + schraffiert |

### Task 1.3: Ableitungen
- Haustür, Vorflur, Diele und Wohnzimmer liegen auf einer Achse (B2-1, B2-8, B2-11).
- Wohnzimmer-Fensterfront (Süd) liegt unter Schlafzimmer + Balkon (Süd).
- Gäste-WC (EG) liegt unter dem Bad (OG). Das passt zu einem gemeinsamen Leitungsschacht.
- Zimmer 2 und Bad liegen am Treppenbereich (Türen direkt daran, B1-16, B1-18).

## Phase 2: Umsetzung
- [x] 2.1 Fotos sichten (2 Batches)
- [x] 2.2 Aufnahme dokumentieren (`docs/00-aufnahme.md`)
- [x] 2.3 Schemaplan EG, OG, DG, KG, Schnitt (`plan/index.html`)
- [ ] 2.4 Maße einarbeiten
- [ ] 2.5 Keller fotografieren und zeichnen
- [ ] 2.6 DG-Studio korrekt ausrichten (Dachschrägen, Dachfenster)
- [ ] 2.7 Möbel/Elektro/Smart-Home-Ebene (falls gewünscht)

## Bekannte Schwächen
- Alle Wände sind gleich dick gezeichnet. Tragende Wände sind nicht unterschieden.
- Das DG-Studio ist in Lage und Form geraten (Fotos zeigen keine Gesamtansicht).
- Türaufschläge sind aus Fotos geschätzt.
