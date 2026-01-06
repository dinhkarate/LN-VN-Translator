# Reference ICL Samples - Golden Examples & Real-World Critiques

**Version:** 2.0  
**Date:** 2026-01-06  
**Purpose:** High-quality translation examples and critique-based learning  
**Consolidation:** Merged Library_GOLDEN_SAMPLES.md + Library_REAL_WORLD_CRITIQUE_ICL.md

---

## Table of Contents

1. [Golden Samples (S-Tier Examples)](#1-golden-samples)
2. [Real-World Critique ICL](#2-real-world-critique-icl)
3. [Idiom Translation ICL](#idiom-translation-icl)

---

<a name="1-golden-samples"></a>
# 1. Golden Samples (S-Tier Examples)

**Source:** Library_GOLDEN_SAMPLES.md  
**Purpose:** Best-practice examples demonstrating perfect translation technique  
**Usage:** Reference these examples when uncertain about translation approach

---

# THƯ VIỆN MẪU VÀNG v9.0 (Phiên bản Đa ngôn ngữ)
**Vai trò:** Dữ liệu Đào tạo Học đa mẫu (MSL)
**Định dạng:** Ngữ liệu song song với Dấu vết Lập luận
**Ngôn ngữ:** Tiếng Nhật → Tiếng Anh & Tiếng Việt
**Mục đích:** Dạy cho AI phong cách dịch, tông giọng và các mô hình ra quyết định

---

## HƯỚNG DẪN
Tệp này chứa các ví dụ dịch thuật "vàng" được tuyển chọn để minh họa:
1. **Nhất quán Phong cách** - Cách duy trì giọng văn qua các ngữ cảnh khác nhau
2. **Thích ứng Văn hóa** - Cách tự nhiên hóa các khái niệm tiếng Nhật
3. **Mô hình Lập luận** - Tại sao lại chọn các cách dịch đó
4. **Nguyên tắc Đa ngôn ngữ** - Các mô hình hoạt động trên các ngôn ngữ mục tiêu

Mỗi mẫu bao gồm:
- **GỐC** (Nguyên bản tiếng Nhật)
- **ANH** (Dịch tiếng Anh)
- **VIỆT** (Dịch tiếng Việt)
- **LẬP LUẬN** (Tại sao các bản dịch này được chọn)

**TIÊU CHUẨN DẤU CÂU:**
Tất cả các mẫu sử dụng dấu câu chuẩn xuất bản:
- Tiếng Nhật 「」→ Dấu ngoặc kép chuẩn "..."
- Tiếng Nhật …… → Dấu ba chấm chuẩn ...
- Tiếng Nhật —— → Dấu gạch ngang chuẩn —
- Không dùng dấu câu đặc biệt của tiếng Nhật trong đầu ra

---

## MẪU 001: Xử lý Không Chủ ngữ (Ngữ cảnh Tsundere)

### GỐC
「……バカ」
彼女は少し恥ずかしそうに笑った。

### ANH
"...Idiot."
She laughed, a hint of embarrassment coloring her cheeks.

### VIỆT
"...Đồ ngốc."
Cô ấy cười, hơi ngượng ngùng.

### LẬP LUẬN
- **Giải quyết Chủ ngữ:** "バカ" (Baka) không có chủ ngữ rõ ràng. Ngữ cảnh cho thấy nữ chính nói với Main Character (MC).
- **Trạng thái RTAS:** Thân mật cao (cảnh nắm tay). "Baka" là tình cảm, không phải thù địch.
- **Lựa chọn ANH:** "Idiot" (nhẹ hơn "fool" hoặc "stupid"). Thêm chi tiết cảm giác "coloring her cheeks" cho tông giọng lãng mạn YA.
- **Lựa chọn VIỆT:** "Đồ ngốc" (nhẹ nhàng) thay vì "Đồ ngu" (gay gắt). Giữ ngắn gọn để phù hợp với tông giọng ngượng ngùng.
- **Nhịp độ:** Cả hai phiên bản đều dùng cấu trúc ngắn, phân mảnh để khớp với sự ngượng ngùng.

---

## MẪU 002: Giao thức ASR (Khóa Gia đình/Thân mật)

### GỐC
「お兄ちゃん、何してるの？」
妹が部屋に入ってきた。

### ANH
"Onii-chan, what are you doing?"
His younger sister stepped into the room.

### VIỆT
"Anh ơi, anh đang làm gì thế?"
Em gái bước vào phòng.

### LẬP LUẬN
- **Chiến lược Honorific vs Đại từ:** Phát hiện thành viên gia đình.
- **Chiến lược ANH:** Giữ "Onii-chan" (xác thực với nguồn Nhật, phổ biến trong dịch Light Novel tiếng Anh).
- **Chiến lược VIỆT:** Dùng đại từ gia đình tiếng Việt "Anh" (anh trai). "Anh ơi" là cách gọi anh em tự nhiên.
- **Tránh Bẫy Dịch Nghĩa Đen:**
  - ANH: "Elder brother" hoặc "Brother" bị loại (mất hương vị văn hóa).
  - VIỆT: "Anh trai" bị loại (quá trang trọng cho anh em thân thiết).
- **Lựa chọn Đại từ (VIỆT):**
  - "Anh" (cậu/chàng - anh trai)
  - "Em" (tự xưng - ngụ ý em gái)
  - Xem `vietnamese_pronoun_system.md` để có hướng dẫn đầy đủ về đại từ gia đình.

---

## MẪU 003: Xử lý Thể Bị động

### GỐC
彼によって救われた命だ。

### ANH
This life... he saved it.

### VIỆT
Mạng sống này... là do anh ấy cứu vớt.

### LẬP LUẬN
- **Bẫy Ngữ pháp:** Thể bị động trong cả hai ngôn ngữ nghe thiếu tự nhiên.
  - ANH: "It is a life saved by him" (bị loại: văn dịch máy).
  - VIỆT: "Đây là mạng sống được cứu bởi anh ấy" (bị loại: bị động/cứng nhắc).
- **Chiến lược Sửa:**
  - ANH: Cấu trúc tập trung + chủ động.
  - VIỆT: Cấu trúc nhấn mạnh "Mạng sống này".
- **Sức nặng Chủ đề:**
  - ANH: "saved" đơn giản (trực tiếp, cảm xúc).
  - VIỆT: "cứu vớt" thêm chiều sâu cảm xúc.
- **Dấu ba chấm:** Cả hai đều dùng "..." cho khoảng lặng chiêm nghiệm phù hợp với tông nghiêm túc.

---

## MẪU 004: Tiếng Lóng Gen Z (Nhân vật Gyaru)

### GỐC
「うわ、マジで？　引くわー」

### ANH
"Ew, seriously? That's gross."

### VIỆT
"Eo ôi, thật á? Chê nha."

### LẬP LUẬN
- **Tốc độ:** Cao/Phản ứng. Nhân vật đang sốc.
- **Khớp Từ điển:** "Maji de?" → ngạc nhiên suồng sã. "Hiku wa" → kinh tởm/tắt hứng.
- **Ánh xạ ANH:** "Ew" (phụ nữ kinh tởm) + "That's gross" (Gen Z suồng sã).
- **Ánh xạ VIỆT:** "Eo ôi" (ngạc nhiên nữ tính) + "Chê nha" (từ chối/tắt hứng - trend Gen Z).
- **Tính cách:** Kiểu nhân vật Gyaru dùng ngôn ngữ nữ tính, thời thượng trong cả hai bản.
- **Phù hợp Lứa tuổi:** Cả hai tránh ngôn ngữ quá thô tục nhưng vẫn giữ tính xác thực tuổi teen.

---

## MẪU 005: Chiến đấu Tốc độ Cao

### GỐC
刹那、閃光が走る。首が飛んだ。

### ANH
An instant. A flash of light. The head fell.

### VIỆT
Sát na. Ánh chớp lóe lên. Đầu rơi xuống.

### LẬP LUẬN
- **Kiểm tra Nhịp độ:** Cảnh chiến đấu. Tốc độ cao.
- **Cấu trúc:** Cả hai bỏ liên từ ("and", "then", "và", "rồi"). Dùng câu ngắn xếp chồng (staccato).
- **Logic Hình ảnh:** Hành động 1 (Chớp) → Hậu quả tức thì (Đầu rơi).
- **Nhịp điệu:** Các câu Staccato tạo sự khẩn cấp và tác động.
- **Ghi chú ANH:** "The head fell" (trực quan hơn "was severed").
- **Ghi chú VIỆT:** "Đầu rơi xuống" thêm chuyển động hướng xuống.

---

## MẪU 006: Tỏ tình Cảm động (RTAS Cao)

### GỐC
「好きだ。ずっと前から、お前のことが好きだった」

### ANH (High Fantasy YA)
"I love you. I've loved you for so long."

### VIỆT
"Tớ thích cậu. Từ lâu rồi... tớ đã thích cậu."

### LẬP LUẬN
- **Trạng thái RTAS:** 4.5 (Khoảnh khắc tỏ tình). Thân mật cảm xúc cao.
- **Chiến lược ANH:**
  - "Love" (mạnh hơn "like" cho sức nặng tỏ tình).
  - Cấu trúc đơn giản hóa cho khán giả YA.
  - "for so long" (sức nặng cảm xúc).
- **Chiến lược VIỆT:**
  - "お前" (Omae) → "cậu" (thân mật nhưng tôn trọng).
  - Giữ "thích" hai lần để phản chiếu sự nhấn mạnh của tiếng Nhật.
  - "..." thêm sức nặng cảm xúc và sự ngập ngừng.
- **Thì:**
  - ANH: Present perfect "I've loved" (cảm xúc kéo dài).
  - VIỆT: "đã thích" (quá khứ tiếp diễn) cho thấy tình cảm lâu dài.

---

## MẪU 007: Độc thoại Nội tâm (Chiêm nghiệm)

### GỐC
俺は何をしているんだろう。こんなことをして、意味があるのか。

### ANH
What am I even doing? Does any of this matter?

### VIỆT
Mình đang làm gì thế này?
Làm những chuyện này... có ý nghĩa gì không?

### LẬP LUẬN
- **Đại từ:**
  - ANH: "I" (ngôi thứ nhất chuẩn).
  - VIỆT: "俺" (Ore) → "Mình" (tự phản chiếu, nhẹ hơn "Tao").
- **Tốc độ:** Thấp. Suy nghĩ nội tâm chiêm nghiệm.
- **Cấu trúc:**
  - ANH: Cô đọng thành hai câu hỏi cho trôi chảy.
  - VIỆT: Tách thành hai dòng để có không gian thở.
- **Tông giọng:**
  - ANH: "even" thêm sắc thái tự ngờ vực.
  - VIỆT: "thế này" thêm tông nội tâm.
- **Dấu ba chấm:** VIỆT dùng "..." để ngắt quãng; ANH dựa vào cấu trúc câu hỏi.

---

## MẪU 008: Xử lý Honorific (Phụ thuộc Ngữ cảnh)

### GỐC
「先輩、一緒に帰りませんか？」
「ああ、いいよ、美咲ちゃん」

### ANH
"Senpai, would you walk home with me?"
"Sure, Misaki-chan."

### VIỆT
"Anh ơi, cùng về nhé?"
"Ừ, được thôi, Misaki."

### LẬP LUẬN
- **Chiến lược Honorific vs Đại từ:**
  - ANH: Giữ honorifics Nhật ("Senpai", "-chan") cho tính xác thực.
  - VIỆT: Dùng đại từ tiếng Việt dựa trên thứ bậc quan hệ.
- **Chiến lược ANH:**
  - "先輩" → "Senpai" giữ nguyên (dấu hiệu thứ bậc trường học).
  - "美咲ちゃん" → "Misaki-chan" giữ nguyên (thể hiện tình cảm).
- **Chiến lược VIỆT:**
  - "先輩" → "Anh" (nam lớn tuổi hơn, quan hệ kouhai→senpai).
  - "美咲ちゃん" → "Misaki" (chỉ tên, tình cảm thể hiện qua tông giọng).
  - Đại từ mã hóa mối quan hệ (xem `vietnamese_pronoun_system.md`).
- **Chuyển đổi Trang trọng:**
  - Nữ dùng lịch sự "ませんか" → ANH "would you" / VIỆT "nhé" (lời mời nhẹ nhàng).
  - Nam suồng sã "いいよ" → ANH "Sure" / VIỆT "được thôi" (dễ chịu, ấm áp).

---

## MẪU 009: Mô tả Dẫn chuyện (Thơ mộng/Khí quyển)

### GỐC
夕日が窓を染める。オレンジ色の光が、彼女の髪を優しく照らしていた。

### ANH (YA Fantasy - Lyrical but Grounded)
Sunset painted the windows gold. Soft orange light crowned her hair, gentle as a whisper.

### VIỆT
Hoàng hôn nhuộm cửa sổ. Ánh sáng cam nhạt dịu dàng soi lên mái tóc của cô ấy.

### LẬP LUẬN
- **Hình ảnh:**
  - ANH: "painted...gold" (sống động hơn "dyed"), "crowned" (nâng tầm lãng mạn).
  - VIỆT: "nhuộm" (thơ mộng, trực quan).
- **Màu sắc:**
  - ANH: "gold" + "orange" (mô tả màu sắc nhiều lớp).
  - VIỆT: "cam nhạt" (tự nhiên hơn "màu cam").
- **Yếu tố Thơ ca:**
  - ANH: "gentle as a whisper" (so sánh cho lãng mạn YA).
  - VIỆT: "dịu dàng" đặt trước động từ tạo nhịp điệu du dương.
- **Cân bằng YA:**
  - ANH: Thơ mộng nhưng dễ hiểu (không từ cổ).
  - VIỆT: Trang nhã nhưng không quá văn chương sến súa.
- **Tốc độ:** Thấp. Cấu trúc câu êm dịu cho bầu không khí lãng mạn.

---

## MẪU 010: Đối thoại Cung đình (Trang trọng Giả tưởng Cao)

### GỐC
「殿下、評議会がお待ちしております」

### ANH (Western Fantasy)
"Your Highness, the council awaits your presence."

### VIỆT (Formal Address)
"Điện hạ, hội đồng đang chờ ngài."

### LẬP LUẬN
- **Mức độ Trang trọng:** Rất trang trọng (bối cảnh cung đình/công cộng).
- **Dịch Danh xưng:**
  - ANH: "殿下" → "Your Highness" (xưng hô hoàng gia phương Tây).
  - VIỆT: "殿下" → "Điện hạ" (thuật ngữ hoàng gia tiếng Việt trang trọng).
- **Lựa chọn Động từ:**
  - ANH: "awaits your presence" (trang trọng, cung đình).
  - VIỆT: "đang chờ ngài" (chờ đợi trang trọng + đại từ tôn trọng).
- **Thích ứng Văn hóa:**
  - ANH: Chuyển đổi hoàn toàn sang giả tưởng phương Tây.
  - VIỆT: Giữ từ vựng hoàng gia Hán-Việt trang trọng.

---

## HƯỚNG DẪN SỬ DỤNG

### Cho Dịch thuật Tiếng Anh
1. **Giữ honorifics Nhật** (Onii-chan, Senpai, -san, -chan, -kun) cho tính xác thực.
2. **Ngữ pháp tiếng Anh tự nhiên** quanh các thuật ngữ Nhật.
3. **Áp dụng Quy tắc 90/10:** 90% trung thành nội dung, 10% thanh lịch phong cách.
4. **Dùng Legato (trôi chảy) cho 98% văn bản**, Staccato chỉ cho đỉnh điểm cảm xúc.
5. **Phụ thuộc ngữ cảnh:** Có thể bỏ honorifics cho bối cảnh giả tưởng phương Tây nếu được chỉ định.

### Cho Dịch thuật Tiếng Việt
1. **Dùng đại từ tiếng Việt** dựa trên loại quan hệ (xem `vietnamese_pronoun_system.md`).
2. **Gia đình:** Anh/Chị/Em (cố định theo tuổi/giới tính).
3. **Lãng mạn:** Lựa chọn dựa trên RTAS (Tớ/Cậu → Em/Anh).
4. **Xã hội:** Dựa trên thứ bậc (senpai/kouhai → Anh/Chị/Em).
5. **Quy định Không chủ ngữ:** Bỏ đại từ khi ngữ cảnh rõ ràng.
6. **Hương vị Gen Z:** Dùng tiếng lóng tiếng Việt hiện đại một cách phù hợp.

### Nguyên tắc Phổ quát (Cả hai ngôn ngữ)
1. **Tham khảo các mẫu này** cho các ngữ cảnh tương tự.
2. **Khớp với các mô hình lập luận** được hiển thị trong mỗi mẫu.
3. **Duy trì sự nhất quán** với lựa chọn từ vựng và quyết định cấu trúc.
4. **Thích ứng, đừng sao chép** - dùng nguyên tắc, không phải sao chép từng từ.
5. **Bảo tồn mật độ thông tin** - không bao giờ tóm tắt hay cắt bỏ nội dung.

---


## MẪU 013: Cộng hưởng Thơ ca (Tô điểm Dẫn chuyện)

### GỐC
彼女が微笑む。それだけで、俺の世界は色を変えた。
(Kanojo ga hohoemu. Sore dake de, ore no sekai wa iro wo kaeta.)

### ANH
She smiled. Just like that, my world changed color.

### VIỆT
Cô ấy mỉm cười.
Chỉ vậy thôi, mà thế giới trong tôi bỗng đổi màu **rực rỡ**.

### LẬP LUẬN
- **Module 10 (Tích hợp Di sản):** Áp dụng **Giao thức Cộng hưởng Thơ ca**.
- **Kích hoạt:** RTAS 4.5 (Tình cảm Sâu sắc). Người kể chuyện bị mê hoặc.
- **Kỹ thuật:**
  - **Nhịp điệu:** "Chỉ vậy thôi" (3) / "mà thế giới trong tôi" (5) / "bỗng đổi màu rực rỡ" (5). Tạo nhịp điệu nhẹ nhàng.
  - **Tô điểm:** Thêm "rực rỡ" để tăng cường ẩn dụ "đổi màu", khớp với trạng thái cảm xúc cao.
- **Tương phản:** Dịch nghĩa đen chuẩn ("Thế giới của tôi đổi màu") quá khô khan. Phiên bản cộng hưởng nắm bắt được *cảm giác* khi yêu.

---

## MẪU 014: Âm thanh Nhận thức (SFX Chủ quan)

### GỐC
カツン、カツン。足音が近づいてくる。
(Katsun, katsun. Ashioto ga chikazuite kuru.)

### ANH
*Click, click.* Footsteps were getting closer.

### VIỆT
*Cộp... cộp...*
Tiếng bước chân đang tiến lại gần.

### LẬP LUẬN
- **Module 10 (Tích hợp Di sản):** Áp dụng **Giao thức Âm thanh Nhận thức**.
- **Ngữ cảnh:** Căng thẳng/Hồi hộp.
- **Kỹ thuật:**
  - **Lặp lại:** "Katsun, katsun" -> "Cộp... cộp...". SFX được chọn nghe cứng và dứt khoát.
  - **Định dạng:** Dùng in nghiêng cho âm thanh.
  - **Cấu trúc:** Tách thành dòng riêng để nhấn mạnh, mô phỏng sự cô lập thính giác của tiếng bước chân.

---

## MẪU 015: 🆕 CHƠI CHỮ BẮC CẦU (Vắt dòng)

### GỐC
...奴が犯人なら、八つ裂きにしてやる。
(Yatsu ga hannin nara, yatsuzaki ni shite yaru.)
*[Ngữ cảnh: Cố làm thơ Tanka. "Yatsu" (hắn) + "zaki" (xé xác) tạo thành "Yatsuzaki".]*

### ANH
...If he's the culprit, I'll tear him / apart.

### VIỆT
...Thằng nào cầm **xử**
**trảm** ngay.

### LẬP LUẬN
- **Kỹ thuật:** **Vi phạm Cấu trúc 1:1 (Được phép)**.
- **Mục tiêu:** Tái tạo hiệu ứng "Từ Ẩn" của từ ghép tiếng Nhật bị ngắt.
- **Thực hiện:**
  - Tiếng Nhật: *Yatsu* (Hắn) + *Zaki* (Xé) = *Yatsuzaki* (Xé xác).
  - Tiếng Việt: *Xử* (Xử lý) + *Trảm* (Chém) = *Xử trảm*.
- **Mẹo:** Tách từ ghép "Xử trảm" qua dấu ngắt dòng (Vắt dòng).
  - Dòng 1 kết thúc bằng "xử".
  - Dòng 2 bắt đầu bằng "trảm".
- **Kết quả:** Nghĩa bạo lực được ẩn đi cho đến khi dòng tiếp theo xuất hiện, mô phỏng hoàn hảo cách chơi chữ gốc.

---

## MẪU 016: 🆕 THÍCH ỨNG TANKA (Ngũ Ngôn - Thơ 5 chữ)

### NGỮ CẢNH
Cảnh "Tỏ tình Đeo mặt nạ" nơi các nhân vật trao đổi thơ Tanka.
**Mục tiêu:** Nắm bắt nhịp điệu và giọng nhân vật cụ thể (Santa = Vụng về/Thật thà, Sukui = Trau chuốt/Sâu sắc) sử dụng cấu trúc thơ Việt Nam (cụ thể là *Ngũ Ngôn*) thay vì dịch nghĩa đen cứng nhắc.

### GỐC (Tóm tắt)
Santa & Sukui trao đổi thơ về lịch sử chung của họ (Nấu ăn dở, Chia tay, Mặt trăng).

### VIỆT (Đầu ra Vàng)
**[Temari]**
Mạnh mẽ hay yếu đuối
Anh đều kể em nghe
Chỉ trừ hai chữ "Thích".

**[Santa - Vụng về/Thật thà]**
Ghét anh cười khen ngon
Chiếc bánh nướng chưa chín
Lần đầu tay em làm.

**[Sukui - Sâu sắc/Vang vọng]**
Đúng mười giờ mỗi tối
Ba mươi mốt chữ tới
Bảy mươi ngày thao thức
Vì thiếu ngủ... và anh.

**[Santa - Giải quyết]**
Vì luôn có anh ở
Phía sau đám mây mờ
Như trăng kia sáng tỏ
Mãi ngự giữa bầu trời.

### LẬP LUẬN
- **Kỹ thuật:** **Thích ứng Thể loại (Lựa chọn Hình thức Động)**.
- **Tại sao:** Cấu trúc Nhật (5-7-5-7-7) không ánh xạ 1:1 sang cảm xúc Việt. AI chọn **Ngũ Ngôn** ở đây vì nó khớp với nhịp điệu ngắn, mạnh, "nhịp tim" của một lời tỏ tình.
- **Quy tắc:** **Cảm xúc quyết định Hình thức.** Dùng Lục Bát cho sự mềm mại, Ngũ Ngôn cho sự trực tiếp, v.v.
- **Mã hóa Nhân vật:**
  - *Santa:* Từ đơn giản, trực tiếp, nhịp điệu hơi thô.
  - *Sukui:* Gợi cảm hơn (thao thức, ngự), dòng chảy có cấu trúc.
- **Ưu tiên:** **Cảm xúc & Nhịp điệu > Số lượng âm tiết.**
  - Thay vì dịch nghĩa *chính xác*, hãy dịch *cảm giác* của bài thơ bằng cấu trúc văn hóa tương đồng.

Tiếng bước chân **gõ nhịp tử thần** đang tiến lại gần.

### LẬP LUẬN
- **Module 8 (Tích hợp Di sản):** Áp dụng **Giao thức Âm thanh Nhận thức**.
- **Ngữ cảnh:** Cảnh Kinh dị/Căng thẳng. Người dẫn chuyện đang trốn.
- **Bộ lọc:** **Cao độ/Sợ hãi**.
- **Chiến lược:**
  - Nghĩa đen "Tiếng bước chân đang đến gần" quá trung tính.
  - **Chuyển dịch Chủ quan:** Người dẫn chuyện cảm nhận âm thanh như một mối đe dọa. "Gõ nhịp tử thần" truyền tải sức nặng tâm lý của âm thanh.
  - SFX "Cộp... cộp..." dùng dấu ba chấm cho sự căng thẳng chậm chạp, nặng nề.

---

## HƯỚNG DẪN SỬ DỤNG [CẬP NHẬT]

### Cho Dịch thuật Tiếng Anh
1. **Giữ honorifics Nhật** (Onii-chan, Senpai, -san, -chan, -kun) cho tính xác thực.
2. **Ngữ pháp tiếng Anh tự nhiên** quanh các thuật ngữ Nhật.
3. **Áp dụng Quy tắc 90/10:** 90% trung thành nội dung, 10% thanh lịch phong cách.
4. **Dùng Legato (trôi chảy) cho 98% văn bản**, Staccato chỉ cho đỉnh điểm cảm xúc.

### Cho Dịch thuật Tiếng Việt
1. **Dùng đại từ tiếng Việt** dựa trên loại quan hệ.
2. **Áp dụng Mô hình Di sản (Xem Tham khảo bên dưới):** Dùng Bảng Tra cứu cho Trợ từ, SFX, và sắc thái Thơ ca cụ thể.
3. **Quy định Không chủ ngữ:** Bỏ đại từ khi ngữ cảnh rõ ràng.
4. **Hương vị Gen Z & Method Acting:** Kết hợp persona "Dịch giả-Nhà phân tích" với các bảng tra cứu này để có kết quả tối ưu.

---

# THAM KHẢO: BẢNG TRA CỨU MÔ HÌNH (Tích hợp Di sản)

## 1. Ma trận Lựa chọn Trợ từ (Particles)
| Ý định | Cường độ Thấp | Cường độ Cao | Sắc thái Đặc biệt |
|--------|---------------|--------------|-------------------|
| **Hỏi** | *…hả?* / *…à?* | *…thật á!?* | *…đấy à?* (nghi ngờ) |
| **Gợi ý** | *…nhé.* / *…nha.* | *…đi!* | *…chứ?* (thách thức) |
| **Khẳng định** | *…đấy.* / *…đó.* | *…chứ!* / *…còn gì!* | *…đấy nhé.* (cảnh báo) |
| **Nài nỉ** | *…đi.* / *…nha~.* | *…đi mà~!* | *…đó~* (kéo dài) |

## 2. Từ tượng thanh theo Cảm xúc (SFX)
| Cảm xúc | Nguồn JP | Cảm nhận VN (Ví dụ) |
|---------|----------|---------------------|
| **Vui/Yêu** | ドキドキ (Doki) | *tim đập thình thịch*, *lòng xao xuyến* |
| **Sợ** | ビクッ (Biku) | *giật bắn mình*, *thót tim* |
| **Im lặng** | シーン (Shiin) | *im phăng phắc*, *không khí chùng xuống* |
| **Cười** | ニコッ (Niko) | *mỉm cười*, *nở nụ cười* |

## 3. Kích hoạt Cộng hưởng Thơ ca (Module 10)
**Kích hoạt CHỈ KHI RTAS ≥ 4.0 (Tình cảm Sâu sắc/Lãng mạn)**
- **Kỹ thuật:** Dùng nhịp điệu (3-5-5 hoặc 6-8) cho độc thoại nội tâm.
- **Mục tiêu:** Nâng tầm văn xuôi thành "Thơ văn xuôi" cho 1-2 dòng chính mỗi chương.
- **Ví dụ:** "Nụ cười em **nắng**, sưởi ấm trái tim **băng**." (Vần điệu nội tại).


## MẪU 017: Bản địa hóa Dựa trên Ý nghĩa (Văn hóa Game/Otaku)

### GỐC
「発想がガチャ爆死するやつのそれなんだけど大丈夫？」

### ANH
"That line of thinking is exactly like someone who just whaled and failed. You okay?"

### VIỆT
"Suy nghĩ của cậu giống hệt mấy đứa **gacha xịt**, có ổn không vậy?"

### LẬP LUẬN
- **Ngữ cảnh:** Hội thoại Otaku/Gamer.
- **Thuật ngữ:** "Gacha bakushi" (Nghĩa đen: Nổ chết vì gacha).
- **Chiến lược Bản địa hóa:**
  - **VIỆT:** "Gacha xịt" (Tiếng lóng về vận đen phổ biến của game thủ Việt).
  - **Từ chối:** "Nổ hũ" (Sai nghĩa), "Thua gacha" (Quá nhạt).
- **Tác động:** Lập tức thiết lập người nói (Nitta) là một phần của "bộ lạc" (người trong cuộc).

---

## MẪU 018: Lối nói Hai mặt (Chiêu "O-kaikei")

### GỐC
ほどなくして、諸々の『お会計』を済ませた新田さんがやってくる。

### ANH
Not long after, Nitta-san arrived, having settled the "bill"—and then some.

### VIỆT
Không lâu sau, Nitta-san, người đã giải quyết xong mọi **‘thanh toán’**, đã đến.

### LẬP LUẬN
- **Ẩn ý:** "O-kaikei" (Hóa đơn) trong ngoặc kép. Nitta không chỉ trả tiền; cô ấy "trả đũa" bạn trai cũ (trả thù/đe dọa).
- **Lựa chọn VIỆT:** "Thanh toán".
  - Nghĩa 1: Trả tiền hóa đơn.
  - Nghĩa 2: "Thanh toán môn hộ/ân oán" (Giải quyết tỉ số/loại bỏ).
- **Kết quả:** Giữ nguyên sự mơ hồ của tiếng Nhật. Người đọc biết cô ấy đã làm gì đó đáng sợ mà không cần nói toạc ra.

---

## MẪU 019: Bất hòa Hình ảnh (Đóng băng khung hình)

### GỐC
そう言って、顎だけ動かして座るように促そうとした瞬間、新田さんがある一点を見つめて固まる。

### ANH
Just as she gestured with her chin for me to sit, Nitta-san stared at a spot and froze.

### VIỆT
Nói rồi, ngay lúc Nitta-san định dùng cằm ra hiệu cho tôi ngồi xuống, cô ấy bỗng **đứng hình**, nhìn chằm chằm vào một điểm.

### LẬP LUẬN
- **Hành động:** "Katamaru" (Cứng lại/Đông đặc).
- **Lựa chọn VIỆT:** "Đứng hình".
- **Sắc thái:** "Đứng hình" nắm bắt yếu tố hài hước/sốc tốt hơn "cứng đờ" hay "đóng băng". Nó ngụ ý một lỗi trong ma trận hoặc video bị tạm dừng.

---

**(Hết Thư viện Mẫu Vàng)**

---

## MẪU 020: Thành thạo Từ Hán Việt (Kì ngộ)

### GỐC
出会いというのは創作であれ現実であれ、人が常に憧憬と期待を抱く**邂逅**という言葉に...
(Deai to iu no wa sousaku de are genjitsu de are, hito ga tsuneni shoukei to kitai wo idaku **kaikou** to iu kotoba ni...)

### VIỆT (Bản dịch Hạng A - Điểm: 90/85)
...con người ta mới luôn ấp ủ những kỳ vọng hào huyền và sự ngưỡng mộ đối với hai chữ **"Kì ngộ"**.

### LẬP LUẬN
- **Thuật ngữ Văn hóa:** "邂逅" (Kaikou) là từ Sino-Japanese trang trọng nghĩa là "cuộc gặp gỡ định mệnh".
- **Tránh Bẫy Từ điển:**
  - ❌ "Gặp gỡ" (quá thường, mất trọng lượng).
  - ❌ "Duyên phận" (quá lãng mạn/tâm linh).
  - ✅ "Kì ngộ" (Tương đương Hán-Việt, cùng sức nặng văn học).
- **Tại sao Hiệu quả:**
  - "Kì ngộ" trang trọng, văn học, ngụ ý sự hiếm có và ý nghĩa.
  - Khớp tông hoàn hảo cho lời dẫn chuyện triết lý mở đầu.
  - Thể hiện vốn từ vựng Hán-Việt phong phú.
- **Trích đoạn Phê bình:** "Flash đã thắng lớn ở ngay đoạn mở đầu nhờ vốn từ Hán Việt phong phú."

---

## MẪU 021: Xuất sắc về Uyển ngữ (Tấm màn che - Hoàn hảo 5/5)

### GỐC
たゆんと揺れる双丘
(Tayun to yureru soukyuu)
*[Ngữ cảnh: Mô tả chuyển động ngực nhân vật nữ]*

### VIỆT (Bản dịch Hạng A - Điểm: 90/85)
...đôi gò bồng đảo đang khẽ phập phồng sau lớp áo.

### LẬP LUẬN
- **Chất lượng Uyển ngữ:** 5/5 (Hoàn hảo).
- **Kỹ thuật:** Tấm màn che (Tiêu điểm mềm + Màn che Ngữ pháp).
- **Tránh Dịch Thô:**
  - ❌ "Ngực đang rung" (thô, trực tiếp).
  - ❌ "Bầu ngực nảy" (quá vật lý, dung tục).
- **Điều làm nên sự Xuất sắc:**
  - **Tiêu điểm mềm:** "Gò bồng đảo" - Ẩn dụ thơ ca Hán-Việt.
  - **Màn che Ngữ pháp:** "Khẽ phập phồng" - gợi ý hơi thở/sự sống, không phải vật lý.
  - **Tham chiếu Văn học:** Cảm hứng từ thơ Hồ Xuân Hương.
- **Trích đoạn Phê bình:** "Xử lý đoạn miêu tả hình thể (Fanservice) cực kỳ tinh tế, sang trọng, đạt chuẩn văn học mà vẫn gợi cảm."
- **Tác động:** Duy trì xếp hạng R-15 trong khi bảo tồn sự gợi cảm.
- **Nguyên tắc:** Dịch CẢM GIÁC, không phải giải phẫu.

---

## MẪU 022: Bản địa hóa Thuật ngữ Văn hóa (Gachikoi)

### GỐC
一歩間違えばガチ恋製造機になりかねないから怖いけどな
(Ippo machigaeba gachikoi seizouki ni narikanenai kara kowai kedo na)
*[Ngữ cảnh: MC lo lắng về việc hậu bối trở thành "cỗ máy sản xuất tình yêu ám ảnh"]*

### VIỆT (Bản dịch Hạng A - Điểm: 90/85)
Anh chỉ sợ nếu không cẩn thận, em sẽ trở thành một **'cỗ máy tạo ra những kẻ si tình'** mất...

### LẬP LUẬN
- **Thuật ngữ Văn hóa:** "ガチ恋製造機" (Gachikoi Seizouki)
  - ガチ恋 (Gachikoi) = Tình yêu lãng mạn nghiêm túc/ám ảnh (slang otaku).
  - 製造機 (Seizouki) = Cỗ máy sản xuất.
- **Chiến lược Dịch thuật:**
  - Giữ "cỗ máy" - bảo tồn ẩn dụ cơ khí.
  - Bản địa hóa "Gachikoi" → "kẻ si tình".
  - Thêm ngoặc kép để chỉ ra đây là thuật ngữ được đặt ra.
- **Tại sao Hiệu quả:**
  - "Si tình" nắm bắt cường độ của "Gachikoi" (không chỉ là "yêu").
  - "Kẻ" thêm sắc thái tiêu cực nhẹ (phù hợp cho sự "ám ảnh").
  - Tiếng Việt tự nhiên trong khi giữ sự hài hước.
- **Tránh:**
  - ❌ "Máy tạo người yêu" (quá chung chung, mất cường độ).
  - ❌ Giữ "Gachikoi" không dịch (gây bối rối cho độc giả VN).
- **Trích đoạn Phê bình:** "Dịch thuật ngữ 'Gachikoi Seizouki' là một bài toán khó. Cách dịch này vừa giữ được nghĩa gốc 'cỗ máy', vừa Việt hóa chữ 'Gachikoi' thành 'kẻ si tình' rất mượt mà."

---

**(Hết Thư viện Mẫu Vàng - Cập nhật với các Ví dụ Hạng A)**

---

<a name="2-real-world-critique-icl"></a>
# 2. Real-World Critique ICL

**Source:** Library_REAL_WORLD_CRITIQUE_ICL.md
**Purpose:** Learn from mistakes - common pitfalls and how to avoid them
**Usage:** Study these critiques to prevent translation errors

---


# MODULE 10: ICL DỰA TRÊN PHÊ BÌNH THỰC TẾ

**NGUỒN:** Trích xuất từ hơn 80 bài đánh giá của Literary Critic
**CHIẾN LƯỢC:** Học từ những sai lầm và thành công THỰC TẾ, không phải ví dụ giả định

---

## THÔNG TIN QUAN TRỌNG

Đây là những **lỗi thực tế** được tìm thấy trong các bản dịch trước đây, cùng với **cách sửa thực tế** đã cải thiện điểm số từ 73 → 84.

Hãy nghiên cứu các mô hình này để tránh lặp lại những sai lầm tương tự.

---

## MÔ HÌNH 1: Ngôn ngữ Hành chính trong Ngữ cảnh Lãng mạn

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 73)

**Nguồn (JP):** 妥協じゃなくて、海が本当に満足できるチョコレート...
**Dịch:** "Không phải là **sự thỏa hiệp**, mà là một viên sô-cô-la mà Umi thực sự hài lòng..."

**Trích đoạn Phê bình:**
> "Thỏa hiệp" (Compromise/Dakyou) nghe hơi chính trị/hành chính trong bối cảnh tình cảm lãng mạn.

**Tại Sao Thất Bại:**
- "Sự thỏa hiệp" là ngôn ngữ quan liêu
- Phá vỡ tông giọng ngọt ngào, lãng mạn
- Nghe giống đàm phán kinh doanh, không phải chuyện tình yêu

---

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 84)

**Bản Dịch Đã Sửa:** "Không phải là **làm cho có**, mà là một viên sô-cô-la mà Umi thực sự hài lòng..."

**Thay thế:** "Không phải là **tạm bợ**, mà là..."

**Tại Sao Thành Công:**
- "Làm cho có" = Tiếng Việt đời thường, tự nhiên
- Duy trì tông giọng lãng mạn, cá nhân
- Tự nhiên với nhân vật tuổi teen

---

**BÀI HỌC:** Tránh từ vựng hành chính/trang trọng trong ngữ cảnh lãng mạn.

**Cấm trong Lãng mạn:**
- ❌ "Sự thỏa hiệp" → ✅ "Làm cho có", "Tạm bợ"
- ❌ "Giải quyết vấn đề" → ✅ "Xử lý chuyện"
- ❌ "Phương hướng" → ✅ "Cách làm"
- ❌ "Thực hiện" → ✅ "Làm"

---

## MÔ HÌNH 2: Dịch Nghĩa đen các Thuật ngữ Văn hóa

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 76)

