# Portfolio Project — CLAUDE.md

## About Me (context for all content edits)
- Name: Anil Kumar
- Current role: AI/ML Engineer at Secninjaz Technologies LLP, New Delhi (Jun 2026 – Present)
- Previously: AI/ML Intern at the same company (Mar 2026 – Jun 2026)
- Education: M.Tech, Computer Science and Engineering, IIT (ISM) Dhanbad, CGPA 7.92
- Location: Jodhpur, India
- Contact: anilkumarbarupal.01@gmail.com | +91 9783039318
- LinkedIn: linkedin.com/in/anilkbarupal
- Live site: https://anilkb.surge.sh/
- Tone: confident working professional, NOT "student" / "aspiring" / "learning" framing —
  portfolio currently reflects college days and needs a full tone shift

## Tech Stack
<!-- Run /init or let Claude inspect the repo to auto-fill this; update once confirmed -->
- Framework: [fill in — React / Next.js / plain HTML-CSS-JS]
- Styling: [fill in — Tailwind / CSS Modules / plain CSS]
- Deployment: Surge (surge.sh)

## Project Structure
<!-- Update after Claude explores the repo -->
- `src/components/` — page sections (About, Experience, Projects, Skills, Contact)
- `src/data/` — content data (if content is separated from components)
- `public/` — static assets, resume PDF, images

## Live Site Sections (confirmed from https://anilkb.surge.sh/)
The site nav has: Home, About, Experience, Services, Projects, Skills,
Certifications, Events, Contact. Every one of these needs a pass — not
just Experience/Projects/Skills. Map resume content onto them as below.

## Conventions
- Keep content data-driven where possible — edit a data file, not JSX/HTML directly, for text-only changes
- Match existing code style already present in the repo (indentation, naming, component patterns)

## Content to Update

### Home / Hero
- Headline currently reads "M.Tech CSE @ IIT (ISM) Dhanbad" — replace with something like
  "AI/ML Engineer @ Secninjaz Technologies" (or a short professional tagline)
- Keep "View Projects" / "Download Resume" / "Contact" CTA buttons as-is unless asked
- Swap resume file behind "Download Resume" for the attached PDF (Anil-Kumar-AI-ML-Engineer.pdf)

### Experience (add/replace)
- AI/ML Engineer — Secninjaz Technologies LLP, New Delhi — Jun 2026–Present
  - Leads a team of 5 evaluating opportunities in the drone industry; delivered proposals that expanded addressable market
  - Builds end-to-end LLM solutions on on-premise NVIDIA H200 GPU infrastructure; authored a local LLM deployment proposal submitted to a state government
  - Works with the core AI team on the org's transition to an AI-native organization
- AI/ML Intern — Secninjaz Technologies LLP, New Delhi — Mar 2026–Jun 2026
  - Delivered AI/ML integrations across multiple POC initiatives, translating business requirements into technical solutions
  - Evaluated federated learning and presented commercial viability to the internal business committee
  - Solo-designed and submitted a full solution for the CDSCO–IndiaAI Health Innovation Acceleration Hackathon
- Vice President — CSES, IIT (ISM) Dhanbad — Feb 2024–Feb 2025 (keep as leadership entry, not primary focus)

### Skills (update list)
- Languages: Python, C++, SQL, C
- AI/NLP/GenAI: RAG, Prompt Engineering, LLM Pipelines, Hugging Face Transformers, LangChain, Agentic AI
- Backend & APIs: FastAPI, REST APIs, Docker, Git, Linux
- Databases/Retrieval: PostgreSQL, FAISS, Vector Databases, Hybrid Search, Reranking

### Projects (add/update)
- **HomeoBuddy** — RAG-powered chatbot (Python, LangChain, RAG, NLP, Llama 2-7B, Mistral 7B)
  - Llama-2 chatbot generating structured, symptom-based homeopathy recommendations
  - GPT-3.5-based evaluation system improving accuracy by 82.3%; Mistral 7B for chat-PDF functionality
- **MasterPlay** — AI research agent (Python, ChromaDB, RAG, LLM, agentic workflow)
  - Stateful RAG agent generating structured, factual video game reports
  - Tavily API web-search fallback expanding query coverage by 55%; state-machine-based evaluation improving retrieval accuracy by 28%

### Achievements (add)
- 96th percentile, GATE CS 2024 (top 4% of 150K+ candidates)
- AIR 2, SRMC'2025 Round 1 (organized by IIT Madras & IIT Bombay)
- 1st place (problem statement), Agglomeration 1.0, IIT (ISM) Dhanbad

### Education (keep, de-emphasize relative to experience)
- M.Tech, CSE, IIT (ISM) Dhanbad — CGPA 7.92/10

### Services
<!-- Resume has no explicit "services" list — Claude should read the current
     site content in this section before deciding whether to keep, trim, or
     rewrite it. Do not invent freelance offerings not implied by the resume;
     flag this section for Anil to confirm if it needs new content. -->
- If currently framed around college/freelance work, update framing to reflect
  professional AI/ML engineering services (e.g. LLM solution design, RAG pipeline
  development, ML consulting) — confirm exact wording with Anil before publishing

### Certifications
<!-- Resume has no certifications listed. If the live site currently shows
     certifications, keep them as-is unless they're outdated/irrelevant.
     Do not fabricate new certifications. Flag for Anil to confirm. -->

### Events (map from resume achievements/leadership)
- CDSCO–IndiaAI Health Innovation Acceleration Hackathon — solo participant, designed and submitted a full end-to-end solution
- Agglomeration 1.0, IIT (ISM) Dhanbad — 1st place in problem statement (5th/77 overall)
- SRMC'2025 Round 1 (IIT Madras & IIT Bombay) — AIR 2
- Yaadein'25, Udbhav'25, Agglomeration 2.0 — led operations/logistics as VP, CSES IIT (ISM) Dhanbad (500+ participants)

### General changes
- Remove/rework any "currently pursuing" or "student" language sitewide
- Move old college-only projects (if any exist beyond HomeoBuddy/MasterPlay) to an "Archive" or "Earlier Projects" section instead of deleting
- Update resume PDF in `public/` to the latest version (attached resume: Anil-Kumar-AI-ML-Engineer.pdf)
- Update meta/title tags and any "About" hero text to reflect current role

## Do NOT
- Don't change color scheme, layout, or overall design system unless explicitly asked
- Don't remove the CSES/Vice President entry — reframe it as leadership experience, don't delete
- Dont delete anything from there just modify if needed


<!-- maintainer note: fill in tech stack + project structure sections after first Claude Code session inspects the repo -->