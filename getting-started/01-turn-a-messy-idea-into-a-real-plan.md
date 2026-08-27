# Turn a Messy Idea Into a Real Plan

Use this when you have the beginning of an initiative, but the information is still scattered, incomplete, or not ready to become a real project plan.

## Prompt

Review the information I provide and help me turn it into a realistic delivery plan.

Start by identifying the business problem, intended outcome, who is affected, and what success appears to mean. If the goal is too vague to plan against or success cannot yet be measured, call that out.

Before building the plan, separate what we actually know from what we're assuming or still need to figure out. Call out missing information, dependencies, constraints, and decisions that still need to be made.

Then break the initiative into logical phases. For each phase, identify the major work, expected deliverables, likely teams or roles involved, important dependencies, decisions or approvals needed, and reasonable milestones. Stay at the level supported by the information I gave you. Do not invent detailed tasks, owners, dates, or estimates when there is not enough information to support them.

As you build the plan, look for things we may be overlooking. Consider technology, integrations, data, security, compliance, vendors, business-process changes, testing, UAT, training, communications, operational readiness, support after launch, resources, and user adoption. Don't force all of these into the plan. Only include what actually matters for this initiative.

Identify the most important risks, bottlenecks, dependencies, and unresolved decisions. Be specific about the cause and likely impact.

Create an initial delivery view with:

| Phase | Major Deliverable | Owner / Team | Key Dependency | Target Timing | Confidence |
| ----- | ----------------- | ------------ | -------------- | ------------- | ---------- |
|       |                   |              |                |               |            |

Use placeholders where ownership or timing is still unknown.

Finish with:

**What we need to answer now:** Questions or decisions that materially affect scope, timing, cost, feasibility, or ownership.

**What can wait:** Open questions that do not need to be resolved before planning continues.

**What I should do next:** The first practical actions needed to move the initiative forward.

**What I should not commit to yet:** Dates, scope, estimates, or outcomes that are not supported by enough information.

## What to provide

Paste any available project information, notes, requirements, requests, constraints, dates, risks, or other context.

## Example

### Example input

We want to replace a manual access-request process with a new internal platform.

Right now, requests are submitted by email and approved by managers. The new platform has already been selected, but we have not finalized the workflow.

The business wants to launch in about four months.

Known so far:

* employees and contractors will use it
* manager approval will still be required
* HR data may be needed to identify managers
* Information Security needs to review the design
* the vendor will help configure the platform
* Operations will support it after launch
* we have not decided who owns training
* there is no final UAT plan yet
* several teams currently handle access differently

### Example output excerpt

**What we know**

* A replacement platform has been selected.
* Manager approval remains part of the future process.
* HR data may be required.
* Information Security review is needed.
* Operations is expected to own support after launch.

**What we still need to figure out**

* Whether the four-month target is based on vendor and internal-team capacity.
* Which access workflows will be standardized and which require exceptions.
* Who owns the future business process.
* Who owns training and user communications.
* What HR integration or data transfer is required.
* What UAT must prove before launch.

**What we should not commit to yet**

The launch date should not be treated as committed until the integration approach, workflow decisions, security review, vendor timeline, and UAT window are better understood.
