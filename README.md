# natas-overthewire
# 🔐 OverTheWire Natas — Complete Web Security Labs

<p align="center">

<img src="https://img.shields.io/badge/CTF-OverTheWire-black?style=for-the-badge" alt="CTF">
<img src="https://img.shields.io/badge/Web%20Security-Natas-red?style=for-the-badge" alt="Web Security">
<img src="https://img.shields.io/badge/Burp%20Suite-Testing-orange?style=for-the-badge" alt="Burp Suite">
<img src="https://img.shields.io/badge/Linux-Kali-blue?style=for-the-badge" alt="Linux">
<img src="https://img.shields.io/badge/Python-Automation-yellow?style=for-the-badge" alt="Python">

</p>

<p align="center">
  <b>My complete practical journey through the OverTheWire Natas web-security wargame.</b>
</p>

---

## 📌 About This Repository

This repository documents my hands-on cybersecurity journey through the **OverTheWire Natas wargame**, progressing from basic web information disclosure and client-side weaknesses to more advanced web exploitation and application-security concepts.

Natas is designed around deliberately vulnerable web applications. Each level requires identifying a vulnerability or weakness and using that understanding to obtain the credentials required for the next level.

My goal with this repository is not simply to record passwords or solutions, but to document:

* 🔎 Reconnaissance and vulnerability discovery
* 🌐 HTTP request/response analysis
* 🧪 Exploitation methodology
* 🕵️ Burp Suite testing
* 🐧 Linux command-line techniques
* 🐍 Python-based automation
* 🔐 Authentication and session security
* 💉 Injection vulnerabilities
* 📤 File-upload security
* 🛡️ Defensive remediation
* 📝 Lessons learned from each lab

My initial Natas documentation covers Levels 0–10, including source-code disclosure, directory listing, `robots.txt`, HTTP headers, cookie manipulation, LFI, encoding analysis and command injection.
The Levels 11–20 documentation expands into XOR cookie forgery, file-upload bypasses, SQL injection, blind SQL injection, command injection and session attacks.
The Levels 21–26 documentation covers shared-session hijacking, access-control/redirect logic bypasses, PHP type-juggling, local file inclusion combined with HTTP log poisoning for remote code execution, and insecure PHP object deserialization.

---

# 🎯 Objectives

This project is intended to develop practical skills in:

```text
Web Application Security
        ↓
Reconnaissance
        ↓
Source Code Analysis
        ↓
HTTP Analysis
        ↓
Vulnerability Identification
        ↓
Controlled Exploitation
        ↓
Automation
        ↓
Security Impact Analysis
        ↓
Defensive Remediation
```

---

# 🧩 Natas Progress

| Level         | Status | Main Area                                    |
| ------------- | :----: | --------------------------------------------- |
| Natas 00 → 01 |    ✅   | Source Code Disclosure                       |
| Natas 01 → 02 |    ✅   | Client-Side Restriction Bypass               |
| Natas 02 → 03 |    ✅   | Directory Listing                            |
| Natas 03 → 04 |    ✅   | `robots.txt` Disclosure                      |
| Natas 04 → 05 |    ✅   | HTTP Referer Manipulation                    |
| Natas 05 → 06 |    ✅   | Cookie Manipulation                          |
| Natas 06 → 07 |    ✅   | Source Code / Secret Disclosure              |
| Natas 07 → 08 |    ✅   | Local File Inclusion                         |
| Natas 08 → 09 |    ✅   | Reversible Encoding                          |
| Natas 09 → 10 |    ✅   | OS Command Injection                         |
| Natas 10 → 11 |    ✅   | Argument Injection / Filter Bypass           |
| Natas 11 → 12 |    ✅   | XOR Cookie Forgery                           |
| Natas 12 → 13 |    ✅   | Unrestricted File Upload                     |
| Natas 13 → 14 |    ✅   | Image Header / File Upload Bypass            |
| Natas 14 → 15 |    ✅   | Classic SQL Injection                        |
| Natas 15 → 16 |    ✅   | Boolean-Based Blind SQLi                     |
| Natas 16 → 17 |    ✅   | Blind Command Injection                      |
| Natas 17 → 18 |    ✅   | Time-Based Blind SQLi                        |
| Natas 18 → 19 |    ✅   | Session ID Brute Force                       |
| Natas 19 → 20 |    ✅   | Session ID Reverse Engineering               |
| Natas 20 → 21 |    ✅   | Custom Session Storage                       |
| Natas 21 → 22 |    ✅   | Shared Session Hijacking (Colocated Apps)    |
| Natas 22 → 23 |    ✅   | Access-Control / Redirect Logic Bypass       |
| Natas 23 → 24 |    ✅   | PHP `strstr()` + Numeric Type Juggling       |
| Natas 24 → 25 |    ✅   | PHP `strcmp()` Array Type Juggling           |
| Natas 25 → 26 |    ✅   | LFI + HTTP Log Poisoning (RCE)               |
| Natas 26 → 27 |    ✅   | Insecure PHP Object Deserialization          |
| Natas 27 → 28 |    ⏳   | In Progress                                   |
| Natas 28 → 29 |    ⏳   | In Progress                                   |
| Natas 29 → 30 |    ⏳   | In Progress                                   |
| Natas 30 → 31 |    ⏳   | In Progress                                   |
| Natas 31 → 32 |    ⏳   | In Progress                                   |
| Natas 32 → 33 |    ⏳   | In Progress                                   |
| Natas 33 → 34 |    ⏳   | In Progress                                   |

