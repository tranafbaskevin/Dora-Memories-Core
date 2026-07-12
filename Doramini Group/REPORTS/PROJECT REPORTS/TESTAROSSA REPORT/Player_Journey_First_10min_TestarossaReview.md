# Player Journey — 5-10 Phút Đầu

**Testarossa (Claude) — Logic Review / Gameplay Design & Balance**
**Du an:** Memory Distortion: Nhieu Ky Uc
**Muc dich:** Phac thao trai nghiem nguoi choi trong 5-10 phut dau, danh gia pacing/confusion, de xuat event va dieu chinh intensity.

---

## 1. Gia dinh dau vao

Dua tren `MEMORY_DISTORTION_ULTIMATE_INFO_BY_DORA.md`:
- Cau truc: Room ↔ Hallway ↔ Room, nha 2 tang.
- Loop: Explore → Observe → Interact → Dialogue → Memory Distortion → Discover Truth.
- Distortion co 6 cap do (0-5), bat dau tu Level 0 (binh thuong).
- Nhan vat: Kevin, khong co combat, khong jumpscare spam.

Neu gia dinh nay sai lech so voi ban thiet ke moi nhat (Technical_Notes.md), can Kevin/Nobita xac nhan lai — Testarossa se dieu chinh journey theo do.

---

## 2. Player Journey — Timeline chi tiet

### Phut 0:00 - 1:00 — Onboarding im lang

- Man hinh mo, Kevin tinh day / buoc vao phong ngu cua chinh minh (Level 0, hoan toan binh thuong).
- Khong co UI ro rem, khong tutorial text an hien lien tuc.
- Player tu do di chuyen trong 1 phong duy nhat (phong ngu) de lam quen control (WASD/arrow, tuong tac E).
- 1 object tuong tac don gian (vd: cai guong, dong ho ban) → trigger 1 dong monologue ngan cua Kevin, thiet lap tone: binh than nhung co gi do khong on.

**Muc tieu:** Day la "baseline" — player phai nho ro trang thai binh thuong nay de sau nay nhan ra su khac biet.

### Phut 1:00 - 3:00 — Buoc ra hanh lang, kham pha tang tret co ban

- Player roi phong ngu, vao hanh lang tang 2 → xuong tang tret.
- Hanh lang dong vai tro hub: co the nhin thay 2-3 cua phong khac (phong bo me, phong em, WC) nhung chua can vao het.
- Khuyen khich kham pha nhe: 1 note/vat pham nho trong hanh lang goi y co chuyen gi do (vd: lich de ban bi gach cheo mot ngay, anh gia dinh treo lech).
- Xuong tang tret: phong khach, bep, phong an — cho phep tuong tac 2-3 vat the de lam quen he thong Interact.

**Muc tieu:** Mo rong khong gian tu tu, khong don dap player bang qua nhieu phong cung luc.

### Phut 3:00 - 5:00 — Distortion dau tien (Level 1)

- Player quay lai mot phong da di qua (vd: phong khach) → phat hien 1 thay doi nho: mot vat bi di chuyen vi tri, hoac mot cau thoai NPC (neu co) khac di mot chut.
- Day la distortion trigger dau tien trong game — **rat quan trong ve pacing**: phai du ro de player nhan ra, nhung khong qua lo lieu de khong gay hoang mang som.
- Sau khi phat hien, Kevin co 1 dong doc thoai the hien su nghi ngo nhe ("Minh nho la no o day ma?").

**Muc tieu:** Gieo hat giong nghi ngo dau tien — core hook cua game.

### Phut 5:00 - 8:00 — Lap lai loop, tang dan tan suat distortion

- Player tiep tuc kham pha cac phong con lai o tang tret (WC, khu vuc phu tro).
- Distortion Level 1 xuat hien them 1-2 lan nua o cac phong khac nhau, tan suat tang dan nhe.
- Co the dua vao 1 "anchor object" — mot vat the player duoc khuyen khich quay lai kiem tra nhieu lan (vd: buc anh gia dinh) — moi lan quay lai, vat co the thay doi mot chi tiet rat nho. Day la cong cu tao rhythm cho nguoi choi.

**Muc tieu:** Xay dung rhythm "explore → return → notice change" — day la vong lap chinh cua toan game, can duoc "day" ro trong doan mo dau.

### Phut 8:00 - 10:00 — Ket thuc doan mo dau, hook chuyen tiep

- Player len tang 2, tiep can phong lam viec hoac phong bo me (cua dong, gay to mo).
- Xuat hien 1 distortion manh hon mot chut (van trong Level 1-2, chua sang Level 2 that su) — du de tao cam giac "co gi do sai" ro rang hon, ket thuc doan mo dau bang mot cliffhanger nhe (vd: cua phong em dong lai dot ngot, hoac anh sang thay doi thoang qua).
- Khong reveal gi them — chi de lai cau hoi.

**Muc tieu:** Ket thuc 10 phut dau voi mot "moment" du manh de giu player choi tiep, nhung khong lam lo toan bo co che distortion qua som.

---

## 3. Danh gia: Co bi confuse khong?

**Rui ro confusion duoc xac dinh:**

