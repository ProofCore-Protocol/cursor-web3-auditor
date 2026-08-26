# 🛡️ Cursor Web3 Security Auditor (with Blockchain Notarization)

Supercharge your **Cursor IDE** or **Cline** with an autonomous Web3 security auditor. 
It hunts for reentrancy, overflow, and access control bugs, and **cryptographically anchors audit verdicts on the TON Blockchain** using the [ProofCore Protocol](https://proofcore.org).

[![Cursor Directory](https://img.shields.io/badge/Cursor%20Directory-cursor--web3--auditor-blue)](https://cursor.directory/plugins/cursor-web3-auditor)
[![Smithery](https://img.shields.io/badge/Smithery-100%2F100-brightgreen)](https://smithery.ai/server/proofcore-org/notary)
[![TON Blockchain](https://img.shields.io/badge/Blockchain-TON-0098EA?logo=ton&logoColor=white)](https://ton.org)

---

## 🚀 Installation

### Option A: Install via Cursor Directory (1-Click)
Open [cursor.directory/plugins/cursor-web3-auditor](https://cursor.directory/plugins/cursor-web3-auditor) and click **Add to Cursor**.

### Option B: Manual Setup
1. Copy `rules/proofcore-auditor.mdc` to your project's `.cursor/rules/` directory.
2. (Recommended) Add the ProofCore MCP server in Cursor Settings -> Features -> MCP:
   - **Command:** `uvx proofcore-mcp`

---

## ✨ How it works in Chat

Ask Cursor: *"Audit MyToken.sol for security vulnerabilities."*

The AI will perform the audit and automatically seal the final verdict on the TON Blockchain:

> *"I have found 0 Critical and 1 Low vulnerability in MyToken.sol.*
> 
> 🛡 **ProofCore Integrity Proof:** https://proofcore.org/app/123e4567-e89b-12d3-a456-426614174000"

Your audit trail is mathematically proven, timestamped with an Ed25519 notary signature, and anchored on-chain!