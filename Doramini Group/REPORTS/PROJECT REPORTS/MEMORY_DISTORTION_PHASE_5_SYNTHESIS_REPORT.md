# Memory Distortion System – Phase 5 Synthesis Report

## Overview
Phase 5 đánh dấu bước chuyển từ hệ thống kỹ thuật sang trải nghiệm gameplay thực sự. Nếu Phase 4 xây nền (audio, vignette, distortion systems) thì Phase 5 là lúc tất cả bắt đầu “nói chuyện với người chơi”.

## Core Gameplay Loop
Gameplay loop được định hình rõ ràng dựa trên trạng thái tâm lý người chơi:
- Spawn → trạng thái bình thường
- Nghi ngờ → môi trường thay đổi nhẹ
- Nhận ra bất thường → distortion tăng dần
- Tìm cách thoát → mục tiêu rõ ràng (key, door)

Loop này không ép người chơi bằng jumpscare mà dẫn dắt bằng câu hỏi:
“Tôi đang làm gì ở đây?” → “Tại sao mọi thứ thay đổi?” → “Làm sao thoát ra?”

## Gameplay Systems Breakdown
- Key System: KeyItem được đặt trong phòng làm việc, đóng vai trò mục tiêu rõ ràng đầu tiên cho người chơi.
- Distortion Trigger: Nhật ký (journal) kích hoạt trạng thái “nhà bắt đầu sai”, chuyển game từ exploration sang psychological mode.
- Exit System: LockedDoor tại hành lang F1 tạo mục tiêu thoát cụ thể, giúp loop hoàn chỉnh.
- Auto Save: Mỗi lần mở cửa sẽ lưu trạng thái, đảm bảo progression không bị reset gây frustration.
- Room State System: Các phòng (TV, kitchen, hallway, bedroom) thay đổi dựa trên số lần vào, tạo cảm giác “không gian không ổn định”.

## Player Experience (Testarossa Insights)
- Điểm mạnh: Mystery tốt ngay từ đầu, người chơi tò mò tự nhiên mà không cần tutorial.
- Điểm mạnh: Loop rõ ràng, không bị lạc hướng.
- Điểm yếu: Early game hơi chậm trước khi distortion đầu tiên xuất hiện.
- Điểm yếu: Trigger (journal) còn mang tính cơ học, chưa đủ “tự nhiên”.
- Kết luận: Người chơi tò mò nhưng chưa thực sự gắn kết cảm xúc.

## Distortion Design (Ultima Insights)
- Điểm mạnh: Ý tưởng distortion đa dạng (loop hallway, fake door, room mismatch).
- Điểm mạnh: Có tiềm năng replay cao.
- Điểm yếu: Chưa có hệ thống escalation rõ ràng.
- Điểm yếu: Chưa phân cấp distortion (nhẹ → nặng).
- Kết luận: Distortion có nhưng chưa được “điều khiển”.

## Core Problem
Game hiện tại có hệ thống và ý tưởng, nhưng thiếu một đường cong cảm xúc rõ ràng cho người chơi.

## Direction for Phase 6
- Thêm Distortion Levels (Subtle → Environmental → Spatial → Psychological)
- Đưa distortion xuất hiện sớm hơn (2–3 phút đầu)
- Giảm thời gian “đi bộ trống”
- Biến mục tiêu từ “tìm key” thành “tìm thứ gì đó không rõ bản chất”
- Tăng yếu tố cảm xúc thay vì chỉ mechanic

## Conclusion
Phase 5 đã biến Memory Distortion từ prototype thành một trải nghiệm có thể chơi được. Tuy nhiên, game hiện tại mới chỉ gây “bối rối” chứ chưa tạo được “ám ảnh”. Phase 6 cần tập trung vào cảm xúc, escalation và ending để hoàn thiện bản sắc psychological horror.