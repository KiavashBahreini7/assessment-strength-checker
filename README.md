# Assessment Strength Checker

**An AI-Powered Tool for Evaluating Assignment Resistance to Generative AI**

> *"The question is no longer whether students have access to AI. They do. The question is whether your assignments are designed to require their thinking still."*

---

**Kiavash Bahreini, Ph.D.**  
Associate Teaching Professor, Computer Science  
Knight Foundation School of Computing and Information Sciences  
Florida International University  
kbahrein@fiu.edu  
https://github.com/KiavashBahreini7/assessment-strength-checker  

---

## What This Tool Does

The **Assessment Strength Checker** is a free, single-file, browser-based tool built for university faculty across all disciplines. Paste any assignment prompt and receive an instant AI-resistance score powered by Google Gemini 2.5 Flash — along with four dimension scores, three concrete redesign suggestions, and a fully rewritten version of your prompt that preserves your learning objective while significantly raising its resistance to AI completion.

No installation. No server. No subscription. Open the HTML file in any browser, paste your free Gemini API key, and you are ready in under two minutes.

---

## What You Get

| Output | Description |
|--------|-------------|
| AI-Resistance Score | 1–10 scale. 1 = Gemini completes it instantly. 9 = requires genuine human engagement. |
| Verdict | High Resistance / Moderate Vulnerability / High Vulnerability |
| Authenticity Required | Does the task demand something only this specific student can provide? |
| Process Visibility | Must the student show their thinking, not just a final product? |
| Specificity to Context | Is the prompt anchored to a scenario that AI cannot access? |
| Higher-Order Thinking | Does this require analysis and judgment, or recall? |
| Three Suggestions | Specific, actionable redesign steps you can apply this week |
| Redesigned Prompt | Your prompt rewritten to be meaningfully more AI-resistant |

---

## Quick Start

1. Download Assessment_Strength_Checker.html from this repository
2. Get a free Gemini API key at https://aistudio.google.com/apikey
3. Open the HTML file in any browser
4. Paste your API key in the blue banner at the top
5. Type or paste your assignment prompt and click Analyze

---

## Step-by-Step Setup Guide

### STEP 1 — Create a Google Account

Skip this step if you already have a Gmail or Google account.

1. Go to https://accounts.google.com/signup
2. Fill in your name and choose a Gmail address
3. Choose a password and complete verification
4. Your Google account is ready

### STEP 2 — Get Your Free Gemini API Key

1. Go to https://aistudio.google.com/apikey
2. Sign in with your Google account
3. Click the blue Create API key button
4. Select Create API key in new project
5. Copy the key that starts with AIza...
6. Paste it somewhere temporarily — you will need it in Step 4

Free tier — no credit card required. Hundreds of analyses per day. The key never expires unless you delete it. Your key is stored only in your browser session and is never uploaded to any server.

### STEP 3 — Download and Open the Tool

1. On this GitHub page, click the green Code button at the top right
2. Click Download ZIP
3. Extract the ZIP file on your computer
4. Find Assessment_Strength_Checker.html
5. Double-click it — it opens in your default browser

### STEP 4 — Paste Your API Key

1. At the top of the page, find the dark blue banner labeled Gemini API Key
2. Click inside the field and paste your key
3. Click the eye icon to verify that it has pasted correctly
4. The key is stored only in your browser session

### STEP 5 — Analyze Your First Assignment

1. Paste any assignment prompt into the text box
2. Optionally, click a discipline chip to load a Level 3 example prompt
3. Optionally select your discipline for more targeted suggestions
4. Click Analyze My Assignment or press Ctrl+Enter
5. Results appear in 5 to 10 seconds
6. Scroll down to see your score, dimensions, suggestions, and redesigned prompt

---

## How to Read Your Results

**Score (1–10)**
How easily can AI complete this assignment? 1 means Gemini solves it instantly and perfectly. 9 means the assignment genuinely requires the student's own thinking, experience, and context.

**Verdict**
High AI-Resistance means the assignment is well-designed for the AI age. Moderate Vulnerability means a motivated student using AI strategically could still produce convincing work without a deep understanding. High AI-Vulnerability means the assignment is at serious risk.

**Authenticity Required**
Does the task demand something only this specific student can provide — their clinical observation, their neighborhood, their learning history, their internship? If yes, AI cannot supply it.

**Process Visibility**
Must the student show how they thought, not just what they produced? Submitting a draft and a revision with a rationale for every change scores high here.

