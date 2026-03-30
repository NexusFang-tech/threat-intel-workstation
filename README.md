# NEXUS::SENTINEL — Cyber Threat Intelligence Workstation

**Live:** [nexusfang-tech.github.io/threat-intel-workstation](https://nexusfang-tech.github.io/threat-intel-workstation/)

Full-featured cybersecurity threat intelligence workstation with 10+ integrated tools across a three-panel layout. Includes IP reputation analysis, password strength auditing, hash identification, subnet calculation, port scanning, multi-format encoding/decoding, JWT token analysis, security header checking, an animated threat radar, and a live MITRE ATT&CK coverage grid.

## Tools

### Left Panel — Quick Analysis
- **IP Intelligence** — Risk scoring, ASN lookup, ISP identification, Tor/proxy detection, abuse report count, geolocation
- **Password Auditor** — Real Shannon entropy calculation, 10-point strength criteria, crack time estimation at 10B guesses/sec with charset analysis
- **Hash Identifier** — Paste any hash and get algorithm identification with confidence scores (MD5, SHA-1/256/384/512, bcrypt, Argon2, PBKDF2, CRC32, etc.)
- **Subnet Calculator** — CIDR notation input with network/broadcast address, host range, wildcard mask, and total host count

### Center — Main Workstation
- **Threat Feed** — Auto-updating simulated threat intelligence cards with severity ratings, MITRE technique tags, and timestamps
- **Port Scanner** — Simulated network scan with service/version detection across quick (20), common (100), and full (1024) profiles
- **Encode/Decode** — 7 encoding schemes: Base64, URL, Hexadecimal, Binary, ROT13, HTML Entities, Reverse
- **JWT Decoder** — Splits header/payload/signature, auto-decodes Base64url, annotates iat/exp/nbf timestamps with expiry checking
- **Security Header Checker** — Audits 12 HTTP security headers with individual grades and overall security score

### Right Panel — Monitoring
- **Animated threat radar** — Rotating sweep with severity-colored blips
- **Real-time system log** — Color-coded entries (info, warn, error, success)
- **Live metrics** — Threats/hr, packets/s, latency, uptime
- **MITRE ATT&CK grid** — Interactive 15-tactic coverage toggle

## Tech Stack

`Vanilla JS` · `HTML Canvas` · `CSS Animations` · `GitHub Pages`

Single HTML file. Zero dependencies. No build step. Cinematic boot sequence.

## Repo Description

> Cyber threat intelligence workstation with IP analysis, password auditing, hash identification, subnet calculator, port scanner, encoder/decoder, JWT decoder, security header checker, animated threat radar, and MITRE ATT&CK grid. Single file, zero dependencies.
