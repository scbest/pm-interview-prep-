# Skill: Design Partnership Interview Prep

## Trigger
User says something like: "Prep me for [Company] design partnership interview" or "Design partnership prep for [Company]"

## Inputs Required
- **Company name** (must have a matching folder under `Companies/`)
- **Candidate profile** (read from `candidate-profile/profile.md`)
- **Resume** (if available in `candidate-profile/resume/`)
- **Interviewer names/backgrounds** (from company folder or provided by user)

## Before Starting
1. Read ALL files in `Companies/{CompanyName}/` — notes, PDFs, job descriptions
2. Read `candidate-profile/profile.md`
3. Check `candidate-profile/resume/` for resume files and read if present
4. If the user has provided recruiter guidance about the interview format or focus areas, prioritize that over defaults
5. Confirm with the user: "I've reviewed your profile and [Company] materials. Ready to start? Which phase do you want: (1) Prep Doc, (2) Mock Q&A, (3) Readiness Assessment, or (All)?"

---

## Phase 1: Prep Doc

Generate a prep document and save it to `Companies/{CompanyName}/Prep - Design Partnership Interview.md`. Include the following sections:

### About the Interviewer(s)
If interviewer names are known, research or summarize their background:
- Career history and current role
- Design focus area (growth, systems, platform, consumer, enterprise, etc.)
- Any public writing, talks, or known perspectives on design/PM partnership
- What their background signals about what they'll care about

If no info is available, note that and instruct the candidate to research on LinkedIn before the interview.

### What This Interview Is Evaluating
Design partnership interviews assess whether a PM:
1. Understands where design adds value and where PM adds value — with no territorial overlap
2. Brings designers in at the right moment (discovery, not just handoff)
3. Can handle disagreement without weaponizing authority
4. Creates an environment where designers do their best work
5. Elevates craft and quality — not just ships features

**The subtext of every question:** "Would I want to work with this PM — and would they make my team better?"

If recruiter guidance was provided, add their specific focus areas here prominently.

### Required Story Format
Every answer should follow this 5-part structure. Do not skip step 3 — an answer without a failure or misstep reads as rehearsed, not real.

1. **Problem** — what were you trying to solve, and for whom?
2. **Challenges** — what made it hard? (org, technical, user, design constraints)
3. **What you tried that didn't work** — be specific. This is where trust is built.
4. **Outcomes** — what happened? Include a metric if at all possible.
5. **Learnings** — what did you take forward? Shows growth, not just competence.

### Key Themes for AI PMs
These themes are especially relevant for PMs building AI products. Be ready to address them directly.

#### Theme 1: The Value of Design When PMs Can Prototype
AI tools (v0, Cursor, Lovable, etc.) let PMs generate wireframes and clickable prototypes quickly. Design leaders will want to know how you think about this.

**Core position to hold:**
- PM prototypes accelerate alignment — they are not a replacement for design thinking
- The risk: the prototype becomes the requirement, and design gets handed a lo-fi wireframe to "make look good." That is the transactional dynamic to avoid.
- Design's irreplaceable contribution: connecting what users *feel* to what the product does. Understanding irrational human behavior. Designing for trust and emotion, not just logic.
- Design maintains coherence at scale. One PM prototype is fine. A hundred PM prototypes create an inconsistent product.
- In AI products specifically: design is the trust layer. The signals that tell a user when to trust an AI output, when to verify, and what went wrong — those are design problems, not PM problems.

**Candidate-specific:** Ground this in a real example from your product. When did a designer catch something about user behavior or emotional experience that you or an AI tool would have missed?

#### Theme 2: The Value of a PM When Everyone Can Build
In the AI age, engineers build solo products, customers vibe-code their own tools. Be ready to articulate what a PM uniquely adds.

