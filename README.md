# 🧠 NeuroBridge — Adaptive Learning for Every Mind

> **Isazi.ai × UNISA · AI for Accessibility Hackathon 2026**  
> Built by Lethabo Hoaeane · BCom Business Informatics · UNISA

---

## The Problem

**1 in 7 people globally are neurodiverse** — including individuals with ADHD, dyslexia, autism spectrum traits, and other cognitive differences. Yet almost every digital learning platform delivers content in a single fixed format: dense text, one-size-fits-all pacing, and zero sensory accommodation.

In South Africa, where educational inequality is already stark, neurodiverse learners face a triple barrier: under-resourced schools, unsupported teachers, and tools designed for a neurotypical majority. The result? Higher dropout rates, lower self-confidence, and talent left behind.

**NeuroBridge exists to change that.**

---

## What It Does

NeuroBridge is a **mobile-first AI-powered adaptive learning web app** that reshapes how educational content is delivered — in real time — based on each learner's cognitive profile.

### Core Features

| Feature | Description |
|---|---|
| 🧩 **Adaptive Content Delivery** | AI reformats any lesson into the learner's preferred style: visual (charts/diagrams), reading-based (structured text/notes), or interactive (quizzes/challenges) |
| ⏱️ **Sensory-Aware Pacing** | Pomodoro-style focus sessions with calming transitions and break prompts for ADHD learners |
| 💬 **Plain-Language AI Tutor** | Ask anything. Get it explained in simpler words, as an analogy, or step-by-step — until it clicks |
| 🔊 **Full Accessibility Stack** | Text-to-speech, dyslexia-friendly font mode, high-contrast theme, keyboard navigation |
| 📊 **Non-Judgmental Progress Tracking** | No red crosses. Tracks effort, consistency & mastery separately |
| 🌍 **SA Curriculum Context** | Local examples, code-switching support, works on low-bandwidth connections |

---

## How It Works

```
1. Quick Cognitive Onboarding (5 min)
   └─ Interactive quiz identifies learning style, attention span & accessibility needs

2. Upload or Select a Topic
   └─ Paste text, upload a page, or pick from the curriculum library

3. AI Reformats in Real Time
   └─ Claude API adapts the content to the learner's profile

4. Learn in Your Rhythm
   └─ Timed sessions, distraction-free mode, read-aloud on any element

5. AI Watches & Adapts
   └─ Detects struggle patterns → offers alternative explanation automatically
```

---

## Tech Stack

```
Frontend   →  HTML5 / CSS3 / Vanilla JS  (zero dependencies, works offline)
AI Layer   →  Anthropic Claude API (claude-sonnet)
            •  Content reformatting  
            •  Plain-language explanations  
            •  Quiz generation from any topic  
TTS        →  Web Speech API (browser-native, no cost)
Hosting    →  Static — runs from a single HTML file, no server needed
```

> ⚡ **Self-contained by design.** No infrastructure, no database, no build tools required — aligns with hackathon constraints.

---

## Getting Started

Just open the app — no installation, no API key, no setup needed.

👉 https://neurobridge-iota.vercel.app
```

Add your API key in `index.html`:
```javascript
No API key needed — just open the app and start learning.
```

---

## Project Structure

```
neurobridge/
├── index.html          # Complete app (single-file, self-contained)
├── README.md           # This file
└── LICENSE             # MIT License
```

---

## Accessibility Commitment

This project was built with **disability-inclusive design from day one**, not as an afterthought:

- ✅ Screen reader compatible (semantic HTML + ARIA labels)
- ✅ Keyboard-only navigation throughout
- ✅ Dyslexia-friendly font toggle (OpenDyslexic)
- ✅ High-contrast mode
- ✅ Text-to-speech on every content block
- ✅ Reduced-motion mode respects `prefers-reduced-motion`
- ✅ Works on 2G / low-bandwidth (no heavy assets)

---

## Who This Is For

- Students with **ADHD** who need structured, timed, low-distraction sessions
- Learners with **dyslexia** who benefit from TTS and visual-first formatting
- Students on the **autism spectrum** who thrive with predictable, structured content
- Any learner whose brain just works **differently** from the textbook format

---

## Impact

> *"The goal isn't to fix the learner. It's to fix the learning environment."*

NeuroBridge doesn't pathologize difference — it celebrates it. By meeting learners where they are, we believe we can meaningfully reduce dropout rates, improve confidence, and unlock potential that rigid systems leave behind.

---

## About the Builder

**Lethabo Hoaeane**  
BCom Business Informatics · UNISA (Student No: 25055682)  
Completed: Afrikan AI Masterclass I & II (STU-110, STU-111) · 2026  
HackerRank Certified: SQL Basic + Intermediate · March 2026  
📧 lethabomphukuile14@gmail.com

---

## License

MIT — free to use, modify and build on. Let's make learning accessible for everyone.

---

*Built for the Isazi.ai AI for Accessibility Hackathon · March 2026*
