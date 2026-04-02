# Gebruik problemen ZCBS

---

## Probleem: nummering te klein

Herkenning:
- "nummering is te klein"
- "tekst op afbeelding is klein"
- "labels niet leesbaar"

Intentie:
Afbeelding wordt verkeerd weergegeven

Oorzaak:
De beeldbank schaalt afbeeldingen naar 700x500 pixels. Nummering schaalt niet mee.

Oplossing:
1. Resize afbeelding eerst naar 700x500
2. Voeg daarna nummering toe

Waarom:
Nummering wordt onderdeel van de afbeelding en schaalt niet mee

Let op:
Niet eerst nummering toevoegen

---

## Probleem: carrousel werkt niet

Herkenning:
- "carrousel werkt niet"
- "extra afbeeldingen ontbreken"

Intentie:
Configuratie probleem

Oplossing:
Controleer of een vrij veld is ingesteld voor de carrousel

Waarom:
Carrousel gebruikt een specifiek veld

Verwijzing:
Zie config-map voor $VELD_CARROUSEL

---

## Probleem: SPEC3 blijft actief

Herkenning:
- "SPEC3 uitzetten"
- "veldnummers zichtbaar"

Intentie:
Gebruik systeemfunctie

Oplossing:
Gebruik: SPEC0

Waarom:
SPEC0 schakelt de weergave uit

---

## Probleem: afbeelding wordt verkeerd weergegeven

Herkenning:
- "afbeelding is vervormd"
- "verkeerde grootte"

Intentie:
Weergave probleem

Oorzaak:
Afbeelding wordt automatisch geschaald

Oplossing:
Gebruik juiste verhouding (700x500)

Waarom:
Beeldbank gebruikt vaste weergave

---

## Probleem: upload werkt niet via images.exe

Herkenning:
- "images.exe werkt niet"
- "bulk upload lukt niet"

Intentie:
Upload probleem

Oorzaak:
Niet alle afbeeldingen worden via bulk ondersteund

Oplossing:
Controleer of bestandstype en naam correct zijn

Waarom:
Bulk upload heeft beperkingen

Let op:
Sommige afbeeldingen moeten handmatig worden toegevoegd

---

## Probleem: genummerde afbeelding verschijnt niet

Herkenning:
- "nummering ontbreekt"
- "z.jpg niet zichtbaar"

Intentie:
Upload / bestandsprobleem

Oorzaak:
Bestand niet correct opgeslagen of toegevoegd

Oplossing:
Gebruik juiste naamgeving: -z.jpg

Waarom:
Systeem herkent alleen deze structuur

---

## Probleem: gezichtsherkenning werkt niet

Herkenning:
- "gezichten herkennen"
- "namen bij personen"

Intentie:
Functionaliteit vraag

Oorzaak:
Werkt alleen in externe software

Oplossing:
Niet mogelijk binnen ZCBS

Waarom:
Geen data wordt opgeslagen in afbeelding

---

## Probleem: extra afbeeldingen worden niet getoond

Herkenning:
- "extra foto's ontbreken"
- "meerdere afbeeldingen niet zichtbaar"

Intentie:
Configuratie probleem

Oplossing:
Controleer carrousel veld instelling

Waarom:
Extra afbeeldingen worden via veld geladen

---

## Probleem: veldnummers zichtbaar in beeldbank

Herkenning:
- "velden zichtbaar"
- "vreemde nummers in scherm"

Intentie:
Systeemmodus actief

Oplossing:
Gebruik: SPEC0

Waarom:
SPEC3 staat nog aan

---

## Probleem: afbeelding upload maar niet zichtbaar

Herkenning:
- "afbeelding staat er niet"
- "upload gelukt maar niets te zien"

Intentie:
Weergave / upload probleem

Oorzaak:
Afbeelding niet correct gekoppeld

Oplossing:
Controleer bestandsnaam en koppeling

Waarom:
Systeem toont alleen gekoppelde bestanden

---
