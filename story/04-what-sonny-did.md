<sub><a href="../README.md">Sonny</a> / Chapter 04 of 08</sub>

# What Sonny Did 🛠️

### The actual workflows, without the technical jargon.

Sonny started as a way to make my own workday easier. Once those workflows proved useful, I started building a copilot that could help other implementation consultants find answers and make better decisions.

This chapter covers **what I built and used**, then **what I built and piloted**. The bigger, unbuilt implementation vision lives in [Chapter 8](08-whats-next.md).

---

## 01 / The personal assistant

![Five personal Sonny workflows](assets/01-personal-workflows.png)

I used **Claude** with tools we already worked in: Gmail, Slack, Google Docs and Sheets, Zoom meeting summaries, a browser, and our time-tracking system. Some workflows ran on a schedule; others were one-off requests.

### The one I used most: meeting follow-ups

**The problem:** After a customer call, I still had to turn my notes into a recap and, if something was broken, a support ticket.

**Sonny's job:** Use the meeting summary, customer directory, and open tickets to prepare drafts for me to review.

**The result:** My observed prep time went from **30–60 minutes to under five minutes**. That's from my own use, not a controlled team-wide measurement.

<details>
<summary><b>See the workflow rules (and a workaround I'm still proud of)</b></summary>

- Drafts were addressed to me, not sent to customers.
- Never mark emails as read or change the customer directory.
- Use `[pending]` for missing details rather than guessing.
- Tickets needed the customer, problem, requested action and urgency, and affected users.
- Check existing open tickets to avoid duplicates.

**The workaround:** The email connection only returned a preview of some messages. Rather than working from incomplete context, Sonny opened the full message in a browser. Not glamorous, but it mattered.

[See an example recap and ticket →](05-see-it-in-action.md#meeting-recap--support-ticket)
</details>

### The other four workflows

| Workflow | What Sonny prepared | What kept it useful |
|---|---|---|
| **Monday digest** | Wins, meeting highlights, and open items in Slack | Checked sent email and other updates before calling something overdue |
| **Tuesday agenda** | Team updates, an icebreaker, a learning topic, and top tracker issues | Included only updates grounded in actual messages; readable in two minutes |
| **Friday ramp report** | Status updates for new consultants | Used defined green/yellow/red rules; I filled in context the data couldn't capture |
| **Vacation catch-up** | A prioritized list of what still needed attention | Removed anything resolved while I was away |

<details>
<summary><b>More on the Monday digest</b></summary>

Sonny looked across meeting summaries, Slack, and my email — including messages I'd sent. An item counted as open only if there was no sign I'd already handled it. Customer escalations and repeated follow-ups took priority; newsletters and automatic notifications didn't.

[See an example digest →](05-see-it-in-action.md#monday-digest)
</details>

---

## 02 / The consultant copilot

My personal workflows were useful, but I kept seeing a bigger problem: **the team needed easier access to the knowledge experienced consultants had built up over years.**

I built and began piloting a knowledge copilot that consultants could ask for help with preparation, scoping, troubleshooting, and launch decisions.

![Two types of knowledge behind Sonny](assets/02-copilot-knowledge.png)

I organized its knowledge into **seven files**: four about how we work, and three about how the products work. That separation was deliberate. Our implementation methodology should be reusable even as products, packaging, and features change.

### Eight ways a consultant could use Sonny

| Ask Sonny for… | Get back… |
|---|---|
| **Call prep** | Customer goals, stakeholders, agenda, questions, demo ideas, and a backup plan |
| **Contract review** | What was agreed, what was unclear, and possible scope concerns |
| **Project planning** | Suggested milestones, owners, and definitions of done |
| **Product coaching** | A feature explained in customer-friendly language |
| **Troubleshooting** | A structured investigation and the details Support would need |
| **Launch readiness** | A green/yellow/red assessment with reasons |
| **Customer communication** | Draft recaps, action lists, risk notes, and handoffs |
| **Practice** | Customer role-play, quizzes, and practice-call feedback |

[See examples of Sonny's outputs →](05-see-it-in-action.md)

<details>
<summary><b>What Sonny was taught about a good implementation</b></summary>

1. Start with why the customer bought the product, not a feature tour.
2. Explain what to configure, why it matters, how to test it, and what can go wrong.
3. Launch the simplest useful version first.
4. Have customers practice during training rather than just watch.
5. Distinguish documented product behavior from recommended practice.
6. Never invent product functionality, pricing, or contracted scope.
7. Flag requests that fall outside the agreement.
8. Consider reporting and adoption from the beginning.

</details>

---

## 03 / What Sonny didn't do

Sonny wasn't a replacement for a consultant. It **prepared work and surfaced information**; people still made the calls.

- **No autonomous customer emails.** I reviewed drafts before sending.
- **No invented details.** Missing information stayed visible.
- **No unapproved scope promises.** Anything outside the contract was flagged.
- **No pretending every signal was in the data.** Some onboarding judgments stayed manual.

And I didn't collect enough data from the team pilot to claim company-wide time savings or adoption results.

That's an important distinction: **the personal workflows were built and used; the team copilot was built and piloted; the end-to-end implementation platform was a future concept.**

---

## What I'd improve next

I'd standardize access to shared knowledge, give each knowledge source a clear owner, and measure output quality and consultant adoption during a longer pilot.

Because a good assistant isn't just one that gives an answer quickly. It's one people can rely on — and know when to question.

---

<p align="center"><a href="03-how-sonny-grew.md">← How Sonny Grew</a> &nbsp;·&nbsp; <a href="../README.md">Back to Sonny</a> &nbsp;·&nbsp; <a href="05-see-it-in-action.md">See It in Action →</a></p>
