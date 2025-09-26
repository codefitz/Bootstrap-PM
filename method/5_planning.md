# Delivery & Customer Plans

Every project needs a plan — but not the bloated, carved-in-stone kind.
Bootstrap plans are alive. They breathe, shift, and evolve.

There are two plans you care about: the Delivery Plan and the Customer Plan.
One is for you and your team. The other is for the people paying.

## Delivery Plan (Living)

- Built for the delivery stake (your team, partners, anyone hands-on).
- Must have **outcomes as milestones**. If it’s not tied to an outcome, it’s noise.
- Format doesn’t matter — kanban board, gantt chart, grid, whatever.
- Granularity rule: every task must directly affect progress. If it doesn’t move the needle, bin it.
- Document owners for tasks. If no one owns it, it won’t get done.
- Keep it alive. Update as things shift. Don’t let it rot.

## Customer Plan (Light)

- Built for the customer stakeholders, especially the KDM with the money.
- High-level milestones only — no one outside the delivery team cares about sub-tasks.
- Includes deliverables that the customer and their 3rd parties must produce.
- Should fit in an email or slide.
- Tone = clarity. They need to know what’s coming, when, and what they own.

## The Handshake

Delivery Plan = detail.
Customer Plan = story.

Both must line up. If they drift apart, you’re in trouble.

## When to Pivot

- Budget overrun? → Update both plans.
- Undocumented change? → Only update delivery plan if the change is still in progress. Don't update the customer plan, but document retrospectively.
- Outcome dropped or swapped? → Update both plans.

Living means living. If the plan doesn’t reflect reality, it’s a liability.

## Effort Forecasting

Forecasting is fundamental to bootstrapping. No fluff. You need a number you can stand behind.

### Estimating: Fermi First

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

### How to Write the Estimate (keep it blunt)

| Task | Type (BAU/Ambig/Unknown) | SME Effort (d) | Buffer x1.5 | Published Effort (d) | Notes/Assumptions |
|------|---------------------------|----------------|-------------|----------------------|-------------------|
| Install VM image | BAU | 1.0 | 1.5 | **1.5** | Same image/version as last month |
| New image (vNext) | Ambig | 1.5 | 2.25 | **2.5** | Last time driver issue (+0.5d) |
| GCP VM first-time | Unknown | 2.0 | 3.0 | **3.0** | Fermi: net + firewall + perms |

Document as **estimate**. Call out assumptions and traps.

## Example

**Delivery Plan Milestone**  
- Outcome: “Migrate core finance reports”
- Tasks: Extract dataset / Transform / Load / Validate / Customer sign-off
- Owner: Dev Lead + Finance SME
- Status: In progress

**Customer Plan Milestone**  
- “Finance reports available in new system by 31st March”
- Customer deliverable: Provide dataset by 15th Feb
- Sign-off: CFO

## Checklist

- [ ] Build Delivery Plan (outcomes as milestones, granular tasks, owners).  
- [ ] Build Customer Plan (milestones only, includes their deliverables).  
- [ ] Confirm both line up.  
- [ ] Share Delivery Plan with delivery stake only.  
- [ ] Share Customer Plan with stakeholders.  
- [ ] Keep both alive. Update on every major change.

**Estimation**
- [ ] Task classified (BAU / Ambig / Unknown)
- [ ] History reviewed (last time, snags, fixes)
- [ ] Fermi used where needed
- [ ] Buffer x1.5 applied and **published**
- [ ] Assumptions + traps written down
- [ ] Every task estimated (**iron rule**)