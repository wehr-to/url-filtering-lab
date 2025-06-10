# 🌐 URL Filtering Lab

## 🎯 Purpose
This repository is built to demonstrate and explain URL filtering at depth — how it works, how it's bypassed, and how to simulate policy enforcement.

Covers core concepts, evasions, labs, and industry tooling examples to help red teamers, defenders, and architects alike.

## 🔍 Topics Covered

### Core Concepts
- What URL filtering is and isn't
- Static vs real-time categorization
- Categorization providers (Webroot, Forcepoint, Zscaler)
- False positive remediation processes

### Bypass Techniques
- Homoglyph & Unicode domain tricks
- Base64 encoded redirect payloads
- Javascript and meta-refresh redirection
- Abuse of low reputation domains and expired subdomains

### Lab Demos
- Obfuscated URL generation script
- Public reputation API checks
- Category prediction based on token models

## 📂 Folder Overview
- `fundamentals/`: Deep dives into filtering mechanics
- `evasion_techniques/`: Real bypass tactics used in phishing and malware delivery
- `labs/`: Practical, hands-on simulations
- `test_urls/`: Seed lists for testing your own SWG/DNS setups
- `diagrams/`: Pipeline for visual learning and interview aid
- `references/`: API docs, vendor feature mapping, etc.

## ✅ To Do
- [ ] Integrate VirusTotal URL checks
- [ ] Add support for Censys/Shodan link enrichment
- [ ] Build URL shortener abuse lab (bit.ly, tinyurl)
- [ ] Add multi-layer test cases (URL + content type mismatch)

## 📄 License
MIT
