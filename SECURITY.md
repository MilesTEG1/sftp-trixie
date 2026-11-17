# 🛡️ Security Policy

## 📦 Supported Versions

Security fixes and operating system updates are actively applied to the following container image tags:

| Tag | Base Image | Architectures | Status |
| :--- | :--- | :--- | :--- |
| `latest`, `trixie` | Debian 13 Trixie | `linux/amd64`, `linux/arm64` | :white_check_mark: Supported |
| `alpine` | Alpine Linux | `linux/amd64`, `linux/arm64` | :white_check_mark: Supported |
| Legacy tags (`bookworm`, etc.) | Debian Bookworm | `linux/amd64` | :x: End of Life |

---

## 🔒 Reporting a Vulnerability

We take the security of this SFTP container very seriously. If you discover a security vulnerability, we appreciate your help in disclosing it to us responsibly.

### 🛑 Please do NOT report security vulnerabilities via public GitHub Issues.

Instead, please use one of the following private reporting channels:

1. **GitHub Private Vulnerability Reporting (Preferred)** :
   * Go to the [Security Advisories page](https://github.com/MilesTEG1/sftp-trixie/security/advisories).
   * Click on the **"Report a vulnerability"** button.
   * Provide a detailed description of the vulnerability, steps to reproduce, and any potential impact.

2. **Direct Contact** :
   * If you cannot use GitHub's advisory system, you can contact the maintainer directly via GitHub profile: [@MilesTEG1](https://github.com/MilesTEG1).

---

## ⏱️ Response & Disclosure Process

* **Acknowledgment**: We aim to acknowledge receipt of your vulnerability report within **48 hours**.
* **Assessment & Fix**: We will assess the severity, reproduce the issue, and prepare a patched container release.
* **Release & Advisory**: Once a fix is verified and deployed to GitHub Container Registry (`ghcr.io/milesteg1/sftp-trixie`), a public GitHub Security Advisory will be published crediting the reporter (if desired).
