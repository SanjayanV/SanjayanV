<div align="center">

```
███████╗ █████╗ ███╗   ██╗     ██╗ █████╗ ██╗   ██╗ █████╗ ███╗   ██╗
██╔════╝██╔══██╗████╗  ██║     ██║██╔══██╗╚██╗ ██╔╝██╔══██╗████╗  ██║
███████╗███████║██╔██╗ ██║     ██║███████║ ╚████╔╝ ███████║██╔██╗ ██║
╚════██║██╔══██║██║╚██╗██║██   ██║██╔══██║  ╚██╔╝  ██╔══██║██║╚██╗██║
███████║██║  ██║██║ ╚████║╚█████╔╝██║  ██║   ██║   ██║  ██║██║ ╚████║
╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝
```

### Application Security Researcher · Bug Bounty Hunter · CVE Author

[![Bug Bounty](https://img.shields.io/badge/Bug%20Bounty-Active-success?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://github.com/SanjayanV)
[![AppSec](https://img.shields.io/badge/AppSec-Researcher-blueviolet?style=for-the-badge&logo=owasp&logoColor=white)](https://github.com/SanjayanV)

</div>

---

## `whoami`

```bash
$ cat /etc/passwd | grep SanjayanV

SanjayanV:x:1337:1337:AppSec Researcher,Bug Bounty Hunter,CVE Author:/home/SanjayanV:/bin/zsh
```

> I break things before the bad guys do.  
> Application security researcher focused on **supply chain attacks**, **web exploitation**, and **CI/CD security**. I hunt bugs, write CVEs, and build tools that make attack surfaces visible.

---



## ⚙️ Projects

### 🔐 [SecureAuth Framework](https://github.com/SanjayanV/secureauth)
> Production-grade authentication library in **Go**

A fully open-source auth framework implementing JWT, session-based auth, OAuth 2.0/OIDC, and API key management — designed as both a portfolio piece and a teaching resource for secure implementation patterns.

```
├── JWT (HS256/RS256, revocation strategies)
├── Session management (stateful, lifecycle hardening)
├── OAuth 2.0 / OIDC integration
├── API key management
└── CI/CD pipeline (SAST · Secrets · SBOM · Trivy · Dependency-Check)
```

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)

---

### 🛡️ [ChainSentry](https://github.com/SanjayanV/chainsentry) *(In Development)*
> Supply chain security monitoring tool

Built on the methodology that discovered CVE-2026-0933 — ChainSentry detects malicious patterns in lockfiles, dependency manifests, and CI/CD pipeline configs before they reach your build.

```
Target attack surfaces:
  package-lock.json · pnpm-lock.yaml · yarn.lock
  .github/workflows · Dockerfile · requirements.txt
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SBOM](https://img.shields.io/badge/SBOM-Aware-orange?style=flat-square)

---

## 🧰 Arsenal

```
╔══════════════════════════════════════════════════════════════╗
║                      RECON & DISCOVERY                       ║
║  subfinder · httpx · gau · amass · shodan                    ║
╠══════════════════════════════════════════════════════════════╣
║                     EXPLOITATION                             ║
║  Burp Suite Pro · Nuclei · ysoserial · sqlmap · ffuf         ║
╠══════════════════════════════════════════════════════════════╣
║                     APPSEC / SAST                            ║
║  Semgrep · CodeQL · Trivy · Gitleaks · OWASP ZAP             ║
╠══════════════════════════════════════════════════════════════╣
║                  CLOUD / INFRA SECURITY                      ║
║  kubeaudit · kube-bench · truffleHog · Syft                  ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🎯 Current Focus

```python
focus = {
    "exploitation":   ["SSRF", "XXE", "JWT attacks", "SSTI", "Deserialization"],
    "infra":          ["CI/CD attack surfaces", "GitHub Actions poisoning"],
    "research":       ["Lockfile injection", "Supply chain CVE hunting"],
    "bounty":         ["NordPass", "Rapyd"],
    "goal":           "AppSec Engineer role"
}
```

---

## 📊 Attack Surface Coverage

| Domain | Techniques | Status |
|---|---|---|
| Web AppSec | SSRF, XXE, IDOR, SSTI, Deserialization, JWT | 🟢 Active |
| Supply Chain | Lockfile injection, dependency confusion, CI poisoning | 🟢 CVE Filed |
| Session Security | Fixation, hijacking, JWT revocation bypass | 🟢 Active |
| Infrastructure | K8s misconfig, container escape, secret leakage | 🟡 In Progress |
| DAST / Runtime | OWASP ZAP, dynamic pipeline scanning | 🟡 In Progress |

---



## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanjayan-v-119957326/)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/h/0x7152-h_nt3r)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanjayan.v@outlook.com)

</div>

---

<div align="center">

```
"Security is not a product, but a process." — Bruce Schneier
```

![Visitor Count](https://komarev.com/ghpvc/?username=SanjayanV&color=blueviolet&style=flat-square)

</div>
