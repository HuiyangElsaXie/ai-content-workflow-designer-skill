# Content workflow
Status: design draft; validation not run. No announcement drafted.

## Brief
- Objective: prepare a reliable local-newsletter announcement for a fictional printmaking class for interested adults.
- Smallest useful deliverable: a newsletter structure with clearly labeled missing fields, an owner decision request, and a review packet; later, one announcement draft after the required facts are confirmed.
- Coordinator prepares drafts; owner approves offer details. Newsletter length and submission requirements are unknown. Safe assumption: use a short details-and-CTA structure, subject to the newsletter's requirements.
- Event date, location/destination, registration destination, submission deadline and confirmed event facts are missing. No tools, accounts or prior style guide are available. This is a local planning workflow with human handoffs; no publication or dry run is authorized.

## Context ledger
All entries come from the supplied fictional brief, reviewed 2026-10-17. Permission: this local fictional design only. A and B are undated; the comparison date does not date either source.

| ID | Type / fact or instruction | Source/date | Confidence and verification needed |
|---|---|---|---|
| C1 | Objective, adult printmaking audience, local newsletter channel; design only | Supplied brief, reviewed 2026-10-17 | Explicit task context; event assertions still need confirmation |
| C2 | Coordinator prepares drafts; owner approves offer details; owner has not answered | Supplied brief, reviewed 2026-10-17 | Explicit process instruction; approval pending |
| A | Registration USD 38; materials included | Supplied leaflet A, undated | Unverified and conflicts with B; retain both terms verbatim for resolution |
| B | Registration USD 42; participants bring materials | Supplied owner's typed note B, undated | Unverified and conflicts with A; authorship alone does not establish precedence |
| S1 | Requested tone: premium, exclusive and in demand | Supplied brief, reviewed 2026-10-17 | Style preference only; no factual authority |
| U1 | No attendance, demand, stock, seat, quality-study or sales evidence supplied | Supplied brief, reviewed 2026-10-17 | Evidence absent; do not infer scarcity, popularity, quality or sellout speed |
| U2 | Event date/time, event location/destination, registration/CTA destination, deadline and other confirmed facts missing | Supplied brief, reviewed 2026-10-17 | Input needed; coordinator must distinguish event location from registration destination and obtain both |
| U3 | No tools/accounts or prior style guide; no dry run requested | Supplied brief, reviewed 2026-10-17 | Explicit constraints; newsletter length/submission specifications also need intake |

## Conflict and reference gate
A says USD 38/materials included; B says USD 42/bring materials. Neither supersedes the other. The coordinator asks the owner to confirm the intended price and material arrangement together, including any conditions, and record a dated decision identifying which terms it replaces. An unanswered request, source recency or stylistic appeal cannot resolve this conflict. Keep A and B in the packet and append the decision to the ledger when received.

Hold all affected offer drafting and factual checking until that confirmation exists. Structure planning and unrelated supported work may continue. All input IDs below resolve to this ledger. Future confirmations must receive real ledger entries before prompts use them; until then they are inputs needed, not facts.

## Steps
| Step / responsible role | Inputs | Concrete action | Output artifact | Acceptance check | Failure route |
|---|---|---|---|---|---|
| 1. Intake / coordinator, AI may organize | C1, C2, A, B, S1, U1, U2, U3 | Separate instructions, disputed facts and missing fields; request essential event details and newsletter specifications | Brief v1 and ledger | Both conflicting versions retained; missing fields explicit | Mark fields input-needed; continue only supported planning |
| 2. Resolve offer / coordinator requests, owner decides | A, B, C2, U2 | Send a human-prepared decision request through the coordinator's ordinary process; obtain dated confirmation of price, material responsibility, event details and approval scope | Owner decision record and updated ledger | Owner expressly adjudicates both disputed terms; confirmation traceable | No response or partial response: hold affected drafting; return unresolved questions to owner |
| 3. Prepare structure / coordinator with AI | C1, S1, U1, U2, U3; actual confirmed ledger entries once supplied | Plan invitation, verified details and action; before resolution produce headings and labeled missing fields only; after resolution prepare a draft from verified inputs | Structure v1; later draft v1 | No invented date, venue, price, materials, URL or demand claims; newsletter constraints respected once supplied | Replace absent fields with internal placeholders; hold completed draft if essential inputs remain missing |
| 4. Verify facts and usefulness / coordinator | C1, C2, A, B, U1, U2; actual owner decision and draft once supplied | Compare every factual claim with its ledger evidence; verify event details, exact offer terms and CTA usability | Claim-to-source checklist and usefulness check | Each claim supported; conflicts explicitly resolved; CTA and dates usable | Unsupported claim removed/qualified or returned to owner; factual gate remains pending/blocked |
| 5. Polish wording / AI assists, coordinator reviews | C1, S1, U1; fact-checked draft and checklist once supplied | Apply restrained, polished wording while preserving verified details and CTA | Draft v2 with change list | No new factual assertions or loss of offer conditions; factual check repeated for substantive changes | Revert unsupported additions; route changed claims to step 4 |
| 6. Handoff / coordinator, owner approves offer | C1, C2, U2, U3; actual ledger, draft and checks once supplied | Assemble versioned packet; obtain recorded owner offer approval and identify the newsletter submission role | Review packet with approval status and exact next action | All required gates recorded; open issues visible; final terms match approved version | Hold submission while blockers remain; resubmit changed offer to owner |