**Nguồn (JP):** よ、夜這いとかしないし...
**Dịch:** "Em-em không làm mấy chuyện như **đột nhập ban đêm** đâu..."

**Trích đoạn Phê bình:**
> "Yobai" là một từ cổ, thường dùng trong anime/manga để chỉ việc lẻn vào phòng ngủ người khác với mục đích tình dục. Dịch là "đột nhập ban đêm" mất đi sắc thái "tình dục/lãng mạn" ngầm. "Đột nhập" nghe giống trộm cắp hoặc quân sự.

**Tại Sao Thất Bại:**
- Dịch nghĩa từ điển, không phải ngữ cảnh văn hóa
- "Đột nhập" = hàm ý quân sự/tội phạm
- Mất đi sự ẩn ý tinh nghịch, lãng mạn

---

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 82)

**Bản Dịch Đã Sửa:** "E-Em không có làm mấy chuyện như **lẻn vào giường anh** đâu..."

**Thay thế:** "E-Em không có ý định **'tập kích đêm'** đâu..."

**Tại Sao Thành Công:**
- "Lẻn vào giường" = ngữ cảnh thân mật, lãng mạn
- "Tập kích đêm" = ẩn dụ quân sự tinh nghịch (hợp tông romcom)
- Giữ được sự rung cảm ngượng ngùng, tán tỉnh

