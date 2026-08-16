# Mobile issues audit

| Issue | Assessment | Evidence | Recommendation |
|---|---|---|---|
| #54 | UNKNOWN / cross-repo | Nextcloud mobile editing cannot be assigned from web-apps alone | reproduce and split by owning repo |
| #88 | reproducible from code | all mobile patches disable ContextMenu | compatibility-focused future PR, device test |
| #131 | partially mitigated | mobile PL had 796 missing keys; PR2 fills keys, runtime untested | PR1 + PR2 + central fallback |
| #143 | partially addressed | theme config/assets contain mobile logo support | visual/browser/device review |
| #161 | partially mitigated | mobile missing keys filled; runtime fallback absent | regression test + fallback PR |
| #185 | UNKNOWN | issue metadata not bundled/local | manual GitHub review |