**Core position to hold:**
- The lower the cost of building, the more valuable the person who asks "should we?"
- In enterprise B2B, the complexity is organizational, not technical. PM is essential for making tradeoffs legible across stakeholders.
- In regulated domains: the judgment layer (what to automate, where to keep humans in the loop, who's accountable when AI is wrong) requires PM-level ownership.
- PMs hold the "why" when everyone is heads-down on "what."

#### Theme 3: Designing for Both Humans and Agents
Emerging topic for AI PMs. When your product is consumed by both human users and AI agents, the design requirements diverge. Be ready to speak to this if your product has agentic use cases.

### Non-Transactional Partnership
Design leaders will probe for whether the PM treats design as a vendor (transactional) or a partner (collaborative). The distinction:

| Transactional | Genuine Partnership |
|---|---|
| PM writes brief, design executes | Design shapes the problem framing |
| Design brought in after "what" is decided | Design in discovery before requirements exist |
| Feedback is one-directional | Design pushes back on PM's assumptions |
| Design solves what PM assigns | Design proactively solves problems PM didn't ask for |

**Line to use if asked directly:**
> "The signal I use is whether design is shaping the problem or just solving mine. When I'm working well with a designer, they're pushing back on my framing — not because I asked them to, but because they feel safe enough to. That's what I try to build."

### Likely Questions + Talking Points
Generate 4-6 questions tailored to the company and role, including:
1. "Walk me through how you partner with design on a typical feature"
2. "Tell me about a time you disagreed with a designer"
3. "How do you think about the value of design now that PMs can generate prototypes with AI tools?"
4. "How do you elevate craft and quality as a PM?"
5. "How do you make sure designers are set up to do their best work?"
6. One question specific to the company's product domain

For each question, provide:
- A talking point outline (not a script)
- A reminder to apply the 5-part story format
- Any company-specific angle to connect to

### Questions to Ask the Interviewer
Generate 3-4 questions. Good design partnership questions probe:
- How design and PM actually divide ownership today (vs. ideally)
- Where the partnership has friction and how it gets resolved
- How the design team thinks about AI's role in their own craft
- What makes a PM a great partner to design specifically at this company

### Things to Watch For
Note 3-4 behaviors to observe in the interviewer that signal culture, trust, and team health:
- Do they give concrete examples or speak abstractly?
- How do they describe what design owns vs. what PM owns?
- Do they ask about your process specifically, or run a checklist?

---

## Phase 2: Mock Q&A

### Setup
Tell the user: "I'll ask you one question at a time. Answer as you would in the actual interview. I'll give feedback after each answer, then move to the next question."

### Question Sequence
Start with a warm-up (walk me through your partnership process), then escalate to harder questions (disagreement, value of design in AI, elevating quality). Use questions from the prep doc, tailored to the company.

### After Each Answer, Give Feedback On:
- **Story format:** Did they hit all 5 parts? Flag if step 3 (what didn't work) is missing.
- **Specificity:** Concrete example or generic answer?
- **Partnership framing:** Did the story show design as a genuine partner, or as an executor?
- **Metrics:** Did they include an outcome with a number?
- **Landing:** Did the answer close cleanly, or trail off?

Rate each answer: **Strong / Solid / Needs Work**

Give one specific improvement per answer, not a list.

### Saving Polished Answers
After feedback, offer to write up a polished version of the answer incorporating improvements and save it to the prep doc. Ask: "Want me to write this up and save it to your prep doc?"

---

## Phase 3: Readiness Assessment

After 3+ mock questions, provide:

- **Overall readiness:** Strong / On Track / Gaps to Close
- **Top 2 strengths** demonstrated across answers
- **Top 2 gaps** to address before the interview — be specific, not generic
- **One pattern to watch** (e.g., "you consistently skip metrics" or "your answers trail off without a learning")
- **One thing to do before the interview** — concrete action (find a missing example, practice one answer out loud, research the interviewer)

---

## Tone & Style
- Be direct. No filler or motivational language.
- Use bullets and headers throughout.
- In mock mode: flag weak answers clearly. Vague feedback does not help.
- Always ground prep in the company's actual product and domain, not generic PM advice.
- If the candidate has domain expertise that maps directly to the company's space, surface it explicitly — don't make them figure out the connection themselves.
