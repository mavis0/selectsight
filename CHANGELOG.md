# Changelog

All notable user-facing updates to the **SelectSight** Chrome extension and **[selectsight.lol](https://selectsight.lol/)** web tools are documented here.

---

## [1.0.0] - 2026-11

### Added
- **Browser Image Tools Suite**: Launched four no-install browser tools powered by local WebAssembly OCR:
  - [Image to Text](https://selectsight.lol/image-to-text) — 100% local plain-text extraction with zero uploads and no sign-up.
  - [Image to Excel](https://selectsight.lol/image-to-excel) — Local OCR paired with AI table reconstruction and numeric `.xlsx` export.
  - [Image to Word](https://selectsight.lol/image-to-word) — Local OCR paired with AI document structuring and editable `.docx` export.
  - [Translate Image](https://selectsight.lol/translate-image) — Local OCR and in-place translated image rendering with full-resolution PNG download.
- **Shared Account & Google Sign-In**: Added Google OAuth sign-in alongside 6-digit email verification, sharing credit balances across the extension and website tools.
- **20 Recognition Languages**: Added automatic on-demand model caching across 20 OCR languages while keeping English + browser language ready out of the box.
- **In-Place Free Translation**: Added online text translation directly from image selections and screenshot captures (400 chars/request for guests, 2,000 chars/request when signed in, 0 credits used).

### Changed
- Standardized default screenshot shortcuts to `Option + S` (macOS) / `Alt + S` (Windows), with `Option + X` / `Alt + X` as backup bindings.
- Unified welcome trial allowance to 5 one-time shared credits upon first verified sign-in, plus 3 daily free conversions per IP across web Word, Excel, and Translate Image tools.

---

## [0.2.0] - 2026-09

### Added
- Interactive [How to use](https://selectsight.lol/how-to-use) practice page with live image and paused-video sandboxes.
- Optional cloud structured exports (`.docx` / `.xlsx`) and SelectSight Pro monthly/annual plans.
- Published [Refund Policy](https://selectsight.lol/refund), [Privacy Policy](https://selectsight.lol/privacy), and [Terms of Use](https://selectsight.lol/terms).

---

## [0.1.0] - 2026-09

### Added
- Initial release of the SelectSight Chrome extension featuring local hover-and-drag text selection on webpage images, paused HTML5 video frames, and manual region screenshots.
