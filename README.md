# Eduardo Romera | Cybersecurity Portfolio

<p align="center">
  <b>eJPT Certified · Offensive Security · Windows Internals · Network Security · Security Research</b>
</p>

<p align="center">
  Perfil técnico centrado en ciberseguridad ofensiva, análisis de Windows, redes, scripting y fundamentos de bajo nivel.
</p>

---

## Sobre mí

Soy desarrollador con formación en **Desarrollo de Aplicaciones Web (DAW)** y una especialización cada vez más profunda en **ciberseguridad ofensiva, Windows Internals y seguridad de redes**.

Mi forma de aprender es principalmente práctica: construyo laboratorios, documento lo que estudio, analizo mecanismos de seguridad de Windows, practico reconocimiento y explotación en entornos controlados y convierto los resultados en notas técnicas estructuradas y write-ups.

Me interesan especialmente:

- Windows Internals y seguridad del sistema operativo
- Tokens, privilegios e impersonación
- Escalada de privilegios
- Reconocimiento y análisis de redes
- Metodología de pentesting
- Seguridad web
- PowerShell y scripting orientado a seguridad
- C, Assembly y fundamentos de bajo nivel
- Comprensión defensiva de técnicas ofensivas

> Todo el contenido relacionado con seguridad de mis repositorios está orientado a laboratorios autorizados, investigación y aprendizaje.

---

## Certificación

### eJPT — eLearnSecurity Junior Penetration Tester

Certificación práctica de pentesting que cubre áreas como:

- Reconocimiento de hosts y redes
- Enumeración de servicios
- Identificación de vulnerabilidades
- Evaluación de aplicaciones web
- Fundamentos de explotación
- Pivoting y segmentación de red
- Post-explotación
- Metodología de pentesting

