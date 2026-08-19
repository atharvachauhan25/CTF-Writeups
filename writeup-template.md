# <Machine / Room Name> — CTF Writeup

**Platform:** <TryHackMe / HackTheBox / VulnHub / CyLabAcademy / ...>
**Category:** <Boot2Root / Web / CTF Event / etc.>
**Difficulty:** <Easy / Medium / Hard>
**Date:** <YYYY-MM-DD>

## Overview

<2–4 sentences: what the box/challenge is, what the vulnerable service or
bug class is, and what the end result was (e.g. "root shell via X").>

**Final result:** <one-line summary of the win condition, e.g. "Remote
root shell via CVE-XXXX-XXXXX">

---

## 1. Reconnaissance

### Host discovery

```
<command>
```

| IP | Role |
|----|------|
|    |      |

### Port/service scan

```
<command>
```

| Port | Service | Version |
|------|---------|---------|
|      |         |         |

---

## 2. Enumeration

### <Service/Port A>

```
<commands + relevant output>
```

<Findings. Note explicitly if this was a dead end and why.>

### <Service/Port B>

```
<commands + relevant output>
```

<Findings.>

<Add more subsections as needed — one per service investigated.>

---

## 3. Initial Access / Exploitation

<What CVE / misconfig / logic bug was found, and how it was confirmed
(searchsploit, Metasploit, manual testing, source review, etc.)>

```
<exploit commands / payload / script>
```

```
<relevant output showing the exploit landing>
```

### Verification

```
whoami
<result>
```

---

## 4. Privilege Escalation

<Steps taken to go from initial foothold to root/admin/system. If
initial access already granted full compromise, state that explicitly
here instead of deleting the section — e.g. "Not required — initial
exploit landed directly as root.">

---

## 5. Root Cause

- <Underlying technical reason the vulnerability exists>
- <Any contributing factors — missing mitigations, outdated software,
  misconfiguration>

## 6. Remediation

- <Patch/upgrade recommendation>
- <Config hardening recommendation>
- <Network-level mitigation>

---

## Tools Used

`<tool1>`, `<tool2>`, `<tool3>`
