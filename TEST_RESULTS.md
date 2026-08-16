# Test results (updated)

| Branch | Command | Result | Notes |
|---|---|---|---|
| pr1 | `python3 -m unittest discover -s translation/tests -v` | PASS | 12 tests: nested missing/stale/empty/identical, placeholder conventions ({0}, %1, %s, %d, ${x}, {{x}}), empty+non-string values, invalid nested structure, malformed JSON, missing locale file detection, real EuroOffice mobile fixture |
| pr1 | `git diff --check` | PASS | |
| pr2 | checker `--language pl` | PASS mobile | DE/PE/SSE/VE mobile: missing=0, empty=0, invalid=0, placeholder_mismatches=0; identical (to EN) = 13/4/13/4; reviewed technical/short labels (technical/short terms, list in report) |
| pr3 | checker `--language pl` | PASS desktop | 11/11 desktop+embed+forms+formula surfaces: missing=0, placeholder_mismatches=0; mobile files still FAIL in pr3 (out of scope, covered by pr2) |
| pr3 | `git diff --check` | PASS | 5378 insertions, 28 deletions (additive diff) |
| all | full build | BLOCKED BY ENVIRONMENT | requires npm install, sibling SDK/DocumentServer |
| all | real device/WebView tests | BLOCKED BY ENVIRONMENT | |
