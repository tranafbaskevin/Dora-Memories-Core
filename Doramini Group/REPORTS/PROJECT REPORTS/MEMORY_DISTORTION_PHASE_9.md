# PHASE 9 REPORT — REALITY DISTORTION SYSTEM

Project: Memory Distortion: Nhiễu Ký Ức  
Phase: 9 — Reality Distortion System  
Status: Completed  

---

## Core Philosophy

This phase focuses on breaking the player's trust in their own perception.

No jumpscare.  
No direct threat.  
Only subtle, state-driven distortion.

---

## Systems Implemented

### 1. Room State Drift
- Props shift position randomly (up to 18px) and rotate slightly (up to 0.06 rad).
- Movement intensity scales with Global Fear Level.
- Decorative props may disappear (up to 30% at high fear levels).
- Player does NOT see objects move directly — only realizes something is "off".
- Purpose: create spatial inconsistency and subconscious unease.

---

### 2. Perception Trap
- Activated when `fear_level >= 2`.
- Uses `peripheral_only` logic (visible only at edge of screen).
- Disappears instantly when player looks directly.
- Supports:
  - vanish_on_look
  - peripheral_only
- Purpose: simulate unreliable peripheral vision and psychological paranoia.

---

### 3. Memory Bleed
- Cross-room hallucination system.
- Example:
  - Bloody family photo appears in Toilet F1 when fear >= 3
  - Child crying audio from Bedroom F2 bleeds into Toilet F1
- Includes delayed trigger (~1.8s after entering room)
- Purpose: merge memory layer with physical space.

---

### 4. Micro Distortion Loop
- Each loop subtly alters room structure.
- Door position shifts horizontally (~35px per loop).
- Objects may disappear or relocate.
- Player loses spatial certainty gradually.
- Purpose: reinforce loop instability without obvious reset.

---

### 5. Psychological Puzzle — Blind Spot Cabinet
- Cabinet cannot be opened normally.
- Unlock condition:
  - Player stands near
  - Turns completely away (dot product < -0.3)
  - Remains still for ~2.5 seconds
- Trigger reveals narrative message:
  "Sự thật không nằm ở nơi mày nhìn chằm chằm..."
- Increases Truth Acceptance Level.
- Purpose: force player to abandon control and accept indirect truth.

---

## System Integration

All systems are connected through:

- Global Fear Level
- Loop Count (`distortion_events_count`)
- Player Facing Direction

No system operates independently.

---

## Player Experience Goal

Player begins to question:

- What is real  
- What has changed  
- Whether they caused it  

Fear is generated from:

- Inconsistency  
- Loss of control  
- Subtle environmental betrayal  

---

## Result

Phase 9 successfully transforms the experience from:

> A horror game  

into:

> A psychological instability simulator  

---

## Dora Note

This phase is the turning point of the entire project.

From here, the game no longer relies on:

- Visual shock  
- External threats  

Instead, it uses:

- Perception  
- Memory  
- Self-doubt  

to create fear.

---

## Next Direction (Preview)

Phase 10 will focus on:

- Narrative Collapse System  
- Acceptance vs Denial Ending Branch  
- Loop Manipulation  

Where the player no longer understands:

- Timeline  
- Reality  
- Their own identity  

---

End of Phase 9.