# 📦 Screw The Box

> A personal documentation project for working through SecrewTheBox machines — step by step, mistake by mistake.

---

## 🧠 What Is This?

**Screw The Box** is a hands-on learning repository where I document my journey through [SecrewTheBox] machines. Each machine gets its own dedicated folder with a full write-up covering the entire process — from initial reconnaissance all the way to root.

This isn't a polished cheat sheet. It's a real learning journal — including dead ends, wrong turns, and the "aha" moments that come with them.

---

## 🎯 Why This Exists

- To **understand** every step of the process, not just copy commands
- To **build a reference** I can revisit and learn from over time
- To **share knowledge** with anyone who's learning offensive security and needs a walkthrough that actually explains the *why*, not just the *what*
- Because machines are hard, and writing things down makes them stick

---

## 📁 Repository Structure

Each machine is documented in its own folder, named after the machine itself.

```
Screw-The-Box/
│
├── README.md               ← You are here
│
├── MachineName/
│   └── README.md           ← Full write-up for that machine
│
├── AnotherMachine/
│   └── README.md
│
└── ...
```

---

## 📝 What Each Write-Up Covers

Every machine write-up follows a consistent structure:

| Section | Description |
|---|---|
| **Machine Info** | Name, OS, difficulty, release date |
| **Tools Used** | All tools used throughout the process |
| **Reconnaissance** | Port scanning, service enumeration |
| **Enumeration** | Deeper digging into discovered services |
| **Exploitation** | How initial access was gained |
| **Privilege Escalation** | Path from user to root/system |
| **Flags** | User and root flag locations (redacted) |
| **Key Takeaways** | What I learned from this machine |

---

## ⚠️ Disclaimer

- This repository is **strictly for educational purposes**
- All machines documented here are from **SecrewTheBox**, a legal and ethical penetration testing platform
- Techniques discussed should **only** be used in authorised environments
- Never use these methods against systems you do not have explicit permission to test

---

## 🛠️ Tools You'll See Frequently

- `nmap` — Port and service scanning
- `gobuster` / `ffuf` — Directory and file fuzzing
- `nikto` — Web vulnerability scanning
- `netcat` / `pwncat` — Shells and listeners
- `metasploit` — Exploitation framework
- `linpeas` / `winpeas` — Privilege escalation enumeration
- `burpsuite` — Web traffic interception
- `john` / `hashcat` — Password cracking
- and whatever else the machine throws at me...

---

## 🚀 Getting Started

If you're new to SecrewTheBox or CTF-style machines, here's the general flow you'll see in every write-up:

1. **Scan** — Find open ports and services
2. **Enumerate** — Understand what's running and look for weaknesses
3. **Exploit** — Leverage a vulnerability to gain access
4. **Escalate** — Move from a low-privilege user to root/admin
5. **Document** — Write it all down so it actually sticks

---

## 📬 Contributions & Feedback

This is primarily a personal learning project, but if you spot an error, have a better approach, or want to discuss a machine — feel free to open an issue or drop a message. Learning is better when it's shared.

---

*Happy Hacking. Stay legal. Stay curious.* 🔐
