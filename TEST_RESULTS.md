# Test results

- PR1: `python3 -m unittest discover -s translation/tests -v` — PASS (2 tests).
- PR1: `git diff --check` — PASS.
- PR2: locale checker — mobile missing keys 0; placeholder mismatches and formula exceptions remain — PARTIAL.
- PR2: `git diff --check` — PASS.
- Full build — BLOCKED BY ENVIRONMENT: sibling SDK/DocumentServer and dependencies unavailable.
- Real device/WebView/touch tests — BLOCKED BY ENVIRONMENT.
