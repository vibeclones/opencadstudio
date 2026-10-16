# opencadstudio (Vibeclones mirror)

Hosted browser (WebAssembly) builds of [Open CAD Studio](https://github.com/HakanSeven12/OpenCADStudio), an open-source 2D drafting and 3D modeling app, by [HakanSeven12](https://github.com/HakanSeven12). The code is theirs; this repo only builds and hosts it. The project's own web app is at https://www.opencadstudio.com.

- Latest: `/opencadstudio/latest/`
- A specific version: `/opencadstudio/v<version>/`, for example `/opencadstudio/v2026.41/`
- Version list: `/opencadstudio/versions.json`

Each version is built from an upstream release tag with the same Trunk command the project uses, but with relative paths so it works from a subfolder. A scheduled workflow builds new releases.

Upstream is licensed GPL-3.0. Every version folder includes the license and a `SOURCE.txt` naming the exact upstream tag it was built from; the source is at https://github.com/HakanSeven12/OpenCADStudio.