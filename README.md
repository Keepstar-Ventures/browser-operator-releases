# browser-operator releases

Release artefacts and the agent-executable install document for browser-operator. No source lives here.

Each release carries: INSTALL.md, install.mjs, bop-extension-<tag>.zip, bop-runtime-<tag>.tgz, SHA256SUMS.
Verify with: shasum -a 256 -c SHA256SUMS

Install: fetch install.mjs from the release and follow INSTALL.md.

## Licence


The artefacts in this repository are proprietary: Copyright (c) 2026 Keepstar Ventures, all rights reserved, under the terms in [`LICENSE`](LICENSE). Every release carries the same `LICENSE` as an asset beside its archives (listed in that release's `SHA256SUMS`) and at the root of both archives. Being able to download an artefact here is not permission to use it: the artefacts may be used only with a valid licence key issued by Keepstar Ventures, and the `LICENSE` (the terms of use) and the licence key (the credential that activates one installation, entered at install Step 8 in `INSTALL.md`) are different things — neither grants what the other withholds. No redistribution, modification or reverse engineering beyond what applicable law permits; no warranty.
