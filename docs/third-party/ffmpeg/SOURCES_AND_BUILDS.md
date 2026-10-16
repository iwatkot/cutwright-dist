# FFmpeg components and upstream build references

CutWright does not modify these codec binaries. This directory records their installed-package identity, license texts and upstream source/build references; it does not rebuild or download FFmpeg.

## Browser audio tempo core

- Installed @ffmpeg/core version and registry integrity are recorded in ../runtime-manifest.json; the wrapper and core have distinct licenses.
- The 0.12.10 core upstream source/build configuration: https://github.com/ffmpegwasm/ffmpeg.wasm/tree/v0.12.10
- That Dockerfile pins FFmpeg n5.1.4 and lists external-library repositories/versions: https://github.com/ffmpegwasm/ffmpeg.wasm/blob/v0.12.10/Dockerfile
- FFmpeg source: https://github.com/FFmpeg/FFmpeg/tree/n5.1.4
- Core build scripts: https://github.com/ffmpegwasm/ffmpeg.wasm/tree/v0.12.10/build
- Core build instructions: https://ffmpegwasm.netlify.app/docs/contribution/core/
- Upstream license explanation: https://ffmpegwasm.netlify.app/docs/faq/#what-is-the-license-of-ffmpegwasm

## AAC extension

- @mediabunny/aac-encoder 1.61.5 embeds a libavcodec-based AAC encoder.
- Its supplied C/TypeScript source and complete upstream build instructions accompany this distribution under ../sources/aac-encoder/.
- The local correction changes JavaScript packet timing only; the embedded encoder bytes are unchanged.

## Desktop executable

- Installed ffmpeg-static package: 5.3.0; binary release tag: b6.1.1.
- native-package-README.md describes the upstream binary suppliers and build/release links.
- native-binary-README.txt and native-binary-LICENSE.txt, when supplied by the installed package, retain the binary supplier version, source commit, external-library list and license.
- FFmpeg source and legal information: https://ffmpeg.org/download.html and https://ffmpeg.org/legal.html

Electron also ships its own LICENSE and LICENSES.chromium.html alongside the installed executable; retain those files when redistributing it.
