# kittycataclysmic.com

Personal intellectual project site. [kittycataclysmic.com](https://kittycataclysmic.com)

---

## What this is

A long-term body of work applying Lean Six Sigma to texts and systems that were never designed to be audited. LSS is the constant spine across every project. The secondary lenses rotate per project depending on what the subject demands.

The methodology stays constant. The lenses rotate. The texts don't get to opt out.

---

## Pages

| Nav Label | Page | Description |
|-----------|------|-------------|
| **The Index** | Homepage | Practitioner identity, CATACLYSM acrostic, project registry |
| **The Auditor** | About | 9-paragraph profile of the methodology and the person behind it |
| **Submit Findings** | Contact | hey@kittycataclysmic.com |

---

## Projects

| # | Project | Corpus | Lens Stack | Status |
|---|---------|--------|------------|--------|
| 01 | **The Optimized Void** | 80 Penguin Little Black Classics | LSS × Foucault × Nietzsche × Jungian Archetypes × Cognitive Bias | Active |
| 02 | **The Cipher** | Shakespeare — 20 plays | LSS × Dr. Dre × Eminem × Snoop Dogg × 50 Cent | Coming |
| 03 | **The Acceptable Loss** | Japanese Literature — Dazai, Soseki, Kawabata, Mishima | LSS × mono no aware | Coming |
| 04 | **The Null Hypothesis** | Belief Systems Under Collapse — Lewis, Dostoevsky, Kafka, Bukowski, Hemingway | LSS × Camus | Coming |
| 05 | **The Prince Variations** | Political Figures — Hitler, Genghis Khan, Che Guevara, Rasputin, Stalin | LSS × Machiavelli × Orwell | Coming |
| 06 | **The Original Spec** | Sacred Texts — The Bible, The Bhagavad Gita, The Quran | LSS × Kierkegaard | Coming |
| 07 | **The Single Point of Failure** | Cult Leaders — Jim Jones, David Koresh, Charles Manson, Sun Myung Moon, Shoko Asahara | LSS × Cialdini × Fromm | Coming |
| 08 | **The Externality** | Historical Empires & Institutions — Rome, The British Empire, Modern Corporations, Religious Institutions | LSS × Marx × Chomsky | Coming |
| 09 | **The Diagnostic** | Psychological & Personality Frameworks — MBTI, Enneagram, Big Five, CBT, IFS | LSS × Adler × Kahneman | Coming |

---

## Tech stack

- Single `index.html` file — no build tools, no dependencies beyond CDN
- Hosted on Cloudflare Workers (static assets)
- Auto-deploys on push to `main`
- Charts rendered with Chart.js
- Fonts: Cormorant Garamond + DM Mono
- Favicon: embedded base64 PNG — no separate file needed

## Deployment

Push `index.html` to `main`. Cloudflare deploys automatically within 60 seconds. No configuration required.

---

*LSS is the spine. Everything else is a scalpel.*
