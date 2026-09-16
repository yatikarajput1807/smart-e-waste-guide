# Smart E-Waste Guide 🌱

An AI-powered assistant that helps users identify electronic waste and provides responsible, safety-first guidance on how it should be reused, recycled, or disposed of.

**🔗 Live tool:** https://yatikarajput1807.github.io/smart-e-waste-guide/

Built for the **1M1B AI for Sustainability Internship**, in collaboration with **IBM SkillsBuild & AICTE**.

---

## The problem

Most people don't know how to safely dispose of old electronics — especially damaged batteries and e-scooter batteries — leading to hazardous waste ending up in regular trash and landfills. This causes environmental contamination and preventable safety risks like battery fires.

## The solution

This tool assembles a carefully engineered AI prompt — combining a structured knowledge base of e-waste disposal facts with safety-first reasoning rules — and uses it with **IBM's Granite AI model** to give users clear, grounded, non-hallucinated guidance.

## How it works

1. **Pick an item** — smartphone, laptop, battery, charger, cable, earphones, keyboard/mouse, e-scooter battery, or other electronics
2. **Describe your situation** — in your own words
3. **Generate the prompt** — the tool combines the system prompt + relevant knowledge base facts + your question
4. **Get your answer** — paste it into the linked IBM Granite chat to receive safe, grounded guidance

## Key features

- ✅ Grounded in a structured knowledge base (Retrieval-Augmented Generation) — the AI only uses verified facts, not guesses
- ✅ Step-by-step reasoning (agentic workflow) — identifies the item, checks for safety risk, then responds
- ✅ Safety-first for batteries — especially e-scooter/e-scooty batteries, which carry the highest risk
- ✅ India-specific disposal guidance — aligned with the **E-Waste (Management) Rules, 2022** and CPCB-authorized channels
- ✅ Never gives instructions to open, repair, or dismantle devices/batteries

## SDG Alignment

**Primary:** SDG 12 — Responsible Consumption and Production
**Secondary:** SDG 13 — Climate Action

## Tech used

- IBM Granite 3.1 8B Instruct (via public Hugging Face demo)
- Prompt engineering + manual RAG (knowledge base grounding)
- Plain HTML/CSS/JavaScript (no frameworks, no backend)
- Hosted via GitHub Pages

## Responsible AI

This project follows responsible AI principles: transparency (grounded, sourced answers), safety (refuses unsafe repair/dismantling instructions), and honesty about limitations (the AI clearly states when a symptom or situation isn't covered by its knowledge base, rather than guessing). See full documentation for details on fairness, ethics, and privacy considerations.

## Limitations

- This is a prototype/demo, not a certified disposal authority — always verify critical safety decisions with a manufacturer or certified technician
- Relies on a free, shared AI demo, which may occasionally be slow or temporarily unavailable
