# Use the current tracker

Read the live tool schema rather than copying a provider's method name into another host. Never embed credentials or account-specific IDs in this package.

## Notion-style page/database tracker

- Find the authorized database/page and its existing work item. Read the database schema and page before editing.
- Copy exact property names and allowed status values from that schema. Preserve relation IDs; title similarity is insufficient identity.
- Prefer a targeted body edit and supported property update. If owner or next action has no property, use existing body prose.
- If the operation is asynchronous, wait for its supported terminal result before dependent actions, then fetch the page.
- Compare the changed text, state, parent and unresolved obligations with the requested operation. Preserve child-page blocks and unrelated content.

## GitHub-style work item

- Read the identified repository and Issue/PR, including relevant body/comments and current state. Do not treat the Issue representation of a PR as a second work unit.
- Use existing relationships and work-item identity. A link does not prove the linked object's state; read it when that state matters.
- Record only authorized, audience-appropriate task evidence. Never publish private source bodies, local paths, credentials or raw logs just to fill a template.
- Read back the actual body/comment/state and its canonical link. Closure is a separate action under the current workflow, not a side effect of writing a progress note.

## Other trackers

Map the same needed operations to their supported capabilities: find, read, create if necessary, update and readback. Missing capabilities limit only the dependent operation. Do not invent endpoints, status names, connectors or permissions.

## Evidence to retain

Keep the intended update, actual tool outcome, readback and any mismatch in the existing work record. A local mock can test a helper but cannot establish that the real tracker saved a change. Report a simulated case as simulated.
