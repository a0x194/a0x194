<h1 align="center">a0x194</h1>

<p align="center">
  <strong>Security Researcher · Tool Developer · Penetration Tester</strong>
</p>

<p align="center">
  <a href="https://www.tryharder.space">
    <img src="https://img.shields.io/badge/Website-tryharder.space-00ff88?style=flat&logo=firefox&logoColor=white" />
  </a>
  <a href="https://github.com/a0x194/tryharder-extension">
    <img src="https://img.shields.io/badge/🔥_NEW-Browser_Extension-ff6b6b?style=flat" />
  </a>
  <a href="https://www.tryharder.space/tools/">
    <img src="https://img.shields.io/badge/Security-Tools-00ff88?style=flat&logo=gnubash&logoColor=white" />
  </a>
  <a href="mailto:admin@tryharder.space">
    <img src="https://img.shields.io/badge/Contact-Email-00ff88?style=flat&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🔥 Featured: TryHarder Security Suite

<div align="center">

[![Extension Banner](https://img.shields.io/badge/🧩_Browser_Extension-15_Security_Tools_in_One-00ff88?style=for-the-badge&labelColor=000000)](https://github.com/a0x194/tryharder-extension)

**15-in-1 Browser Security Testing Toolkit**

Works with Chrome · Edge · Firefox · Brave

[![Download](https://img.shields.io/badge/⬇️_Download-v1.0.0-00ff88?style=for-the-badge&labelColor=000)](https://github.com/a0x194/tryharder-extension/releases)
[![Stars](https://img.shields.io/github/stars/a0x194/tryharder-extension?style=for-the-badge&labelColor=000&color=00ff88)](https://github.com/a0x194/tryharder-extension)

</div>

<table>
<tr>
<td width="33%">

**Tier 1 - Recon**
- SubRecon
- ParamFuzz
- JSHunter
- SQLiDetect
- AuthBypass

</td>
<td width="33%">

**Tier 2 - Info Gathering**
- WaybackMiner
- HeaderAudit
- APIRecon
- PortRush
- GitLeaks

</td>
<td width="34%">

**Tier 3 - Advanced**
- ProtoDetect
- CertWatch
- DNSTracer
- WebTechFP
- CachePoison

</td>
</tr>
</table>

---

### About

Security researcher building open-source offensive security tools. Creator of **[TryHarder](https://www.tryharder.space)** — a security training platform for ethical hackers.

---

## 🔧 Security Tools

<table>
<tr>
<td width="50%">

### [CORScan](https://github.com/a0x194/corscan)

**CORS Misconfiguration Scanner**

Fast, multi-threaded scanner for detecting dangerous CORS configurations.

```bash
./corscan -u https://target.com
./corscan -l urls.txt -t 20
```

**Features:**
- Origin reflection detection
- Wildcard + credentials check
- Null origin bypass
- Subdomain trust issues

</td>
<td width="50%">

### [HTTPSmuggler](https://github.com/a0x194/httpsmuggler)

**HTTP Request Smuggling Detector**

Detect CL.TE, TE.CL, and TE.TE smuggling vulnerabilities.

```bash
./httpsmuggler -u https://target.com
./httpsmuggler -l urls.txt -t 5
```

**Features:**
- CL.TE / TE.CL detection
- TE.TE obfuscation tests
- Time-based analysis
- Multiple payload variants

</td>
</tr>
<tr>
<td width="50%">

### [CloudBucket](https://github.com/a0x194/cloudbucket)

**Multi-Cloud Storage Bucket Scanner**

Discover misconfigured buckets across AWS, GCP, Azure, and more.

```bash
./cloudbucket -b company-backup
./cloudbucket -l buckets.txt -p aws,gcp
```

**Features:**
- AWS S3 / GCP / Azure / Alibaba OSS
- Public read/write detection
- File enumeration
- Multi-threaded scanning

</td>
<td width="50%">

### [CICDGuard](https://github.com/a0x194/cicdguard)

**CI/CD Pipeline Security Scanner**

Detect vulnerabilities in GitHub Actions, GitLab CI, Jenkins.

```bash
./cicdguard -d ./my-project
./cicdguard -repo owner/repo
```

**Features:**
- Hardcoded secrets detection
- Command injection checks
- Dangerous workflow triggers
- Unpinned action versions

</td>
</tr>
</table>

---

### Quick Install

All tools are written in **Go** — single binary, zero dependencies.

```bash
# Clone and build any tool
git clone https://github.com/a0x194/corscan.git
cd corscan && go build -o corscan

# Or download pre-built binaries from Releases
```

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,js,bash,docker,kubernetes,linux,aws,gcp,azure&theme=dark" />
</p>

---

### Expertise

```
Offensive Security           Cloud Security              Development
─────────────────           ─────────────────           ─────────────────
• Web App Pentesting        • AWS / GCP / Azure         • Go
• API Security              • Container Security        • Python
• OWASP Top 10              • Kubernetes                • JavaScript
• Red Team Operations       • Infrastructure as Code    • Bash
```

---

<p align="center">
  <strong><a href="https://www.tryharder.space">🌐 www.tryharder.space</a></strong>
  &nbsp;·&nbsp;
  <strong><a href="https://github.com/a0x194/tryharder-extension">🧩 Browser Extension</a></strong>
  &nbsp;·&nbsp;
  <strong><a href="https://www.tryharder.space/tools/">🔧 More Tools</a></strong>
</p>
