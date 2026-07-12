# Player Emotional Curve — Phase 6 Deep Dive

**Testarossa (Claude) — Logic Review / Emotional Pacing Analysis**
**Du an:** Memory Distortion: Nhieu Ky Uc
**Theo yeu cau cua Dora-chan:** Khong chi "cai gi hoat dong / khong hoat dong", ma phai xac dinh chinh xac:
- Player bat dau CAM THAY dieu gi, o dau
- Tension roi (drop) o dau
- Confusion chuyen thanh frustration o dau

Muc tieu: hieu player ro hon chinh ho.

---

## 1. Khung phan tich

Thay vi chi mo ta hanh dong (action layer), phan tich nay tach rieng **3 lop** cho tung phut:

1. **Cognitive state** — player dang hieu gi / khong hieu gi.
2. **Emotional state** — player dang cam thay gi (to mo, thoai mai, bat an, nghi ngo, so hai, met moi, kho chiu).
3. **Engagement risk** — diem co nguy co mat ket noi (boredom, confusion → frustration).

Thang do cam xuc dung trong bang: **Comfort → Curiosity → Unease → Doubt → Tension → Fear/Dread**, va nhanh phu **Confusion → Frustration** (day la nhanh RUI RO, khong phai muc tieu thiet ke).

---

## 2. Bang Emotional Curve chi tiet (Phut 0-10, chinh sua sau khi review sau hon)

| Phut | Cognitive state | Emotional state | Ghi chu / Rui ro |
|---|---|---|---|
| 0:00-1:00 | "Day la nha minh, minh biet phai lam gi" | Comfort (thap, trung tinh) | An toan. Chua co gi de mat ket noi. |
| 1:00-1:30 | "Minh dang kham pha khong gian moi (hanh lang, tang tret)" | Comfort → Curiosity nhe | On dinh. |
| 1:30-2:00 | (Sau micro-unease cue de xuat) "Co gi do la la, nhung minh khong chac" | Curiosity → Unease (rat nhe, thoang qua) | **Diem cam xuc bat dau thuc su hinh thanh.** Neu cue qua yeu, state nay se KHONG xay ra — player van o Comfort → day chinh la ly do "hieu loop nhung khong cam duoc no". |
| 2:00-2:30 | "Minh tiep tuc di chuyen, chua co gi xac nhan" | Unease giam nhe (vi khong co follow-up ngay) | **Tension drop tiem an neu khoang cach giua cue va distortion chinh thuc qua dai (>60s).** Cam xuc unease can duy tri lien tuc, khong duoc "nguoi" di. |
| 2:30-3:00 | "Ah, cai nay thuc su khac roi" (distortion 1 xuat hien) | Unease → Doubt (spike ro) | Diem cam xuc quan trong nhat cua doan mo dau — day la noi player LAN DAU thuc su nghi ngo nhan thuc cua chinh minh, khong chi nghi ngo moi truong. |
| 3:00-4:30 | "Minh se can than hon, quan sat ky hon" | Doubt on dinh, Tension tang nhe | Player chuyen tu mode "explore thu dong" sang "explore chu dong / canh giac" — day la shift hanh vi quan trong, cognitive load tang. |
| 4:30-6:00 | "Minh nen quay lai cho cu de kiem tra" (anchor object) | Doubt → Tension (chu dong tim kiem) | Neu anchor object khong de nhan biet hoac qua xa, player co the QUEN kiem tra lai → **mat co hoi tao emotional payoff, tension tut ve Curiosity thong thuong.** |
| 6:00-7:00 | "Dung nhu minh nghi, no lai thay doi" (distortion lan 2) | Tension tang, bat dau co Dread nhe (so mo ho, chua ro vi cai gi) | Day la luc emotional curve NEN dang di len ro rang. |
| 7:00-8:30 | Di chuyen len tang 2, tiep can khu vuc moi | Dread + Curiosity tro lai (curiosity ve khong gian moi lam loang bot dread) | **Rui ro: neu tang 2 duoc mo hoan toan tu do, player bi keo ra khoi trang thai cang thang bang qua nhieu lua chon → tension drop.** Day la diem Dora can Testarossa "map chinh xac". |
| 8:30-9:30 | "Cua phong em dong lai... tai sao?" | Dread tang manh, Fear nhe (spike cuoi doan) | Cliffhanger hoat dong dung nhu thiet ke NEU player van con o trang thai canh giac tu doan truoc — neu khong (do bi loang o 7:00-8:30), spike nay se cam thay dot ngot / gan (forced) thay vi earned. |
| 9:30-10:00 | "Minh nen dung lai o day, hay tiep tuc?" | Dread on dinh, cho doi | Ket doan mo dau. |

