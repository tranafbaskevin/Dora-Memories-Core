# Memory Distortion – Phase 6 Tasks Assigned to: Carrera-chan Role: Gameplay Systems Engineer

PHASE GOAL: Transform Phase 5 prototype into a controlled psychological horror experience using structured pacing (Testarossa) and distortion system design (Ultima).

REFERENCE FILES (MANDATORY READ BEFORE IMPLEMENTATION):
- Player_Journey_First_10min_TestarossaReview.md → defines WHEN events should happen (player emotional pacing)
- MEMORY_DISTORTION_SCENARIOS_IDEAS.md → defines WHAT distortion events should exist (idea pool)

IMPORTANT: Use these reports as design references, but follow this task file as the implementation guide.

---

CORE SYSTEM 1 – DISTORTION TIER SYSTEM

Implement structured distortion levels based on Ultima report:

Tier 1 (Subtle):
- light flicker
- minor audio anomaly
- small environmental inconsistency

Tier 2 (Environmental):
- object position change
- TV state change
- lighting instability

Tier 3 (Spatial):
- fake door
- room mismatch
- hallway loop

Tier 4 (Psychological):
- whisper audio
- presence illusion
- perception manipulation

Requirements:
- Each tier must feel distinct
- No random triggering without control
- Must support escalation logic

---

CORE SYSTEM 2 – TIME-BASED EMOTIONAL PACING

Implement pacing based on Testarossa timeline:

0–2 minutes:
- no distortion (baseline calm)

2–4 minutes:
- trigger 1 Tier 1 event

4–6 minutes:
- introduce Tier 2 distortion

6–10 minutes:
- escalate to Tier 3

After 10 minutes:
- unlock Tier 4 (psychological pressure)

Requirements:
- Use timer or progression state
- Avoid repetition spam
- Match emotional curve defined in Testarossa report

---

CORE SYSTEM 3 – DISTORTION CONTROLLER (CRITICAL)

Create central controller: DistortionController.gd

Responsibilities:
- track player time/progress
- determine current tier
- select distortion event from pool (Ultima ideas)
- trigger event with cooldown control
- prevent duplicate spam

All distortion MUST be routed through this controller.

---

CORE SYSTEM 4 – EVENT MAPPING (INTEGRATION)

Map existing systems into tier structure:

- hallway fake door → Tier 3
- bedroom distortion → Tier 2
- kitchen state change → Tier 2
- light flicker → Tier 1
- whisper/audio illusion → Tier 4

Requirements:
- remove random trigger logic
- unify under DistortionController
- ensure consistency with pacing system

---

CORE SYSTEM 5 – EVENT SELECTION SYSTEM

Implement controlled randomness:

- each tier has event pool (based on Ultima report)
- select event using:
  + weighted random
  + cooldown per event
  + no immediate repetition

Goal:
- maintain unpredictability without chaos

---

CORE SYSTEM 6 – EARLY EXPERIENCE IMPROVEMENT

Based on Testarossa feedback:

- ensure first anomaly appears within 2–3 minutes
- reduce empty walking time
- guarantee at least 1 “strange moment” before major trigger (journal or equivalent)

---

CORE SYSTEM 7 – PRE-ENDING PRESSURE BUILDUP

Before exit:

- increase distortion frequency
- introduce mixed tier events
- reduce safe spaces

Goal:
- create psychological pressure before ending

---

DELIVERABLE:

- DistortionController fully implemented
- Tier system working
- Time-based escalation functional
- Existing events integrated into system
- Controlled event randomness active
- Early game pacing improved

---

NOTE:

Do NOT add new content unnecessarily. Focus on making existing systems feel intentional, controlled, and psychologically effective.

This phase defines how the game manipulates the player’s perception.