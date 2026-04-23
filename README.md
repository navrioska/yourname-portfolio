# How I Built a Personal Brand Site with AI — And How You Can Fork It

### A reusable methodology for technical professionals, builders, and teams who are done waiting on agencies

---

## Why This Exists

Most portfolio sites fail before a single line of code is written.

Not because the person lacks skills. Because they never defined what the site needs to do, who it is for, and what decision it needs to drive in under ten seconds. They pick a template, fill in the fields, and ship something that looks like everyone else's — which means it does what everyone else's does: nothing.

I built [navrioska.com](https://navrioska.com) in 5 active days using Claude Code as my primary development environment. No agency. No template. No budget. A clear brief, a governance file, and the same disciplined process I use to deliver enterprise programs with 1,400-plus users, zero incidents, and zero rollbacks.

This repository is that process, made forkable.

Follow it and you will ship a personal brand site that is distinctly yours, built for a specific audience, and maintainable without a developer on call. If you want it done at director and executive level — tighter brief, higher stakes, a design system that holds up across platforms — that is a different conversation. The framework is here for anyone ready to do the work.

---

## What This Actually Is

This is not a website starter kit. It is a **program framework** packaged as a GitHub repository.

The repository gives you:

- A `CLAUDE.md` governance file that functions as a project charter for your AI-assisted build
- A folder structure for a single-page HTML/CSS/JS portfolio site
- A brand token reference template
- A deployment guide for GitHub Pages with custom domain DNS
- This document: the lifecycle and decision map

What it does not give you is a shortcut past the thinking. The `CLAUDE.md` only works if you have done the brand work first. The design system only holds if the decisions behind it are real. The site only lands if you know who you are building it for.

**The repo is the tool. The thinking is the product.**

---

## The Project Dimensions

Before you open a code editor, four dimensions need to be clear. If any one is vague, the build will drift — and you will feel it in every session.

| Dimension | The Question | Example: Princess Leia Organa |
|---|---|---|
| **Audience** | Who lands on this page and what decision are they making? | Rebel Alliance commanders, galactic press, and coalition partners evaluating her for a strategic leadership role |
| **Feeling** | What do you want them to feel in the first 10 seconds? | Credible under pressure. Uncompromising. The person who gets things done when everything is on the line. |
| **Proof** | What three outcomes prove the feeling is earned? | Negotiated the Rebel fleet alliance at Yavin. Extracted intelligence from Tarkin under direct interrogation. Built the Resistance from a single outpost on D'Qar. |
| **Action** | What is the one thing you want them to do after visiting? | Start a conversation. Not download a resume. Not follow on Holonet. Start a conversation. |

If you cannot answer all four in one paragraph per row, you are not ready to open `CLAUDE.md` yet.

---

## The Lifecycle

This project runs in four phases. Each phase has a clear entry condition, a defined set of decisions, and a hard output required before the next phase begins.

---

### Phase 1: Brief
**Entry condition:** You know your audience, your feeling, your proof, and your action.
**Time:** 2 to 4 hours. Not spread across days.

In this phase you define:

- Your tagline: one sentence, present tense, active voice — what you do and for whom
- Your three proof points: real numbers, real outcomes, no fabricated metrics
- Your visual direction: not colors yet — tone (editorial, technical, warm authority, bold minimalist)
- Your audience signal: what tells a visitor in the first scroll that this site was built for them

**Output:** A completed brand brief. One page. If it runs longer, you have not made the decisions yet — you have listed the options.

---

### Phase 2: Governance
**Entry condition:** Completed brand brief.
**Time:** 1 to 2 hours.

In this phase you create your `CLAUDE.md` file — the governance layer of the project. It functions as:

- A project charter: scope, audience, success criteria
- A technical spec: file structure, naming conventions, component rules
- A design system brief: color tokens, typography hierarchy, spacing rules
- A voice guide: how copy sounds and what it never does

Every Claude Code session reads this file first. That is how you eliminate context drift across sessions and protect scope from day one. The same discipline that keeps enterprise migrations on track applies directly here.

The `CLAUDE.md` template in this repository is fully annotated. Every section explains what it does, why it exists, and includes a filled example from Princess Leia Organa's brand so you see a complete version before writing your own.

**Output:** A committed `CLAUDE.md` in your repository root.

---

### Phase 3: Build
**Entry condition:** `CLAUDE.md` committed to the repo.
**Time:** 3 to 7 active working days, depending on scope and your comfort with HTML/CSS.

Each Claude Code session starts by reading the `CLAUDE.md`. The build order matters:

1. Scaffold the file structure and base HTML
2. Implement the design system — colors, typography, spacing — as CSS custom properties
3. Build each section in sequence: hero, proof, about, contact
4. Create the brand lockup reference file: your living design system document
5. Test across devices before touching DNS

Any decision made in this phase that is not already in the `CLAUDE.md` goes in before the next session. Skip this and the next session will contradict the decision. You will do the work twice.

**Output:** A working site on `localhost` or a GitHub Pages preview URL.

---

### Phase 4: Deploy and Document
**Entry condition:** Site is visually complete and tested on mobile.
**Time:** 2 to 4 hours.

Steps in order:

1. Configure GitHub Pages in repository settings
2. Purchase your domain and configure DNS records: A record pointing to GitHub Pages IPs, CNAME for `www`
3. Wait for DNS propagation — up to 48 hours. Do not touch the config during this window.
4. Enable HTTPS in GitHub Pages settings after propagation confirms
5. Update your `CLAUDE.md` with the live URL and any deployment decisions
6. Archive Phase 1 through 3 notes into a `DECISIONS.md` for future maintainers — including future you

**Output:** Live site at your custom domain. Updated governance files committed. Repository clean enough for someone else to read without asking you a single question.

---

## Skills and Tools Required

This project sits at the intersection of three disciplines. You do not need to be expert-level in all three, but you need to be functional in each.

**Brand strategy:** Make decisions about who you are and for whom — and hold them under pressure. The build will surface moments where a different option looks appealing. Brand discipline is what keeps you from chasing it.

**Systems thinking:** The `CLAUDE.md` is a system. The CSS custom properties are a system. The file structure is a system. Treat this as a series of one-off decisions instead of a coherent architecture and the site will feel like one.

**Technical execution:** HTML, CSS, and enough comfort with GitHub to push commits, configure Pages, and read an error message without panic. JavaScript expertise is not required for a portfolio site. Terminal confidence is.

**AI fluency:** Claude Code is not a magic shortcut. It is a highly capable collaborator that does exactly what you tell it to do. A vague brief produces vague output. A tight `CLAUDE.md` produces tight sessions. The quality of your AI output is a direct measure of the clarity of your thinking.

---

## What Makes This Different From a Template

Templates give you someone else's decisions. This gives you a process for making your own.

The difference shows up the first time someone asks about your site — a recruiter, a client, a collaborator. If you used a template, you can describe the site. If you ran this process, you can describe every decision: why that font, why that tagline, why that proof point in that order, why that action and not another.

That is the difference between a portfolio and a positioning document. One shows that you exist. The other shows how you think.

Fork the repo. Run the process. Ship the site.

And if you want to see what this looks like done at director and executive level — tighter brief, more rigorous design system, cleaner deployment, positioning built to open specific doors — the work is at [navrioska.com](https://navrioska.com).

---

## Repository Structure

```
your-portfolio/
├── CLAUDE.md                  # Governance file — read this first, always
├── DECISIONS.md               # Decisions log — updated throughout the build
├── README.md                  # This document
├── index.html                 # Single-page site entry point
├── assets/
│   ├── css/
│   │   └── styles.css         # Design system as CSS custom properties
│   ├── js/
│   │   └── main.js            # Minimal interaction layer
│   └── images/
│       └── brand/             # Logo, lockup, favicons
└── brand-reference.html       # Living design system document
```

---

## Deployment Stack

| Tool | Purpose | Cost |
|---|---|---|
| GitHub Pages | Static site hosting with HTTPS | Free |
| Domain registrar (Namecheap, Google Domains, Squarespace) | Domain purchase and DNS management | $10 to $20 per year |
| Claude Code | AI-assisted development environment | Claude Pro subscription |
| Browser developer tools | Testing and debugging | Free |

No build pipeline. No framework. No dependency management. A portfolio site does not need infrastructure complexity. It needs clarity of purpose and clean execution.

---

*Built by Navrioska Mateo Mejía. Senior TPM. AI builder. Methodology forked from 14 years of delivering programs that actually ship.*

*[navrioska.com](https://navrioska.com) · [LinkedIn](https://linkedin.com/in/navrioska)*
