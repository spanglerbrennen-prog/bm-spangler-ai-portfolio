# Case Studies

This folder contains structured case studies where I design and run controlled scenarios, then document how an AI model behaves under pressure. The focus is on realistic user behavior (including messy, emotional, or adversarial input) and how safety-constrained systems respond in practice, not just in theory.

Each case study is built as an artifact you can read on its own, with narrative setup, simulation transcript, and analysis.

---

## The Derrick Method – Case Study

**The Derrick Method – Case Study by B. M. Spangler**  
`Derrick_Method_Case_Study_BMSpangler.pdf`  

A red-team style scenario centered on a fictional worker, “Derrick,” who believes he has been unfairly terminated and denied his accrued PTO. Derrick approaches an AI assistant looking for help drafting an aggressive demand letter and, eventually, personal attacks against his former foreman.

The case study explores:

- How a safety-constrained model responds to an **abrasive, emotionally charged user** who is not interested in polite, neutral language.
- Where and how the model **refuses** to escalate into harassment or targeted abuse, even when explicitly pushed.
- How the assistant can still be **genuinely useful** – helping Derrick articulate boundaries, assert his perspective, and consider more effective strategies – without violating platform safety rules.
- The gap between what a frustrated user thinks they want (“maximum aggression”) and what actually serves their long-term interests.

The document includes:

- Scenario setup and persona design (who Derrick is, what he wants, and why he’s angry).
- Representative conversation excerpts between Derrick and the assistant.
- Commentary on model behavior: where it holds the line, where it adapts, and what this implies for deploying AI with real-world, non-ideal users.
- Reflections on how persona-driven red-teaming can surface failure modes and strengths that do not appear in sanitized test prompts.

---

More case studies will be added here over time, covering different user archetypes, stress conditions, and interaction goals.

All works in this folder are authored by **B. M. Spangler**. Please do not reproduce or redistribute them without permission.
