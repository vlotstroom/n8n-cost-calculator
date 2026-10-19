# n8n AI workflow cost calculator

Free single-file calculator for anyone running scheduled n8n workflows
with AI nodes: what each workflow costs per day, week, month and year,
with per-workflow attribution and a biggest-spender callout.

- Open `index.html` in any browser, or use the hosted copy:
  https://vlotstroom.github.io/n8n-cost-calculator/
- English + Nederlands, no signup, no external requests, nothing sent.

Honest arithmetic, no benchmarks claimed:

- Cost per run = AI calls x (prompt tokens x price in + completion
  tokens x price out) / 1,000,000 + other metered cost per run
- Month = runs per day x 30 (a 30-day month, not a calendar month)
- Model prices are rough public list prices and fully editable.
  Repurpose a row for any other model. Totals use only the numbers
  you enter on the page.

Built by Vlotstroom. We also sell a ready-made n8n automation pack for
salons and clinics (waitlist autofill, appointment reminders, no-show
rescue and more): https://vlotstream.gumroad.com/l/rhmxw

Related free tools:
- no-show cost calculator: https://vlotstroom.github.io/noshow-calculator/
- waitlist fill-rate calculator: https://vlotstroom.github.io/waitlist-calculator/
