# Questions for Seth and Lawrence

*(Originally addressed to Lawrence. Re-pointed 23 Sep — Seth and Lawrence are the people who can walk through how the setup works and how anything was wired.)*

Ordered by what can't be recovered later. The first three are the ones to get today.

---

## 1 — The deleted campaign

**1.1** ~~Who deleted the campaign for `3375 17th St #311` (id `c05714e3-35db-4223-8873-c65639a33173`), when, and why?~~ **ANSWERED — no longer a question for you.** Jonathan deleted it deliberately; Seth and Lawrence have both confirmed it was a test of that listing approach, not a funded campaign. The remaining questions below still stand, because the send itself reached about 2,000 real agents with no unsubscribe link.

**1.2** **Has anything else been deleted?** Campaigns, lead lists, or sending accounts. I'm asking because our lifetime total was short by about 20% and nobody knew.

**1.3** **Can we export the surviving Unibox message threads for it before they go?** They're the only remaining record of those 2,000+ sends. Once they're gone the sends are unauditable — including the removal request Leah McKern sent on 7 August.

---

## 2 — The August send volume

**2.1** That campaign sent 2,000+ emails in five days across five metrixgenerate mailboxes — roughly **80/day per mailbox**. Lawrence says those accounts ramp +5/day from 30 toward 100. **What were the caps in August, and were they cut afterwards?** I need to know whether the caps govern actual volume or not.

---

## 3 — The root cause of Stanley Lo

**3.1** We cold-emailed Stanley Lo — an existing counterparty with DocuSign transactions back to 2021 — from rosanes@ in July, and Cherry emailed him about a live offer in August. **Is there any suppression list of existing clients and counterparties?**

**3.2** **Can we pull a list of every email address we've ever transacted with** — from the CRM, DocuSign, or the mailboxes — and load it into the Instantly blocklist as a standing exclusion? This is the fix that stops it recurring.

---

## 4 — How the lists are built

**4.1** Verification checks whether a realtor has recently sold or listed. **Does anything check the state or licence?** Leah McKern was sent a San Francisco listing on a Texas TREC licence.

**4.2** **Does anything check whether a person is already on another campaign?** Max Lo received 16 emails — two campaigns, four sending addresses, both domains. He got twinhomebuyer.com in July and metrixgenerate.com in September, which shows anyone paying attention that the two domains are one operation.

**4.3** **Are the lists de-duplicated by person or by email address?** Max Lo was on one list twice under two addresses.

**4.4** Do you have the **source files** for each list — where each was bought or built, and when?

---

## 5 — Things I couldn't resolve from the screens

**5.1** **Are carlo@ and juan@ actually deleted?** Instantly lists 11 sending accounts while reporting 9, and both still appear. accounting@ is correctly gone. If those two are still attached, Realtors July and SF County can resume on a broken sender.

**5.2** **Is the CRM connected to Instantly at all?** Any webhook or integration? Where do opportunities land, and has it ever fired successfully?

**5.3** **Why did Realtors July 2026 stop at 11%?** It holds 9 of our 17 opportunities and the only note on it is "no further instructions."

**5.4** The three realtor campaigns run **identical copy** to overlapping Bay Area audiences from one domain. **Deliberate, or copied and never differentiated?**

**5.5** The campaign index lists **8 sequence steps** for those three campaigns; the export has 7. **What is Step 8?**

**5.6** Does **Mariaelena Diaz** (DRE #02034560) have a signed agreement covering the 27 Prague St and 3375 17th St sends? She's the third-party agent both were signed by.

---

## 6 — Two things for the KPI bot

**6.1** The bot posts campaign names that don't match Instantly — it reported "PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500" for what Instantly calls "Phase 1 – Peninsula Listing Agents." **Can it post the Instantly name**, or can we write the mapping down? That one mismatch cost most of a day.

**6.2** **Can it flag any realtor lead past 24 hours without a first touch?** You already have the API access, so this is the cheapest way to make the SLA real rather than aspirational.
