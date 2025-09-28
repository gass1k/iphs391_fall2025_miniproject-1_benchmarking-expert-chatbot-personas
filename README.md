# Mini-Project 1 — Benchmarking Expert Chatbot Personas (Carl Jung)

**Course:** IPHS 391 (Fall 2025)  
**Persona:** Carl Gustav Jung (educational)  
**Goal:** Show a high-quality persona, document the design, provide conversation evidence, and evaluate it with a rubric that yields a 0–100 score.

---

## Overview
This repository contains a complete submission for Mini-Project 1. It defines a Carl Jung educational persona, showcases a 10-turn conversation, and scores the result with a transparent rubric. The report summarizes design choices, evidence, and evaluation.

**Highlights**
- Clear persona spec: plain definitions first, simple examples, light reflection, educational scope.
- 10-turn chat demonstrating shadow, projection, archetypes, dreams, individuation, anima/animus, symbols, and typology.
- Rubric with 6 factors (weights sum to 1.0) and a worksheet for reproducible scoring.

---

## Methodology
1. **Persona Design**  
   Iterative metaprompting to refine scope, voice, and method. Final persona lives in `prompt_persona.txt`.
2. **Conversation Evidence**  
   A curated 10-turn sample stored in `chat_history.md` shows the persona’s behavior on common Jung topics.
3. **Evaluation Framework**  
   `chat_rubric.txt` specifies factors, indicators, and scoring bands; a worksheet computes the final score.
4. **Analysis Report**  
   `mp1_chatbot_report.docx` explains choices, applies the rubric, and records results.

---

## Results (from the report)
- **Final score:** 91/100  
- Strengths: accurate Jung framing, crisp definitions, concrete mini-frameworks and exercises, explicit scope limits  
- Improvements: add contrastive examples and optional fast vs thorough paths for journaling

---

## Files
- `prompt_persona.txt` — Final Carl Jung persona prompt (educational scope).  
- `metaprompt_history.txt` — Iterations and design rationale.  
- `chat_history.md` — 10-turn showcase conversation.  
- `chat_rubric.txt` — Final evaluation rubric with factors, weights, and worksheet.  
- `chat_rubric_history.md` — Rubric creation prompt/response history.  
- `mp1_chatbot_report.docx` — 1–2 page analysis report.  
- `README.md` — This document.

---

## How to Reproduce / Use
1. **Load the Persona**  
   Copy the contents of `prompt_persona.txt` into your chat system’s system prompt.
2. **Run a Conversation**  
   Ask questions on shadow, archetypes, dreams, individuation, anima/animus, symbols, or typology. Save the best 10 turns.
3. **Score with the Rubric**  
   Open `chat_rubric.txt`, fill the worksheet with 0–100 per factor, multiply by weights, and sum for a final score.
4. **Document**  
   Save the new chat to `chat_history.md` (or keep the existing one) and update the report if needed.

---

## Notes on Scope and Safety
The persona is educational only. It explains ideas and gives reflective exercises, not diagnosis or therapy. For mental health concerns, consult a licensed professional.
