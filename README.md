# 🤖 Furhat Voice Ordering System for Blind Users

A voice-based restaurant ordering system built on the **Furhat social robot**, designed to enhance accessibility for blind and visually impaired users. This project investigates how speech verbosity (concise vs. descriptive) affects usability, task efficiency, and user satisfaction in a voice-only interaction context.

> 📄 A full research report is included in this repository: [`project_report.pdf`](./project_report.pdf)

---

## 📌 Overview

Dining out is a significant challenge for visually impaired individuals. Most restaurant technologies rely on visual interfaces, excluding blind users from independent dining experiences. This project addresses that gap by designing a **voice-only ordering system** using a Furhat robot, removing all visual dependencies.

We conducted a between-subjects study comparing two speech design conditions:
- **Concise speech** — brief, direct instructions with minimal words
- **Descriptive speech** — detailed explanations with additional context

---

## 👥 Authors

| Name | Student ID | Email |
|------|-----------|-------|
| Baris Kaban | 2837738 | b.kaban@student.vu.nl |
| Goktug Yildirim | 2814081 | g.yildirim2@student.vu.nl |
| Salma el Ouali | 2783275 | s.el.ouali@student.vu.nl |

*Vrije Universiteit Amsterdam — Artificial Intelligence*

---

## 🧪 Study Design

- **Type:** Exploratory between-subjects experiment
- **Participants:** 8 (aged 18–20, university community)
- **Simulation method:** Sighted participants kept eyes closed throughout
- **Task:** Order at least one main dish and one drink via voice commands
- **Robot:** Furhat, programmed in Furhat Blockly

### Menu Structure
The system featured 4 categories with 3 items each:
- Starters, Mains, Drinks, Desserts

### Measures
- Task completion time (stopwatch)
- System Usability Scale (SUS)
- Satisfaction rating (1–5 Likert)
- Confidence rating (1–5 Likert)

---

## 📊 Key Results

| Measure | Concise Speech | Descriptive Speech | p-value |
|---|---|---|---|
| Task Time (s) | 142 ± 21.97 | 213 ± 28.62 | 0.008 ✅ |
| SUS Score | 82.5 ± 2.04 | 67.5 ± 4.33 | 0.030 ✅ |
| Satisfaction (1–5) | 4.5 ± 0.58 | 3.25 ± 0.96 | 0.074 |
| Confidence (1–5) | 4.25 ± 0.50 | 3.75 ± 0.96 | 0.418 |

> ✅ = statistically significant (p < 0.05)

Concise speech achieved **"excellent" usability** (SUS > 80), while descriptive speech fell in the **"acceptable"** range.

---

## 💡 Design Recommendations

Based on our findings (pending validation with actual blind users):

1. Use **brief, clear speech** while retaining necessary information
2. Offer **optional elaboration** rather than mandatory detailed descriptions
3. Implement **clear navigation cues** without excessive verbalization
4. Support **repeat and interruption commands** for user control
5. Use **consistent, predictable** interaction patterns throughout

---

## ⚠️ Limitations

- Participants were **sighted users simulating blindness** — not actual blind users
- Small sample size (n=8) limits generalizability
- Lab setting doesn't capture real restaurant noise/complexity
- Uneven gender distribution (2F, 6M) confounded with Furhat experience

---

## 🔭 Future Work

- Replicate study with **actual blind and visually impaired users**
- Build **adaptive verbosity systems** that adjust to user behavior
- Conduct **field studies** in real restaurant environments
- Explore integration with smartphone apps for order history and personalized menus

---

## 🛠️ Tech Stack

- [Furhat Robot](https://furhatrobotics.com/)
- Furhat Blockly (interaction programming)
- System Usability Scale (SUS) for evaluation

---

## 📁 Repository Structure

furhat-voice-ordering-accessibility/
├── project_report.pdf       # Full research paper
├── README.md
├── src/                     # Furhat Blockly source files
├── data/                    # Raw collected data (SUS scores, timings)
└── questionnaires/          # Consent forms, demographic & rating scales

---

## 📄 License

This project was developed for academic purposes at Vrije Universiteit Amsterdam. Please cite appropriately if referencing this work.