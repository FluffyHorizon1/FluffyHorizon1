<div align="center">

# 👋 Hey, I'm Finnian

**Security Architect • Founder • Systems Engineer**

*Building the next generation of secure financial infrastructure*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/finnian-bond)
[![Website](https://img.shields.io/badge/securedcybersolutions.co.uk-1E2327?style=for-the-badge&logo=googlechrome&logoColor=58A6FF)](https://securedcybersolutions.co.uk/)

</div>

---

## 🔐 What I Do

I architect **zero-trust security systems** and **embedded finance platforms** at the intersection of cybersecurity and fintech. Currently leading:

- **[Secured Cyber Solutions](https://securedcybersolutions.co.uk/)** — Enterprise security consulting & the "Swiss Fort" decentralized infrastructure
- **Bond FinTech** — Quantitative trading systems and embedded credit solutions

> *"The future of investment is autonomous, validated by performance, and secured by cryptography."*

---

## 🛠️ Featured Projects

### 🦭 [SecureSeaHorse](https://github.com/FluffyHorizon1/SecureSeaHorse)

A production-grade **C++ telemetry agent** with mTLS, anti-tamper mechanisms, and zero-trust architecture. Built for high-security environments where standard monitoring solutions fall short.

**Tech:** `C++20` • `OpenSSL` • `mTLS` • `Linux Kernel Modules`

### 🔒 [z-messanger](https://github.com/FluffyHorizon1/z-messanger)

**Z** — a zero-trust, end-to-end encrypted messenger where messages live **only** on the two devices that exchanged them. No accounts, no phone numbers, no server storage: the relay is a zero-knowledge, RAM-only pipe shuttling opaque ciphertext it can't read, alter, or forge.

- **E2EE core** — X3DH-style handshake + Signal-style Double Ratchet (X25519 / HKDF / HMAC), payloads sealed with XChaCha20-Poly1305. Forward secrecy and post-compromise healing on every round trip.
- **Zero-knowledge relay** — RAM-only Node.js WebSocket relay that runs on a read-only filesystem; scales horizontally behind a load balancer with RAM-only Redis.
- **Encrypted local vault** — on-device SQLite with every sensitive cell encrypted under an OS-keystore key, composable with an optional Argon2id passphrase.
- **No identifiers** — your address is a hash of your public key; contacts exchanged via QR / signed codes and verified with safety numbers. Disappearing messages and encrypted attachments built in.
- **One codebase, four targets** — Android, Windows, Linux, and macOS from a single Flutter app, with a pure-Dart crypto core proven by an end-to-end integration test through the real relay.

**Tech:** `Dart` • `Flutter` • `Node.js` • `X25519 / Double Ratchet` • `XChaCha20-Poly1305` • `SQLite` • `Docker`

### 🏰 Swiss Fort Architecture

Decentralized server fleet implementing *"Compartmentalization by Design"*:

- **Privacy Gateway** — Swiss-hosted ingress with kernel-level encryption
- **Adversarial Emulation** — Isolated APT simulation sandbox
- **Threat Monitoring** — Real-time SIEM with anomaly detection
- **Sovereign Vault** — Zero-port storage accessible only via encrypted tunnels

### 📈 Quantitative Trading Systems

Proprietary algorithms validated across diverse market regimes. Specialized in crypto arbitrage, order-flow analysis, and systematic alpha generation.

---

## 💻 Tech Stack

```text
Security     C++ • Python • OpenSSL • Metasploit • Burp Suite • Wireshark • Snort
Systems      Linux • Docker • AWS • PostgreSQL • Bash • CMake
Data/Quant   Pandas • NumPy • SQL • Real-time Analytics
DevOps       Git • Jenkins • Grafana • Syslog • CI/CD
```

---

## 🎯 Current Focus

```cpp
// Current Focus (2026)
const auto current_projects = {
    .building      = "Next-gen telemetry infrastructure with eBPF",
    .exploring     = "Zero-knowledge proofs for financial privacy",
    .hardening     = "Anti-tampering mechanisms in SecureSeaHorse",
    .learning      = "Rust for systems programming",
    .collaborating = "Open-source security tooling"
};
```

---

## 📊 GitHub Stats

<!-- Cards render from a SELF-HOSTED github-readme-stats instance on Vercel:
       https://github-readme-stats-dun-omega-13.vercel.app
     If the cards ever stop loading: confirm the instance is up and that the
     PAT_1 env var on Vercel hasn't expired (regenerate the token + redeploy).
     The streak card uses streak-stats.demolab.com and needs no instance. -->

<div align="center">

![Top Languages](https://github-readme-stats-dun-omega-13.vercel.app/api/top-langs/?username=FluffyHorizon1&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

</div>

---

## 🏆 Notable Achievements

- 🚀 Scaled Imployable® to a **£10m valuation** as ISSO & Technical Lead
- 🛡️ Architected enterprise security for clients across the UK & EU
- 💰 Developed validated trading algorithms benchmarked against standard strategies
- 🎤 Keynote speaker on cyber resilience and fintech innovation
- 🌍 Successfully campaigned for Fairtrade accreditation in the education sector

---

## 📫 Let's Connect

I'm always interested in discussing:

- **Zero-trust architecture** and security infrastructure
- **Quantitative finance** and algorithmic trading
- **Open-source security tooling**
- **Embedded finance** and regulatory tech

**Reach out:**

- 💼 [LinkedIn](https://linkedin.com/in/finnian-bond)
- 🌐 [securedcybersolutions.co.uk](https://securedcybersolutions.co.uk/)
- 🔗 Check out my pinned repositories below

---

<div align="center">

*"Bridging institutional capital and the decentralized web through rigorous security and quantitative analysis"*

![Profile Views](https://komarev.com/ghpvc/?username=FluffyHorizon1&color=58A6FF&style=flat-square)

</div>
