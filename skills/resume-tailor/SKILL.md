---
name: resume-tailor
description: Tailors a resume to a specific job posting. Use when the user shares a resume and a job description and wants to improve fit, rewrite bullets, find keyword gaps, or check ATS readiness. Also use for general resume reviews.
---

# Resume Tailor

Help the user tailor their resume to one specific job posting. Make it stronger and more relevant without inventing anything.

## What you need

Before starting, make sure you have:

1. **The resume** (pasted text, PDF, or .docx)
2. **The job description** (pasted text or a link's contents)

If either is missing, ask for it. If the user only shares a resume, do a general review using the "Bullet quality" and "Format check" sections, and ask what kind of role they're targeting.

## Ground rules

- **Never invent experience, skills, tools, titles, dates, or numbers.** Only reword and reorder what the user actually did.
- If a bullet would be stronger with a number the resume doesn't have, ask the user for it. Use a placeholder like `[X%]` and flag it, rather than guessing.
- If the job requires something the user doesn't have, say so honestly and suggest how to address it (a project, a course, the cover letter), not how to hide it.
- Keep the user's voice. Don't turn every bullet into the same template.

## Steps

### 1. Read the job description
Pull out:
- The 5 to 8 most important requirements (skills, tools, experience)
- Repeated words and phrases (these are likely what an ATS and recruiter scan for)
- The level of the role (entry, mid, senior) and what it implies about scope

### 2. Compare against the resume
Build a short fit table:

| Requirement | Evidence on resume | Strength |
|---|---|---|
| e.g. SQL | Data analyst internship, bullet 2 | Strong |
| e.g. Stakeholder management | Implied, not stated | Weak, can be surfaced |
| e.g. Tableau | Not present | Gap |

### 3. Rewrite the bullets that matter most
Focus on the roles and projects most relevant to this job. For each rewrite, show **Before** and **After**.

Good bullets follow this shape: **action verb + what you did + result or impact.**
- Lead with a strong, specific verb (built, launched, reduced, led, analyzed), not "responsible for" or "helped with."
- Include a result: a number, a scale, or a concrete outcome.
- Use the job description's language where it honestly fits.
- Keep each bullet to one or two lines.

### 4. Suggest reordering
Recommend which bullets, projects, or sections should move up so the most relevant evidence appears first.

### 5. Format check
Flag anything that commonly hurts readability or ATS parsing:
- Tables, text boxes, columns, headers/footers holding key info, images, or icons
- Inconsistent date formats or tense (past tense for past roles, present for current)
- Length: one page is the default for students and early-career candidates
- Missing contact info or a LinkedIn URL

## Output format

1. **Fit summary** (2 to 3 sentences: how well this resume matches and the biggest opportunity)
2. **Fit table** (from step 2)
3. **Rewritten bullets** (Before / After)
4. **Reorder suggestions**
5. **Format fixes**
6. **Questions for you** (any missing numbers or details that would make bullets stronger)

If the user asks for the final resume as a file, produce a clean, single-column .docx with no tables or text boxes.
