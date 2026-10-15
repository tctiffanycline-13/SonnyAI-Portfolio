<sub><a href="../README.md">Sonny</a> / Chapter 06 of 08</sub>

# Keeping AI in Check 🛡️

### I wanted Sonny to save time — not create a new problem for someone else to clean up.

The more I used Sonny, the clearer one thing became: **a confident answer isn't necessarily a correct one.** That's especially risky in implementations, where a made-up date, product claim, or scope commitment can turn into a real customer expectation.

So I built rules around the work Sonny was allowed to *prepare* and the decisions that still belonged to a person.

---

## 01 / Draft first. Human approves.

![Sonny's human approval flow](https://github.com/tctiffanycline-13/SonnyAI-Portfolio/blob/main/assets/13-human-approval-flow.png)

For customer follow-ups, Sonny could gather context and prepare an email or ticket. **He didn't send customer emails on his own.** I reviewed the wording, facts, recipients, and next steps before anything went out.

That same principle applied to the consultant copilot: it could recommend an approach, but not approve new scope or make a customer commitment.

---

## 02 / What happened when something was missing?

![Four examples of Sonny's guardrails in practice](https://github.com/tctiffanycline-13/SonnyAI-Portfolio/blob/main/assets/14-guardrails-in-practice.png)

These are **fictional reconstructions** of the kinds of situations I designed for, not screenshots or transcripts from production.

The rules were simple, but important:

| If Sonny encountered… | I wanted it to… | Not… |
|---|---|---|
| **Missing information** | Mark it `[pending]` and ask for confirmation | Guess an owner, date, or decision |
| **An existing support issue** | Check open tickets and flag a possible match | Create a duplicate by default |
| **A request outside the SOW** | Flag the scope concern for a consultant | Promise extra work |
| **An unsupported product question** | Distinguish documented behavior from a suggestion | Invent a feature or entitlement |
| **A possibly resolved task** | Check sent email and recent updates | Call it overdue without context |

---

## 03 / Protect the source of truth

I separated the consultant copilot's knowledge into **how we implement** and **how the products work**. The first changes relatively slowly; the second can change with releases, packaging, and entitlements.

That mattered because a good implementation practice isn't the same thing as a verified product capability. I wanted Sonny to be helpful without blurring that line.

<details>
<summary><b>What I'd check before trusting a response</b></summary>

- **Source:** Is this supported by a meeting note, contract, ticket, or maintained knowledge file?
- **Freshness:** Could the product or customer context have changed?
- **Completeness:** Are important facts missing or conflicting?
- **Authority:** Is Sonny drafting a recommendation, or accidentally making a decision only a person can make?
- **Audience:** Would I be comfortable putting this in front of the customer after review?

</details>

---

## 04 / What I learned — and what I hadn't proven yet

In my own workflows, the guardrails helped me produce drafts I could review quickly. The recap and ticket preparation process went from roughly **30–60 minutes to under five minutes** in my personal use. That's an observation, **not** a measured quality or safety study.

I also built and began piloting the consultant copilot, but I **didn't complete a broad evaluation** of its accuracy, adoption, or failure rate. I wouldn't claim the rules eliminated hallucinations or that the tool was ready to act independently.

If I were expanding the pilot, I'd test it against real-world scenarios with known answers: ambiguous scope, outdated product guidance, missing owners, duplicate issues, and contradictory notes. I'd track **how often it gave a useful answer, how often a consultant corrected it, and whether anyone acted on a wrong one**.

Because my goal was never to take judgment away from the consultant. It was to give them a better starting point — and make uncertainty obvious before it reached a customer.

---

<p align="center"><a href="05-see-it-in-action.md">← See It in Action</a> &nbsp;·&nbsp; <a href="../README.md">Back to Sonny</a> &nbsp;·&nbsp; <a href="07-decisions-along-the-way.md">Decisions Along the Way →</a></p>
