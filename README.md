# Očevid lokator – izvanmrežni podaci

Paketi cesta i naselja po županijama za aplikaciju Očevid lokator (Postavke → Izvanmrežni podaci).

- `index.json` – popis paketa, datum izvora podataka, veličina i SHA-256 svakog paketa
- `hr-01.zip` … `hr-21.zip` – ploče od 0,25° × 0,25° za pojedinu županiju s pojasom od 0,3° oko nje

Podaci su izrađeni skriptom `tools/build_offline.py` iz projekta Očevid lokator, iz izvoza
Geofabrik `croatia-latest.osm.pbf`.

Osvježavanje: preuzeti noviji `croatia-latest.osm.pbf`, pokrenuti
`python tools/build_offline.py croatia-latest.osm.pbf <ova mapa>` i objaviti promjene.

## Licenca podataka

© OpenStreetMap suradnici. Podaci su dostupni pod licencom Open Database License (ODbL) 1.0,
https://www.openstreetmap.org/copyright
