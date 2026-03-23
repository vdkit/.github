<div align="center">

	# VDK (Vibe Development Kit)

	**Build AI context once. Run it everywhere.**

	[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
	[![Schema](https://img.shields.io/badge/AI_Context_Schema-v3.0-6366f1.svg)](https://github.com/vdkit/ai-context-schema)
	[![CLI](https://img.shields.io/badge/CLI-Execution_Core-0ea5e9.svg)](https://github.com/vdkit/VibeKit-VDK-CLI)
	[![Hub](https://img.shields.io/badge/Hub-vdk.tools-8b5cf6.svg)](https://vdk.tools)

</div>

---

## Overview

VDK is an ecosystem for **portable AI coding context**. Instead of rewriting instructions for every tool, VDK defines canonical blueprint semantics and adapts them across Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Windsurf, Cline, and more.

### Why VDK

- One canonical contract for AI context behavior
- Deterministic adaptation across platform-specific carriers
- Curated retrieval that prioritizes signal over noise
- Explicit conversion outcomes: `lossless`, `lossy`, `unsupported`

## Ecosystem Components

| Component | Purpose | Repo / URL |
|---|---|---|
| `ai-context-schema` | Canonical schema and behavior contract | <https://github.com/vdkit/ai-context-schema> |
| `VDK-Blueprints` | Curated blueprint inventory | <https://github.com/vdkit/VDK-Blueprints> |
| `VDK-CLI` | Retrieval, adaptation, deployment engine | <https://github.com/vdkit/VibeKit-VDK-CLI> |
| `VDK-Hub` | Discovery, packaging, and distribution UX | <https://github.com/vdkit/VDK-Hub> |
| `VDK-Wiki` | Documentation and implementation guidance | <https://wiki.vdk.tools> |

### Operating order

1. `ai-context-schema`
2. `VDK-Blueprints`
3. `VDK-CLI`
4. `VDK-Hub`
5. `VDK-Wiki`

Hub and docs mirror CLI runtime semantics; they do not redefine them.

## Blueprint Taxonomy

Canonical `kind` values:

- `project-memory`
- `conditional-rule`
- `skill`
- `command`
- `workflow`
- `agent`
- `hook`
- `mcp-integration`
- `plugin-distribution`

Retrieval defaults:

- Blend `L0-L3` (foundation to org/workspace specific)
- Exclude `L4` provenance variants by default
- Surface explicit adaptation classification on conversion/deploy

## Quick Start

<table>
	<tr>
		<td align="center" width="25%"><strong>1. Explore</strong><br/>Browse curated blueprints</td>
		<td align="center" width="25%"><strong>2. Select</strong><br/>Choose canonical kind + specificity</td>
		<td align="center" width="25%"><strong>3. Deploy</strong><br/>Apply via VDK CLI semantics</td>
		<td align="center" width="25%"><strong>4. Iterate</strong><br/>Refine through cross-tool validation</td>
	</tr>
</table>

Published research: <https://zenodo.org/records/16788626>

## Documentation & Links

| Resource | Link |
|---|---|
| Organization | <https://github.com/vdkit> |
| Hub | <https://vdk.tools> |
| Wiki | <https://wiki.vdk.tools> |
| CLI issues | <https://github.com/vdkit/VibeKit-VDK-CLI/issues> |
| Hub discussions | <https://github.com/vdkit/VDK-Hub/discussions> |

## Contributing

We welcome contributions across the ecosystem:

- Blueprint additions and quality improvements
- Adapter and conversion reliability fixes
- Documentation and examples
- Cross-platform integration testing

Use each repository’s `CONTRIBUTING.md` for repo-specific workflow.

---

<div align="center">
	<sub>VDK ecosystem • canonical blueprints • cross-tool adaptation</sub>
</div>
