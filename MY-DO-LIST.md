# Jonathan's do-list — Instantly

Just the clicks. No findings, no reading.

## Today

**1. Strip the dead senders — 10 minutes, do this first**
Open each of these three campaigns → Sequences/Settings → sender pool → remove `seth@twinhomebuyer.com` and `juan@twinhomebuyer.com`:
- Realtors July 2026
- Oakland Realtor Campaign
- San Francisco County Realtor

They'll fail on resume otherwise.

**1b. Upload the blocklist — 5 minutes, the file is already made**
Settings → Blocklist → paste in the contents of `data/blocklist-upload.txt`. That's 48 addresses that have already bounced on us. Re-emailing a known bad address is the quickest way to push the bounce rate back up.

**1c. Switch off Oakland's blank email — 2 minutes**
Oakland Realtor Campaign → Sequences → email 1. It has six versions and the sixth is empty. Delete it or turn it off. Restart Oakland with it live and it can send blank emails.

**2. Ask Seth and Lawrence for the original spreadsheets** — the single highest-value message you will send
Every campaign's leads were uploaded from an offline CSV that Instantly never kept. Those files still exist on somebody's Drive or laptop, with phone numbers and brokerages Instantly never stored. One message recovers all of them:

> *"Can you send me the source CSVs you uploaded for each campaign?*
>
> * *Realtors July — 1,713 leads loaded, 1,554 contacted*
> * *Oakland Realtor — 1,598 loaded, 948 contacted*
> * *SF County Realtor — 1,387 loaded, 203 contacted*
> * *Phase 1 – Peninsula — 517 leads*
> * *27 Prague St — 156 leads*
> * *3375 17th St #311 blast, 6 August — ~2,000 leads*
>
> *I'm rebuilding them as permanent named lead lists inside Instantly, so a paused, completed or deleted campaign can never take a whole list down with it again, and so we can run clean de-duplication across campaigns from here on."*

Giving both numbers matters: it tells them to send the **original full CSV**, not an export of only the leads that already received an email.

**2b. While you wait, pull what the logs hold.** Unibox → clear the status filter (it's showing only negative replies) → search `3375 17th St #311` → switch the folder from **Inbox to Sent** → select → export CSV. No developer needed. 57 addresses are already recovered and saved in the Dossiers tab.

**3. Delete the greenbanker leads**
Peninsula → Leads → search `greenbanker` → delete all 3 (Stanley Lo, Max Lo ×2).
Then Realtors July 2026 → Leads → same search → delete.

**4. Blocklist both Max Lo addresses**
Settings → Blocklist → add:
- `maxlo@greenbanker.com`
- `maxlo.greenbanker@gmail.com`

**5. Send the two messages**
`FOR-CHERRY.md` and the Legal message in `MESSAGES-TO-SEND.md`.

## This week

**6. Build the suppression list** — the one fix that prevents another Stanley Lo
Pull every address the company has transacted with — deal mailboxes, DocuSign participants, past clients, counterparty agents. One CSV. Upload to Settings → Blocklist. It applies across every campaign automatically.

**7. Confirm the postal address is in every footer** — the unsubscribe link is done, this is the other half
CAN-SPAM needs a valid physical address as well as the opt-out link. Open each campaign's sequence and check `170 Glenn Way, Suite 5, San Carlos, CA 94070` sits alongside the unsubscribe link. Four campaigns: Realtors July, Oakland, SF County, Peninsula.

**8. Read and answer the open replies**
- SF County's 2 replies and the $1,000 opportunity
- **Rob Edwards** — `rob.edwards.sf@gmail.com`, replied 7 Aug at 18:56 asking *"Can you tell me who you are or why you contacting me?"* — still unread after seven weeks. Answer this one first; it's a real person who asked us a direct question.
- Anything Instantly AI question 9 turns up

**9. Finish the opt-out sweep**
Each campaign → Leads → search: `kurt` · `jason` · `leah` · `anagnostou`. Delete hits.
Peninsula, Realtors July, Oakland, SF County, 27 Prague St.

**10. Export the 10 live leads**
They exist nowhere but Instantly. Download them. The ten:
- Realtors July — Jonathan Lee `jonathan.a2mrealestate@gmail.com` · Andrea Ruth `aruth9563@aol.com` · Jonathan Britton `brittonco@gmail.com` · Lisa Eccleston `lisa@ecclestoninc.com` · Paul Skrabo `pskrabo@yahoo.com`
- Oakland — Don Dunbar `dondunbar322@gmail.com` · Tim Gullicksen `timjgullicksen@gmail.com`
- Peninsula — Amelia Middel `amelia.middel@cbnorcal.com`
- SF County — Todd Wiley `todd.wiley@compass.com`
- Earlier sequence — Steven `steven@ascendre.com`

Don't carry the dollar amounts over. Instantly puts a default $1,000 on every tagged lead; none of it is real.

**11. Get the rest of the bounces** — we have 48 of about 324
Ask Seth or Lawrence to run the bounce export for every campaign, using the steps in `GET-THE-BOUNCES.md`. Expect roughly 195 on Realtors July, 29 on SF County, 16 on Oakland, 2 on 27 Prague, and about 38 on the 3375 test run. All of them go on the blocklist.

**12. Fix the signature so it matches the sender** — the identity problem
Every email is signed *Juan Diaz* but goes out from six different addresses. Five out of six agents get mail from a name that isn't in the message, and replies land in whichever mailbox sent it instead of with Juan. Two ways to fix it, pick one:
- Send the realtor campaigns from `juan@` only, so sender and signature agree; or
- Give each sending address its own signature, so bryan@ signs as Bryan and so on.

While you're in there: add a `twinhomebuyer.com` link to the copy. There isn't one anywhere, so an agent who's never heard of us has no way to check we're real.

**13. Settle licence #1066892** — one for Legal, not for you to decide
It goes out as a **Twin Home Buyer** licence in the three realtor campaigns and as a **Matrix Group One** licence in the 27 Prague email. Same number, two company names, both in mail sent to licensed agents. Add it to the Legal message alongside the Mariaelena Diaz question.

## Standing rules

- **Never delete a campaign.** Pause, archive, rename. Deleting destroys the send record and the leads.
- **Load leads as a named list**, never straight into a campaign queue.
- **Sending runs Monday to Saturday**, six days. Nothing on Sunday.
