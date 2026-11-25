# TLS/SSL Certificate Watchdog

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Scope of Perimeter Verification](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/ca/security-headers-check/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Automated monitoring of SSL/TLS certificate expiration, cryptographic chain integrity, and encrypted transport standards in Canada.

Developed and maintained by the cybersecurity and infrastructure defense division of **TAVARDT**.

***

## 1. Scope of Perimeter Verification

This command-line utility audits transport encryption validity, cipher negotiation, and CA root hierarchies:

* **Preventative Expiry Warning:** Calculates remaining days until certificate expiry with customizable notification thresholds.
* **Cipher and Protocol Audit:** Ensures TLS 1.3 adoption and exclusion of deprecated cipher suites.
* **Certificate Authority (CA) Validation:** Verifies the root authority trust chain and SAN definitions.
* **Zero External Dependencies:** Implemented strictly with native Python ssl and socket modules.

***

## 2. Quick Start Guide

Run this tool directly via Python without installing third-party packages:

```bash
python watchdog.py example.ca
```

***

## 3. Online Diagnostic Tools (Canada)

Audit the public perimeter of your systems using the TAVARDT technical verification suite:

* HTTP Security Headers Checker
* [Consent Mode v2 & PIPEDA Validator](https://tools.tavardt.com/ca/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/ca/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/ca/exposed-files-scanner/)
* [Full Canadian Tools Portal](https://tools.tavardt.com/ca/)

***

## 4. Technical Advisory & Remediation

For cryptographic server hardening, PKI auditing, and data governance compliance in Canada, contact **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/ca/
* **Diagnostic Suite:** https://tools.tavardt.com/ca/
* **Technical Contact:** https://ag.tavardt.com/ca/contact/

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
