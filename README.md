# BEM Tutorial

Willkommen zum **BEM-Tutorial** von "Programmieren lernen" auf YouTube!  
In diesem Repository findest du den Code zum Mitmachen und zum Vergleichen.

---

## 🔽 Wie kann ich den Code herunterladen und nutzen?

### ✅ Option 1: Als ZIP-Datei herunterladen (empfohlen für Anfänger)

1. Klicke oben auf den grünen **`Code`**-Button
2. Wähle **`Download ZIP`**
3. Entpacke die ZIP-Datei auf deinem Rechner
4. Öffne den Ordner in deinem Code-Editor (z. B. [Visual Studio Code](https://code.visualstudio.com/))
5. Öffne z. B. die Datei `form.html` oder `button.html` – dort wird im Tutorial gemeinsam gearbeitet

### ✅ Option 2: Über Git klonen (für Fortgeschrittene)

```
git clone https://github.com/Developer-Akademie-YouTube/BEM-tutorial.git
cd BEM-tutorial
```

## 🧾 Es gibt zwei Versionen (Branches) des Codes:

- **`start`** – Ausgangspunkt zum Mitmachen im Tutorial  
- **`final`** – Fertiger Code am Ende des Videos

### 🔀 Wechsle z. B. so zum Start-Code:
```
git checkout start
```

## 📚 Was ist BEM?

**BEM** steht für:

### 🟩 Block  
Ein eigenständiger, wiederverwendbarer Baustein der Benutzeroberfläche.  
**Beispiel:** `form`, `button`, `header`

### 🟦 Element  
Ein Bestandteil eines Blocks, der ohne den Block keinen Sinn ergibt.  
**Beispiel:** `form__input`, `button__icon`

### 🟨 Modifier  
Eine Variante oder ein Zustand eines Blocks oder Elements.  
**Beispiel:** `form--dark`, `button--primary`

---

### 🔤 BEM-Schreibweise: `block__element--modifier`

- `__` (Doppel-Unterstrich) verbindet einen Block mit einem **Element**  
  → z. B. `form__input` = Eingabefeld im Formular

- `--` (Doppel-Bindestrich) steht für einen **Modifier**  
  → z. B. `form__button--primary` = primäre Variante eines Buttons

```
  <!-- Block -->
<section class="form">

  <!-- Element -->
  <input class="form__input" type="text" />

  <!-- Modifier -->
  <button class="form__button form__button--primary">Absenden</button>

</section>
```

## 📁 Dateien in diesem Projekt

| Datei         | Beschreibung |
|---------------|--------------|
| `button.html` | Hier erstellen wir im Tutorial gemeinsam einen Button im BEM-Stil |
| `form.html`   | Hier wird im Video ein Formular Schritt für Schritt aufgebaut |
| `header.html` | Fertiges Beispiel eines Headers mit BEM-Struktur |
| `login.html`  | Zusammengesetztes Beispiel aus mehreren Komponenten |
| `signup.html` | Noch ein Beispiel mit anderen Blöcken und Modifiern |

---