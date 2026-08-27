# Learn Enough to Lead the Implementation

Use this when you are responsible for implementing a technology, platform, or solution you have not worked with before.

The goal is not to turn me into the technical SME. The goal is to help me understand enough to lead the implementation intelligently, ask better questions, and recognize when something important may be getting missed.

## Prompt

I am responsible for helping lead the implementation described below.

Explain the solution in practical terms first. Tell me what it does, what business problem it typically solves, and how it generally fits into an organization's technology and operating environment.

Then walk me through what an implementation usually looks like from start to finish. Tell me who normally needs to be involved, what decisions need to happen early, and what dependencies I should understand. Cover integrations, data, security or compliance, testing, deployment, training, and ongoing support where they're relevant.

Tell me where implementations like this tend to get into trouble. Think about things like unclear ownership, hidden dependencies, underestimated data work, vendor lead times, environment issues, testing gaps, user resistance, support, or assumptions that surface too late.

Give me a list of questions I should ask:

* the technical team
* the business owner
* the vendor, if applicable
* operations or support
* security, risk, or compliance
* affected users

Also tell me what I personally need to understand well enough to lead the work and what can reasonably remain with the technical or business SMEs.

Finish with a short **Ã¢â‚¬Å“If I only remember ten thingsÃ¢â‚¬Â** summary.

Do not pretend to know details that depend on our specific environment. Flag those as questions for my team.

## What to provide

Include, where available:

* technology or solution
* industry or organization
* business problem
* known environment or constraints
* what you already know

## Example

### Example input

**Technology or solution:** Privileged access management platform

**Industry / organization:** Large regulated company

**Business problem:** Administrative access is handled differently across several technology teams. The company wants stronger controls, better logging, and a more consistent process.

**Known environment or constraints:** Security will own the platform. Several infrastructure teams will be affected. Some systems are old and may not integrate cleanly.

**What I already know:** I understand why privileged access is risky, but I have never implemented a PAM platform.

### Example output excerpt

**What you need to understand as the implementation lead**

You do not need to become the person configuring vaults or writing integrations.

You do need to understand:

* what privileged accounts are in scope
* how users will request and receive elevated access
* which systems can integrate directly and which may need another approach
* how credentials will be stored or rotated
* how emergency access works
* what gets logged
* what happens when the platform is unavailable
* who owns onboarding new systems after the project ends

**Questions for the technical team**

* Which account types are in scope for the first release?
* Which target systems have known integration limitations?
* What happens to existing service accounts?
* What technical dependency has the longest lead time?

**Questions for operations**

* Who will own access exceptions?
* Who handles failed onboarding or integration issues?
* What recurring work will exist after launch?
