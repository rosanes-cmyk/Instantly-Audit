# Instantly Handoff Tracker — all user-facing copy

Every sentence a reader sees, with the key it lives under. The page itself is
`tracker.html`; this file is only the words.

**How to use this:** rewrite any block you want clearer, keep the `key` line
above it unchanged, and send it back. The keys are how each revision gets put
back in the right place. Leave the numbers and dates alone unless they are
wrong — they are read off the account and they are what the audit rests on.

**What to aim for:** a reader who has never used Instantly and is not technical.
Plain words, short sentences, no jargon that is not defined on the page.


## Page header and status tiles
**`header.eyebrow`**
> Outbound operations · handoff in progress
**`header.title`**
> Instantly Audit & Handoff
**`header.subtitle`**
> Owner Jonathan · reporting to Cherry · deadline end of day today · update posted at least hourly
**`tile.tileDone`**
> Complete — Nothing checked off yet
**`tile.tilePhase`**
> Current phase — Audit the current setup
**`tile.tileUpd`**
> Last update — First update due within the hour


## Tab names
**`TABS[0].label`**
> Phases
**`TABS[1].label`**
> System Map
**`TABS[2].label`**
> SOP
**`TABS[3].label`**
> Accounts
**`TABS[4].label`**
> Campaigns
**`TABS[5].label`**
> Dossiers
**`TABS[6].label`**
> Decisions
**`TABS[7].label`**
> Templates
**`TABS[8].label`**
> Updates
**`TABS[9].label`**
> Contacts


## Section headings and their one-line notes
**`section.phasesH.heading`**
> The Handoff, Phase by Phase
**`section.phasesH.note`**
> Check a task when it is genuinely done — not when it is scheduled. Notes are what Cherry reads if she opens this.
**`section.mapH.heading`**
> System Map — How Instantly Actually Works
**`section.mapH.note`**
> Fill in each stage with what is really happening today, not what was intended. The drawn version of this is in the SOP tab — the whole flow in one picture, plus the two sending domains side by side. This is the same thing in words, stage by stage.
**`section.sopH.heading`**
> How Instantly Works Here
**`section.sopH.note`**
> The standing operating procedure for Twin Realtor Reach, written for whoever runs this next — no technical background assumed. Every term is defined, and the last section says which parts of it are not yet true.
**`section.acctH.heading`**
> Sending Accounts
**`section.acctH.note`**
> Score each inbox on deliverability health. Worst scores sort to the top of their domain, so the inboxes dragging the setup down are the ones you read first.
**`section.campH.heading`**
> Campaigns
**`section.campH.note`**
> Score each campaign on how it is performing. Active campaigns come first, worst score at the top.
**`section.dosH.heading`**
> Campaign Dossiers
**`section.dosH.note`**
> One page per campaign: its status and numbers, the copy that actually went out, and the addresses it went to. The extraction Cherry asked for — and the answer to “what is this campaign, and who did it reach?” without opening Instantly.
**`section.fixH.heading`**
> Decisions for Cherry
**`section.fixH.note`**
> Three decisions, each with a recommendation. Nothing else needs Cherry's attention. The full audit record — everything found, with owners — is kept in FIXES-ARCHIVE.md and in the database as state/fixes_archive.
**`section.tplH.heading`**
> Email Templates
**`section.tplH.note`**
> What each campaign actually sends. Instantly stays the source of truth — this is the archive as pulled, so re-pull it if a sequence is edited.
**`section.logH.heading`**
> Update Log No update posted yet Post an update Connecting to the shared log… Post update No updates yet. The first one is due within the hour — say where the audit stands, even if the answer is "waiting on Lawrence". Who To Contact
**`section.logH.note`**
> The escalation path this SOP hands over. If sending breaks, this is the order to work down.


