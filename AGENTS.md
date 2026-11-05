# AGENTS.md — Rules for working on ilaydatezcn-lab.github.io

This is İlayda Tezcan's personal website, hosted on GitHub Pages. Every file here may end up public, so any agent working in this folder follows these rules.

## 1. Never publish
- **Phone number.** It is on the CV but never goes on the site.
- Home address, or any location more specific than "New York, USA".
- Date of birth, ID or passport numbers, visa or immigration status.
- Salary, compensation, or anything about job offers or job searches that İlayda hasn't announced.
- Confidential client information: BCG or Pfizer client names, deal values that aren't on the CV, internal documents, or non-public project details. Write about engagements only the way the CV does.
- Other people's names, photos, or contact details, unless İlayda says they agreed to it.
- Passwords, API keys, tokens, or private links.
- The raw CV PDF and the original full-resolution photo, unless İlayda asks for them to be posted.

## 2. Ask İlayda first
- Before any `git commit`, `git push`, creating a repo, or anything else that makes content public.
- Before adding facts, numbers, titles, or dates that aren't in the CV. Never invent or "round up" achievements.
- Before rewording a CV claim in a way that changes what it means.
- Before adding a new public link, a new photo, or contact details beyond email, LinkedIn and GitHub.
- Before adding analytics, tracking, cookies, third-party embeds, or forms that collect visitor data.
- Before deleting or overwriting an existing file.

## 3. Style
- **Vibe:** professional and casual. Confident and warm, first person where it fits, no corporate filler.
- **Look:** dark and minimal, terminal-inspired. Black background (`#000`), warm cream text (`#ECE7DC`), and BCG-style bright green (`#29BA74`) as the only accent. Red/cyan (`#FF2A4F` / `#1EF2FF`) appear only inside the glitch effect.
- **Type:** Space Grotesk, light weight (300), uppercase for headings and the oversized name. JetBrains Mono for dates, tags and metadata. Proper Turkish uppercase (İ, Ğ, Ç): mark Turkish words with `lang="tr"`.
- **Signature details:** glitch on the name, blinking block cursor ▮, experience shown as log entries that expand with a fast typing reveal, subtle grain. All motion must switch off under `prefers-reduced-motion`.
- **Inspiration, not a copy:** the mood is inspired by altayacar.com, but don't copy its layout, code, canvas scene, page-flip or music player.
- **No BCG branding:** use the green only. Never use the BCG logo, wordmark, or anything that makes the site look official or affiliated.
- **Navigation:** streamlined. One fixed top bar with anchor links to each section, plus a numbered section index in the intro. A single page that's easy to scan.
- **Content order:** follow the CV's section order: Work Experience → Education → Leadership & Voluntary Work → Extracurricular Experience.
- **Layout:** log lists rather than boxed cards, lots of empty black space, readable at phone width (no horizontal scroll), accessible contrast, semantic HTML.
- **Tech:** plain HTML and CSS in one file where possible, no build step, Google Fonts only for external assets.
- **Writing:** American English, keep proper Turkish spelling (İlayda, Boğaziçi), dates written as `Mon YYYY – Mon YYYY`.
