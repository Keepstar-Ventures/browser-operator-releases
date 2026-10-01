# Proxyhand releases

# proxyhand releases

Release artefacts and the agent-executable install document for proxyhand. No source lives here.

Each release carries: INSTALL.md, install.mjs, bop-extension-<tag>.zip, bop-runtime-<tag>.tgz, SHA256SUMS.
Verify with: shasum -a 256 -c SHA256SUMS

Install: fetch install.mjs from the release and follow INSTALL.md.

## Licence


The artefacts in this repository are proprietary: Copyright (c) 2026 Keepstar Ventures, all rights reserved, under the terms in [`LICENSE`](LICENSE). Every release carries the same `LICENSE` as an asset beside its archives (listed in that release's `SHA256SUMS`) and at the root of both archives. Being able to download an artefact here is not permission to use it: the artefacts may be used only with a valid licence key issued by Keepstar Ventures, and the `LICENSE` (the terms of use) and the licence key (the credential that activates one installation, entered at install Step 8 in `INSTALL.md`) are different things — neither grants what the other withholds. No redistribution, modification or reverse engineering beyond what applicable law permits; no warranty.

## Renamed on 2026-10-01

This repository was `browser-operator-releases` and the product was `browser-operator`; GitHub redirects the old URLs, and a pre-rename `install.mjs` keeps fetching through the redirect. From v1.0.0 the artefacts are `proxyhand-extension-vX.Y.Z.zip` and `proxyhand-runtime-vX.Y.Z.tgz`, the tools are `ph_*`, the environment is `PH_*` and the install directory is `.proxyhand`; the upgrade procedure ships with the release as INSTALL.md and the runbook in the source.
