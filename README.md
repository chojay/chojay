# Jay Cho

Process and materials engineer. ALD PhD (UCLA, thin-film solid electrolytes), plasma etch on 5-14 nm nodes at Lam Research, thin-film process integration at Apple. I build AI tooling for fab and lab data and write down where it works and where it fails.

Everything here is nights-and-weekends work on public data and public physics. Nothing uses employer data, tools or systems.

## Start here

- **In-situ Etch Signal Lab** (link on first public commit, October 2026): simulated thin-film reflectance during an etch with injected drift, PCA/PLS/EWMA baselines, ML on time-based and held-out-chamber splits, an MCP agent whose one write tool is dry-run by default, and a 50-case eval with false-alarm and miss rates.
- **The hull-swap bug** in [side-quests / mp-interface-reactions](https://github.com/chojay/side-quests/blob/main/computational-materials/mp-interface-reactions/README.md): a silently changed API default (mixed GGA/R2SCAN hull) that corrupted reaction energies until a literature cross-check caught it.
- **[NIIMBOT GOTCHAS.md](https://github.com/chojay/side-quests/blob/main/hardware-tools/niimbot-labelmaker/GOTCHAS.md)**: visually identical printers, different firmware dialects; one returns byte-perfect success traces while printing blanks.
- **[mos_r.py](https://github.com/chojay/side-quests/blob/main/medical-imaging/gma-video-pipeline/src/gma_pipeline/mos_r.py)**: a scorer that declares three subscales NOT_COMPUTABLE rather than guessing.

## How I work

Old APC methods (PCA, PLS, EWMA) get a fair run before any model. Every number in a README is regenerable from the repo. Agents get read tools freely and write tools behind a dry run and a human approval.

Published in public since August 2026. Earlier repos were coursework and are private.

LinkedIn: https://www.linkedin.com/in/chojay | Dissertation: https://escholarship.org/uc/item/2vr3z5pd
