# Instantly Audit — every claim, for fact-checking

> **CHECKED 22 Sep 2026 against the live workspace. 76 of 77 confirmed, 1 partly.**
> Three things came back that changed the tracker:
> **4.6 PARTLY** — Instantly keeps no history of what a setting used to be, so "cut from 100 to 30" is an
> inference. The send logs put the old cap at 80 or above; the exact number cannot be read back.
> **5.7 CONFIRMED BUT EXPLAINED** — our archive is the live copy. The wording was rewritten in the editor
> after 25 July, so anyone emailed before that got a different version which exists only in the send logs.
> That was not a gap in our records; it was an undocumented edit.
> **New detail** — Rob Edwards replied from rob.edwards.sf@gmail.com on 7 Aug at 18:56:29 asking who we
> were, and it is still unread. Leah McKern's reply was "I moved to Texas about a decade ago. Please remove
> me from your distribution list. Thx" at 18:04:23, eight minutes after we emailed her. The four people who
> asked to be removed are Leah McKern, Kurt Byer, Jason Born and John Anagnostou.
**Workspace:** My Organization · **Audit date:** 22 September 2026 · **Auditor:** Jonathan

---

## How to use this

Paste this into Instantly AI and ask it to check each numbered claim against the account.

For every claim, one of four answers:

- **CONFIRMED** — matches the account.
- **WRONG** — and the correct value is X.
- **CANNOT CHECK** — the data does not exist or is not reachable.
- **PARTLY** — and here is what is off.

**Claims are tagged so you know what kind of thing you are checking:**

| Tag | Meaning |
|---|---|
| `[READ]` | Read straight out of Instantly. Should be checkable exactly. |
| `[MATH]` | Worked out from Instantly's numbers. Check the arithmetic and the inputs. |
| `[JUDGEMENT]` | My reading of what the data means. Not a fact — argue with it if you disagree. |
| `[PERSON]` | Only a human can answer. Do not guess; say CANNOT CHECK. |

**Please flag anything I have stated more confidently than the data supports.** That is more useful to me than a list of confirmations.

---

## 1 — The account

**1.1** `[READ]` There is exactly ONE workspace: *My Organization*, id `8d8ff5b0-7e32-492c-a115-474351f15c24`, owned by carlo@twinhomebuyer.com. No second workspace exists.

**1.2** `[READ]` There are **9** connected sending accounts, all showing Active with a warmup score of 100.

**1.3** `[READ]` twinhomebuyer.com: `bryan@`, `lawrence@`, `rosanes@`, `seth@` — daily cap **100 each**.

**1.4** `[READ]` metrixgenerate.com: `ariana@` at **100**; `christopher@`, `isabella@`, `penelope@`, `victoria@` at **30 each**.

**1.5** `[MATH]` Total daily capacity is **620** (400 + 220).

**1.6** `[READ]` `accounting@`, `carlo@` and `juan@twinhomebuyer.com` were deleted on 22 Sep 2026 and now return *account not found*.

**1.7** `[READ]` Despite that, `carlo@` and `juan@` are **still listed in the sender lists** of Realtors July 2026, Oakland Realtor Campaign and San Francisco County Realtor. Resuming any of those three without editing the sender pool would fail.

**1.8** `[READ]` **Open tracking is off** across every campaign. Every day of every analytics export shows 0 opens.

**1.9** `[READ]` **Click tracking is also off.** Every day of every export shows 0 clicks.

**1.10** `[READ]` There is **no CRM connection** — no active webhooks, no sync to any outside system. All 20 opportunities exist only as lead-status flags inside Instantly.

**1.11** `[READ]` Only **one named lead list** exists in the workspace: *Oakland Realtor list*, id `b3952de8-3610-42ad-807c-44be8a09a1e2`, uploaded 27 Jul 2026. Every other campaign's leads were loaded straight into the campaign.

**1.12** `[READ]` The blocklist was **completely empty** before 22 Sep 2026 — no entry had ever been added. Five addresses were added that day.

---

## 2 — Lifetime totals

**2.1** `[MATH]` **11,821 emails sent** since 9 Jul 2026 — 9,821 across the five listed campaigns plus about 2,000 from the deleted campaign `c05714e3` (internally a test run, but the sends were real).

**2.2** `[READ]` **324 bounces**, which is **2.74%** of 11,821.

**2.3** `[READ]` **81 replies** from **57** unique people.

**2.4** `[READ]` **20 opportunities** worth **$19,400** in total.

