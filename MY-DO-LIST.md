# Jonathan's do-list — Instantly

Just the clicks. No findings, no reading.

## Today

**1. Strip the dead senders — 10 minutes, do this first**
Open each of these three campaigns → Sequences/Settings → sender pool → remove `carlo@twinhomebuyer.com` and `juan@twinhomebuyer.com`:
- Realtors July 2026
- Oakland Realtor Campaign
- San Francisco County Realtor

They'll fail on resume otherwise.

**2. Ask Carlo and Lawrence for the original spreadsheets** — the single highest-value message you will send
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

**10. Export the 17 opportunities**
They exist nowhere but Instantly. Download them.

## Standing rules

- **Never delete a campaign.** Pause, archive, rename. Deleting destroys the send record and the leads.
- **Load leads as a named list**, never straight into a campaign queue.
- **Sending runs Monday to Saturday**, six days. Nothing on Sunday.
