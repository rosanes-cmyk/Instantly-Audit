# Three messages to send — 22 Sep 2026

Paste as-is. Send Cherry's first.

---

## 1 — CHERRY (send now)

Subject: Instantly audit — two things you need today

Hi Cherry,

The audit is finished and the tracker has the detail. Two things can't wait, and both involve you personally.

**Stanley Lo.** Between 20 and 25 July we sent him three cold acquisition emails from **my address, rosanes@twinhomebuyer.com**, as part of the Realtors July 2026 campaign. On **4 August you emailed him yourself** about an offer on 2032 Lyon Avenue, Belmont. So we cold-pitched an existing counterparty from our own domain, and ten days later did real business with him. We have completed DocuSign transactions with him going back to 2021. He has since died.

Those three emails also carried **no unsubscribe link and no postal address** — Realtors July 2026 is one of three campaigns missing both. His address is blocked now and his records are being pulled from the lists. I'd rather you hear this from me than from his family or his estate.

It wasn't isolated. **The blocklist was completely empty** when I opened it — eleven weeks of sending with no opt-out ever recorded. Four people had asked to be removed by replying, because there was no link to click. The oldest was 41 business days overdue. All four are blocked now.

**A campaign has been deleted.** A property send for 3375 17th St #311 went out 6–10 August — **over 2,000 emails** — and the campaign record no longer exists in Instantly. Only the raw message threads survive. Two consequences: every total I've reported is short by about 20% (the real lifetime is ~11,800 emails, not 9,821), and the bounces, replies and opportunities from those 2,000 sends are **unrecoverable**. It's also the campaign one of those four removal requests came from, so if we're ever asked to show we handled it properly, the campaign it came from is gone. I need to know who deleted it and why. Nothing gets deleted from here on.

**Then one decision, and the audit has made it sharper than I first thought.**

**Does cold outreach run from twinhomebuyer.com at all?** The split isn't a caps problem — it's which domain sends what:

- **twinhomebuyer.com** sends Realtors July, Oakland and SF County — the three campaigns with **no unsubscribe link**, 7,241 emails, and the two worst bounce rates (4.06% and 4.72%, both near the 5% level where providers suspend senders).
- **metrixgenerate.com** — the domain built to absorb exactly this risk — sends the compliant campaigns, and bounces at 1.69%.

The burner domain is carrying the safe traffic and our real business domain is carrying the risk. That domain also carries our contracts, our DocuSign, and your own correspondence. Stanley Lo is what that looks like in practice: cold mail from rosanes@twinhomebuyer.com in July, your offer from cherry@twinhomebuyer.com in August.

**And one more decision.** **Realtors July 2026** is paused at 11% and holds 9 of our 17 opportunities — our best performer, and also the campaign that emailed Stanley. The only note on it is "no further instructions." Resume, retire, or rework?

**One sign-off.** I've set a 24-hour first-touch target on realtor leads and a reporting cadence of daily at 4pm in Google Chat copied to you by email, plus a Friday weekly. Both are my proposal, not an agreement — say yes or tell me what it should be.

Nothing should resume on the three non-compliant campaigns until Legal clears the footer. I've written to them separately.

Jonathan

---

## 2 — LEGAL

Subject: CAN-SPAM review needed — 7,241 emails already sent

Hi,

I've audited our cold email setup and need a review before anything restarts.

**Three campaigns — Realtors July 2026, Oakland Realtor, San Francisco County Realtor — carry no unsubscribe mechanism and no physical postal address.** US CAN-SPAM requires both in commercial email. 7,241 emails have already gone out across them.

Because there was no link, replying was the only way out. **Four people did. None was recorded as an opt-out** — our blocklist was empty. The longest ran 41 business days past the 10-business-day window. All four are suppressed now.

A fourth campaign, Phase 1 – Peninsula, has the correct footer — San Carlos address plus unsubscribe — so it's a copy job once you've approved the wording. Its Step 2 has a broken unsubscribe link, which I'm fixing.

**What I need from you:**
1. Approve the footer wording before the three campaigns resume.
2. Confirm the San Carlos address is the right postal address for these sends.
3. Tell me whether the four late opt-outs need anything beyond suppression.

Happy to walk you through the tracker.

Jonathan

---

## 3 — REPLY TO LAWRENCE (replaces the original Carlo message — he's already answered)

Subject: Re: Instantly — thanks, two follow-ups

Hi Lawrence,

Thanks, that clears up most of it. Two of the four are closed on your answers.

**On the removed inboxes** — understood, and that's the right call. I'd logged them as an unattended error state; knowing they were pulled deliberately to protect mailbox health changes how it reads. Worth saying: the same logic applies to lawrence@, rosanes@, seth@ and bryan@, which are still sending cold at 100/day each on the same domain.

**On verification** — this was the most useful thing you told me, because it explains a result I'd misread. I'd assumed "verified" meant email verification. Checking whether a realtor has recently sold or listed is a better method than I'd credited, and the numbers back it: Peninsula bounces at **1.69% across 2,424 sends**, against **4.06%** on Realtors July 2026 and **4.72%** on SF County. Active realtors have live mailboxes. I've corrected my report.

The gap is narrower than I thought, and it's one thing: the activity check can't see whether the mailbox still exists. **23 of Peninsula's 41 bounces are dead compass.com addresses** on realtors who are demonstrably active. Can we run Instantly's bulk verification over each list before its campaign resumes — SF County and Realtors July first, since they're the two at 4%+? It's a pass over lists that already exist.

**On the ramp** — I had this wrong and I've withdrawn it. I'd read the 30/day as a throttle against the twinhomebuyer 100s; +5/day toward 100 is a deliberate ramp and the right mechanism.

I also asked you to hold at 50/day. **Withdrawing that too** — I pulled the daily send data and it doesn't support me. Per address, on each campaign's busiest day: SF County sent **26/day and fails at 4.72%**; Oakland sent **47/day and fails at 0.91%**. The one sending least fails most. Volume isn't what's driving it, the lists are. A cap cut would have cost us capacity and fixed nothing.

**So the real ask is just the list verification.** Can we run Instantly's bulk verification over each list before its campaign resumes? SF County first — it has **1,184 people who have never been emailed** sitting on the list with the worst delivery rate we own.

**And the source spreadsheets, which matter more than anything else here.** Every campaign's leads went straight into the campaign rather than a saved list, so a deleted campaign takes its list with it — which is exactly what happened to 3375 17th St. Can you send me the original CSVs you uploaded?

* Realtors July — 1,713 loaded, 1,554 contacted
* Oakland Realtor — 1,598 loaded, 948 contacted
* SF County Realtor — 1,387 loaded, 203 contacted
* Phase 1 – Peninsula — 517
* 27 Prague St — 156
* 3375 17th St #311, 6 August — ~2,000

I'm rebuilding them as permanent named lists so this can't happen again.

**Two questions on August, and I'd rather have them in writing.** The daily data shows **Realtors July, Oakland and SF County all stopped sending on 3 August, the same day** — that looks like one decision rather than three. What happened that week? And **who deleted the 3375 campaign, and why?** Instantly doesn't log it, so there's no way to answer it from the system.

Last one if you have time: can the Realtor Outreach KPI bot also flag any realtor lead past 24 hours without a first touch? You already have the API access.

Jonathan