**2.5** `[MATH]` Of those, **3 opportunities worth $3,000** belong to the deleted campaign and cannot be traced to specific leads.

**2.6** `[MATH]` **5,378 leads contacted** across all six campaigns.

**2.7** `[MATH]` About **1,994 leads are loaded into campaigns and have never been emailed** — 1,184 on San Francisco County, 650 on Oakland, 159 on Realtors July, 1 on Peninsula.

**2.8** `[MATH]` The account-level total previously read **9,825**, which is exactly the five listed campaigns (9,821) plus the four sends of TEST CAMPAIGN REPLY. **Claim: a deleted campaign drops out of account-level reporting entirely, which is why those ~2,000 sends were missing.** Please confirm that is how Instantly behaves.

---

## 3 — The six campaigns

For each: please confirm **sent, leads loaded, leads contacted, bounces, bounce %, reply %, opportunities, value, number of steps, and sending domain.**

**3.1** `[READ]` **Realtors July 2026** — `67d3a54b-e374-4503-ae65-77c9eef028fc` · Paused · created 9 Jul 2026 15:29 UTC · twinhomebuyer.com · 4,867 sent · 1,713 loaded · 1,554 contacted · 198 bounces (4.07%) · 1.29% reply · 9 opportunities ($9,000) · 7 steps, 5 variants on step 1.

**3.2** `[READ]` **Oakland Realtor Campaign** — `54635e3e-4652-49bc-bab1-b923c007cd31` · Paused at 44% · created 25 Jul 2026 21:58 UTC · twinhomebuyer.com · 1,760 sent · 1,598 loaded · 948 contacted · 16 bounces (0.91%) · 0.32% reply · 2 opportunities ($2,000) · 7 steps, **6 variants on step 1, one of which is blank**.

**3.3** `[READ]` **San Francisco County Realtor** — `c1979cb5-7009-47c6-8fdb-6ddc8cd81790` · Paused at 0% · created 29 Jul 2026 21:01 UTC · twinhomebuyer.com · 614 sent · 1,387 loaded · 203 contacted · 29 bounces (4.72%) · 0.49% reply · 1 opportunity ($1,000, still open) · 7 steps.

**3.4** `[READ]` **Phase 1 – Peninsula Listing Agents** — `2484bb6e-1c62-41fe-8be4-414a5ec058fc` · Completed · created 31 Jul 2026 23:09 UTC · metrixgenerate.com · 2,424 sent · 517 loaded · 516 contacted · 41 bounces (1.69%) · 1.16% reply · 2 opportunities ($1,400) · **5 steps**.

**3.5** `[READ]` **27 Prague St, San Mateo, CA 94401** — `e7e18f27-7411-4ff5-b770-91a5695df4c8` · Completed · created 15 Aug 2026 20:31 UTC · metrixgenerate.com · 156 sent · 156 leads · 2 bounces (1.28%) · 2.56% reply · 3 opportunities ($3,000) · 1 step.

**3.6** `[READ]` **3375 17th St #311, San Francisco** — `c05714e3-35db-4223-8873-c65639a33173` · **DELETED**, returns 404 · sent 6 Aug 2026 21:26 UTC to 10 Aug 2026 18:05 UTC · metrixgenerate.com, all five addresses · ~2,000 sent · ~38 bounces (~1.9%) · ~1.15% reply · 3 opportunities ($3,000) · 1 step, signed Mariaelena Diaz. **Internally confirmed as a test run** (deleted deliberately, verified with Seth and Lawrence) — please still confirm the send figures above, since the emails reached real recipients either way.

**3.7** `[READ]` **TEST CAMPAIGN REPLY** existed with 4 sends, 0 bounces, 13 replies, 1 opportunity, created 3 Aug 2026, sender victoria@metrixgenerate.com. Deleted 22 Sep 2026.

**3.8** `[READ]` **There is no campaign named "PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500."** That is the KPI bot's label for Phase 1 – Peninsula Listing Agents.

**3.9** `[MATH]` Reply rate throughout is calculated as **unique repliers ÷ leads contacted**, not ÷ emails sent. Please confirm that matches how Instantly reports it.

---

## 4 — Dates and the timeline

**4.1** `[READ]` **Realtors July 2026, Oakland Realtor and San Francisco County Realtor all sent their last email on 3 August 2026** — the same day.

**4.2** `[READ]` Realtors July 2026 was manually paused on **3 Aug 2026 at 17:28 UTC**, with no reason recorded.