1. **Qua nhieu phong mo cung luc** — neu tang tret + tang 2 deu mo tu dau, player co the lac huong, khong biet nen di dau truoc. → *De xuat: khoa tam thoi mot so cua (vd: phong bo me, phong lam viec) cho den khi qua mot moc nhat dinh, mo dan theo tien do.*
2. **Distortion dau tien qua tinh te** — neu thay doi qua nho, player co the khong nhan ra, dan den cam giac "khong hieu game dang lam gi". → *De xuat: distortion dau tien nen la mot thay doi ro rang hon binh thuong mot chut (lan dau can "day" ro co che, cac lan sau moi tinh te dan).*
3. **Thieu phan hoi (feedback) khi tuong tac** — neu Interact khong co animation/sound/UI cue ro rang, player se khong chac minh vua lam gi. → *De xuat: moi tuong tac can it nhat 1 tin hieu (am thanh nho + text ngan), du la moi truong yen tinh.*

**Ket luan:** Voi cau truc hien tai, muc do confuse o muc chap nhan duoc NEU distortion dau tien du ro va viec mo khoa phong duoc kiem soat. Neu khong co gating, rui ro confuse tang dang ke.

---

## 4. Danh gia: Pacing da on chua?

**Diem manh:**
- Cau truc 3 giai doan (baseline → explore → distortion dau tien) hop ly ve mat tam ly hoc — dung "quy tac thiet lap binh thuong truoc khi pha vo" (dung trong horror thiet ke tot).
- Loop explore → return → notice change duoc gioi thieu tu som, dung voi core loop da chot trong tai lieu master.

**Diem can dieu chinh:**
- Khoang phut 1:00-3:00 (kham pha tang tret co ban) co nguy co **hoi dai va phang** neu khong co bat ky hook nao ngoai di chuyen thuan tuy. 2 phut khong co bat ky tin hieu bat thuong nao co the lam nguoi choi mat tap trung, dac biet trong the loai psychological horror can duy tri tension ngam.
- Distortion dau tien xuat hien o phut 3:00 — hoi tre neu so voi chuan pacing cua game horror atmosphere (thuong nen co "unease cue" dau tien truoc phut 2:00, du rat nho, truoc khi co distortion ro rang).

**De xuat dieu chinh pacing:**
- Them 1 "micro-unease cue" o khoang phut 1:30 - 2:00 (truoc distortion chinh thuc): mot am thanh nho bat thuong, anh sang chop nhe, hoac mot do vat hoi lech vi tri ma khong can Kevin comment gi ca — chi de nguoi choi tu hoi "minh co nhin nham khong?". Day KHONG phai la distortion chinh thuc, chi la atmosphere seed.
- Dich distortion dau tien (chinh thuc, co Kevin phan ung) tu phut 3:00 xuong con khoang **2:30-3:00** de rut ngan doan "phang".

---

## 5. De xuat them Event

| Thoi diem | Event de xuat | Muc dich |
|---|---|---|
| ~1:30 | Micro-unease cue (am thanh/anh sang nho, khong loi thoai) | Gieo tension ngam truoc distortion chinh thuc |
| ~2:30-3:00 | Distortion Level 1 dau tien (ro rang, co Kevin phan ung) | Chinh thuc gioi thieu co che loi choi |
| ~4:30 | Anchor object xuat hien (vd: buc anh gia dinh) | Tao diem quay lai lap lai xuyen suot game |
| ~6:00-7:00 | Distortion Level 1 lan 2, o vi tri khac | Cung co pattern "explore → return → notice" |
| ~9:00 | Distortion manh hon (giap ranh Level 2), cliffhanger | Ket doan mo dau, giu hook |

---

## 6. De xuat dieu chinh Intensity

- **Intensity curve de xuat cho 10 phut dau:** thap → cuc thap (baseline) → tang rat nhe (micro cue) → spike nho (distortion 1) → on dinh o muc thap-trung → spike nho lan 2 → tang nhe cuoi doan (cliffhanger). Tuc la mot duong **rang cua nho dan**, khong phai duong thang tang deu — dieu nay giup tranh cam giac "leo thang deu deu" thuong thay o horror kem chat luong.
- Khong nen dua Level 2 (mat vat the) vao trong 10 phut dau — de danh cho doan sau, tranh "chay het bai" qua som.
- Am thanh nen giu vai tro chinh trong viec dieu tiet intensity o giai doan nay (theo dung dinh huong "im lang dot ngot, tieng dong nho tinh te" trong tai lieu master) hon la visual effect manh, vi Level 1 chua can effect thi giac ro ret.

---

## 7. Ket luan (Logic Review)

Cau truc hien tai ve co ban dung huong (baseline → explore → distortion), nhung can:
1. Them gating nhe cho cac phong o tang 2 de tranh player lac huong qua som.
2. Them 1 micro-unease cue truoc distortion chinh thuc de tranh doan giua bi "phang".
3. Dich thoi diem distortion dau tien som hon mot chut (2:30-3:00 thay vi 3:00+).
4. Gioi han Level distortion trong 10 phut dau o muc 0-1 (giap 2), khong vuot qua de giu du "bai" cho cac chuong sau.

Testarossa san sang dieu chinh lai neu Dora/Kevin co dinh huong khac ve cau truc nha hoac thu tu phong.