## Phases — the 11 tasks and their prompts
**`PHASES.p1.title`**
> Audit the Current Setup
**`PHASES.p1.target`**
> Target: first hour
**`PHASES.p2.title`**
> Define “Working Fine”
**`PHASES.p2.target`**
> Target: hour 2
**`PHASES.p3.title`**
> Realtor Lead SLA
**`PHASES.p3.target`**
> Target: hour 3
**`PHASES.p4.title`**
> Reporting Cadence to Cherry
**`PHASES.p4.target`**
> Target: hour 4, then ongoing
**`PHASES.p1t1.text`**
> Get a walkthrough from Lawrence on the Instantly configuration — campaigns, sequences, sending domains/inboxes, integrations/webhooks
**`PHASES.p1t1.note`**  _(the grey prompt inside the notes box)_
> When it happened, and what surprised you
**`PHASES.p1t2.text`**
> Get a live walkthrough (not just a description) from Lawrence and Seth of what they've actually been monitoring, and how often
**`PHASES.p1t2.note`**  _(the grey prompt inside the notes box)_
> What they check, where they check it, how often
**`PHASES.p1t3.text`**
> Write down current state: active campaigns, sending accounts, deliverability health, known gaps or complaints
**`PHASES.p1t3.note`**  _(the grey prompt inside the notes box)_
> Known gaps, complaints, anything unexplained
**`PHASES.p2t1.text`**
> List the daily checks Jonathan will run: sequences firing on schedule, no paused or errored campaigns, replies routed with none sitting unread, CRM sync accurate
**`PHASES.p2t1.note`**  _(the grey prompt inside the notes box)_
> Where each check happens — Instantly dashboard, inbox, CRM
**`PHASES.p2t2.text`**
> Set up daily and weekly KPI reporting: emails sent, open rate, reply rate, bounce rate, leads advanced to next stage — pulled the same way each day
**`PHASES.p2t2.note`**  _(the grey prompt inside the notes box)_
> Where the numbers come from and who pulls them
**`PHASES.p2t3.text`**
> Define “nothing left behind” in concrete terms — reply response time target, time-to-sequence for a new contact
**`PHASES.p2t3.note`**  _(the grey prompt inside the notes box)_
> Reply response target, and time-to-sequence for a new contact
**`PHASES.p3t1.text`**
> Set a first-touch turnaround target for realtor leads, aligned with the realtor relationship program
**`PHASES.p3t1.note`**  _(the grey prompt inside the notes box)_
> Who agreed to the target
**`PHASES.p3t2.text`**
> Build a way to flag any realtor lead stalled past the SLA so it doesn't sit silently
**`PHASES.p3t2.note`**  _(the grey prompt inside the notes box)_
> How a stalled lead surfaces — filter, tag, alert, daily sweep
**`PHASES.p4t1.text`**
> Confirm the daily KPI snapshot format and delivery time
**`PHASES.p4t1.note`**  _(the grey prompt inside the notes box)_
> Confirmed with Cherry on…
**`PHASES.p4t2.text`**
> Confirm the weekly summary format for realtor lead throughput and process gaps
**`PHASES.p4t2.note`**  _(the grey prompt inside the notes box)_
> What the weekly summary covers
**`PHASES.p4t3.text`**
> Write a short SOP: how Instantly is configured, what gets checked daily, who to contact if something breaks
**`PHASES.p4t3.note`**  _(the grey prompt inside the notes box)_
> Where the SOP lives


## System Map — the five stages
**`STAGES.s1.name`**
> Lead Source
**`STAGES.s1.prompt`**  _(placeholder text)_
> Where do leads enter? List pull, scrape, CSV upload, form, partner feed — and who loads them.
**`STAGES.s2.name`**
> Campaign / Sequence
**`STAGES.s2.prompt`**  _(placeholder text)_
> Which campaigns are live, how many steps, what the sending schedule and daily cap are.
**`STAGES.s3.name`**
> Send & Follow-up
**`STAGES.s3.prompt`**  _(placeholder text)_
> Sending domains and inboxes, warmup state, follow-up spacing, what stops a sequence.
**`STAGES.s4.name`**
> Reply Handling
**`STAGES.s4.prompt`**  _(placeholder text)_
> Where replies land, who reads them, how fast, how a positive reply is marked.
**`STAGES.s5.name`**
> CRM Handoff
**`STAGES.s5.prompt`**  _(placeholder text)_
> What pushes into the CRM, automatic or manual, which fields, and how a miss gets caught.


## SOP tab

