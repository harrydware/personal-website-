# Harry Ware — personal site

Personal site for Harry Ware. Audience: Silicon Valley founders, investors, accelerators. Work is the main event; personal content is secondary and sits lower on the page.

## Files
- `index.html` — whole site: HTML, CSS, and JS in one file. No build step, no framework.
- `assets/` — headshot.jpg, mtb.jpg, surf.jpg, nols.jpg (already cropped and compressed).
- Deploy: GitHub repo → GitHub Pages or Vercel, static.

## Page order (keep it)
1. **Hero** — large 4:5 rectangular headshot → "Pepperdine · Philosophy, Data Science minor · Class of '29" (white, ~13px, uppercase) → name "Harry Ware" in JetBrains Mono. Nothing else in the hero.
2. **01 About** — one sentence only: the goal statement ("My goal is to build the agent systems that run the next generation of startups — mapping out business processes and automating them with frontier models and well-designed bots."). No portrait, no facts table, no second paragraph.
3. **02 Work** — project rows, newest/strongest first: Yeahme, Highway Ventures, HDW AI Consulting, Waves, PersonaBuilder, Ignite, Vendors FORE, Grand Savings, Trail Trimming Robot & Scotland, AI Video, NWACC, then a small "Also" line (OpenAI Academy). Each row: year · title + tag · short description + skill pills · metric on the right.
4. **03 Outside Work** — NOLS origin story paragraph, one line on outdoors, then a 3-photo strip (MTB, surf, NOLS).
5. **Contact footer** — email, LinkedIn, PersonaBuilder, GitHub (`#ghlink`, auto-hidden while href is `#`).

## Design system
- Pure black background (#000), off-white text (#f4f2ec), muted gray (#8a877f). **No accent color.**
- Fonts: Fraunces (serif, section heads and leads), JetBrains Mono (body, name, labels).
- Background: full-screen canvas flow-field of white particle strokes, mouse/touch swirl, fading trails. "Loud" is intentional — the background is the art. Grain and vignette overlays keep text legible.
- Reveals: `.reveal` elements fade up via IntersectionObserver. Hero uses CSS-only `.fade` animations so text never disappears if JS fails (an earlier JS-dependent hero broke and collapsed the text).
- Photos are full color. Do not grayscale or blend them.

## Copy rules (Harry's feedback, consistently)
- Plain, direct, factual. If it sounds like AI wrote it or like bragging, cut it.
- Short beats long. Business first.
- Rejected lines — don't bring them back: "Same idea, more leverage every time", "The work below is the proof…", "Networking is my gift…", the three-line clever hero headline.
- Use his wording where he gave it; light tightening only.

## Facts on the page (source of truth: Harry's resume, Nov 2026)
- Education: Pepperdine, BA Philosophy (Philosophy of AI independent study), minor Data Science, Class of 2029. Full-year study abroad, Pepperdine Switzerland 2026–27.
- Yeahme (yeahme.app), Co-Founder, 2026–present, in beta: AI introspection platform. 4-stage Claude reasoning pipeline (voice/text intake → sequenced goal plan); real-time voice interview (Deepgram STT/TTS) steered by a gap engine; weekly Pattern Engine with code-verified evidence to block fabrication; "Vent" reflection space. Stack: Next.js, React, Supabase (Postgres, RLS), Anthropic API, Deepgram, Vercel Cron.
- Highway Ventures, Project Intern (paid, full-time), May–Aug 2026: led AI-native initiative; shared agent infra on PostgreSQL + pgvector knowledge base; 6 Slack agents (morning brief, daily market reports, on-demand research, market intelligence, content, SDR). SDR agent: shipped in 2 weeks, 200+ qualified leads, Apollo → HubSpot. GTM for portfolio co Clinary ($93.6M PACT rural health funding research, Baptist Health targeting, sales collateral); CRM/account-strategy tool with AI analysis.
- HDW AI Consulting, Founder & CEO, Mar 2025–present: prompting/AI-tool workshops, custom software and AI video for clients. **$9,300 revenue** (do not use $10K or the margin claim).
- Waves Innovation Accelerator: inaugural cohort fellow, selected from 100+ Pepperdine applicants.
- PersonaBuilder: personabuilder.live — 15-min survey → custom AI instructions for ChatGPT, Claude, Gemini, Perplexity.
- Ignite Professional Studies, Leadership Team (Technology Strand), Fall 2023–Spring 2025: built early AI agents on GPT-3.5/GPT-4 (recommendation-letter and resume-builder tools).
- Vendors FORE Education: 1 of 3 selected by interview; cold-reached 50+ companies; $6K raised, 2nd place.
- Grand Savings Bank App: team-built spending-visualization app, $1,000 scholarship, Dec 2024.
- Trail Trimming Robot / Scotland, Summer 2024: "Mullet TTR" designed with GPT-4o and DALL·E 2 at 17; Edinburgh Napier research on Scottish Borders trail systems (Innerleithen/Peebles); helped build handlebar-vibration monitoring systems.
- AI Video: Veo 2 early access Feb 2025, then Veo 3; content for multiple companies.
- NWACC Trail Technician Program, Outreach & Engagement Specialist (paid), Jan 2024–Jul 2025: led social for Trail & Bike Tech programs; **+300% following and engagement**.
- OpenAI Academy, AI Nonprofit Jam, July 2025.
- Activities: Pepperdine Surf Team, Alpha Tau Omega, Varsity Basketball Captain (Bentonville HS, 2023–25).
- Deliberately left off: Coursera certs (ChatGPT Prompt Engineer, Google Prompt Essentials) — read junior next to shipped work. Phone number — keep off a public page.
- NOLS: 30-day Alaska expedition, June 2022, age 16. ChatGPT launched Nov 2022 — the origin story connects the two.

## Open to-dos
- [x] Major, Highway dates, Yeahme, Waves, Ignite, OpenAI Academy — done from resume.
- [ ] Yeahme screenshots or a short demo clip in its row.
- [ ] Add GitHub URL to `#ghlink`.
- [ ] Embed AI video work and robot presentation (Harry to supply files/links).
- [ ] Connect custom domain (GitHub Pages: 4 A records → 185.199.108–111.153, `www` CNAME → username.github.io; or Vercel Domains tab).
- [ ] Check mobile layout and performance of the canvas on phones.