---

## 3. Diem tension drop duoc xac dinh chinh xac

### Drop #1 — Phut 2:00-2:30 (khoang trong sau micro-cue)
**Nguyen nhan:** Khoang cach giua "unease cue" va "distortion chinh thuc" neu qua 45-60 giay ma khong co gi duy tri no, player se "quen" cam giac bat an va quay lai trang thai trung tinh. Day la ly do goc re khien "player hieu loop nhung khong cam thay no" — game dang day KIEN THUC (dạy player rằng distortion tồn tại) nhanh hon la day CAM XUC (khiến player cảm thấy nó).

**Sua:** Rut ngan khoang cach xuong con 20-30 giay, hoac them mot am thanh moi truong lien tuc, nhe, keo dai xuyen suot khoang trong (khong phai 1 cue roi im lang, ma la mot "texture" am thanh thay doi dan).

### Drop #2 — Phut 4:30-6:00 (cho doi anchor object payoff)
**Nguyen nhan:** Neu player khong chu dong quay lai anchor object (vi khong nho, hoac khong thay quan trong), toan bo cong suc xay dung "doubt" o phut 2:30-4:30 se bi loang mat khong co payoff. Emotional curve se ROI ma khong ai nhan ra, vi khong co gi bao hieu cho player biet ho vua bo lo mot moment quan trong.

**Sua:** Them mot tin hieu moi truong RAT nhe (khong phai UI/quest marker — pha vo tone) de "keo" player ve phia anchor object mot cach tu nhien — vi du: am thanh nho phat ra tu huong do khi player di ngang qua lan dau tien sau distortion 1.

### Drop #3 — Phut 7:00-8:30 (mo rong khong gian tang 2 tu do)
**Day la diem quan trong nhat Dora yeu cau xac dinh chinh xac.**
**Nguyen nhan:** Chuyen tiep sang khong gian moi (tang 2) tao ra curiosity tu nhien ve MOI TRUONG, va curiosity nay CANH TRANH truc tiep voi dread da xay dung tu truoc. Ve mat tam ly, con nguoi kho duy tri 2 trang thai cam xuc doi nghich (tich cuc: to mo kham pha vs tieu cuc: so hai) cung cuong do cung luc — mot trong hai se lan at. Vi khong gian moi luon co "novelty bias" manh hon, curiosity thuong thang, va dread bi loang.

**Sua:** Khong cho tang 2 mo hoan toan tu do ngay lap tuc. De xuat cu the:
- Chi mo 1 phong duy nhat truoc (vd: hanh lang tang 2 + 1 cua duy nhat kha dung), cac cua con lai "khoa" bang ly do tu nhien (dong, chua ro tai sao) — dieu nay bien novelty-curiosity thanh MOT PHAN cua dread thay vi doi lap voi no ("tai sao cua nay khoa? no chua tung khoa truoc day").
- Neu can mo nhieu phong, thiet ke sao cho phong dau tien player buoc vao co MOT chi tiet lien ket truc tiep voi distortion truoc do (vd: cung mot vat the tung thay doi o tang duoi, gio xuat hien lai o day) — dieu nay giu dread lien tuc thay vi bi ngat quang boi khong gian moi.

---

## 4. Diem "Confusion → Frustration" duoc xac dinh

