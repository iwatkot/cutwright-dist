# CutWright static browser distribution

Serve this entire directory from an HTTPS static host. It also runs on http://localhost for local verification.
Keep the assets directory alongside index.html. The app can be mounted at a URL subpath; the desktop installer is downloaded separately from the pinned HTTPS URL below.
Serve .js files as JavaScript and .wasm files as application/wasm. No application backend or upload endpoint is needed.
Use current Chrome or Edge with local storage enabled for browser video export. Opening index.html directly with file:// is not supported.
The desktop download is https://github.com/iwatkot/cutwright-dist/releases/download/v0.2.0-rc.4/CutWright-Setup-0.2.0-rc.4.exe. Its SHA-256 is 637616dbff00ba355c39b8b536e4e8d84b830eb17fd48b3fe2bfdb8f7adf885c.
The included build manifest records source and artifact identities. A successful build alone does not certify release quality.
Keep media originals and save project files separately; local browser storage belongs to the current site and browser profile.
