# Task registration and tracking

## Use the implementation

The runnable entry for an agent is [SKILL.md](SKILL.md). It directs the agent to perform the task with existing authorized tools; it is not a daemon or a deterministic classifier. An LLM/agent host capable of reading skill files and using the required tools is needed. No sibling repository is required.

1. Obtain this repository through your normal authorized Git workflow, retaining all package files together. Review the skill and resources before adoption.
2. Install the repository folder as a skill named `task-tracking` through your host's documented skill installer or skill directory. Do not overwrite an existing customized installation; compare and preserve it first. Hosts without skill discovery can explicitly read `SKILL.md` and its task-relevant resources from the checked-out folder.
3. Invoke it on an actual authorized work item: “Use $task-tracking to reconcile this task with the existing authorized tracker, update the material change, and read back the saved item without duplicating it.” Supply the original goal, existing work-item/destination reference and permitted effects. Let the agent recover available facts rather than supplying fictitious observations.
4. Inspect the actual output and tool effects. A successful file load or syntax check is not actual-use acceptance. Missing tools/authority must be reported precisely rather than replaced with a simulated success.

Updates replace only this package after review; preserve customization, active obligations and history. Removing its skill folder stops future discovery after the host refreshes, not obligations or pending work already created. Follow the host's documented reload behavior; no current-session activation is promised.

Implementation and real-use evidence belong on the [owning work item](https://github.com/jack61714z/task-tracking/issues/1) and its linked candidate review. Until those observations are saved, actual use remains pending. Explicit invocation does not prove automatic selection or background event coverage.


## Purpose and adoption boundary

Keep existing tasks current while authorized work proceeds: find or register the real work unit, record material changes, and verify saved state. Use the team's existing tracker, including Notion when already used. No new tracker, common schema/runtime, template, review method or companion document/version is required.

This repository includes an independently invocable agent skill. The package is not activated merely by publication. It grants no tool access or standing permission and does not establish automation. Use and redistribution are governed by the MIT license in this repository. Current privacy, writer, approval and other host requirements remain effective. Progressive Investigation (PI), an investigation method, and an existing Chat–Codex handoff system (C2C) remain independent; their active contracts are unchanged.

## Map only the existing host operations needed

Here PI means Progressive Investigation, an investigation method, and C2C means Chat/Codex communication tooling. Neither is required for this tracking guide.

Recover these facts from authorized tools and task context first. Ask only for consequential facts or authority still missing:

- Actual project/database or other destination and existing task identity.
- Verified parent/slice and linked Issue/PR relationships.
- Responsible actor and supported find/create/update/read operations under current authority.
- Existing status values and places for goal, scope, owner, blocker, next action, result/review evidence and remaining obligations. Ordinary task-body text is sufficient when a custom field is absent.
- The actual intake, material-update and closure transitions where the actor performs registration/update.
- Whether coverage includes only this workflow's tasks or a supported existing event source also detects changes elsewhere.

Preserve any identity, candidate/revision, source and authority metadata material to correctness. Existing tracker formatting and required identifiers take precedence over generic labels. Tool availability, saved instructions or a proposed schema do not authorize writes or sharing. Carry only authorized information to each destination and audience.

Map required work-order, execution-result and review preservation separately from tracker state. The existing project workflow identifies the authoritative destination, actual publication owner, required save points, readback and continuation after incomplete persistence. A tracker entry or evidence link does not replace required full records. This mapping uses existing project instructions and tools; it is not a mandatory shared adapter or a requirement to use GitHub.

## Register once and update during work

At intake, find the task using stable identity and verified relationships. Reuse it; create only if it is absent and creation is authorized. Repeated requests, clarifications, similarly titled items and tracker updates do not automatically define new work units.

At material scope/dependency changes, changed owner/blocker/next action, accepted results or actual closure, update the existing item through the supported authorized operation. Carry out these routine updates as part of the authorized workflow rather than waiting for another reminder. Missing standing authority or host capability blocks only its dependent effects; identify that exact dependency.

Record decisions already made by the responsible process. Updating a status is not itself evidence that work passed review, a PR merged, a result was delivered, or a parent outcome was achieved. Do not infer such facts from an intended next action.

A closed slice does not close its unfinished parent. Preserve the parent's remaining owner/next action. Closure relationships and review/retrospective references may come from existing Issue/PR history and ordinary records; they do not require a particular review policy or template.

## Verify persistence and handle uncertainty

Read back the actual saved content and state before claiming successful registration/update. Preserve actual item references and evidence; never invent a successful write or a task link.

If creation or update has an uncertain result, reconcile current state before retrying. Do not create a duplicate simply because the first response was unclear. This is a workflow responsibility, not a claim of transactional duplicate prevention.

If saving is blocked or incomplete, state what is not persisted, the missing capability/authority and the next owner/action. Continue unrelated authorized work. Keep delivered artifacts, accepted outcomes and saved tracking state as separate claims where necessary.

## Independent use and maintenance

Example: an existing team accepts a document revision using its own review procedure. The tracker actor updates the existing task's status and evidence link, reads it back, and leaves the parent open for its unfinished chapter. No new review axes, work-order labels, closure policy or runtime are required.

This document owns registration/update timing, identity reconciliation and persistence verification. It does not decide whether work should be accepted, authorize closure, judge lesson quality, prescribe seven-axis review, or detect all external events. Equivalent facts from any authorized existing workflow are sufficient. Other active duties remain effective under their own authority.

Update this guide independently. Do not change tracker fields, status semantics, permissions or other installed contracts merely to match it. No mandatory migration or synchronized sibling version is created.

Automatic registration/update can be claimed only after observing the configured host perform the supported operations. This document supplies responsibility, not a background service, event hook or proof of actual behavior. No experiment or document-revision efficacy result is claimed.

Replace or remove this guide independently under the active host's authority. Retain task records, history and open obligations, including tracking duties required elsewhere. Removal does not change tracker fields, permissions or sibling guidance.

## Revision, maintenance and license

Initial public document revision: 2026-10-12. Maintainer: jack61714z. Corrections may be proposed through this repository. Revised independently; sibling versions are not prerequisites. Publication does not activate this guidance, and behavioral efficacy remains unverified.

This document includes adapted policy and record material from [codex-with-chatgpt](https://github.com/jack61714z/codex-with-chatgpt), licensed under MIT, Copyright (c) 2026 codex-with-chatgpt contributors. New contributions are Copyright (c) 2026 jack61714z. See [LICENSE](LICENSE) for the complete MIT terms and preserved notices.