**4.3** `[READ]` Realtors July's busiest day was **514 emails**, and it went from 30/day to over 500/day within three days (30, 30, 30, 30, 10, 216, 44, 438, 508…).

**4.4** `[READ]` Peninsula ramped gradually: 25, 30, 35, 40, 45, 50, 60, 70, 80, 100 over about a month, then tapered 94, 64, 42, 30, 19 as it ran out of leads.

**4.5** `[READ]` Peninsula's final send was **19 emails on 21 Sep 2026, on step 5** — subject *"When You Just Need a Straight Answer."*

**4.6** `[READ]` **On 8 Aug 2026 at 23:15 UTC, four of the five metrixgenerate accounts had their daily caps changed to 30.** `ariana@` was left at 100. Please confirm what they were set to immediately before that change.

**4.7** `[READ]` San Francisco County's last send was 3 Aug 2026; a reply arrived **10 Sep 2026 — 38 days later**.

**4.8** `[READ]` Realtors July's last send was 3 Aug 2026; a reply arrived **17 Aug 2026**.

---

## 5 — The emails themselves

**5.1** `[READ]` Realtors July, Oakland and San Francisco County have **7 steps each**. Peninsula has **5**. 27 Prague St has **1**. There is no step 8 anywhere.

**5.2** `[READ]` Peninsula's five steps are the shared sequence's steps **1, 2, 3, 4 and 7** — not steps 1 to 5.

**5.3** `[READ]` All three realtor campaigns' copy is signed **Juan Diaz, CA GC Lic. #1066892**, while sending from six different twinhomebuyer.com addresses.

**5.4** `[READ]` 27 Prague St and 3375 17th St are signed **Mariaelena Diaz, eXp Realty, DRE #02034560**.

**5.5** `[READ]` Peninsula's footer carries a postal address (170 Glenn Way, Suite 5, San Carlos, CA 94070) and an unsubscribe link. The other three carried **neither**, across **7,241 emails**, until 22 Sep 2026.

**5.6** `[READ]` Peninsula's **step 2 had an empty unsubscribe href** — the link was present but went nowhere.

**5.7** `[READ]` **IMPORTANT, please check this carefully.** Our archived copy of the realtor sequence does not match what actually sent. The archive holds step-1 variants with subjects like *"When the deal falls apart late."* But the send records show Stanley Lo and Max Lo receiving **"{first name} — help with off-market situations"** and **"{first name} — backup plan for hard-to-move properties"** at step 1, then **"seller who can't list?"** and **"Re: seller who can't list?"** at steps 2 and 3. Those three subjects appear nowhere in our archive. **Which set is actually live on those campaigns?**

---

## 6 — Specific people

**6.1** `[READ]` **Stanley Lo** (stanleylo@greenbanker.com) was sent **3 emails from rosanes@twinhomebuyer.com** on Realtors July 2026: 20 Jul 23:47, 22 Jul 20:10, 25 Jul 19:32 UTC. No opens (tracking off), no reply.

**6.2** `[READ]` A further manual email went to him on **4 Aug 2026 from cherry@twinhomebuyer.com**, about an offer on 2032 Lyon Avenue, Belmont.

**6.3** `[READ]` He also appears on Peninsula's lead list, but Instantly records **no Peninsula sends to him** — which would make him the single uncontacted lead of Peninsula's 517. Please confirm.

**6.4** `[READ]` **Max Lo received 16 emails in total.** `maxlo@greenbanker.com`: 3 from rosanes@ (Realtors July, 20/22/25 Jul) + 5 from ariana@ (Peninsula, 1/2/3/4/7 Sep). `maxlo.greenbanker@gmail.com`: 3 from rosanes@ (21/22/25 Jul) + 5 from victoria@ (1/2/3/4/7 Sep).

**6.5** `[READ]` **leah@leahmckern.com** was emailed on **7 Aug 2026 at 17:56:35 UTC by victoria@metrixgenerate.com** on the deleted 3375 campaign, and replied asking to be removed. Her request was **never recorded as an unsubscribe**.

**6.6** `[READ]` **cindy.manning@compass.com** was emailed 6 Aug 2026 at 21:26:39 UTC on the same campaign, and replied out of office.

**6.7** `[READ]` **Rob Edwards** also replied to the 3375 campaign and the reply has never been read. Please give his address and the date.

**6.8** `[READ]` **57 recipients of the deleted campaign have been recovered** from the message logs. Please confirm the true total number of recipients for `c05714e3`, and whether the full list can still be pulled.

