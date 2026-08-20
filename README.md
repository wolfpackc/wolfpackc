# Eduardo Romera | Cybersecurity Portfolio

<p align="center">
  <b>eJPT Certified · Offensive Security · Windows Internals · Network Security · Security Research</b>
</p>

<p align="center">
  Building a strong technical foundation across offensive security, Windows internals, networking, scripting and low-level systems.
</p>

---

## 👋 About Me

I am a cybersecurity-focused developer with a background in **Web Application Development (DAW)** and a growing specialization in **offensive security, Windows internals and network security**.

My learning approach is strongly hands-on: I build labs, document what I learn, analyze Windows security mechanisms, practice enumeration and exploitation in controlled environments, and turn the results into structured technical notes and write-ups.

I am especially interested in:

- Windows security internals
- Privilege escalation and token security
- Network reconnaissance and traffic analysis
- Pentesting methodology
- Active Directory and lateral movement concepts
- Web application security
- PowerShell and offensive scripting
- C, Assembly and low-level security concepts
- Defensive understanding of offensive techniques

> All security-related material in my repositories is intended for authorized labs, research and educational environments.

---

## 🏅 Certification

### eJPT — eLearnSecurity Junior Penetration Tester

Hands-on penetration testing certification covering practical skills such as:

- Host and network reconnaissance
- Service enumeration
- Vulnerability identification
- Web application assessment
- Exploitation fundamentals
- Pivoting and network segmentation
- Post-exploitation concepts
- Methodical pentesting workflows

