# Carrera Report - Phase 1 Core Playable Ready

Project: Memory Distortion - Nhiễu Ký Ức  
Developer Agent: Carrera (Antigravity)  
Managed By: Doramini Group  
Phase: Phase 1 - Core Foundation  
Status: Completed

---

# 1. Tổng quan

Carrera đã hoàn thành việc xây dựng nền móng gameplay đầu tiên cho dự án Memory Distortion.

Mục tiêu của Phase 1:

- Thiết lập project Godot hoàn chỉnh.
- Tạo cấu trúc thư mục game có thể mở rộng.
- Xây dựng hệ thống nhân vật cơ bản.
- Xây dựng hệ thống camera.
- Tạo môi trường test.
- Chuẩn bị nền móng cho việc phát triển map, phòng, hành lang và gameplay chính.

Phase 1 không tập trung vào visual cuối cùng mà tập trung xây dựng core architecture để các phase sau tiếp tục phát triển.

---

# 2. Engine và cấu trúc dự án

Engine:

Godot Engine 4.7 Stable

Project location:

C:\Users\PHAM TUAN HUNG\Documents\memory-distortion


Cấu trúc hiện tại:
memory-distortion
├── environment
│   ├── door.gd
│   └── Door.tscn
│
├── player
│   ├── player.gd
│   ├── Player.tscn
│   ├── custom_camera.gd
│   └── custom_camera.gd.uid
│
├── scenes
│   ├── hallway_test.tscn
│   └── room_test.tscn
│
├── global.gd
├── project.godot
├── README.md
└── .gitignore

---

# 3. Những hệ thống Carrera đã hoàn thành

## 3.1 Player System

Đã tạo:

- Player scene.
- Player script.
- Collision system.
- Sprite placeholder.
- Basic movement foundation.

Player hiện tại có thể:

- Tồn tại trong scene.
- Nhận input.
- Di chuyển trong môi trường test.
- Tương thích với camera system.


File:
player/player.gd
player/Player.tscn

---

# 3.2 Camera System

Đã tạo hệ thống camera riêng:
player/custom_camera.gd

Mục tiêu:

- Camera follow player.
- Chuẩn bị khả năng zoom.
- Là nền móng cho phong cách camera top-down / RPG Maker hybrid.

Đây là bước quan trọng vì Memory Distortion không sử dụng góc nhìn FPS.

Định hướng camera:

- Top-down.
- Fixed room perspective.
- Visual Novel + RPG hybrid.

---

# 3.3 Environment System

Đã tạo hệ thống môi trường cơ bản:
environment/Door.tscn
environment/door.gd

Mục đích:

- Chuẩn bị cửa chuyển cảnh.
- Là nền móng cho việc đi giữa:
    - phòng nhân vật chính
    - hành lang
    - các khu vực trong nhà

Hệ thống này sẽ mở rộng thành:

- Door interaction.
- Scene transition.
- Memory distortion transition.

---

# 3.4 Scene Testing System

Đã tạo:
scenes/hallway_test.tscn
scenes/room_test.tscn

Mục đích:

Test:

- Player spawn.
- Camera.
- Movement.
- Không gian phòng.
- Không gian hành lang.


Đây là prototype đầu tiên của gameplay loop.

---

# 4. Những gì đã đạt được

Trạng thái hiện tại:

CORE PLAYABLE READY


Có nghĩa:

Game đã có:

✅ Godot project hoạt động  
✅ Player system  
✅ Camera system  
✅ Scene structure  
✅ Environment foundation  
✅ Door foundation  
✅ Test scenes  


Dự án đã chuyển từ:

"Ý tưởng thiết kế"

sang:

"Prototype có thể chạy được"

---

# 5. Những phần chưa thực hiện

Phase 1 chưa bao gồm:

❌ Artwork cuối cùng

❌ Character sprite chính thức

❌ Nhà hoàn chỉnh

❌ Tầng 1 / tầng 2 full map

❌ Dialogue system

❌ Inventory

❌ Horror event system

❌ Memory distortion mechanic

❌ Sound design

❌ Save system


Các phần này thuộc các phase tiếp theo.

---

# 6. Đánh giá tiến độ dự án

Trước Phase 1:

Memory Distortion tồn tại dưới dạng:

- Concept.
- Story.
- Floor plan.
- Visual direction.


Sau Phase 1:

Memory Distortion đã có:

- Engine.
- Code foundation.
- Scene architecture.
- Gameplay skeleton.


Tiến độ:

Concept Phase
        ↓
Design Phase
        ↓
Core Foundation Phase ✅
        ↓
Gameplay Expansion Phase
        ↓
Content Production Phase
        ↓
Polishing Phase


---

# 7. Định hướng Phase tiếp theo

Phase 2 dự kiến:

## Room & House System


Mục tiêu:

- Xây dựng căn nhà thật.
- Tạo hành lang chính.
- Tạo phòng nhân vật chính.
- Tạo hệ thống chuyển phòng.


Theo design của Kevin:

Lưu ý quan trọng:

Toàn bộ layout tầng 1 và tầng 2 chỉ là FULL MAP REFERENCE.

Trong gameplay thực tế:

- Player không nhìn toàn bộ căn nhà.
- Player chỉ ở trong từng khu vực nhỏ.
- Khi vào phòng:
    camera chỉ hiển thị một không gian giới hạn.
- Hành lang là khu vực di chuyển chính.


Phong cách gameplay:

RPG Maker inspired.

Không phải:

- FPS.
- Open world 3D.
- Roblox style roaming.

---

# 8. Repository Status

GitHub:

https://github.com/tranafbaskevin/Memory-Distortion


Initial commit:

Memory Distortion - Milestone 001: Core Foundation


Current branch:

main


---

# 9. Carrera Conclusion

Phase 1 đã hoàn thành mục tiêu:

"Tạo nền móng kỹ thuật để Memory Distortion có thể trở thành một game thật."


Các bước tiếp theo cần phối hợp:

- Dora:
  quản lý design, story, architecture.

- Remi:
  hỗ trợ code khi available.

- Carrera:
  tiếp tục phát triển gameplay systems.

- Các AI khác:
  review, research, optimization.


Status:

PHASE 1 COMPLETE

READY FOR PHASE 2