### Glossary — 15 terms
**`SOP_GLOSSARY[0]`**  _(term: "Instantly.ai")_
> The software that actually sends the emails and collects the replies. Everything in this SOP happens inside it. app.instantly.ai
**`SOP_GLOSSARY[1]`**  _(term: "Sending account (inbox)")_
> One email address the system sends from, e.g. rosanes@twinhomebuyer.com. We have several so the volume is spread out instead of coming from one address.
**`SOP_GLOSSARY[2]`**  _(term: "Domain")_
> The part after the @. We use two: twinhomebuyer.com (the real company domain, which also carries contracts and DocuSign) and metrixgenerate.com (a separate domain kept for cold outreach so problems don't touch the real one).
**`SOP_GLOSSARY[3]`**  _(term: "Sequence")_
> The set of emails one contact receives, spaced over days. Nobody writes them one at a time — the sequence runs on its own.
**`SOP_GLOSSARY[4]`**  _(term: "Step")_
> One email inside a sequence. Our realtor sequence has 7 steps over 7 days.
**`SOP_GLOSSARY[5]`**  _(term: "Variant")_
> An alternative version of the same step. Instantly rotates between them so not every recipient gets identical wording.
**`SOP_GLOSSARY[6]`**  _(term: "Daily cap")_
> The most emails one inbox is allowed to send in a day. Going over it gets the address flagged as spam.
**`SOP_GLOSSARY[7]`**  _(term: "Warmup")_
> Instantly quietly sending small amounts of mail between its own inboxes to build a new address's reputation before real outreach. Warmup mail is NOT outreach and must never be counted as sent volume.
**`SOP_GLOSSARY[8]`**  _(term: "Bounce")_
> An email that could not be delivered — usually a dead address. Above roughly 5% bounces, email providers start suspending the sender.
**`SOP_GLOSSARY[9]`**  _(term: "Unibox")_
> The single screen where every reply lands, no matter which inbox it came to. Replies are worked here, not in scattered mailboxes. app.instantly.ai/app/crm
**`SOP_GLOSSARY[10]`**  _(term: "Lead")_
> One contact — a realtor we are emailing.
**`SOP_GLOSSARY[11]`**  _(term: "Lead list")_
> A group of leads, loaded together. Always load a list as a NAMED list, never straight into a campaign (see gap 2 below).
**`SOP_GLOSSARY[12]`**  _(term: "Blocklist / suppression")_
> Addresses the system must never email, whatever list they appear on. This is where opt-outs and existing clients go.
**`SOP_GLOSSARY[13]`**  _(term: "Opt-out")_
> Someone asking to stop receiving our email. By law we must honour it within 10 business days, permanently.
**`SOP_GLOSSARY[14]`**  _(term: "Open tracking")_
> An invisible pixel that reports when someone opens an email. Ours is switched OFF on purpose — it hurts deliverability and the numbers are unreliable. Do not turn it on, and do not report open rate.

### The seven steps
**`SOP_STEPS[0].title`**
> Build the list
**`SOP_STEPS[0].body`**
> Assemble the market's active listing agents into a working sheet. For each one capture: First Name, Last Name, Email, Brokerage, City, County.
> 
> Sources: MLSListings.com, brokerage sites, agent websites, Realtor.com, Zillow, Compass, LinkedIn.
> 
> Prioritise agents with RECENT listing activity in the target market. Those are the people bringing sellers to market, and they are the only ones worth the send.
**`SOP_STEPS[1].title`**
> Verify every lead
**`SOP_STEPS[1].body`**
> Never upload an unverified list — bad data burns the sender's reputation and it does not recover quickly.
> 
> For each agent confirm all five:
>   1. Active — the agent is currently working.
>   2. Listing-side — confirmed by recent listing activity, not buyer-side only.
>   3. Email — a real, deliverable address. This is a SEPARATE check from the two above; an active agent can still have a dead mailbox.
>   4. Verification source — where you confirmed it.
>   5. Verification date — when you checked.
> 
> Set Final Status to 'Ready for Instantly' only when all five pass. Anything unconfirmed is dropped or held. Nothing else moves forward.
**`SOP_STEPS[2].title`**
> Format the columns
**`SOP_STEPS[2].body`**
> Export to the Instantly-ready format, in this column order:
> 
> First Name · Last Name · Email · Brokerage · City · County · Active Status · Listing-Side Status · Verification Source · Verification Date · Final Status
> 
> First Name, Brokerage and City are the personalisation variables the sequence uses, so they must be clean and correctly cased. 'JOHN' or 'john' appears in the email exactly as typed.
> 
> Save as Instantly_Ready_[Market].csv
**`SOP_STEPS[3].title`**
> Upload and check
**`SOP_STEPS[3].body`**
> In Instantly: open or create the realtor-outreach campaign, upload the CSV, and map the columns to Instantly's fields.
> 
> Then, before launching, confirm four things:
>   - Instantly's duplicate and invalid-email flags are cleared.
>   - The sending accounts on the campaign are the approved ones and are warmed up.
>   - The sequence is the approved copy.
>   - The schedule and daily cap are right.
**`SOP_STEPS[4].title`**
> Launch and hold the volume
**`SOP_STEPS[4].body`**
> Launch at 30–50 emails/day across all sending accounts, and hold there until reply rate and deliverability are proven.
> 
> Sending runs SIX DAYS A WEEK — Monday to Saturday. Nothing goes out on Sunday. At 30–50/day that is roughly 180–300 emails a week, which is the number to size a list against.
> 
> Keep warmup enabled on every inbox. Let Instantly spread sends across inboxes and throttle each one — do not override its limits.
> 
> Scale only gradually, and only after the numbers justify it. More volume on a weak list produces bounces, not meetings.
**`SOP_STEPS[5].title`**
> Work the replies
**`SOP_STEPS[5].body`**
> Check the Unibox at least once a day. Speed is what turns a reply into a booked meeting.
> 
>   - Answer interested replies fast.
>   - Update each lead's status: interested, not interested, meeting booked.
>   - Book meetings promptly and hand off to the right person.
>   - Process opt-outs and bounces the same day. Opt-outs go on the blocklist immediately.
**`SOP_STEPS[6].title`**
> Report
**`SOP_STEPS[6].body`**
> Daily at 4pm: the Realtor Outreach KPI bot posts per-campaign lines into Google Chat by itself. Underneath it, add the one human summary line — account totals, opportunities and their value, inbox health, and any exception worth flagging. Copy it to Cherry by email, unchanged.
> 
> Weekly on Friday at 4pm: realtor leads in, first touch inside 24 hours, SLA breaches, sent, replies, bounce rate, opportunities and value, plus any process gap with a named owner.
> 
> Report emails sent, reply rate, bounce rate and meetings booked. Do NOT report open rate — see the glossary.

### Our actual setup
**`SOP_SETUP[0]`**  _(row: "Outreach operator")_
> Jonathan — rosanes@twinhomebuyer.com. Owns this system outright: the daily Unibox check, the realtor lead SLA, the 4pm report, and everything in the escalation table below. Lawrence is the reference on how it was wired, but the work sits here now.
**`SOP_SETUP[1]`**  _(row: "Workspace")_
> One only — 'My Organization', owned by carlo@twinhomebuyer.com. There is no second workspace.
**`SOP_SETUP[2]`**  _(row: "Sending accounts")_
> 9 active. twinhomebuyer.com: bryan@, lawrence@, rosanes@, seth@ (100/day each). metrixgenerate.com: ariana@ (100/day), christopher@, isabella@, penelope@, victoria@ (30/day each).
**`SOP_SETUP[3]`**  _(row: "Deleted accounts")_
> carlo@, juan@ and accounting@twinhomebuyer.com were removed on 22 Sep to protect those mailboxes' health. Do not re-add them to campaigns.
**`SOP_SETUP[4]`**  _(row: "Campaigns")_
> 5 live or completed: Realtors July 2026, Oakland Realtor, San Francisco County Realtor, Phase 1 – Peninsula Listing Agents, 27 Prague St. All paused or finished.
**`SOP_SETUP[5]`**  _(row: "Which domain sends what")_
> The three realtor campaigns send from twinhomebuyer.com. Peninsula and the property campaigns send from metrixgenerate.com. Whether that stays that way is one of Cherry's open decisions.
**`SOP_SETUP[6]`**  _(row: "Sequences")_
> The three realtor campaigns share one 7-step sequence (5 variants on step 1). Peninsula has its own 5-step sequence. 27 Prague St is a single email.
**`SOP_SETUP[7]`**  _(row: "Signature")_
> Every realtor email is signed Juan Diaz, CA GC Lic. #1066892 — regardless of which inbox sent it.
**`SOP_SETUP[8]`**  _(row: "Reporting")_
> Realtor Outreach KPI bot → Google Chat, 4pm daily, one line per campaign. Plus the human summary, copied to Cherry by email. Weekly on Fridays.
**`SOP_SETUP[9]`**  _(row: "Bot naming")_
> The bot posts its own labels, not Instantly's campaign names. 'PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500' is the bot's name for 'Phase 1 – Peninsula Listing Agents'. Same campaign.
**`SOP_SETUP[10]`**  _(row: "Sending days")_
> SIX days a week — Monday to Saturday. Nothing sends on Sunday. Worth one check against the campaign schedule: the KPI bot's posts show no Saturday activity either, so if Saturday is meant to be sending, confirm it is switched on.
**`SOP_SETUP[11]`**  _(row: "Actual send volume")_
> The KPI bot's Google Chat posts show Peninsula sending 100/day through mid-September — 100, 100, 100, 94, 64, 42, 30, 19 as it ran out of leads, about 549 emails over those eight days, every one delivered and none bounced, and no replies. So the 30–50/day in step 5 is the target for starting a NEW campaign, not a description of what this account has been doing.
**`SOP_SETUP[12]`**  _(row: "Open tracking")_
> OFF account-wide, on purpose. Leave it off.
**`SOP_SETUP[13]`**  _(row: "Lifetime volume")_
> ~11,800 emails sent since 9 July 2026. 17 opportunities worth $17,400. Overall bounce rate 2.9%.
**`SOP_SETUP[14]`**  _(row: "Unsubscribe footer")_
> As of 22 September the unsubscribe link is on all four live campaigns. The postal address is a separate element — see gap 3 below.

### The routine
**`SOP_ROUTINE[0]`**  _(group: "Every campaign")_
> - Build the market list of active listing agents.
> - Verify every lead on all five checks; set Final Status = Ready for Instantly.
> - Export to the Instantly-ready columns.
> - Upload, clear duplicates and invalids, map fields.
> - Confirm approved sending accounts, approved copy, schedule and cap.
> - Launch at 30–50/day.
**`SOP_ROUTINE[1]`**  _(group: "Every day")_
> - Check the Unibox. Answer interested replies fast.
> - Update lead statuses.
> - Process opt-outs and bounces — same day, no exceptions.
> - Check no campaign has paused or errored on its own.
> - Check no inbox has gone into an error state.
> - Post the 4pm summary under the bot's lines, and copy it to Cherry.
**`SOP_ROUTINE[2]`**  _(group: "Every week")_
> - Pull metrics: sent, reply rate, bounce rate, meetings booked.
> - Review deliverability — bounce and complaint rates per campaign.
> - Post the Friday 4pm weekly summary.
> - Name any process gap, with an owner. A gap with no owner does not get fixed.
**`SOP_ROUTINE[3]`**  _(group: "Every 90 days")_
> - Re-read this SOP against what the system actually does.
> - Re-verify the sending domains, inboxes and daily caps.
> - Re-confirm the approved sequence copy.

### Compliance
**`SOP_COMPLIANCE[0].title`**
> Say who we are, truthfully
**`SOP_COMPLIANCE[0].body`**
> Every email identifies Twin Home Buyer honestly, with a subject line that reflects what the email actually says. No deceptive sender names or headers.
**`SOP_COMPLIANCE[1].title`**
> Include a real postal address
**`SOP_COMPLIANCE[1].body`**
> Every commercial email needs a valid physical mailing address in it. Ours is 170 Glenn Way, Suite 5, San Carlos, CA 94070.
**`SOP_COMPLIANCE[2].title`**
> Include a working opt-out
**`SOP_COMPLIANCE[2].body`**
> Every email needs a clear way to unsubscribe, and the link must actually work — not just be present.
**`SOP_COMPLIANCE[3].title`**
> Honour opt-outs fast and forever
**`SOP_COMPLIANCE[3].body`**
> Within 10 business days, permanently. Add the address to Instantly's blocklist the same day you see the request. A reply asking to be removed counts as an opt-out even if they did not click anything.
**`SOP_COMPLIANCE[4].title`**
> Never email a bounce or an opt-out again
**`SOP_COMPLIANCE[4].body`**
> Both go on the blocklist. The blocklist applies across every campaign, which is why it is the safety net.
**`SOP_COMPLIANCE[5].title`**
> Keep the verification trail
**`SOP_COMPLIANCE[5].body`**
> The list stays to legitimate business contacts, and the record of how each was verified stays intact.
**`SOP_COMPLIANCE[6].title`**
> If someone objects, stop
**`SOP_COMPLIANCE[6].body`**
> Stop that thread and escalate to ops. Do not argue, and do not keep the sequence running.

### Escalation
**`SOP_ESCALATION[0]`**  _(situation: "Bounce rate climbing")_
> Pause the campaign. Clean and re-verify the list before sending again. Above 5% risks suspension.
**`SOP_ESCALATION[1]`**  _(situation: "Deliverability drop or spam flags")_
> Pause sending. Check warmup and domain health. Jonathan handles it — rosanes@twinhomebuyer.com.
**`SOP_ESCALATION[2]`**  _(situation: "A sending account or domain breaks")_
> Jonathan, as Instantly admin — rosanes@twinhomebuyer.com. Lawrence is the reference on how something was wired, not the person who fixes it.
**`SOP_ESCALATION[3]`**  _(situation: "A recipient complains, or a compliance question")_
> Stop the thread. Escalate to ops and ownership the same day.
**`SOP_ESCALATION[4]`**  _(situation: "Low reply rate across a full cycle")_
> Do not send more. Review targeting and copy with the campaign owner.
**`SOP_ESCALATION[5]`**  _(situation: "A campaign or list looks wrong or missing")_
> Do not delete anything. Escalate — deleting a campaign in Instantly destroys its send record and its leads permanently.

### The three gaps
**`SOP_GAPS[0].title`**
> There is no blocklist of existing clients yet
**`SOP_GAPS[0].body`**
> This SOP assumes the blocklist protects people we already do business with. It does not yet — there has never been one. Until it exists, a cold list can contain a current client, a past counterparty, or someone mid-transaction with us. Building it is the single highest-value fix outstanding: one CSV of every address the company has transacted with, uploaded once, applies to every campaign automatically.
**`SOP_GAPS[1].title`**
> Leads have been loaded straight into campaigns, not as named lists
**`SOP_GAPS[1].body`**
> Only one named lead list exists in the whole workspace. Every other campaign's leads sit inside that campaign alone. That means nothing can be de-duplicated across campaigns, a list cannot be cleaned once and re-used, and deleting a campaign deletes its leads for good. From here, load leads as a named list first — always.
**`SOP_GAPS[2].title`**
> The postal address still needs confirming in every footer
**`SOP_GAPS[2].body`**
> The unsubscribe link went onto all four live campaigns on 22 September, which closes the larger half of this. CAN-SPAM requires a valid physical mailing address as well, and that is a separate element in the footer. Open each campaign's sequence and confirm 170 Glenn Way, Suite 5, San Carlos, CA 94070 appears alongside the unsubscribe link — then this is fully closed. Legal has been asked to review the footer wording for the 7,241 emails already sent, which is history and cannot be changed now.


## The two diagrams
**`figure[0].caption`**
> The whole system, in one picture. The top row is outbound, the bottom row is everything coming back. Two things are worth reading closely. The blocklist is a gate, not a list — every single send is checked against it, which is why one upload of past clients protects every campaign at once, and why it being empty for eleven weeks let cold mail reach people we were already doing business with. And the named list is dashed because it has been skipped: leads were loaded straight into campaigns, so nothing could be de-duplicated across them and deleting a campaign deleted its leads. The loop closes at the bottom right: an opt-out or a bounce arriving as a reply goes straight onto that same blocklist, which is how one person asking to be removed is honoured on every campaign at once.
**`figure[1].caption`**
> The decision Cherry has to make, in one picture. The two worst bounce rates in the account — both close to the 5% level where providers start suspending senders — are on the left, on the domain that also carries our contracts and Cherry’s own mail. All three campaigns that went out with no unsubscribe link were on the left too. The domain built to absorb that risk is on the right, sending the clean campaigns and carrying nothing else. Swapping the daily caps would not change this: it is about which domain sends which campaign.
**`figure[4].aria-label`**  _(read aloud to anyone who cannot see the picture)_
> How a realtor goes from a sourced list to a booked meeting: build and verify the list, load it as a named list, assign it to a campaign, every send checked against the blocklist, out through nine inboxes on two domains, and every reply returning into one Unibox to be answered, tagged and reported to Cherry at 4pm.
**`figure[5].aria-label`**  _(read aloud to anyone who cannot see the picture)_
> The two sending domains side by side. twinhomebuyer.com runs four inboxes at 100 a day and sends the three realtor campaigns, including the two worst bounce rates in the account, while also carrying the company's contracts, DocuSign and Cherry's own correspondence. metrixgenerate.com runs five inboxes and sends the property campaigns at 1.69 and 1.28 percent bounce, and carries nothing else.


## Templates tab — what the copy shows
**`TPL_FLAGS[0].title`**  _(severity: note)_
> Unsubscribe link added to every campaign — 22 Sep 2026
**`TPL_FLAGS[0].body`**
> Realtors July 2026, Oakland Realtor and San Francisco County Realtor had no opt-out mechanism and no postal address across 7,241 emails already sent. The unsubscribe link is now in place on all three. That was the single largest compliance gap in this audit and it is closed going forward. Two things it does not reach: the 7,241 emails already sent cannot be retrofitted, and the postal address is a separate requirement — confirm 170 Glenn Way, Suite 5, San Carlos, CA 94070 sits in each footer alongside the link.
**`TPL_FLAGS[1].title`**  _(severity: note)_
> Peninsula Step 2 unsubscribe link fixed — 22 Sep 2026
**`TPL_FLAGS[1].body`**
> Step 2 carried an empty href, so recipients of that one step had no way to opt out even on the campaign that already had a compliant footer. Fixed in the same pass that added the link to the other three.
**`TPL_FLAGS[2].title`**  _(severity: warn)_
> Six inboxes send mail signed by one person
**`TPL_FLAGS[2].body`**
> Every step is signed Juan Diaz, but the three twinhomebuyer campaigns send from bryan@, carlo@, juan@, lawrence@, rosanes@ and seth@. A recipient gets a mail from one name signed by another, and any reply lands in whichever inbox sent it rather than with Juan — which is why replies are scattered and untriaged.
**`TPL_FLAGS[3].title`**  _(severity: warn)_
> Three campaigns run identical copy
**`TPL_FLAGS[3].body`**
> Realtors July 2026, Oakland and SF County share the same 7-step sequence with only subject-line differences, aimed at overlapping Bay Area realtor audiences from the same domain. Identical bodies at volume is a filtering risk, and it makes it impossible to learn which message works.
**`TPL_FLAGS[4].title`**  _(severity: warn)_
> Daily limits exceed live capacity
**`TPL_FLAGS[4].body`**
> Realtors July 2026 and Oakland are each set to 500/day, 1,000/day combined, against 400/day of live twinhomebuyer inbox capacity (4 working inboxes at 100). SF County adds another 150. The limits describe volume the account cannot actually send.
**`TPL_FLAGS[5].title`**  _(severity: warn)_
> The test campaign inflates the reply figures
**`TPL_FLAGS[5].body`**
> TEST CAMPAIGN REPLY has 13 replies tracked against 4 sent. Those 13 sit inside the account's 47 replies, so real outreach replies are nearer 34 — a reply rate around 0.35%, not 0.48%. Archive it.
**`TPL_FLAGS[6].title`**  _(severity: note)_
> There is no Step 8 — resolved
**`TPL_FLAGS[6].body`**
> The campaign index showed 8 steps for the three realtor campaigns while the export had 7. The campaign objects settle it: Realtors July, Oakland and SF County have 7 steps each, Peninsula has 5. The 8 was a display artifact and nothing is missing. One thing did fall out of checking: Oakland’s Step 1 carries a sixth variant that is blank — confirm it is inert before Oakland resumes.
**`TPL_FLAGS[7].title`**  _(severity: warn)_
> A third party's licence appears on a Twin Home Buyer domain
**`TPL_FLAGS[7].body`**
> 27 Prague St is sent from metrixgenerate.com but signed Mariaelena Diaz, eXp Realty, DRE #02034560. Confirm that agent has agreed to outreach being sent under their name and licence from a domain they do not control.
**`TPL_FLAGS[8].title`**  _(severity: note)_
> Only Step 1 is being tested
**`TPL_FLAGS[8].body`**
> Step 1 has five variants; steps 2 through 7 have one version each. Most of the sequence has never been tested.


## Dossiers tab

### Realtors July 2026
**`DOSSIERS.realtors_july.leadnote`**
> 1,713 leads, of which 159 were never contacted. No named lead list exists for this campaign — the leads sit inside it and nowhere else.
**`DOSSIERS.realtors_july.flags[0]`**  _(severity: crit)_
> No unsubscribe link until 22 Sep — this campaign is where Stanley Lo received three cold emails from rosanes@ on 20, 22 and 25 July, ten days before Cherry emailed him about the 2032 Lyon Avenue offer.
**`DOSSIERS.realtors_july.flags[1]`**  _(severity: warn)_
> Best performer in the account: 9 of the 17 opportunities, on 11% progress. Paused with no reason on record.
**`DOSSIERS.realtors_july.flags[2]`**  _(severity: warn)_
> Still lists the deleted carlo@ and juan@ as senders. Resuming without editing the sender pool will fail.

### Oakland Realtor Campaign
**`DOSSIERS.oakland.leadnote`**
> This is the ONLY campaign with a named lead list in the workspace: 'Oakland Realtor list', id b3952de8-3610-42ad-807c-44be8a09a1e2, uploaded 27 Jul 2026. Every other campaign's leads were loaded straight into the campaign.
**`DOSSIERS.oakland.flags[0]`**  _(severity: ok)_
> Cleanest list in the account at 0.91%. The reply path demonstrably worked here: timjgullicksen@gmail.com replied to lawrence@, was tagged Interested — and then the campaign was paused.
**`DOSSIERS.oakland.flags[1]`**  _(severity: warn)_
> Step 1 carries a sixth variant that is blank. Confirm it is inert before this resumes, or it can send an empty email.
**`DOSSIERS.oakland.flags[2]`**  _(severity: warn)_
> Still lists the deleted carlo@ and juan@ as senders.

### San Francisco County Realtor
**`DOSSIERS.sf_county.leadnote`**
> Lead count not on record. No named list — leads are inside the campaign only.
**`DOSSIERS.sf_county.flags[0]`**  _(severity: crit)_
> Worst bounce rate in the account, on the smallest volume — which points at a dirty list rather than too much volume. 4.72% is inside touching distance of the 5% level where providers suspend senders.
**`DOSSIERS.sf_county.flags[1]`**  _(severity: crit)_
> STILL TAKING REPLIES WHILE PAUSED. Two replies arrived in the last four weeks against zero sends, and a $1,000 opportunity is still open. Nobody is watching a campaign that reads 0%.
**`DOSSIERS.sf_county.flags[2]`**  _(severity: warn)_
> Still lists the deleted carlo@ and juan@ as senders.

### Phase 1 – Peninsula Listing Agents
**`DOSSIERS.peninsula.leadnote`**
> 517 leads, 516 contacted. The rows carry name and email only — job title, company, location, website and LinkedIn are all empty, so nothing in the list itself establishes these are Peninsula listing agents.
**`DOSSIERS.peninsula.flags[0]`**  _(severity: ok)_
> Footer already correct — San Carlos postal address plus a working unsubscribe link. This is the footer the other three were copied from on 22 Sep.
**`DOSSIERS.peninsula.flags[1]`**  _(severity: warn)_
> The KPI bot calls this campaign 'PHASE 1 — SAN MATEO/PENINSULA VERIFIED 500'. Same campaign, different label. That mismatch cost most of a day.
**`DOSSIERS.peninsula.flags[2]`**  _(severity: warn)_
> 23 of the 41 bounces are invalid recipients at compass.com (SMTP 5.1.1) — dead mailboxes on realtors who are demonstrably active. Activity verification cannot see a dead mailbox.
**`DOSSIERS.peninsula.flags[3]`**  _(severity: crit)_
> Worst conversion in the account: 1 opportunity per 1,212 sent. Max Lo was emailed here AND on Realtors July, from two domains.
**`DOSSIERS.peninsula.copy.note`**
> Peninsula runs five steps: steps 1 to 4 of the shared sequence, then the shared step 7 as its fifth and final email. Confirmed against the send records for both Max Lo addresses, 1 to 7 September.

### 3375 17th St #311, San Francisco
**`DOSSIERS.st3375.leadnote`**
> UNRECOVERABLE. Over 2,000 SF-area agents were emailed and there is no list left. The only addresses still retrievable are those who replied, from the Unibox.
**`DOSSIERS.st3375.flags[0]`**  _(severity: crit)_
> THE RECORD IS GONE. Over 2,000 emails were sent in five days and the campaign object has been hard-deleted. Instantly does not log who deleted a campaign or why, so only a person can answer that — get it in writing.
**`DOSSIERS.st3375.flags[1]`**  _(severity: crit)_
> Its leads are unrecoverable. They were loaded straight into the campaign and existed nowhere else, so deleting the campaign deleted them.
**`DOSSIERS.st3375.flags[2]`**  _(severity: crit)_
> This is the send Leah McKern replied to on 7 Aug, 17:56 UTC, asking to be removed. The one campaign whose record was destroyed is a campaign with a known unhonoured opt-out against it.
**`DOSSIERS.st3375.flags[3]`**  _(severity: warn)_
> Two other replies survive in the Unibox: ROB EDWARDS, never read, and Cindy Manning (out of office). Export them before they go too.
**`DOSSIERS.st3375.flags[4]`**  _(severity: warn)_
> Roughly 400 emails a day across five mailboxes, about 80 each — well above the 30/day those accounts now run at. Four of the five were throttled from 100 down to 30 on 8 Aug at 23:15 UTC, two days into this send.
**`DOSSIERS.st3375.copy.note`**
> Not on record. Subject line was '3375 17th St #311 – Available from Owner/Investor'. The body was never archived and the campaign that held it is gone. The only surviving copy is inside the Unibox threads of the people who replied — which is why exporting them matters today rather than next week.

### 27 Prague St, San Mateo, CA 94401
**`DOSSIERS.prague.leadnote`**
> Roughly 156 leads — one send each. No named list; the leads are inside the campaign. This is the list worth extracting first, because it is small and it is the only one whose targeting demonstrably worked.
**`DOSSIERS.prague.flags[0]`**  _(severity: ok)_
> THE BEST PERFORMER IN THE ACCOUNT, by a wide margin. 3 opportunities from 156 emails is 1 per 52, against 1 per 541 on Realtors July and 1 per 1,212 on Peninsula — between ten and twenty-three times better. One property, one short email, a named audience.
**`DOSSIERS.prague.flags[1]`**  _(severity: warn)_
> And the one we are least sure we were entitled to send. It is signed by a third-party agent, Mariaelena Diaz of eXp Realty, DRE #02034560, and sent from a domain she does not control. Whether she agreed to that is unconfirmed.
**`DOSSIERS.prague.flags[2]`**  _(severity: ok)_
> Footer correct — unsubscribe link present.
**`DOSSIERS.prague.copy.note`**
> One email, sent once. This is the full copy as archived on 21 Sep.
**`MISMATCH_NOTE`**  _(shown on the three realtor campaigns instead of their copy)_
> WHAT WE HOLD DOES NOT MATCH WHAT WENT OUT. The Templates tab archives a 7-step Juan Diaz sequence for these three campaigns, and Instantly confirms all three run identical copy. But the send records show different subject lines in use: Stanley Lo and Max Lo received '<first name> — help with off-market situations' and '<first name> — backup plan for hard-to-move properties' at step 1 (internal variant 0_0_4), then 'seller who can't list?' and 'Re: seller who can't list?' at steps 2 and 3. None of those three subjects appears in the archive, so the archive holds some variants and not the ones actually sending. TO CLOSE THIS: open the campaign's Editor, expand every step and every variant, and paste the copy below. The archive is incomplete until that is done, and a handoff cannot claim to include what these campaigns say.


## Empty states, banners and hints
**`empty.acctEmpty`**
> No sending accounts recorded yet. Add each inbox Instantly sends from — every one gets a status, a daily cap and room for its own report.
**`empty.campEmpty`**
> No campaigns recorded yet. Add each one and mark it active or not — a paused campaign nobody knows about is exactly the gap this audit is for.
**`empty.fixEmpty`**
> No fixes recorded yet.
**`empty.logEmpty`**
> No updates yet. The first one is due within the hour — say where the audit stands, even if the answer is "waiting on Lawrence".
**`banner.readonly`**
> You can read everything here, but ticking a task or posting an update needs edit access — ask Jonathan to share it as “can edit”.
**`footer.note`**
> Deliverability thresholds shown are the standard limits cold-email sending is judged against: bounce under 2%, spam complaints under 0.1%.
