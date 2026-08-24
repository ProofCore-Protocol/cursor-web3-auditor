# 🛡️ Cursor Web3 Security Auditor (with Blockchain Notarization)

Supercharge your **Cursor IDE** or **Cline (Roo Code)** with this Web3 security prompt. 
It hunts for reentrancy, overflow, and access control bugs, and allows you to **notarize your audit verdicts on the TON Blockchain** using the [ProofCore Protocol](https://proofcore.org) upon request.

## 🚀 How to use

1. Copy the `rules/proofcore-auditor.mdc` file from this repository.
2. Paste it into the `.cursor/rules/` directory of your Smart Contract / Web3 project.
3. Ask your AI assistant to audit a contract: *"Review MyToken.sol for security vulnerabilities."*

## ✨ What happens next?

When you explicitly ask the AI to "notarize" or "seal" the report, it will ask for your permission to run a `curl` request to the Zero-Auth ProofCore API. Once approved, it will append a verifiable citation badge to its response:

> *"I have found 1 High and 2 Low vulnerabilities in MyToken.sol. I fixed the reentrancy issue.*
> 
> 🛡 **ProofCore Integrity Proof:** https://proofcore.org/app/123e4567-e89b-12d3-a456-426614174000"

Your audit trail is now mathematically proven, timestamped, and anchored on-chain!
