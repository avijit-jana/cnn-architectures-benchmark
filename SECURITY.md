# 🔐 Security Policy

We take security seriously and appreciate the community’s efforts in responsibly disclosing vulnerabilities. This document outlines supported versions, reporting procedures, and scope for security issues in this repository.

---

## ✅ Supported Versions

Only the following version of this repository currently receives security updates:

| Version | Supported |
| ------- | --------- |
| `main`  | ✅ Yes     |

All other branches, forks, or experimental features should be considered unsupported.

---

## 🚨 Reporting a Vulnerability

If you discover a security issue, please follow **responsible disclosure** practices:

1. **Do not open a public GitHub issue or discussion.**
2. Send a detailed report via LinkedIn:

   **🔗 [Avijit Jana](https://www.linkedin.com/in/avijit-jana/)**

3. Include the following information in your report:
   * Steps to reproduce the vulnerability
   * Affected files, datasets, or components
   * Potential impact (e.g., data exposure, privilege escalation, denial of service)
   * Proof-of-concept code or logs (if available)

We aim to acknowledge valid reports within **48 hours**.

---

## ⏳ Disclosure & Fix Timeline

* Verified vulnerabilities are typically addressed within **30 days**.
* Once fixed, a security advisory may be published.
* Reporters will be credited unless anonymity is requested.

---

## 🛡 Scope

This security policy applies only to:

* Code hosted in this repository
* The default `main` branch
* Core benchmarking scripts, training pipelines, and evaluation notebooks

It does **not** cover:

* Forks or downstream derivatives
* Local deployments, misconfigurations, or custom modifications
* Third-party dependencies (TensorFlow, PyTorch, dataset sources — please report those upstream)

---

## 📦 Dependencies & Updates

This project relies on external libraries such as **TensorFlow**, **PyTorch**, and dataset loaders.  
We recommend users:

* Keep dependencies updated via `requirements.txt`
* Monitor upstream advisories for TensorFlow/PyTorch
* Apply patches promptly to avoid exposure to known CVEs

---

## 🤝 Responsible Research

We encourage ethical security research. Activities such as denial-of-service attacks, social engineering, or unauthorized data exfiltration are **strictly prohibited**.

If you are unsure whether your testing approach is acceptable, contact us before proceeding.

Thank you for helping keep this project and its users safe.

<div align="center">

![Developer](https://img.shields.io/badge/Developed%20By-Avijit_Jana-blueviolet?style=for-the-badge)

</div>
