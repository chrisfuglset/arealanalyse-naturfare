# Arealanalyse – naturfare og vassdrag

Kartbasert verktøy for å vurdere naturfare og vassdrag i et planområde, som grunnlag for reguleringsplan. Bygget som en selvstendig HTML-fil (HTML, CSS og JavaScript i én fil) — ingen installasjon nødvendig.

## Hva verktøyet gjør

- Hent kartlag direkte fra **NVE** sine karttjenester: flom, skred i bratt terreng, snøskred, fjellskred, kvikkleire, erosjon, overvann, vassdrag, energianlegg og kulturminner.
- Vis **eiendomsgrenser** fra Kartverkets Matrikkel-tjeneste.
- Velg analyseområde som **punkt** (med valgfri sirkelradius), **polygon** eller **rektangel**, og rediger området i etterkant (dra noder, flytt punkt, endre radius).
- Automatisk vurdering av de ulike naturfaretemaene, gruppert etter tema (flom/overvann, erosjon/vassdrag, skred, kvikkleire, energianlegg), med henvisninger til relevante TEK17-krav og NVE-veiledere.
- Generer en sammenhengende analysetekst som kan kopieres rett inn i et planinitiativ eller en planbeskrivelse.
- Lag ferdige **kartutsnitt som PDF** (A4/A3, valgfri målestokk og koordinatsystem), med tegnforklaring som kun viser kartlag som faktisk har treff innenfor analyseområdet (inkl. en 50 m buffersone).

## Bruk

Åpne `arealanalyse-naturfare.html` i en nettleser. Verktøyet krever internettforbindelse, siden kartlag og biblioteker (Leaflet, esri-leaflet, Turf.js, jsPDF) hentes direkte fra NVE, Kartverket og eksterne CDN-er.

## Forbehold

Analyseteksten genereres automatisk fra NVEs kartlag og må kvalitetssikres av planlegger eller fagkyndig før bruk i planbeskrivelse, ROS-analyse eller saksbehandling. Aktsomhetskart er grove og avklarer ikke reell fare alene.
