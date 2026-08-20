# The Importance of Patch Management

## Oasis Infobyte — Cyber Security Internship

### Task 6 — Research Report

---

## 1. Introduction

Patch management is the process of identifying, prioritizing, acquiring, testing, installing, and verifying software updates and security patches across an organization's systems. Software vendors regularly release patches to fix security vulnerabilities, bugs, and other problems. Effective patch management is an important part of cybersecurity because it reduces the number of weaknesses that attackers can exploit.

Patch management is closely connected to the vulnerability-management lifecycle. When a vulnerability is discovered, organizations need to identify affected systems, determine the level of risk, obtain the appropriate fix, deploy it, and verify that the vulnerability has been addressed.

---

## 2. Why Patches Matter

### 2.1 What Is a Vulnerability?

A vulnerability is a weakness in software, hardware, configuration, or a system that could potentially be exploited by an attacker.

For example, a software application may contain a programming error that allows an attacker to execute unauthorized commands.

When security researchers or vendors discover vulnerabilities, they can be documented and tracked so organizations can understand and address them.

### 2.2 What Is a CVE?

**CVE** stands for **Common Vulnerabilities and Exposures**.

A CVE identifier is a standardized identifier for a publicly known cybersecurity vulnerability.

A CVE record helps security professionals consistently identify and discuss a particular vulnerability.

A CVE may look like:

`CVE-2026-12345`

Organizations can use CVE information to determine whether their systems contain vulnerable software.

### 2.3 What Is CVSS?

**CVSS** stands for **Common Vulnerability Scoring System**.

CVSS provides a standardized method for describing the severity of a vulnerability.

It considers factors such as:

- Attack complexity
- Required privileges
- User interaction
- Attack vector
- Confidentiality impact
- Integrity impact
- Availability impact

CVSS scores can help security teams prioritize vulnerabilities. Organizations should also consider whether a vulnerability is actively being exploited and how important the affected system is.

### 2.4 From Vulnerability Discovery to Exploitation

The vulnerability process can be simplified as:

```text
Vulnerability discovered
        ↓
Vulnerability reported
        ↓
CVE assigned
        ↓
Vendor investigates
        ↓
Security patch released
        ↓
Organization identifies affected systems
        ↓
Patch deployed
        ↓
