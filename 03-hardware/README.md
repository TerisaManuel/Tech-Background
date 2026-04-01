# 🖥️ Hardware & Technical Experience

This section proves real technical capability, not just theory.
Every task here was done hands-on, documented, and can be explained step by step.

---

## 📸 1. Photo Documentation — Laptop Disassembly & Reassembly

**Device:** Lenovo V14-IGL (Model: 82C2)

A full video walkthrough of disassembling and reassembling a laptop,
identifying every internal component and explaining its function.

🎬 [Watch the full video here](YOUR-YOUTUBE-LINK-HERE)

**What the video covers:**
- Pre-disassembly safety checks — powered off, unplugged, face down
- Removing the bottom panel and identifying internal components
- Heat pipe — draws heat away from the Intel Celeron N4020 processor
- Battery (35Wh lithium-ion) — disconnected first to cut all power to the board
- Motherboard — the central circuit board everything connects through
- RAM (4GB DDR4-2400) — soldered directly, cannot be upgraded
- WiFi card — handles all wireless connectivity
- M.2 SSD slot — where the operating system and files are stored
- Full reassembly and power on to verify everything is functioning

**Why this matters:** Anyone can read about a motherboard — this shows I can
identify one, explain it, and work around it safely.

---

## 🔍 2. Problem & Solution — Cisco Packet Tracer

**Tool:** Cisco Packet Tracer — industry standard network simulation software

**The Problem:**
A laptop on a SOHO network cannot communicate with other devices due to
an incorrect default gateway — one of the most common issues an IT support
technician encounters.

**The Solution:**
- Built a SOHO network with a wireless router, PC, two laptops and a printer
- Configured the router with SSID, WPA2 security and DHCP
- Deliberately misconfigured Laptop0 with the wrong default gateway
- Used `ipconfig` to identify the misconfiguration
- Used `ping` to confirm connectivity had failed
- Corrected the gateway and verified connectivity was restored using `ping`

🎬 [Watch the Loom walkthrough here](YOUR-LOOM-LINK-HERE)

See the `packet-tracer/` folder for all screenshots.

**Why this matters:** This proves I can simulate, identify, and fix a real
network problem systematically — not just guess.

---

## 🔧 3. Build Walkthrough — Ethernet Cable

A step-by-step build of a functioning ethernet cable from scratch.

**Steps:**
1. Stripped the outer casing to expose the inner wires
2. Arranged wires in T568B standard order
3. Trimmed wires to even length and inserted into RJ45 connector
4. Crimped the connector using a crimping tool
5. Tested cable for connectivity — passed

See the `photos/` folder for before, during and after photos.

**Why this matters:** Physical network skills are foundational for IT support.
Building a cable from scratch proves I understand how networks are physically
connected.

---

## 🛠️ 4. Troubleshooting Log

| Issue | What I tried | Outcome |
|---|---|---|
| Laptop0 could not ping PC0 | Checked IP configuration — found incorrect default gateway | Corrected gateway to 192.168.0.1 — connectivity restored |
| Ping to printer timed out | Checked printer IP via Config tab — confirmed DHCP assigned 192.168.0.105 | Identified that Packet Tracer printer blocks ICMP by default — redirected test to router ping instead |
| [Add real hardware example] | [Steps you took] | [How it was resolved] |

---

## 💡 Key Takeaway

Every task here was done hands-on. I didn't just read about it —
I did it, documented it, and can explain why each step matters.
