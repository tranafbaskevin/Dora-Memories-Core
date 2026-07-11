# Technical Notes: Nhiễu Ký Ức (FINAL - Godot 2D TopDown + VN)

## 1. Core Architecture
The game is built around two main systems:
1. Exploration System (Top-down 2D)
2. Narrative System (Visual Novel)
Player loop: Explore → Interact → Dialogue → Return → Continue

## 2. Scene Structure (CRITICAL)
Each room is a separate scene.
Example:
- MainBedroom.tscn
- LivingRoom.tscn
- Kitchen.tscn
- Hallway.tscn
- Office.tscn
No single large map is used.
Scenes are switched when player moves between rooms.

## 3. Scene Transition System
Use:
get_tree().change_scene_to_file("res://scenes/rooms/MainBedroom.tscn")
Return:
get_tree().change_scene_to_file("res://scenes/hallway/Hallway.tscn")

## 4. Exploration System (Top-down)
Use:
- CharacterBody2D
- Camera2D
Features:
- WASD movement
- 4-direction or 8-direction movement
- Collision-based navigation

## 5. Interaction System
Use Area2D for triggers.
Flow:
- Player enters area
- Press E
- Trigger event
Events include:
- Start dialogue
- Change scene
- Modify state

## 6. Visual Novel System
Simple dialogue system:
- Array of text
- Index-based progression
Example:
var dialogue = [
"This place feels familiar...",
"But something is wrong.",
"Why can't I remember clearly?"
]

## 7. Mode Switching
When dialogue starts:
- Disable player movement
- Show UI layer
When dialogue ends:
- Enable player movement
- Hide UI

## 8. Camera Design
- Fixed top-down view
- No rotation
- Focus on framing and composition

## 9. Room Design Principles
Each room must:
- Be small and focused
- Have clear layout
- Contain at least 1 interaction
- Support emotional storytelling

## 10. Hallway System
Hallway is:
- A special scene
- Slightly larger than rooms
- Connects all rooms
Used for:
- Navigation
- Event triggers
- Building tension

## 11. State System (IMPORTANT - FUTURE)
Game must track:
- Object states
- Room states
- Dialogue progression
Example:
- Object disappears
- Room layout changes
- Dialogue changes based on past actions

## 12. Folder Structure
res://
├── scenes/
│   ├── hallway/
│   ├── rooms/
│   └── vn/
├── scripts/
├── assets/
└── ui/

## 13. Phase 1 Technical Goal
- Player can move (top-down)
- Player can enter 1 room
- Player can trigger dialogue
- Player can return to hallway

## 14. Design Constraints
- No FPS mechanics
- No large open world
- No unnecessary complexity
Focus:
- Simplicity
- Atmosphere
- Emotional impact

## 15. Future Expansion
- Branching dialogue
- Memory distortion system
- Dynamic room changes
- Sound system