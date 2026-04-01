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