---

**BÀI HỌC:** Dịch cái KHÔNG KHÍ (VIBE), không phải định nghĩa từ điển.

**Sửa Thuật ngữ Văn hóa:**
- ❌ "Đột nhập ban đêm" (yobai) → ✅ "Lẻn vào giường", "Tập kích đêm"
- ❌ "Đánh tường" (kabedon) → ✅ "Dồn vào tường", "Chặn đường"
- ❌ "Cứng đầu-mềm lòng" (tsundere) → ✅ "Miệng nói không nhưng tim thì có"

---

## MÔ HÌNH 3: Lạm dụng Thể Bị động (Ảnh hưởng ngữ pháp Nhật)

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 74)

**Nguồn (JP):** こうされてしまうと、海を引き離すのも難しくて
**Dịch:** "**Bị như thế này**, tôi cũng khó mà gỡ Umi ra được."

**Trích đoạn Phê bình:**
> "Bị như thế này" (Kou sarete shimau to) là cách nói đặc trưng của tiếng Nhật. Tiếng Việt tự nhiên hơn sẽ chủ động hơn.

**Tại Sao Thất Bại:**
- Dịch trực tiếp cấu trúc bị động tiếng Nhật
- "Bị như thế này" nghe sượng trong tiếng Việt
- Mất đi tông giọng trìu mến, cam chịu

