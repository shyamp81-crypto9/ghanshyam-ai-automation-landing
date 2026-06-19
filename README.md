# Ghanshyam Prasad — AI Automation Landing Page

A static, conversion-focused landing page built from `Personal Brand Blueprint – Ghanshyam Prasad.docx`.

## Strategy summary

- Page goal: generate qualified free AI Automation Strategy Call bookings.
- Target visitor: Network Engineers, IT professionals, and students who want practical AI automation skills.
- Core promise: save time, increase productivity, and future-proof a technical career using AI agents and automation.
- Primary offer: AI Automation Consulting and AI Agent Development.
- Primary CTA: Book a free AI Automation Strategy Call.
- Design direction: premium, technical, modern, systems-oriented, and trust-building.
- Main proof used: Network Engineering experience, early AI adoption, real-world automation focus, and ability to simplify complex technical ideas.

## Files

- `index.html` — semantic landing page markup.
- `styles.css` — responsive premium visual design.
- `README.md` — setup, deployment, and replacement notes.

## Local preview

```bash
cd "/home/shyam/landing page/ghanshyam-ai-automation-landing"
python3 -m http.server 4173
```

Open: http://localhost:4173

## CTA placeholder to replace

The final CTA currently points to:

```text
mailto:hello@example.com?subject=Free%20AI%20Automation%20Strategy%20Call%20with%20Ghanshyam
```

Replace `hello@example.com` with one of:

- a Calendly booking link,
- a Vercel form endpoint,
- a real email address,
- a LinkedIn DM URL.

## Missing proof/assets to add

The page avoids fake proof. Add these when available:

1. Named project screenshots or anonymized before/after workflows.
2. Workshop delivery details, if applicable.
3. Client or colleague testimonials with permission.
4. Real case studies showing time saved or process improvements.
5. The final PDF/download URL for “10 AI Agents Every Network Engineer Should Use.”

## GitHub manual publishing

```bash
git init
git add .
git commit -m "Add AI automation landing page"
git branch -M main
gh repo create ghanshyam-ai-automation-landing --public --source=. --remote=origin --push
```

## Vercel manual deployment

If the Vercel CLI is authenticated:

```bash
vercel --prod --yes
```

If deploying from the Vercel dashboard:

1. Create/push the GitHub repo.
2. Go to https://vercel.com/new.
3. Import the GitHub repository.
4. Framework preset: Other.
5. Build command: leave blank.
6. Output directory: `.`
7. Deploy.

## Version 2 improvements

1. Replace the mailto placeholder with a booking link or embedded form.
2. Add real case studies and screenshots from AI automation implementations.
3. Create and connect the “10 AI Agents Every Network Engineer Should Use” lead magnet.
4. Add a short founder video or LinkedIn intro clip for trust.
5. Add analytics and conversion tracking after deployment.
