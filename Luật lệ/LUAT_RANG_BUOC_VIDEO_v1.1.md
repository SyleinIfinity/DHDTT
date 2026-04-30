# LUẬT RÀNG BUỘC SẢN XUẤT VIDEO AI
## Dự án: "RLCraft Dregora Xâm Nhập Thực Tại"
### Phiên bản: 1.1 — Cập nhật đủ 5 nhân vật sống sót

---

> **Mục đích tài liệu này:** Đảm bảo mọi clip AI sinh ra đều nhất quán về phong cách, nhân vật và vật lý thực tại. Đọc kỹ trước khi tạo bất kỳ shot nào.

---

## PHẦN 1 — NHẤT QUÁN PHONG CÁCH (Style Consistency)

### 1.1 Bảng màu chủ đạo

| Vùng hình ảnh | Màu sắc | Ghi chú |
|---|---|---|
| Thế giới thực tại (bình thường) | Xám xi măng, trắng đèn đường, xanh LED | Màu đời thực Đà Nẵng ban đêm |
| Vùng bị pixel hóa | Đỏ cam Nether (#FF4500), đen than (#1A0A00) | Màu RLCraft địa ngục |
| Thế giới hybrid (cảnh kết) | Neon xanh lam + nền tro đỏ | Kết hợp 2 thế giới |
| Màn hình Creator | Trắng lạnh, font monospace xanh lá | Giao diện terminal/code |

**Quy tắc:** Không tự ý thêm màu tím, hồng, hay gold — trừ khi ghi rõ trong kịch bản.

---

### 1.2 Phong cách hình ảnh theo từng loại cảnh

**Cảnh thực tại Đà Nẵng:**
- Token bắt buộc: `cinematic lighting`, `wet asphalt reflection`, `night city Vietnam`, `Unreal Engine 5 render`
- Token cấm: `anime`, `cartoon`, `illustration`, `flat design`

**Cảnh pixel hóa / Nether xâm nhập:**
- Token bắt buộc: `hybrid reality`, `pixel corruption`, `voxel invasion`, `photorealistic base`, `8-bit overlay`
- Pixel chỉ xuất hiện ở vùng Rahovart chạm — phần còn lại vẫn đời thực

**Cảnh thế giới hybrid (4:40–5:00):**
- Token bắt buộc: `neon noir`, `hybrid world`, `concrete and voxel`, `neon reflection on ash ground`

---

### 1.3 Ánh sáng và góc máy

**Quy tắc ánh sáng:**
- Cảnh hành động ban đêm: Chỉ nguồn sáng tự nhiên trong cảnh (đèn đường, lửa, màn hình)
- Lâm: Ánh màn hình laptop xanh lạnh chiếu lên mặt và kính titanium
- Rahovart: Backlight lửa đỏ cam từ dưới lên — KHÔNG front-lit
- Ngọc: Áo khoác phản quang neon phản lửa Rahovart — dùng làm nguồn sáng phụ
- Khánh & Quân: Ánh màn hình trắng lạnh — tách biệt hoàn toàn với thế giới bên dưới

**Quy tắc góc máy:**
- Rahovart: Low angle ngước lên — tạo cảm giác khổng lồ, đe dọa
- Thành: Medium shot ngang ngực hoặc thấp hơn — nhấn vào khối cơ thể
- Kais (cảnh 4th Wall): Low angle ngước lên khi anh ta tìm "kẻ viết code"
- Khánh/Quân: Góc nhìn thẳng trung tính — cảm giác quan sát từ ngoài vào

---

## PHẦN 2 — NHẤT QUÁN NHÂN VẬT (Character Consistency)

### 2.1 Key Visual & Prompt Khóa

> **Nguyên tắc vàng:** Tạo ảnh Key Visual chuẩn cho từng nhân vật TRƯỚC khi tạo bất kỳ clip nào. Dùng ảnh đó làm Reference Image cho tất cả shot sau.

---

**① TRẦN HẢI LÂM**
```
Vietnamese male, 24, 178cm, slim build, straight black undercut hair,
thin titanium-frame glasses, charcoal hoodie with reflective tape on shoulder,
black tactical cargo pants, dirty white sneakers,
black waterproof backpack, blue-white laptop screen light on face,
cold analytical expression, night environment
```
- Đặc điểm không được thay đổi giữa các clip: **kính titanium mỏng + hoodie xám phản quang**
- Biểu cảm: Không biến sắc cho đến phút 4:00

---

**② NGUYỄN MAI AN**
```
Vietnamese female, 22, 164cm, slim athletic build, brown hair in high ponytail,
black leather biker jacket with colorful patches, camouflage jogger pants,
trail running shoes, modified helmet with hand-drawn decals and smoke visor,
metal chain across body, earphone in right ear only,
smirking confident expression, always in motion, night city street
```
- Đặc điểm không được thay đổi: **biker jacket + dây xích + mũ bảo hiểm decal**
- Không bao giờ dừng hẳn — luôn có micro-movement dù đứng yên

---

**③ PHẠM BÍCH NGỌC**
```
Vietnamese female, 25, 160cm, petite but resilient, black hair clipped up with crab clip,
light blue medical scrubs stained with dirt and blood,
neon yellow-green paramedic reflective jacket,
matching scrub pants, thick-soled sport shoes,
red-white cross first aid backpack,
cold evaluating expression, ice-calm gaze, not panicking
```
- Đặc điểm không được thay đổi: **áo khoác phản quang neon + ba lô chữ thập đỏ**
- Biểu cảm: Không hoảng loạn — chỉ đánh giá. Ngay cả khi tình huống nguy hiểm nhất.

---

**④ LÊ HOÀNG "KAIS"**
```
Vietnamese male, 23, 170cm, slim lanky build, slightly slouched posture,
natural brown wavy hair touching nape, messy unkempt,
unbuttoned flannel plaid shirt over black graphic t-shirt with monster logo,
ripped denim jeans worn at knees, old yellowed canvas sneakers,
large over-ear gaming headset around neck,
small lapel mic clipped to t-shirt collar,
eyes: mix of manic excitement + analytical calm + paranoid awareness,
NOT frightened when seeing monsters — recognition expression
```
- Đặc điểm không được thay đổi: **tai nghe over-ear quanh cổ + micro lapel + flannel khoác hờ**
- Ánh mắt là điểm nhấn quan trọng nhất — không được để anh ta trông sợ hãi thông thường
- [CAMERA: Close-up on eyes] khi anh ta phân tích Boss
- [CAMERA: Low angle] khi anh ta ngước nhìn lên phá 4th Wall

---

**⑤ ĐINH VÕ THÀNH**
```
Vietnamese male, 26, 182cm, 88kg, extremely muscular stocky build,
square jaw, wide cheekbones, small scar cutting through left eyebrow,
direct unwavering gaze,
orange-black safety vest over dark sweat-soaked t-shirt,
heavy-duty khaki work pants, steel-toe work boots,
motorbike pad protectors strapped to elbows and knees,
rubber security baton in hand, broken iron bar tucked in vest,
silent protective expression, always positioned between danger and teammates
```
- Đặc điểm không được thay đổi: **vest bảo hộ cam-đen + sẹo lông mày trái + pad bảo vệ khuỷu/đầu gối**
- Positioning bắt buộc: Luôn đứng giữa mối nguy và đồng đội — không bao giờ ở hàng sau

---

**⑥ PHAN VĂN KHÁNH (Meta)**
```
Vietnamese male, 21, 172cm, balanced build, clean white dress shirt sharp fit,
dark jeans, no accessories whatsoever,
cold calculating expression, debugging face — never panics,
blue-white terminal screen light, script timeline visible on monitor
```

**⑦ LÊ GIA ANH QUÂN (Meta)**
```
Vietnamese male, 21, 170cm, athletic posture, round or clear-frame glasses,
oversized graphic design hoodie bold colors, jogger pants, streetwear sneakers,
holding drawing tablet and stylus professionally,
curious creative expression, sharp eyes behind glasses,
render monitor background, warm creative workspace lighting
```

---

### 2.2 Quy trình dùng Reference Image

```
Bước 1 → Tạo Key Visual chuẩn (1 ảnh đứng yên, đủ ánh sáng, thấy rõ trang phục)
Bước 2 → Lưu ảnh
Bước 3 → Mọi clip có nhân vật đó PHẢI tải ảnh này lên làm Reference Image
Bước 4 → Thêm Prompt Khóa vào CUỐI lệnh (không để ở đầu)
Bước 5 → Dùng Last Frame của clip vừa tạo làm First Frame của clip kế tiếp
```

---

## PHẦN 3 — NHẤT QUÁN VẬT LÝ (Temporal & Physical Consistency)

### 3.1 Quy tắc vật lý bắt buộc

| Hiện tượng | Quy tắc |
|---|---|
| Lửa của Rahovart | Cháy xuống dưới theo trọng lực + làn sóng nhiệt làm méo không khí xung quanh |
| Pixel hóa | Lan từ vùng Rahovart chạm ra ngoài — không tự xuất hiện ở xa |
| Chạy bộ | Chân chạm đất — không moonwalk, không trượt, có bóng đổ |
| Tan pixel (Lâm) | Bắt đầu từ ngón tay → lan lên — không lan từ trên xuống |
| Thành phố tái tạo | Vật liệu thực xuất hiện trước → lớp voxel phủ lên sau |
| Màn hình Creator | Nổi lơ lửng nhưng có bóng đổ xuống nền |
| Áo khoác Ngọc | Phản quang neon phải sáng lên khi có nguồn lửa Rahovart gần đó |
| Dây xích An | Có khối lượng — không bay lơ lửng, phải có arc vật lý khi ném |

### 3.2 Lỗi vật lý phổ biến cần tránh

- ❌ Pixel xuất hiện ở xa không có lý do
- ❌ Nhân vật chạy không có bóng đổ
- ❌ Lửa không chiếu sáng lên mặt và trang phục nhân vật xung quanh
- ❌ Vết nứt không gian không có distortion quanh mép
- ❌ Tường hầm biến thành netherrack ngay lập tức (phải morphing từ từ)
- ❌ Thành đứng sau nhóm (luôn phải ở phía nguy hiểm)
- ❌ Kais trông sợ hãi khi nhìn Boss (phải là nhận ra, không phải kinh hãi)

---

## PHẦN 4 — KỸ THUẬT NỐI CẢNH (Chaining)

### 4.1 Quy trình First & Last Frames

```
Veo3 xuất 5 giây / lần → ghép nhiều clip lại:

Clip 1 (0–5s)  → lấy frame cuối → First Frame của Clip 2
Clip 2 (5–10s) → lấy frame cuối → First Frame của Clip 3
... tiếp tục
```

**Kết quả cần đạt:** Trang phục, mặt, tóc không thay đổi giữa các clip.

### 4.2 Thời lượng chuẩn theo loại cảnh

| Loại cảnh | Thời lượng đề xuất | Lý do |
|---|---|---|
| Cảnh hành động (chạy, chiến đấu) | 3–5 giây / clip | Tránh AI sáng tác thêm |
| Cảnh im lặng / BEAT | 5–8 giây / clip | Cho camera ở lại lâu hơn |
| Cảnh thoại | 3–4 giây / câu | 1 câu = 1 clip để kiểm soát khẩu hình |
| Cảnh VFX phức tạp (pixel hóa) | 3 giây / clip | Càng ngắn càng kiểm soát được kỹ xảo |
| Cảnh Thành đứng chắn | 4–5 giây / clip | Cần đủ thời gian để khối cơ thể tạo visual impact |

### 4.3 Checklist trước khi ghép clip

- [ ] Trang phục nhân vật giống nhau ở clip trước và sau?
- [ ] Khánh vẫn KHÔNG có phụ kiện?
- [ ] Tai nghe Kais vẫn vòng qua cổ (không đột ngột biến mất)?
- [ ] Sẹo lông mày trái Thành vẫn còn?
- [ ] Kính titanium Lâm không thay hình dạng?
- [ ] Màu áo khoác phản quang Ngọc nhất quán?
- [ ] First Frame clip mới khớp Last Frame clip cũ?
- [ ] Âm thanh transition không cắt đột ngột?

---

## PHẦN 5 — RAHOVART — QUY TẮC RIÊNG

### 5.1 Hình dạng bắt buộc
- Thân: Pixel block 8-bit ~40% + lửa volumetric thực ~60%
- KHÔNG bao giờ thấy toàn thân ngay lập tức — luôn camera từng bộ phận: mắt → tay → tổng thể
- Mắt: Pixel đỏ cam, không có lòng trắng
- Bàn tay: Block pixel — khi chạm thực tại để lại vết pixel lan như virus

### 5.2 Cách Rahovart di chuyển
- Bước đi, không bay — mỗi bước rung mặt đất
- Tìm kiếm: Quay đầu chậm, chính xác
- Tấn công: Cú quét tay → làn sóng lửa ngang

### 5.3 Prompt gợi ý
```
massive Nether Sovereign boss, hybrid 8-bit pixel block body with volumetric fire,
pixel red-orange glowing eyes, each step shakes ground,
photorealistic fire overlay on blocky pixel voxel form,
dark Vietnam city night background, low angle shot looking up,
cinematic lighting, Unreal Engine 5, no text no watermark --ar 16:9
```

---

## PHẦN 6 — CẢNH META (Khánh & Quân)

### 6.1 Màn hình Creator
- Kích thước: Màn hình máy tính bình thường phóng to — KHÔNG phải màn hình chiếu trời
- Texture: Bề mặt màn hình thực, vỡ một góc, pixel artifact ở cạnh
- Nội dung: Chỉ thấy `DELETE CHARACTER` và lệnh mờ — không rõ chi tiết

### 6.2 Không gian Creator
- Tối — chỉ ánh màn hình chiếu lên, không thấy tường rõ
- Cảm giác: Lớp thực tại khác, không cùng không gian với nhóm 5 người
- Camera: Nhìn thẳng vào họ từ phía trước, không pan xung quanh

---

## BẢNG TÓM TẮT NHANH

```
✅ LUÔN LÀM:
   → Tạo Key Visual nhân vật trước, dùng làm Reference Image
   → Thêm Prompt Khóa vào CUỐI mọi lệnh có nhân vật
   → Dùng Last Frame làm First Frame của clip kế tiếp
   → Thành đứng trước nhóm, Kais không trông sợ hãi

❌ KHÔNG BAO GIỜ:
   → Để pixel xuất hiện không có lý do
   → Thay đổi trang phục nhân vật giữa các clip
   → Để max intensity kéo dài quá 60 giây
   → Giải thích lore bằng thoại
   → Khánh có phụ kiện
   → Kais trông kinh hãi khi nhìn Rahovart
   → Dùng màu tím/hồng/gold không có trong bảng màu dự án
```

---

*Phiên bản 1.1 — Cập nhật: thêm Đinh Võ Thành, trang phục chi tiết đủ 5 nhân vật, Acting Protocol Kais*