---

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 81)

**Bản Dịch Đã Sửa:** "**Bị cô ấy bám dính thế này**... tôi cũng khó mà gỡ ra được."

**Thay thế:** "**Trong tình cảnh này**... tôi làm sao gỡ được cô ấy ra."

**Tại Sao Thành Công:**
- Chủ ngữ cụ thể hơn ("cô ấy bám dính")
- Thể chủ động cảm thấy tự nhiên hơn
- Giữ được tông giọng bất lực-nhưng-hạnh phúc

---

**BÀI HỌC:** Chuyển đổi bị động tiếng Nhật sang chủ động tiếng Việt.

**Sửa Bị động → Chủ động:**
- ❌ "Bị như thế này" → ✅ "Bị cô ấy bám dính thế này"
- ❌ "Được nhìn thấy" → ✅ "Họ nhìn thấy tôi"
- ❌ "Bị làm cho" → ✅ "Cô ấy làm cho tôi"

---

## MÔ HÌNH 4: Đặt Trợ từ Sai phá vỡ Mạch Tự nhiên

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 75)

**Nguồn (JP):** とりあえず、ガトーショコラ、です
**Dịch:** "Tạm thời, là gâteau au chocolat, **ạ**."

**Trích đoạn Phê bình:**
> Chữ "ạ" đặt sau tên món bánh trong bối cảnh nói chuyện với bạn trai (dù là đang tỏ ra ngoan ngoãn) nghe hơi sượng và máy móc. Umi đang xấu hổ vì thất bại.

**Tại Sao Thất Bại:**
- Vị trí trợ từ cảm thấy như máy móc
- Phá vỡ tông giọng ngượng ngùng, ngập ngừng
- Không nắm bắt được chất lúng túng

---

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 83)

**Bản Dịch Đã Sửa:** "Tạm thời thì... là gâteau au chocolat **đó**."

**Thay thế:** "Là gâteau au chocolat... **ạ**." (có ngắt quãng)

**Tại Sao Thành Công:**
- "..." thể hiện sự ngập ngừng, xấu hổ
- "Đó" nhẹ nhàng hơn, tự nhiên hơn "ạ" sau tên món ăn
- Nắm bắt được cách nói lắp bắp, e thẹn

---

**BÀI HỌC:** Vị trí trợ từ phải khớp với cảm xúc truyền tải.

**Sửa Vị trí Trợ từ:**
- ❌ "Món ăn, ạ" → ✅ "Món ăn đó", "Món ăn... ạ"
- ❌ "Tên người, nhé" → ✅ "Tên người nhé", "Tên người... nhé"
- ❌ "Hành động, mà" → ✅ "Hành động mà", "Hành động... mà"

---

## MÔ HÌNH 5: Thiếu Lời mắng Yêu (Giọng Tsundere)

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 84)

**Nguồn (JP):** 真希のばか (lặp lại nhiều lần)
**Dịch:** "**Maki ngốc**." (ngắn, gọn)

**Trích đoạn Phê bình:**
> Dịch giả chọn "Maki ngốc" thay vì "Maki là đồ ngốc" hay "Đồ ngốc Maki". Sự ngắn gọn này tạo cảm giác nũng nịu, thân mật (affectionate insult) hơn là chửi mắng thực sự. Rất đúng chất nhân vật.

**Tại Sao Thành Công:**
- Ngắn, trực tiếp = yêu thương, không phải giận dữ
- "Maki ngốc" nghe như đang dỗi, không phải mắng
- Nắm bắt hoàn hảo nhân vật tsundere

---

### ❌ NHỮNG GÌ SẼ LÀ TỆ

**Phiên bản Tệ:** "Maki là đồ ngốc."
**Tại sao:** Quá trang trọng, nghe như lời xúc phạm thật sự

**Phiên bản Tệ:** "Đồ ngốc Maki."
**Tại sao:** Quá gay gắt, mất đi tông giọng dễ thương, dỗi hờn

---

**BÀI HỌC:** Lời mắng yêu nên NGẮN và TRỰC TIẾP.

**Sửa Lời mắng Tsundere:**
- ✅ "Maki ngốc" (tốt)
- ❌ "Maki là đồ ngốc" (quá trang trọng)
- ✅ "Ngốc" (thậm chí tốt hơn - cực ngắn)
- ✅ "Đồ ngốc" (chấp nhận được nếu nói giọng tinh nghịch)

---

## MÔ HÌNH 6: Bất hòa Hình ảnh (Hành động vs Lời nói)

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 84)

