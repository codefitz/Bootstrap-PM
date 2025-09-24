# Sign-offs

Sign-off is the currency of Bootstrap Project Management.
It’s not the Gantt chart, not the Jira board, not the ritual.
When the customer signs, the milestone is done.

## What a Sign-off Is

- A sign-off is a signal of **customer satisfaction**.  
  - Once it’s signed, no more work is required to meet satisfaction.  
- A deliverable does **not** have to be “complete” to be signed off. There are many reasons it may stop short:  
  - Customer descoped the work.  
  - Customer ran out of money.  
  - Activity was timeboxed — the days are done, even if the intended product isn’t finished.  

If there’s a sign-off, that’s the definition of done.  

## Why Sign-off Matters

- **Customer satisfaction is the target.** Sign-off is proof they’re satisfied.
- Without evidence of sign-off, everything is open to dispute.
- Sign-off protects the delivery team from scope creep, memory loss, and “we never agreed to that.”
- It locks in the outcome.

## Acceptable Forms of Sign-off

- Signed contract / SoW.
- Email from KDM confirming acceptance.
- Meeting notes circulated and acknowledged (best if customer replies “agree”).
- Recorded call / video clip (if agreed as valid).
- Even a simple ticket comment — as long as it’s explicit.

If you can point to it later, it counts. If not, it doesn’t.  

## How to Collect Sign-off

- Ask for it explicitly. Don’t assume silence = approval.
- Present outcomes/KPIs and the evidence that they’re met.
- Keep the request simple:
  > *“We’ve delivered \<milestone>. Please confirm acceptance.”*

## Where to Store Sign-offs

- All sign-offs go in the **Evidence folder** (or repo if versioned).
- Structure it by milestone:

```
/Deliverables
    /Milestone-01
        outcome.md
        evidence.pdf
        signoff-email.eml
    /Milestone-02
```
- Treat this folder like a courtroom exhibit box. When things get ugly, this is what saves you.

## When Sign-off Is Missing

- Don’t proceed to the next phase until it’s locked.
- Escalate politely but persistently.
- Use the “assumption reflex” trick:
> *“If I don’t hear back by EOD, I’ll assume Milestone X is signed off and will progress accordingly.”*

People hate being misquoted — they’ll respond faster.

## If You Can’t Get a Sign-off

Refusal to sign-off = danger. Risks:
- Not getting paid.
- Legal disputes.
- Project being considered “incomplete” even when work was delivered.

PM must first understand *why* there’s no sign-off:
- Customer doesn’t feel the work is complete.
- Customer is waiting on internal approval (e.g. CFO sign-off).
- Project was cancelled mid-way.

## Resolution Process

### 1. Customer not satisfied
- Objective = resolve without escalation.
- Ask: Did we deliver to spec?
  - **Yes:** Collect evidence and present.
  - **No / lack of evidence:** Gap analysis, fix it. It should never have reached sign-off attempt.
  - **No / functionally impossible:** Document SME explanation. Raise with customer.

**If delivered to spec but customer still unsatisfied**
- Likely a disconnect between what was sold vs. what they thought they bought.
- Hold a rescoping workshop with SMEs.
- Resolve through change management (new scope, new money).
- If they refuse change - escalate to sales/account manager.
  - Account may waive costs as goodwill.
- If it’s a toxic relationship → execs decide to cut losses - Go to Last Resort.

**If delivery not complete**
- Instruct SMEs to do gap analysis and finish.
- If undocumented changes complicated delivery - raise them now. May negotiate more money, but no guarantees, the customer is not obliged to accept unnapproved changes to scope (even if they asked for them).

**If blocked by functionality (impossible ask)**
- Should have been caught at kickoff, but if you inherited a failing project it’s on your lap.
- Document SMEs’ case and explain to customer.
- If customer insists anyway, follow same resolution as above (rescope, negotiate, or escalate).
- Push SMEs to think laterally: is there a tool, workaround, or purchase that could make it viable?

**If customer abandoned project**
- Could be layoffs, refocus, budget pulled.
- Go to Last Resort.

## Last Resort

If all reasonable attempts fail and escalation hasn’t worked:

1. Send a formal note that the milestone/project is considered **closed**, with a **5-day grace period** to dispute.
2. If disputed, modify note to reflect next steps (invoice, suspension, etc), you may even have a template email from legal at this stage.
3. After this, either stakeholder may end up initiating legal action for breach of contract.

The **Evidence folder** becomes critical here. Expect it to be used in legal review.

## Checklist

- [ ] Sign-off requested explicitly for every milestone.
- [ ] Outcome and KPI evidence attached.
- [ ] Sign-off captured (contract, email, meeting note, etc).
- [ ] Stored in Evidence folder under correct milestone.
- [ ] Refusals investigated and resolved via steps above.
- [ ] Last resort triggered only when all else fails.

## Comments

Bootstrap PM doesn’t chase velocity.
It doesn’t chase story points.
It chases **signatures**.

Signed = satisfied.
Satisfied = success.
