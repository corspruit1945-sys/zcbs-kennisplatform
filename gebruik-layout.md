# Layout / Afbeeldingen

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