---
name: ai-content-workflow-designer-skill
description: Design a lightweight, repeatable AI-assisted marketing content workflow with sourced inputs, quality gates, owners, and handoff requirements. Use for planning a workflow, not publishing content.
---

# AI Content Workflow Designer
Adapted on 2026-10-16 from Anthropic skill-creator; see THIRD_PARTY_NOTICES.md.

## Intake
Reuse relevant user-provided context before asking questions. Capture objective, audience, channel, deliverable, constraints, deadline and reviewer. Ask only about missing information that changes the design; label safe assumptions. Do not copy confidential project architecture into reusable or public examples.

Maintain a small context ledger: ID, fact or instruction, source/link or conversation reference, date, confidence, permitted use, and verification needed. An unavailable source stays unverified. Separate content facts (offers, dates, product properties, evidence) from style preferences (voice, length, rhythm); style never establishes truth.

## Design
1. State the desired outcome and smallest useful deliverable. Separate draft preparation from external publication.
2. Map 4–7 practical steps from intake to human handoff. For each step give input IDs, responsible role, concrete action, output artifact, acceptance check and failure route.
3. Add factual verification before style polish. Each claim needs evidence or must be removed/qualified. Resolve conflicting sources explicitly; don't choose the more attractive claim.
4. Give a short reusable prompt for each AI-assisted step: task, allowed sources, output shape and missing-information behavior.
5. Add a factual gate (supported claims, dates, offer terms), a usefulness gate (audience, CTA and channel), and a style gate. Distinguish blockers from editable preferences.
6. Define the handoff: artifact/version, provenance, open issues, gate status, named role for approval and exact next action. An unchecked gate is pending, not passed.
7. Propose one low-cost dry-run task and an observable success criterion. Execute only if requested and authorized; label a proposed test as not run. Revise after actual feedback, preserving useful context.

Use assets/workflow-template.md for the deliverable and examples/fictional-workflow.md for scope calibration. A design can finish with a blocked publication gate; don't fabricate missing evidence to mark it ready.

## Boundaries
Do not send, publish, purchase tools, upload confidential inputs, or alter accounts as a side effect of planning. No special orchestration framework is required. Do not claim measured speed, conversion or quality improvements without a recorded comparison.

