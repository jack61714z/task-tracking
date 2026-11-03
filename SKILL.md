---
name: task-tracking
description: Use when an authorized task must be found, registered, deduplicated, updated or closed in an existing tracker; confirm the real work state and saved item before acting.
---

# Task tracking

Perform the tracker operation, not just advice about it. Use the current task's authorized tools and destination. This skill grants no access, publication permission, or review authority. It works independently of other skills.

## Establish the operation

If the work originated in Chat/Codex sessions, treat session IDs and model receipts as evidence for the stable work-item identity, not new tracker items. Verify whether the actual parent completed and the responsible reviewer accepted the result before closing an item; a child's `task_complete`, model claim or saved draft does not close its parent. Keep private raw traces and local paths out of public tracker updates.

Read the user's actual outcome, current decision and existing task reference. Find the matching work item by stable identity and verified relationships. If no reference is supplied, search the authorized tracker before proposing creation. A repeated request, clarification or similarly titled item is not automatically a new task.

Read the destination's current schema and supported operations. Map its existing status values, parent relation and locations for outcome, owner, blocker, next action and evidence. Use ordinary body text for facts without custom fields; do not add schema. Use [the host-operation guide](references/host-operations.md) when the tool requires a concrete mapping.

Confirm that the information, destination and write are authorized. Tool access alone is insufficient. If only one field or operation is blocked, report it and continue independent authorized work.

## Execute

1. Read the matching item and relevant parent. Determine what materially changed from actual evidence. Track the responsible process's decision; do not independently turn an unreviewed result into accepted work.
2. Reuse the item. Create only for an absent, genuinely distinct work unit when authorized. Preserve existing parent/slice relationships. Multiple repository slices can remain in one item's body if the host already represents them that way; this skill does not require new children.
3. Apply the smallest authorized update at intake, changed scope/owner/blocker, accepted result, or actual closure. Include the next concrete action and who owns it. Preserve unrelated content and historical evidence.
4. Read the actual saved item. Compare the intended changed content, state and parent relationship with the result. An API acceptance, draft, task card or returned ID alone does not prove persistence.
5. Report the verified item link, actual saved change, remaining obligations and next action. Keep artifact delivery, review acceptance and tracker persistence distinct.

If a write times out or returns an uncertain outcome, read/search the intended destination before retrying. If the write already took effect, continue from that state. If absent, use a supported retry only within the original authority. If ambiguous, retain the ambiguity instead of making a duplicate. Do not claim transactional exactly-once behavior.

## Completion and continued use

Close only the work unit whose actual completion has been accepted under its existing process. Leave an unfinished parent open with its next owner/action. An Issue/PR closure does not prove deployment or parent completion.

When invoked again for the same work, recover the same identity and update it rather than replaying creation. If no material change exists, say so and do not write merely to show activity.

For workflows requiring full work orders, execution results or reviews elsewhere, preserve their owning destination and publication responsibility. A tracker link or summary does not substitute for those records.

This is an agent-operated skill, not a background listener. State whether the observed invocation was explicit or automatically selected by the host. Do not claim coverage of events the host never delivered. Removal of this skill does not delete task history or cancel outstanding duties.