> **Current official scope:** Natas currently documents the progression through **Natas 33 → Natas 34**.

---

# 📚 Skills Covered

## 🌐 Web Application Security

* HTTP fundamentals
* Request/response analysis
* Cookies
* Sessions
* Authentication
* Authorization
* Source-code analysis
* Parameter manipulation
* Input validation
* Information disclosure

## 💉 Injection

* SQL Injection
* Blind SQL Injection
* Time-Based SQL Injection
* Command Injection
* Argument Injection
* Input-filter bypass techniques

## 📁 File & Path Security

* Directory listing
* Local File Inclusion
* HTTP log poisoning (LFI → RCE)
* File upload vulnerabilities
* Path manipulation
* Sensitive file disclosure
* Server-side file validation

## 🍪 Authentication & Session Security

* Cookie tampering
* Predictable session IDs
* Session enumeration
* Session manipulation
* Custom session storage
* Shared / colocated session hijacking
* Authentication bypasses

## 🧠 Application Logic & Deserialization

* PHP type juggling (`strstr()`, `strcmp()`, loose comparison)
* Broken access-control / redirect logic
* Insecure PHP object deserialization (`unserialize()`)
* Magic-method (`__destruct()`) gadget abuse for RCE

## 🕵️ Security Testing

* Burp Suite Proxy
* Burp Repeater
* Burp Intruder
* Browser DevTools
* HTTP headers
* Request manipulation
* Response analysis
* Payload testing
* Online PHP sandboxes for behaviour verification

## 🐧 Linux

* Linux terminal
* `curl`
* `grep`
* `cat`
* `ls`
* `xxd`
* `base64`
* `rev`
* `cewl` (targeted wordlist generation)
* File and directory analysis
* Shell concepts

## 🐍 Python

Python is used where appropriate for:

* Encoding/decoding
* Payload generation
* XOR operations
* Brute-force automation
* HTTP request automation
* Repetitive security-testing tasks

---

# 🗂️ Repository Structure

```text
overthewire-natas-web-security/
│
├── README.md
│
├── levels/
│   │
│   ├── 00-source-code/
│   ├── 01-client-side-bypass/
│   ├── 02-directory-listing/
│   ├── 03-robots-txt/
│   ├── 04-referer-header/
│   ├── 05-cookie-manipulation/
│   ├── 06-source-disclosure/
│   ├── 07-lfi/
│   ├── 08-encoding/
│   ├── 09-command-injection/
│   ├── 10-filter-bypass/
│   │
│   ├── 11-xor-cookie/
│   ├── 12-file-upload/
│   ├── 13-image-upload-bypass/
│   ├── 14-sqli/
│   ├── 15-blind-sqli/
│   ├── 16-blind-command-injection/
│   ├── 17-time-based-sqli/
│   ├── 18-session-bruteforce/
│   ├── 19-session-reverse-engineering/
│   ├── 20-custom-session-storage/
│   │
│   ├── 21-shared-session-hijacking/
│   ├── 22-redirect-logic-bypass/
│   ├── 23-strstr-type-juggling/
│   ├── 24-strcmp-type-juggling/
│   ├── 25-lfi-log-poisoning/
│   ├── 26-insecure-deserialization/
│   │
│   ├── 27/
│   ├── 28/
│   ├── 29/
│   ├── 30/
│   ├── 31/
│   ├── 32/
│   ├── 33/
│   └── 34/
│
├── screenshots/
│   ├── natas00/
│   ├── natas01/
│   ├── natas02/
│   ├── ...
│   ├── natas21/
│   ├── natas22/
│   ├── natas23/
│   ├── natas24/
│   ├── natas25/
│   └── natas26/
│
├── scripts/
│   ├── xor/
│   ├── encoding/
│   ├── sql-injection/
│   └── automation/
│
├── writeups/
│   ├── natas-00-10.pdf
│   ├── natas-11-20.pdf
│   └── natas-21-26.pdf
│
└── notes/
    ├── burp-suite.md
    ├── web-security.md
    ├── sql-injection.md
    ├── php-type-juggling.md
    ├── php-object-injection.md
    └── command-injection.md
```

