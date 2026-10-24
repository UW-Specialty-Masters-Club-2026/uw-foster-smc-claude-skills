# SMC Claude Skills Library

> 📅 **SMC Claude Skills Workshop · Monday, October 26, 2026.** Part of Claude AI Week, hosted by the Specialty Masters Club.

A curated starting list of Claude Skills for UW Foster specialty master's students, maintained by the Specialty Masters Club (SMC) AI & Tech Committee.

Skills teach Claude how to do a specific task the same way every time: drafting in a certain format, building a web page, making a slide deck. This repo has two parts: a set of **career skills written by SMC** that you can download and upload directly, and a curated list of **open-source skills** from other authors. For those, we don't host copies; every link goes to the original source.

---

## Before you start

1. Sign in at [claude.ai](https://claude.ai) **with the same email you registered with on Luma.** That's how your free credits are applied.
2. Go to **Settings → Capabilities** and turn on **Code execution and file creation**. Skills won't run without it.
3. Your skills live under **Customize → Skills**.

---

## From the workshop (October 26, 2026)

Skills shared by Prof. Leo during the workshop. We'll add them together in the session. If you missed it, download the skill and follow [How to install a skill from GitHub](#how-to-install-a-skill-from-github).

| Skill | What it does | Link |
|---|---|---|
| _Added after the workshop_ | | |

---

## Already in Claude (nothing to download)

Claude creates these file types automatically once code execution is on. Just ask for the file.

| Skill | What it does |
|---|---|
| Word | Create and edit .docx documents |
| PowerPoint | Create slide decks |
| Excel | Build spreadsheets with formulas and charts |
| PDF | Create, read, and fill PDFs |

---

## Career skills (made by SMC)

Written by the SMC AI & Tech Committee for the job search. Each one is ready to upload: click **Download**, then on the GitHub page click the **download icon** (↓) to save the ZIP, and upload it in **Customize → Skills → + → Create skill → Upload a skill**. No unzipping needed.

| Skill | What it does | Download | Read it first |
|---|---|---|---|
| Resume Tailor | Matches your resume to a job posting: fit table, before/after bullet rewrites, ATS format check | [ZIP](downloads/resume-tailor.zip) | [SKILL.md](skills/resume-tailor/SKILL.md) |
| Cover Letter Writer | A specific 250–350 word letter built from your two strongest stories, without the generic phrases | [ZIP](downloads/cover-letter-writer.zip) | [SKILL.md](skills/cover-letter-writer/SKILL.md) |
| Interview Prep Coach | Likely questions, a STAR story bank, and mock interviews one question at a time with feedback | [ZIP](downloads/interview-prep-coach.zip) | [SKILL.md](skills/interview-prep-coach/SKILL.md) |
| LinkedIn Optimizer | Headline options, About section, and experience bullets rewritten for your target role | [ZIP](downloads/linkedin-optimizer.zip) | [SKILL.md](skills/linkedin-optimizer/SKILL.md) |
| Networking Outreach | Connection notes, coffee-chat requests, referral asks, and follow-ups people actually answer | [ZIP](downloads/networking-outreach.zip) | [SKILL.md](skills/networking-outreach/SKILL.md) |

**Try it:** after uploading Resume Tailor, start a new chat, attach your resume, paste a job description, and ask: *"Tailor my resume to this job."*

All five skills are built never to invent experience or numbers. If a bullet needs a metric you didn't provide, Claude will ask you for it instead of making one up. Always review the output before you send anything.

---

## Starter picks from Anthropic

From Anthropic's official, open-source repo: [anthropics/skills](https://github.com/anthropics/skills). Check **Customize → Skills** first, since some of these may already be listed there for you to switch on. If not, install it from GitHub.

| Skill | Good for | Link |
|---|---|---|
| Skill Creator | Turning something you do often (case prep, meeting notes, study guides) into your own skill | [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) |
| Frontend Design | Better-looking web pages and app prototypes | [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) |
| Internal Comms | Status updates, newsletters, and team announcements | [internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms) |
| Brand Guidelines | Keeping documents and visuals on-brand | [brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines) |
| Canvas Design | Posters and visual designs | [canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design) |
| Algorithmic Art | Generative art with code | [algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) |

---

## Explore more

Community-maintained lists with hundreds of skills. Quality varies, so read a skill before you install it (see [Stay safe](#stay-safe)). Many of these are built for Claude Code, a developer tool, rather than claude.ai.

- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills)
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- [VoltAgent/awesome-claude-skills](https://github.com/VoltAgent/awesome-claude-skills)

---

## How to install a skill from GitHub

Claude needs each skill uploaded as **its own ZIP file**. GitHub's "Download ZIP" button gives you the whole repo, so there's one extra step.

1. Open the repo and click **Code → Download ZIP**.
2. Unzip it and find the folder for the skill you want (it contains a `SKILL.md` file).
3. Compress **just that folder** into a ZIP.
   - Mac: right-click the folder → **Compress**
   - Windows: right-click the folder → **Send to → Compressed (zipped) folder**
4. In Claude, go to **Customize → Skills**, click **+**, then **Create skill → Upload a skill**, and choose your ZIP.
5. Make sure the skill's toggle is on, then try it in a new chat.

**If the upload fails:** the folder name must match the skill's name, and the folder must contain a `SKILL.md` file. Don't rename the folder.

---

## Stay safe

Skills can run code inside Claude. Only install skills from sources you trust, and open the `SKILL.md` file first to see what it does. Be careful with any skill that runs scripts or connects to outside websites.

---

## Suggest a skill

Found a skill your classmates should know about? Open a pull request adding it to the right table with a one-line description and a link to the original source, or message the SMC AI & Tech Committee.

Want to improve an SMC career skill? Edit its `SKILL.md` in a pull request. The committee will re-package the ZIP in `downloads/` when it's merged.

_The career skills in `skills/` are maintained by SMC. Every other skill listed here is owned by its original author and carries its own license; this list only links to them._
