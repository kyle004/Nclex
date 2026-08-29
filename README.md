# NCLEX-RN Simulator (2026 NGN Standards)

A single-file, browser-based practice simulator modeled on the Next Generation
NCLEX-RN test environment. Open `index.html` in any modern browser — no build
step, no server, no dependencies beyond the Tailwind CDN.

## What it includes

- **15-item bank** spanning pharmacology, management of care, safety and
  infection control, maternity, pediatrics, psych/mental health, and
  physiological adaptation.
- **NGN item types**: standard multiple choice, matrix/grid multiple response
  (select-all-that-apply), stand-alone numeric dosage calculations, and a
  Bow-Tie item (Condition / Action / Parameter) with a clinical case exhibit.
- **Exam-like environment**: 5-hour countdown timer, forward-only navigation,
  on-screen basic calculator, candidate scratchpad, and disabled text
  selection.
- **Scored review**: percentage score against a 73% competency threshold plus
  the clinical rationale for every item.

## Usage

```
open index.html          # macOS
xdg-open index.html      # Linux
```

Answers are held in memory only; reloading the page starts a fresh session.

## Disclaimer

Practice material for study use only. NCLEX-RN® is a registered trademark of
the National Council of State Boards of Nursing, Inc., which does not endorse
or sponsor this project. Content is not a substitute for clinical judgment or
current institutional protocol.
