# Marketing Research Orchestrator Skill

## Purpose
Break a broad marketing question into independent tasks, select the right skills, and combine outputs into one decision-ready brief.

## When to invoke
Invoke this skill when a Reznt team member needs the task described above completed independently.

## Required inputs
- Broad business question.
- Decision owner, target segment, geography, timeframe, and constraints.
- Skills or tools available in the platform.

If a critical input is missing, state the assumption or ask one concise clarification. Do not block useful work when reasonable assumptions can be clearly labeled.

## Operating procedure
1. Rewrite the request as a decision question and success criteria.
2. Decompose it into small tasks: ICP, VoC, competitor, channel, content, product proof, analytics, and compliance as relevant.
3. Assign each task to the most appropriate individual skill; do not invoke every skill by default.
4. Define shared assumptions, source standards, output schema, and handoff points.
5. Run independent research where possible; wait for evidence before drawing conclusions.
6. Reconcile conflicting findings and label evidence strength.
7. Produce one prioritized recommendation, execution plan, owners, metrics, and open questions.
8. Create separate research-log records for material findings.

## Required output
- Task decomposition and skill map.
- Combined decision brief with citations.
- Recommended sequence, owners, dependencies, metrics.
- Unresolved conflicts and next research tasks.

## Quality and safety checks
Do not fabricate results from skills that were not run. Do not treat orchestration as permission to access private data or send campaigns.

## Reznt context
Use `00-foundation/REZNT_BRAND_BRIEF.md` and `00-foundation/RESEARCH_STANDARDS.md`. Keep Reznt's positioning as an AI Revenue Operator for conversation-led businesses in view. Do not reduce the value proposition to “automated replies” unless the task specifically concerns that feature.

## Related skills
Use related skills when the task requires deeper evidence or execution.

## Research logging
For material findings, produce a completed record using `00-foundation/RESEARCH_LOG_TEMPLATE.md`. Include source URLs and evidence labels. Never claim that you saved data to a system unless the platform actually provides and confirms that capability.