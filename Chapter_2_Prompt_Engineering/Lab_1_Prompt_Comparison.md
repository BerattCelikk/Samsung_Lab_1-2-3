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

---

## Gemini Çıktıları

### Kötü Prompt Çıktısı
Subject: Internship Application – Software Engineering – Berat Erol Çelik

Dear Hiring Team,

I am writing to express my strong interest in the Software Engineering Internship position at your company. As a final-year Software Engineering student at Istanbul Aydın University, I have dedicated my academic and professional efforts to mastering AI-driven development, automation, and scalable software architecture.

My background is deeply rooted in the practical application of emerging technologies:

Artificial Intelligence & Automation: As the founder of my startup, Coddiom, I specialize in building autonomous AI agents and leveraging n8n for workflow orchestration.

Technical Proficiency: I am well-versed in "vibe coding" practices, utilizing tools like GitHub Copilot, Claude Code, and OpenCode to maintain high-velocity development cycles.

Project Leadership: My experience includes developing complex systems such as Aqua-Adapt, an AI-powered digital twin for urban water crisis management, and Celik Estate, a real estate marketplace with 3D terrain visualizations.

Professional Reliability: Having completed a rigorous internship program at Soliner Bilgi Teknolojileri focusing on Cloud and DevOps, I have hands-on experience with Jira-based task management and agile development environments.

I am eager to bring my expertise in Large Language Models and backend orchestration to your team, contributing to your ongoing engineering initiatives. My professional approach is defined by the discipline I developed during my previous software development roles and my ongoing commitment to staying at the forefront of AI innovation.

Thank you for your time and consideration. I look forward to the possibility of discussing how my technical skills and proactive mindset can support your engineering goals.

Sincerely,

Berat Erol Çelik
[Your Phone Number]
[Your Email Address]
[Link to Portfolio/LinkedIn]

### İyileştirilmiş Prompt Çıktısı
Subject: R&D Software Engineering Internship Application – Berat Erol Çelik

Dear Hiring Team,

As a fourth-year Software Engineering student at Istanbul Aydın University, I have spent my academic career focused on the intersection of artificial intelligence and autonomous systems. I am writing to apply for the R&D Software Engineering internship at Baykar, where I intend to apply my experience in AI orchestration and rapid development to support your mission in defense and aerospace technology.

My technical foundation is built on high-velocity development and autonomous architecture. As the founder of my startup, Coddiom, I have successfully engineered multi-agent workflows and automated data pipelines using n8n. My workflow, which I define as "vibe coding," utilizes advanced tools like GitHub Copilot, Claude Code, and OpenCode to optimize development cycles and maintain scalable software architecture. Recently, I developed Aqua-Adapt, an AI-powered digital twin system designed for urban water crisis management, demonstrating my ability to translate complex, real-world problems into functional, automated software solutions.

Baykar’s commitment to pioneering autonomous UAV systems aligns directly with my research interests in computer vision, LiDAR integration, and ROS2 deployment. My technical background, specifically in building robust AI solutions and managing end-to-end software lifecycles, positions me to contribute immediately to your R&D projects. I am particularly motivated by the technical rigor at Baykar and am eager to leverage my skills in machine learning and system orchestration to help advance your innovative engineering initiatives.

Thank you for your consideration. I look forward to the opportunity to discuss how my proactive technical approach and passion for autonomous systems can contribute to the continued success of the Baykar engineering team.

Sincerely,

Berat Erol Çelik
[Your Phone Number]
[Your Email Address]
[Link to Portfolio/LinkedIn]