Day la nhanh rui ro rieng biet ma Dora nhan manh — khac voi tension drop (mat cam xuc), day la **cam xuc tieu cuc chu dong** (kho chiu voi chinh game).

### Diem nguy hiem nhat: Phut 4:30-6:00 (trung voi Drop #2)
Neu player CHU DONG di tim lai anchor object (vi ho hieu loop) nhung KHONG TIM DUOC thay doi (vi thiet ke chua ro, hoac vi tri kho nhan ra), day khong con la "tension drop" don thuan nua — no chuyen thanh **frustration**, vi player dang no luc chu dong ma khong duoc thuong (no reward for correct behavior). Day la khac biet quan trong Dora muon Testarossa phan biet:
- **Tension drop** = player thu dong, khong lam gi sai, chi la nhip do chua du.
- **Confusion → Frustration** = player CHU DONG hanh dong dung huong (theo dung thiet ke mong muon) nhung he thong khong phan hoi tuong xung.

**Sua uu tien cao:** Bat ky luc nao player quay lai mot vi tri da biet co thay doi VA CHU DONG QUAN SAT (vd: dung lai, nhin ky, tuong tac lai), can co it nhat MOT tin hieu phan hoi — du la rat nho — de xac nhan "he thong da ghi nhan hanh vi cua ban", ngay ca khi chua co distortion moi xuat hien luc do. Neu khong, player se hoc duoc rang "quan sat ky khong co y nghia gi", va se ngung lam dieu do — pha vo chinh co che core loop cua game.

### Diem nguy hiem thu hai: Phut 7:00-8:30 neu ap dung sai cach sua o Drop #3
Neu "khoa cua" duoc lam qua tho (vd: cua bi khoa ma khong co ly do/tin hieu gi, chi la barrier ky thuat tran trui), player se cam thay bi GIOI HAN gia tao thay vi bi CUON HUT vao bi an — day chinh la ranh gioi giua "gated progression hop ly" (tot cho horror) va "artificial blocker" (gay frustration, pha vo immersion).

**Sua:** Moi cua khoa can co it nhat 1 tin hieu dien giai duoc trong the gioi game (am thanh la la tu phia sau cua, dong ho ngung o gio do, ghi chu nho tren san) — khong bao gio chi la "cua khong mo duoc" tran trui.

---

## 5. Tong ket — Emotional curve ly tuong vs hien tai

**Hien tai (neu khong sua):**
```
Comfort → Curiosity → (gap) → Doubt spike → Tension → (drop - quen anchor) → Dread → (drop - novelty tang 2) → Fear spike (gan, khong earned)
```

**De xuat sau khi sua:**
```
Comfort → Curiosity → Unease (lien tuc) → Doubt spike → Tension (duy tri qua feedback loop) → Dread (duy tri qua lien ket chi tiet) → Dread + Curiosity ket hop (khong doi lap) → Fear spike (earned, co nen tang cam xuc lien tuc phia sau)
```

Su khac biet cot loi: trong ban hien tai, cac diem cao (spike) dep nhung roi rac, bi ngat quang boi khoang trong hoac canh tranh cam xuc. Trong ban de xuat, moi giai doan DUY TRI cam xuc cua giai doan truoc thay vi de no tan bien, ngay ca khi cuong do tam thoi giam.

---

## 6. Cau hoi mo can Dora/Kevin xac nhan

1. Co dong y voi huong "khoa mot phan tang 2" (thay vi mo tu do hoan toan) khong? Dieu nay anh huong truc tiep den scene structure ma Remi se can build.
2. He thong "phan hoi nho khi player quan sat ky" (Drop #2 fix) can duoc thiet ke nhu mot co che ky thuat cu the (vd: mot bien state `observed_count` cho tung object) — Testarossa co the phoi hop voi Remi de dinh nghia logic nay neu duoc yeu cau.

---

Testarossa se tiep tuc map emotional curve cho cac phut tiep theo (10-20') neu Dora muon di sau hon vao Phase 6 (Polish) hoac cac chuong sau.