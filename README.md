<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Eduardo%20Romera&fontAlign=50&fontAlignY=38&desc=Cybersecurity%20%7C%20Offensive%20Security%20%7C%20Windows%20Internals&descAlignY=58&animation=fadeIn" width="100%" />

<a href="https://github.com/wolfpackc">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=900&center=true&vCenter=true&width=900&lines=%3E+Initializing+security+profile...;%3E+Loading+Windows+Internals...+%5BOK%5D;%3E+Loading+Active+Directory...+%5BOK%5D;%3E+Loading+Network+Security...+%5BOK%5D;%3E+Learning+by+building%2C+breaking+and+documenting." alt="Animated terminal" />
</a>

![eJPT](https://img.shields.io/badge/Certification-eJPT-111111?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Offensive%20Security-111111?style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-Internals-111111?style=for-the-badge&logo=windows11)
![AD](https://img.shields.io/badge/Active-Directory-111111?style=for-the-badge)

</div>

---

## `profile.json`

```json
{
  "name": "Eduardo Romera",
  "role": "Cybersecurity / Offensive Security",
  "background": "Desarrollo de Aplicaciones Web (DAW)",
  "certifications": ["eJPT"],
  "current_focus": [
    "Active Directory",
    "Kerberos",
    "Windows Internals",
    "Privilege Escalation",
    "Network Security",
    "Pentesting Methodology"
  ],
  "low_level": ["C", "Assembly", "Win32 API", "Drivers"],
  "approach": "Understand what happens internally, reproduce it in a lab, document it."
}
```

## `about_me.log`

```text
[+] Formación en desarrollo de aplicaciones web
[+] Certificación eJPT
[+] Laboratorios de pentesting Windows / Linux
[+] Active Directory y Kerberos
[+] Windows Internals, tokens, privilegios y servicios
[+] Redes, enumeración y movimiento lateral
[+] C / Assembly como base de sistemas y exploit development
[+] Documentación técnica y write-ups reproducibles
```

Mi forma de aprender es principalmente práctica: construyo laboratorios, documento lo que estudio y trato de comprender **por qué una técnica funciona internamente**, no solo qué comando ejecutarla.

> Todo el contenido de seguridad de estos repositorios está orientado a laboratorios autorizados, investigación y aprendizaje.

---

## `active_directory.json`

```json
{
  "directory_services": ["Active Directory", "LDAP", "DNS"],
  "authentication": ["Kerberos", "NTLM"],
  "kerberos": ["TGT", "TGS", "SPN", "AS-REP", "Kerberoasting"],
  "movement": ["SMB", "WinRM", "SQL", "Pass-the-Hash", "Pass-the-Ticket"],
  "analysis": ["Users", "Groups", "Computers", "ACLs", "BloodHound"],
  "goal": "Understand identity, permissions and attack paths inside a domain."
}
```

### Repositorios relacionados

- [`Active-Directory`](https://github.com/wolfpackc/Active-Directory) — conceptos, Kerberos, cuentas, servicios y metodología.
- [`eCPPtv3`](https://github.com/wolfpackc/eCPPtv3) — preparación y documentación orientada a pentesting profesional.
- [`eCPPTv3-Notes`](https://github.com/wolfpackc/eCPPTv3-Notes) — material de estudio y referencia para eCPPTv3.
- [`NetExec-CrackMapExec`](https://github.com/wolfpackc/NetExec-CrackMapExec) — notas y uso de herramientas para entornos Windows/AD.

---

## `windows_internals.json`

```json
{
  "topics": [
    "Processes & Threads",
    "Access Tokens",
    "Primary vs Impersonation Tokens",
    "Privileges & Integrity Levels",
    "Windows Services",
    "UAC",
    "Drivers",
    "WinDbg"
  ],
  "languages": ["C", "PowerShell", "Assembly"],
  "objective": "Move from tool usage to operating-system understanding."
}
```

### [`WINDOWS`](https://github.com/wolfpackc/WINDOWS)

Mi base de conocimiento principal sobre Windows desde una perspectiva de seguridad: procesos, hilos, tokens, privilegios, servicios, drivers, UAC, debugging y estructuras internas.

### [`TokenSteal`](https://github.com/wolfpackc/TokenSteal)

Proyecto práctico en C orientado al estudio de **Access Tokens** y APIs de Windows, incluyendo `OpenProcessToken`, `DuplicateTokenEx`, impersonación, SIDs, Integrity Levels y privilegios.

### [`power-shell`](https://github.com/wolfpackc/power-shell)

Automatización, administración de Windows, networking y scripting aplicado a seguridad.

---

## `network_security.json`

```json
{
  "recon": ["Nmap", "Wireshark"],
  "services": ["SMB", "FTP", "SSH", "HTTP/S"],
  "network_security": ["Bettercap", "ARP", "MITM labs", "BPF filters"],
  "wireless": ["802.11", "Wi-Fi reconnaissance", "Packet capture"],
  "lab_rule": "Isolated and authorized environments only"
}
```

- [`Bettercap`](https://github.com/wolfpackc/Bettercap) — reconocimiento, sniffing, ARP, MITM en laboratorio, filtros BPF y caplets.
- [`WIFI`](https://github.com/wolfpackc/WIFI) — fundamentos 802.11, reconocimiento y análisis de seguridad inalámbrica.
- [`HackTheBox-CTF-Writeups`](https://github.com/wolfpackc/HackTheBox-CTF-Writeups) — metodología de enumeración, explotación y post-explotación.

---

## `low_level.json`

```json
{
  "C": ["Memory", "Pointers", "Processes", "Native APIs"],
  "Assembly": ["Registers", "Stack", "Calling conventions", "x86/x64"],
  "why": "Build foundations for Windows Internals, reverse engineering and exploit development."
}
```

- [`C`](https://github.com/wolfpackc/C)
- [`assembly-tutorial`](https://github.com/wolfpackc/assembly-tutorial)
- [`AZURE`](https://github.com/wolfpackc/AZURE)

---

## `methodology.sh`

```bash
#!/usr/bin/env bash

recon
  -> enumerate
  -> identify_attack_surface
  -> gain_access
  -> post_exploitation
  -> privilege_escalation
  -> lateral_movement
  -> document
```

En cada técnica intento responder a cuatro preguntas:

1. **¿Qué está ocurriendo?**
2. **¿Por qué funciona?**
3. **¿Qué hace internamente el sistema operativo o protocolo?**
4. **¿Cómo podría detectarse o mitigarse?**

---

## `stack.json`

```json
{
  "security": [
    "Nmap", "Metasploit", "Wireshark", "Bettercap", "Burp Suite",
    "Kali Linux", "Windows", "Linux", "SMB", "Kerberos", "LDAP"
  ],
  "windows_low_level": [
    "Windows Internals", "WinDbg", "PowerShell", "C", "Assembly",
    "Win32 API", "Services", "Access Tokens", "Drivers"
  ],
  "development": [
    "PHP", "JavaScript", "HTML", "CSS", "Bootstrap",
    "Python", "Java", "MySQL / MariaDB", "Git"
  ],
  "cloud_infra": ["AWS", "Azure", "Apache", "IIS"]
}
```

---

## `featured_repositories`

| Área | Repositorio |
|---|---|
| Active Directory | [`Active-Directory`](https://github.com/wolfpackc/Active-Directory) |
| eCPPTv3 | [`eCPPtv3`](https://github.com/wolfpackc/eCPPtv3) |
| Windows Internals | [`WINDOWS`](https://github.com/wolfpackc/WINDOWS) |
| Windows Token Security | [`TokenSteal`](https://github.com/wolfpackc/TokenSteal) |
| CTF / Pentesting | [`HackTheBox-CTF-Writeups`](https://github.com/wolfpackc/HackTheBox-CTF-Writeups) |
| Network Security | [`Bettercap`](https://github.com/wolfpackc/Bettercap) |
| Wi-Fi Security | [`WIFI`](https://github.com/wolfpackc/WIFI) |
| PowerShell | [`power-shell`](https://github.com/wolfpackc/power-shell) |
| C / Low Level | [`C`](https://github.com/wolfpackc/C) |
| Assembly | [`assembly-tutorial`](https://github.com/wolfpackc/assembly-tutorial) |
| Cloud | [`AZURE`](https://github.com/wolfpackc/AZURE) |

---

<div align="center">



<br><br>

```text

Prefiero dominar un campo pequeño que tener conocimientos superficiales en treinta.

```

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer" width="100%" />

</div>