---

# 🔬 Level Documentation Format

Each completed level will follow the same structure:

```text
# Natas XX → Natas XX+1

## 🎯 Objective

What the challenge asks us to discover.

## 🔎 Reconnaissance

What was observed during initial testing.

## 🐛 Vulnerability

The vulnerability or security weakness identified.

## 🧠 Root Cause

Why the application is vulnerable.

## 🧪 Exploitation

Controlled exploitation steps performed inside the Natas lab.

## 🛠️ Tools

Tools used during the investigation.

## 📸 Evidence

Screenshots showing important findings.

## 🔐 Result

Credential/flag obtained for the next level.

## 🛡️ Remediation

How a real-world application should prevent the vulnerability.

## 📚 Key Takeaways

What I learned from the challenge.
```

---

# 🧪 Example: Early Natas Techniques

The first levels establish important fundamentals.

### Natas 0

**Concept:** Source-code disclosure.

The password is exposed in the HTML source, demonstrating that comments and client-delivered HTML are not secret.

### Natas 1

**Concept:** Client-side restriction bypass.

Disabling right-click does not prevent users from accessing source code through other methods such as DevTools or `view-source:`.

### Natas 4

**Concept:** HTTP header manipulation.

The challenge demonstrates why security decisions should not depend on client-controlled headers such as `Referer`.

### Natas 5

**Concept:** Cookie manipulation.

A client-controlled cookie is modified to demonstrate why authorization decisions must be verified server-side.

### Natas 7

**Concept:** Local File Inclusion.

User-controlled input reaches PHP's `include()` functionality, demonstrating the risk of directly mapping URL parameters to server-side files.

---

# 🔥 Advanced Concepts

The later documented levels introduce significantly more advanced techniques.

### XOR Cookie Forgery

Natas 11 demonstrates known-plaintext analysis against a repeating XOR key and subsequent manipulation of the encrypted cookie.

### File Upload Bypass

Natas 12–13 explore weaknesses in server-side upload validation and image-header validation.

### Blind SQL Injection

Natas 15 demonstrates extracting information through a true/false response oracle rather than directly receiving database output.

### Time-Based SQL Injection

Natas 17 removes the visible response difference and requires timing information to distinguish correct and incorrect conditions.

### Session Attacks

Natas 18 and 19 demonstrate weaknesses caused by predictable and reverse-engineerable session identifiers.

### Custom Session Storage

Natas 20 demonstrates how unsafe custom serialization and delimiter handling can allow attacker-controlled session data to be injected.

### Shared Session Hijacking

Natas 21 demonstrates how two colocated applications sharing the same `PHPSESSID` / session backend allow session data written on one app (e.g. an admin flag) to affect authorization decisions on the other.

### Access-Control / Redirect Logic Bypass

Natas 22 demonstrates that a redirect guarded only by `isset($_GET['param'])`-style logic can be bypassed simply by supplying the parameter with an empty value, rather than needing to guess a "correct" one.

### PHP Type Juggling

Natas 23 and 24 demonstrate two variants of PHP's loose-comparison ("type juggling") weaknesses — numeric-string coercion with `strstr()` combined with `>`, and `strcmp()` returning `NULL` (falsy) when passed an array instead of a string.

### LFI + Log Poisoning (RCE)

Natas 25 demonstrates escalating a Local File Inclusion vulnerability into Remote Code Execution by injecting PHP code into a request header (`User-Agent`) that gets written into a server-side log file, then including that log file through the LFI sink.

### Insecure PHP Object Deserialization

Natas 26 demonstrates PHP Object Injection: crafting a serialized `Logger` object with attacker-controlled `exitMsg`/`logFile` fields and passing it through `unserialize()` via a cookie, so that the object's `__destruct()` magic method writes a PHP web shell to disk.

---

# 🛡️ Defensive Security Lessons

Every offensive technique in this repository is paired with a defensive lesson.

