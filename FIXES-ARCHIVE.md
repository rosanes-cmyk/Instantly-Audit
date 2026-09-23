# Fixes archive — full audit record

The Fixes tab in the tracker now carries Cherry's three decisions only. This is the complete record of everything the audit found, preserved verbatim. It is also in the artifact database as `state/fixes_archive`.

**34 items.**

## Add unsubscribe link and postal address to 3 campaigns

`Blocker` · owner **Legal** · status **Blocked**

Realtors July 2026, Oakland Realtor and San Francisco County Realtor carry no opt-out mechanism and no physical postal address, across 7,241 emails already sent. US CAN-SPAM requires both in commercial email. Phase 1 – Peninsula already has the correct footer (San Carlos address + unsubscribe), so it is a copy job once reviewed.

THE MANUAL FALLBACK DEMONSTRABLY FAILED. With no link, replying was the only way out — four people did, and none was recorded as an unsubscribe. Four out of four missed. So this is not a paperwork gap: the opt-out route did not work in practice, and one person was told in writing they had been removed when there is no record of it.

DONE = footer present on all three, signed off by whoever handles legal, and the four known opt-outs blocklisted.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Legal. Route through Cherry, who directs the work.

---

## Suppress stanleylo@greenbanker.com — do not send

`Blocker` · owner **Jonathan** · status **Done**

DONE 22 Sep 2026: stanleylo@greenbanker.com blocklisted. Stanley Lo has died; no reply was sent, which is the correct outcome. The blocklist prevents any sequence reaching the address whatever list it sits on — and it was found still sitting on a campaign lead list, so without this a resumed campaign would have emailed him.

Context worth keeping: Stanley was not a cold prospect. juan@'s mailbox holds completed DocuSign transactions from 2021 onward, offers and disclosures on 2032 Lyon Avenue Belmont, 2704 Hillside Dr Burlingame, 340 Chesham and 1705 Wolfe Drive, and a property walkthrough invitation, with Juan signing as Managing Member and President. He was still sent the Realtors sequence opening 'I'm Juan Diaz, founder of Twin Home Buyer', and his reply sat unread for about two months in a mailbox whose IMAP was not connected. It can no longer be answered. That single thread is the strongest argument in this audit both for the suppression list and for reading replies daily.

The Green Banker contact decision and the duplicate lead record are tracked separately.

---

## Blocklist the 4 manual opt-outs — all overdue

`Blocker` · owner **Jonathan** · status **Done**

DONE 22 Sep 2026. All four opt-outs honoured on the Instantly blocklist, verified on screen:
· kurt@readyrealtyllc.com — 9:02 AM — asked 24 Jul, 41 business days late
· jason@jasonborn.com — 9:02 AM — asked 31 Jul, 36 business days late
· leah@leahmckern.com — 9:02 AM — asked 7 Aug, 32 business days late
· johnanagnostou@me.com — 9:12 AM — asked 2 Aug ('Stop'), removal promised by juan@ 3 Aug, 37 business days late
· VOICE blocklist: +16502557840 (John Anagnostou) — 9:12 AM, because he said 'Stop', not 'stop emailing'
Addresses only, no domains, so colleagues who never opted out are unaffected.

WHEN FOUND the blocklist was completely empty — 'No entries found' — so across 9,825 emails and 11 weeks not one opt-out had ever been recorded by any route. Instantly had John tagged 'Not interested', so the system knew and never acted on it.

Sweeping the campaign lists for these addresses is tracked separately, so it does not hold this closed.

---

## Decide whether cold outreach runs from twinhomebuyer.com

`Blocker` · owner **Cherry** · status **Blocked**

All 4,867 emails of Realtors July 2026 went from the primary business domain, including the owner's own address and a role address. If that domain is filtered it takes the company's real mail with it. DONE = a decision recorded here, and the caps set to match it.

SHARPENED 22 Sep 2026 by Instantly AI's per-campaign sender lists, which show the split is clean and is exactly the wrong way round:

  twinhomebuyer.com sends: Realtors July 2026 · Oakland Realtor · San Francisco County Realtor
  metrixgenerate.com sends: Phase 1 – Peninsula · 27 Prague St · the deleted 3375 17th St campaign

The three campaigns on the PRIMARY BUSINESS DOMAIN are precisely the three with NO unsubscribe link and NO postal address — 7,241 emails of non-compliant mail — and they carry the two worst bounce rates in the account, 4.06% and 4.72%. The three on the burner domain are the compliant ones, and Peninsula bounces at 1.69%.

So metrixgenerate.com, the domain built to absorb risk, carries the safe traffic. twinhomebuyer.com, which carries the company's real mail — contracts, DocuSign, Cherry's own correspondence — carries the non-compliant, high-bounce traffic. That is the entire risk of this setup in one sentence, and it is not a cap problem: swapping the caps would not change which domain sends which campaign.

Stanley Lo makes it concrete. Three non-compliant cold emails reached him from rosanes@twinhomebuyer.com in July; Cherry emailed him from cherry@twinhomebuyer.com about a real offer in August. Same domain, both times.

DONE = a decision from Cherry on whether twinhomebuyer.com sends cold mail at all, and if not, the three realtor campaigns moved to metrixgenerate senders before any of them resumes.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Max Lo got 16 emails from both domains — the separation is defeated

