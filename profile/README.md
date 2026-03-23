<div align="center">
  <img src="../media/vdk-mark.svg" alt="VDK" width="72" height="72">

  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![Schema](https://img.shields.io/badge/AI_Context_Schema-v3.0-6366f1.svg)](https://github.com/vdkit/ai-context-schema)
  [![npm](https://img.shields.io/npm/v/@vibe-dev-kit/cli.svg?logo=npm&label=vdk-cli)](https://www.npmjs.com/package/@vibe-dev-kit/cli)
  [![GitHub stars](https://img.shields.io/github/stars/vdkit/VibeKit-VDK-CLI.svg?logo=github)](https://github.com/vdkit/VibeKit-VDK-CLI/stargazers)

</div>

---

## Overview

**VDK (Vibe Development Kit)** is a unified ecosystem for portable AI coding context. Define blueprint behavior once through canonical schema contracts, then adapt and deploy across Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Windsurf, Cline, and other tool carriers.

**Why VDK?**
- Canonical `kind` taxonomy for context behavior (`project-memory`, `skill`, `agent`, etc.)
- Deterministic adaptation with explicit outcomes (`lossless`, `lossy`, `unsupported`)
- Curated retrieval signal model (`L0-L3` defaults; `L4` provenance opt-in)
- End-to-end ecosystem flow from schema → blueprints → CLI → Hub → Wiki

## Key Features

<table>
<tr>
<td width="50%">

### Canonical Blueprint Architecture
- Universal AI Context Schema as the source of truth
- Functional taxonomy across heterogeneous tool formats
- Cross-platform behavior mapping with adaptation contracts
- Provenance-aware curation model for high-signal retrieval

### CLI Execution Core
- Search and deploy blueprint workflows
- Cross-tool migration and format conversion
- Deterministic install semantics aligned to runtime adapters
- Explicit adaptation classification on every conversion

</td>
<td width="50%">

### Ecosystem Surfaces
- **VDK Hub** for discovery, packaging, and sharing
- **VDK Wiki** for implementation and operational docs
- **VDK Blueprints** as curated reusable inventory
- **ai-context-schema** for contract-level consistency

### Multi-Tool Interoperability
- Claude Code, Codex, Cursor, Copilot, Gemini CLI, Windsurf
- Standardized behavior despite carrier-specific syntax
- Reusable context assets across orgs and repositories
- Migration-first architecture for reducing vendor lock-in

</td>
</tr>
</table>

## Tech Stack

<div align="center">

| Technology | Role in Ecosystem |
|------------|-------------------|
| ![Node.js](https://img.shields.io/badge/Node.js-22-339933?style=for-the-badge&logo=node.js&logoColor=white) | CLI runtime and tooling |
| ![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white) | Type-safe ecosystem development |
| ![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=for-the-badge&logo=next.js) | VDK Hub platform |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) | Hub data layer |
| ![JSON Schema](https://img.shields.io/badge/JSON_Schema-Draft_7-8B5CF6?style=for-the-badge) | Canonical blueprint contract |

</div>

## Repositories & Surfaces

### Core Repositories

| Repository | Purpose |
|------------|---------|
| [ai-context-schema](https://github.com/vdkit/ai-context-schema) | Canonical schema and validation contract |
| [VDK-Blueprints](https://github.com/vdkit/VDK-Blueprints) | Curated blueprint library |
| [VibeKit-VDK-CLI](https://github.com/vdkit/VibeKit-VDK-CLI) | Runtime retrieval/adaptation/deployment engine |
| [VDK-Hub](https://github.com/vdkit/VDK-Hub) | Web discovery and distribution platform |
| [VDK-Wiki](https://wiki.vdk.tools) | Documentation and operational guidance |

### Operating Order

1. `ai-context-schema`
2. `VDK-Blueprints`
3. `VDK-CLI`
4. `VDK-Hub`
5. `VDK-Wiki`

Hub and Wiki mirror CLI semantics; they do not redefine runtime behavior.

## Quick Start

<table>
<tr>
<td align="center" width="25%">
<strong>1. Install CLI</strong><br>
<code>npm i -g @vibe-dev-kit/cli</code>
</td>
<td align="center" width="25%">
<strong>2. Initialize</strong><br>
<code>vdk init</code>
</td>
<td align="center" width="25%">
<strong>3. Search</strong><br>
<code>vdk search --kind skill</code>
</td>
<td align="center" width="25%">
<strong>4. Deploy</strong><br>
<code>vdk deploy &lt;blueprint-id&gt;</code>
</td>
</tr>
</table>

Published research paper: <https://zenodo.org/records/16788626>

## Documentation

<div align="center">

| Resource | Link |
|----------|------|
| Organization | <https://github.com/vdkit> |
| Hub | <https://vdk.tools> |
| Wiki | <https://wiki.vdk.tools> |
| CLI Repository | <https://github.com/vdkit/VibeKit-VDK-CLI> |
| Blueprints Repository | <https://github.com/vdkit/VDK-Blueprints> |

</div>

## Contributing

<div align="center">

[![CLI Issues](https://img.shields.io/github/issues/vdkit/VibeKit-VDK-CLI.svg?logo=github)](https://github.com/vdkit/VibeKit-VDK-CLI/issues)
[![Hub Issues](https://img.shields.io/github/issues/vdkit/VDK-Hub.svg?logo=github)](https://github.com/vdkit/VDK-Hub/issues)
[![Discussions](https://img.shields.io/badge/Discussions-VDK_Hub-5865F2?logo=github)](https://github.com/vdkit/VDK-Hub/discussions)

</div>

We welcome contributions across all repositories. Use each repo’s `CONTRIBUTING.md` for local conventions and workflow.

| Type | Action |
|------|--------|
| Bug Report | [Open an issue](https://github.com/vdkit/VibeKit-VDK-CLI/issues) |
| Feature Proposal | [Start a discussion](https://github.com/vdkit/VDK-Hub/discussions) |
| Security Report | [Private disclosure policy](https://github.com/vdkit/VDK-Blueprints/security/policy) |

## License

VDK projects are generally MIT-licensed; verify license per repository.

---

<div align="center">

  [![Website](https://img.shields.io/badge/Website-vdk.tools-6366f1?style=for-the-badge)](https://vdk.tools)
  [![Wiki](https://img.shields.io/badge/Wiki-wiki.vdk.tools-6366f1?style=for-the-badge)](https://wiki.vdk.tools)
  [![GitHub Org](https://img.shields.io/badge/GitHub-vdkit-111827?style=for-the-badge&logo=github)](https://github.com/vdkit)

  <br>
  <sub>Built for cross-platform AI context interoperability</sub>

</div>
