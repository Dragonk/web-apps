# Mobile parity matrix

| Area | Feature | Status | Evidence / next step |
|---|---|---|---|
| Document | open/edit/save/close | PARTIAL | mobile editor/toolbar present; no device smoke test |
| Document | selection/touch/keyboard | UNKNOWN | requires browser, Android and iOS validation |
| Document | copy/cut/paste/context menu | MISSING | `apps/documenteditor/mobile/src/lib/patch.jsx` disables ContextMenu; separate PR |
| Document | undo/redo/formatting/comments/track changes | PARTIAL | APIs/controllers/locales present; targeted tests needed |
| Spreadsheet | selection/formulas/formatting/sheets | UNKNOWN | source present, no runtime matrix |
| Spreadsheet | context menu | MISSING | ContextMenu disabled in patch |
| Presentation | slides/text/shapes/images/tables | PARTIAL | source present, no device validation |
| Presentation | context menu | MISSING | ContextMenu disabled in patch |
| Visio | editing | MISSING | `isSupportEditFeature = false` |
| All | locale loading | PASS structural | PR2 matches EN key sets; fallback wording needs QA |
| All | offline/error/WebView/Nextcloud | UNKNOWN | integration spans web-apps, DocumentServer, Nextcloud and clients |
