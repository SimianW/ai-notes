# Experiments

Each experiment lives in its own folder: `YYYY-MM-slug/` (e.g., `2026-11-minigpt/`).

## Suggested layout per experiment

```text
2026-11-minigpt/
├── README.md          # Goal, setup, key observations, results
├── pyproject.toml     # Or requirements.txt (so old experiments stay reproducible)
└── notebook.ipynb     # Or src/*.py
```

Tip: avoid committing huge inline notebook outputs (e.g., large base64 plots or long training logs) so diffs stay readable.
