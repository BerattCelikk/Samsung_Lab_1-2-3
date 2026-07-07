# Lab 1 — Prompt Comparison: A/B Testing

## Bad Prompt

> Write a motivation letter for a software engineering internship.

## Improved Prompt (Structured)

> **Role:** You are a professional career consultant and technical recruiter.
>
> **Goal:** Write a compelling motivation letter for an R&D Software Engineering internship at Baykar.
>
> **Context:** The applicant is Berat Erol Çelik, a 4th-year Software Engineering student at Istanbul Aydın University and founder of the AI startup Coddiom. He has hands-on experience building AI agents, orchestrating workflows with n8n, and practicing vibe coding with GitHub Copilot and Claude Code.
>
> **Constraints:**
> - Maximum 400 words
> - Single page
> - Formal but confident tone
> - Do not use clichés or generic filler
>
> **Style:**
> - Professional and concise
> - Each paragraph should demonstrate a specific skill or project outcome
> - Show, don't tell — use concrete examples
>
> **Output Format:**
> - Subject line
> - Salutation
> - 3 body paragraphs (introduction, experience & projects, why Baykar)
> - Closing

## Analysis

| Aspect | Bad Prompt | Improved Prompt |
|--------|-----------|----------------|
| **Clarity** | Vague — no details about the applicant or the company | Explicit role, context, and constraints eliminate ambiguity |
| **Hallucination risk** | High — the model may invent skills, companies, or experiences | Low — every claim is grounded in real facts about the applicant |
| **Output quality** | Generic — likely produces a templated, forgettable letter | Tailored — ready-to-use content that highlights relevant projects (Coddiom, n8n, vibe coding) |
| **Control** | None — no guidance on length, tone, or structure | Full control via constraints and format specifiers |

The structured prompt prevents hallucinations because it grounds the model in specific facts (name, university, startup, technologies) and constrains the output format. Without these guardrails, a general-purpose LLM tends to invent plausible-sounding but false details — a common failure mode for recruitment-related generation tasks.
