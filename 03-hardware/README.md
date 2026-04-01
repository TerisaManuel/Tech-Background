# 🖥️ Hardware & Technical Experience

This section proves real technical capability, not just theory.
Every task here was done hands-on, documented, and can be explained step by step.

---

<details>
<summary>📸 Photo Documentation — Laptop Disassembly & Reassembly</summary>
<br>

**Device:** Lenovo V14-IGL (Model: 82C2)

A full video walkthrough of disassembling and reassembling a laptop,
identifying every internal component and explaining its function.

[![Laptop Disassembly & Component Identification](./Laptop%20Disassembly.png)](https://youtu.be/tm8huvp6ip8?si=lZnC4YoHjupjtlMy)

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

</details>

---

<details>
<summary>🔍 Problem & Solution — Cisco Packet Tracer</summary>
<br>

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
- Corrected the gateway and verified connectivity using `ping`

[![Cisco Packet Tracer Walkthrough](./SOHO.png)](https://www.loom.com/share/4f58dd1fd5104b54a9f2f609cc92fb0b)

</details>

---

<details>
<summary>🛠️ Troubleshooting Log</summary>
<br>

| Issue | What I tried | Outcome |
|---|---|---|
| Laptop0 could not ping PC0 | Checked IP configuration — found incorrect default gateway | Corrected gateway to 192.168.0.1 — connectivity restored |
| Ping to printer timed out | Checked printer IP via Config tab — confirmed DHCP assigned 192.168.0.105 | Identified that Packet Tracer printer blocks ICMP by default — redirected test to router ping instead |

</details>

---

<details>
<summary>💡 Key Takeaway</summary>
<br>

Every task here was done hands-on. I didn't just read about it —
I did it, documented it, and can explain why each step matters.

</details>