**Specificity to Context**
Is the prompt anchored to a particular scenario, situation, or constraint that rules out generic AI answers?

**Higher-Order Thinking**
Does the assignment require analysis, evaluation, synthesis, and creation, or only recall and description?

**Three Suggestions**
Specific, actionable changes tailored to your exact assignment. Each targets the dimension where your score was weakest.

**Redesigned Version**
A rewrite of your original prompt that preserves your learning objective but significantly raises AI-resistance.

---

## Three Levels of AI Resistance — Examples Across Eight Disciplines

### Level 1 — High Vulnerability (Score 1–3)

AI completes these in under 60 seconds. The student contributes nothing original.

| Discipline | Example Prompt |
|------------|----------------|
| Computer Science | Explain what a linked list is and compare it to an array. Give one real-world example of each. |
| Nursing | Define the five rights of medication administration and explain why each one is important. |
| Business | Describe the four Ps of marketing with one example each. |
| Education | List and explain Bloom's six levels of the taxonomy, with one classroom example per level. |
| Law | Explain the doctrine of precedent in common law and give two landmark examples. |
| Psychology | Describe the key differences between classical and operant conditioning with two examples of each. |
| Architecture | Explain the principles of biophilic design and describe five key benefits. |
| Arts and Humanities | Compare the Baroque and Romantic periods in Western music and name two major composers from each. |

### Level 2 — Moderate Vulnerability (Score 4–6)

AI can help significantly, but the student still needs to direct, review, and make decisions.

| Discipline | Example Prompt |
|------------|----------------|
| Computer Science | Compare three data structures for a ride-sharing app serving 10,000 concurrent users. Justify your recommendation. |
| Nursing | Write a care plan for a 72-year-old with congestive heart failure admitted with shortness of breath and peripheral edema. |
| Business | A retail chain has seen a 30% decline in foot traffic over the past 2 years. Diagnose causes using three-course frameworks and recommend a recovery strategy. |
| Education | Design a two-week interdisciplinary unit for Grade 8 on climate change with differentiation strategies for diverse learners. |
| Law | Analyze the legal liability of a company that collected biometric data from employees without explicit written consent. |
| Psychology | Using a biopsychosocial framework, analyze a 17-year-old presenting with anxiety and social withdrawal after their parents' divorce. |
| Architecture | Design a 200-seat community theater with a budget of $8 million. Address acoustics, accessibility, and sustainability. |
| Arts and Humanities | Analyze a work of visual art produced between 1950 and 1980 that responded directly to a political event of its time. |

### Level 3 — High Resistance (Score 7–9)

These require the student to show up as a specific person with specific experiences. AI cannot fake either.

| Discipline | Example Prompt |
|------------|----------------|
| Computer Science | Design a scheduling system for a clinic with 12 doctors on different shifts. Identify 3 data structures, walk through conflict detection logic, reflect on one design trade-off, and identify one privacy risk. Defend your proposal in a live 10-minute Q&A. |
| Nursing | Identify a moment from your most recent clinical placement where a communication breakdown affected patient care. Analyze the contributing factors, connect your analysis to a person-centered care framework from this course, and propose one concrete change to ward protocol. Discuss with your clinical instructor. |
| Business | Visit a locally owned business in your neighborhood that you have personally patronized in the last 30 days. Do not use any chain or franchise. Analyze one specific marketing or operational decision using two course frameworks. Propose a 90-day improvement plan under $2,000. Present in class and answer objections. |
| Education | Identify a student from your practicum placement whose needs are not being met by current instruction. Design a 3-session evidence-based intervention, implement one session, document your observations, and revise your plan. Submit your original plan, session notes, and revised plan with a written rationale for every change. |
| Law | Attend a live public court proceeding or regulatory hearing you have never attended before. Identify one moment where you witnessed a tension between the letter of the law and what you personally perceived as a just outcome. Analyze that tension using two jurisprudential frameworks from this course. Write a 750-word reflection. Discuss in a one-on-one oral examination with your professor. |
| Psychology | Over the next two weeks, keep a structured daily log applying one psychological concept from this course to something you personally observed or experienced each day. At the end, select the three entries that surprised you most and write a 650-word analysis of what each surprise revealed about the gap between understanding a concept intellectually and recognizing it in yourself. |
| Architecture | Spend one hour walking through a public space in your city that you use regularly. Observe how different groups of people use the space, where they gather, and where they avoid. Identify one design feature creating a negative social outcome for a specific group. Propose a low-cost intervention costing less than $50,000 and defend your observations to a panel that includes at least one classmate who uses a different part of the city. |
| Arts and Humanities | Visit a live performance or exhibition in your city that is completely outside your usual cultural experience. Spend at least 90 minutes there. Write a 750-word critical response that honestly traces your reaction — what confused you, what moved you, what you resisted, and what shifted. Include one moment where you identified an assumption you were making and describe what happened when you examined it. Read a two-minute excerpt in class and take unscripted questions from peers. |

