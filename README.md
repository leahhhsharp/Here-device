# Here-device
A physical device designed to help people capture and stay present in meaningful moments.
# Interface

![Dial Interface](images/dial-interface.png)

# Device Prototype

![Device Render](images/device-render.png)

# Memory Output

![Memory Strip](images/memory-strip.png)

# Overview

The HERE device is a small tactile tool that allows users to quickly capture a moment using a simple dial interface and a thermal printer.

Instead of pulling out a phone or writing a long note, the device creates a small ritual: turning a dial to reflect the emotional clarity of a moment, pressing once, and receiving a printed memory strip that can be saved in a notebook or memory bank.

The goal is to make reflection and presence effortless.

---

# The Problem

Modern life moves quickly, and meaningful moments often pass without being acknowledged.

Most tools for capturing memories require too much friction:

- opening an app  
- typing notes  
- navigating distractions  
- losing the moment  

The HERE device aims to remove that friction by creating a **single tactile interaction** that captures the moment instantly.

---

# The Concept

The HERE device encourages users to pause briefly and recognize a moment.

A rotary dial lets the user select how the moment feels:

| State | Meaning |
|------|------|
| Foggy | Uncertain, overwhelmed, or unclear |
| Steady | Calm, grounded, neutral |
| Clear | Joyful, meaningful, or memorable |
| Blank | A moment worth capturing without labeling |

After selecting a state, pressing the dial prints a small timestamped strip.

The strip can be placed in a notebook to create a physical record of moments over time.

---

#Interface

The device uses a **four-position rotary dial** arranged like a compass.
        Foggy
          ↑
Clear ←  ●  → Steady
          ↓
        Blank
##Interaction Flow

1. Rotate dial to desired state
2. Press the dial
3. Device prints a memory strip
4. Add strip to notebook or memory log

This interaction is designed to take **less than 3 seconds**.

---

#Output Example
The printed strip captures:

- Date
- Time
- Emotional state
- Optional short note

Two strips fit neatly on one notebook page.

---

#Hardware Concept

Initial prototype components include:

- ESP32 microcontroller
- thermal printer module
- rotary encoder with push button
- rechargeable battery
- internal paper roll
- sand-textured enclosure

The goal is to create a **compact handheld device** that feels intentional and tactile.

---

#Design Philosophy

The HERE device follows a few core principles:

**Low friction**  
Capture a moment in seconds.

**Tactile interaction**  
Physical input encourages presence.

**Minimal interface**  
No screen, no notifications.

**Physical memory**  
Printed moments create a tangible record.

---

#Use Cases

Examples of moments someone might capture:

- A meaningful conversation
- A quiet morning
- A family memory
- A creative breakthrough
- A moment of clarity
- A pause during a busy day

Over time, the collection of strips becomes a **timeline of presence**.

---

#Status

Current stage: **Concept + Early Prototype**

Work in progress:

- hardware prototype
- enclosure design
- printing workflow
- notebook integration

---

#Future Ideas

Potential future features include:

- companion notebook system
- optional mobile sync
- customizable emotional states
- analytics of emotional patterns
- collaborative memory logging

---

#Why Build This

The HERE device is inspired by a simple idea:

Small moments are easy to miss, but they are often the ones that matter most.

This device creates a simple ritual to pause, acknowledge the moment, and save it.

---

#Author

Leah Sharp

Creator documenting systems, tools, and ideas that help people stay present and build meaningful lives.

---
