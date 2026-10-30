# Turtle Club Bedrock Companion v1.3.0

Multi-world local-first PWA. Four-card home, Library, God Gear, World Tools, Settings and backup/restore.

## Safe deployment from Android
1. On the CURRENT installed V1.2.1 app, export a fresh backup JSON and keep it safe outside the browser.
2. Download this ZIP and extract it. Upload the SIX deployment files to the ROOT of GitHub repository `fideo-byte/turtle-club-bedrock-companion` on `main`, replacing existing files, then commit.
3. Open the deployed URL in the SAME browser installation; do not clear browser data or uninstall.
4. Verify world profile, projects, tasks, librarian trades and God Gear. Export another backup after verifying.
5. On a separate browser/device with no existing local data, verify the app starts with an unnamed empty world (no personal seed).

## Data and privacy
V1.3 saves to `tc-worlds-v13`, preserving the legacy `tc-world-db-v12` key unchanged. Library (`tc-libs`) and God Gear (`tc-gear-v11`) remain device-wide for this release. There is no sync and GitHub Pages is public. The app does not automatically send seeds to external finder sites; it provides copy controls.

## Known limitations
World/player-specific Library and God Gear are deferred. External finder URLs open their standard home pages; URL parameters have not been validated. Android hardware back behavior and storage migration require real-device acceptance testing before treating this as a verified stable release.
