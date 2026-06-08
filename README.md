# 🛡️ Nixion - All-in-One Security Toolkit # 

A comprehensive cybersecurity toolkit for reconnaissance, vulnerability assessment, exploitation testing, stress testing, and phishing simulation, inspired by the all-seeing giant Argus.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-green.svg)

## ⚠️ Legal Disclaimer
**This tool is for educational and authorized security testing only.** Misuse is illegal. The developer assumes no liability. Only test systems you own or have written permission for.

## ✨ Core Features (from the main menu)

### 🔍 Reconnaissance (Tools 1-41)
- **Identity & OSINT**: Username, email, phone, IP, MAC address lookups.
- **Domain & Network Intel**: WHOIS, DNS, reverse DNS, ASN, subdomain enumeration & bruteforce, zone transfer checks.
- **Web Analysis**: HTTP headers, tech detection, SSL/TLS info, favicon hash, WAF/CDN detection, DMARC/SPF/DKIM checks.
- **Content Discovery**: Link/JS endpoint extractors, robots.txt/sitemap analyzer, Wayback Machine, cloud storage finder.
- **Utilities**: Port scanner, traceroute, banner grabbing, ping sweep, hash lookup, Google Dorks generator, website screenshot.

### 💥 Exploitation Testing (Tools 42-62)
- **Web Vulnerabilities**: SQLi, Reflected XSS, CORS, Open Redirect, LFI/Path Traversal, CRLF Injection, SSRF, XXE, Command Injection, Host Header Injection, Clickjacking, Prototype Pollution.
- **Authentication & Session**: JWT Analyzer, CSRF Token Analyzer, Insecure Cookie Checker.
- **Infrastructure**: Subdomain Takeover, CMS Vulnerability Scanner, Supabase RLS Auditor, Directory/File Bruteforcer, HTTP Methods Discovery.
- **Utilities**: Reverse Shell Generator, Payload Encoder/Decoder.

### 🌊 Stress Testing (Tools 63-72)
HTTP Flood, Slowloris, R.U.D.Y., TCP/UDP/ICMP Floods, DNS/WebSocket Flood, GoldenEye, HTTP Slow Read.

### 🎣 Phishing Simulation (Tools 73-82)
Homoglyph/Typosquatting Generators, Email Spoofing Checker, Credential Harvester, URL Obfuscator, Phishing Kit Detector, Campaign Planner.

### 🤖 Advanced
- **AI Search (A)**: Find the best tool for your needs.
- **Stealth Mode (S)**: Configure proxies/anonymity.
- **Botnet Mode (B)**: Coordinated DDoS simulation.
- **World Map (W)**: Visual zombie network distribution.

## 🚀 Quick Start

1.  **Clone the repository**
    ```bash
    git clone https://github.com/SilentRootX208/Nixion.git
    cd Nixion
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the toolkit**
    ```bash
    python argus.py
    ```

## 📖 Usage Guide

Navigate the interactive menu by entering the number or letter of your desired tool.

**Command-line examples:**
```bash
# Run a specific tool directly (if supported)
python argus.py --tool 7 --domain example.com
python argus.py --tool 42 --url "http://testphp.vulnweb.com/artists.php?artist=1"

# Use AI to find a tool
python argus.py --ai "I need to find subdomains"

🔧 Configuration

Set your API keys in config.yaml for full functionality (Shodan, HaveIBeenPwned, etc.). Configure proxy/TOR in the Stealth Mode menu (S).

🙏 Acknowledgments

Built for educational purposes. Use responsibly and ethically, like the guardian Argus.

```

