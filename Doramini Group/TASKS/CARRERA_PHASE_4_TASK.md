# 🧠 Carrera Task — Phase 4: Horror Expansion & Atmosphere

## 🎯 Objective
Transform Phase 3 prototype into a true psychological horror experience by enhancing atmosphere, audio, and dynamic events.

## ⚙️ Core Focus

Phase 4 MUST introduce:

- Sound & atmosphere
- Advanced horror events
- Environmental storytelling
- Player psychological pressure

---

## 🔊 1. Sound System (CRITICAL)

Goal: Add audio layer to create tension.

Requirements:

- Background ambient sound (loop)
- Triggered sound events (door, step, whisper)
- Volume control per scene

Implementation:

- Create AudioManager.gd (singleton)
- Support:
  - play_ambient()
  - play_sfx()

Notes:
- No need for real assets yet → can use placeholder sound
- System must be ready for future asset injection

---

## 👁️ 2. Advanced Horror Event System

Goal: Move from simple trigger → layered psychological events.

Requirements:

- Multi-step events (not single trigger)
- Delayed effects (event happens after a few seconds)
- Randomized triggers (not always same outcome)

Examples:

- Enter hallway → nothing happens → after 3s → whisper sound
- Open door → normal → close → reopen → something changed
- Walk past object → nothing → walk back → object moved

Implementation:

- Extend EventTrigger.gd
- Add:
  - delay timer
  - random chance
  - multi-state event flow

---

## 🧱 3. Environment Change System

Goal: Make environment feel unstable.

Requirements:

- Objects can appear/disappear
- Objects change position
- Light color/intensity change
- Scene variation (A/B version of same room)

Implementation:

- Use flags or global state
- Support:
  - first visit
  - revisited state
  - triggered state

Example:

Kitchen:
- First visit → normal
- Second visit → chair slightly moved
- Third visit → light dim + sound

---

## 🧠 4. Psychological Pressure System

Goal: Create constant unease without jumpscare.

Requirements:

- Subtle screen effects:
  - slight camera zoom
  - small shake
  - vignette (optional)

- Player disorientation:
  - slight position offset
  - delayed control response (very nhẹ)

- Repetition discomfort:
  - same hallway but “feels different”
  - loop illusion

Implementation:

- Extend camera system
- Add optional effect trigger in EventTrigger
- Keep effect subtle (DO NOT overdo)

---

## 📖 5. Environmental Storytelling

Goal: Tell story through environment, not text.

Requirements:

- Objects hint at story:
  - TV showing strange message
  - note on table
  - misplaced items

- No direct explanation
- Player must “feel” story, not read everything

Implementation:

- Use existing Interactable system
- Trigger short narrative text only when needed

---

## 🧪 Testing Requirements

- At least 2 rooms have atmosphere (sound + change)
- At least 1 multi-step horror event works
- Player notices environment inconsistency
- No crash / no broken transition

---

## 📦 Expected Result

Game should now:

- feel uncomfortable even without jumpscare
- have dynamic environment
- have layered horror (not single trigger)
- start forming identity of “Memory Distortion”

---

## 🚫 DO NOT

- Add heavy UI
- Add inventory system yet
- Add loud jumpscare

Focus:
👉 psychological horror + subtle distortion

---

## 🧾 Report Required

Carrera must provide:

- What systems were extended
- What events were added
- How distortion is handled
- Any limitation or bug