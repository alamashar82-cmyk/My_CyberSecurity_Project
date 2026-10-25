# CodeAlpha Cyber Security Internship Projects

This pack contains three beginner-friendly projects based on the CodeAlpha task sheet:

1. **Basic Network Sniffer** — view packet metadata on a network you own or have permission to test.
2. **Phishing Awareness Training** — an interactive learning page with a quiz.
3. **Secure Coding Review** — a small Python source-code review tool and example findings.

## Important
- Only capture traffic on networks/devices you own or are explicitly authorized to monitor.
- The sniffer displays packet metadata by default, not full payload contents.
- This is an educational starter pack. Test and customize the projects, take your own screenshots, and understand the code before submitting it as your internship work.

## Project 1 — Basic Network Sniffer

### Requirements
- Python 3.10+
- Scapy

Install:
```bash
python -m pip install -r requirements.txt
```

Run on an authorized network (administrator/root privileges may be required):
```bash
python sniffer.py
```

Optional: analyze a PCAP file:
```bash
python sniffer.py --pcap sample.pcap
```

### Features
- Shows timestamp, source/destination IP, protocol, and ports when available.
- Optional PCAP analysis.
- Does not intentionally print packet payloads.

## Project 2 — Phishing Awareness Training

Open `phishing-awareness/index.html` in a browser. It includes warning signs, prevention tips, examples, and an interactive quiz. It runs locally and needs no server or dependencies.

## Project 3 — Secure Coding Review

Run:
```bash
python secure-coding-review/review.py secure-coding-review/examples/sample_app.py
```

The scanner demonstrates basic pattern-based checks for risky Python patterns. It is not a replacement for a professional security audit or a full static analyzer.

## Suggested GitHub repository names
Create separate repositories if your internship coordinator expects one repository per task:
- `CodeAlpha_BasicNetworkSniffer`
- `CodeAlpha_PhishingAwarenessTraining`
- `CodeAlpha_SecureCodingReview`

If you upload this combined pack as one repository, a suitable name is `CodeAlpha_CyberSecurityProjects`.

## Before submission
1. Run each project yourself and verify the output.
2. Add your own screenshots to the relevant folder.
3. Replace this README's author section with your own details if desired.
4. Do not claim tests or results you have not personally verified.