`Blocker` · owner **Lawrence** · status **Blocked**

CONFIRMED 22 Sep 2026 on Phase 1 – Peninsula. Max Lo appears twice on the same list under two addresses — maxlo.greenbanker@g… (Google) and maxlo@greenbanker.com (Microsoft). The campaign contacted 516 of its 517 leads, so both were emailed: one person received the sequence twice.

Neither Max Lo address is blocklisted — only Stanley's is. If Green Banker is off-limits (see that fix), both need adding.

Also visible on those rows: JOB TITLE, COMPANY, LOCATION, WEBSITE and LINKEDIN are all EMPTY. These leads are name and email only, with no enrichment — so nothing in the list itself establishes that they are listing agents in the Peninsula, which is what the campaign claims to target. That bears on the list-relevance fix as much as this one.

Found by accident while searching one domain on one campaign, so the duplicate rate across 9,825 sends is unknown.

DONE = every campaign list de-duplicated by person rather than by address, and a rule for catching it at import.

CONFIRMED AND MUCH WORSE, 22 Sep 2026. Instantly AI's send records:

maxlo@greenbanker.com — 8 emails
  Realtors July 2026, from rosanes@twinhomebuyer.com: 20, 22, 25 Jul (steps 1–3)
  Phase 1 – Peninsula, from ariana@metrixgenerate.com: 1, 2, 3, 4, 7 Sep (steps 1–5)

maxlo.greenbanker@gmail.com — 8 emails
  Realtors July 2026, from rosanes@twinhomebuyer.com: 21, 22, 25 Jul (steps 1–3)
  Phase 1 – Peninsula, from victoria@metrixgenerate.com: 1, 2, 3, 4, 7 Sep (steps 1–5)

SIXTEEN COLD EMAILS TO ONE PERSON, across two campaigns, from four sending addresses, ON TWO DIFFERENT DOMAINS. No opens (tracking off), no replies.

THE REAL DAMAGE IS NOT THE DUPLICATION — IT IS THE DOMAIN EXPOSURE. metrixgenerate.com exists so cold outreach risk stays off twinhomebuyer.com. Max Lo received, across his two mailboxes, the same kind of pitch from twinhomebuyer.com in July and from metrixgenerate.com in September. Anyone who puts those side by side can see the two domains are one operation. The separation the whole sending architecture depends on is defeated by the lists overlapping — and nobody would have noticed, because nothing checks whether a person is already on another campaign.

If it happened to the one person we happened to look at, the rate across 11,800+ sends is unknown and could be large. Question 19 on the Instantly AI list will give the number.

Raised from severity 3 to severity 1. This is not list hygiene; it is the sending strategy failing silently.

DONE = the cross-campaign overlap measured, a rule that no person enters a second campaign while on another, and a decision on whether the two domains can still be treated as separate given how much overlap there is.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## A campaign that sent 2,000+ emails was deleted — records gone

`Blocker` · owner **Jonathan** · status **Open**

CONFIRMED BY INSTANTLY AI, 22 Sep 2026. The campaign for '3375 17th St #311 – Available from Owner/Investor' exists, id c05714e3-35db-4223-8873-c65639a33173. It sent from 6 to 10 August 2026, from all five metrixgenerate.com accounts, to SF-area agents. Volume: OVER 2,000 EMAILS. Its status is Deleted — the API returns 404 and the campaign record is gone. Only the Unibox message threads survive.

WHY THIS IS THE MOST SERIOUS FINDING IN THE AUDIT.

1. THE LIFETIME FIGURE IS WRONG BY ABOUT 20%. Every total in this tracker and in the report to Cherry rests on 9,821 sends across five campaigns. Add this campaign and the real number is roughly 11,800+. Its bounces, replies and opportunities are in no total we have, and cannot be recovered from the campaign record, because there is no campaign record.

2. IT IS THE CAMPAIGN THAT COLLECTED AN OPT-OUT REQUEST. Leah McKern replied to this send on 7 Aug asking to be removed. So the one campaign whose record has been destroyed is a campaign with a known unhonoured opt-out against it. If we are ever asked to show we handled that request properly, the campaign it came from no longer exists in our system.

3. DELETING A CAMPAIGN IN INSTANTLY DESTROYS THE SEND RECORD. That is now demonstrated, not theoretical. STANDING RULE FROM HERE: no campaign is ever deleted again. Pause, archive, rename — never delete. (Noted against myself: I advised deleting TEST CAMPAIGN REPLY earlier today. Four sends, and its figures were captured first, so nothing was lost — but the advice was given without knowing this, and I would not give it again.)

4. THE VOLUME DOES NOT FIT THE CAPS. Over 2,000 emails in five days from five accounts is roughly 400/day, or 80/day per mailbox. Lawrence describes metrixgenerate as ramping +5/day from 30 toward 100. Either the caps were far higher in August and were cut afterwards, or the caps are not what governs actual send volume. Worth asking.

QUESTIONS THAT NEED ANSWERS: who deleted this campaign, when, and why. Whether the same has happened to others. And whether the Unibox threads can be exported before they go too.

