# 🔧 Snelle oplossingen ZCBS (Snippets)

Direct toepasbare antwoorden op veelgestelde vragen.

---

## 🖼️ Afbeelding naast tekst (objectpagina)
Gebruik:
$LAYOUT3 = 1

Zorgt ervoor dat de afbeelding naast de tekst wordt weergegeven.

---

## 🖼️ Meerdere afbeeldingen naast elkaar
Gebruik:
-z images

Toont afbeeldingen naast elkaar in één regel.

---

## 🖼️ Afbeeldingen onder elkaar
Gebruik:
-x images

Toont afbeeldingen onder elkaar.

---

## 🖼️ Tweede afbeelding naast eerste
Gebruik:
-p images

Plaatst afbeelding 2 naast afbeelding 1.

---

## 📏 Veldnamen links uitlijnen
Gebruik:
$VELD_ALIGN = "left"

(Default is vaak al left)

---

## 🔤 Datum formaat aanpassen
Gebruik:
$JMD = "1"

Formaat:
jaar-maand-dag of dag-maand-jaar

---

## 📌 Titel vet maken
Gebruik:
$TITEL_BOLD = "1"

Toont titel in vet.

---

## 🔎 Tekst "Lees meer..." vervangen door link
Gebruik:
$LEES_MEER = "1"

Maakt van "Lees meer..." een klikbare hyperlink.

---

## 🔢 Databaserecord nummer tonen/verbergen
Gebruik:
$PRE_FIXT_NUMBER = ""

Leeg = niet tonen

---

## 🧾 Namen onder afbeelding tonen
Gebruik:
$TEKST_NAMEN = "1"

Toont namen direct onder de foto.

---

## 📷 Afbeelding positie aanpassen (layout)
Gebruik:
$LAYOUT3 = 1

Let op:
Dit werkt samen met layout.html

---

## 🧱 Layout aanpassen (geavanceerd)
Gebruik:
layout.html

Bijvoorbeeld:
- afbeelding links / rechts
- tekst naast afbeelding

---

## ⚙️ Configuratie bestand locatie
Bestand:
cfg-cbs.pl

Hierin staan alle parameters.

---

## 🔐 Toegangsrechten instellen
Bestand:
permit.lst

Regelt toegang per gebruiker / IP

---

## 🔄 Zoekwoorden vervangen (synoniemen)
Bestand:
replace.txt

Wordt gebruikt voor zoekoptimalisatie.

---

## 🧩 INSERT gebruiken voor aanpassingen
Gebruik:
$INSERTX

Voor dynamische aanpassingen van output.

---

## 🧭 Alleen op specifieke pagina toepassen
Gebruik:
$WEB_PAGE

1 = homepage  
2 = zoekresultaten  
3 = objectpagina  
4 = formulier  

---

## 📤 Export van objecten maken
Gebruik:
DUMP_OBJECTEN

Maakt exportbestand (XML-achtig formaat)

---

## 💾 Backup bij MERGE
Automatisch:

backup1 map bevat:
- oude database
- update database
- nieuwe database

---

# 🚀 Gebruik

Zoek op wat je wilt doen, niet op parameternaam.

Bijvoorbeeld:
- "afbeelding naast tekst"
- "veld uitlijnen"
- "meerdere afbeeldingen"

---

# 💡 Tip

Breid deze lijst uit bij elke nieuwe vraag.
