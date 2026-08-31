# Agent Collaboration Control

A portable control framework for consequential multi-agent work: explicit human authority, one writer per mutable surface, append-only transition evidence, independent review, liveness checks, and bounded succession.

```bash
npx skills add AntreasAntoniou/agent-collaboration-control
python3 scripts/validate_transition_event.py \
  --policy assets/collaboration-policy.example.json \
  assets/transition-event.example.json
```

The framework does not grant authority or run agents. A project must bind real roles, budgets, mutable surfaces, and approval rules before live operations.

## Test

```bash
python3 -m unittest discover -s tests
```

MIT licensed.
