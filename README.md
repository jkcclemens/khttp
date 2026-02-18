# ⚠️ Security Notice: Namespace Takeover

This repository and its associated namespace have been claimed as part of a security research project demonstrating **Supply Chain** impact using reborn namespaces in JitPack coordinates.

**This is a benign placeholder. No malicious code is being distributed or published from this repository.**

## 📖 The Research

To understand how this namespace was taken over, the implications for the software supply chain, and how to mitigate this type of vulnerability, please read our full disclosure:

🔗 **[Supply Chain Necromancy: Reborn namespaces in JitPack coordinates](https://labs.itresit.es/2026/02/18/supply-chain-necromancy-reborn-namespaces-in-jitpack-coordinates/)**

## 🛠️ Action Required

The original **khttp** library is abandoned and no longer maintained. 

Continuing to use these coordinates (`jkcclemens/khttp`) via services like JitPack exposes your software supply chain to hijacking risks. We strongly advise that you **remove this dependency** from your projects and migrate to modern, actively maintained alternatives (such as OkHttp, Ktor, or similar libraries).

```gradle
// REMOVE THIS LINE FROM YOUR BUILD:
implementation 'com.github.jkcclemens:khttp:x.y.z'
```
---

*This proof of concept was conducted by LABS @ ITRES for educational and responsible disclosure purposes.*




