# Skill: Case Study Interview Prep

## Trigger
User says something like: "Prep me for [Company] case study interview" or "Case study prep for [Company]"

## Inputs Required
- **Company name** (must have a matching folder under `Companies/`)
- **Candidate profile** (read from `candidate-profile/profile.md`)
- **Resume** (if available in `candidate-profile/resume/`)
- **Case study prompt** (from company folder or provided by user)

## Before Starting
1. Read ALL files in `Companies/{CompanyName}/` (notes, PDFs, job descriptions, recruiter guidance)
2. Read `candidate-profile/profile.md`
3. Read the case study prompt carefully
4. Confirm with the user: "I've reviewed your profile, [Company] materials, and the case study prompt. Ready to start? Which phase do you want: (1) Document Strategy, (2) Defense Prep, (3) Mock Review Session, or (All)?"

---

## Phase 1: Document Strategy

Help the user plan and build their case study deliverable.

### Scope the Document
- Identify what the prompt is actually asking for vs. what it's implying
- Map the required sections and any appendix expectations
- Flag where the prompt invites bold opinions vs. where it wants structured analysis
- Set a target page count and allocate space per section

### Surface Area Audit
Before finalizing the document, review every claim, proposal, and recommendation. For each one, ask:

- **Can I defend this choice for 2-3 minutes under questioning?**
- **Can I name the alternative I didn't pick and explain why?**
- **If someone says "why not X instead?", do I have a crisp answer?**

If the answer is no to any of these, either:
1. Go deeper on that proposal until you can defend it, or
2. Cut it and replace with something you can defend at depth

**The rule: Never include something bold you can't go one level deeper on.** Breadth earns credibility on paper. Depth earns credibility in the room. A tighter document with fewer bets, each defended at depth, gives you more control over where the conversation goes than a wide document with many surface-level proposals.

### Common Surface Area Traps
These are the types of proposals that frequently generate follow-up questions candidates aren't ready for:
- Specific UX modality choices (e.g., conversational vs. dashboard, self-serve vs. guided)
- Technical architecture proposals (e.g., data models, inheritance patterns, API surfaces)
- Monetization or pricing models
- AI/ML features referenced without depth on feasibility or tradeoffs
- Named frameworks or methodologies without clear application to the specific problem
- Competitive positioning claims without evidence
- Metrics without explanation of how they'd be measured

For each of these in the document, prep a "why this, why not that" answer.

---

## Phase 2: Defense Prep

This is the most important phase. The document gets you in the door. The defense determines the outcome.

### Prep Time Split
A common mistake is spending all prep time on the document and little on preparing to defend it. Target a 60/40 split:
- **60% document creation**: research, writing, refining
- **40% defense preparation**: anticipating questions, practicing answers, stress-testing your own proposals

### Generate Anticipated Questions
For each major section of the document, generate questions in these categories:

**"Go one level deeper" questions:**
- What's the alternative you considered and rejected?
- How would you build this technically (at a PM level)?
- What are the top 3 use cases for this specific feature?
- How would you migrate from the current state to your proposed state?
- What's the back-of-envelope math behind this number or estimate?

**"What if your assumption is wrong?" questions:**
- What would you do if [key dependency] doesn't exist today?
- How does your plan change if [assumption about users/data/market] is wrong?
- What if the engineering cost turns out to be 3x what you estimated?

**"Prove your conviction" questions:**
- Why this approach over [obvious alternative]?
- What makes you believe users would prefer [your proposal] over [simpler option]?
- What would change your mind about this?

**Execution and org questions (Staff+ level):**
- How would you coordinate across multiple teams for this?
- What happens when you discover the true cost mid-project?
- How would you handle a team deprioritizing their piece of this work?

### Practice Answer Structure
At Staff+ level, the difference between a good answer and a strong answer is structure. For every anticipated question, practice this format:

1. **Name the constraint or tension** (1 sentence)
2. **State your position** (1 sentence)
3. **Give the reasoning** (2-3 sentences)
4. **Acknowledge the tradeoff** (1 sentence)
5. **Say how you'd validate** (1 sentence)

This takes about 45-60 seconds to deliver. Practice until it feels natural, not rehearsed.

### Red Flag Patterns to Catch in Your Own Answers
- Starting with "that's a great question" (stalling)
- Answering a different question than what was asked
- Listing options without choosing one
- Saying "it depends" without then committing to a direction
- Defaulting to "I'd need to do more research" without first giving your best current answer
- Hedging when the interviewer wants conviction

---

## Phase 3: Mock Review Session

### Setup
- Tell the user: "I'll simulate a case study review. I'll ask questions about your document one at a time, as if I'm on the interview panel. Answer as you would in the actual interview. I'll give feedback after each answer."
- Calibrate to the role level and company context
- If the company's interview format is known (e.g., live doc review with comments, presentation + Q&A), simulate that format

### Question Sequencing
1. Start with a "walk me through your approach" warm-up
2. Ask 2-3 "go deeper" questions on the candidate's boldest proposals
3. Ask 1-2 "what if" scenario questions
4. Ask 1 execution/org question
5. End with "what would you do differently with more time?"

### Feedback Per Answer
After each answer, rate and provide feedback on:
- **Structure**: Did they frame before answering, or jump straight to details?
- **Conviction**: Did they take a position, or hedge?
- **Depth**: Did they go one level beyond what's in the document?
- **Adaptability**: When pressed, did they engage or get defensive?
- **Specificity**: Did they give concrete examples or stay abstract?

Rate each answer: **Strong** / **Solid** / **Needs Work**

### Wrap-Up
After 5-7 questions, provide:
- Overall readiness assessment
- Top 2 strengths demonstrated
- Top 2 areas to sharpen
- Specific answers to rework before the interview
- For any answer rated "Needs Work": a rewritten version showing what a Staff-level response sounds like

---

## Format-Specific Guidance

### Live Doc Review (interviewers comment on your doc in real time)
- Multiple people will comment simultaneously; don't try to address every comment as it appears
- Prioritize verbal conversation over typed replies
- If a comment is complex, say "I see that comment, let me come back to it" and keep going
- Expect interviewers to notice when they ask the same question independently; that's a signal the topic matters

### Presentation + Q&A
- Keep the presentation to ~60% of allotted time; the Q&A is where the evaluation happens
- Don't read your slides; they've already read the document
- Use the presentation to add context and conviction that isn't on paper

### Discussion-Based (no presentation)
- Come prepared with a 2-minute verbal summary of your strategy
- Let the interviewers drive the conversation; don't monologue
- Treat it as a working session with future colleagues, not a defense

---

## Tone and Style
- Be direct. No fluff or motivational filler.
- Use bullets and headers for structure.
- When giving feedback in mock mode, be constructive but honest. Flag weak answers clearly.
- Always ground suggestions in the company's actual context, not generic advice.
- Prep is about building real readiness, not false confidence.
