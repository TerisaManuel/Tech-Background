# 🖥️ Tech & Hardware — Practical Skills

This section proves real technical capability, not just theory.

---

## 🎥 Laptop Disassembly & Reassembly

A full video walkthrough of disassembling and reassembling a Lenovo V14-IGL
(Model: 82C2), identifying the internal component.

🎬 [Watch the full video here](https://youtu.be/tm8huvp6ip8?si=lZnC4YoHjupjtlMy)

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

**Why this matters:** Taking apart and rebuilding a laptop while explaining every
component proves real hands-on technical ability. Anyone can read about a
motherboard — this shows I can identify one, explain it, and work around it safely.

---

## 🔍 Problem & Solution — Cisco Packet Tracer

**Problem:** A laptop is connected to a home network but cannot access the
internet due to an incorrect default gateway.

**Tool used:** Cisco Packet Tracer — industry standard network simulation software

### Step 1 — Network Setup
![Network Setup](./packet-tracer/01-network-setup.png)

Built a home network simulation with a wireless router and two laptops.

### Step 2 — The Problem
![Wrong Gateway](./packet-tracer/02-wrong-gateway.png)

Deliberately set the wrong default gateway on Laptop 1 to simulate a real
misconfiguration.

### Step 3 — ipconfig Shows the Issue
![ipconfig fail](./packet-tracer/03-ipconfig-problem.png)

Running `ipconfig` confirms the incorrect gateway is assigned.

### Step 4 — Ping Fails
![Ping fail](./packet-tracer/04-ping-fail.png)

Running `ping 192.168.0.1` fails — the laptop cannot reach the router.

### Step 5 — Fix Applied
![Fix](./packet-tracer/05-gateway-corrected.png)

Default gateway corrected to the right address.

### Step 6 — Ping Succeeds
![Ping success](./packet-tracer/06-ping-success.png)

Running `ping 192.168.0.1` now succeeds — connectivity restored.

**Why this matters:** This is a real scenario IT support technicians face daily.
Being able to identify, simulate, and fix a network misconfiguration proves I
can troubleshoot systematically — not just guess.

---

## 🔧 Build Walkthrough — Ethernet Cable

### Before — Raw Cable
![Ethernet Before](./photos/04-ethernet-before.jpg)

Unstripped cable before any work begins.

### During — Wiring Arrangement
![Ethernet During](./photos/05-ethernet-during.jpg)

Wires arranged in T568B standard order before crimping.

### After — Completed & Tested
![Ethernet After](./photos/06-ethernet-after.jpg)

Crimped and tested — passed.

Step-by-step:
1. Stripped the outer casing to expose the inner wires
2. Arranged wires in T568B standard order
3. Trimmed wires to even length and inserted into RJ45 connector
4. Crimped the connector using a crimping tool
5. Tested cable for connectivity — passed

**Why this matters:** Physical network skills are foundational for IT support.
Building a cable from scratch proves I understand how networks are physically
connected.

---

## 🛠️ Troubleshooting Log

| Issue | What I tried | Outcome |
|---|---|---|
| [Add your real example] | [Steps you took] | [How it was resolved] |

---

## 💡 Key Takeaway

Every task here was done hands-on. I didn't just read about it —
I did it, documented it, and can explain why each step matters.
