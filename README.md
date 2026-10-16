# CutWright

CutWright is a free local video editor, available in your browser and as a Windows desktop application.

- [Open the browser editor](https://iwatkot.github.io/cutwright-dist/)
- [Download CutWright for Windows](https://github.com/iwatkot/cutwright-dist/releases/download/v0.1.0/CutWright-Setup-0.1.0.exe)
- [Release checksums](https://github.com/iwatkot/cutwright-dist/releases/download/v0.1.0/SHA256SUMS)

Editing and rendering run on your device. Your media stays local; the editor does not require an account, media uploads, a render service, or a paid AI subscription. External agents connect from their own applications through supported browser or local desktop interfaces.

Open the browser editor, import your local media, and click a library item to add it to the timeline. Save your project file before closing, and use Export to render the movie locally. Use Connect for external-agent setup; client compatibility and any agent-provider charges are separate from the free editor.

Browser export has been verified in desktop Chrome and Edge on Windows. Export time, codec support and project capacity depend on the device and browser. Keep your original media and saved project files separately: project files do not contain the originals, and browser storage belongs to the current site and browser profile. Import matching originals to relink a project on another device or site.

Browser video cards currently use placeholders; video thumbnails and audio waveforms are available in the Windows app. Title appearance depends on installed fonts. The Windows installer is unsigned.

This repository contains the compiled public distribution and its release records. The implementation repository is maintained separately. Runtime dependencies retain their licenses and notices, which accompany the browser and desktop distributions.

The pinned Windows download and SHA256SUMS identify the same release. The browser's distribution-manifest.json records its source and artifact identities.