DONE = the surviving Unibox threads exported and kept; volume, bounces and replies reconstructed from them as far as possible; every total in this tracker restated to include it; who deleted it and why established; and the no-deletion rule written into the SOP.

---

## Stanley Lo — cold-emailed from rosanes@ in July, Cherry's offer in August

`Blocker` · owner **Cherry** · status **Blocked**

CONFIRMED ON SCREEN 22 Sep 2026. A 'greenbanker' search on Phase 1 – Peninsula Listing Agents (campaign 2484bb6e-1c62-41fe-8be4-414a5ec058fc) returns three leads:
  1. Max Lo — maxlo.greenbanker@g… (Google)
  2. Max Lo — maxlo@greenbanker.com (Microsoft)
  3. Stanley Lo — stanleylo@greenbanker… (Microsoft)

The campaign is marked Completed and its own counters read 517 leads / 516 contacted. Exactly ONE lead of 517 went uncontacted, so all three of these were emailed — at most one could have escaped, and not all three. This is no longer a question of exposure risk: the sends happened.

What that means. Stanley Lo was not a cold prospect. juan@'s mailbox holds completed DocuSign transactions with him from 2021 onward — offers and disclosures on 2032 Lyon Avenue. He has since died. Cold acquisition mail from this campaign reached a deceased existing counterparty's mailbox, which is now read by whoever handles his affairs. Blocklisting (done) stops anything further; it does not undo this.

STILL TO CAPTURE, before the rows are deleted: open each of the three leads and record from the activity timeline the send dates, how many of the 8 steps went out, and any opens or replies. The list view does not show contacted status — the lead detail panel does.

DONE = send dates and step counts captured for all three, the rows deleted, and Cherry told. A send to a deceased existing client is a relationship and reputational matter, not a deliverability one, and she should hear it from us rather than from the family.

CORRECTED 22 Sep 2026 — I HAD THE WRONG CAMPAIGN. I recorded that Stanley Lo was emailed by Phase 1 – Peninsula, inferred from his appearing in a greenbanker search of Peninsula's lead list against 516 of 517 contacted. Instantly AI's send records say otherwise, and they are the better evidence.

WHAT ACTUALLY HAPPENED. Stanley Lo was emailed by REALTORS JULY 2026 — three sequence emails, all from rosanes@twinhomebuyer.com:
  - 20 Jul 2026 23:47 UTC — Step 1, 'Stanley — help with off-market situations'
  - 22 Jul 2026 20:10 UTC — Step 2, 'seller who can't list?'
  - 25 Jul 2026 19:32 UTC — Step 3, 'Re: seller who can't list?'
No opens recorded (open tracking is off on the campaign). No reply.

THEN, TEN DAYS LATER: a manual email on 4 Aug 2026 from cherry@twinhomebuyer.com, about an offer on 2032 Lyon Avenue, Belmont.

So the order is: we cold-pitched him from Jonathan's own address in July, and Cherry emailed him about a real live offer in August. The cold mail came first. He is not a stranger contacted by mistake — he is a counterparty the company was actively doing business with while a cold acquisition sequence ran at him.

WORSE THAN I FIRST RECORDED, ON THREE COUNTS.
  - The sender was rosanes@twinhomebuyer.com — the primary business domain and Jonathan's own address, not a burner.
  - Realtors July 2026 is one of the three campaigns with NO unsubscribe link and NO postal address, so those three emails were non-compliant as well.
  - Cherry is personally in the thread, so this is not something she can be told about abstractly.

He is on Peninsula's lead list too, but Instantly AI records no Peninsula sends to him — which would make him the single uncontacted lead of Peninsula's 517. Worth one check, because the alternative is that the send records are incomplete.

He has since died. His address is blocklisted, which stops anything further.

DONE = Cherry told, with these dates and the Lyon Avenue thread in front of her; his records removed from both lead lists; and the cause established, which is that existing counterparties were never screened out of the cold lists.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Fix the empty unsubscribe href on Peninsula Step 2

`Blocker` · owner **Jonathan** · status **Open**

The one campaign with a compliant footer has an empty href on its Step 2 unsubscribe link, so recipients of that step could not opt out. DONE = the link resolves to a working unsubscribe.

---

## Check list relevance, not just deliverability

`Blocker` · owner **Lawrence** · status **Blocked**

Two proven cases, neither of which email verification would have caught:

1. Leah McKern was sent a San Francisco listing. She holds a TREC licence — a Texas agent — and moved there about a decade ago. Her address was valid, so verification would have passed her straight through.
2. Existing counterparties are on the cold lists (see the suppression-list item), so valid, relevant-looking addresses can still be entirely the wrong people to contact this way.

This is how to read the verified-500 result: 0 bounces on 19 sent proves the addresses work. It proves nothing about whether the people are the right people. A campaign can hold a 0% bounce rate while going to the wrong market, or to your own clients.

DONE = a documented sourcing rule covering geography, licence state and exclusion of existing relationships, and a sample of the verified-500 list checked against it.

ANSWERED 22 Sep by Lawrence Oliveros: "those are realtors verified thru the process of checking if they have sold or listed new properties thats how can i say its verified."

