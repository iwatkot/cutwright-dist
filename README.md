# CutWright

CutWright is a free local video editor, available in your browser and as a Windows desktop application.

- [Open the browser editor](https://iwatkot.github.io/cutwright-dist/)
- [Download the Windows release candidate](https://github.com/iwatkot/cutwright-dist/releases/download/v0.2.0-rc.4/CutWright-Setup-0.2.0-rc.4.exe)
- [Release checksums](https://github.com/iwatkot/cutwright-dist/releases/download/v0.2.0-rc.4/SHA256SUMS-0.2.0-rc.4)
- [Open-source editor](https://github.com/iwatkot/cutwright-editor) · [Website source](https://github.com/iwatkot/cutwright-website)

Editing and rendering run on your device. Your media stays local; the editor does not require an account, media uploads, a render service, or a paid AI subscription. External agents connect from their own applications through supported browser or local desktop interfaces.

Open the browser editor, import your local media, and click a library item to add it to the timeline. Save your project file before closing, and use Export to render the movie locally. Use Connect for external-agent setup; client compatibility and any agent-provider charges are separate from the free editor.

Browser export has been verified in desktop Chrome and Edge on Windows. Export time, codec support and project capacity depend on the device and browser. Keep your original media and saved project files separately: project files do not contain the originals, and browser storage belongs to the current site and browser profile. Import matching originals to relink a project on another device or site.

Browser video cards currently use placeholders; video thumbnails and audio waveforms are available in the Windows app. Title appearance depends on installed fonts. The Windows installer is unsigned.

This repository contains the compiled public distribution and its release records. The editor implementation is open source in the separate repository linked above. The website is being prepared for cutwright.cc, and the editor for app.cutwright.cc; the GitHub Pages link remains usable during domain setup. Runtime dependencies retain their licenses and notices, which accompany the browser and desktop distributions.

The current editor no longer has a Windows download button; downloads belong on the separate website. The browser now includes compact settings, Light/Dark/Auto themes, editable Text presets, portrait and landscape formats, pixel guides/grid, timeline markers and context menus, and preview zoom/pan. The release is explicitly a prerelease. Older hashed JavaScript/CSS chunks remain in this static host for visitors with a cached previous index; the current index and distribution manifest identify the RC4 assets.

The pinned Windows download and SHA256SUMS identify the same release. The browser's distribution-manifest.json records its source and artifact identities.
