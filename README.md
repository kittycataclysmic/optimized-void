# kittycataclysmic.com

Personal intellectual project site. [kittycataclysmic.com](https://kittycataclysmic.com)

---

## What this is

A long-term body of work applying Lean Six Sigma to texts, systems, and images that were never designed to be audited. LSS is the constant spine across every project. The secondary lenses rotate per project depending on what the subject demands.

The methodology stays constant. The lenses rotate. The subjects don't get to opt out.

---

## Pages

| Nav Label | Page | Description |
|-----------|------|-------------|
| **Home** | Homepage | Practitioner identity — CATACLYSM acrostic + 9 sentences |
| **The Index** | Projects | 9 long-form audit projects across text and institutional systems |
| **The Still Case** | Paintings | 9 visual audits — one painting at a time, fixed lens stack |
| **The Auditor** | About | 9-paragraph profile of the methodology and the person behind it |
| **Submit Findings** | Contact | hey@kittycataclysmic.com |

---

## The Index — 9 Projects

| # | Project | Corpus | Lens Stack | Status |
|---|---------|--------|------------|--------|
| 01 | **The Optimized Void** | 80 Penguin Little Black Classics | LSS × Foucault × Nietzsche × Jungian Archetypes × Cognitive Bias | Active |
| 02 | **The Cipher** | Shakespeare — 20 plays | LSS × Dr. Dre × Eminem × Snoop Dogg × 50 Cent | Coming |
| 03 | **The Acceptable Loss** | Japanese Literature — Dazai, Soseki, Kawabata, Mishima | LSS × mono no aware | Coming |
| 04 | **The Null Hypothesis** | Belief Systems Under Collapse — Lewis, Dostoevsky, Kafka, Bukowski, Hemingway | LSS × Camus | Coming |
| 05 | **The Prince Variations** | Political Figures — Hitler, Genghis Khan, Che Guevara, Rasputin, Stalin | LSS × Machiavelli × Orwell | Coming |
| 06 | **The Original Spec** | Sacred Texts — The Bible, The Bhagavad Gita, The Quran | LSS × Kierkegaard | Coming |
| 07 | **The Single Point of Failure** | Cult Leaders — Jim Jones, David Koresh, Charles Manson, Sun Myung Moon, Shoko Asahara | LSS × Cialdini × Fromm | Coming |
| 08 | **The Externality** | Historical Empires & Institutions — Rome, The British Empire, Modern Corporations, Religious Institutions | LSS × Marx × Chomsky × Kaczynski | Coming |
| 09 | **The Diagnostic** | Psychological & Personality Frameworks — MBTI, Enneagram, Big Five, CBT, IFS | LSS × Adler × Kahneman | Coming |

---

## The Still Case — 9 Paintings

Fixed lens stack applied to every painting: **LSS × Panofsky × Berger × Bataille**

| # | Painting | Artist | Year | Status |
|---|---------|--------|------|--------|
| 01 | **Faun by Moonlight** | Léon Spilliaert | 1900 | Active |
| 02 | **Saturn Devouring His Son** | Francisco Goya | 1819 | Coming |
| 03 | **Isle of the Dead** | Arnold Böcklin | 1880 | Coming |
| 04 | **Judith Beheading Holofernes** | Caravaggio | 1599 | Coming |
| 05 | **The Dead Mother** | Edvard Munch | 1900 | Coming |
| 06 | **Black Square** | Kazimir Malevich | 1915 | Coming |
| 07 | **The Sin** | Franz von Stuck | 1893 | Coming |
| 08 | **Salome with the Head of John the Baptist** | Gustave Moreau | 1876 | Coming |
| 09 | **The Nightmare** | Henry Fuseli | 1781 | Coming |

All images sourced from Wikimedia Commons (public domain, pre-1927).

---

## Lens Registry — No Repeats Across All Projects

| Lens | Used In |
|------|---------|
| LSS | All projects (spine) |
| Foucault | 01 The Optimized Void |
| Nietzsche | 01 The Optimized Void |
| Jungian Archetypes | 01 The Optimized Void |
| Cognitive Bias | 01 The Optimized Void |
| Dr. Dre × Eminem × Snoop Dogg × 50 Cent | 02 The Cipher |
| mono no aware | 03 The Acceptable Loss |
| Camus | 04 The Null Hypothesis |
| Machiavelli × Orwell | 05 The Prince Variations |
| Kierkegaard | 06 The Original Spec |
| Cialdini × Fromm | 07 The Single Point of Failure |
| Marx × Chomsky × Kaczynski | 08 The Externality |
| Adler × Kahneman | 09 The Diagnostic |
| Panofsky × Berger × Bataille | The Still Case (all paintings) |

---

## Tech Stack

- Single `index.html` file — no build tools, no dependencies beyond CDN
- Hosted on Cloudflare Workers (static assets)
- Auto-deploys on push to `main`
- Charts rendered with Chart.js
- Fonts: Cormorant Garamond + DM Mono
- Favicon: embedded base64 PNG

## Deployment

Push `index.html` to `main`. Cloudflare deploys automatically within 60 seconds. No configuration required.

---

*LSS is the spine. Everything else is a scalpel.*