THIS IS THE MOST USEFUL ANSWER OF THE FOUR, and it settles what 'verified' has meant all along: verified for REALTOR ACTIVITY — has this person recently sold or listed — and not for anything else. That is a real targeting method and a better one than a bought list, and if Phase 1 – Peninsula is the verified list then it has the numbers behind it: 41 bounces on 2,424 sent, 1.69%, against 4.06% on Realtors July 2026 and 4.72% on San Francisco County. Two and a half times better across a large sample. Active realtors have live mailboxes.

But it also names precisely what the check does NOT cover, and each gap matches a failure already on record:

1. EMAIL VALIDITY. 23 of Peninsula's bounces are invalid recipients at compass.com, SMTP 5.1.1 — dead addresses. A realtor can have listed a property last month and still have a mailbox that no longer exists. Activity verification cannot see that; a pre-send validity check can.
2. GEOGRAPHY AND LICENCE STATE. Leah McKern was sent a San Francisco listing on a Texas TREC licence. She may well have sold or listed recently — in Texas. The activity check passes her.
3. EXISTING RELATIONSHIPS. Stanley Lo sold and listed. He was also an existing counterparty with DocuSign transactions back to 2021, and has since died. The activity check passes him too, and did.

None of these is a criticism of the method. They are three screens to run alongside it.

CORRECTION TO THE AUDIT REPORT: it said the verified-500's 0 bounces on 19 sends were 'the first hard evidence that pre-send verification fixes the bounce problem'. That was wrong — the verification was never about email addresses. The corrected and much stronger evidence is the 1.69% versus 4.06%/4.72% comparison above, subject to confirming Peninsula is the verified list.

DONE = a documented sourcing rule that keeps the activity check and adds validity, geography/licence state, and exclusion of existing relationships, plus a sample of the verified list checked against it.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Read juan@'s mailbox for unanswered replies

`Blocker` · owner **Jonathan** · status **Done**

CLOSED 22 Sep 2026 AS WON'T DO. Decision taken by the creator of the Instantly setup together with the team — not a unilateral call by Jonathan. The position: nobody will be checking that mailbox.

What that leaves open, recorded so it is not a surprise later: juan@twinhomebuyer.com's Google mailbox still exists and has never been read. Its IMAP was never connected to Instantly, which is why Stanley Lo's and John Anagnostou's replies sat unseen for about two months — both were found by manual searching, not by any system surfacing them. The account has now been deleted from Instantly, so nothing will surface anything in there again.

The risk is specific rather than theoretical: this mailbox is known to have received reply traffic including opt-out-adjacent messages, and CAN-SPAM gives 10 business days to honour an opt-out. Any further request sitting in it is already overdue and will stay unhonoured.

Cheap ways to close it off later: forward the mailbox to a monitored inbox, set an auto-reply pointing senders somewhere live, or read it once and close the account. Reopen this item if any is chosen.

---

## Reconcile the full campaign inventory

`Blocker` · owner **Jonathan** · status **Done**

REVISED 22 Sep after reading the Engage campaign list with the status filter on 'All statuses'. It shows five campaigns: 27 Prague St (156 sent), Phase 1 – Peninsula Listing Agents (2,424), San Francisco County Realtor (614), Oakland Realtor (1,760), Realtors July 2026 (4,867). Sum: 9,821 sent, 17 opportunities.

ONE OF THE TWO GAPS HAS PROBABLY CLOSED. 'PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500' is most likely Phase 1 – Peninsula Listing Agents under a different label: Peninsula holds 517 leads, is Completed at 100%, and has run out of leads. Check Peninsula → Analytics over 21 Sep; 19 emails that day confirms it, and this half of the blocker closes.

THE OTHER GAP IS REAL AND STANDS. The property campaign for '3375 17th St #311, San Francisco', sent by victoria@metrixgenerate.com on 7 Aug, appears nowhere in this list. It is the email Leah McKern replied to asking for removal — so a send that produced an opt-out request is not in the inventory at all. Signed Mariaelena Diaz, DRE #02034560, the same third-party agent as 27 Prague St.

Kept as a blocker for that second campaign alone. The question for Lawrence is no longer 'where are these two' but 'where do property one-off sends live, because one of them collected an opt-out and is not in the campaign list'.

DONE = the 3375 17th St send located and catalogued, the verified-500 question settled either way, and the reason a property send can exist outside the campaign list understood so it cannot recur.

Q1 ANSWERED, BUT NOT THIS QUESTION. Lawrence Oliveros replied: "the account was added late than the other metrixgenerate.com email." That explains when victoria@metrixgenerate.com was set up; it does not say where the 3375 17th St #311 campaign lives, so this stays open.

It does, however, suggest the likeliest explanation. If victoria@ was added later and under a SEPARATE INSTANTLY WORKSPACE, campaigns sent from it would not appear in the campaign list this audit was built from, however the status filter is set. That would account for a send existing outside the inventory without anything being broken.

NARROWED FOLLOW-UP for Lawrence or Lawrence, to replace the original question: which Instantly workspace is victoria@metrixgenerate.com in, and is there a second workspace holding the property one-off sends? Check the workspace switcher in Instantly before asking — if there is a second workspace, both the 3375 17th St send and 27 Prague St are probably in it, and the inventory is not missing so much as split in two.

DONE 22 Sep 2026 — THE INVENTORY IS NOW COMPLETE. Instantly AI settled every part of it:

