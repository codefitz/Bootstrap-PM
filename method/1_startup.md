# Startup
When you land in a project — whether fresh or mid-flight — this is how you bootstrap. It's about getting the basics in place fast, without choking in process.
If you're new to the playbook, skim the broader [methodology](./methodology.md) so you know how Startup fits into the rest of the flow.

## 1. Establish What's Been Sold
- First question: what's actually been sold, bought, or requested?
- Don't trust hearsay. Get the contract, the SoW, the email trail — whatever the customer thinks they paid for. That's your baseline.
- Translate the promises into measurable outcomes using the [Defining Outcomes](./2_outcomes.md) guidance. If it isn't written, it isn't real.

## 2. Assemble the Team
- Could be a one-man project (you). Could be a full squad. Doesn't matter — you start with your local neighbourhood first.
  - By "neighbourhood," I mean your delivery stake. The people actually doing the work.
- Map every name against the [roles](./roles.md) so you know who is the Alchemist (Project Manager), the Knights (Subject Matter Experts), the Envoy (Sales), and the rest of the court.
- Kick off internally before you even talk to the customer.

## 3. Schedule Internal/Delivery Kick-off
Agenda:
- Review what's been sold and any outcomes already defined.
- Ask two questions: can it be done? and how can it be done?
- Apply **5W1H**: Who, What, When, Where, Why, How.
- Use the [Stakeholder Kick-offs](./3_kickoffs.md) playbook to structure the session and prep for the customer.
- If the [Knights (Subject Matter Experts)](./roles.md#the-knight-sme) say "cannot be done" — you stop here. Flag immediately with the [King (Executive Authority)](./roles.md#the-king-executive-authority) and the [Custodian (Customer Key Decision Maker)](./roles.md#the-custodian-customer---kdmspoc) before wasting another minute.

## 4. Draft the Plan
- If it's feasible: the [Alchemist (Project Manager)](./roles.md#the-alchemist-project-manager) drafts the delivery plan, the customer plan, and proposed KPIs.
  - Delivery plan = living, granular, for the team.
  - Customer plan = high-level milestones only.
  - KPIs = how success will be measured.
- Shape the artefacts with the [Planning](./5_planning.md) playbook and set up tracking with the [Delivery Tracking](./6_tracking.md) guidance.
- Once drafted, arrange the kick-off with the customer stakeholder.

## 5. File Structure
Set up the bones of the project. Keep it light, consistent, and easy to share. Suggested layout:

```
/Architecture
/Templates
/Data
/Media
/Meetings
/Products
/Deliverables
```

- Code should live in a repo with version control, not a file share.
- Deliverables folder is where all evidence and sign-off docs go.
- Don't over-engineer it. Just enough structure so no one can say "I couldn't find it."
- Keep evidence tidy; it becomes your ammo for [Sign-off](./8_sign_off.md) later.

> **Iron Bootstrap Rule**: No empty folders. Empty folders are a sign of failure to commit or failure to deliver. A placeholder is OK but if it looks like it's not being used, bin it. Save time searching for things later in the audit.

## Startup Checklist

- Confirm what's been sold/bought/requested (see [Defining Outcomes](./2_outcomes.md))
- Assemble delivery stake / team (map against [Roles](./roles.md))
- Run internal kick-off (review, 5W1H, feasibility check)
- If blocked → flag customer immediately
- Draft delivery plan, customer plan, KPIs (lean on [Planning](./5_planning.md) and [Delivery Tracking](./6_tracking.md))
- Arrange customer kick-off (prep with [Stakeholder Kick-offs](./3_kickoffs.md))
- Create project file structure and repos (store evidence ready for [Sign-off](./8_sign_off.md))
