# Marketing Automation & Workflow Design Skill

## Purpose
Identify safe, useful ways to automate repeatable Reznt marketing operations without losing human oversight.

## When to invoke
Invoke this skill when a Reznt team member needs the task described above completed independently.

## Required inputs
- Workflow to improve.
- Current tools/connectors and permissions.
- Trigger, inputs, outputs, owners, and failure consequences.

If a critical input is missing, state the assumption or ask one concise clarification. Do not block useful work when reasonable assumptions can be clearly labeled.

## Operating procedure
1. Map the current workflow and quantify pain where data exists.
2. Identify repeatable steps suitable for automation and decisions that need human approval.
3. Define trigger, input schema, transformation, output destination, access control, and audit trail.
4. Design error handling, retries, deduplication, rate limits, monitoring, and manual fallback.
5. Minimize personal data and apply least-privilege access.
6. Create a small pilot with success metrics and rollback criteria.
7. Document ownership, maintenance, and change control.

## Required output
- Current/future workflow map.
- Automation specification and data schema.
- Human approval and failure handling.
- Pilot plan, metrics, and maintenance owner.

## Quality and safety checks
Do not claim an integration exists without verification. Never automate external messaging or destructive actions without appropriate authorization and safeguards.

## Reznt context
Use `00-foundation/REZNT_BRAND_BRIEF.md` and `00-foundation/RESEARCH_STANDARDS.md`. Keep Reznt's positioning as an AI Revenue Operator for conversation-led businesses in view. Do not reduce the value proposition to “automated replies” unless the task specifically concerns that feature.

## Related skills
Use related skills when the task requires deeper evidence or execution.

## Research logging
For material findings, produce a completed record using `00-foundation/RESEARCH_LOG_TEMPLATE.md`. Include source URLs and evidence labels. Never claim that you saved data to a system unless the platform actually provides and confirms that capability.