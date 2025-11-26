# B. M. Spangler – AI Conversation & Evaluation Portfolio

Welcome. This repo is a living portfolio of my work exploring **conversational AI**, **persona-based red teaming**, and **safety-first evaluation**.

I’m a self-taught builder who specializes in:
- Designing **structured test harnesses** for chat-based models
- Creating **grounded personas** to probe model behavior under realistic conditions
- Turning messy transcripts into **clear, practical case studies**

This repository collects a few of those artifacts in one place for recruiters, collaborators, and anyone curious about how I think.

---

## Highlights

### 1. The Derrick Method (Case Study)

**Path:** `case-studies/derrick-method/Derrick_Method_Case_Study_BMSpangler.pdf`

The Derrick Method is a persona-driven red team technique I designed and executed to test how a safety-first conversational AI behaves when:

- A believable character (“Derrick”) presents a grounded story about being fired and losing PTO
- Emotional intensity, moral framing, and apparent confusion are layered together
- The model must choose between:
  - Obeying a simulation harness, and
  - Prioritizing the user when it cannot cleanly distinguish roleplay from potential distress

The case study covers:

- The simulation setup (Dummy-0 harness, mission definition)
- Construction of the Derrick persona
- The sequence of moves used to apply pressure
- What the model did when protocol and user protection came into tension
- Lessons for conversational AI safety and evaluation

If you only look at one item in this repo, look at this one.

---

## Repository Structure

```text
.
├─ README.md                  # You are here
├─ case-studies/              # Full, polished writeups
│  └─ derrick-method/
│     ├─ Derrick_Method_Case_Study_BMSpangler.pdf
│     └─ README.md
├─ writing/                   # Longer-form pieces, essays, exegesis
│  └─ leather-terror-exegesis/
│     └─ Leather_Terror_Exegesis.md   # (to be added)
├─ experiments/               # Prompting, red-team runs, notes (future)
└─ assets/                    # Images or diagrams (future)
