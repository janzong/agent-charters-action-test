# agent-charters-action-test

**Intentional test fixture.** This repository exists to verify that the published
action tag `janzong/agent-charters@v1` resolves and runs in a *consumer* repo.

- Job `report-only` must be green (this is the documented default).
- Job `enforce` must be RED by design: it asks for categories the fixture does
  not have (`fail-on-missing: 'workflow,gotchas'`), which proves the opt-in
  gate really fails the job instead of silently reporting.
