# Where Does a Human Still Need to Be Involved?

Use this when AI or automation is being added to a workflow and you need to decide where human judgment, approval, review, or oversight still matters.

## Prompt

Review the workflow below and help determine where a human still needs to be involved.

Break the workflow into the decisions, recommendations, actions, and handoffs that actually matter. Show what the AI or automation is doing and what people are still doing.

For each one, look at:

* consequence if it is wrong
* how easy the outcome is to reverse
* whether judgment or context is required
* whether the decision affects a person's rights, access, money, employment, safety, or another meaningful outcome
* data quality and confidence
* privacy, security, regulatory, or fairness concerns
* whether someone can detect that the AI was wrong
* who is accountable for the outcome
* how exceptions are handled

Recommend what human involvement is actually needed. That may include one or more of these:

**Decide**

**Approve**

**Review**

**Override when needed**

**Monitor**

**Not routinely required**

Explain why.

Also identify where human involvement could become a meaningless rubber stamp instead of useful oversight.

For areas where the AI can act without case-by-case approval, recommend appropriate monitoring, audit, exception handling, or after-the-fact review.

Don't assume every AI decision needs a person approving it first. But don't remove human judgment just because the technology can technically do the work.

Finish with:

**Where people need to stay directly involved**

**Where AI can reasonably act with oversight**

**Where more information is needed before deciding**

**Who should own the outcome**

## What to provide

Paste the workflow, proposed AI or automation use, decisions being made, available data, affected users, potential consequences, existing controls, and any known regulatory, privacy, security, or fairness concerns.

## Example

### Example input

An AI system reviews incoming customer-support requests.

It can:

* identify the topic
* estimate urgency
* route the request to a support queue
* draft a response

The team is considering allowing the system to automatically send responses for low-risk requests. Employees would continue handling higher-risk cases.

Requests may include account information or customer complaints.

### Example output excerpt

**Topic classification: Monitor with override**

Classification errors are generally reversible. The system can classify and route requests automatically if routing accuracy is monitored and employees can correct mistakes.

**Urgency: Human review or override**

A missed urgent request could have a larger consequence than an incorrect topic label. Human review or a strong escalation path is more important here.

**Drafting responses: Human review**

The system can prepare a response, but a person should review it before it is sent when the request involves customer-specific information, complaints, or meaningful judgment.

**Automatically sending low-risk responses: Potentially appropriate with defined boundaries**

This may be reasonable, but "low risk" needs to be defined before automation is approved.

Confirm:

* which request types qualify
* what data the system can use
* what happens when confidence is low
* when the request must be escalated to a person
* how automated responses will be monitored
* who owns the outcome if the response is wrong

Human involvement does not need to look the same at every step. The level and type of oversight should match the consequence of getting the decision wrong.
