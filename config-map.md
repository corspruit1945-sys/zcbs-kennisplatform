# ZCBS Config Map

---

## 🖼️ Afbeelding naast tekst

**Vraag**
Ik wil de afbeelding naast de tekst plaatsen.

**Oplossing**
Gebruik $LAYOUT3

**Code**
$LAYOUT3 = 1;

**Uitleg**
Zet afbeelding naast de metadata op de objectpagina.

---

## 🔄 Volgorde velden aanpassen

**Vraag**
Ik wil de volgorde van velden aanpassen.

**Oplossing**
Gebruik INSERT141

**Code**
&INSERT141 ("2,blanco,25,5,7");

**Uitleg**
Bepaalt de volgorde van velden op de objectpagina.

---

## 🖼️ Thumbnail grootte aanpassen

**Vraag**
Ik wil grotere afbeeldingen in de lijst.

**Oplossing**
Gebruik $THUMBNAIL_WIDTH

**Code**
$THUMBNAIL_WIDTH = "style="max-width:150px"";

**Uitleg**
Past de grootte van thumbnails aan.

---

## 🔍 Zoeken op meerdere woorden

**Vraag**
Ik wil dat alle zoekwoorden verplicht zijn.

**Oplossing**
Gebruik $ZOEKOP

**Code**
$ZOEKOP = "AND";

**Uitleg**
Zoekt alleen resultaten met alle woorden.

---

## 🎨 Layout aanpassen

**Vraag**
Ik wil de layout van de pagina aanpassen.

**Oplossing**
Gebruik $FILE_LAYOUT

**Code**
$FILE_LAYOUT = "misc/layoutgvn.html";

**Uitleg**
Bepaalt de HTML-structuur van de pagina.

---

## 🎨 Layout aanpassen

**Categorie**
Layout

**Tags**
layout html pagina structuur template

**Vraag**
Ik wil de layout van de pagina aanpassen.

**Oplossing**
Gebruik $FILE_LAYOUT

**Code**
$FILE_LAYOUT = "misc/layoutgvn.html";

**Uitleg**
Bepaalt de HTML-structuur van de pagina.

---

## 🧱 Extra layout logica

**Categorie**
Layout

**Tags**
layout insert css html aanpassing

**Vraag**
Ik wil extra layout aanpassingen doen.

**Oplossing**
Gebruik $INSERT

**Code**
$INSERT .= <<'EOR';

**Uitleg**
Voegt eigen code toe aan de pagina.

---

## 🖼️ Thumbnail grootte aanpassen

**Categorie**
Afbeeldingen

**Tags**
thumbnail grootte afbeelding lijst

**Vraag**
Ik wil grotere afbeeldingen in de lijst.

**Oplossing**
Gebruik $THUMBNAIL_WIDTH

**Code**
$THUMBNAIL_WIDTH = "style="max-width:150px"";

**Uitleg**
Past de grootte van thumbnails aan.

---

## 📦 Thumbnail layout aanpassen

**Categorie**
Afbeeldingen

**Tags**
thumbnail layout grid breedte

**Vraag**
Ik wil de ruimte rond thumbnails aanpassen.

**Oplossing**
Gebruik $THUMBNAIL_BOX

**Code**
$THUMBNAIL_BOX = "200";

**Uitleg**
Bepaalt de breedte van het thumbnailgebied.

---

## 🚫 Geen thumbnails tonen

**Categorie**
Afbeeldingen

**Tags**
thumbnail uitzetten afbeeldingen

**Vraag**
Ik wil geen thumbnails tonen.

**Oplossing**
Gebruik $NO_THUMBS

**Code**
$NO_THUMBS = 1;

**Uitleg**
Schakelt thumbnails uit.

---

## 🔍 Zoeken op meerdere woorden

**Categorie**
Zoeken

**Tags**
zoeken and or woorden

**Vraag**
Ik wil dat alle zoekwoorden verplicht zijn.

**Oplossing**
Gebruik $ZOEKOP

**Code**
$ZOEKOP = "AND";

**Uitleg**
Zoekt alleen resultaten met alle woorden.

---

## 🔎 Zoekvelden aanpassen

**Categorie**
Zoeken

**Tags**
zoekvelden velden filter

**Vraag**
Ik wil bepalen in welke velden gezocht wordt.

**Oplossing**
Gebruik $VELDMENU

**Code**
$VELDMENU = "07 17 -02";

**Uitleg**
Bepaalt zoekvelden.

---

## 📊 Sortering aanpassen