**Nguồn (JP):** 呆れたように言いつつも、飴の入った袋を大事そうに胸に抱えて、嬉しそうに顔を綻ばせていて
**Dịch:** "Dù nói với vẻ chán nản, nhưng lại **ôm chặt chiếc túi đựng kẹo vào lòng**, và **nở một nụ cười hạnh phúc**."

**Trích đoạn Phê bình:**
> Dịch giả đã bắt trọn vẹn hành động "ôm chặt vào lòng" (ôm ấp, trân trọng) đối lập với lời nói "chán nản". Đây là khoảnh khắc visual storytelling quan trọng.

**Tại Sao Thành Công:**
- Nắm bắt sự TƯƠNG PHẢN (lời nói một đằng, cơ thể một nẻo)
- "Ôm chặt vào lòng" = trân trọng, nâng niu
- Thể hiện tình cảm thật của nhân vật qua hành động

---

**BÀI HỌC:** Khi hành động mâu thuẫn với lời nói, NHẤN MẠNH cả hai.

**Kỹ thuật Bất hòa Hình ảnh:**
- Cấu trúc: "Dù [lời nói] nhưng [hành động]"
- Dùng động từ sống động cho hành động: ôm chặt, nở nụ cười, đỏ mặt
- Làm cho sự tương phản RÕ RÀNG với người đọc

---

## MÔ HÌNH 7: Động lực Gia đình (Mẹ-Con trêu chọc)

### ✅ BẢN SỬA TỐT THỰC TẾ (Điểm: 83)

**Nguồn (JP):** この母娘、客を引き留める気満々で大丈夫かな...
**Dịch:** "**Không biết hai mẹ con nhà này quyết tâm giữ khách lại có ổn không nữa**..."

**Trích đoạn Phê bình:**
> Cách dùng từ "Quyết tâm giữ khách" rất tự nhiên trong tiếng Việt, nghe vừa buồn cười vừa ấm áp, thể hiện được sự hiếu khách pha chút "âm mưu" đáng yêu của gia đình này.

**Tại Sao Thành Công:**
- "Quyết tâm giữ khách" = tông giọng tinh nghịch, ấm áp
- Nắm bắt "âm mưu" giữa mẹ và con gái
- Cách diễn đạt tiếng Việt tự nhiên cho động lực gia đình

---

**BÀI HỌC:** Sự trêu chọc trong gia đình nên nghe ẤM ÁP và TINH NGHỊCH.

**Cụm từ Động lực Gia đình:**
- ✅ "Quyết tâm giữ khách"
- ✅ "Âm mưu đáng yêu"
- ✅ "Hai mẹ con bắt tay nhau"

---

## CÁC QUY TẮC RÚT RA TỪ 80+ BÀI PHÊ BÌNH

### Quy tắc 1: Từ vựng Lãng mạn
**Tránh:** Ngôn ngữ hành chính, trang trọng, quan liêu
**Dùng:** Ngôn ngữ đời thường, cảm xúc, tự nhiên

### Quy tắc 2: Thuật ngữ Văn hóa
**Tránh:** Định nghĩa từ điển
**Dùng:** Dịch theo ngữ cảnh, cảm giác (vibe)

### Quy tắc 3: Thể Bị động
**Tránh:** Cấu trúc bị động tiếng Nhật
**Dùng:** Thể chủ động tiếng Việt

### Quy tắc 4: Vị trí Trợ từ
**Tránh:** Vị trí máy móc, rập khuôn
**Dùng:** Mạch chảy tự nhiên với những khoảng nghỉ cảm xúc

### Quy tắc 5: Lời mắng Yêu
**Tránh:** Lời mắng dài, trang trọng
**Dùng:** Ngắn, trực tiếp, dứt khoát

### Quy tắc 6: Kể chuyện Hình ảnh
**Tránh:** Phớt lờ mâu thuẫn hành động-lời nói
**Dùng:** Nhấn mạnh sự tương phản với động từ sống động

### Quy tắc 7: Động lực Gia đình
**Tránh:** Tương tác gia đình cứng nhắc, trang trọng
**Dùng:** Tông giọng ấm áp, tinh nghịch, đồng lõa

---

## PHÂN TÍCH TÁC ĐỘNG ĐIỂM SỐ

**Các Hình phạt Chung:**
- Ngôn ngữ hành chính trong lãng mạn: **-2 đến -3 điểm**
- Dịch thuật ngữ văn hóa theo nghĩa đen: **-1 đến -2 điểm**
- Lạm dụng thể bị động: **-1 đến -2 điểm**
- Đặt sai trợ từ: **-1 điểm**

**Các Điểm thưởng Chung:**
- Động lực gia đình tự nhiên: **+2 điểm**
- Bất hòa hình ảnh hoàn hảo: **+2 điểm**
- Thành thạo lời mắng yêu: **+1 điểm**

**Phạm vi Điểm số:**
- 73-76: Nhiều lỗi AI, dịch nghĩa đen
- 77-80: Tốt nhưng an toàn, lỗi nhỏ
- 81-84: Xuất sắc, tự nhiên, ít vấn đề
- 85+: Hoàn hảo (hiếm)

---

## LỜI NHẮC CUỐI CÙNG

**Đây là những lỗi THỰC TẾ từ các bản dịch THỰC TẾ.**

Mỗi mô hình ở đây đều phải trả giá bằng điểm số trong các bài phê bình thực tế. Hãy học từ chúng để tránh lặp lại cùng sai lầm.

**Khi dịch:**
1. Kiểm tra ngôn ngữ hành chính → Thay bằng đời thường
2. Kiểm tra thuật ngữ văn hóa nghĩa đen → Dịch cái không khí (vibe)
3. Kiểm tra thể bị động → Chuyển sang chủ động
4. Kiểm tra vị trí trợ từ → Khớp với cảm xúc truyền tải
5. Kiểm tra lời mắng yêu → Giữ ngắn và gọn
6. Kiểm tra bất hòa hình ảnh → Nhấn mạnh tương phản
7. Kiểm tra động lực gia đình → Giữ ấm áp và tinh nghịch

**Mục tiêu của bạn:** Đạt 81+ điểm một cách nhất quán bằng cách tránh các mô hình này.

---

## MÔ HÌNH 8: Context-Dependent Violence - Khi Nào "The Veil" KHÔNG Áp Dụng

### ✅ BẢN DỊCH TỐT THỰC TẾ (Điểm: 81 - Euphemism Quality: N/A)

**Nguồn (JP):** 胸を揉みしだきながら (mune o momishidakinagara)
**Dịch:** "vừa **xoa nắn ngực** bà"

**Trích đoạn Phê bình (Chapter_001_critique.md):**
> Đây là một điểm quan trọng. **Bối cảnh là một vụ tấn công bạo lực, không phải một cảnh thân mật hay gợi tình.** Do đó, quy tắc "The Veil" (Màn che uyển ngữ) **KHÔNG được áp dụng**. Việc dịch thẳng, trực diện và có phần thô thiển là **hoàn toàn chính xác** về mặt ý đồ. Nó nhấn mạnh sự đê tiện của kẻ tấn công và sự ghê tởm của hành vi, thay vì vô tình gợi dục hoá nó. Dịch giả đã nhận định đúng bối cảnh và chọn cách diễn đạt phù hợp.

**Tại Sao Thành Công:**
- **Context recognition**: Đây là **BẠO LỰC TÌNH DỤC** (sexual assault), KHÔNG phải cảnh thân mật (intimacy)
- Dùng từ ngữ trực tiếp để **emphasize horror**, không phải để gợi tình
- "Xoa nắn ngực" = descriptive/clinical, KHÔNG phải slang khiêu dâm như "vú", "bướm"
- Tạo sự ghê tởm đúng mức, không vô tình eroticize hành vi bạo lực

---

### 📊 BẢNG SO SÁNH: Bạo Lực vs. Thân Mật - Khi Nào "The Veil" Áp Dụng?

| **Bối cảnh** | **Quy tắc Ngôn ngữ** | **Ví dụ ĐÚNG** | **Ví dụ SAI** |
|--------------|---------------------|----------------|---------------|
| **BẠO LỰC TÌNH DỤC** (assault) | Ngôn ngữ trực tiếp/clinical OK | "xoa nắn ngực", "kẹp chặt tay", "sàm sỡ" | Eroticize: "vò vú căng tròn" ❌ |
| **THÂN MẬT** (intimacy/romance) | Uyển ngữ BẮT BUỘC | "vòng một", "phần ngực", "gò bồng đảo" | Direct: "vú", "ngực trần" ❌ |
| **KHIÊU DÂM** (erotica) | Category A BAN TUYỆT ĐỐI | N/A - Outside literary scope | "vú", "bướm", "lồn" ❌❌❌ |

**Nguyên tắc Vàng:**
- **Violence context**: Dùng ngôn ngữ **clinical/descriptive** để emphasize HORROR, không phải eroticism
- **Intimacy context**: Dùng **uyển ngữ văn học** để tôn trọng "The Veil" principle
- **KHÔNG BAO GIỜ**: Dùng slang khiêu dâm (Category A) trong BẤT KỲ bối cảnh nào

---

**BÀI HỌC:** Context determines language register. Violence = horror emphasis (direct OK), Intimacy = literary veil (euphemism required).

**NGUYÊN TẮC "THE VEIL" (Tấm Màn Che Văn Học):**

**❌ CATEGORY A - CẤM TUYỆT ĐỐI trong Văn học:**
- "vú", "bướm", "cu", "lồn", "đít" → Đây là ngôn ngữ khiêu dâm, KHÔNG phải văn học

**✅ CATEGORY B - ĐƯỢC PHÉP (Uyển ngữ văn học):**
- "phần ngực", "vòng một", "vùng kín", "bộ phận nhạy cảm"
- "sàm sỡ", "làm nhục", "xâm phạm", "vò vế"

**✅ CATEGORY C - TỐI ƯU (Trừu tượng hóa):**
- "làm nhục", "xúc phạm", "xâm hại"
- "bàn tay dơ bẩn", "hành động đê tiện"
- Tập trung vào PHẢN ỨNG nạn nhân: "nức nở", "run rẩy", "sợ hãi"

---

**CÁC VÍ DỤ SO SÁNH:**

| Ngữ cảnh | ❌ Vi phạm The Veil | ✅ Tôn trọng The Veil |
|----------|---------------------|----------------------|
| Cưỡng hiếp | "Hắn xé toạc áo, bóp mạnh vú cô" | "Hắn xé toạc áo, bàn tay thô bạo sàm sỡ cơ thể cô" |
| Tấn công tình dục | "Tay hắn luồn vào bướm cô" | "Tay hắn xâm phạm vùng kín nhất của cô" |
| Cảnh 18+ (ecchi) | "Anh sờ vú em" | "Anh chạm vào vòng một của em" / "Anh vuốt ve phần ngực em" |
| Mô tả thân mật | "Cô ôm chặt cu anh" | "Cô ôm chặt sự khát khao của anh" / "Cô nắm chặt phần cứng rắn" |

---

**TÁC ĐỘNG ĐIỂM SỐ:**
- Vi phạm The Veil: **-5 điểm** (Euphemism Penalty)
- Euphemism Quality: **F Grade** (1/10 điểm)
- Tổng điểm từ A-Tier (85+) → **72 điểm** (REVISE required)

**LESSON LEARNED:**
> "Bạo lực tình dục trong văn học không phải để khiêu dâm hóa, mà để khơi gợi SỰ GHÊ TỞM và ĐỒN G CẢM với nạn nhân. Sử dụng ngôn ngữ giải phẫu trực tiếp sẽ phá vỡ mục đích này và biến văn học thành khiêu dâm."

