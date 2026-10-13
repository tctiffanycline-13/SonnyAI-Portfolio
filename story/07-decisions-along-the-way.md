<sub><a href="../README.md">Sonny</a> › Chapter 7 of 9</sub>

# 🧭 Decisions Along the Way

### The calls I made, and what I traded off.

---

The first six are calls I made while building Sonny. The last two are calls I'd make for what comes next. I don't rewrite old decisions. If I change my mind, I add a new one and explain why.

---

## 1. Start with support tickets, not the biggest time sink
*While building Sonny*

**The situation:** lots of things took up my time, but sloppy tickets were also keeping customers waiting.
**What I considered:** automate whatever took the most time, fix the thing hurting other people first, or build a general assistant.
**What I chose:** fix tickets first, with four details every ticket must have.
**The trade-off:** smaller time savings at the start, but Support noticed right away, and that built trust fast.
**How I checked:** I watched whether Support still came back with questions. They mostly stopped. I didn't measure it formally.

## 2. Sonny drafts, I send
*While building Sonny*

**The situation:** Sonny reads customer emails and writes things customers will read.
**What I considered:** let it send on its own, let it send when it's "confident," or keep it to drafts.
**What I chose:** drafts only, for anything a customer or colleague sees. Sonny could only act on its own in places that were mine, like a Slack message to me.
**The trade-off:** one extra click per email. In return, no emails to the wrong person and no claims I hadn't read.
**The risk:** people stop reading drafts and just click send. Keeping drafts short and consistent makes them quick to check.

## 3. Double-check before flagging
*While building Sonny*

**The situation:** a digest that says "you owe someone a reply" when you don't would lose my trust in a week.
**What I chose:** something only counts as still open if there's no sign I handled it in Slack, my sent email, a calendar invite, or another meeting.
**The trade-off:** it might occasionally miss something real. I'd rather that than get nagged about things I'd already done.

## 4. Leave a blank instead of guessing
*While building Sonny*

**The situation:** customer IDs and links are easy for AI to guess and painful when they're wrong.
**What I chose:** missing details become `[pending]`, and Sonny tells me where to fix them.
**The trade-off:** sometimes I fill in a blank by hand. A wrong customer ID never reaches Support.

## 5. Keep "how we work" separate from "how the product works"
*While building Sonny*

**The situation:** product names and features change all the time. A good implementation method doesn't.
**What I chose:** four files about our method, three about the products.
**The trade-off:** more setup up front.
**Why it matters:** this is what lets Sonny travel to other products and companies. It's the bet the next version is built on.

## 6. Leave one thing manual on purpose
*While building Sonny*

**The situation:** Sonny could have guessed each new hire's onboarding progress from their activity.
**What I chose:** I kept filling that in myself.
**Why:** the data didn't show it and I knew it. Automating it would have put a confident, wrong number in a report to leadership.

## 7. No single readiness score, yet
*For what comes next*

**The situation:** our scoping spreadsheet already estimates hours. What's missing is risk. One big "readiness score" would be easy to demo.
**What I considered:** one number from 0 to 100, two separate numbers, or green/yellow/red for each area with the reasons shown.
**What I chose:** green/yellow/red for each area, with the evidence. No overall number for now.
**Why:** my own rule from the playbook: a status only means something if you can show the evidence behind it. One number also hides the dangerous combinations, like a vague goal *plus* an unclear owner *plus* a tight deadline.
**The trade-off:** harder to compare projects at a glance, and a little less flashy.
**What would change my mind:** once we can show the flags actually predict real problems, a score might earn its place.

## 8. Check first, build second
*For what comes next*

**The situation:** "upload a contract, get a project plan" is the obvious product, and easy for anyone to copy.
**What I chose:** Sonny's first job is to point out what's missing, unclear or risky, and let the consultant agree or disagree. Plans and documents come after.
**The trade-off:** a less flashy first impression.
**The risk:** consultants might skip the check and just want the plan.
**How I'd know:** how often consultants agree with the flags, and whether those flags change their kickoff.

---

<p align="center"><a href="06-keeping-ai-in-check.md">← 🛡️ Keeping AI in Check</a> &nbsp;·&nbsp; <a href="08-whats-next.md">🚀 What's Next: The Kickoff Check →</a></p>