ONE workspace: 'My Organization', id 8d8ff5b0-7e32-492c-a115-474351f15c24, owned by carlo@twinhomebuyer.com. My second-workspace theory was wrong.

SIX campaigns have ever existed, and that is all of them:
  Realtors July 2026        67d3a54b  Paused     created 9 Jul   4,867 sent  twinhomebuyer senders
  Oakland Realtor           54635e3e  Paused     created 25 Jul  1,760 sent  twinhomebuyer senders
  San Francisco County      c1979cb5  Paused     created 29 Jul    614 sent  twinhomebuyer senders
  Phase 1 – Peninsula       2484bb6e  Completed  created 31 Jul  2,424 sent  metrixgenerate senders
  27 Prague St              e7e18f27  Completed  created 15 Aug    156 sent  metrixgenerate senders
  3375 17th St #311         c05714e3  DELETED    sent 6-10 Aug   2,000+ sent metrixgenerate senders
(plus TEST CAMPAIGN REPLY, 4 sends, deleted today)

The 'PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500' that started this is not a campaign at all — it is the KPI bot's label for Phase 1 – Peninsula, whose step 5 sent 19 emails on 21 Sep.

Closing this, because the question 'what exists' is answered. What it uncovered is bigger than the gap it closed and is tracked separately: a campaign that sent 2,000+ emails has been deleted and its record destroyed.

FOLLOW-ON, small: make the KPI bot post the Instantly campaign name, or record the bot-label-to-campaign mapping in the SOP, so this cannot cost another day.

---

## Review SF County's 2 replies and the $1,000 opportunity

`Blocker` · owner **Jonathan** · status **Open**

San Francisco County Realtor took 2 replies in the last 4 weeks against 0 sends, while paused at 0% progress, and its 1 opportunity worth $1,000 is still open. DONE = both replies answered and the opportunity progressed or closed.

---

## Suppress existing contacts from cold lists

`Blocker` · owner **Cherry** · status **Blocked**

Stanley Lo — a counterparty on multiple closed transactions since 2021 — was cold-emailed as a stranger by Realtors July 2026. Nothing excluded him, which means nothing excludes any existing client, partner or past counterparty from any list.

This is a different failure from bounces or geography. A bounce costs deliverability; introducing yourself to someone you have closed four deals with costs the relationship, and it is invisible in every metric — 0% bounce, no complaint, no unsubscribe, just quiet damage.

Blocker because resuming any campaign repeats it, and the lists have never been checked against the CRM or against sent-mail history.

DONE = a suppression list built from existing CRM contacts and prior transaction counterparties, applied to every campaign before it resumes, and the verified-500 list checked against it.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Bulk-verify every list's email addresses before it sends

`High` · owner **Lawrence** · status **Blocked**

Lawrence Oliveros confirmed 22 Sep that list verification means checking whether a realtor has recently sold or listed a property. That check is sound and the numbers support it — 1.69% bounce on Peninsula against 4.06% and 4.72% on the unverified lists. What it cannot see is whether the mailbox is alive.

23 of Peninsula's 41 bounces are invalid recipients at compass.com, SMTP 5.1.1. Those are addresses that no longer exist, on realtors who are demonstrably active. Activity and deliverability are two different questions and only one is being asked.

THE ASK: run a pre-send email validity check on every list before it sends, on top of the existing activity check. Instantly has bulk verification built in, and the lists already exist, so this is a pass over data rather than new work. Priority order by damage: San Francisco County (4.72%, 614 sent), Realtors July 2026 (4.06%, 4,867 sent), then the rest.

Why it is worth doing before the caps ramp resumes: at 4–5% bounce rates providers begin suspending senders. Cleaning the lists lowers the rate on the volume already going out, and is the precondition for safely sending more.

DONE = every live list bulk-verified before its campaign resumes, and verification added to the documented sourcing rule as a standing step.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Sign off the 24h SLA and the reporting cadence

`High` · owner **Cherry** · status **Blocked**

Two of the 11 handoff tasks were closed on Jonathan's proposal, not on an agreement. They are written up and workable, but they commit other people, so they need a yes:

1. FIRST-TOUCH SLA — 24 hours to first touch on realtor leads, aligned with the realtor relationship program. Proposed, not agreed. Lawrence needs to confirm it is achievable with the current staffing.

2. REPORTING CADENCE — daily at 16:00 in Google Chat, copied to Cherry by email; weekly summary Fridays at 16:00 in the same places. The 16:00 daily slot matches what the 'Realtor Outreach KPI' bot already does, so the daily half is observed fact; the email copy and the Friday weekly are new and are the part being proposed.

Flagged rather than left implicit, so that nobody reads a ticked box as a commitment they never made.

DONE = Cherry confirms the cadence and Lawrence confirms the 24 hours, or either says what it should be instead.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Clean the Realtors July 2026 list

`High` · owner **Lawrence** · status **Blocked**

198 bounces on 4,867 sent = 4.06%, the highest absolute count in the account. DONE = the 198 suppressed and the remaining list run through verification before the campaign resumes.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Clean the San Francisco County Realtor list

`High` · owner **Lawrence** · status **Blocked**

