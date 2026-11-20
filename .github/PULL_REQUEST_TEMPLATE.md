## Linked Approved Issue
<!-- Every external PR MUST link an open, maintainer-created Issue. Unlinked PRs are auto-closed. -->
Fixes #

## Summary of Changes
<!-- Explain what changed and why in your own words. -->

## Screenshot or Screencast (Required)
<!-- Drag and drop or paste a screenshot or screen recording demonstrating your terminal output, test run, or dashboard UI changes. PRs without visual verification will not be reviewed. -->

## AI Assistance Disclosure (Required)
- [ ] **No AI tools were used** in preparing this PR.
- [ ] **AI tools were used** (Tool(s) used: `________` | Extent: `________`), and I have personally reviewed, tested, and can explain every line of code in this PR.

## Verification Checklist
- [ ] My GitHub username is listed in `.github/CONTRIBUTORS.td` and I am not blocked (-username).
- [ ] I have attached a screenshot or screencast demonstrating the behavior/fix above.
- [ ] `uv run ruff check .` and `uv run ruff format --check .` pass cleanly.
- [ ] `uv run pytest -q -p no:randomly --ignore=tests/integration --ignore=tests/e2e` passes 100%.