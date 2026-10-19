## v0.2.0 — 2026-10-19

Fontastic 0.2.0
- Colleagues through the office server: "Share my fonts with the office", Ask colleagues in search, and Get, which brings a colleague's font through the organisation library. Needs an office build of the app and the office server 0.3.0; until then it stays inactive.
- The organisation library downloads to this Mac: progress, pause, download all, and Get, in Locations.
- The LAN peer search ("Ask peers", mDNS) is retired: Macs no longer talk to each other directly.
- Launch: the splash never leaves the app without a window, and an update found at launch is waited for, not cut short.
- The server's state shows in the header; account checks no longer hang on Connecting.
- Many fixes to adding folders to the organisation library.


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