29 bounces on 614 sent = 4.72%, the worst rate in the account and the closest to the 5% level at which providers suspend sending. Small volume, so this is list quality not volume. DONE = the 29 suppressed and the remainder verified.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Decide whether Green Banker is contacted at all

`High` · owner **Cherry** · status **Blocked**

Stanley Lo of Green Banker was a counterparty on multiple closed transactions and has died. Max Lo, same brokerage and same surname, is on a cold list — twice.

A sequence opening 'I'm Juan Diaz, founder of Twin Home Buyer' going to Max Lo is not a decision a lead list should be making. Whether Green Banker is approached at all, by whom, and in what terms, needs a person.

DONE = a decision recorded here, and the greenbanker.com records on every list brought in line with it.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Decide whether Realtors July 2026 resumes

`High` · owner **Cherry** · status **Blocked**

Paused at 11% sequence progress with 4,867 sent and 9 of the account's 18 lifetime opportunities — the best performer by a wide margin. The only note on it is 'no further instructions'. DONE = resume, retire or rework, decided and recorded.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Cherry. Route through Cherry, who directs the work.

---

## Extend the KPI bot to flag SLA breaches

`High` · owner **Lawrence** · status **Blocked**

Phase 3 requires a way for a stalled realtor lead to surface by itself. Instantly has no native SLA alert, but the 'Realtor Outreach KPI' bot already posts to Google Chat at 4pm with API access. Add two lines to that post: replies on realtor campaigns older than 24h with no response sent, and leads tagged Interested older than 24h with no CRM record. Reply Received timestamps are already in the Activity tab, so this is a query not a rebuild. Until it exists the check is manual and depends on someone remembering. DONE = the 4pm post names breaches by itself, and a manual sweep is no longer needed.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Remove open rate from the KPI formats — tracking is off

`High` · owner **Jonathan** · status **Done**

FOUND 22 Sep 2026 in Instantly AI's send records: every send to Stanley Lo and to both Max Lo addresses reports 'Opens: 0 recorded (open tracking disabled)'.

Open tracking being off is a GOOD decision and almost certainly deliberate — tracking pixels hurt deliverability and are increasingly stripped or pre-fetched, which makes open rates unreliable anyway. Nothing to fix there.

The problem is that the reporting we just agreed promises a number that cannot be produced. The daily KPI format in Phase 2 lists 'emails sent, open rate, reply rate, bounce rate, leads advanced'. Open rate will read 0% or blank every single day, and the first person to notice will either assume the reporting is broken or assume nobody opens our email. Both readings are wrong and both are damaging.

The same applies to any open-rate figure anywhere in this audit: if there is one, it is not measuring what it appears to.

DONE = open rate removed from the daily and weekly KPI formats, replaced by reply rate and bounce rate as the deliverability signals, and one line in the SOP saying open tracking is off on purpose, so nobody switches it on to 'fix' the reporting.

DONE 22 Sep 2026 — ALREADY HANDLED, checked rather than assumed. The agreed reporting formats in Phase 2 and Phase 4 do not carry open rate. The Phase 2 note says so explicitly: 'NOT open rate — open and click tracking are disabled account-wide. Keep tracking off and drop the metric.' The daily and weekly formats list Sent, Bounce %, Positive replies and Opportunities, with no open-rate line.

The only place open rate still appears is the original task wording copied from the brief, which the note overrides. Nothing to change.

Raised because Instantly AI's records showed 'open tracking disabled' on every send and I wanted to be sure the reporting we had just committed to did not promise a number that cannot exist. It does not.

---

## Cut the twinhomebuyer sending caps

`High` · owner **Lawrence** · status **Blocked**

RENAMED to stop this being misread: the fix is to bring twinhomebuyer DOWN, not metrixgenerate up.

UPDATED 22 Sep after deleting carlo@, juan@ and accounting@. The account now holds 550/day across 9 inboxes: 4 twinhomebuyer at 100/day (lawrence, rosanes, seth, bryan) = 400, and 5 metrixgenerate at 30/day = 150. So the primary business domain still carries 73% of capacity, down from 81%.

20–50/day per mailbox is the safe range for cold outreach, so the metrixgenerate inboxes at 30 are set correctly. The four remaining twinhomebuyer inboxes at 100/day are the outlier, and they sit on the domain carrying the company's real mail.

DO NOT raise metrixgenerate to 100. A mailbox cannot jump 30 to 100 — volume ramps, roughly +10/day per week while watching bounce and complaint rates. 'Pre-warmed' means warmup completed, not that an inbox can carry high volume. And capacity is not the bottleneck: nothing is sending, and the real constraint is list quality. More volume aimed at unverified, mistargeted lists only does damage faster.

DONE = the twinhomebuyer inboxes removed from cold campaigns or cut to a token cap, and metrixgenerate left at 30–50 with any increase ramped.

ANSWERED 22 Sep by Lawrence Oliveros, on Lawrence's behalf: "the goal was to escalate the level of email sending by adding 5 more each day and the end goal is the maximum is 100."

SO THIS IS NOT MISCONFIGURATION. The 30/day on metrixgenerate is a ramp in progress, not a throttle, and 100/day is the deliberate destination for every mailbox. My original 'the caps are inverted' reading was wrong and is withdrawn: the twinhomebuyer inboxes are not misconfigured, they are simply further along the same ramp. Credit where it is due — a staged ramp is the right mechanism.