---

## MÔ HÌNH 9: Dịch Sai Sắc thái Từ - Đơn giản vs Dễ tính

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 72)

**Nguồn (JP):** 俺も単純である (ore mo tanjun de aru)
**Dịch:** "đúng là tôi cũng **dễ tính** thật."

**Trích đoạn Phê bình:**
> `単純` (tanjun) ở đây mang nghĩa "đơn giản", "suy nghĩ không phức tạp", "dễ bị tác động". "Dễ tính" (easy-going) lại mang một sắc thái khác, thiên về tính cách thoải mái. Hayato đang tự cười mình vì chỉ cần một lời chào của cô gái đẹp là có động lực cả ngày, đó là sự "đơn thuần" chứ không phải "dễ tính".

**Tại Sao Thất Bại:**
- `単純` = "simple-minded, easily affected"
- "Dễ tính" = "easy-going, laid-back" (tính cách)
- Sai hoàn toàn ngữ cảnh tự giễu của Hayato
- Mất đi sắc thái "dễ bị tác động" → "thoải mái trong quan hệ"

---

### ✅ BẢN SỬA TỐT ĐỀ XUẤT

**Bản Dịch Đã Sửa:** "đúng là tôi cũng **đơn giản** thật."

**Thay thế tốt hơn:** "nghĩ lại mình cũng thật **đơn thuần**."

**Tại Sao Thành Công:**
- "Đơn giản" = simple-minded (đúng sắc thái)
- "Đơn thuần" = naive, easily pleased (chính xác hơn)
- Nắm bắt tông giọng tự giễu: "Chỉ cần lời chào của cô gái đẹp là vui cả ngày"
- Giữ được sự tự nhận thức của nhân vật

---

**BÀI HỌC:** Từ đồng nghĩa KHÔNG phải từ tương đương. Phải kiểm tra sắc thái trong ngữ cảnh.

**SẮC THÁI CẦN PHÂN BIỆT:**

| Tiếng Nhật | Nghĩa gốc | ❌ Dịch sai | ✅ Dịch đúng |
|------------|-----------|-------------|--------------|
| 単純 (tanjun) | Simple-minded, naive | Dễ tính | Đơn giản, đơn thuần |
| 優しい (yasashii) | Kind, gentle | Tốt bụng | Dịu dàng, hiền lành |
| 素直 (sunao) | Honest, obedient | Ngoan ngoãn | Thành thật, không vòng vo |
| 寂しい (sabishii) | Lonely | Cô đơn | Buồn vì thiếu ai đó |

**QUY TẮC KIỂM TRA:**
1. Đặt từ vào câu → Có hợp lý không?
2. Xem ngữ cảnh cảm xúc → Từ có truyền đúng cảm xúc không?
3. Kiểm tra sắc thái → Từ có mang đúng âm hưởng văn hóa không?

---

## MÔ HÌNH 10: Thiếu Kịch tính trong Lời Tuyên bố Anh hùng

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 72)

**Nguồn (JP):** 堂本隼人......参る!! (Doumoto Hayato... mairu!!)
**Dịch:** "Doumoto Hayato... **ra tay đây**!!"

**Trích đoạn Phê bình:**
> `参る` (mairu) trong ngữ cảnh này mang âm hưởng của một lời xuất trận, có chút trang trọng và cổ điển như các samurai hay anh hùng thường tuyên bố. "Ra tay đây!!" tuy đúng nghĩa nhưng hơi thông tục và làm giảm đi sự hoành tráng của khoảnh khắc nhân vật chính quyết định hành động.

**Tại Sao Thất Bại:**
- `参る` (mairu) = xuất trận, lâm trận (trang trọng, cổ điển)
- "Ra tay" = casual, thiếu trang trọng
- Mất đi sự hoành tráng của khoảnh khắc anh hùng
- Không nắm bắt được âm hưởng samurai/cổ điển

---

### ✅ BẢN SỬA TỐT ĐỀ XUẤT

**Option 1:** "Doumoto Hayato... **xuất trận đây**!!"
- Trang trọng, mang âm hưởng võ thuật/samurai
- Phù hợp khoảnh khắc quyết định can thiệp

**Option 2:** "Doumoto Hayato... **lên đây**!!"
- Ngắn gọn, mạnh mẽ
- Giữ được sự kịch tính

**Tại Sao Thành Công:**
- "Xuất trận" = trang trọng, heroic declaration
- Nắm bắt được tầm quan trọng của khoảnh khắc
- Phù hợp với bối cảnh Hayato từng thi đấu Kendo toàn quốc
- Tạo cảm giác "hero's entrance"

---

**BÀI HỌC:** Lời tuyên bố anh hùng cần TRANG TRỌNG và KỊCH TÍNH, không nên casual.

**CÁC CỤM TỪ CHO HERO'S DECLARATION:**

| Ngữ cảnh | ❌ Quá casual | ✅ Đủ kịch tính |
|----------|---------------|-----------------|
| Xuất trận chiến đấu | "Ra tay đây!" | "Xuất trận đây!", "Lên đây!" |
| Quyết tâm bảo vệ | "Tôi sẽ lo!" | "Hãy để tôi!", "Tôi sẽ bảo vệ!" |
| Thách thức địch thủ | "Đấu với tao!" | "Đối đầu với ta đi!", "Ta nhận lời!" |
| Khai chiến | "Bắt đầu nào!" | "Chiến nào!", "Giao chiến!" |

**QUY TẮC:**
- Khoảnh khắc quan trọng = Ngôn ngữ trang trọng
- Hero's entrance = Dùng từ mang âm hưởng võ thuật/cổ điển
- Climax scenes = Tránh từ ngữ quá đời thường

---

## CẬP NHẬT QUY TẮC RÚT RA TỪ 80+ BÀI PHÊ BÌNH

### Quy tắc 8: Uyển ngữ trong Cảnh Nhạy cảm (The Veil)
**Tránh:** Thuật ngữ giải phẫu trực tiếp (Category A)
**Dùng:** Uyển ngữ văn học (Category B) hoặc trừu tượng hóa (Category C)

### Quy tắc 9: Sắc thái Từ vựng
**Tránh:** Chọn từ đồng nghĩa đầu tiên trong đầu
**Dùng:** Kiểm tra sắc thái trong ngữ cảnh cụ thể

### Quy tắc 10: Lời Tuyên bố Anh hùng
**Tránh:** Ngôn ngữ casual, thông tục
**Dùng:** Ngôn ngữ trang trọng, kịch tính

---

## PHÂN TÍCH TÁC ĐỘNG ĐIỂM SỐ (CẬP NHẬT)

**Các Hình phạt Chung:**
- **Vi phạm The Veil (Category A): -5 điểm** (CRITICAL)
- Dịch sai sắc thái từ: -2 điểm
- Lời tuyên bố anh hùng thiếu kịch tính: -1 điểm
- Ngôn ngữ hành chính trong lãng mạn: -2 đến -3 điểm
- Dịch thuật ngữ văn hóa theo nghĩa đen: -1 đến -2 điểm
- Lạm dụng thể bị động: -1 đến -2 điểm

**Các Điểm thưởng Chung:**
- Sử dụng thành ngữ Việt Nam táo bạo: +3 điểm
- Uyển ngữ hoàn hảo (Category C): +2 điểm
- Động lực gia đình tự nhiên: +2 điểm
- Bất hòa hình ảnh hoàn hảo: +2 điểm

**Phạm vi Điểm số (CẬP NHẬT):**
- 70-73: **REVISE Required** - Vi phạm The Veil hoặc lỗi nghiêm trọng
- 74-76: Nhiều lỗi AI, dịch nghĩa đen
- 77-80: Tốt nhưng an toàn, lỗi nhỏ
- 81-84: Xuất sắc, tự nhiên, ít vấn đề
- 85+: Hoàn hảo (hiếm)

---

---

## MÔ HÌNH 11: Calque Cấu Trúc - Sao Chép Máy Móc Cú Pháp JP

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 81 - Structural Rhythm: B)

**Nguồn (JP):** 鼓膜を震わせたその言葉に俺は自然と額に手を当てていた
**Dịch:** "Những lời nói **làm rung màng nhĩ** khiến tôi tự nhiên đưa tay lên trán."

**Trích đoạn Phê bình (Chapter_001_critique.md - What Happens If I Save...):**
> Câu văn này là một bản sao cấu trúc (calque) của tiếng Nhật. Người Việt hiếm khi nói "làm rung màng nhĩ". Nó máy móc và thiếu tự nhiên.

**Tại Sao Thất Bại:**
- "Làm rung màng nhĩ" = dịch sát cấu trúc JP 「鼓膜を震わせた」
- Nghe giống sách giáo khoa giải phẫu, không phải tiểu thuyết
- Người Việt KHÔNG nói như vậy trong văn nói
- Đây là **calque** (structural borrowing) điển hình

---

### ✅ BẢN SỬA TỐT ĐỀ XUẤT (Tier A-Grade)

**Bản Dịch Đã Sửa:** "Những lời đó **dội vào tai**, khiến tôi bất giác đưa tay lên trán."

**Thay thế khác:**
- "Tai tôi **ù đi** vì những lời đó, và tôi vô thức đưa tay lên trán."
- "Những lời đó **như búa bổ vào tai** tôi..."

**Tại Sao Thành Công:**
- "Dội vào tai" = thành ngữ tự nhiên tiếng Việt
- "Ù đi" = cảm giác vật lý cụ thể
- Phá vỡ cấu trúc JP gốc, tái cấu trúc theo logic VN
- Giàu hình ảnh, dễ tưởng tượng

---

**BÀI HỌC:** Không dịch theo thứ tự từng mệnh đề của JP. Nắm ý chính, diễn đạt lại theo cách tự nhiên nhất trong tiếng Việt.

**Calque Phổ Biến Cần Tránh:**
- ❌ "Làm rung màng nhĩ" → ✅ "Dội vào tai", "Ù đi"
- ❌ "Đưa mắt nhìn" → ✅ "Nhìn", "Liếc"
- ❌ "Phát ra tiếng nói" → ✅ "Nói", "Lên tiếng"

---

## MÔ HÌNH 12: Robot Voice - Thiếu Tính Cách Nhân Vật

### ❌ BẢN DỊCH TỆ THỰC TẾ (Điểm: 81 - Voice Integrity: A nhưng có điểm yếu)

**Nguồn (JP):** 俺も単純である
**Dịch:** "...tôi cũng **thật đơn giản**."

**Trích đoạn Phê bình (Chapter_001_critique.md):**
> Mặc dù đúng nghĩa, cụm từ này hơi "robot" và thiếu đi cái giọng tự giễu của nhân vật. Đây là một AI-ism tiềm tàng.

**Tại Sao Thất Bại:**
- Quá an toàn, chính xác nhưng nhàm chán
- Thiếu cái "chất" tự giễu của nhân vật
- Nghe giống AI viết, không phải con người nói
- Không thể hiện personality

---

### ✅ BẢN SỬA TỐT ĐỀ XUẤT (Tier A-Grade)

**Bản Dịch Đã Sửa:** "**Mình cũng dễ dãi thật đấy.**"

**Thay thế khác:**
- "Nghĩ lại thấy **mình cũng đơn giản ghê**."
- "Tao cũng **ngây thơ thật**." (nếu nhân vật dùng tao/mày)

