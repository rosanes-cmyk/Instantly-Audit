# Getting the 324 bounced addresses out

**Why bother:** those 324 addresses are dead. If a campaign resumes, they bounce again and count against us again. Putting them on the do-not-email list is the cheapest thing we can do to our bounce rate — one upload, and they can never be emailed by any campaign again.

Right now nothing stops it. There is no rule that a bounced address gets suppressed.

---

## Ask Instantly AI this

> For every email in this account that bounced or failed to deliver, list:
>
> * the recipient email address
> * the campaign it was sent from
> * the date it bounced
> * the bounce reason or error code, and whether it was a hard or soft bounce
> * the sending address it went out from
>
> Include the deleted campaign `c05714e3-35db-4223-8873-c65639a33173`. There should be about 324 in total: 198 on Realtors July 2026, 41 on Phase 1 – Peninsula, 29 on San Francisco County Realtor, 16 on Oakland Realtor, 2 on 27 Prague St, and roughly 38 on the deleted campaign.
>
> Then group them two ways: by recipient domain, and by bounce reason. I want to know which brokerages give us the most dead addresses, and how many are hard bounces we should never retry.

---

## Or get it yourself, no help needed

**Per campaign:** open the campaign → **Analytics** → **Bounced** (or the bounce count itself, which is usually clickable) → select all → **Export**. That gives you a spreadsheet per campaign.

**Account-wide:** Unibox → clear the status filter → filter to bounced → export.

**The deleted campaign:** Unibox only, filtered on campaign id `c05714e3-35db-4223-8873-c65639a33173`. Its own analytics page is gone.

---

## Then do this with them

1. **Upload all 324 to the do-not-email list.** Settings → Blocklist → import. Takes minutes and applies to every campaign at once, forever.
2. **Look at the hard bounces separately.** A hard bounce means the mailbox does not exist. Those should never be retried by anyone, ever.
3. **Check the domain grouping.** If compass.com accounts for 23 of Peninsula's 41, it will show up across the others too. A brokerage that changed its email system leaves hundreds of dead addresses behind, and that is worth knowing before buying another list.
4. **Take them out of the source spreadsheets too** — the ones Seth and Lawrence are sending over. Otherwise the same dead addresses get re-uploaded next time and we are back here.

---

## What this does to the numbers

Removing 324 dead addresses does not change the past. The 2.74% already happened.

What it changes is the next send. San Francisco County has **1,184 people never emailed** on a list that already bounces at 4.72%. If a meaningful share of its 29 known bounces share a domain with those 1,184, cleaning first is the difference between resuming safely and resuming into a block.

Send me the export and I will work out exactly how much of that list is at risk.