TWO OBJECTIONS SURVIVE THE ANSWER, and they are about the destination rather than the method.

1. 100/day per mailbox is roughly double the range most cold-outreach practice holds to (20–50). At +5/day, 30 reaches 100 in a fortnight. Whether 100 is survivable depends entirely on what the mailbox is sending to, which leads to the second point.

2. CAPACITY IS NOT THE CONSTRAINT. Nothing is sending right now, so the ramp is not even advancing. The account produced 17 opportunities from 9,821 sends; 27 Prague St produced 3 of them from 156. Meanwhile Realtors July 2026 bounces at 4.06% and San Francisco County at 4.72%, both inside touching distance of the 5% level where providers start suspending. Ramping to 100/day aims more volume at the lists already generating those rates. The gain from fixing the lists is an order of magnitude; the gain from tripling capacity on the same lists is more bounces, sooner.

WHAT I AM ASKING FOR, narrowed: hold the ramp at 50/day until Realtors July and SF County are under 2%, then resume it. And keep the four twinhomebuyer inboxes out of cold campaigns whatever the cap — that part is unchanged and is the same reasoning Lawrence gave for deleting carlo@, juan@ and accounting@ in answer 2.

DONE = a decision on the 50/day hold and on whether twinhomebuyer inboxes carry cold volume at all.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Reconnect or retire seth@ and juan@

`High` · owner **Jonathan** · status **Done**

DONE 22 Sep 2026 — RETIRED. Decision taken by the creator of the Instantly setup together with the team: delete seth@ and juan@twinhomebuyer.com from Instantly rather than reconnect them. Both were in an error state, not sending, no warmup in a week, IMAP off on juan@, and carlo@ was at a 59% health score. Deleting them also unassigns them from Realtors July 2026 and San Francisco County Realtor, so neither campaign can resume on a broken sender.

accounting@twinhomebuyer.com was deleted in the same decision.

Consequence to keep in mind: the Google mailboxes themselves still exist — only the Instantly connections were removed. juan@'s unread replies are still there and are now invisible to Instantly entirely. Tracked separately, and closed as Won't do by the same decision.

CONFIRMED 22 Sep by Lawrence Oliveros, answering on Lawrence's behalf: "those accounts are removed due to caring on their email health those emails are crucial and must not have issues that causes their email to go to spam."

So the removal was deliberate and for exactly the right reason — these are business-critical mailboxes and were pulled out of cold sending to protect their deliverability. It was never an error state left unattended. Worth recording because it means the team already accepts the principle behind the open domain question: crucial twinhomebuyer.com mailboxes should not carry cold volume. That is the same argument for the four that remain — lawrence@, rosanes@, seth@ and bryan@ — still sending cold at 100/day each.

---

## Sweep every campaign list for the opt-outs

`High` · owner **Jonathan** · status **In progress**

The blocklist prevents sending, so this is hygiene for lists that have not sent — but on a list that HAS sent, a hit is evidence of a send, so capture the lead's activity timeline before deleting the row.

Search each campaign's Leads tab for: kurt, jason, leah, anagnostou, greenbanker.

Done so far:
  - Phase 1 – Peninsula Listing Agents — 'greenbanker' returns 3 leads (Stanley Lo, Max Lo twice). All three were emailed: 516 of 517 contacted. Tracked as its own blocker.
  - 'kurt' returns no leads on the list it was searched on.

CORRECTION TO AN EARLIER NOTE: this record previously filed the three greenbanker records under 27 Prague St. The search confirmed on screen was Phase 1 – Peninsula. 27 Prague St has NOT been searched for greenbanker and still needs to be.

Still to sweep: 27 Prague St, Realtors July 2026, Oakland Realtor, San Francisco County Realtor, PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500, and the 3375 17th St #311 send. Also still to run on Peninsula: kurt, jason, leah, anagnostou.

DONE = all five fragments searched on every campaign list, timelines captured wherever the list has already sent, and the rows removed.

---

## Verify the CRM sync once, end to end

`High` · owner **Lawrence** · status **Blocked**

Nobody has ever checked it. The daily checks assume every lead tagged Interested reaches the CRM. DONE = each Interested lead from a sample day traced to a CRM record, or the gap measured.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Verify the sending account list — 9 claimed, 11 listed

`High` · owner **Jonathan** · status **Open**

DISCREPANCY FOUND 22 Sep 2026. Instantly AI says '9 total' sending accounts and then lists eleven:

  twinhomebuyer.com (6): bryan@, carlo@, juan@, lawrence@, rosanes@, seth@
  metrixgenerate.com (5): ariana@, christopher@, isabella@, penelope@, victoria@

Two problems. The count and the list disagree. And seth@ and juan@ are still listed although both were deleted from Instantly earlier today — while accounting@, deleted in the same action, is correctly absent.

Most likely the AI is reading cached or historical data and the deletions did take. But 'most likely' is not good enough for a handoff document, because if seth@ and juan@ are still attached, Realtors July 2026 and San Francisco County Realtor can still resume on a broken sender, which was the whole reason for removing them.