Repository: **[Preparación para la certificación eJPTv2](https://github.com/wolfpackc/Preparacion_para_la_certificacion_eJPTv2)**

---

# 🔥 Featured Cybersecurity Work

## 🪟 Windows Internals & Security

### [WINDOWS](https://github.com/wolfpackc/WINDOWS)

My main knowledge base for understanding Windows from a security perspective.

Topics include:

- Processes and threads
- Access tokens
- Primary vs impersonation tokens
- Privileges and integrity levels
- Token impersonation and duplication
- Windows services and the Service Control Manager
- User-mode services
- Kernel drivers
- UMDF concepts
- UAC
- Windows object security
- Privilege escalation concepts
- Windows debugging and internal structures

The objective is not only to use Windows security tools, but to understand **why the techniques work internally**.

---

## 🎯 Hack The Box / CTF Methodology

### [HackTheBox-CTF-Writeups](https://github.com/wolfpackc/HackTheBox-CTF-Writeups)

Write-ups and notes focused on developing a repeatable attack methodology:

```text
Reconnaissance
      ↓
Enumeration
      ↓
Attack Surface Analysis
      ↓
Exploitation
      ↓
Post-Exploitation
      ↓
Privilege Escalation
      ↓
Documentation
```

Key areas:

- Nmap-driven reconnaissance
- Web enumeration
- SMB / FTP / SSH / HTTP analysis
- Credential discovery
- Linux and Windows targets
- Privilege escalation methodology

---

## 🌐 Bettercap & Network Security

### [Bettercap](https://github.com/wolfpackc/Bettercap)

Structured learning repository covering Bettercap from fundamentals to advanced concepts.

Includes:

- Bettercap architecture
- Network reconnaissance
- `net.recon`
- `net.probe`
- Packet sniffing
- BPF filters
- ARP concepts
- MITM laboratory scenarios
- Caplets
- Troubleshooting
- Wi-Fi / BLE / API overview

The focus is on understanding the network behavior behind each module instead of memorizing commands.

---

## 📡 Wireless Security

### [WIFI](https://github.com/wolfpackc/WIFI)

Notes and experiments around wireless networking and Wi-Fi security concepts.

Areas of interest include:

- 802.11 fundamentals
- Wireless reconnaissance
- Wi-Fi authentication concepts
- Packet capture
- Network security analysis

---

## ⚙️ PowerShell & Windows Automation

### [power-shell](https://github.com/wolfpackc/power-shell)

PowerShell study and experimentation focused on Windows administration, automation and security-oriented scripting.

Related areas:

- Windows automation
- Process interaction
- System information
- Networking
- Security tooling
- PowerShell internals

---

## 🧠 Low-Level Foundations

### [C](https://github.com/wolfpackc/C)

C programming as a foundation for understanding:

- Memory
- Pointers
- Processes
- Native APIs
- Low-level system programming
- Exploit-development concepts

### [assembly-tutorial](https://github.com/wolfpackc/assembly-tutorial)

Assembly notes and exercises aimed at strengthening low-level understanding of:

- CPU instructions
- Registers
- Stack behavior
- Function calls
- Memory addressing
- x86/x64 concepts

These subjects directly support deeper study of reverse engineering, Windows internals and vulnerability research.

---

## ☁️ Cloud & Infrastructure

### [AZURE](https://github.com/wolfpackc/AZURE)

Azure learning repository covering cloud fundamentals and infrastructure concepts relevant to modern security environments.

---

# 🧰 Technical Stack

## Security

`Nmap` · `Metasploit` · `Wireshark` · `Bettercap` · `Burp Suite` · `Kali Linux` · `Windows` · `Linux` · `SMB` · `FTP` · `SSH` · `HTTP/S`

## Windows / Low Level

`Windows Internals` · `WinDbg` · `PowerShell` · `C` · `Assembly` · `Win32 API` · `Services` · `Access Tokens` · `Drivers`

## Development

`PHP` · `JavaScript` · `HTML` · `CSS` · `Bootstrap` · `Python` · `Java` · `MySQL / MariaDB` · `Git`

## Web / Infrastructure

`WordPress` · `Apache` · `IIS` · `XAMPP` · `AWS` · `Azure`

---

# 🧪 Home Lab Philosophy

I use isolated environments to reproduce concepts and understand systems through experimentation.

Typical lab components include:

```text
                    ┌─────────────────┐
                    │      Kali       │
                    │ Attacker / Test │
                    └────────┬────────┘
                             │
                    Isolated Lab Network
                             │
           ┌─────────────────┼─────────────────┐
           │                 │                 │
    ┌──────▼──────┐   ┌──────▼──────┐   ┌────▼─────┐
    │   Windows   │   │    Linux    │   │ Web Apps │
    │   Targets   │   │   Targets   │   │ / CMS    │
    └─────────────┘   └─────────────┘   └──────────┘
```

I try to answer four questions whenever I study a technique:

1. **What is happening?**
2. **Why does it work?**
3. **What does the operating system or protocol do internally?**
4. **How could the behavior be detected or mitigated?**

---

# 🗺️ Current Focus

```text
Cybersecurity
│
├── Offensive Security
│   ├── Reconnaissance
│   ├── Enumeration
│   ├── Web Security
│   ├── Network Attacks
│   └── Privilege Escalation
│
├── Windows Security
│   ├── Windows Internals
│   ├── Tokens & Privileges
│   ├── Services
│   ├── Drivers
│   └── Debugging
│
├── Low Level
│   ├── C
│   ├── Assembly
│   └── Operating System Internals
│
└── Defensive Perspective
    ├── Traffic Analysis
    ├── Attack Detection
    └── Understanding TTPs
```

---

# 🚀 Professional Direction

I am building toward roles where I can combine practical offensive-security knowledge with a strong understanding of operating systems and networks, including areas such as:

- SOC / Security Operations
- Junior Penetration Testing
- Cybersecurity Analysis
- Vulnerability Assessment
- Windows Security Research
- Threat Detection and Investigation

My goal is to continue turning theory into **documented, reproducible hands-on work**.

---

## 📚 Repository Highlights

| Area | Repository |
|---|---|
| Windows Internals | [WINDOWS](https://github.com/wolfpackc/WINDOWS) |
| Pentesting / eJPT | [Preparacion_para_la_certificacion_eJPTv2](https://github.com/wolfpackc/Preparacion_para_la_certificacion_eJPTv2) |
| CTF Write-ups | [HackTheBox-CTF-Writeups](https://github.com/wolfpackc/HackTheBox-CTF-Writeups) |
| Network Security | [Bettercap](https://github.com/wolfpackc/Bettercap) |
| Wi-Fi Security | [WIFI](https://github.com/wolfpackc/WIFI) |
| PowerShell | [power-shell](https://github.com/wolfpackc/power-shell) |
| C / Low Level | [C](https://github.com/wolfpackc/C) |
| Assembly | [assembly-tutorial](https://github.com/wolfpackc/assembly-tutorial) |
| Cloud | [AZURE](https://github.com/wolfpackc/AZURE) |

---

<p align="center">
  <b>Break things in labs. Understand why they break. Learn how to defend them.</b>
</p>
