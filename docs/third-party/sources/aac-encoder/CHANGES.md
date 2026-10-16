# CutWright AAC timing correction

Upstream package: @mediabunny/aac-encoder 1.61.5. The original copyright and MPL-2.0 license are retained.
modified/mediabunny-aac-encoder.mjs is the readable JavaScript module actually consumed by this build, including the original embedded encoder.
upstream/src contains the preferred TypeScript and C source files supplied in that exact installed package. These upstream source files are unmodified.
The correction is applied to the consumed JavaScript module: preserve libavcodec packet PTS (including negative priming), omit packets beyond the actual input end, and trim the final packet duration.
patch-aac-encoder.mjs records the exact substitutions and original/result SHA-256 values. Apply it in a CutWright checkout after installing the recorded package version; it refuses other versions/hashes.
README.md contains the upstream FFmpeg/encoder build instructions. No codec or embedded WASM bytes are changed by the local timing correction.
The package version, registry tarball/integrity, copied-file hashes and upstream repository are recorded in ../../runtime-manifest.json.