DONE = the Accounts screen checked directly, the true list confirmed against this tracker's Accounts tab, and seth@ and juan@ verified as gone.

---

## Delete TEST CAMPAIGN REPLY

`Medium` · owner **Jonathan** · status **Done**

DONE 22 Sep 2026 — deleted. Instantly offers no Archive on the campaign row, only Delete, so the campaign and its history are gone permanently.

Why: it carried 13 replies against 4 sent, and those 13 sat inside the account's 47, so the reported reply rate read 0.48% when real outreach is about 0.35%. It also held 1 of the 18 opportunities. Left in place it would have distorted every KPI report to Cherry.

Taken knowing it was still in use: it showed 10 replies in the last 4 weeks with activity through 22 Sep, so someone had been testing reply detection with it. That test tool is gone; a fresh one can be made if needed.

Figures recorded before deletion, since the campaign itself no longer holds them: 4 sent, 0 bounces, 13 replies, 1 opportunity, created 3 Aug 2026, sender victoria@metrixgenerate.com.

FOLLOW-UP: re-check the account reply rate and opportunity count — they should now read about 34 replies on 9,821 sent (0.35%) and 17 opportunities.

---

## Confirm Mariaelena Diaz consented to the 27 Prague St sends

`Medium` · owner **Lawrence** · status **Blocked**

That campaign sends from metrixgenerate.com signed with her name, eXp Realty and DRE #02034560 — a domain she does not control. DONE = written confirmation on file.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Fix the sender and signature mismatch

`Medium` · owner **Lawrence** · status **Blocked**

Every step is signed Juan Diaz, but the three twinhomebuyer campaigns send from bryan@, carlo@, juan@, lawrence@, rosanes@ and seth@. Recipients get mail from one name signed by another, and replies land in whichever inbox sent them. This is the mechanical cause of the scattered, untriaged replies. DONE = the signature matches the sending inbox, or a single reply-to is set.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Pull the undocumented Step 8

`Medium` · owner **Lawrence** · status **Blocked**

The campaign index lists 8 steps for the three realtor campaigns; the export contains 7. DONE = Step 8's subject and body recorded in the Templates tab.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Remove accounting@ as a sending account

`Medium` · owner **Jonathan** · status **Done**

DONE 22 Sep 2026. accounting@twinhomebuyer.com deleted from Instantly. A role address on the primary business domain, in an error state, assigned to no campaigns — it was holding a sending licence for nothing and should never have been a sending account.

---

## Use the Email Security Gateway column before resuming a list

`Medium` · owner **Lawrence** · status **Blocked**

Peninsula Leads tab, read 22 Sep 2026: 517 leads, 516 contacted, 41 bounced, and the banner 'This campaign has run out of leads'. The campaign is finished, not paused — there is nothing left for it to send.

Three things this tab shows that no other screen does:

1. LEAD OWNER on the rows is 'Lawrence'. The lists were sourced and are owned by Lawrence — the provenance the handoff has been missing. Any question about where a lead came from, or on what basis it was contacted, goes to him, and whoever inherits this account inherits lists they did not build.

2. There is an 'Email Security Gateway' column, and at least one row reads Proofpoint. That is the signal behind the 6 'policy blocked' bounces: gateway-protected recipients are corporate mailboxes that filter cold mail whatever the sender reputation. The column lets those be predicted before sending instead of discovered as bounces.

3. 41 bounces here against the 35 recorded off the Last-4-weeks filter. 41 is the all-time figure and is the one to report.

DONE = the gateway column checked on each remaining list before it is resumed, and the heaviest gateway domains either excluded or accepted knowingly.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Differentiate the three identical campaigns

`Low` · owner **Lawrence** · status **Blocked**

Realtors July 2026, Oakland and SF County run the same 8-step copy to overlapping Bay Area realtor audiences from one domain. A filtering risk, and it makes it impossible to learn which message works. Only Step 1 has variants at all. DONE = distinct copy per campaign, or merged into one.

HANDED OVER 22 Sep 2026. Jonathan's part of this is finished — it is documented, evidenced and costed above, and nothing further here depends on him. Status set to Blocked rather than Done because the work itself has not been carried out, and this tracker is read by Cherry: a Done against an unfinished item would misrepresent the account's state to the person accountable for it. OWNER: Lawrence — he can speak to the lists and the sequences. Route through Cherry, who directs the work.

---

## Confirm the two Phase 1 walkthroughs were held

`Nice to have` · owner **Jonathan** · status **Won't do**

Both were ticked early, before any of this data existed, and the audit then found three dead inboxes, inverted caps and a paused best-performer — things a walkthrough would surface. DONE = confirmed as genuinely held, or re-held with these findings as the agenda.

CLOSED 22 Sep 2026 as superseded. The point of confirming the walkthroughs was to find out whether anything had been missed. The audit has now answered that directly and at far greater depth than a walkthrough would have: three dead inboxes, an empty blocklist, four unhonoured opt-outs, a deleted 2,000-email campaign, an existing client cold-emailed, one person emailed sixteen times across both domains. Re-holding a walkthrough to look for problems, after finding this many, would be ceremony.

Keeping it open would also inflate the blocker list with process hygiene while real items sit below it. Closed on that basis, not because the walkthroughs were confirmed — they were not.

---
