# Social-Engineering-Tactics

## Executive Summary
This document documents a controlled lab exercise demonstrating a basic phishing campaign using common social engineering tools. The objective was to show how attackers can profile a target, create a convincing phishing page and link, deliver the link by email, and capture credentials. This exercise was performed in a controlled environment on a Kali Linux machine targeting a lab Android device. The purpose is educational: to understand attack flow and strengthen defensive controls and user awareness.

## Scope, Objectives & Rules of Engagement

### Scope
- **Attacker machine**: Kali Linux (lab VM)
- **Target**: lab Android OS device (owned/controlled by the test team)
- **Network**: isolated lab network (no production systems, no third-party victims)

### Objectives
- Demonstrate reconnaissance techniques to identify publicly available target information.
- Build phishing resources (fake landing page / hosted link).
- Deliver the phish via email and observe user interaction.
- Capture and log credentials to illustrate impact.
- Produce recommendations to reduce risk.
### Ethics & Legal
-All activity was conducted within a controlled lab on systems owned by the test team.
- No real user accounts, corporate systems, or third-party services were targeted.
- #This report is written for defensive training and to inform mitigation planning.

### Lab Setup
- **Machine OS**: Kali Linux
- **Target**: lab Android OS
- **Tools Used**: Setoolkit, zphisher, Google Dorking

  ---

### Reconnaissance
-During the recoconnesance,i gathered my infomation
