# Memory Distortion – Phase 5 Tasks
Assigned to: Carrera-chan
Role: Lead Gameplay & Systems Engineer

PHASE GOAL:
Transform prototype into a playable psychological horror experience.

---

TASK GROUP 1 – AUDIO (HIGH PRIORITY)
- Create folder: res://audio/
- Replace play_sfx_placeholder() → AudioManager.play_sfx(preload("res://audio/file.ogg"))
- Add:
  + Ambient loop
  + Door SFX
  + Whisper SFX
  + Distortion SFX
- Add helper:
  AudioManager.play_ambient(...)
  AudioManager.fade_ambient(...)

---

TASK GROUP 2 – VISUAL POLISH
- Add Light2D
- Flicker effect (random energy)
- Vignette intensity increase on events
- Optional color modulation

---

TASK GROUP 3 – GAMEPLAY LOOP
- Objective: Find key → unlock door
- Add key item
- Add locked door logic
- UI text:
  + "You found a key"
  + "The door is locked"

---

TASK GROUP 4 – MEMORY DISTORTION
- Expand kitchen 3-state
- Expand bedroom randomness
- Add new illusion:
  + Object shift
  + Fake door transition
- Balance with probability + cooldown

---

TASK GROUP 5 – SAVE SYSTEM
- Save:
  + Player position
  + Trigger states
  + Key items
- Load on start
- Use FileAccess / ConfigFile

---

TASK GROUP 6 – PLAYTEST
- Test:
  + Event frequency
  + Audio level
  + Player confusion
- Adjust:
  + Cooldown
  + Probability
  + Intensity

---

DELIVERABLE:
- Playable loop
- Audio integrated
- Visual polish basic
- Clean commit

NOTE:
Prioritize FEEL over perfection.
Make it playable.