**Categorie**
Zoeken

**Tags**
sorteren volgorde zoekresultaat

**Vraag**
Ik wil sortering van resultaten aanpassen.

**Oplossing**
Gebruik $SORTEREN

**Code**
$SORTEREN = "17 07 05 02";

**Uitleg**
Bepaalt sorteervolgorde.

---

## 🏠 Homepage titel aanpassen

**Categorie**
Homepage

**Tags**
homepage titel tekst

**Vraag**
Ik wil de titel van de homepage aanpassen.

**Oplossing**
Gebruik $TXT_HEADING1

**Code**
$TXT_HEADING1 = "Mijn titel";

**Uitleg**
Wijzigt de homepage titel.

---

## 🧱 Linkblok aanpassen

**Categorie**
Homepage

**Tags**
homepage menu navigatie

**Vraag**
Ik wil het menu aanpassen.

**Oplossing**
Gebruik $LINKBLOK

**Code**
$LINKBLOK = "...";

**Uitleg**
Bepaalt homepage navigatie.

---

## 🎨 Zoekblok kleur

**Categorie**
Homepage

**Tags**
kleur zoekblok css

**Vraag**
Ik wil de kleur van het zoekblok aanpassen.

**Oplossing**
Gebruik $HP_SEARCH_BLOCK_COL

**Code**
$HP_SEARCH_BLOCK_COL = "#ffffff";

**Uitleg**
Past de achtergrondkleur aan.

---

## 🖼️ Random afbeelding homepage

**Categorie**
Homepage

**Tags**
homepage afbeelding random

**Vraag**
Ik wil een random afbeelding tonen.

**Oplossing**
Gebruik $RANDOM_IMAGE

**Code**
$RANDOM_IMAGE = 1;

**Uitleg**
Toont willekeurige afbeelding.

---

## 🔙 Navigatie knop aanpassen

**Categorie**
Objectpagina

**Tags**
navigatie knop tekst

**Vraag**
Ik wil de terugknop aanpassen.

**Oplossing**
Gebruik $TXT_NAVIGAT2

**Code**
$TXT_NAVIGAT2 = "Terug";

**Uitleg**
Past knoptekst aan.

---

## 🖼️ Meerdere afbeeldingen tonen

**Categorie**
Objectpagina

**Tags**
carousel afbeeldingen

**Vraag**
Ik wil meerdere afbeeldingen tonen.

**Oplossing**
Gebruik $VELD_CAROUSEL

**Code**
$VELD_CAROUSEL = 27;

**Uitleg**
Toont extra afbeeldingen.

---

## 🌍 Google Maps toevoegen

**Categorie**
Objectpagina

**Tags**
google maps locatie

**Vraag**
Ik wil een kaart tonen.

**Oplossing**
Gebruik $GOOGLE_MAP

**Code**
$GOOGLE_MAP = 1;

**Uitleg**
Toont Google Maps.

---

## 🔗 Links in velden

**Categorie**
Velden

**Tags**
links velden url

**Vraag**
Ik wil links klikbaar maken.

**Oplossing**
Gebruik $BESCHRIJVING_VELD

**Code**
$BESCHRIJVING_VELD = "06";

**Uitleg**
Maakt links actief.

---

## 🧾 Veldnamen aanpassen

**Categorie**
Velden

**Tags**
veldnaam label

**Vraag**
Ik wil veldnamen aanpassen.

**Oplossing**
Gebruik $fieldname

**Code**
$fieldname{"VELD05"} = "Titel";

**Uitleg**
Wijzigt veldlabel.

---

## 🔒 Internet zichtbaar

**Categorie**
Systeem

**Tags**
internet zichtbaar

**Vraag**
Ik wil objecten zichtbaar maken.

**Oplossing**
Gebruik $INTERNET

**Code**
$INTERNET = 1;

**Uitleg**
Zet objecten online.

---

## ⏱️ Sessietijd aanpassen

**Categorie**
Systeem

**Tags**
sessie timeout

**Vraag**
Ik wil sessietijd aanpassen.

**Oplossing**
Gebruik $SESSION_INT

**Code**
$SESSION_INT = 60;

**Uitleg**
Bepaalt sessieduur.

---

## 📧 Email instellen

**Categorie**
Systeem

**Tags**
email notificatie

**Vraag**
Ik wil email instellen.

**Oplossing**
Gebruik $EMAIL_TO

**Code**
$EMAIL_TO = "[mail@site.nl](mailto:mail@site.nl)";

**Uitleg**
Stelt email in.

---



