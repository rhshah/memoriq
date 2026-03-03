# 🧠 Memoriq

**Live App:** [https://rhshah.github.io/memoriq/](https://rhshah.github.io/memoriq/)

Memoriq is a lightweight, fully client-side web application designed for interactive learning and spaced review. Built entirely with HTML, CSS, and vanilla JavaScript, it allows users to upload custom `.csv` flashcard decks and instantly generates a dynamic study environment—complete with robust LaTeX math rendering. 

Whether prepping for intensive MBA exams, professional certifications, or general knowledge retention, Memoriq provides a frictionless, privacy-first study experience with zero server-side processing.

---

## ✨ Features

* **Serverless & Privacy-First:** CSV files are parsed entirely in the browser using [PapaParse](https://www.papaparse.com/). No data is ever uploaded to a server.
* **Native Math & LaTeX Rendering:** Integrated with [KaTeX](https://katex.org/) to flawlessly render complex formulas, equations, and statistical symbols on the fly. 
* **Dual Learning Modes:**
  * **Study Mode:** A linear flashcard review interface with a visual progress bar and dynamic card resizing to accommodate long definitions.
  * **Knowledge Check:** An auto-generated multiple-choice quiz that pulls random distractors from your active deck.
* **Power-User Keyboard Navigation:**
  * `Spacebar` to flip cards.
  * `<` or `Left Arrow` for the previous card.
  * `>` or `Right Arrow` for the next card.
* **Pre-Loaded Default Deck:** Includes a built-in portfolio management and finance deck so the app is instantly usable upon loading.

---

## 🛠️ Usage & CSV Formatting

To create your own custom deck, use any spreadsheet software (Excel, Google Sheets, Numbers) and save your file as a **.csv (Comma Separated Values)**.

### Formatting Rules:
1. **Two Columns Only:** Column A is the Question (Front of card), Column B is the Answer (Back of card).
2. **No Headers Required:** The app treats the very first row as your first flashcard.
3. **Commas & Line Breaks:** Standard CSV formats automatically wrap text containing commas or newlines in quotes. Memoriq handles these natively without breaking.

### Using Math/LaTeX:
Memoriq supports standard LaTeX syntax for mathematical notations:
* **Inline Math:** Wrap your equation in single dollar signs (e.g., `The formula is $M^2$`).
* **Block/Display Math:** Wrap your equation in double dollar signs (e.g., `$$S_p = \frac{E(r_p) - r_f}{\sigma_p}$$`).

---

## 💻 Local Development

Because Memoriq is completely serverless, there are no dependencies to install or build steps to run. 

1. Clone the repository:

```bash
   git clone [https://github.com/rhshah/memoriq.git](https://github.com/rhshah/memoriq.git)

```

2. Navigate to the directory:

```bash
cd memoriq

```


3. Open `index.html` directly in any modern web browser.

---

## 🤝 Built With

* Vanilla HTML5 / CSS3 / ES6 JavaScript
* [KaTeX](https://katex.org/) - For fast math typesetting.
* [PapaParse](https://www.papaparse.com/) - For robust in-browser CSV parsing.
* [FontAwesome](https://fontawesome.com/) - For clean, scalable UI icons.

---

## © License & Credits

Built by [Ronak Shah (@rhshah)](https://github.com/rhshah). All rights reserved.
