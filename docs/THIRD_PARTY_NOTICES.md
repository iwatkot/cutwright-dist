# Browser runtime components

The following components retain their own licenses. Their installed versions and license texts accompany this distribution.

- react 18.3.1: MIT; [license text](licenses/react.txt); source repository: https://github.com/facebook/react.git
- react-dom 18.3.1: MIT; [license text](licenses/react-dom.txt); source repository: https://github.com/facebook/react.git
- scheduler 0.23.2: MIT; [license text](licenses/scheduler.txt); source repository: https://github.com/facebook/react.git
- zustand 5.0.15: MIT; [license text](licenses/zustand.txt); source repository: git+https://github.com/pmndrs/zustand.git
- mediabunny 1.61.5: MPL-2.0; [license text](licenses/mediabunny.txt); source repository: git+https://github.com/Vanilagy/mediabunny.git
- @mediabunny/aac-encoder 1.61.5: MPL-2.0; [license text](licenses/mediabunny-aac-encoder.txt); source repository: git+https://github.com/Vanilagy/mediabunny.git
- @ffmpeg/ffmpeg 0.12.15: MIT; [license text](licenses/ffmpeg-ffmpeg.txt); source repository: git+https://github.com/ffmpegwasm/ffmpeg.wasm.git
- @ffmpeg/types 0.12.4: MIT; [license text](licenses/ffmpeg-types.txt); source repository: git+https://github.com/ffmpegwasm/ffmpeg.wasm.git
- @ffmpeg/core 0.12.10: GPL-2.0-or-later; [license text](licenses/ffmpeg-core.txt); source repository: git+https://github.com/ffmpegwasm/ffmpeg.wasm.git

The AAC extension includes a libavcodec-based encoder. Its upstream build instructions and dependency details are included in licenses/aac-encoder-build-and-dependencies.md.
The local AAC JavaScript timing correction, if present, is included as licenses/aac-encoder-local-patch.mjs, with the upstream attribution and a record of the changes. Dependency entry hashes are recorded in distribution-manifest.json.
The local Mediabunny MP3 sample-entry correction, if present, is included as licenses/mediabunny-mp3-local-patch.mjs, alongside the modified demuxer source and JavaScript under the original MPL-2.0 license. It recognizes QuickTime MP3 tracks without changing packet data.
The unmodified FFmpeg WebAssembly core has the license of FFmpeg and its compiled external libraries. See https://ffmpegwasm.netlify.app/docs/faq/#what-is-the-license-of-ffmpegwasm and the upstream source/build scripts at https://github.com/ffmpegwasm/ffmpeg.wasm.
