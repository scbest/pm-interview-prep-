# PM Interview Prep — Project Instructions

## Purpose
A reusable system for interview preparation. Each skill targets a specific interview type and generates tailored prep materials using company-specific context and the candidate's professional background.

## Project Structure
- `candidate-profile/` — your professional background and resume
- `candidate-profile/profile.md` — fill this in before using any skill (copy from `profile-template.md`)
- `candidate-profile/resume/` — drop resume files here (PDF or DOCX)
- `skills/` — one subfolder per interview type, each containing a skill file
- `Companies/` — one subfolder per company with all research, job descriptions, and notes

## Conventions

### Candidate Profile
Always read `candidate-profile/profile.md` before generating any prep materials. Use the candidate's background, strengths, and narrative to tailor all outputs.

### Company Context
When the user names a company they are prepping for:
1. Look in `Companies/{CompanyName}/` for all relevant files (notes, PDFs, job descriptions, recruiter guidance)
2. Read all files in that folder before generating any prep materials
3. Ground all outputs in the company's actual product, market, and role details
4. If recruiter guidance about the interview format is available, prioritize it over skill defaults

### Adding a New Company
Create a subfolder under `Companies/` with the company name. See `Companies/_template/README.md` for what to include.

## Available Skills

### Design Partnership Prep
- Folder: `skills/design-partnership/`
- File: `skills/design-partnership/design-partnership-prep.md`
- Use when: Prepping for a design partnership interview (cross-functional PM/design collaboration)
- Best for: AI PMs — includes themes on value of design when PMs can prototype, PM value in the AI age, designing for humans and agents
- Invoke by saying: `Prep me for [Company] design partnership interview`
