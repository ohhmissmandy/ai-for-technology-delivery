# Are We Actually Ready to Launch?

Use this when the launch date is getting close and you need to know whether the project is truly ready, not just whether the checklist has a lot of green boxes.

## Prompt

Review the launch-readiness information below and assess whether we are actually ready to go live.

Evaluate the areas that matter for this implementation, including:

* technical readiness
* production configuration
* integrations
* data
* security or compliance
* testing and UAT
* open defects
* business readiness
* training
* communications
* vendor readiness
* operational procedures
* support readiness
* monitoring
* escalation paths
* rollback or contingency planning
* known limitations
* unresolved decisions

For each relevant area, classify it as:

**Ready**

**Ready with Conditions**

**Not Ready**

**Not Enough Information**

Explain the evidence behind each rating.

Do not treat a completed task as proof of readiness if the outcome has not actually been validated.

Identify anything that could realistically prevent launch, create unacceptable business impact, or leave operations unable to support the solution.

Separate true launch blockers from items that can reasonably be handled after go-live.

Finish with:

**Overall recommendation: Go / Go with Conditions / No-Go**

**Conditions that must be met before launch**

**Risks being accepted**

**Who needs to make the final go/no-go decision**

## What to provide

Paste the launch checklist, testing status, defect status, training completion, operational-readiness information, vendor status, support plan, contingency plan, known limitations, and unresolved decisions.

## Example

### Example input

A new customer-service platform is scheduled to launch Monday.

Current status:

* production configuration complete
* integration testing complete
* UAT completed with two medium defects still open
* both defects have documented workarounds
* training completed for 92% of users
* new support procedures drafted
* help desk has not yet reviewed the procedures
* vendor support contact confirmed
* rollback steps exist but have not been walked through with the full deployment team
* business leader has approved launch
* one reporting dashboard will not be available until the second week after launch

### Example output excerpt

**Technical readiness: Ready with Conditions**

Production configuration and integration testing are complete. Two medium defects remain, but both have documented workarounds.

**Training: Ready with Conditions**

Most users have completed training, but the remaining population should be identified. Confirm whether anyone who must use the platform on day one is included in the 8% who have not completed training.

**Support: Not Ready**

Support procedures exist, but the help desk has not reviewed or accepted them. A document being written is not the same as the support team being ready to use it.

**Contingency: Ready with Conditions**

Rollback steps exist, but the full deployment team has not walked through them. Confirm decision ownership, trigger points, and the sequence before launch.

**Recommendation: Go with Conditions**

Launch can remain viable if help-desk readiness and rollback alignment are completed before the final go/no-go decision.
