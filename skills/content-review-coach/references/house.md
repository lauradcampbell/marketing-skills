# House context: who you're reviewing for

Everything in this skill that depends on *which company* is publishing lives in this file. The
method in `SKILL.md` and `lenses.md` is the same for any B2B content team; this file tells the coach
what "earns its place on our site" means, who the buyer is, which product facts are settled, and
what the house bar for a use case looks like.

**To use the skill for your own team, replace everything below with your own company's details.**
Keep the headings. The coach reads them by name.

As shipped, this file describes **Plinth**, a fictional company. Every example in
`references/examples.md` is set at Plinth, so the skill works out of the box as a demo.

---

## The publisher

**Plinth** makes practice-management software for architecture and interior design studios of 10
to 80 people. Its blog, use case pages and customer stories live on plinth.example.

## The products

| Product | What it does | Works with |
|---|---|---|
| **Plinth Hours** | Time tracking against projects and their fee stages, with weekly timesheet approval | Plinth Billing |
| **Plinth Billing** | Invoices built from tracked hours and fee stages, synced to the studio's accounting software | Plinth Hours |
| **Plinth Rooms** | Meeting room and model-shop booking | Neither. It's a standalone product and doesn't share data with Hours or Billing |

**Which products genuinely work together.** Hours and Billing are designed to be used together:
approved hours flow into invoices. A piece that features both but presents them separately is
siloing them. Rooms doesn't connect to either, so a piece that presents Rooms on its own is
describing reality, not siloing.

## The buyer

- **Who buys:** studio principals, practice managers and studio managers, the person who chases
  timesheets and sends invoices at month end.
- **Who doesn't buy:** students, freelancers working alone, and individual architects and designers
  who log the hours but don't choose the tool.
- **What buyers search for:** month-end billing pain, fee stages running over, getting timesheets
  in on time, knowing which projects make money.

A piece written for students or solo freelancers can be well written and still be aimed at the
wrong reader for this site.

## Where Plinth has authority

Studio admin: time, fees, billing, project profitability, room booking. Plinth has **no** credible
authority on design itself (drawing, modelling, rendering, building information models) or on AI in
design. A piece whose title claims those topics is claiming ground Plinth can't stand on.

## Settled product facts (safe to flag with confidence)

Renamed terms. Flag these only when the old name actually appears in the piece:

- "Jobs" are now called **Projects** (renamed 2025)
- "Timers" are now called **Hours entries**
- "Client portal" is now **Client view**

How the product is structured:

- A **project** contains **fee stages**. A fee stage never contains a project.
- Hours are logged against a fee stage, not directly against a project.
- Splitting one project's invoices across two clients needs the **Studio plan**. It isn't available
  on the standard plan.
- Tax (VAT, sales tax) is calculated by the studio's accounting software after the invoice syncs.
  Plinth Billing doesn't calculate tax itself. A piece that says it does is mixing up what Plinth
  does with what the accounting software does.

Anything not listed here is **not** settled. For any other product claim, prompt the learner to
check it rather than asserting it's wrong.

## Where drafts and published pieces live

- Drafts: pasted into the conversation, or shared as a document link.
- Published pieces: plinth.example/blog, plinth.example/use-cases, plinth.example/customers.

If your team keeps drafts in a wiki or document tool that has an MCP connector, name the connector
here and the coach will fetch drafts through it.

## The house bar for a use case page

Named role, singular ("the studio manager") + a pronoun for that role + a specific present-tense
scene + the reader addressed as "you". Not a named individual with a backstory. See the persona
lens in `references/lenses.md`.
