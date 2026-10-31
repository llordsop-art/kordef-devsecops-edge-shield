# kordef-devsecops-edge-shield

> **Automated GitHub Actions Security Gates (Trivy, Semgrep), Linux SSH/UFW Hardening & Cloudflare Zero-Trust WAF / DMARC (p=reject) Verification Suite**

Developed by **KOR DEF (Zero-Trust Cloud & AI Security Architecture)**.

---

## 🔒 Modules & Security Controls

- **CI/CD Automated Security Gates**: GitHub Actions workflows running Trivy vulnerability scanning and Semgrep SAST rulesets.
- **Linux Edge & SSH Hardening**: Hardened UFW firewall configuration and SSH daemon security baseline scripts.
- **Cloudflare Zero-Trust WAF Verification**: Edge ruleset validation suite for rate-limiting, bot management, and OWASP Core Rulesets.
- **DMARC Email Security Audit**: Enforces and verifies `p=reject` policies and SPF/DKIM record alignment across corporate domains.

---

## ⚡ Quick Start

```bash
# Run security suite
python3 edge_shield.py --domain kordefence.net --check-dmarc --check-waf
```

---

## 🛡️ About KOR DEF
**KOR DEF** provides end-to-end edge, cloud, and DevSecOps architecture security.
- **Website**: kordefence.net
- **Contact**: info@kordefence.com