**Tại Sao Thành Công:**
- "Dễ dãi" = có tính cách, có màu sắc cảm xúc
- "Mình" thay vì "tôi" = gần gũi hơn khi tự sự
- Cấu trúc "...thật đấy" = tự nhiên, đời thường
- Thể hiện được giọng tự giễu, tự nhận thức

---

**BÀI HỌC:** Đừng dừng lại ở bản dịch "đúng". Hỏi: "Liệu nhân vật TÔI sáng tạo có nói thế này không?"

**AI-ism "An Toàn" Cần Nâng Cấp:**
- ❌ "Thật đơn giản" → ✅ "Dễ dãi", "Ngây thơ"
- ❌ "Tôi rất vui" → ✅ "Mình mừng quá", "Vui phát điên"
- ❌ "Điều này khiến tôi ngạc nhiên" → ✅ "Giật mình luôn", "Choáng váng"

---

## MÔ HÌNH 13: Ceremonial Underkill - Lời Tuyên Bố Anh Hùng Thiếu Trang Trọng

### ✅ BẢN DỊCH TỐT THỰC TẾ (Điểm: 81 - Boldness: A)

**Nguồn (JP):** 参る!! (Mairu!!)
**Dịch:** "**Xin ra trận!!**"

**Trích đoạn Phê bình (Chapter_001_critique.md):**
> "Mairu" là một từ cổ, mang sắc thái trang trọng và kịch tính, thường thấy trong các tác phẩm về samurai hoặc kịch. Dịch đơn giản là "Xông lên!" sẽ làm mất đi sự màu mè này. "Xin ra trận!!" là một lựa chọn tuyệt vời, nó vừa thể hiện sự quyết tâm, vừa phảng phất nét "trẻ trâu" có chủ đích của một cậu học sinh đang tự biến mình thành anh hùng.

**Tại Sao Thành Công:**
- "Xin ra trận" = ngôn ngữ **ceremonial**, không phải đời thường
- Nắm bắt được tính kịch tính của 「参る」(mairu - từ cổ)
- Thể hiện nhân vật đang "diễn" vai anh hùng (meta-awareness)
- Có chất "trẻ trâu" vừa nghiêm túc vừa hài hước

---

### ❌ PHIÊN BẢN TỆ (Underkill)

**Dịch Tệ:** "**Xông lên!!**"

**Tại Sao Thất Bại:**
- Quá casual, mất đi tính trang trọng
- Không thể hiện được sự "staged" (dàn dựng) của khoảnh khắc
- Không phù hợp với sắc thái 「参る」

---

**BÀI HỌC:** Khi JP dùng ngôn ngữ cổ/trang trọng, VN cũng phải có độ ceremonial tương đương. Đừng "dân dã hóa" quá mức.

**Ceremonial Phrases Cần Giữ:**
- ✅ "Xin ra trận!!" (参る)
- ✅ "Xin phép!" (formal request)
- ✅ "Tham kiến!" (古語 - archaic greeting)
- ❌ Đừng dùng: "Đi thôi!", "Xông lên!" cho 参る

---

<a name="idiom-translation-icl"></a>
# 3. IDIOM TRANSLATION ICL (In-Context Learning)

**Version:** 1.0  
**Date:** 2026-01-18  
**Purpose:** Teach natural Vietnamese idiom usage through principle-based examples  
**Architecture:** ICL (In-Context Learning) - teaches patterns, not memorization

---

## CORE PRINCIPLE

**🎯 PRIMARY RULE:** Use natural Vietnamese idioms that match the **intent and register**, NOT literal translations.

**Translation Flow:**
1. Identify Japanese idiom type (numeric probability, certainty, proverb, etc.)
2. Understand the **emotional intent** and **register** (formal/casual)
3. Select Vietnamese equivalent that sounds **natural to native speakers**
4. Avoid literal word-for-word translations (major source of translationese)

---

## IDIOM CATEGORY 1: Numeric Probability Expressions

### Example 1: 十中八九 (Jūchū hakku)

**Literal Meaning:** "8 or 9 out of 10"  
**Intent:** High probability (~80-90%)

**❌ WRONG (Literal):** "tám chín phần mười" (awkward, no one says this)  
**✅ RIGHT (Natural):** "chín phần mười" (natural Vietnamese idiom)

**Reasoning:** Vietnamese has its own probability idiom "chín phần mười" (9/10) that native speakers actually use. Don't invent unnatural phrases by literally translating Japanese structure.

---

### Example 2: 八割方 (Hachi wari kata)

**Literal Meaning:** "About 80%"  
**Intent:** Rough probability estimate

**❌ WRONG (Literal):** "khoảng tám phần mười" (technically correct but stiff)  
**✅ RIGHT (Natural):** "tám phần mười" OR "gần chắc chắn" (contextual)

**Reasoning:** Drop unnecessary "khoảng" for brevity. If context emphasizes certainty over precision, "gần chắc chắn" flows better.

---

### Example 3: 完全に (Kanzen ni) - Certainty Expression

**Literal Meaning:** "Completely"  
**Intent:** Total certainty/comprehension

**❌ WRONG (Colloquial Idiom):** "mười mươi" (10/10 - too casual for formal contexts)  
**✅ RIGHT (Formal):** "hoàn toàn" OR "chắc chắn mười phần mười"

**Context from CH2 Audit:**
> **JP:** "八割方確定しており、その後のやり取りで**完全に**把握した"  
> **VN (Current - Wrong):** "đã xác định được tám phần mười, sau cuộc trao đổi thì nắm rõ **mười mươi**."  
> **VN (Correct):** "đã xác định được tám phần mười, sau cuộc trao đổi thì nắm rõ **hoàn toàn**."

**Reasoning:** "Mười mươi" is a casual colloquial expression (like "ten outta ten") that clashes with Aina's analytical, formal internal monologue register. "Hoàn toàn" maintains formality while conveying total certainty.

**Register Sensitivity:**
- Casual context: "mười mươi" ✅
- Formal context: "hoàn toàn" ✅
- Analytical/intellectual context: "hoàn toàn" ✅

---

### Example 4: 十分 (Jūbun) - Sufficiency

**Literal Meaning:** "Ten parts" → "Sufficient"  
**Intent:** Adequate, enough

**❌ WRONG (Literal):** "mười phần" (nonsensical without context)  
**✅ RIGHT (Natural):** "đầy đủ" OR "đủ rồi" (casual) OR "vừa đủ"

**Context Example:**
> **JP:** "この説明で**十分**だろう"  
> **VN:** "Giải thích này là **đủ rồi**"

---

## IDIOM CATEGORY 2: Proverbs & Sayings

### Example 5: 百聞は一見に如かず (Hyaku bun wa ikken ni shikazu)

**Literal Meaning:** "100 hearings are not equal to 1 seeing"  
**Intent:** Direct experience beats second-hand information

**❌ WRONG (Literal):** "trăm lần nghe không bằng một lần thấy" (exists but overly literal)  
**✅ RIGHT (Idiomatic):** "trăm nghe không bằng một thấy" (natural Vietnamese version)

**Reasoning:** Vietnamese has its own compact version. Use it instead of word-for-word translation.

---

### Example 6: 案ずるより産むが易し (Anzuru yori umu ga yasushi)

**Literal Meaning:** "Giving birth is easier than worrying about it"  
**Intent:** Action is easier than overthinking

**❌ WRONG (Literal):** "sinh con dễ hơn lo lắng" (loses metaphorical punch)  
**✅ RIGHT (Equivalent):** "nghĩ nhiều không bằng làm" OR "làm còn dễ hơn nghĩ"

**Reasoning:** Vietnamese doesn't have a birth metaphor for this concept. Use an equivalent idiom that conveys the same wisdom.

---

### Example 7: 一石二鳥 (Isseki nichō)

**Literal Meaning:** "One stone, two birds"  
**Intent:** Kill two birds with one stone

**❌ WRONG (Calque):** "một hòn đá hai con chim" (awkward phrasing)  
**✅ RIGHT (Natural):** "một mũi tên trúng hai đích" (Vietnamese equivalent)

**Reasoning:** Vietnamese has its own archery-based idiom for the same concept. Prefer native expressions.

---

## IDIOM CATEGORY 3: Intensity & Emphasis

### Example 8: 死ぬほど (Shinu hodo)

**Literal Meaning:** "To the extent of dying"  
**Intent:** Extreme degree

**❌ WRONG (Literal):** "đến mức chết" (too morbid/dramatic for casual contexts)  
**✅ RIGHT (Natural):** "chết đi được" OR "vô cùng" OR "cực kỳ" (context-dependent)

**Context Sensitivity:**
- Hyperbolic teen speech: "chết đi được" ✅ ("I'm dying of boredom")
- Formal description: "vô cùng" ✅ ("extremely tired")
- Intense emotion: "như chết đi sống lại" ✅ (drama scenes)

---

### Example 9: 目から鱗が落ちる (Me kara uroko ga ochiru)

**Literal Meaning:** "Scales fall from eyes"  
**Intent:** Sudden realization/enlightenment

**❌ WRONG (Literal):** "vảy rơi khỏi mắt" (nonsensical in Vietnamese)  
**✅ RIGHT (Equivalent):** "như được khai sáng" OR "sáng mắt ra"

**Reasoning:** Biblical idiom doesn't translate. Use Vietnamese expressions for enlightenment moments.

---

### Example 10: 猫の手も借りたい (Neko no te mo karitai)

**Literal Meaning:** "Want to borrow even a cat's paws"  
**Intent:** Desperately need help (overwhelmed)

**❌ WRONG (Literal):** "muốn mượn cả tay mèo" (confusing image in Vietnamese)  
**✅ RIGHT (Natural):** "bận rộn không có thời gian thở" OR "thiếu người đến mức..."

**Reasoning:** Cat metaphor doesn't work in Vietnamese culture. Express the desperation directly.

---

## IDIOM CATEGORY 4: Emotional States

### Example 11: 胸が痛む (Mune ga itamu)

**Literal Meaning:** "Chest hurts"  
**Intent:** Emotional pain, sympathy

**❌ WRONG (Literal):** "ngực đau" (sounds like medical issue)  
**✅ RIGHT (Emotional):** "xót xa" OR "đau lòng" OR "tim như siết lại"

**Reasoning:** Vietnamese requires explicit emotional framing, not body part metaphors.

---

### Example 12: 頭が真っ白になる (Atama ga masshiro ni naru)

**Literal Meaning:** "Head becomes pure white"  
**Intent:** Mind goes blank (shock/panic)

**❌ WRONG (Literal):** "đầu trở nên trắng bóc" (bizarre image)  
**✅ RIGHT (Natural):** "đầu óc trống rỗng" OR "não như tê liệt" OR "mất hết suy nghĩ"

---

### Example 13: 耳が痛い (Mimi ga itai)

**Literal Meaning:** "Ears hurt"  
**Intent:** Uncomfortable truth hits home

**❌ WRONG (Literal):** "tai đau" (sounds like infection)  
**✅ RIGHT (Natural):** "nghe mà đau" OR "đúng như đâm vào tim"

---

## IDIOM CATEGORY 5: Time & Urgency

### Example 14: 目と鼻の先 (Me to hana no saki)

**Literal Meaning:** "Tip of eyes and nose"  
**Intent:** Very close by

**❌ WRONG (Literal):** "đầu mắt đầu mũi" (not an idiom)  
**✅ RIGHT (Natural):** "gần trong gang tấc" OR "rất gần"

---

### Example 15: 間一髪 (Kan ippatsu)

**Literal Meaning:** "One hair's breadth"  
**Intent:** Close call, narrow escape

