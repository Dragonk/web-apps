# Branches and future PRs (updated after implementation round)

All branches live on `Dragonk/web-apps` (fork). No PRs were created.

| PR | Branch | Scope | Commits | Depends on | Tests | Ready |
|---|---|---|---|---|---|---|
| 1 | `i18n-pl/pr1-i18n-validation` | Generic read-only locale parity checker (PEP8, dataclasses) + 13 unit tests incl. missing-locale detection, malformed JSON, nested structure, non-string values, all placeholder conventions, real fixture | 7 | none | PASS (13 tests) | YES WITH REVIEW |
| 2 | `i18n-pl/pr2-polish-mobile` | Mobile PL: previously missing keys filled and contextual linguistic QA corrections applied (EN->PL), placeholders/markup preserved, 0 missing/0 empty/0 placeholder mismatches on all 4 mobile editors | 13 | PR1 recommended | PASS structural checker; contextual QA corrections applied; additional self-reviewed Polish QA remains in progress | NO — Polish linguistic QA incomplete |
| 3 | `i18n-pl/pr3-polish-desktop` | Desktop PL: 5361 keys added structurally across 11 desktop/embed/forms/formula files; fixed 10 pre-existing placeholder-broken keys (txtWarnUrl {0}, warnNoLicenseUsers %1) that cause `warnNoLicense is undefined`-style runtime issues | 10 | PR1 recommended | PASS: 11/11 desktop surfaces, 0 placeholder mismatches; additional contextual QA corrections applied | NO — contextual Polish QA incomplete |
| 4 | not created | Central runtime English fallback | — | PR1 | — | NOT STARTED |
| 5 | not created | Mobile context menu | — | SDK/touch validation | — | NO |
