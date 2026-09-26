# 🛡️ AgentShield

**Evidence-based security inspection for AI Skills and MCP servers — before you trust them.**

> Built by **Mahmoud Hisham**

AI Skills and MCP servers can interact with files, commands, dependencies, credentials, environment variables, and external services. AgentShield helps developers inspect that risk surface before installing or connecting third-party agent tooling.

## What AgentShield inspects
- Risky scripts and command-execution indicators
- File-system access and permission exposure
- Dependencies and lifecycle/install scripts
- Network endpoints and potential outbound-data paths
- Credentials, secrets, and environment-variable access
- MCP configuration, tools, and schemas
- Prompt-injection and suspicious instruction patterns
- Obfuscated or suspicious code indicators
- Integrity changes using file fingerprints
- Security-relevant changes between package versions

## Evidence, not a “safe / unsafe” badge
AgentShield produces findings with context and evidence rather than claiming that a package is absolutely safe or malicious.

## Local-first approach
The product is designed around local inspection and minimizing unnecessary exposure of source code during analysis.

## Example report
See [docs/SAMPLE-REPORT.md](docs/SAMPLE-REPORT.md).

## Product availability
**AgentShield is a commercial product. This repository is documentation-only.**

The scanner implementation, detection rules, paid Skill package, and production configuration are intentionally **not included** in this public repository.

➡️ **Get AgentShield:** https://lnkd.in/e2ztCUcn

## Responsible positioning
AgentShield is a risk-inspection tool. A finding is not, by itself, proof that software is malicious, and absence of findings is not a guarantee of security.

## Ownership
**Developer / Publisher:** Mahmoud Hisham  
**Product:** AgentShield  
**Copyright © 2026 Mahmoud Hisham. All rights reserved.**

This public repository provides product documentation only. No rights to the proprietary AgentShield implementation, paid package, detection rules, or commercial assets are granted by publication of this repository.

---
**Scan first. See the evidence. Understand the risk. Then decide.**
