CS and Cybersecurity B.S. @ Hofstra University '28 · Long Island, New York

[Persona Site](https://savarsuri-site.vercel.app) · [LinkedIn](https://linkedin.com/in/savarsuri1) · [Gmail] savarsuri06@gmail.com

---

## 🔐 About Me

- 🏖️ Long Island, New York
- 🎓 Studying Computer Science and Cybersecurity @ Hofstra University '28
- 🏛️ Former IT & Cybersecurity Intern @ Town of Oyster Bay
- 🤖 AI model evaluation contractor @ Handshake AI
- 🧑‍🏫 CS & cybersecurity tutor @ Preply
- ⚙️ Building LLM automation for small businesses

I'm most interested in where security meets AI systems: prompt injection, LLM abuse, and what happens when you put a language model somewhere untrusted input can reach it.

---

## 🚀 Projects

### GhostED — live at [ghosted-eta.vercel.app](https://ghosted-eta.vercel.app)

Students anonymously share what actually happened when they applied to internships. Aggregate ghost rates, offer rates, and per-company breakdowns. Built it because I was dozens of applications deep with no idea what was normal.

Audited my own source and found a stored XSS: every user-supplied field was written straight into `innerHTML`, so a crafted company name would execute in every visitor's browser. Remediated it in three layers: HTML-escaped all rendered output, added database-level length constraints, and confirmed row-level security scoped the public key to `SELECT` and `INSERT` only.

Full write-up: [docs/stored-xss.md](https://github.com/SavarSuri/ghosted/blob/main/docs/stored-xss.md)

`JavaScript` `Supabase` `PostgreSQL` `Vercel`

### AI Lead-Response Automation

A 4-stage pipeline (webhook ingestion → field normalization → Anthropic API inference → Gmail delivery) that takes an inbound web-form lead and returns a personalized reply in under a minute, unattended.

`n8n` `Anthropic API` `Webhooks` `Gmail API`

### Personal Site — live at [savarsuri-site.vercel.app](https://savarsuri-site.vercel.app)

One self-contained HTML file, no framework and no build step. Six views, hash routing, keyboard navigation, designed light and dark modes.

`HTML` `CSS` `JavaScript` `Vercel`

---

## 📖 Currently

- CompTIA Security+ (exam December 2026)
- PortSwigger Web Security Academy — OWASP Top 10
- TryHackMe Cyber Defense path
- ARM assembly and systems programming

---

## 🛠️ Tech Stack

**Languages** Python · Java · C/C++ · JavaScript · ARM Assembly · SQL · HTML/CSS

**Security** Stored XSS remediation · output encoding · row-level security · access control review · audit documentation · adversarial model evaluation · defense in depth

**Build** Git · Linux · Supabase/PostgreSQL · Vercel · n8n · REST APIs · Anthropic API

---

## 📜 Certifications

- ✅ Fortinet NSE 2 — Certified in Cybersecurity (2026)
- ✅ Cisco — Introduction to Cybersecurity (2026)
- ✅ Mastercard — Cybersecurity Job Simulation, Forage (2025)
- ⏳ CompTIA Security+ (exam December 2026)

---

## 📫 Let's Connect

- 🌐 [savarsuri-site.vercel.app](https://savarsuri-site.vercel.app)
- ✉️ savarsuri06@gmail.com
- 💼 [linkedin.com/in/savarsuri1](https://linkedin.com/in/savarsuri1)
