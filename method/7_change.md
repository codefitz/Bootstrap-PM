# Change Management

Changes will happen. Ordinary ones can follow standard protocols. Retroactive ones are the landmines.  
The [Alchemist (PM)](./roles.md#the-alchemist-project-manager) has to handle both with speed, evidence, and leverage.  

## Ordinary Changes

- These can follow standard frameworks (e.g. ITIL) — no need to reinvent the wheel.  
- Bootstrap PM’s job is to **identify upfront** what parts of delivery will require a change and what type.  
  - Example: VPN setup, user accounts, firewall rules. Effort might be 0.5 days, but approval could take 5.  
- Build this into the **plan** — every change must carry both:  
  - Effort number (how long to do it)
  - Timescale number (how long it takes to be approved)

Log change requests as soon as possible.
Don’t wait until Day 1 to request VPN access — that’s 5 days wasted with the team sitting idle.

- Use previous projects to anticipate likely changes. Customers often don’t know — lead with assumptions.
  - Example email: *“Assuming we’ll need firewall changes for X. If I don’t hear back by EOD, I’ll raise the request.”*
  - People will correct bad assumptions faster than they’ll answer open questions.

**Change scope types:**  
- **Simple:** (e.g. change button colour). Still document it — scope change matters.
- **Complex:** (e.g. switch database tech stack)). Expect commercial discussion with the [Custodian (Customer KDM)](./roles.md#the-custodian-customer---kdmspoc) and [Castellan (Account Manager)](./roles.md#the-castellan-account-manager).
- **Removed functionality:** customer drops a feature. Must document.
  - Evidence is vital in case of miscommunication or future disputes.
  - Don’t assume freed-up budget can be spent elsewhere. Confirm with customer before reallocating.

## Retroactive Changes (Scope Creep)

This is where [Knights (SMEs)](./roles.md#the-knight-sme) or well-meaning consultants slip in changes before the [Alchemist (PM)](./roles.md#the-alchemist-project-manager) even knows.  
- Customers like to “slide things in” and still expect on-time delivery.
  - Knights like to be helpful — and it strokes their reputation.
- But every one of these **must be documented**. No exceptions.

### Handling Retroactive Changes

- **Small (cosmetic)**  
  - **Example:** button colour red → blue.
  - Not worth tracking as effort.
  - Still log as scope change.

- **Medium (functional)**  
  - **Example:** send an email on form submit.
  - Has an effort cost, may have design impacts.
  - If project is behind → use as leverage for more budget.
  - If project is ahead → document as goodwill/freebie (but keep in pocket if things sour).
  - Always raise risks with the [Custodian (Customer KDM)](./roles.md#the-custodian-customer---kdmspoc). Offer the option to reverse the change (which costs delivery effort).

- **High (structural/strategic)**  
  - **Example:** Wholesale system shift, core design change.
  - If causes you to say out loud, *“What the hell are you doing?!”* — it’s high.
  - Stop project activity immediately.
  - Call an **all-hands** with all stakeholders.
  - If customer-led - must trigger payment or penalty.
  - If Knight/delivery-led - that team eats the pain.

## Checklist

**Ordinary Changes**
- [ ] Identify all changes required for setup/delivery.
- [ ] Log change requests early (before project start if possible).
- [ ] Build both effort + timescale into the plan.
- [ ] Use assumptions to provoke correction and speed.
- [ ] Document all drops/removals of functionality.

**Retroactive Changes**
- [ ] Detect and log every change (no exceptions).
- [ ] Classify: small / medium / high.
- [ ] Document impact and risks.
- [ ] Escalate medium/high to the [Custodian (Customer KDM)](./roles.md#the-custodian-customer---kdmspoc).
- [ ] Reverse option offered if needed.
- [ ] Evidence stored (email, meeting notes, repo log).

**Tone**

Bootstrap-PM isn’t anti-change — it’s anti-surprise. Every change is leverage, evidence, and protection. If it’s not documented, then it's a hidden landmine waiting for the wrong foot to fall at the wrong time.
