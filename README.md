# PM Interview Prep

A reusable system for preparing for product management interviews, built for AI PMs working in B2B SaaS.

## What This Is

A Claude Code project that uses skill files to generate tailored interview prep materials, run mock Q&A sessions, and give honest readiness assessments — grounded in your actual background and the specific company you're interviewing with.

## How It Works

1. **Add your candidate profile** — copy `candidate-profile/profile-template.md` to `candidate-profile/profile.md` and fill it in
2. **Add company research** — create a folder under `Companies/[CompanyName]/` and drop in job descriptions, research notes, and any recruiter guidance (see `Companies/_template/` for what to include)
3. **Invoke a skill** — tell Claude which interview you're prepping for and it handles the rest

## Available Skills

| Skill | Trigger | What It Does |
|---|---|---|
| Design Partnership | `Prep me for [Company] design partnership interview` | Prep doc, mock Q&A, readiness assessment for PM/design collaboration interviews |

More skills coming. Contributions welcome.

## Setup

This project is designed to run with [Claude Code](https://claude.ai/code).

1. Clone this repo
2. Open the folder in Claude Code
3. Copy `candidate-profile/profile-template.md` → `candidate-profile/profile.md` and fill it in
4. Create a company folder and add your research
5. Invoke a skill

## Privacy

Your personal files are gitignored by default. The following are **never committed**:
- `candidate-profile/profile.md` (your filled-in profile)
- `candidate-profile/resume/` (your resume files)
- `Companies/[anything except _template]/` (your company research and prep docs)

Only the templates and skill files are tracked.

## Contributing

Skills are markdown files in `skills/[skill-name]/`. Each skill defines a trigger phrase, inputs, and a workflow. If you build a skill for a new interview type, pull requests are welcome.
