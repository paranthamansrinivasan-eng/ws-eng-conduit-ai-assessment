---
key: ws-eng-cli/857
repositories:
  - trilogy-group/ws-eng-conduit-ai-assessment
subtasks: false
---

# ws-eng-cli/857 — Test Plan for Forked Repository

## Decisions

1. **Testing project picker functionality**
   - Decision: Use this dummy plan to test the new project picker feature
   - Rationale: This repository is not in Team Roster, so it will trigger the fallback flow

## Plan

This is a test plan to verify that the `save-plan` command works correctly when:
1. The repository is NOT in Team Roster
2. The user needs to select a project via picker
3. The selection is cached in `.wseng`

## Breakdown

- Test the project picker
- Verify caching works
- Test `--project` flag bypass
