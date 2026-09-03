## v0.1.2 — 2026-09-03

Release v0.1.2
- Add a launch-time splash window that shows the app version during cold
  start and the initial catalog load, instead of a blank or flashing window.
- Move the update check into the splash on launches that get one, so it no
  longer duplicates the main window's own boot-time check.
- Restore whether the main window was open across restarts, and skip the
  splash on a launch that resumes into a closed window.
- Restyle the app onto the Inter/iris design system, add header search and
  a peer-roster status indicator, and surface peer catalog-sync timestamps.
- Harden the release pipeline: verify every signing secret is present
  before the build starts, and verify the published update manifest
  (version/url/signature) right after publish.


## v0.1.1 — 2026-08-10

Release v0.1.1
First release of the fontastic tool


