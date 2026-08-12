# Hi, I'm Alex

**Albuquerque, NM** · IT support · [ahlyxlabs.com](https://ahlyxlabs.com)

CompTIA **A+** and **Network+** certified. Working toward an A.A.S. in Computer
Information Systems (cybersecurity concentration) at CNM, and studying for Security+.

I'm looking for an entry-level help desk / IT support role.

Most of what's on this profile started the same way: I ran into something I didn't
understand, got curious, and built a tool to figure it out. Studying for A+ turned into
writing a hardware monitor so the specs had something concrete attached to them. Reading
about industrial control systems turned into a compiler project. I learn by building,
and I tend not to stop at "good enough to pass the exam question."

Before IT, I spent two years in food service and got promoted to crew trainer which
mostly meant explaining the same system to a lot of different people until it clicked
for each of them. That's turned out to be the most directly transferable thing I've done.

---

## Certifications

| | |
|---|---|
| **CompTIA Network+** | Issued August 2026 |
| **CompTIA A+** | Issued August 2026 |
| **CompTIA Security+** | In progress — expected December 2026 |

---

## What I work with

| | |
|---|---|
| **Networking** | TCP/IP, DNS, DHCP, subnetting, ARP, packet capture, port scanning |
| **Systems** | Windows, Linux (Ubuntu), hardware diagnostics and repair, virtualization |
| **Python** | My main language. Most of my tools are FastAPI backends. |
| **Other** | Git, technical documentation, end-user support and training |

A few of my projects are written in Go/Rust. I built those with significant AI assistance and
I'm still early with the languages. I'd rather say that plainly than have it read as
something it isn't.

---

## Projects

Everything below is live at [ahlyxlabs.com](https://ahlyxlabs.com) — you can click
through and use it, no or minimal setup required.

**[Network Scanner](https://github.com/Ahlyx/Network-Scanner)** · Python
Finds live hosts on a subnet via ARP sweep, scans each for open TCP ports, and flags
industrial control system protocols. Runs as either a CLI tool or a web dashboard over
shared scan logic.

**[Hardware Dashboard](https://github.com/Ahlyx/Hardware-Dashboard)** · Python
Live CPU, RAM, disk, and network metrics. Built while studying A+ Core 1 — the README
maps each feature back to the concept it demonstrates. Later hardened with rate limiting
and restricted CORS after I found an XSS issue in my own frontend.

**[Security Enrichment API](https://github.com/Ahlyx/security-enrichment-api)** · Python
Looks up an IP across several threat intelligence sources and returns one combined
answer instead of four browser tabs.

**[PCAP Agent](https://github.com/Ahlyx/pcap-agent)**
Captures live network traffic and flags beaconing, port scans, DNS tunneling, and MAC
spoofing, streaming results to a browser dashboard.

**[Baptisia](https://github.com/Ahlyx/Baptisia)**
A programming language for industrial control systems where the compiler refuses to
generate code that runs control logic before safety checks. Well past what any job needs
— it's here because it's the project I'm proudest of.

---

## Security research

I publish independent findings at
[ahlyxlabs.com/research](https://ahlyxlabs.com/research), following responsible
disclosure: vendors get notified first and a 30-day window before anything goes public.
Two writeups so far, both from static analysis of public source code.

---

## Get in touch

📧 [alex@ahlyxlabs.com](mailto:alex@ahlyxlabs.com) · 🌐 [ahlyxlabs.com](https://ahlyxlabs.com)
