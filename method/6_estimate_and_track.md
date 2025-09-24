# Effort Forecasting & Tracking

Forecasting is fundamental to bootstrapping. No fluff. You need a number you can stand behind.

## Estimating: Fermi First

- **Bootstrap PM must be able to Fermi** (or have someone who can). Back-of-the-envelope, reasoned, defensible.
- **Step 1 — Classify the task**
  - **BAU / routine**: repeatable, known, stable (e.g. “install standard VM image”). Use the last known good duration. Don’t overthink.
  - **Ambiguous**: some unknowns. Note them.
- **Step 2 — Reduce ambiguity**
  - Compare to last similar work: *Was it a new image last time? Any snags? How long did fixes take?*
  - Borrow history ruthlessly.
- **Step 3 — Full unknowns**
  - Use a **Fermi estimate** (e.g. “install image in GCP VM — never done before” → break into sub-steps, size each quickly, sum).

**Buffer rule:** take the SME’s effort and **multiply by 1.5**.  
You present the **total** to the customer. Start high so there’s room to come down (they will try to push it down).

> **Iron Bootstrap Rule:** the project **does not proceed** unless **every task is accounted for and estimated**.

## How to Write the Estimate (keep it blunt)

| Task | Type (BAU/Ambig/Unknown) | SME Effort (d) | Buffer x1.5 | Published Effort (d) | Notes/Assumptions |
|------|---------------------------|----------------|-------------|----------------------|-------------------|
| Install VM image | BAU | 1.0 | 1.5 | **1.5** | Same image/version as last month |
| New image (vNext) | Ambig | 1.5 | 2.25 | **2.5** | Last time driver issue (+0.5d) |
| GCP VM first-time | Unknown | 2.0 | 3.0 | **3.0** | Fermi: net + firewall + perms |

Document as **estimate**. Call out assumptions and traps.

## Effort Tracking (Budget Control)

- **Timebox** Fermi tasks when possible. Even if soft, it gives you a heartbeat.
- **Track like this (daily/bi-daily with the owner):**
  - *“Task was sized at 5 days. We’re 2 days in. Where are we?”*
  - If the SME says **“10% done”**, you have a problem. Either the estimate was wrong, or there’s a gate.

**Probe immediately (5 Whys):**
- Is there a **gate** (e.g. waiting on firewall, access, data, approvals)?
  - **Action:** add a visible milestone/blocker in the plan, name the owner, **escalate to KDM**.
- Is it **underestimated** (we just sized it badly)?
  - **Option 1:** **Borrow** time from other tasks (ideally ones already completed under budget).
  - **Option 2:** **Escalate to KDM** — warn it’s taking longer; renegotiate scope/budget/dates.
  - **Blame wisely:** if it’s a customer dependency, say so (with evidence). If it’s on delivery, **own it** and adjust.

**Smell test:** if **% time elapsed >> % work complete**, raise a flag. Don’t wait for Friday.

## Tooling

Bootstrap PMs don’t worship tools, but they use what works:  
- **Burn charts** (progress vs. effort). Quick visual of whether you’re on track or drifting.  
- **RAG status** (Red/Amber/Green). Fast, brutal clarity for execs. If it’s Red, everyone knows.  
- **Kanban board / task grid**. Delivery plan in motion. Doesn’t matter if it’s Jira, Trello, or a whiteboard.  
- **Simple trackers** (Excel/Sheets). Sometimes the fastest way to keep time vs. progress visible.  

Pick the tool that gives clarity with least drag.

## Cadence & Pressure

- Meeting frequency is a **vibe call**:
  - **Clued-up, demanding customer?** Match their pace. Daily stand-ups are fine.
  - **Laid-back customer?** **Red flag.** Micromanage. When dates slip, blame lands on delivery. Stay ahead of it.

**Your job:** Nag both sides. SMEs may moan, but they’re not paying.  
The goal is **customer satisfaction** — visible progress, clean comms, no surprises.

## Lawyer/Detective Mode

- Always gather **evidence**: decisions, blockers, owner acknowledgements, timestamps.
- Run **pre-mortems**: “If this goes wrong, how will it go wrong?” Then go hunt those failure points now.
- If it does go **tits up**, your trail proves diligence and narrows the fix.

## Quick Checklists

**Estimation**
- [ ] Task classified (BAU / Ambig / Unknown)
- [ ] History reviewed (last time, snags, fixes)
- [ ] Fermi used where needed
- [ ] Buffer x1.5 applied and **published**
- [ ] Assumptions + traps written down
- [ ] Every task estimated (**iron rule**)

**Tracking**
- [ ] Timebox set (if possible)
- [ ] Daily/bi-daily progress vs. time check
- [ ] Gates logged as blockers, owners named
- [ ] Under-/over-runs balanced or escalated
- [ ] KDM informed early on impact
- [ ] Evidence captured (notes, emails, screenshots)
