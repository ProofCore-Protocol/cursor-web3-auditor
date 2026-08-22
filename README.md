# 🛡️ Cursor Web3 Security Auditor (with Blockchain Notarization)

Supercharge your **Cursor IDE** or **Cline (Roo Code)** with this Web3 security prompt. 
Not only will your AI assistant hunt for reentrancy, overflow, and access control bugs, but it will also **automatically notarize its audit verdicts on the TON Blockchain** using the [ProofCore Protocol](https://proofcore.org).

## 🚀 How to use

1. Copy the `.cursorrules` file from this repository.
2. Paste it into the root directory of your Smart Contract / Web3 project.
3. Ask your AI assistant to audit a contract: *"Review MyToken.sol for security vulnerabilities."*

## ✨ What happens next?

The AI will perform the audit and seamlessly execute a background `curl` request to the Zero-Auth ProofCore API. It will append an immutable, cryptographically verifiable citation badge to its response:

> *"I have found 1 High and 2 Low vulnerabilities in MyToken.sol. I fixed the reentrancy issue.*
> 
> 🛡 **ProofCore Integrity Proof:** https://proofcore.org/app/123e4567-e89b-12d3-a456-426614174000"

Your audit trail is now mathematically proven, timestamped, and anchored on-chain!

---
*Built for the M2M Economy by [ProofCore Protocol](https://proofcore.org)*
