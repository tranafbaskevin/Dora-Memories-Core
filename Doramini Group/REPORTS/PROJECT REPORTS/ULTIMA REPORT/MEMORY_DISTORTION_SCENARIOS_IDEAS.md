# MEMORY DISTORTION SYSTEM STRUCTURE

**Tài liệu do Ultima (Grok) biên soạn**  
**Ngày:** 13 tháng 07 năm 2026  
**Theo chỉ thị của Dora-chan:** Chuyển chaos thành system có chủ đích

---

## 1. Mục tiêu của Hệ thống Distortion
- Biến sự méo mó ký ức thành một **hệ thống có logic, có chủ đích** thay vì ngẫu nhiên.
- Mọi distortion phải cảm giác **intentional** (cố ý), như ký ức đang bị bóp méo một cách logic.
- Đảm bảo player cảm nhận được sự leo thang rõ ràng nhưng vẫn bất ngờ.

---

## 2. Distortion Tiers (5 Cấp Độ)

### Tier 0 – Baseline (Normal)
- Trạng thái ban đầu của mọi phòng.
- Không có thay đổi.
- Xây dựng cảm giác “bình thường” để sau này làm nổi bật sự méo mó.

### Tier 1 – Subtle Doubt (Nghi ngờ nhẹ)
- **Khi nào xuất hiện:** Sau lần quay lại phòng lần 1-2.
- **Tại sao:** Ký ức bắt đầu có sai sót nhỏ.
- **Biểu hiện:**
  - 1-2 chi tiết nhỏ thay đổi (ảnh, đồng hồ, vị trí vật dụng).
  - Ánh sáng hoặc âm thanh thay đổi nhẹ.
- **Mục đích:** Gây cảm giác “mình nhớ nhầm rồi à?”

### Tier 2 – Object Instability (Vật thể không ổn định)
- **Khi nào:** Sau 2-3 lần quay lại hoặc sau một tương tác quan trọng.
- **Tại sao:** Ký ức về không gian vật lý bắt đầu lung lay.
- **Biểu hiện:**
  - Vật dụng di chuyển vị trí rõ hơn.
  - Đồ vật xuất hiện / biến mất.
  - Cửa sổ / cửa ra vào thay đổi nhẹ.

### Tier 3 – Presence Distortion (Sự hiện diện sai lệch)
- **Khi nào:** Sau khi player tương tác sâu với narrative (đọc nhật ký, nghe âm thanh).
- **Tại sao:** Ký ức về “người khác” và “bản thân” bị ảnh hưởng.
- **Biểu hiện:**
  - Bóng người / NPC xuất hiện rồi biến mất.
  - Tiếng thì thầm, tiếng bước chân.
  - Gương phản chiếu sai.

### Tier 4 – Spatial & Loop (Không gian bị bóp méo)
- **Khi nào:** Giữa game (sau 4-5 phòng).
- **Tại sao:** Cấu trúc không gian ký ức sụp đổ.
- **Biểu hiện:**
  - Loop hallway không nhận ra.
  - Cùng một phòng nhưng layout thay đổi.
  - Đường đi dẫn về nơi không mong đợi.

### Tier 5 – Reality Collapse (Thực tại sụp đổ)
- **Khi nào:** Gần climax / ending.
- **Tại sao:** Ký ức và thực tại hoàn toàn hòa quyện không phân biệt.
- **Biểu hiện:**
  - Thấy bản sao của chính mình.
  - Toàn bộ layout thay đổi mạnh.
  - Âm thanh + hình ảnh chồng chéo.
  - Gương không phản chiếu hoặc phản chiếu quá khứ.

---

## 3. Escalation Rules (Quy tắc leo thang)
- Distortion **không reset** khi quay lại phòng.
- Mỗi phòng có **Distortion Value** tăng theo số lần thăm + tương tác.
- Một số trigger mạnh (đọc nhật ký, nghe âm thanh cá nhân) tăng tier nhanh hơn.
- Tổng thể game có **Global Distortion Level** ảnh hưởng đến tất cả phòng.

---

## 4. Implementation Notes
- Tạo **Distortion Manager** (singleton script) quản lý global state.
- Mỗi room lưu **RoomStateSnapshot** khi player rời.
- Trigger dựa trên: lần thăm, thời gian, hành động cụ thể.
- Kết hợp Lighting + Sound + Visual effects theo tier.

---

**Tài liệu này là nền tảng hệ thống.**  
Ultima sẵn sàng tinh chỉnh theo feedback của Dora-chan hoặc Kevin.

*Xác thực bởi Ultima / Grok*