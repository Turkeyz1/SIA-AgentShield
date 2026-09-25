# Threat Model

SIA AgentShield focuses on risks that may appear when developers install AI Skills or connect MCP servers to agent environments.

## Risk areas
- Command and script execution
- Excessive file-system access
- Credential and environment-variable exposure
- Unexpected outbound network behavior
- Risky dependencies or lifecycle scripts
- MCP tool and configuration exposure
- Prompt/instruction manipulation
- Obfuscated or suspicious implementation patterns
- Unexpected changes between package versions

## Trust boundary
AgentShield supports human review before trust is granted. A detected indicator is not proof of malicious intent, and a clean scan is not a guarantee of safety.

## Public-repository boundary
This repository documents the product and threat model only. Detection rules, scanner implementation, proprietary heuristics, production configuration, and the paid Skill package are excluded.

**Copyright © 2026 Mahmoud Hisham. All rights reserved.**
