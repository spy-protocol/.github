<div align="center">
  <img src="profile/logo.png" alt="SPY Protocol" width="300"/>
  
  # SPY Protocol
  
  **Cryptographic Authentication Standard**
  
  [![Specification](https://img.shields.io/badge/spec-v1.0-blue.svg)](https://github.com/spy-protocol/spy-protocol)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/spy-protocol/spy-protocol/blob/main/LICENSE)
  [![Reference](https://img.shields.io/badge/reference-SPYIL-yellow.svg)](https://github.com/SPYIL)
</div>

---

## About

SPY Protocol is an open standard for cryptographic authentication between agents and proxies. It uses ECDSA public key cryptography to verify authorized clients without passwords, cookies, or behavioral tracking.

## How It Works
Agent (Browser) → Proxy (Gatekeeper) → Protected Resource

1. Agent presents public key and capabilities
2. Proxy challenges with cryptographic nonce  
3. Agent signs challenge with private key
4. Proxy verifies signature and grants access

## Specification

- [Protocol Specification](https://github.com/spy-protocol/spy-protocol) - Complete v1.0 standard
- [Security Model](https://github.com/spy-protocol/spy-protocol/blob/main/SECURITY.md) - Threat analysis
- [Implementation Guide](https://github.com/spy-protocol/spy-protocol/blob/main/IMPLEMENTERS.md) - Build SPY support

## Reference Implementation

[SPYIL](https://github.com/SPYIL) maintains the reference implementations:
- [Night](https://github.com/SPYIL/night) - Proxy (Go)
- [Day](https://github.com/SPYIL/day) - Agent (JavaScript)

## Contact

- Issues: [github.com/spy-protocol/spy-protocol/issues](https://github.com/spy-protocol/spy-protocol/issues)
- Email: info@spy-protocol.org

---

<div align="center">
  <h3>🔐 Secure. 🚀 Fast. 🎯 Effective.</h3>
  <h2>SPY Protocol - Authentication for the AI Age</h2>
  
  <br/>
  
  **Ready to eliminate bots from your sensitive sites?**
  
  [📖 Read the Spec](https://github.com/spy-protocol/spy-protocol) | [🚀 Get Started](https://spyil.com) | [📧 Contact Sales](mailto:sales@spyil.com)
</div>
