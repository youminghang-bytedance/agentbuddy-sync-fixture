# AgentBuddy sync fixture

Controlled synthetic fixtures for AgentBuddy GitHub synchronization tests.

The sync source tracks the default branch `main`. Test inputs live in separate
run-owned directories under `agentplugin-e2e/`. Only synthetic plugin files belong
here; do not add credentials, private source code, or production data.

This initialization is not a completed synchronization test. Runtime evidence
remains in the Registry E2E `runs/` directory.