| Weakness                      | Defensive Approach                                          |
| ------------------------------ | ------------------------------------------------------------ |
| Source disclosure              | Never expose secrets in client-side code                     |
| Cookie tampering               | Use signed/integrity-protected session data                  |
| Header spoofing                | Never trust client-controlled headers for authorization      |
| LFI                             | Use strict allow-lists for file selection                    |
| LFI + log poisoning             | Never allow log files to be reachable via an include path    |
| SQL Injection                   | Use parameterized queries                                    |
| Command Injection               | Avoid shell execution with user input                        |
| File Upload                     | Validate content server-side and isolate uploads             |
| Session attacks                 | Use unpredictable cryptographic session identifiers          |
| Shared session state            | Never share session storage between apps of differing trust  |
| Broken redirect/access logic    | Fail closed; explicitly validate parameter presence and type |
| PHP type juggling                | Use strict comparison (`===`) and explicit type checks       |
| Insecure deserialization        | Never call `unserialize()` on user-controlled input           |
| Information disclosure          | Minimize sensitive errors and exposed files                  |
| Weak filtering                  | Prefer strong allow-lists and secure APIs                    |

The initial Natas documentation repeatedly emphasizes that client-side controls, exposed files, unsafe `include()` calls, shell commands and blacklist-based filtering can all create exploitable weaknesses. The Levels 21–26 documentation extends this to shared session trust boundaries, application logic flaws, PHP's loose type system, and unsafe deserialization.

---

# 📸 Evidence-Based Documentation

Each level will contain screenshots showing relevant evidence such as:

* Initial application behavior
* Source-code findings
* Burp Suite requests
* Modified parameters
* Cookies
* HTTP headers
* Payload testing
* Successful exploitation
* Final result

## The existing walkthroughs already use screenshots alongside the relevant steps, including Burp Suite demonstrations for Natas 13, 15, 17, 18, 19, 20, 21, 22, 23, 24, 25 and 26.

# 📊 Learning Progression

```text
BEGINNER
   │
   ├── Source Code
   ├── HTML / JavaScript
   ├── Directory Enumeration
   ├── robots.txt
   ├── HTTP Headers
   └── Cookies
          │
          ▼
INTERMEDIATE
   │
   ├── Source Disclosure
   ├── LFI
   ├── Encoding
   ├── Command Injection
   ├── Filter Bypass
   └── File Upload
          │
          ▼
ADVANCED
   │
   ├── XOR Cryptanalysis
   ├── SQL Injection
   ├── Blind SQLi
   ├── Time-Based SQLi
   ├── Command Injection Oracles
   ├── Session Attacks
   └── Custom Session Handling
          │
          ▼
EXPERT
   │
   ├── Shared Session Hijacking
   ├── Access-Control Logic Flaws
   ├── PHP Type Juggling
   ├── LFI → RCE via Log Poisoning
   └── Insecure Deserialization (PHP Object Injection)
          │
          ▼
COMPLETE NATAS JOURNEY
```

---

# 🚀 Future Work

As I progress through the remaining levels, this repository will be expanded with:

* [x] Natas 21–26
* [ ] Natas 27–30
* [ ] Natas 31–34
* [ ] Individual level writeups
* [ ] Burp Suite screenshots
* [ ] Python automation scripts
* [ ] Vulnerability classification
* [ ] OWASP Top 10 mapping
* [ ] MITRE ATT&CK mapping where applicable
* [ ] Defensive remediation
* [ ] Lessons learned
* [ ] Final Natas security assessment summary

---

# 🏆 Final Goal

The objective is to complete the currently available Natas progression and transform the individual challenges into a structured **web application security portfolio project**.

By the end, this repository should demonstrate not only:

> **"I completed a CTF."**

but:

> **"I can identify, analyze, reproduce, document and explain real-world web application security vulnerabilities in an authorized environment."**

---

# ⚠️ Responsible Disclosure & Legal Notice

This repository is intended strictly for:

* OverTheWire
* Capture-the-Flag competitions
* Personal cybersecurity laboratories
* Authorized penetration-testing environments
* Security education

Do **not** apply these techniques against systems, applications or networks without explicit authorization.

---

# 🌐 Official Lab

**OverTheWire — Natas**

[OverTheWire Natas](https://overthewire.org/wargames/natas/?utm_source=chatgpt.com)

The official Natas pages currently document the progression through **Natas 33 → Natas 34**.

---

# 📈 Progress

```text
Natas 00 → 10   ████████████████████ 100%
Natas 11 → 20   ████████████████████ 100%
Natas 21 → 26   ████████████████████ 100%
Natas 27 → 34   ░░░░░░░░░░░░░░░░░░░░   0%
```

This progress section should be updated as each remaining lab is completed.

---

## 🔐 Cybersecurity Journey

**Learn → Enumerate → Analyze → Exploit → Automate → Remediate → Document**

<p align="center">
  <b>Built as a practical web-security learning portfolio.</b>
</p>
