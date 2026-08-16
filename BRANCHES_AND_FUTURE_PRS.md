# Branches and future PRs (updated after implementation round)

All branches live on `Dragonk/web-apps` (fork). No PRs were created.

| PR | Branch | Scope | Commits | Depends on | Tests | Ready |
|---|---|---|---|---|---|---|
| 1 | `i18n-pl/pr1-i18n-validation` | Generic read-only locale parity checker (PEP8, dataclasses) + 7 unit tests incl. missing-locale detection, malformed JSON, nested structure, non-string values, all placeholder conventions, real fixture | 1 | none | PASS (7 tests) | YES WITH REVIEW |
| 2 | `i18n-pl/pr2-polish-mobile` | Mobile PL: 1296 previously missing keys translated (EN->PL), placeholders/markup preserved, 0 missing/0 empty/0 placeholder mismatches on all 4 mobile editors | 2 | PR1 recommended | PASS structural checker; QA of wording needed | NO — human Polish QA |
| 3 | `i18n-pl/pr3-polish-desktop` | Desktop PL: 5361 keys added across 11 desktop/embed/forms/formula files; fixed 10 pre-existing placeholder-broken keys (txtWarnUrl {0}, warnNoLicenseUsers %1) that cause `warnNoLicense is undefined`-style runtime issues | 1 | PR1 recommended | PASS: 11/11 desktop surfaces, 0 placeholder mismatches | YES WITH REVIEW |
| 4 | not created | Central runtime English fallback | — | PR1 | — | NOT STARTED |
| 5 | not created | Mobile context menu | — | SDK/touch validation | — | NO |
