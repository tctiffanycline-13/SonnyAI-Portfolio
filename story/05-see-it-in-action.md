<sub><a href="../README.md">Sonny</a> › Chapter 5 of 9</sub>

# 👀 See It in Action

### Real-looking examples with a made-up customer.

---

> **These are made up.** Every company, person and conversation here is fictional, written to show what Sonny's work looked like without sharing anything real.

The pretend customer is **Northwind Logistics**, setting up a sales content and training platform.

**In this chapter:** [Meeting recap + support ticket](#meeting-recap--support-ticket) · [Monday digest](#monday-digest) · [Contract review](#contract-review)

---

## Meeting recap + support ticket

### What Sonny started with: the meeting summary

> **Northwind Logistics: Implementation working session** · 42 min
> **Key takeaways:** Dana confirmed the regional sales group structure. Homepage draft approved with two changes. Sam reported that field reps on mobile can't open the pricing guides; desktop works.
> **Action items:** Dana to send final group list by Thursday. Tiffany to update homepage tiles. Sam to share a screenshot of the mobile error. Next session Tuesday 10am ET.

### Draft 1: the recap

> **To:** *[placeholder: me]*
> **Subject:** Recap - Northwind Logistics / [Vendor] - Implementation Meeting (March 12)
>
> Hi team,
>
> Thank you for a productive working session today. You can find the recording on your [project resource page](#).
>
> **Here are the key points we discussed:**
> - The regional sales group structure is confirmed and will drive content access.
> - The homepage draft is approved, with two tile changes requested.
> - Field reps can't open pricing guides on mobile, though desktop works as expected. We're treating this as a priority before launch.
>
> **Below are the agreed-upon next steps:**
> - **Dana:** send the final group list by Thursday
> - **Tiffany:** update the two homepage tiles
> - **Sam:** share a screenshot of the mobile error
>
> Next meeting: Tuesday at 10am ET.
>
> Please let me know if I missed anything or if there's anything you'd like me to adjust.
>
> Best,
> Tiffany

### Draft 2: the support ticket

> **To:** *[placeholder: me]*
> **Subject:** Northwind Logistics - Pricing guides fail to open on mobile
>
> **Customer:** Northwind Logistics · Site: `northwind.example.com` · Customer ID: `[pending]` · Account ID: `NW-DEMO-01`
> **Issue:** Field reps cannot open pricing guide documents on the mobile app. The same documents open on desktop. Error screenshot requested from the customer.
> **Requested action / priority:** Investigate mobile rendering of these documents. **High:** field reps are the primary launch audience.
> **Affected users:** Field sales reps (regional groups); reported by Sam (Northwind IT)

### The quick report Sonny sends me

```
Threads found: 1
  Northwind Logistics · March 12
    Recap draft: created
    Tickets: 1 created (mobile pricing guides)
    Skipped tickets: none
Directory gaps: Northwind Logistics is missing Customer ID → add to directory
Failures: none
```

#### What to notice
- **Nothing was sent.** Both drafts are addressed to me.
- **The missing customer ID became `[pending]`,** with a note to fix it, instead of a guess.
- **The ticket has all four details,** which is why Support stopped coming back with questions.
- **Next steps are grouped by person,** and the next meeting is only listed because it came up in the call.

---

## Monday digest

Delivered as a Slack direct message on Monday morning.

---

**Good morning!** Here's your weekly digest for Mar 9 – Mar 13.

**🌐 EXTERNAL MEETINGS**

> **Northwind Logistics: Working session** · Thu, Mar 12
> 📋 **Recap:** Group structure confirmed; homepage approved with two changes; mobile issue on pricing guides raised by their IT lead.
> 🎯 **Action items:**
> • ✅ Update homepage tiles · *you posted the updated tiles in the project channel on Friday*
> • 🔄 Mobile pricing guide issue · *ticket drafted; no response from Support yet*
> • ⏳ Confirm SSO test date with Northwind IT · *no reply, sent email, or invite found*

> **Contoso Health: Launch readiness review** · Fri, Mar 13
> 📋 **Recap:** Two of three test users passed; one user could see content they shouldn't.
> 🎯 **Action items:**
> • ✅ Schedule the re-test · *calendar invite sent Friday 4:12pm*

**🏠 INTERNAL MEETINGS**

> **Team meeting** · Tue, Mar 10
> 🎯 **Action items:**
> • ✅ Share the kickoff checklist · *resolved in Wednesday's 1:1 summary*

---

**🏆 TOP WINS**
• 🎉 Contoso's access issue got caught in testing, not after launch.
• 🎉 Northwind's homepage was approved in one round.

---

**📬 PENDING — NEEDS YOUR ATTENTION**

🔴 **Urgent**
• **Fabrikam:** renewal contact has followed up twice about the expansion scope · *Email*

🟡 **High**
• **Northwind IT:** waiting on you to confirm the SSO test date · *Email*

🔵 **Medium**
• **New consultant:** asked for feedback on their mock kickoff · *Slack*

— *Sonny* 🤖

---

#### What to notice
- **Every ✅ says how Sonny knows it's done:** a Slack post, a calendar invite, another meeting.
- **Only three things made the "needs you" list.** Lots of other things came up that week, but they were already handled.
- **Urgent follows a rule, not a vibe:** someone following up twice about a renewal is always urgent.

---

## Contract review

**Consultant's request:** *"Review the Northwind SOW before kickoff. Anything I should worry about?"*

---

### The short answer

**Proceed to kickoff, but resolve two contradictions with Sales first.** The scope is clear on products and exclusions. It's thin on success criteria and assumes customer capacity the handoff doesn't support.

### What the contract actually says (the highlights)

| What | What it says | Where |
|---|---|---|
| Goal | "Help field sales find approved content faster" | §1 |
| Who does the setup | The customer handles content, users and settings | §4 |
| Timeline | 90 days from kickoff | §5 |
| Not included | Moving existing content; creating new content | §6 |
| Success criteria | **Missing.** The section still has template text in it | §7 |
| Vague wording | "Custom branding as needed" | §3 |

### ⚠ Things that don't match

1. **Customer capacity.** The contract puts content and user setup on Northwind. The handoff says their project owner "is stretched across two other launches." If that's true, the build work has no owner.
2. **Migration.** The handoff notes Northwind "expects help moving their existing library." The contract excludes it.

### What's missing

- Measurable success criteria (template text was never replaced)
- User provisioning method
- Named executive sponsor

### Extra asks, and how to handle them

| Request | Response |
|---|---|
| Content migration | Clarify the outcome they want; check whether a migration consultation plus a self-serve upload plan covers it; if not, document effort and route for a change order. **Don't commit on the kickoff call.** |
| "Custom branding as needed" | Define "custom" before kickoff. Standard branding settings are in scope; bespoke design work is not. |

### Questions for Sales before kickoff
1. Who owns content upload on Northwind's side, and do they have the time?
2. Was migration discussed as included, or as something to scope later?
3. What did Northwind say success looks like in their own words?

### Double-check before telling the customer
- Whether the AI search add-on covers all content types Northwind plans to upload. *Product behavior varies by configuration; verify against current documentation.*

---

#### What to notice
- **The answer comes first,** then the details.
- **Everything points back to the contract,** and "it's not in there" counts as a finding.
- **The scope advice is specific:** what to do, and what not to promise.
- **When Sonny isn't sure about the product, it says so** instead of guessing.

---

<p align="center"><a href="04-what-sonny-did.md">← 🛠️ What Sonny Did</a> &nbsp;·&nbsp; <a href="06-keeping-ai-in-check.md">🛡️ Keeping AI in Check →</a></p>