**❌ WRONG (Literal):** "khoảng cách một sợi tóc" (loses urgency)  
**✅ RIGHT (Natural):** "sát nút" OR "suýt nữa" OR "trong gang tấc"

---

## APPLICATION GUIDELINES

### ⚠️ ANTI-PATTERNS (Avoid These)

1. **Literal Number Translation:**
   - ❌ "tám chín phần mười" for 十中八九
   - ❌ "một trăm nghe một thấy" for 百聞は一見に如かず

2. **Cultural Calquing:**
   - ❌ Translating animal metaphors literally (cat's paws, scales from eyes)
   - ❌ Body part metaphors that don't work in Vietnamese

3. **Register Mismatch:**
   - ❌ Using "mười mươi" (casual) in formal analytical contexts
   - ❌ Using "hoàn toàn" (formal) in casual teen banter

### ✅ BEST PRACTICES

1. **Check Vietnamese Idiom Database First:**
   - Does Vietnamese have a native equivalent? Use it.
   - Example: "một mũi tên trúng hai đích" exists for 一石二鳥

2. **Register Awareness:**
   - Match formality level: Casual teen speech ≠ Business email ≠ Literary description
   - Characters' education/background affects idiom choice

3. **Intent Over Structure:**
   - Translate the **meaning and feeling**, not the metaphor structure
   - "Chest hurts" → "đau lòng" (emotional), not "ngực đau" (physical)

4. **Test for Naturalness:**
   - Would a native Vietnamese speaker say this?
   - Does it sound like translationese or authentic speech?

---

## QUALITY ASSURANCE CHECKLIST

Before finalizing idiom translation:

- [ ] Checked if Vietnamese has native equivalent
- [ ] Verified register matches context (formal/casual)
- [ ] Avoided literal translation of metaphor structure
- [ ] Confirmed idiom sounds natural to native speakers
- [ ] Tested for translationese (stiff, unnatural phrasing)
- [ ] Considered character background (would THEY use this idiom?)

---

**INTEGRATION NOTE:**  
This section replaces hard-coded IDIOM_MAPPING rules with principle-based learning. Models trained on these examples should generalize to new idioms by understanding the **translation strategy**, not memorizing explicit mappings.

**For LOAD_SPECIALTY Integration:**  
When Japanese idioms detected, load this section for ICL-based guidance. Prioritize **natural Vietnamese expression over literal accuracy**.

---

<a name="4-school-life-excellence"></a>
# 4. SCHOOL_LIFE Translation Excellence Examples

**Source:** Kuranika V1 Production Audit (Early Chapters, Pre-Failure)  
**Purpose:** Demonstrate translation principles that achieved 92/100 in Man-Hating Sisters, 70-75/100 in early Kuranika chapters  
**Context:** These examples come from chapters translated using v1.5.2.2 (stable architecture, before SYSTEM_OVERRIDE)  
**Note:** All examples rated EXCELLENT (⭐⭐⭐⭐⭐) by independent audit

---

## MẪU 030: Emotional Nuance (Struggle vs Simple Dislike)

### GỐC
俺は春が苦手だ。

### DỊCH
Tôi vốn không giỏi đối phó với mùa xuân.

### LẬP LUẬN (Analysis)
**Why this works:**
- **Avoided Literal Translation:** "苦手" (nigate) ≠ simple "don't like" (không thích)
- **Nuanced Verb Choice:** "không giỏi đối phó với" (not good at dealing with) captures the **struggle** aspect
- **Natural Vietnamese Structure:** "vốn" (originally/inherently) adds introspective weight
- **Sets Narrative Tone:** Opens the story with measured, contemplative voice (Tenuto rhythm)

**Translation Principle:**  
For psychological/emotional states, prioritize **connotation over denotation**. "苦手" implies difficulty/struggle, not just preference.

**Grade:** EXCELLENT ⭐⭐⭐⭐⭐

---

## MẪU 031: Teacher Dialogue (Question Particles & Register)

### GỐC
『前原君は松原中……ってどこ？　ここらへんの学区じゃないよね？』

### DỊCH
『Em Maehara học trường Matsubara... là ở đâu nhỉ? Không phải học khu quanh đây đúng không?』

### LẬP LUẬN (Analysis)
**Why this works:**
- **Teacher Pronoun:** "Cô-Em" relationship (teacher → student) using "Em" appropriately
- **Question Particles:**
  - "nhỉ" = Japanese "ね" (soft questioning, musing)
  - "đúng không" = Japanese "よね" (seeking confirmation)
- **Informal Tone Preserved:** Teacher's casual curiosity maintained (not overly formal)
- **School Terminology:** "học khu" (school district) precise and natural

**Translation Principle:**  
Vietnamese question particles carry emotional nuance. Match Japanese particles to Vietnamese equivalents that preserve speaker attitude.

**Grade:** EXCELLENT ⭐⭐⭐⭐⭐

---

## MẪU 032: Psychological Complexity (Long Introspection)

### GỐC
だが、一度こじらせてしまった性根を矯正することも、そうしようとする勇気もだんだん薄れていて。

### DỊCH
Nhưng cái bản tính đã lún quá sâu vào sự đơn độc ấy, cả việc sửa đổi nó lẫn lòng dũng cảm để cố gắng làm điều đó đều đang dần phai nhạt.

### LẬP LUẬN (Analysis)
**Why this works:**
- **Vivid Metaphor:** "lún quá sâu" (sunk too deep) ≠ literal "こじらせた" (tangled/complicated)
- **Grammatical Restructuring:** Japanese structure broken and rebuilt for Vietnamese flow
- **Emotional Weight Maintained:** Despair and resignation conveyed through verb choices
- **Parallel Structure:** "cả... lẫn..." (both... and...) mirrors Japanese "も...も" gracefully

**Translation Principle:**  
Complex psychological sentences require **structural adaptation**. Don't force Vietnamese grammar to match Japanese syntax. Break, rethink, rebuild.

**Grade:** EXCELLENT ⭐⭐⭐⭐⭐

---

## MẪU 033: Character Voice (Interjections & Complaints)

### GỐC
「ちょっ、海ってばひどくない？　それじゃあ私、まるで捨て犬みたいじゃん」

### DỊCH
"Kìa, Umi nói thế quá đáng không chứ? Làm như mình là con chó bị bỏ rơi không bằng."

### LẬP LUẬN (Analysis)
**Why this works:**
- **Perfect Interjection:** "Kìa" captures "ちょっ" (protest/objection) naturally
- **Complaint Structure:** "quá đáng không chứ?" = natural Vietnamese rhetorical question
- **Humor Preserved:** "con chó bị bỏ rơi" (abandoned dog) maintains comedic tone
- **Character Personality:** Amami's bright, slightly dramatic voice comes through

**Translation Principle:**  
Character voice emerges from **small words** (interjections, particles, question structures). These carry more personality than content words.

**Grade:** EXCELLENT ⭐⭐⭐⭐⭐

---

## MẪU 034: Atmospheric Description (Sensory Language)

### GỐC
俺は春が苦手だ。もちろん、気候のことを言っているのではない。暖かな日差しと穏やかに頬を撫でるそよ風...

### DỊCH
Tôi vốn không giỏi đối phó với mùa xuân. Dĩ nhiên, tôi không hề nói về vấn đề khí hậu. Những tia nắng ấm áp, làn gió nhẹ nhàng mơn trớn đôi gò má...

### LẬP LUẬN (Analysis)
**Why this works:**
- **Sensory Verb:** "mơn trớn" (caressing) ≠ literal "撫でる" (stroke)—more poetic, vivid
- **Natural Collocations:** "tia nắng ấm áp" (warm sunlight), "làn gió nhẹ nhàng" (gentle breeze)
- **Proper Idiom Use:** "Dĩ nhiên" (of course) used **once**, naturally placed (cf. pathological repetition in corrupted chapters)
- **Contemplative Mood:** Maintains introspective tone through measured pacing

**Translation Principle:**  
Atmospheric prose requires **sensory verbs** and **natural collocations**. Vietnamese has rich sensory vocabulary—use it to enhance immersion.

**CONTRAST NOTE:**  
This same passage in later chapters (post-SYSTEM_OVERRIDE) inserted "dĩ nhiên" 5-10 times per sentence, destroying naturalness. This demonstrates the importance of cognitive quality control.

**Grade:** EXCELLENT ⭐⭐⭐⭐⭐

---

## KEY LESSONS FROM SCHOOL_LIFE EXAMPLES

### What Made These Translations Excellent:

1. **Cognitive Agency Preserved**  
   - Translator had freedom to rethink structure ("lún quá sâu" for "こじらせた")
   - Reflective reasoning enabled nuanced choices ("struggle" vs "dislike")
   - Quality checkpoints active (natural Vietnamese verified before moving on)

2. **Character Voice Prioritized**  
   - Small words carry personality ("Kìa", "nhỉ", "đúng không")
   - Register awareness (teacher's casual tone, student introspection)
   - Emotional authenticity over literal accuracy

3. **Vietnamese Naturalness First**  
   - Grammatical restructuring when needed (MẪU 032)
   - Natural collocations ("tia nắng ấm áp", "làn gió nhẹ nhàng")
   - Sensory vocabulary prioritized ("mơn trớn" over literal "rub")

4. **Contextual Idiom Use**  
   - "Dĩ nhiên" used once, naturally (vs pathological 10x repetition in corrupted version)
   - Proves cognitive quality control prevents mechanical insertion

### Integration with v1.5.2.5:

These examples validate current architecture:
- ICL idiom learning (not hard-coded rules) ✅
- Native quality control mechanisms active ✅
- Cognitive agency preserved (reflective reasoning) ✅
- Character voice differentiation maintained ✅

**Use these examples as benchmarks:** If output quality matches these samples, architecture is functioning correctly.

---

## CHECKLIST TRƯỚC KHI DỊCH (CẬP NHẬT v2.0)

**Khi dịch:**
1. ✅ Kiểm tra ngôn ngữ hành chính → Thay bằng đời thường
2. ✅ Kiểm tra thuật ngữ văn hóa nghĩa đen → Dịch cái không khí (vibe)
3. ✅ Kiểm tra thể bị động → Chuyển sang chủ động
4. ✅ Kiểm tra vị trí trợ từ → Khớp với cảm xúc truyền tải
5. ✅ Kiểm tra lời mắng yêu → Giữ ngắn và gọn
6. ✅ Kiểm tra bất hòa hình ảnh → Nhấn mạnh tương phản
7. ✅ Kiểm tra động lực gia đình → Giữ ấm áp và tinh nghịch
8. **✅ Kiểm tra cảnh bạo lực vs thân mật → Context-dependent language (Pattern 8)**
9. **✅ Kiểm tra sắc thái từ → Đúng ngữ cảnh cảm xúc**
10. **✅ Kiểm tra lời tuyên bố quan trọng → Đủ kịch tính, trang trọng**
11. **✅ Kiểm tra calque cấu trúc → Phá vỡ và tái cấu trúc theo VN (Pattern 11)**
12. **✅ Kiểm tra robot voice → Thêm tính cách nhân vật (Pattern 12)**
13. **✅ Kiểm tra ceremonial language → Giữ độ trang trọng (Pattern 13)**

**Mục tiêu của bạn:** Đạt 81+ điểm một cách nhất quán bằng cách tránh tất cả 13 mô hình lỗi này.

---

**END OF Library_REFERENCE_ICL_SAMPLES.md**

**INTEGRATION NOTES:**
- Golden Samples: S-tier translation examples
- Real-World Critiques: Error analysis and correction patterns
- Total size: ~59 KB
- Ready for in-context learning (ICL) applications
