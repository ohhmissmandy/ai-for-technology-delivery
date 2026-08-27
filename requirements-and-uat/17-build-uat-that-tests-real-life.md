# Build UAT That Tests Real Life

Use this when you need UAT to prove the solution works for real users and real workflows, not just the happy path.

## Prompt

Build a practical UAT approach from the information below.

Start with what UAT actually needs to prove for this implementation.

Identify the business processes, user roles, rules, decisions, handoffs, integrations, data conditions, and exceptions that matter most.

Then create realistic test scenarios that cover:

* normal day-to-day workflows
* important variations
* exceptions and error handling
* role or permission differences
* business rules
* integrations
* data conditions
* approvals
* downstream impacts
* operational handoffs

For each scenario, include:

**Scenario**

**User role**

**Purpose**

**Preconditions**

**Steps or workflow**

**Expected result**

**Evidence to capture**

**Related requirement or business outcome**

Prioritize the scenarios based on business impact and risk.

Call out anywhere scripted testing could give us false confidence because real users may not follow the script.

Also identify anything that should be tested outside UAT because it belongs in another testing phase.

Do not treat a successful login or screen load as proof that the business process works.

## What to provide

Paste the requirements, workflows, user roles, business rules, integrations, known risks, acceptance criteria, or other available implementation information.

## Example

### Example input

A company is replacing an expense-approval workflow.

Employees submit expenses. Managers approve them. Certain expenses also require Finance review.

Important rules:

* receipts are required above a specific amount
* employees cannot approve their own expenses
* Finance must review international expenses
* rejected expenses return to the employee
* managers can delegate approval when they are out of office
* approved expenses are sent to the accounting system

### Example output excerpt

**What UAT needs to prove**

UAT should prove that real users can complete the expense process correctly across the normal workflow and the exceptions that affect approval, compliance, and downstream accounting.

**Scenario: Manager has delegated approval**

**User role:** Employee and delegated manager

**Purpose:** Confirm delegated approval works without changing the underlying approval rules.

**Preconditions:** Primary manager has an active delegation.

**Scenario:** Employee submits an expense that requires manager approval.

**Expected result:** The delegated manager can review and approve the expense. The employee cannot approve their own request. The approval history shows who acted.

**Evidence to capture:** Submitted expense, delegation record, approval history, final status.

**Related business outcome:** Expenses continue moving when a manager is unavailable without weakening approval controls.