---

## Three Design Moves That Raise Any Assignment

**Move 01 — Anchor It to What Only the Student Has**  
Their clinical placement. Their neighborhood. Their own learning history. Their internship. AI does not have any of these. The moment your prompt requires a student to draw on their specific lived experience, the assignment becomes significantly harder to outsource.

Before: Analyze a marketing crisis.  
After: Analyze a decision made by a business in your own community that you visited personally.

**Move 02 — Add a Live Accountability Component**  
A 5-minute verbal defense. A brief in-class discussion. A Q&A after a presentation. A conversation with a clinical instructor. A student who genuinely engages with their work can answer spontaneous follow-up questions. A student who submitted an AI output cannot. Adding just one sentence — You will discuss this in a 5-minute conversation with your instructor — moved a test prompt from 5 out of 10 to 8 out of 10.

**Move 03 — Make the Process Visible**  
Require a draft and a revision with an explanation of what changed. Ask for a decision log. Request annotated AI transcripts. When students must show their thinking as it developed — not just the final product — the assignment measures learning, not output.

Submit: initial draft, peer feedback notes, revised version with rationale for every change.

---

## Color Themes

The tool includes eight built-in color themes. Click any colored circle in the top black bar to switch instantly. Your choice is saved automatically in your browser.

- Navy and Gold — FIU Classic
- Burnished Gold — darker metallic
- Gold and Ivory — warm background
- Burgundy and Champagne — elegant and distinctive
- Forest and Copper — warm and sophisticated
- Sapphire and Gold — cool and professional
- Crimson and Gold — bold and authoritative
- Steel and Rose Gold — contemporary and refined

---

## Files in This Repository

| File | Description |
|------|-------------|
| Assessment_Strength_Checker.html | The main tool — open in any browser |
| Assessment_Presentation_Bahreini.pptx | 8-slide faculty presentation deck |
| Assessment_Strength_Checker_Guide.docx | Full faculty guide with all examples |
| qr_code.png | QR code linking to this repository |
| LICENSE.txt | CC BY 4.0 license with required citation |
| README.md | This file |

---

## How to Cite This Tool

Any use, adaptation, presentation, or publication referencing this tool must include the following attribution.

APA 7th Edition:

Bahreini, K. (2026). Assessment Strength Checker: An AI-powered tool for evaluating assignment resistance to generative AI (Version 1.0) [Software]. Knight Foundation School of Computing and Information Sciences, Florida International University. kbahrein@fiu.edu https://doi.org/10.5281/zenodo.XXXXXXX

BibTeX:

@software{bahreini2026asc,
  author      = {Bahreini, Kiavash},
  title       = {Assessment Strength Checker},
  year        = {2026},
  version     = {1.0},
  institution = {KFSCIS, Florida International University},
  email       = {kbahrein@fiu.edu},
  url         = {https://doi.org/10.5281/zenodo.XXXXXXX},
  license     = {CC BY 4.0}
}

Chicago:

Bahreini, Kiavash. 2026. Assessment Strength Checker. Version 1.0. Software. Knight Foundation School of Computing and Information Sciences, Florida International University. https://doi.org/10.5281/zenodo.XXXXXXX

---

## License

This tool is released under the Creative Commons Attribution 4.0 International license CC BY 4.0. You can use, share, and adapt for any purpose, including commercial use, as long as you give appropriate credit using the citation format above. Full license text at https://creativecommons.org/licenses/by/4.0/

---

Designed to help faculty design assessments that make AI a tool for learning — not a shortcut around it.

Kiavash Bahreini, Ph.D.  
Associate Teaching Professor, Computer Science  
Knight Foundation School of Computing and Information Sciences  
Florida International University · CASE 337  
kbahrein@fiu.edu  
https://github.com/KiavashBahreini7/assessment-strength-checker
