# Jonathan's do-list — Instantly

Just the clicks. No findings, no reading.

## Today

**1. Strip the dead senders — 10 minutes, do this first**
Open each of these three campaigns → Sequences/Settings → sender pool → remove `carlo@twinhomebuyer.com` and `juan@twinhomebuyer.com`:
- Realtors July 2026
- Oakland Realtor Campaign
- San Francisco County Realtor

They'll fail on resume otherwise.

**2. Export the deleted campaign's threads**
Ask Carlo to run Unibox `getEmails` with `campaign_id: c05714e3-35db-4223-8873-c65639a33173`. Save the output somewhere outside Instantly. Only surviving record of 2,000+ sends.

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

**7. Fix the Peninsula Step 2 unsubscribe link**
Peninsula → Editor → Step 2 → the unsubscribe href is empty. Point it at the working one from another step.

**8. Read and answer the open replies**
- SF County's 2 replies and the $1,000 opportunity
- Rob Edwards — replied to the deleted campaign, never read
- Anything Instantly AI question 9 turns up

**9. Finish the opt-out sweep**
Each campaign → Leads → search: `kurt` · `jason` · `leah` · `anagnostou`. Delete hits.
Peninsula, Realtors July, Oakland, SF County, 27 Prague St.

**10. Export the 17 opportunities**
They exist nowhere but Instantly. Download them.

## Standing rules

- **Never delete a campaign.** Pause, archive, rename. Deleting destroys the send record and the leads.
- **Load leads as a named list**, never straight into a campaign queue.