**6.9** `[READ]` **23 of Peninsula's 41 bounces** are invalid-recipient failures at compass.com.

**6.10** `[READ]` Peninsula's lead rows show the lead owner as **"Carlo James Ballerdo"**, and the job title, company, location, website and LinkedIn fields are **empty** on those rows.

**6.11** `[READ]` **timjgullicksen@gmail.com** replied to lawrence@twinhomebuyer.com on Oakland Realtor and was tagged Interested. The campaign was then paused.

**6.12** `[READ]` Four people asked to be removed by replying, and **none was recorded as an unsubscribe**. The oldest request was **41 business days** overdue when found.

---

## 7 — My analysis, not facts. Argue with these.

**7.1** `[JUDGEMENT]` **Sending volume does not explain the bounce rates.** Per address on each campaign's busiest day: San Francisco County 26/day → 4.72% bounce; Peninsula 20/day → 1.69%; 27 Prague 6/day → 1.28%; Oakland 47/day → 0.91%; Realtors July 86/day → 4.07%. The campaign sending least per address has the worst rate. **Conclusion: list quality drives bounces, not throughput.** Do you agree?

**7.2** `[JUDGEMENT]` 27 Prague St is the best-performing campaign: **1 opportunity per 52 emails**, against 1 per 541 (Realtors July) and 1 per 1,212 (Peninsula).

**7.3** `[JUDGEMENT]` Because leads were loaded into campaigns rather than saved lists, nothing could be de-duplicated across campaigns — which is how Max Lo received 16 emails.

**7.4** `[JUDGEMENT]` Peninsula's list was verified for *realtor activity* (has this person recently sold or listed), which does not check whether the mailbox is alive — hence the 23 dead compass.com addresses.

**7.5** `[JUDGEMENT]` The three realtor campaigns running identical copy to overlapping Bay Area lists from one domain is a spam-filtering risk.

**7.6** `[JUDGEMENT]` Realtors July and Oakland are each set to 500/day, 1,000 combined, against 400/day of working twinhomebuyer capacity. The settings describe volume the account cannot send.

---

## 8 — Corrections I already made. Did I get them right?

**8.1** I first said all 35 bounces belonged to Peninsula. That was read off a *Last 4 weeks* filter. All-time, Peninsula has **41**.

**8.2** I said the caps were "inverted." They are a deliberate ramp toward 100/day. **Withdrawn.**

**8.3** I then asked for the ramp to be held at 50/day. Claim 7.1 disproves that. **Also withdrawn.**

**8.4** I said the "VERIFIED 500" was a missing campaign. It is the KPI bot's label for Peninsula. **Withdrawn.**

**8.5** I said the verified list's 0 bounces on 19 sends proved pre-send *email* verification works. The verification was about realtor activity, not addresses. **Withdrawn** — the real evidence is 1.69% vs 4.07%/4.72%.

**8.6** I said the deleted campaign's contacts were gone for good. **Too strong** — the message logs hold them, and the original upload spreadsheet exists offline.

**8.7** I said Stanley Lo was emailed by Peninsula. He was emailed by **Realtors July 2026**, from rosanes@. **Corrected.**

**8.8** I reported 17 opportunities and $17,400. The real figures are **20 and $19,400** — the deleted campaign held 3 worth $3,000. **Corrected.**

**8.9** I recorded Oakland at 948 leads and SF County at 203. Those were *contacted* counts. Real list sizes are **1,598** and **1,387**. **Corrected.**

---

## 9 — Only a person can answer these. Please do not guess.

**9.1** ~~`[PERSON]` Who deleted campaign `c05714e3`, when, and why?~~ **WITHDRAWN — answered internally.** Jonathan deleted it deliberately, and Seth and Lawrence confirmed it was a test send. No longer a question for anyone outside.

**9.2** `[PERSON]` Why did Realtors July, Oakland and San Francisco County all stop sending on 3 August 2026?

**9.3** `[PERSON]` Why were four metrixgenerate caps cut to 30 on 8 August?

**9.4** `[PERSON]` Has any other campaign, lead list or sending account been deleted?

**9.5** `[PERSON]` Did Mariaelena Diaz agree to outreach going out under her name and DRE licence from an address she does not control?

**9.6** `[PERSON]` Where are the original upload spreadsheets for each campaign's leads?

---

## Last thing

If any number here is right but my *description* of it is misleading, say so. An accurate figure with a wrong story attached is worse than a wrong figure, because nobody checks it twice.
