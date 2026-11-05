---
name: ship-check
description: Pre-launch review of a web app or page. Use when the user is about to launch, deploy, ship or share their project, or asks "is this ready?".
---

# Ship Check

Run the app, open it in the browser, and go through this list. Report results as a table: ✅ pass / ⚠️ fix soon / ❌ fix before launch.

## Works
- [ ] Main user flow works end to end (do it yourself, click by click)
- [ ] No errors in the browser console
- [ ] Forms validate and show clear error messages
- [ ] Loading, empty and error states exist
- [ ] Production build runs without warnings that matter

## Looks right
- [ ] 375px mobile, 768px tablet, 1440px desktop — nothing overflows or overlaps
- [ ] Brand colors and fonts from CLAUDE.md are used consistently
- [ ] No leftover placeholder text or lorem ipsum

## Accessible
- [ ] Text contrast ≥ 4.5:1
- [ ] Everything reachable and visible with keyboard (Tab / Enter / Esc)
- [ ] Images have alt text, buttons have labels

## Findable & safe
- [ ] Page title, meta description, favicon, Open Graph image
- [ ] No API keys or secrets in frontend code or the repo
- [ ] Environment variables set in the hosting dashboard

Fix every ❌ (ask first if the fix is big), then re-run the check.