## Reusable prompts
Use these manually with available AI assistance; no automation or tool access is required. Artifacts described as “once supplied” must actually be provided before the dependent task runs.

1. **Intake:** “Organize C1, C2, A, B, S1, U1, U2 and U3 into a brief and context ledger. Output facts, conflicting versions, style preferences and missing inputs separately. Preserve both A and B; invent nothing. Return a short list of essential questions for the coordinator.”
2. **Owner request preparation:** “Using A, B, C2 and U2, prepare a decision-request checklist for the coordinator: exact price, material responsibility, conditions and missing event/CTA details. Show both source versions without choosing one. Output questions plus blank decision/date/approver fields. If no answer exists, label affected drafting on hold.” The coordinator handles the actual request; AI cannot adjudicate.
3. **Structure/draft:** “Using C1, S1, U1, U2 and U3, output a concise newsletter structure with internal missing-field labels. Use facts only from actual confirmed ledger entries once supplied. Until A/B are resolved, do not draft offer language. After confirmation, output one draft plus a claim-to-source map. Report absent inputs; never invent destinations or use tone as evidence.”
4. **Verification:** “Using the supplied draft, actual updated ledger and recorded owner decision once supplied, check every claim, date, offer condition and CTA against evidence; C1, C2, A, B, U1 and U2 identify the requirements and unresolved risks. Output claim/source/status/correction and audience/CTA checks. Missing evidence is pending or blocked, never passed. An unresolved offer conflict returns to the owner before affected checks proceed.”
5. **Polish:** “Using C1, S1 and U1 plus the fact-checked draft and checklist once supplied, improve clarity and polished tone. Output revised draft and changes. Preserve all facts and conditions. Do not add exclusivity, limited availability, popularity, proven quality or sellout claims. Express the requested style only where wording remains truthful; flag any preference that needs evidence.”
6. **Packet preparation:** “Using C1, C2, U2 and U3 plus actual versioned draft, updated ledger, decision and checks once supplied, assemble artifact/version, provenance, open issues, gate status, approver and exact next action. Do not infer approval. If inputs or checks are absent, list them as pending and hold submission.”

## Quality gates
| Gate | Requirement | Current status / evidence | Severity |
|---|---|---|---|
| Facts and offer | Every claim traced; owner resolves A/B; date/time, location and terms confirmed | BLOCKED: A/B conflict; owner unanswered; U2 missing | Blocks affected drafting and publication |
| Usefulness | Adult audience addressed; newsletter requirements met; clear usable CTA and destination | PENDING: C1 defines audience/channel; U2 and U3 leave operational details missing | Missing essential event/CTA information blocks submission; wording preferences editable |
| Style | Clear, polished wording consistent with verified facts | PENDING: no draft exists; S1 supplies preference, U1 supplies no substantiation | Cosmetic wording editable; unsupported factual implications block acceptance |
| Approval and handoff | Owner approves final offer version; submission role and next action recorded | PENDING: C2 has no approval | Blocks submission; this design grants no publication permission |

The requested “exclusive and in demand” wording cannot imply factual exclusivity or demand without evidence. Coordinator may use restrained phrasing and careful presentation; claiming premium quality also requires support. No gate has been tested or passed.

## Handoff
- Artifact/version: this workflow design v1; future packet should include the labeled structure/draft version, ledger, both A/B versions, dated owner resolution, claim checklist, gate results and change history.
- Provenance: supplied synthetic brief only; no external verification conducted. No confirmed owner response exists.
- Approval role: class owner approves offer details; coordinator owns draft preparation and packet assembly. Newsletter submission role remains to be named.
- Exact next action: coordinator obtains the owner's explicit decision on the two price/material versions and requests date/time, location, registration destination, deadline and newsletter specifications. Record responses before affected drafting resumes.
- Current deliverable is usable for planning; announcement completion and submission remain blocked/pending as listed above. No announcement, account operation or publication is performed.

## Proposed dry run
Not run, as requested. Once the owner has supplied a recorded resolution, coordinator can test the workflow locally with a short dummy draft containing the superseded price/material combination and an unsupported “selling out fast” claim. Success is observable if the checklist identifies both the superseded terms and unsupported demand claim, cites the decision and missing demand evidence, and holds handoff until corrected. This is a proposed low-cost test, with no measured result or improvement claim.
