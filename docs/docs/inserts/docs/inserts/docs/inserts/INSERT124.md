# INSERT124 – Sortering corrigeren

## 📌 Doel
Corrigeert alfabetische sortering van namen en plaatsen.

---

## ⚙️ Gebruik
&INSERT124("12,14,23");

---

## 🧠 Werking
- Verplaatst voorvoegsels zoals:
  - 's-Gravenhage → Gravenhage
  - 't Zand → Zand
- Zorgt voor correcte alfabetische volgorde

---

## ⚠️ Let op
- Alleen visuele aanpassing (data blijft hetzelfde)
- Moet vóór INSERT111 gebruikt worden

---

## 💡 Use case

### Probleem
't Zand staat onder T in plaats van Z

### Oplossing
Gebruik INSERT124

### Resultaat
Correct gesorteerde lijst
