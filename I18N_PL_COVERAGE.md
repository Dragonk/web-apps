# Polish locale coverage

Structural baseline from upstream SHA `73bdfbb0b74ce5a778505135bb8845c2fd400932`. Identical values are reported separately and are not counted as translated.

| Surface | EN | PL | Missing | Stale | Empty | Identical | Placeholder mismatches | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `apps/pdfeditor/main/locale/en.json` | 3080 | 1360 | 1720 | 0 | 0 | 11 | 2 | 44.1% |
| `apps/spreadsheeteditor/main/locale/en.json` | 5294 | 3567 | 1727 | 0 | 0 | 64 | 2 | 67.3% |
| `apps/spreadsheeteditor/main/resources/formula-lang/en.json` | 514 | 514 | 1 | 1 | 0 | 68 | 0 | 99.8% |
| `apps/spreadsheeteditor/mobile/locale/en.json` | 867 | 71 | 796 | 0 | 0 | 4 | 0 | 8.2% |
| `apps/spreadsheeteditor/mobile/locale/l10n/functions/en.json` | 514 | 514 | 1 | 1 | 0 | 68 | 0 | 99.8% |
| `apps/spreadsheeteditor/embed/locale/en.json` | 59 | 56 | 3 | 0 | 0 | 0 | 0 | 94.9% |
| `apps/documenteditor/main/locale/en.json` | 4374 | 3652 | 722 | 0 | 0 | 64 | 1 | 83.5% |
| `apps/documenteditor/forms/locale/en.json` | 212 | 208 | 4 | 0 | 0 | 2 | 1 | 97.6% |
| `apps/documenteditor/mobile/locale/en.json` | 812 | 668 | 144 | 0 | 0 | 12 | 1 | 82.1% |
| `apps/documenteditor/embed/locale/en.json` | 77 | 73 | 4 | 0 | 0 | 2 | 0 | 94.8% |
| `apps/visioeditor/mobile/locale/en.json` | 192 | 54 | 138 | 0 | 0 | 2 | 1 | 27.6% |
| `apps/visioeditor/embed/locale/en.json` | 60 | 54 | 6 | 0 | 0 | 0 | 0 | 90.0% |
| `apps/visioeditor/main/locale/en.json` | 481 | 424 | 57 | 0 | 0 | 8 | 1 | 87.9% |
| `apps/presentationeditor/embed/locale/en.json` | 59 | 56 | 3 | 0 | 0 | 0 | 0 | 94.9% |
| `apps/presentationeditor/main/locale/en.json` | 3574 | 2471 | 1103 | 0 | 0 | 49 | 3 | 69.1% |
| `apps/presentationeditor/mobile/locale/en.json` | 546 | 328 | 218 | 0 | 0 | 0 | 1 | 59.9% |

Mobile target branches remove missing mobile keys structurally, but English fallback values require Polish QA before production claim.
