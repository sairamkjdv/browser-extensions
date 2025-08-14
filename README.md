# Task 7 - Identify and Remove Suspicious Browser Extensions

## Objective
To learn how to identify potentially harmful browser extensions and remove them to improve browser security.

## Steps Performed
1. Opened Chrome Extensions Manager: Menu → Extensions.
2. Reviewed all installed extensions.
3. Checked each extension's developer source, permissions, and user reviews online.
4. Identified extensions with high permissions or low trust factors.
5. Removed unused/suspicious extensions.
6. Restarted the browser for changes to take effect.

## Installed Extensions
A full list of all installed extensions before removal is documented in  
[`installed_extensions.txt`](./installed_extensions.txt)

## Suspicious or Unnecessary Extensions Found
- **Gmail-GPT** – Requires permission to read/write Gmail data; not from official Gmail developer.
- **SignalHire** – Requests access to all browsing data; potential privacy risk.
- **MyLens AI** – High-level access to all web content; low trust developer.
- **YouTube Summary with ChatGPT & Claude** – Requires access to all YouTube data; check developer authenticity.
- **Cookie-Editor** – Can read and modify all cookies (session hijacking risk if compromised).
- **Meta Pixel Helper** – Developer tool; may not be needed for regular browsing.

## Extensions Removed
The list of extensions removed during this task is documented in  
[`removed_extensions.txt`](./removed_extensions.txt)

## Outcome
Unnecessary and high-permission extensions removed, reducing attack surface and improving overall browser privacy and security.

---

> Task successfully completed as part of the Elevate Labs Cyber Security Internship Program.
