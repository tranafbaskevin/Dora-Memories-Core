# 🧠 Carrera Task — Phase 3: Interaction & Horror Foundation

## 🎯 Objective
Build core interaction system and first layer of horror mechanics on top of Phase 2 house structure.

## ⚙️ Required Systems

### 1. Interaction System
Goal: Allow player to interact with objects inside rooms.

Requirements:
- Press key (E or Enter) to interact
- Detect nearby interactable objects
- Show simple feedback (print/log or basic UI)
- Support reusable interaction logic

Implementation:
- Create script: Interactable.gd
- Create base node: Interactable (Area2D or Node2D)
- Player detects objects via Area2D or Raycast
### 2. Door & Room Transition System
Goal: Allow player to move between rooms with interaction.

Requirements:
- Door interaction triggers scene change
- Smooth transition (fade or instant for now)
- Maintain player position using spawn markers
- Reusable door logic

Implementation:
- Update Door.gd to support interaction trigger
- Add scene loading logic (change_scene or custom loader)
- Use SpawnMarker system from Phase 2

---

### 3. Basic Horror Trigger System
Goal: Introduce first psychological horror elements.

Requirements:
- Trigger events when entering area or interacting
- Simple effects: sound, flicker, object change
- One-time trigger support
- Easy to expand later

Implementation:
- Create script: EventTrigger.gd
- Use Area2D for detection
- Support flags: triggered / repeatable
### 4. First Memory Distortion Mechanic
Goal: Create first “something is wrong” moment.

Requirements:
- Room changes after re-enter
- Object appears/disappears or moves
- Door leads to unexpected location (simple version)
- At least 1 working scenario

Example:
Enter room → leave → re-enter → layout or object changed

Implementation:
- Use flags or global state
- Modify scene or objects after trigger

---

### 5. Basic Narrative System
Goal: Provide simple story feedback to player.

Requirements:
- Show text when interacting or entering room
- Simple popup or print system
- No complex UI needed

Implementation:
- Create simple text display (Label or print)
- Trigger via EventTrigger or Interactable

---

## 🧪 Testing Requirements
- Interaction works in at least 2 rooms
- At least 1 horror event triggers
- Memory distortion works (1 case)
- Scene transitions stable
- No crash or player stuck

---

## 📦 Expected Result
Player can:
- interact with objects
- move between rooms
- trigger simple horror event
- experience first distortion

---

## 🚫 Do NOT implement
- Inventory system
- Complex UI
- Advanced animation
- Full sound system

Focus on core gameplay feeling.

---

## 🧾 Report Required
Carrera must provide:
- Systems implemented
- Events created
- Known issues
- Suggested improvements