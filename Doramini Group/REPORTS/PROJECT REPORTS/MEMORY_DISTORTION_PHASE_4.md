# Memory Distortion System – Phase 4 Report

## Overview
Phase 4 expands the psychological horror layer of the project by introducing audio systems, visual pressure, and advanced event logic. The focus is not on jumpscares, but on subtle instability and player uncertainty.

---

## Core Systems Implemented

### 1. AudioManager (Autoload)
- Handles ambient audio, SFX, and fade transitions
- Provides helper functions:
  - play_ambient()
  - play_sfx()
  - fade_ambient()
- Designed for easy future integration with real audio assets

---

### 2. Vignette Shader
- Darkens screen edges dynamically
- Used to increase psychological pressure
- Can be controlled via script for intensity scaling

---

### 3. AdvancedEventTrigger
- Supports:
  - Delay
  - Random chance
  - Cooldown
- Enables non-deterministic horror events
- Prevents predictable gameplay patterns

---

### 4. Kitchen 3-State System
- Environment changes across multiple interactions:
  1. Normal
  2. Slight distortion (lights, objects)
  3. Strong distortion (camera drift, atmosphere)
- Reinforces memory inconsistency

---

### 5. Hallway F2 Whisper Event
- Multi-step trigger sequence (4 steps)
- 80% chance activation
- Includes delay to avoid immediate triggering
- Creates anticipation and unease

---

### 6. Loop Illusion (F1)
- 60% chance hallway extends or loops
- Player feels spatial inconsistency
- No hard teleport → illusion-based design

---

### 7. Bedroom Distortion Enhancement
- Each entry increases distortion:
  - Object displacement
  - Wrong door routing
  - Camera zoom + vignette
- Progressive psychological pressure

---

## Technical Notes

- All major systems implemented using modular scripts
- Autoload singletons used:
  - Narrative
  - AudioManager
  - Vignette
- Fixed engine sync issue by reloading project
- Verified compatibility with Godot 4.7

---

## Design Philosophy

The system follows the core principle:

> “Do not break reality abruptly — distort it slightly.”

- No jumpscares
- Focus on doubt and uncertainty
- Player questions memory instead of reacting to fear spikes

---

## Current Status

- All Phase 4 systems implemented successfully
- No runtime or parse errors after reload
- Systems are stable and extendable

---

## Next Steps (Phase 5)

- Add real audio assets (.ogg)
- Improve visual polish (lighting, shader tuning)
- Expand interaction content
- Add save/load progression
- Playtesting & balancing

---

## Conclusion

Phase 4 establishes the foundation of the psychological horror identity of the project. The game now successfully creates unease through subtle distortion rather than direct fear.

The system is ready for content expansion and polish in the next phase.