Repositorio relacionado: **[Preparación para la certificación eJPTv2](https://github.com/wolfpackc/Preparacion_para_la_certificacion_eJPTv2)**

---

# Proyectos destacados de ciberseguridad

## Windows Internals & Security

### [WINDOWS](https://github.com/wolfpackc/WINDOWS)

Mi principal base de conocimiento para entender Windows desde una perspectiva de seguridad.

Temas incluidos:

- Procesos e hilos
- Access Tokens
- Primary Token vs Impersonation Token
- Privilegios e Integrity Levels
- Impersonación y duplicación de tokens
- Servicios de Windows y Service Control Manager
- Servicios en user mode
- Drivers en kernel mode
- UMDF
- UAC
- Seguridad de objetos de Windows
- Conceptos de escalada de privilegios
- Depuración con WinDbg
- Estructuras internas de Windows

El objetivo no es solo aprender herramientas, sino entender **por qué las técnicas funcionan internamente**.

### [TokenSteal](https://github.com/wolfpackc/TokenSteal)

Proyecto práctico en C para estudiar el funcionamiento de los **Access Tokens de Windows** y su uso en escenarios controlados de laboratorio.

El proyecto implementa y documenta conceptos como:

- Enumeración y apertura de procesos
- `OpenProcessToken`
- Privilegios como `SeDebugPrivilege` y `SeImpersonatePrivilege`
- Duplicación de tokens mediante `DuplicateTokenEx`
- Diferencia entre `Primary Token` e `Impersonation Token`
- Impersonación del hilo actual
- Inspección de SID, Integrity Level y privilegios habilitados
- Creación de un nuevo proceso utilizando un token primario duplicado
- Manejo de procesos protegidos y escenarios donde el acceso al token es denegado

El objetivo del proyecto es trasladar la teoría de Windows Internals a código nativo y observar directamente cómo interactúan procesos, hilos, privilegios y tokens en user mode.

---

## Hack The Box / CTF Methodology

### [HackTheBox-CTF-Writeups](https://github.com/wolfpackc/HackTheBox-CTF-Writeups)

Write-ups y notas orientadas a desarrollar una metodología de ataque repetible:

```text
Reconocimiento
      ↓
Enumeración
      ↓
Análisis de superficie de ataque
      ↓
Explotación
      ↓
Post-explotación
      ↓
Escalada de privilegios
      ↓
Documentación
```

Áreas principales:

- Reconocimiento con Nmap
- Enumeración web
- Análisis de SMB / FTP / SSH / HTTP
- Descubrimiento de credenciales
- Objetivos Linux y Windows
- Metodología de escalada de privilegios

---

## Bettercap & Network Security

### [Bettercap](https://github.com/wolfpackc/Bettercap)

Repositorio de estudio estructurado sobre Bettercap, desde fundamentos hasta conceptos avanzados.

Incluye:

- Arquitectura de Bettercap
- Reconocimiento de red
- `net.recon`
- `net.probe`
- Sniffing de tráfico
- Filtros BPF
- Fundamentos de ARP
- Escenarios MITM en laboratorio
- Caplets
- Troubleshooting
- Introducción a Wi-Fi / BLE / API

El enfoque es comprender qué ocurre en la red detrás de cada módulo y no limitarse a memorizar comandos.

---

## Wireless Security

### [WIFI](https://github.com/wolfpackc/WIFI)

Notas y prácticas sobre redes inalámbricas y seguridad Wi-Fi.

Áreas de estudio:

- Fundamentos de 802.11
- Reconocimiento inalámbrico
- Autenticación Wi-Fi
- Captura de paquetes
- Análisis de seguridad de redes inalámbricas

---

## PowerShell & Windows Automation

### [power-shell](https://github.com/wolfpackc/power-shell)

Estudio y experimentación con PowerShell aplicados a administración de Windows, automatización y seguridad.

Áreas relacionadas:

- Automatización en Windows
- Interacción con procesos
- Información del sistema
- Networking
- Scripting de seguridad
- Fundamentos internos de PowerShell

---

## Fundamentos de bajo nivel

### [C](https://github.com/wolfpackc/C)

Programación en C como base para comprender:

- Memoria
- Punteros
- Procesos
- APIs nativas
- Programación de sistemas
- Fundamentos de exploit development

### [assembly-tutorial](https://github.com/wolfpackc/assembly-tutorial)

Notas y ejercicios de Assembly orientados a reforzar conocimientos sobre:

- Instrucciones de CPU
- Registros
- Stack
- Llamadas a funciones
- Direccionamiento de memoria
- Conceptos x86/x64

Estos conocimientos sirven como base para profundizar en reverse engineering, Windows Internals y análisis de vulnerabilidades.

---

## Cloud & Infrastructure

### [AZURE](https://github.com/wolfpackc/AZURE)

Repositorio de aprendizaje sobre Azure y conceptos de infraestructura cloud relevantes para entornos modernos de seguridad.

---

# Stack técnico

## Seguridad

`Nmap` · `Metasploit` · `Wireshark` · `Bettercap` · `Burp Suite` · `Kali Linux` · `Windows` · `Linux` · `SMB` · `FTP` · `SSH` · `HTTP/S`

## Windows / Bajo nivel

`Windows Internals` · `WinDbg` · `PowerShell` · `C` · `Assembly` · `Win32 API` · `Services` · `Access Tokens` · `Drivers`

## Desarrollo

`PHP` · `JavaScript` · `HTML` · `CSS` · `Bootstrap` · `Python` · `Java` · `MySQL / MariaDB` · `Git`

## Web / Infraestructura

`WordPress` · `Apache` · `IIS` · `XAMPP` · `AWS` · `Azure`

---

# Metodología de laboratorio

Trabajo con entornos aislados para reproducir conceptos y comprender sistemas mediante experimentación.

Una topología típica de laboratorio puede ser:

```text
                    ┌─────────────────┐
                    │      Kali       │
                    │ Attacker / Test │
                    └────────┬────────┘
                             │
                    Red de laboratorio
                             │
           ┌─────────────────┼─────────────────┐
           │                 │                 │
    ┌──────▼──────┐   ┌──────▼──────┐   ┌────▼─────┐
    │   Windows   │   │    Linux    │   │ Web Apps │
    │   Targets   │   │   Targets   │   │ / CMS    │
    └─────────────┘   └─────────────┘   └──────────┘
```

Intento responder siempre a cuatro preguntas cuando estudio una técnica:

1. **¿Qué está ocurriendo?**
2. **¿Por qué funciona?**
3. **¿Qué hace internamente el sistema operativo o protocolo?**
4. **¿Cómo podría detectarse o mitigarse?**

---

# Áreas de estudio actuales

```text
Ciberseguridad
│
├── Seguridad ofensiva
│   ├── Reconocimiento
│   ├── Enumeración
│   ├── Seguridad web
│   ├── Ataques de red
│   └── Escalada de privilegios
│
├── Seguridad de Windows
│   ├── Windows Internals
│   ├── Tokens y privilegios
│   ├── Servicios
│   ├── Drivers
│   └── Debugging
│
├── Bajo nivel
│   ├── C
│   ├── Assembly
│   └── Internals de sistemas operativos
│
└── Perspectiva defensiva
    ├── Análisis de tráfico
    ├── Detección de ataques
    └── Comprensión de TTPs
```

---

# Orientación profesional

Estoy orientando mi perfil hacia puestos donde pueda combinar conocimientos prácticos de seguridad ofensiva con una comprensión sólida de sistemas operativos y redes, especialmente en áreas como:

- SOC / Security Operations
- Pentesting junior
- Análisis de ciberseguridad
- Evaluación de vulnerabilidades
- Seguridad de Windows
- Threat Detection e investigación

Mi objetivo es seguir convirtiendo teoría en **trabajo práctico, documentado y reproducible**.

---

## Repositorios destacados

| Área | Repositorio |
|---|---|
| Windows Internals | [WINDOWS](https://github.com/wolfpackc/WINDOWS) |
| Windows Token Security | [TokenSteal](https://github.com/wolfpackc/TokenSteal) |
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
