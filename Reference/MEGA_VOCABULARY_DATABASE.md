# MEGA VOCABULARY DATABASE

**Version:** 2.0  
**Date:** 2026-01-06  
**Purpose:** Unified vocabulary reference for JP-VN Light Novel translation  
**Consolidation:** Merged 6 files into single authoritative source

---

## Table of Contents

1. [Vietnamese Pronoun System](#1-vietnamese-pronoun-system)
2. [Visual Proxemics Quick Reference](#2-visual-proxemics-quick-reference)
3. [Genre-Specific Vocabulary Mapping](#3-genre-specific-vocabulary-mapping)
4. [Vietnamese Expression Mapping](#4-vietnamese-expression-mapping)
5. [Sensory Lexicon](#5-sensory-lexicon)
6. [Long Vowel Romanization](#6-long-vowel-romanization)

---

<a name="1-vietnamese-pronoun-system"></a>
# 1. Vietnamese Pronoun System


# HỆ THỐNG ĐẠI TỪ TIẾNG VIỆT v9.1 (VIETNAMESE PRONOUN SYSTEM)
**Vai Trò:** Hướng Dẫn Chọn Đại Từ cho Dịch Thuật Tiếng Việt
**Phạm Vi:** Hệ thống đại từ lai Nhật/Việt dựa trên động lực mối quan hệ
**Triết Lý:** Giữ kính ngữ Nhật cho sự trang trọng, chuyển sang đại từ Việt cho sự thân mật

---

## 🆕 PHẦN 0: ĐẠI TỪ NGÔI THỨ NHẤT CHO MC/NGƯỜI KỂ CHUYỆN (ICL)

### 0.1 NGUYÊN TẮC CƠ BẢN

**Mặc định:** Sử dụng **"tôi"** cho tất cả nhân vật MC/Narrator cho đến khi archetype được xác định.

```
MẶC ĐỊNH: "tôi" (trung tính, phổ quát)
         ↓ (sau khi archetype được định hình)
CHUYỂN: "mình" (thân mật, nội tâm, đặc biệt cho nữ POV)
```

### 0.2 QUY TẮC CHỌN ĐẠI TỪ NGÔI THỨ NHẤT

| Tình huống | Đại từ | Lý do |
|------------|--------|-------|
| **Chương 1-2 (chưa biết archetype)** | "tôi" | Trung tính, an toàn |
| **MC Nam - chuẩn mực** | "tôi" | Formal, trưởng thành |
| **MC Nam - casual/otaku** | "mình" hoặc "tớ" | Tùy độ casual |
| **MC Nữ - sau khi định hình** | "mình" | Mềm mại, nội tâm |
| **MC Nữ - tsundere/mạnh mẽ** | "tôi" | Defensive, cold |
| **POV thay đổi (chương nữ chính)** | "mình" | Nữ tính, soft |

### 0.3 ICL EXAMPLES

**[ICL_PRONOUN_01] MẶC ĐỊNH: Dùng "tôi"**
```
INPUT: 僕は教室に向かって歩いていた。
OUTPUT_ĐÚNG: "Tôi đang đi về phía lớp học."
OUTPUT_SAI: "Mình đang đi về phía lớp học."
LÝ DO: Chương đầu, chưa biết archetype → MẶC ĐỊNH "tôi"
```

**[ICL_PRONOUN_02] NHẤT QUÁN TRONG CHƯƠNG**
```
ĐOẠN 1: "Tôi cảm thấy buồn ngủ."
ĐOẠN 2: "Tôi nhìn cô ấy từ xa."
ĐOẠN 3: "Điều đó khiến tôi ngạc nhiên."

❌ SAI:
ĐOẠN 1: "Tôi cảm thấy buồn ngủ."
ĐOẠN 2: "Mình nhìn cô ấy từ xa." ← KHÔNG NHẤT QUÁN!
ĐOẠN 3: "Điều đó khiến tôi ngạc nhiên."

NGUYÊN TẮC: Một khi đã chọn "tôi" hoặc "mình", LOCK xuyên suốt chương.
```

**[ICL_PRONOUN_03] NỮ POV - Chuyển sang "mình"**
```
CONTEXT: Chương kể từ góc nhìn nữ chính (sau khi đã giới thiệu)

INPUT: 私は彼のことが気になっていた。
OUTPUT_ĐÚNG: "Mình đã để ý đến anh ấy."
OUTPUT_CHẤP_NHẬN: "Tôi đã để ý đến anh ấy." (cũng OK nếu đã lock "tôi")

LÝ DO: Nữ POV + đã định hình archetype → "mình" tự nhiên hơn
```

**[ICL_PRONOUN_04] TSUNDERE NỮ - Giữ "tôi"**
```
CONTEXT: Nhân vật nữ tsundere/cold/defensive

INPUT: 「私は別にあなたのことなんか…！」
OUTPUT_ĐÚNG: "Tôi đâu có quan tâm đến anh hay gì đâu...!"
OUTPUT_SAI: "Mình đâu có quan tâm đến anh hay gì đâu...!"

LÝ DO: Tsundere dùng "tôi" để tạo khoảng cách/defensive
```

**[ICL_PRONOUN_05] NAM MC CASUAL/OTAKU**
```
CONTEXT: MC nam là otaku, casual, không formal

INPUT: 俺は疲れた。ゲームやりすぎたわ。
OUTPUT_ĐÚNG: "Mình mệt quá. Chơi game nhiều quá rồi."
OUTPUT_CŨNG_OK: "Tớ mệt quá. Chơi game nhiều quá rồi."

LÝ DO: Casual archetype → "mình" hoặc "tớ" tự nhiên hơn "tôi"
```

### 0.4 QUYẾT ĐỊNH LOCK ĐẠI TỪ

```
CHO MỖI TÁC PHẨM:
1. Xác định archetype MC từ đoạn đầu tiên
2. LOCK đại từ ngôi thứ nhất:
   - Default: "tôi"
   - Nữ POV soft: "mình"  
   - Nam casual: "mình" hoặc "tớ"
   - Tsundere/defensive: "tôi"
3. GIỮ NHẤT QUÁN xuyên suốt tác phẩm
4. CHỈ THAY ĐỔI khi POV chuyển nhân vật khác
```

### 0.5 MULTI-POV (Nhiều góc nhìn)

```
VÍ DỤ: Truyện có cả nam chính và nữ chính kể chuyện

CHƯƠNG 1 (Nam MC - Touya):
→ LOCK: "tôi" (default, formal)
"Tôi bước vào cửa hàng tiện lợi."

CHƯƠNG 2 (Nữ chính - Watanuki):
→ LOCK: "mình" (nữ POV, đã định hình)
"Mình không ngờ lại gặp cậu ấy ở đây."

CHƯƠNG 3 (Quay lại Nam MC):
→ DÙNG LẠI: "tôi" (nhất quán với Chương 1)
```

### 0.6 CHECKLIST ĐẠI TỪ NGÔI THỨ NHẤT

- [ ] Xác định POV của chương (nam/nữ)
- [ ] Xác định archetype (formal/casual/tsundere/soft)
- [ ] LOCK đại từ ngôi thứ nhất phù hợp
- [ ] Kiểm tra NHẤT QUÁN xuyên suốt chương
- [ ] Không trộn lẫn "tôi" và "mình" trong cùng POV

---

## 🚨 PHẦN 0.7: ICL QUAN HỆ GIA ĐÌNH (CRITICAL!)

### **NGUYÊN TẮC BẤT BIẾN:**
Quan hệ gia đình **LUÔN ƯU TIÊN CAO NHẤT**, không bao giờ dùng "tao/mày" cho anh chị em!

### **[ICL_FAMILY_01] CHỊ GÁI → EM TRAI**
```
CONTEXT: Mei (chị, 17 tuổi) nói với Touya (em, 16 tuổi)
QUAN HỆ: Chị gái → Em trai (Onee-san → Otouto)

INPUT: 「ねぇ冬也ぁ、アイス買ってきてぇ」

OUTPUT_SAI (tao/mày):
"Nè Touya, mua kem về cho tao đi"
→ SAI! "tao/mày" chỉ dùng cho bạn bè, KHÔNG dùng cho gia đình!

OUTPUT_ĐÚNG (chị/em):
"Nè em ơi, mua kem về cho chị đi"
hoặc "Touya ơi, mua kem về cho chị đi"

LOGIC: Dù Mei có nhõng nhẽo/casual thế nào, chị gái PHẢI dùng "chị/em"
```

### **[ICL_FAMILY_02] EM TRAI → CHỊ GÁI**
```
CONTEXT: Touya (em) nói với Mei (chị)
QUAN HỆ: Em trai → Chị gái (Otouto → Onee-san)

INPUT: 「やだよ。この時間に心臓バクバクしたくないんだけど」

OUTPUT_SAI (tao/mày):
"Hả, không đời nào. Giờ này mà tao không muốn tim đập nhanh đâu"
→ SAI! Em trai KHÔNG nói "tao" với chị gái!

OUTPUT_ĐÚNG (em/chị):
"Hả, không đời nào. Giờ này mà em không muốn tim đập nhanh đâu"
"Với lại chị nghĩ giờ là mấy giờ rồi?"

LOGIC: Em trai PHẢI dùng "em" khi nói với chị, xưng "chị" cho chị gái
```

### **[ICL_FAMILY_03] NARRATOR ĐỀ CẬP CHỊ GÁI**
```
CONTEXT: Touya (người kể chuyện) đề cập đến Mei

INPUT: 芽衣は本当に俺より一つ年上なのか...姉なのか?

OUTPUT_SAI:
"Mei thật sự sinh trước tôi một năm sao... là chị gái hơn tôi một tuổi sao?"
→ SAI! Không dùng "Mei" trống không, phải có "chị"

OUTPUT_ĐÚNG:
"Chị Mei thật sự sinh trước em/tôi một năm sao... là chị gái em/tôi thật sao?"
hoặc "Chị ấy thật sự sinh trước mình một năm sao..."

LOGIC: Khi đề cập chị gái trong tường thuật, PHẢI có prefix "Chị"
```

### **[ICL_FAMILY_04] CHỊ GÁI NHÕNG NHẼO VẪN DÙNG CHỊ/EM**
```
CONTEXT: Mei nhõng nhẽo, làm nũng - VẪN LÀ CHỊ GÁI!

INPUT: 「えー、むりむりー。お姉ちゃん幼稚園のときから成長してないんだもん」

OUTPUT_SAI:
"Ehh, không không chịu được, tao từ hồi mẫu giáo đến giờ vẫn không lớn mà"
→ SAI! Dù nhõng nhẽo, Mei vẫn là chị gái!

OUTPUT_ĐÚNG:
"Ehh, không không chịu được đâu, chị đây từ hồi mẫu giáo đến giờ có lớn thêm tí nào đâu"
"Nếu không làm nũng với đứa em trai trưởng thành thì chị không sống nổi đâu."

LOGIC: Tính cách KHÔNG thay đổi quan hệ gia đình! Nhõng nhẽo ≠ bạn bè
```

### **BẢNG THAM CHIẾU NHANH - GIA ĐÌNH**

| Quan hệ | Người nói | Tự xưng | Gọi đối phương |
|---------|-----------|---------|----------------|
| Chị → Em | Mei | "chị" | "em" / tên |
| Em → Chị | Touya | "em" | "chị" / "chị Mei" |
| Anh → Em | - | "anh" | "em" / tên |
| Em → Anh | - | "em" | "anh" / "anh [Tên]" |

### **🔴 CẤM KỴ:**
- ❌ KHÔNG BAO GIỜ dùng "tao/mày" cho anh chị em ruột
- ❌ KHÔNG BAO GIỜ dùng "tớ/cậu" cho anh chị em ruột  
- ❌ KHÔNG BAO GIỜ bỏ prefix "Chị/Anh" khi đề cập tên
- ❌ Tính cách nhõng nhẽo/casual KHÔNG thay đổi quy tắc gia đình

### **[ICL_FAMILY_05] CẤM TỚ/CẬU CHO CHỊ EM** ⚠️
```
CONTEXT: Mei (chị gái) nói với Touya (em trai)
INPUT: 「最近はダイエットまぁじ頑張ってるから...」

OUTPUT_SAI (tớ/cậu):
"Dạo này tớ cố gắng giảm cân dữ lắm đó, lâu lâu cũng muốn được tự thưởng cho mình chứ!"
"tớ cho cậu ăn một ngụm kem..."
→ SAI! "tớ/cậu" là đại từ dùng cho BẠN BÈ, KHÔNG PHẢI gia đình!

OUTPUT_ĐÚNG (chị/em):
"Dạo này chị cố gắng giảm cân dữ lắm đó, lâu lâu cũng muốn được tự thưởng cho mình chứ!"
"Chị cho em ăn một ngụm kem..."

PHÂN BIỆT:
- tớ/cậu = Bạn bè thân (同級生, 友達)
- chị/em = Chị em ruột (姉弟, 兄妹)
- tao/mày = Bạn bè rất thân hoặc cãi nhau
- Mei + Touya = CHỊ EM RUỘT → PHẢI dùng chị/em!
```

### **[ICL_FAMILY_06] NHẬN DIỆN QUAN HỆ GIA ĐÌNH** 🔍
```
CÁC TỪ KHÓA XÁC ĐỊNH QUAN HỆ CHỊ EM TRONG RAW:
- 姉 (ane) = chị gái
- 弟 (otouto) = em trai  
- お姉ちゃん (onee-chan) = chị (gọi thân mật)
- 年上 (toshiue) = người lớn tuổi hơn
- 一つ年上 (hitotsu toshiue) = hơn một tuổi

KỊCH BẢN:
Nếu văn bản có: "芽衣は...姉なんだよな" (Mei... là chị gái nhỉ)
→ XÁC ĐỊNH: Mei = CHỊ GÁI
→ KHÓA: Mei dùng "chị", Touya dùng "em"
→ KHÔNG BAO GIỜ dùng tớ/cậu/tao/mày cho dialogue 2 người này!
```

---

## 🆕 HỆ THỐNG MÃ CẶP ĐẠI TỪ (PRONOUN PAIR ID SYSTEM)

**Mục Đích:** Loại bỏ sự đoán mò. Khi RTAS đã được tính, PAIR_ID được xác định. Gemini chọn cặp đúng một cách máy móc.

**Bảng Tham Chiếu Chính:**

### CẤP ĐỘ GIA ĐÌNH (Cố Định, Không Phụ Thuộc RTAS)

| PAIR_ID | Loại Cặp | Đại Từ | RTAS | Ngữ Cảnh | Ví Dụ |
|---|---|---|---|---|---|
| **PAIR_FAM_1** | Anh Chị Lớn | Anh/Chị (họ) + Em (mình) | N/A (Cố định) | Em → Anh/Chị | "Anh ơi, anh làm gì thế?" |
| **PAIR_FAM_2** | Em Nhỏ | Em (họ) + Anh/Chị (mình) | N/A (Cố định) | Anh/Chị → Em | "Em đang học chưa?" |
| **PAIR_FAM_3** | Cha Mẹ (Trẻ em) | Ba/Mẹ (họ) + Con (mình) | N/A (Cố định) | Con → Cha Mẹ | "Con xin lỗi ba ạ" |
| **PAIR_FAM_4** | Cha Mẹ (Người lớn) | Con (họ) + Ba/Mẹ (mình) | N/A (Cố định) | Cha Mẹ → Con lớn | "Con thế nào rồi?" |

**Quy Tắc:** Các cặp gia đình **LUÔN ĐƯỢC DÙNG** bất kể các yếu tố khác. Kiểm tra quan hệ gia đình TRƯỚC TIÊN.

---

### CẤP ĐỘ LÃNG MẠN/THÂN MẬT (Phụ Thuộc RTAS)

| PAIR_ID | Loại Cặp | Đại Từ | Phạm Vi RTAS | Giai Đoạn Quan Hệ | Ví Dụ |
|---|---|---|---|---|---|
| **PAIR_1** | Bạn Bè Xã Giao | Tớ (mình) + Cậu (họ) | 2.0–3.5 | Bạn bè, cặp đôi mới, lảng tránh | "Cậu yên tâm đi." |
| **PAIR_2** | Thân Mật Chuyển Tiếp | Tớ (mình) + Anh (họ) | 3.5–4.2 | Tổn thương nhẹ, phụ thuộc | "Anh, tớ sợ lắm." |
| **PAIR_3** | Thân Mật Đỉnh Điểm | Em (mình) + Anh (họ) | 4.2–5.0 | Tổn thương tối đa, chăm sóc, yêu | "Em ở đây, đừng lo." |
| **PAIR_4** | Khoảng Cách Trang Trọng | Cô/Anh (họ) + (Tôi ngầm) | 1.0–2.0 | Người lạ, gặp lần đầu, tôn trọng | "Anh có thời gian không?" |
| **PAIR_5** | Tsundere/Kháng Cự | Tôi (mình) + Anh (họ) | 1.5–2.5 | Phòng thủ, che giấu cảm xúc | "Tôi không cần anh lo!" |

---

### CẤP ĐỘ PHÂN CẤP XÃ HỘI (Dựa Trên Ngữ Cảnh)

| PAIR_ID | Loại Cặp | Đại Từ | Ngữ Cảnh | Ghi Đè RTAS | Ví Dụ |
|---|---|---|---|---|---|
| **PAIR_SOCIAL_1** | Senpai (RTAS < 4.0) | Senpai (giữ tiếng Nhật) | Cách biệt tuổi học đường, chưa hẹn hò | Giữ kính ngữ Nhật | "Senpai, xem cái này đi" |
| **PAIR_SOCIAL_2** | Senpai (RTAS ≥ 4.0) | Anh/Chị (chuyển sang tiếng Việt) | Hẹn hò, vượt ngưỡng RTAS | Chuyển sang tiếng Việt | "Anh ơi, cùng về nhé" |
| **PAIR_SOCIAL_3** | Giáo Viên/Học Sinh | Thầy/Cô (họ) + Em (mình) | Ngữ cảnh học thuật | N/A (ngữ cảnh) | "Em xin lỗi thầy ạ" |
| **PAIR_SOCIAL_4** | Trang Trọng/Chính Thức | Ngài (họ) + Tôi (mình) | Tòa án, chính phủ, nghi lễ | Trang trọng cao nhất | "Tôi xin tuân mệnh, ngài." |

---

## TRA CỨU MÃ CẶP ĐẠI TỪ (Cây Quyết Định)

**Sử dụng lưu đồ này để chọn PAIR_ID đúng:**

```
BẮT ĐẦU: Xác định loại mối quan hệ
  │
  ├─→ QUAN HỆ GIA ĐÌNH?
  │   ├─ CÓ → Kiểm tra loại gia đình
  │   │   ├─ Em → Anh/Chị? → DÙNG PAIR_FAM_1
  │   │   ├─ Anh/Chị → Em? → DÙNG PAIR_FAM_2
  │   │   ├─ Con → Cha Mẹ? → DÙNG PAIR_FAM_3
  │   │   └─ Cha Mẹ → Con? → DÙNG PAIR_FAM_4
  │   └─ KHÔNG → Tiếp tục kiểm tra
  │
  ├─→ NGỮ CẢNH LÃNG MẠN?
  │   ├─ CÓ → Tính toán RTAS
  │   │   ├─ RTAS 2.0–3.5? → DÙNG PAIR_1 (Tớ-Cậu)
  │   │   ├─ RTAS 3.5–4.2? → DÙNG PAIR_2 (Tớ-Anh)
  │   │   └─ RTAS 4.2–5.0? → DÙNG PAIR_3 (Em-Anh)
  │   └─ KHÔNG → Tiếp tục kiểm tra
  │
  ├─→ BỐI CẢNH TRANG TRỌNG/CHÍNH THỨC?
  │   ├─ CÓ → DÙNG PAIR_SOCIAL_4 (Ngài/Tôi)
  │   └─ KHÔNG → Tiếp tục kiểm tra
  │
  ├─→ SENPAI/KOUHAI hoặc CÁCH BIỆT TUỔI?
  │   ├─ CÓ → Kiểm tra RTAS
  │   │   ├─ RTAS < 4.0? → DÙNG PAIR_SOCIAL_1 (Giữ "Senpai")
  │   │   └─ RTAS ≥ 4.0? → DÙNG PAIR_SOCIAL_2 (Chuyển sang tiếng Việt)
  │   └─ KHÔNG → Tiếp tục kiểm tra
  │
  ├─→ GIÁO VIÊN/HỌC SINH?
  │   ├─ CÓ → DÙNG PAIR_SOCIAL_3 (Thầy/Cô + Em)
  │   └─ KHÔNG → Tiếp tục kiểm tra
  │
  ├─→ NHÂN VẬT LÀ TSUNDERE hoặc PHÒNG THỦ?
  │   ├─ CÓ → DÙNG PAIR_5 (Tôi-Anh)
  │   └─ KHÔNG → Tiếp tục
  │
  └─→ MẶC ĐỊNH: DÙNG PAIR_4 (Cô/Anh - Khoảng Cách Trang Trọng)
```

---

## QUY TẮC GÁN CẶP TỰ ĐỘNG (Giao Thức Gemini)

**Khi Gemini gặp đối thoại, nó tuân theo quy trình này:**

### Bước 1: Xác định Người Nói và Mục Tiêu
```
Ví dụ: Umi nói với Maki
Người nói: Umi
Mục tiêu: Maki
```

### Bước 2: Kiểm tra Quan Hệ Gia Đình
```
Umi có phải là gia đình của Maki không? KHÔNG
→ Tiếp tục kiểm tra
```

### Bước 3: Kiểm tra Ngữ Cảnh Lãng Mạn
```
Đây có phải là cảnh lãng mạn không? CÓ
Tính toán RTAS(Umi → Maki) = 4.6
RTAS 4.6 rơi vào khoảng 4.2–5.0
→ Gán PAIR_3 (Em-Anh)
```

### Bước 4: KHÓA PAIR_ID cho Cảnh
```
Umi-Maki trong cảnh này: PAIR_3
CHỈ dùng Em-Anh cho tất cả đối thoại Umi→Maki
```

### Bước 5: Xuất Đối Thoại Dùng PAIR_3
```
Umi: "Em ở đây, anh đừng lo." (Em-Anh bị khóa)
Maki: [Đáp lại Umi dùng đại từ tương ứng]
```

**KHÔNG LỆCH HƯỚNG** cho đến khi RTAS được tính lại sang một phạm vi mới.

---

## MA TRẬN CẶP CẢNH ĐA NHÂN VẬT

**Với cảnh có 3+ nhân vật, tạo tham chiếu này:**

```
VÍ DỤ: Cảnh Maki + Umi + Yuu + Nitta

NGƯỜI NÓI → MỤC TIÊU | RTAS | PAIR_ID | ĐẠI TỪ | KHÓA |
─────────────────────────────────────────────────────────
Maki → Umi     | 4.6  | PAIR_3  | Em-Anh  | ✓
Umi → Maki     | 4.6  | PAIR_3  | Em-Anh  | ✓
Maki → Yuu     | 2.1  | PAIR_4  | Cô-Anh  | ✓
Yuu → Maki     | 2.1  | PAIR_4  | Cô-Anh  | ✓
Umi → Yuu      | 2.3  | PAIR_4  | Cô-Anh  | ✓
Yuu → Umi      | 2.3  | PAIR_4  | Cô-Anh  | ✓
Nitta → All    | 1.5  | PAIR_4  | Cô-Anh  | ✓
```

**Cách dùng:** Trước khi viết bất kỳ dòng thoại nào, tham khảo ma trận này để tìm PAIR_ID bị khóa.

---



Dịch thuật tiếng Việt sử dụng **phương pháp lai động** dựa trên RTAS (Điểm Căng Thẳng & Tình Cảm Quan Hệ):

### Quy Tắc Chuyển Đổi (The Switching Rule)

```
┌─────────────────────────────────────────────────────────────┐
│ RTAS < 4.0 (Người lạ/Người quen/Bạn bè)                    │
│ → GIỮ NGUYÊN kính ngữ Nhật (-san, -kun, Senpai, v.v.)      │
│ → Lý do: Sự trang trọng, khoảng cách, hương vị văn hóa     │
├─────────────────────────────────────────────────────────────┤
│ RTAS ≥ 4.0 (Hẹn hò/Người yêu/Thân mật sâu sắc)             │
│ → CHUYỂN SANG đại từ tiếng Việt (Em/Anh, v.v.)             │
│ → Lý do: Biểu đạt sự thân mật tự nhiên trong tiếng Việt    │
└─────────────────────────────────────────────────────────────┘
```

### Các Ví Dụ về Hệ Thống Lai

**RTAS 2.0 (Bạn cùng lớp):**
```
RAW: 「田中さん、これ見て」
VN:  "Tanaka-san, xem cái này đi"
```
→ Giữ "-san" (khoảng cách trang trọng)

**RTAS 3.5 (Cảm nắng nhưng chưa hẹn hò):**
```
RAW: 「先輩、一緒に帰りませんか？」
VN:  "Senpai, cùng về nhé?"
```
→ Giữ "Senpai" (chưa đủ thân mật)

**RTAS 4.5 (Hẹn hò/Chấp nhận lời tỏ tình):**
```
RAW: 「好きだよ、美咲」
VN:  "Anh thích em, Misaki"
```
→ Chuyển sang "Anh/Em" (mở khóa thân mật lãng mạn)

**NGOẠI LỆ: Quan hệ gia đình LUÔN dùng đại từ tiếng Việt bất kể RTAS**
```
RAW: 「お兄ちゃん」
VN:  "Anh ơi" (KHÔNG PHẢI "Onii-chan")
```
→ Gia đình = Đại từ tiếng Việt (cố định)

---

## NGUYÊN TẮC CỐT LÕI: ĐẠI TỪ LÀ DẤU HIỆU QUAN HỆ

Đại từ tiếng Việt mã hóa:
1. **Khoảng Cách Tuổi** (lớn/nhỏ)
2. **Giới Tính** (nam/nữ)
3. **Mức Độ Thân Mật** (người lạ → gia đình)
4. **Địa Vị Xã Hội** (ngang bằng/cấp trên/cấp dưới)
5. **Trạng Thái Cảm Xúc** (trang trọng/suồng sã/tình cảm)

---

## QUAN HỆ GIA ĐÌNH (Ưu Tiên Cao Nhất)

### Anh Chị Em (Ruột/Thân thiết)

| Tiếng Nhật | Bối Cảnh | Đại Từ Tiếng Việt | Ví Dụ |
|----------|---------|---------------------|---------|
| お兄ちゃん | Em gái → Anh trai | **Anh** (họ) / **Em** (mình) | "Anh ơi, anh đang làm gì thế?" |
| お姉ちゃん | Em → Chị gái | **Chị** (họ) / **Em** (mình) | "Chị ơi, em muốn đi cùng!" |
| 弟 | Anh/Chị → Em trai | **Em** (họ) / **Anh/Chị** (mình) | "Em đang học à?" |
| 妹 | Anh/Chị → Em gái | **Em** (họ) / **Anh/Chị** (mình) | "Em ăn cơm chưa?" |

**Quy Tắc:** Đại từ gia đình là **CỐ ĐỊNH** bất kể thay đổi về mức độ thân mật.

### Cha Mẹ & Con Cái

| Tiếng Nhật | Tiếng Việt (Con → Cha Mẹ) | Tiếng Việt (Cha Mẹ → Con) |
|----------|----------------------------|----------------------------|
| お父さん | **Ba/Bố** (họ) / **Con** (mình) | **Con** (con) / **Ba/Bố** (mình) |
| お母さん | **Mẹ/Má** (họ) / **Con** (mình) | **Con** (con) / **Mẹ/Má** (mình) |

---

## QUAN HỆ LÃNG MẠN (HỆ THỐNG LAI DỰA TRÊN RTAS)

### Thang RTAS: 1.0 (Người Lạ) → 5.0 (Tri Kỷ)

**🔑 QUAN TRỌNG: RTAS 4.0 là ngưỡng chuyển đổi**

| RTAS | Giai Đoạn Quan Hệ | Chiến Lược Dịch Tiếng Việt | Ví Dụ |
|------|-------------------|--------------------------------|---------|
| 1.0-1.5 | Người lạ/Bạn cùng lớp | **Giữ Tiếng Nhật** (-san, -kun) | "Tanaka-san" |
| 2.0-2.5 | Người quen | **Giữ Tiếng Nhật** (Senpai, -kun) | "Senpai" |
| 3.0-3.5 | Bạn bè/Cảm nắng | **Giữ Tiếng Nhật** (tên-kun, Senpai) | "Yamada-kun" |
| **4.0-4.5** | **Hẹn hò/Tỏ tình** | **CHUYỂN SANG Tiếng Việt** (Anh/Em) | "Anh/Em" |
| 5.0 | Cam kết/Kết hôn | **Tiếng Việt** (Anh/Em) | "Anh/Em" |

**Các Bước Chuyển Đổi Chính:**
- **RTAS < 4.0:** Giữ nguyên kính ngữ Nhật (trang trọng, khoảng cách, phong vị văn hóa)
- **RTAS ≥ 4.0:** Chuyển sang đại từ tiếng Việt (biểu đạt thân mật tự nhiên)
- **Thời Điểm Chuyển Đổi:** Thường xảy ra khi chấp nhận lời tỏ tình hoặc nụ hôn đầu

### Khoảnh Khắc Tỏ Tình (RTAS 3.5 → 4.5) - ĐIỂM CHUYỂN ĐỔI

**Trước Tỏ Tình (RTAS 3.5):**
```
RAW: 「先輩、好きです」
VN:  "Senpai, em thích anh"
```
→ Vẫn dùng "Senpai" (chưa đủ thân mật)

**Sau Khi Chấp Nhận Tỏ Tình (RTAS 4.5):**
```
RAW: 「ありがとう。俺も好きだ」
VN:  "Cảm ơn em. Anh cũng thích em"
```
→ Chuyển sang "Anh/Em" (mở khóa thân mật lãng mạn)

**Ngày Hôm Sau (Đã Hẹn Hò):**
```
RAW: 「おはよう、美咲」
VN:  "Chào em, Misaki"
```
→ Không còn "Misaki-chan", dùng "Em" (đại từ bạn gái)

---

## HỌC ĐƯỜNG/PHÂN CẤP XÃ HỘI (HỆ THỐNG LAI)

### Hệ Thống Senpai/Kouhai

**Chiến Lược Mặc Định: Giữ nguyên kính ngữ Nhật**

| Tiếng Nhật | Tiếng Việt (RTAS < 4.0) | Tiếng Việt (RTAS ≥ 4.0) |
|----------|------------------------|------------------------|
| 先輩 (Senpai) | **"Senpai"** (giữ tiếng Nhật) | **"Anh/Chị"** (chuyển tiếng Việt) |
| 後輩 (Kouhai) | **"[Tên]-kun/-chan"** (giữ tiếng Nhật) | **"Em/Cậu"** (chuyển tiếng Việt) |

**Ví Dụ:**

**RTAS 2.5 (Kouhai cảm nắng Senpai):**
```
RAW: 「先輩、一緒に帰りませんか？」
VN:  "Senpai, cùng về nhé?"
```
→ Giữ "Senpai" (chưa hẹn hò)

**RTAS 4.5 (Đã hẹn hò):**
```
RAW: 「一緒に帰ろう」
VN:  "Cùng về nhé, em"
```
→ Chuyển sang "Em" (đại từ bạn gái/bạn trai)

### Giáo Viên/Học Sinh

| Ngữ Cảnh | Học Sinh → Giáo Viên | Giáo Viên → Học Sinh |
|---------|------------------|-------------------|
| Trang trọng | **Thầy/Cô** (gv) / **Em/Con** (mình) | **Em/Con** (hs) / **Thầy/Cô** (mình) |
| Thân mật | **Thầy/Cô** (gv) / **Em** (mình) | **Em** (hs) / **Thầy/Cô** (mình) |

**Ghi chú:** Giáo viên/học sinh luôn dùng tiếng Việt (không dùng kính ngữ Nhật).

---

## BẠN BÈ (Cùng Tuổi, Ngang Hàng)

### Các Kết Hợp Giới Tính

| Mối Quan Hệ | Nam → Nam | Nữ → Nữ | Nam → Nữ | Nữ → Nam |
|--------------|-------------|-----------------|---------------|---------------|
| Bạn Xã Giao | Tao/Mày (thận trọng) | Tớ/Cậu | Tớ/Cậu | Tớ/Cậu |
| Bạn Thân | Tao/Mày | Tao/Mày (hiếm) | Tớ/Cậu | Tớ/Cậu |
| Bạn Chí Cốt | Tao/Mày | Mình/Bạn | Mình/Bạn | Mình/Bạn |

**Thang Trang Trọng (Bạn Bè):**
1. **Tao/Mày** - Rất suồng sã, bạn thân cùng giới
2. **Tớ/Cậu** - Thân thiện nhưng lịch sự, an toàn cho khác giới
3. **Mình/Bạn** - Ấm áp, bao hàm, trung tính

---

## CÁC TRƯỜNG HỢP ĐẶC BIỆT

### Nhân Vật Tsundere (Biến Động Khoảng Cách Cảm Xúc)

| Trạng Thái Cảm Xúc | Đại Từ | Ví Dụ |
|----------------|----------|---------|
| Phòng thủ/Giận | Tôi/Anh (xa cách) | "Tôi không cần anh lo!" |
| Bình thường | Tớ/Cậu (trung tính) | "Cậu... đi đâu thế?" |
| Khoảnh khắc Dere | Em/Anh (mềm) | "Em... lo cho anh thôi." |

**Quy Tắc:** Đại từ thay đổi theo bức tường cảm xúc lên/xuống.

### Bối Cảnh Trang Trọng/Công Khai

| Bối Cảnh | Đại Từ | Ví Dụ |
|---------|----------|---------|
| Tòa án/Chính thức | Tôi/Ngài, Điện hạ | "Tôi xin tuân mệnh, điện hạ." |
| Chào cờ/Họp trường | Em/Thầy, Cô | "Em xin báo cáo với thầy." |
| Họp mặt gia đình | (Đại từ gia đình) | "Con chào bác ạ." |

**Quy Tắc:** Bối cảnh công khai → đại từ trang trọng hơn, ngay cả giữa người thân thiết.

---

## LƯU ĐỒ CHỌN ĐẠI TỪ (HỆ THỐNG LAI)

```
BẮT ĐẦU
  ↓
Là GIA ĐÌNH? → CÓ → Dùng đại từ gia đình VN (Anh/Chị/Em/Ba/Mẹ)
  ↓ KHÔNG
Là ngữ cảnh LÃNG MẠN?
  ↓ CÓ
  Kiểm tra RTAS:
    RTAS < 4.0? → Giữ kính ngữ Nhật (-san, -kun, Senpai)
    RTAS ≥ 4.0? → Dùng đại từ lãng mạn VN (Anh/Em)
  ↓ KHÔNG
Có KHOẢNG CÁCH TUỔI (senpai/kouhai)?
  ↓ CÓ
  Kiểm tra RTAS:
    RTAS < 4.0? → Giữ "Senpai" hoặc "[Tên]-kun/-chan"
    RTAS ≥ 4.0? → Dùng tiếng Việt (Anh/Chị/Em)
  ↓ KHÔNG
Là BỐI CẢNH TRANG TRỌNG? → CÓ → Dùng VN trang trọng (Tôi/Ngài, Điện hạ)
  ↓ KHÔNG
Bạn Cùng Tuổi NGƯỜI LẠ/XÃ GIAO? → CÓ → Giữ kính ngữ Nhật (-san, -kun)
  ↓ KHÔNG
Bạn Cùng Tuổi BẠN BÈ? → CÓ → Giữ Nhật hoặc dùng Tớ/Cậu (tùy ngữ cảnh)
  ↓
MẶC ĐỊNH: Giữ kính ngữ Nhật (an toàn, trang trọng)
```

**Các Điểm Quyết Định Chính:**
1. **Gia đình = Luôn là Tiếng Việt** (ưu tiên cao nhất)
2. **RTAS ≥ 4.0 = Chuyển sang Tiếng Việt** (ngưỡng thân mật)
3. **RTAS < 4.0 = Giữ Tiếng Nhật** (trang trọng, khoảng cách)
4. **Bối cảnh trang trọng = Tiếng Việt** (tòa án, chính thức)

---

## VÍ DỤ DỊCH THUẬT

### Ví Dụ 1: Đối thoại Anh Em
```
RAW: 「お兄ちゃん、何してるの？」
EN: "Onii-chan, what are you doing?"
VN: "Anh ơi, anh đang làm gì thế?"
```
**Lý do:** Quan hệ gia đình → "Anh" (anh trai) là cố định.

### Ví Dụ 2: Tỏ Tình (Chuyển đổi RTAS)
```
RAW: 「好きだ。ずっと前から、お前のことが好きだった」
EN: "I like you. I've liked you for a long time."
VN: "Tớ thích cậu. Từ lâu rồi... tớ đã thích cậu."
```
**Lý do:** Trước tỏ tình → vẫn dùng "Tớ/Cậu" (bạn bè). Sau khi chấp nhận, sẽ chuyển sang "Em/Anh".

### Ví Dụ 3: Senpai/Kouhai
```
RAW: 「先輩、一緒に帰りませんか？」
EN: "Senpai, would you walk home with me?"
VN: "Anh ơi, cùng về nhé?"
```
**Lý do:** Kouhai → Senpai = "Anh" (anh nam lớn hơn). Bản thân = "Em" (ngầm hiểu).

### Ví Dụ 4: Biến Động Tsundere
```
RAW: 「……バカ」(embarrassed/affectionate)
EN: "...Idiot."
VN: "...Đồ ngốc." (không cần đại từ - ngữ cảnh rõ ràng)
```
**Lý do:** Khoảnh khắc thân mật cao → lược bỏ đại từ (quy tắc zero-pronoun).

### Ví Dụ 5: Tòa Án Trang Trọng
```
RAW: 「殿下、評議会がお待ちしております」
EN: "Your Highness, the council awaits."
VN: "Điện hạ, hội đồng đang chờ ngài."
```
**Lý do:** Xưng hô hoàng gia → "Điện hạ", "ngài" (trang trọng).

---

## TÍCH HỢP VỚI MẪU VÀNG (GOLDEN SAMPLES)

Khi dịch sang tiếng Việt:
1. **Xác định loại mối quan hệ** (gia đình/lãng mạn/xã hội/trang trọng)
2. **Kiểm tra mức RTAS** (cho quan hệ lãng mạn)
3. **Xem xét trạng thái cảm xúc** (cho nhân vật tsundere/biến động)
4. **Áp dụng đại từ từ hướng dẫn này**
5. **Xác minh tính nhất quán** với cách dùng trước đó trong Kho Lưu Trữ Omni-Volume

---

## CÁC LỖI THƯỜNG GẶP CẦN TRÁNH

❌ **Dùng "Tôi/Bạn" cho bạn thân** (quá trang trọng)
❌ **Dùng "Tao/Mày" khác giới** (quá thô lỗ)
❌ **Giữ đại từ lãng mạn sau khi chia tay** (hồi quy RTAS)
❌ **Trộn lẫn đại từ gia đình và lãng mạn** (ví dụ: "Anh" cho cả anh trai và bạn trai - ngữ cảnh phải rõ ràng)
❌ **Lạm dụng đại từ** (Tiếng Việt lược bỏ đại từ khi ngữ cảnh rõ ràng)

---

## 🆕 HYBRID HONORIFIC SYSTEM (KÍNH NGỮ HYBRID)

### MỤC ĐÍCH

Xử lý kính ngữ Nhật Bản (-senpai, -san, -sama, -kun, -chan) một cách **nhất quán** và **chuẩn format**.

---

### QUY TẮC FORMAT CHUẨN

**NGUYÊN TẮC VÀNG:** Honorific đi SAU tên, nối bằng dấu gạch ngang `-`

| Input (RAW) | SAI ❌ | ĐÚNG ✅ |
|-------------|--------|---------|
| Watanuki先輩 | Senpai Watanuki | **Watanuki-senpai** |
| 綿貫さん | San Watanuki | **Watanuki-san** |
| 先輩が... | tiền bối | **senpai** (hoặc "tiền bối" tùy context) |

---

### ICL HYBRID HONORIFIC

**[ICL_HYBRID_01] TÊN + SENPAI FORMAT**

```
INPUT: 「ねえ、綿貫先輩じゃない?」
CONTEXT: Dialogue bình thường, nhắc đến tiền bối

OUTPUT_SAI:
「Nè, không phải Watanuki* senpai đó sao?」 ← Dấu * + cách space!
「Nè, không phải Senpai Watanuki đó sao?」 ← Senpai đứng trước!

OUTPUT_ĐÚNG:
「Nè, không phải Watanuki-senpai đó sao?」

FORMAT: Tên-honorific (không space, có dấu gạch ngang)
```

**[ICL_HYBRID_02] THỨ TỰ TRONG CÂU**

```
INPUT: 先輩の綿貫さんが...
CONTEXT: Narrator nhắc đến tiền bối

OUTPUT_SAI:
"Senpai Watanuki lại là người..." ← Senpai đứng trước!
"Watanuki senpai lại là người..." ← Thiếu gạch ngang!

OUTPUT_ĐÚNG:
"Watanuki-senpai lại là người..."

NGUYÊN TẮC: LUÔN đặt tên trước, honorific sau, nối bằng `-`
```

---

### BẢNG HONORIFIC CHUẨN

| Honorific JP | Romanji | Format chuẩn | Khi nào dùng tiếng Việt |
|--------------|---------|--------------|-------------------------|
| 先輩 | senpai | Tên-senpai | RTAS ≥ 4.0 → "anh/chị" |
| さん | san | Tên-san | Formal → "anh/chị/cô/chú" |
| 様 | sama | Tên-sama | Trang trọng → "ngài" |
| くん | kun | Tên-kun | Thân mật nam → tên không |
| ちゃん | chan | Tên-chan | Thân mật nữ/trẻ em → tên không |
| 先生 | sensei | Tên-sensei | Học thuật → "thầy/cô" |

---

### ANTI-ENGLISH LOANWORD (CHỐNG TỪ VỰNG ANH NGỮ)

**MỤC ĐÍCH:** Hạn chế tiếng Anh trong văn nói bình thường, trừ khi raw có chủ đích sử dụng (archetype sính ngoại).

**[ICL_ANTI_ENG_01] THAY THẾ TIẾNG ANH THƯỜNG GẶP**

```
INPUT: エナジードリンク (energy drink)
OUTPUT_SAI: "energy drink" ← Để nguyên tiếng Anh!
OUTPUT_ĐÚNG: "nước tăng lực"

INPUT: コンビニ (convenience store)  
OUTPUT_ĐÚNG: "cửa hàng tiện lợi" hoặc "tiện lợi" (ngắn gọn)

INPUT: スマホ (smartphone)
OUTPUT_ĐÚNG: "điện thoại" hoặc "máy" (informal)
```

**BẢNG THAY THẾ LOANWORD:**

| Tiếng Nhật (Katakana) | Tiếng Anh | Tiếng Việt (ƯU TIÊN) |
|-----------------------|-----------|----------------------|
| エナジードリンク | energy drink | nước tăng lực |
| コンビニ | convenience store | cửa hàng tiện lợi |
| スマホ | smartphone | điện thoại |
| パソコン | personal computer | máy tính |
| コーヒー | coffee | cà phê |
| サンドイッチ | sandwich | bánh mì sandwich |
| アイスクリーム | ice cream | kem |
| ゲーム | game | game (CHO PHÉP - đã Việt hóa) |
| バイト | part-time job | làm thêm |
| デート | date | hẹn hò |

**NGOẠI LỆ - CHO PHÉP TIẾNG ANH:**
- Thuật ngữ gaming (rank, buff, nerf) → giữ nguyên
- Thuật ngữ tech phổ biến (game, video, WiFi) → giữ nguyên
- Nhân vật có archetype "sính ngoại" → cho phép mix

---

### 🔮 [TƯƠNG LAI] PAISEN HANDLING (GAL ARCHETYPE)

**Paisen (パイセン):** Cách đọc ngược của Senpai, thường dùng bởi gal/gyaru characters.

```
INPUT: パイセン、まじウケる～
CONTEXT: Gal character nói

OUTPUT_ĐÚNG:
「Paisen ơi, tức cười thật đấy～」

NGUYÊN TẮC:
- Paisen = slang của Senpai
- Giữ nguyên "Paisen" cho gal characters
- Format: Tên-paisen (nếu có tên)
- KHÔNG dịch sang "tiền bối" (mất feel slang)
```

---

### ICL TỔNG HỢP VÍ DỤ THỰC TẾ

**[ICL_HYBRID_FULL] BA CHƯƠNG CÙNG NHÂN VẬT**

```
CHAPTER 1:
INPUT: 「ねえ、綿貫先輩じゃない?」
SAI: 「Nè, không phải Watanuki* senpai đó sao?」
ĐÚNG: 「Nè, không phải Watanuki-senpai đó sao?」

CHAPTER 2:
INPUT: 綿貫先輩がエナジードリンクを大量に買っていた
SAI: Senpai Watanuki lại là người mua cả đống energy drink
ĐÚNG: Watanuki-senpai lại là người mua cả đống nước tăng lực

CHAPTER 3:
INPUT: 嘘をついて、綿貫先輩にバレないように
SAI: mong là tiền bối Watanuki sẽ không phát hiện
ĐÚNG: mong là Watanuki-senpai sẽ không phát hiện

LOGIC ĐÃ ÁP DỤNG:
1. Tên-senpai format nhất quán
2. "energy drink" → "nước tăng lực"
3. Honorific đi sau tên, nối bằng `-`
```

---

**(Hết Hệ Thống Đại Từ Tiếng Việt v2.0 - Bổ sung Hybrid Honorific)**

---

<a name="2-visual-proxemics-quick-reference"></a>
# 2. Visual Proxemics Quick Reference


# CÔNG CỤ PROXEMICS VĂN BẢN — Hướng Dẫn Tham Khảo Nhanh
**LN VN-Translator v10.0 — Text-Based Distance Estimation**

---

## 🎯 PROXEMICS VĂN BẢN LÀ GÌ?

**Proxemics** là khoa học về khoảng cách vật lý trong giao tiếp. Trong bối cảnh dịch Light Novel, chúng ta **ước tính khoảng cách giữa các nhân vật dựa trên từ vựng và ngữ cảnh** để điều chỉnh tông giọng cảm xúc và lựa chọn đại từ.

**Lưu ý:** Module này hoạt động hoàn toàn dựa trên **text-based cues** (không cần hình ảnh).

---

## 📍 BA VÙNG KHÔNG GIAN

### VÙNG THÂN MẬT (0–45cm)

**Từ vựng gợi ý (Text Cues):**
- Động từ tiếp xúc: 触れる (chạm), 抱く (ôm), 握る (nắm tay), 撫でる (vuốt ve)
- Mô tả hơi thở: 息が触れる (hơi thở chạm vào), 吐息 (tiếng thở)
- Vị trí: 耳元で (bên tai), 顔を近づける (ghé mặt lại gần)
- Cảm giác nhiệt độ: 体温を感じる (cảm nhận thân nhiệt), 温もり (hơi ấm)

**Ví dụ văn bản:**
```
「...好きだ」と耳元で囁いた。
→ Thì thầm bên tai: "...Tớ thích cậu."
[Proxemics: THÂN MẬT - "耳元で" = bên tai]
```

**Những gì bạn làm:**
- **ĐẨY RTAS lên ≥3.5** (ngay cả khi văn bản gợi ý sự trang trọng)
- Mở khóa các đại từ ấm áp nhất: *Anh-Em*, *Cậu-Tớ*, *Tôi-Em*
- Thêm các trợ từ làm mềm: *-à*, *-nhé*, *-ơi*
- Ví dụ: "Thưa Công chúa" → "Công chúa à" (chức danh + sự yêu mến)

**Cảm xúc:** Dễ bị tổn thương tối đa, tin tưởng, hoặc thu hút

---

### VÙNG CÁ NHÂN (45cm–1.2m)

**Từ vựng gợi ý (Text Cues):**
- Vị trí: 隣に座る (ngồi bên cạnh), 向かい合う (đối diện), 並んで歩く (đi cạnh nhau)
- Hành động chung: 一緒に読む (đọc cùng nhau), 肩を並べる (sát vai)
- Giao tiếp mắt: 目を合わせる (nhìn vào mắt nhau), 視線を交わす (trao đổi ánh mắt)
- Không gian: 近くに (gần đó), そばに (bên cạnh)

**Ví dụ văn bản:**
```
二人は並んで歩いていた。
→ Hai người đi cạnh nhau.
[Proxemics: CÁ NHÂN - "並んで" = cạnh nhau]
```

**Những gì bạn làm:**
- **Giữ RTAS như được tính toán** từ văn bản
- Mở khóa các biến thể cảm xúc trong tông giọng đối thoại
- Cho phép sự trêu chọc, quan tâm ẩn giấu, từ chối vui vẻ
- Ví dụ: "Hứ!" (bĩu môi) thêm *-nha*, *-chứ*, *-kìa* để tạo hương vị Gen Z

**Cảm xúc:** Gần gũi nhưng có ranh giới xã hội; có thể thể hiện tính cách

---

### VÙNG XÃ HỘI (1.2m–3.6m)

**Từ vựng gợi ý (Text Cues):**
- Rào cản vật lý: 机を挟んで (qua bàn), 扉の向こう (bên kia cửa)
- Vị trí xa: 離れた場所 (nơi xa), 遠くから (từ xa)
- Bối cảnh công cộng: 教室で (trong lớp), 会議室 (phòng họp), 廊下 (hành lang)
- Quan sát: 見つめる (nhìn chằm chằm từ xa), 眺める (ngắm nhìn)

**Ví dụ văn bản:**
```
机を挟んで向かい合って座った。
→ Ngồi đối diện nhau qua bàn.
[Proxemics: XÃ HỘI - "机を挟んで" = qua bàn = rào cản]
```

**Những gì bạn làm:**
- **Khóa chế độ ghi đè trang trọng** ngay cả khi văn bản có vẻ ấm áp
- Sử dụng đại từ kính trọng: *Vương nữ-Thần*, *Tiểu thư-Tôi*
- Tránh các trợ từ thân mật
- Duy trì khoảng cách chuyên nghiệp trong giọng văn

**Cảm xúc:** Trang trọng, quan sát, ý thức về quyền lực

---

## 🔍 TỪ KHÓA TIẾP XÚC VẬT LÝ (PHYSICAL CONTACT KEYWORDS)

### Chạm Tóc (Điểm Nhấn Quan Trọng)

| Từ vựng Nhật | Nghĩa | Tác động RTAS | Thay đổi Tông giọng |
|---|---|---|---|
| 髪に触れる | Chạm vào tóc | Tăng +2.0 | Cực kỳ nhẹ nhàng, che chở |
| 髪を撫でる | Vuốt tóc | Tăng +2.5 | Tình cảm đỉnh điểm |
| 髪をいじる | Nghịch tóc | Tăng +1.5 | Thân mật, tinh nghịch |

**Ví dụ:**
```
彼女の髪に触れた。
→ Anh chạm vào tóc cô ấy.
[RTAS Boost: +2.0 → Chuyển sang đại từ Em-Anh nếu context cho phép]
```

---

### Nắm Tay / Ôm

| Từ vựng Nhật | Nghĩa | Tác động RTAS | Vùng |
|---|---|---|---|
| 手を握る | Nắm tay | +1.5 | Thân mật |
| 手を繋ぐ | Nắm tay (dài hạn) | +2.0 | Thân mật |
| 抱きしめる | Ôm chặt | +2.5 | Thân mật |
| 肩を抱く | Ôm vai | +1.0 | Cá nhân → Thân mật |

---

### Tư Thế / Nghiêng Người

| Từ vựng Nhật | Nghĩa | Ý nghĩa | Tác động Đại từ |
|---|---|---|---|
| 身を寄せる | Nghiêng người vào | Chủ động yếu đuối, tìm kiếm sự gần gũi | Chuyển sang *Cậu*, *Em*, *Anh* |
| 身を引く | Lùi lại | Ngại ngùng, phòng thủ | Áp dụng giọng Tsundere |
| 服を掴む | Nắm chặt quần áo | Phụ thuộc, bám víu | Đại từ dễ bị tổn thương (*Tôi-Anh*) |
| 顔を背ける | Quay mặt đi | Tsundere, xấu hổ | Gắt gỏng + ấm áp ẩn giấu |

---

## 📋 BẢNG TRA CỨU NHANH: TỪ VỰNG → VÙNG KHÔNG GIAN

| Từ khóa Nhật | Vùng | RTAS Adjustment | Ví dụ Dịch |
|---|---|---|---|
| 耳元で囁く | Thân mật | +2.0 | "Thì thầm bên tai" |
| 抱きしめる | Thân mật | +2.5 | "Ôm chặt" |
| 並んで歩く | Cá nhân | +0.5 | "Đi cạnh nhau" |
| 向かい合う | Cá nhân | 0 | "Đối diện nhau" |
| 机を挟んで | Xã hội | -1.0 | "Qua bàn" (trang trọng) |
| 遠くから見る | Xã hội | -1.5 | "Nhìn từ xa" |

---

## 🧮 CÔNG THỨC PROXEMICS VĂN BẢN

```
RTAS CƠ BẢN (từ phân tích hội thoại)
    ↓
+ ĐIỀU CHỈNH VÙNG KHÔNG GIAN (từ từ vựng vị trí)
    ↓
+ TĂNG CƯỜNG TIẾP XÚC VẬT LÝ (từ động từ chạm/ôm)
    ↓
+ ĐIỀU CHỈNH TƯ THẾ (nghiêng vào/ra, quay mặt)
    ↓
= RTAS CUỐI CÙNG CHO QUYẾT ĐỊNH ĐẠI TỪ
```

**Ví dụ:**
```
Input: 「姫様...」と彼女の髪に触れながら囁いた。

Phân tích:
- Văn bản: "姫様" (Công chúa) → RTAS cơ bản = 2.0 (trang trọng)
- Vùng: "囁いた" (thì thầm) → Thân mật → +1.5
- Tiếp xúc: "髪に触れる" (chạm tóc) → +2.0
- RTAS Cuối: 2.0 + 1.5 + 2.0 = 5.5 → Giới hạn tối đa 5.0

Output: "Công chúa à..." anh thì thầm, nhẹ nhàng chạm vào tóc cô.
[Đại từ: Anh-Cô (thay vì Thần-Vương nữ) vì RTAS = 5.0]
```

---

## ✅ DANH SÁCH KIỂM TRA PHÂN TÍCH

Trước khi dịch một đoạn văn:

- [ ] **Quét từ khóa vị trí:** 隣, 向かい, 遠く, 近く, そば
- [ ] **Kiểm tra động từ tiếp xúc:** 触れる, 抱く, 握る, 撫でる
- [ ] **Ghi chú tư thế:** 身を寄せる, 身を引く, 顔を背ける
- [ ] **Xác định vùng không gian:** Thân mật / Cá nhân / Xã hội
- [ ] **Tính toán RTAS Adjustment:** Cộng/trừ điểm dựa trên bảng tra cứu
- [ ] **Chốt quyết định đại từ:** Dựa trên RTAS cuối cùng
- [ ] **Ghi lại khối PHÂN TÍCH PROXEMICS** (nếu cần)

---

## 📝 MẪU NHẬT KÝ TƯ DUY (THINKING LOG)

Khi thực hiện phân tích Proxemics, ghi lại như sau:

```
[PHÂN TÍCH PROXEMICS VĂN BẢN]

**Từ khóa Vị trí:** [vd: 耳元で = bên tai]
**Vùng Không gian:** [Thân mật/Cá nhân/Xã hội]

**Động từ Tiếp xúc:**
- [vd: 髪に触れる = chạm tóc → +2.0]

**Tư thế/Ngôn ngữ Cơ thể:**
- [vd: 身を寄せる = nghiêng vào → tìm kiếm sự gần gũi]

**Tính toán RTAS:**
- Cơ bản (từ hội thoại): 2.0
- Vùng (Thân mật): +1.5
- Tiếp xúc (Chạm tóc): +2.0
- **RTAS Cuối cùng: 5.5 → Giới hạn 5.0**

**Quyết định Đại từ:**
- Văn bản gốc: "姫様" (Công chúa - trang trọng)
- Proxemics cho phép: "Công chúa à" (trang trọng + hậu tố dịu dàng)
- Cặp đại từ: Anh-Cô (thay vì Thần-Vương nữ)
- Tông giọng: Nhẹ nhàng, che chở, tình cảm
```

---

## 🎓 QUY TẮC TỐI THƯỢNG

**Khi từ vựng gợi ý khoảng cách gần (Thân mật/Cá nhân), HÃY TIN VÀO TỪ VỰNG.**

Các động từ tiếp xúc (触れる, 抱く, 握る) và từ vị trí (耳元, そば, 隣) là bằng chứng khách quan về khoảng cách vật lý. Ngay cả khi đối thoại có vẻ trang trọng, hãy điều chỉnh tông giọng để phản ánh sự thân mật thực tế.

---

## 🔄 SO SÁNH: TRƯỚC VÀ SAU KHI ÁP DỤNG PROXEMICS

### Ví dụ 1: Chạm tóc

**Input:**
```
「姫様...」と彼女の髪に触れた。
```

**Trước (Không Proxemics):**
```
"Công chúa..." anh chạm vào tóc cô ấy.
[RTAS: 2.0 - Trang trọng thuần túy]
```

**Sau (Có Proxemics):**
```
"Công chúa à..." anh thì thầm, nhẹ nhàng chạm vào tóc cô.
[RTAS: 5.0 - Trang trọng + Tình cảm đỉnh điểm]
[Proxemics Boost: +3.0 từ "髪に触れる"]
```

---

### Ví dụ 2: Ngồi đối diện qua bàn

**Input:**
```
机を挟んで向かい合って座った。
```

**Trước:**
```
Ngồi đối diện nhau.
[RTAS: 3.0 - Bình thường]
```

**Sau (Có Proxemics):**
```
Ngồi đối diện nhau qua bàn.
[RTAS: 2.0 - Xã hội, có rào cản]
[Proxemics Penalty: -1.0 từ "机を挟んで" = qua bàn]
[Giữ tông giọng trang trọng hơn]
```

---

## 📚 TỪ VỰNG BỔ SUNG: KHOẢNG CÁCH & VỊ TRÍ

### Thân mật (0-45cm)
- 耳元で (bên tai)
- 顔を近づける (ghé mặt lại gần)
- 抱き合う (ôm nhau)
- 頬を寄せる (ghé má vào)
- 息が触れる (hơi thở chạm vào)

### Cá nhân (45cm-1.2m)
- 隣に座る (ngồi bên cạnh)
- 並んで (cạnh nhau)
- 向かい合う (đối diện)
- そばに (bên cạnh)
- 肩を並べる (sát vai)

### Xã hội (1.2m-3.6m)
- 離れた場所 (nơi xa)
- 遠くから (từ xa)
- 机を挟んで (qua bàn)
- 扉の向こう (bên kia cửa)
- 廊下の端 (cuối hành lang)

---

**Cập nhật lần cuối:** 31 Tháng 12, 2024 — LN VN-Translator v10.0 (Text-Based Proxemics)

---

<a name="3-genre-specific-vocabulary-mapping"></a>
# 3. Genre-Specific Vocabulary Mapping


# Genre-Specific Vocabulary Mapping

**Version:** 1.0  
**Purpose:** Provide genre-specific Hán-Việt vocabulary preferences for Japanese-to-Vietnamese Light Novel translation  
**Integration:** Used by HAN_VIET_RATIO_CONTROLLER in master_prompt_vn.xml

---

## Overview

This reference file contains vocabulary mapping tables for 6 Light Novel genres, each with a target Hán-Việt ratio:

| Genre | Hán-Việt Ratio | Style | Use Case |
|-------|----------------|-------|----------|
| **CULTIVATION/WUXIA** | 70% | Formal, archaic | Xianxia, martial arts novels |
| **SCHOOL_LIFE** | 30% | Casual, modern | School romcoms, slice-of-life |
| **FANTASY** | 50% | Balanced | Isekai, magic systems |
| **ROMANCE** | 35% | Natural with depth | Romance, love comedies |
| **MYSTERY** | 45% | Professional | Detective, crime solving |
| **GENERAL** | 40% | Default balanced | Mixed or unclear genre |

---

## CULTIVATION/WUXIA (70% Hán-Việt Target)

**Style:** Formal, archaic language for gravitas and authenticity  
**Avoid:** Modern slang, casual Vietnamese

### Combat Verbs

| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 倒す (taosu) | đánh bại | chiến thắng | Defeat enemy in battle |
| 殺す (korosu) | giết | trảm sát, tru diệt | Kill (formal/archaic) |
| 修練する (shuurensuru) | luyện tập | tu luyện | Cultivate/train |
| 突破する (toppa suru) | vượt qua | đột phá | Breakthrough to new level |
| 攻撃する (kougeki suru) | tấn công | công kích | Attack |
| 防御する (bougyo suru) | phòng thủ | phòng ngự | Defend |
| 逃げる (nigeru) | chạy trốn | đào tẩu, tẩu thoát | Flee/escape (formal) |
| 追う (ou) | đuổi theo | truy kích | Chase/pursue |

### Cultivation Terms

| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 境界 (kyoukai) | cấp độ, level | cảnh giới | Cultivation realm/stage |
| 霊気 (reiki) | năng lượng | linh khí | Spiritual energy/qi |
| 丹薬 (tanyaku) | thuốc | đan dược | Cultivation pill |
| 功法 (kouhou) | kỹ thuật | công pháp | Cultivation technique |
| 宗門 (shuumon) | nhóm, hội | tông môn | Sect/clan |
| 師匠 (shishou) | thầy | sư phụ | Master (cultivation) |
| 弟子 (deshi) | học trò | đệ tử | Disciple |
| 修真 (xiuzhen) | tu luyện | tu chân | Cultivation (Xianxia) |

### Adjectives

| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 強い (tsuyoi) | mạnh | hùng mạnh, cường đại | Powerful |
| 神秘的 (shinpiteki) | kỳ lạ | huyền ảo, huyền bí | Mystical |
| 古い (furui) | cũ | cổ xưa | Ancient |
| 高貴な (koukina) | sang trọng | cao quý | Noble |
| 恐ろしい (osoroshii) | đáng sợ | khủng khiếp, kinh hoàng | Terrifying |
| 美しい (utsukushii) | đẹp | mỹ lệ, tuyệt mỹ | Beautiful (formal) |

### Heroine Description (NARRATIVE ONLY)

#### Face
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 美しい顔 | mặt đẹp, gương mặt xinh | dung nhan tuyệt sắc | Beautiful face (formal) |
| 綺麗な顔 | xinh đẹp | dung mạo thanh tú | Pretty face (elegant) |
| 可愛い顔 | dễ thương | nhan sắc tuyệt trần | Cute face (elevated) |

#### Hair
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 長い黒髪 | tóc đen dài | mái tóc đen nhánh như thác đổ | Long black hair (poetic) |
| 美しい髪 | tóc đẹp | tóc dài suôn mượt như tơ | Beautiful hair |
| 髪が揺れる | tóc bay | mái tóc bay phấp phới | Hair fluttering |

#### Eyes
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 輝く瞳 | mắt sáng | đôi mắt long lanh huyền ảo | Sparkling eyes (mystical) |
| 鋭い目 | mắt sắc | nhãn thần sắc bén | Sharp gaze |
| 美しい目 | mắt đẹp | đôi mắt tinh anh | Beautiful eyes (formal) |

#### Aura/Presence
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 気品 | vẻ đẹp, phong cách | khí chất cao quý | Noble aura |
| 雰囲気 | không khí | phong thái thoát tục | Transcendent demeanor |
| 威厳 | uy nghiêm | khí tượng phi phàm | Extraordinary presence |

#### Body/Figure
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| スタイル | dáng đẹp | thân hình mảnh mai | Slender figure |
| 美しい体 | người đẹp | dáng người uyển chuyển | Graceful figure |
| 姿 | hình dáng | thể thái yêu kiều | Charming physique |

#### Skin
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 白い肌 | da trắng | làn da trắng ngần | Fair skin |
| 綺麗な肌 | da đẹp | da dẻ mịn màng | Beautiful skin |
| 雪のような肌 | da như tuyết | sắc da tuyết trắng | Snow-white skin |

#### Movement
| Japanese | Pure Vietnamese (AVOID) | Hán-Việt (PREFER) | Context |
|----------|-------------------------|-------------------|---------|
| 歩く | đi | bước đi uyển chuyển | Walk gracefully |
| 動く | cử động | cử chỉ thanh nhã | Move elegantly |
| 仕草 | cử chỉ | động tác uyển chuyển | Gestures (graceful) |

---

## SCHOOL_LIFE (30% Hán-Việt Target)

**Style:** Casual, modern language for natural everyday speech  
**Avoid:** Archaic Hán-Việt, overly formal vocabulary

### Daily Verbs

| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 行く (iku) | đi | tiền vãng | Go (casual) |
| 食べる (taberu) | ăn | thực dụng | Eat (casual) |
| 勉強する (benkyou suru) | học | học tập | Study (học is fine) |
| 遊ぶ (asobu) | chơi | vui chơi | Play/hang out |
| 話す (hanasu) | nói chuyện | đàm thoại | Talk/chat |
| 笑う (warau) | cười | hoan hỷ | Laugh (cười is natural) |
| 泣く (naku) | khóc | khóc lóc | Cry (khóc is natural) |
| 走る (hashiru) | chạy | phi hành | Run (chạy is natural) |

### School Terms

| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 友達 (tomodachi) | bạn | bằng hữu | Friend (bạn is natural) |
| 先生 (sensei) | thầy/cô | giáo viên | Teacher (both OK) |
| 教室 (kyoushitsu) | lớp | giáo thất | Classroom (lớp is natural) |
| 学校 (gakkou) | trường | học đường | School (trường is fine) |
| 部活 (bukatsu) | câu lạc bộ | hoạt động ngoại khóa | Club activities |
| クラス (kurasu) | lớp học | ban học | Class |
| 試験 (shiken) | thi, kiểm tra | khảo thí | Exam/test |

### Adjectives

| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 楽しい (tanoshii) | vui | hoan lạc | Fun/enjoyable |
| 悲しい (kanashii) | buồn | u sầu | Sad |
| 美しい (utsukushii) | đẹp | mỹ lệ | Beautiful (đẹp is natural) |
| 可愛い (kawaii) | dễ thương | khả ái | Cute (dễ thương is natural) |
| 面白い (omoshiroi) | hay, thú vị | hứng thú | Interesting |

### Heroine Description (NARRATIVE ONLY)

#### Face
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 美しい顔 | xinh, đẹp | dung nhan | Pretty face (casual) |
| 綺麗な顔 | gương mặt xinh xắn | dung mạo | Beautiful face (natural) |
| 可愛い顔 | dễ thương | nhan sắc | Cute face (casual) |

#### Hair
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 長い黒髪 | tóc đen dài | mái tóc đen nhánh | Long black hair (simple) |
| 美しい髪 | tóc dài suôn mượt | tóc như thác đổ | Beautiful hair (natural) |
| 髪が揺れる | tóc bay | mái tóc óng mượt | Hair swaying |

#### Eyes
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 輝く瞳 | mắt long lanh | nhãn thần | Sparkling eyes (natural) |
| 大きな目 | mắt to tròn | đôi mắt huyền ảo | Big eyes (casual) |
| 美しい目 | mắt sáng | đôi mắt tinh anh | Beautiful eyes (simple) |

#### Aura/Presence
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 雰囲気 | vẻ tươi trẻ | khí chất | Youthful appearance |
| 元気 | năng động, tươi tắn | phong thái | Energetic presence |
| スタイル | phong cách trẻ trung | thần thái | Youthful style |

#### Body/Figure
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| スタイル | dáng cao, thon thả | thân hình | Tall, slender (casual) |
| 美しい体 | dáng người thanh mảnh | thể thái | Slender figure (natural) |
| 姿 | dáng | hình hài | Figure (simple) |

#### Skin
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 白い肌 | da trắng | sắc da | Fair skin (simple) |
| 綺麗な肌 | da mịn, làn da trắng hồng | da dẻ mịn màng | Beautiful skin (natural) |

#### Movement
| Japanese | Pure Vietnamese (PREFER) | Hán-Việt (AVOID) | Context |
|----------|--------------------------|------------------|---------|
| 歩く | đi nhẹ nhàng | bước đi uyển chuyển | Walk lightly (casual) |
| 動く | cử chỉ tự nhiên | cử chỉ thanh nhã | Move naturally |
| 仕草 | cử động | động tác uyển chuyển | Gestures (simple) |

---

## FANTASY (50% Hán-Việt Target)

**Style:** Balanced formality - formal for magic/fantasy terms, natural for dialogue  
**Use:** Isekai, magic systems, dungeons, monsters

### Magic Terms

| Japanese | Pure Vietnamese | Hán-Việt (PREFER) | Context |
|----------|-----------------|-------------------|---------|
| 魔法 (mahou) | phép thuật | ma pháp | Magic (general) |
| 呪文 (jumon) | câu thần chú | chú văn | Spell/incantation |
| 魔力 (maryoku) | năng lượng ma thuật | ma lực | Magical power |
| マナ (mana) | năng lượng | linh lực | Mana |
| スキル (sukiru) | kỹ năng | kỹ năng | Skill (both OK) |
| レベル (reberu) | cấp độ | đẳng cấp | Level (both OK) |

### Fantasy Creatures

| Japanese | Pure Vietnamese | Hán-Việt | Context |
|----------|-----------------|----------|---------|
| モンスター (monsutaa) | quái vật | ma thú | Monster |
| ドラゴン (doragon) | rồng | long | Dragon |
| 悪魔 (akuma) | quỷ | ma quỷ | Demon |
| 天使 (tenshi) | thiên thần | thiên sứ | Angel |

### Fantasy Actions

| Japanese | Pure Vietnamese | Hán-Việt | Context |
|----------|-----------------|----------|---------|
| 冒険する (bouken suru) | phiêu lưu | mạo hiểm | Adventure |
| 探索する (tansaku suru) | khám phá | thám hiểm | Explore |
| 戦う (tatakau) | chiến đấu | giao chiến | Fight/battle |

---

## ROMANCE (35% Hán-Việt Target)

**Style:** Natural with emotional depth - moderate Hán-Việt for literary quality  
**Use:** Romance novels, love comedies, confession scenes

### Emotion Verbs

| Japanese | Pure Vietnamese | Hán-Việt | Context |
|----------|-----------------|----------|---------|
| 愛する (aisuru) | yêu | ái mộ | Love (yêu is natural) |
| 好き (suki) | thích | ưa thích | Like (thích is natural) |
| 恋する (koisuru) | yêu, thầm thương | luyến ái | Fall in love |
| 告白する (kokuhaku suru) | tỏ tình | cáo bạch | Confess love (tỏ tình is natural) |

### Emotion Nouns

| Japanese | Pure Vietnamese | Hán-Việt (MIX) | Context |
|----------|-----------------|----------------|---------|
| 恋愛 (renai) | tình yêu | tình cảm | Romance/love |
| 気持ち (kimochi) | cảm giác | tâm tình | Feelings |
| 心 (kokoro) | tim, lòng | tâm | Heart (emotional) |
| 愛 (ai) | tình yêu | ái tình | Love (formal) |

### Adjectives

| Japanese | Pure Vietnamese | Hán-Việt | Context |
|----------|-----------------|----------|---------|
| 優しい (yasashii) | dịu dàng, tốt bụng | ôn nhu | Gentle/kind |
| 寂しい (sabishii) | cô đơn | cô tịch | Lonely |
| 嬉しい (ureshii) | vui, hạnh phúc | hân hoan | Happy/glad |
| 切ない (setsunai) | đau lòng | thống thiết | Heartbreaking |

---

## MYSTERY (45% Hán-Việt Target)

**Style:** Professional, analytical tone - moderate Hán-Việt for serious atmosphere  
**Use:** Detective novels, crime solving, investigation

### Investigation Terms

| Japanese | Pure Vietnamese | Hán-Việt (PREFER) | Context |
|----------|-----------------|-------------------|---------|
| 調査する (chousa suru) | điều tra | khảo sát | Investigate |
| 分析する (bunseki suru) | phân tích | giải tích | Analyze |
| 証拠 (shouko) | bằng chứng | chứng cứ | Evidence |
| 犯人 (hannin) | kẻ phạm tội | thủ phạm | Culprit |
| 事件 (jiken) | vụ việc | vụ án | Case/incident |
| 推理 (suiri) | suy luận | suy lý | Deduction/reasoning |
| 探偵 (tantei) | thám tử | trinh thám | Detective |

### Mystery Actions

| Japanese | Pure Vietnamese | Hán-Việt | Context |
|----------|-----------------|----------|---------|
| 疑う (utagau) | nghi ngờ | hoài nghi | Suspect/doubt |
| 解決する (kaiketsu suru) | giải quyết | giải quyết | Solve (both OK) |
| 隠す (kakusu) | giấu | ẩn nấp | Hide/conceal |
| 発見する (hakken suru) | phát hiện | phát giác | Discover |

---

## GENERAL (40% Hán-Việt Target)

**Style:** Default balanced approach when no specific genre is detected  
**Use:** Mixed genres, unclear genre, general translation

**Guideline:** Use current KANJI_HANDLER logic without genre-specific constraints. Balance between natural Vietnamese and literary Hán-Việt based on context.

---

## Usage Guidelines

### For NARRATIVE Text
- Apply genre-specific vocabulary preferences
- Use target Hán-Việt ratio as guideline (not strict rule)
- Prioritize natural flow over exact percentage
- Heroine descriptions follow genre-specific vocabulary

### For DIALOGUE Text
- **ARCHETYPE_VOICE_LOCK takes priority** over genre ratio
- Character personality > genre vocabulary
- Example: GYARU in CULTIVATION novel still uses casual Vietnamese in dialogue
- Genre ratio only affects narrative descriptions

### Conflict Resolution
1. **ARCHETYPE_VOICE_LOCK** (dialogue) > Genre ratio
2. **FAMILY_OVERRIDE** > Genre ratio
3. **Natural flow** > Strict percentage
4. **Technical terms** use appropriate vocabulary regardless of ratio

---

**Last Updated:** 2026-01-06  
**Version:** 1.0  
**Integrated with:** master_prompt_vn.xml v1.4

---

<a name="4-vietnamese-expression-mapping"></a>
# 4. Vietnamese Expression Mapping


# 14_VIETNAMESE_EXPRESSION_MAPPING
**Trạng thái:** HOẠT ĐỘNG & ƯU TIÊN CAO (Tra cứu khi gặp hội thoại)  
**Mục tiêu:** Đa dạng hóa từ ngữ, chống lặp từ (Anti-Repetition), và Việt hóa tự nhiên.

---

## PHẦN 1: TỪ ĐIỂN CẢM THÁN & THÁN TỪ (INTERJECTIONS)
*Quy tắc: Không dùng mãi một từ. Hãy xoay tua (rotate) các lựa chọn dưới đây tùy theo ngữ cảnh và nhân vật.*

### 1.1 Ngạc nhiên / Sốc (Surprise)
**Nguồn Nhật:** ええ！？ (Ehh!?), うそ (Uso), まじ (Maji), はあ (Haa), あら (Ara)

| Mức độ | Các lựa chọn Tiếng Việt (Xoay tua) | Ngữ cảnh sử dụng |
| :--- | :--- | :--- |
| **Nhẹ** | Ơ? / Ủa? / Hả? / Gì cơ? | Ngạc nhiên thông thường. |
| **Vừa** | Cái gì? / Đùa à? / Thật á? / Ảo thế? | Khi nghe tin khó tin. |
| **Mạnh** | Vãi! / Điêu! / Chém gió! / Gì vậy trời! | (Gen Z/Suồng sã) Sốc. |
| **Sốc nặng** | Không thể tin nổi! / Cái quái gì...? / Trời đất ơi! | Sốc tột độ. |
| **Ara Ara** | Ái chà / Ồ là la / Chà chà / Ô hay | (Onee-san/Ojou) Thích thú. |

### 1.2 Khó chịu / Bực bội (Annoyance)
**Nguồn Nhật:** もう (Mou), まったく (Mattaku), チッ (Tsk), はあ (Haa - Sigh)

| Mức độ | Các lựa chọn Tiếng Việt (Xoay tua) | Ngữ cảnh sử dụng |
| :--- | :--- | :--- |
| **Thở dài** | Haiz... / Chán chả buồn nói... / Thiệt tình... | Bất lực, ngán ngẩm. |
| **Trách móc** | Rõ khổ... / Lạy hồn... / Mệt ghê... / Gớm... | Phàn nàn nhẹ (Tsundere hay dùng). |
| **Cáu** | Phiền phức quá! / Rách việc! / Đủ rồi đấy! | Bực mình thật sự. |
| **Chửi thầm** | Khỉ thật. / Chết tiệt. / Mẹ kiếp. | (Delinquent/Nam) Tức giận. |

### 1.3 Ghê tởm / Sợ hãi (Disgust / Fear)
**Nguồn Nhật:** うわ (Uwa), げっ (Geh), きも (Kimo), ひい (Hii)

| Cảm xúc | Các lựa chọn Tiếng Việt (Xoay tua) | Ngữ cảnh sử dụng |
| :--- | :--- | :--- |
| **Ghê tởm** | Eo ôi... / Khiếp... / Ớn... / Tởm quá... | Thấy gì đó bẩn/kỳ quặc. |
| **Nổi da gà** | Vái cả nón... / Sởn cả gai ốc... / Rùng mình... | Sợ hãi hoặc cringe. |
| **Sợ hãi** | Ối mẹ ơi! / Ối dồi ôi! / Thôi xong! / Toang! | Gặp nguy hiểm/ma. |
| **Giật mình** | Hú hồn! / Giật cả mình! / Hết hồn chim én! | Bị hù. |

### 1.4 Đồng ý / Tán thành (Agreement)
**Nguồn Nhật:** なるほど (Naruhodo), 確かに (Tashikani), そうそう (Sou sou)

| Sắc thái | Các lựa chọn Tiếng Việt (Xoay tua) | Ngữ cảnh sử dụng |
| :--- | :--- | :--- |
| **Hiểu ra** | Ra là thế. / Hèn gì. / Thảo nào. / Bảo sao. | Vỡ lẽ ra vấn đề. |
| **Đồng tình** | Chuẩn. / Công nhận. / Đúng đấy. / Chí phải. | Tán thành ý kiến. |
| **Khen ngợi** | Uy tín luôn. / Hết nước chấm. / Đỉnh. | (Slang) Khen ngợi. |

---

## PHẦN 2: CỤM TỪ PHẢN XẠ (REACTIVE PHRASES MAPPING)
*Quy tắc: Thay thế bản dịch "từ điển" (Cột SAI) bằng bản dịch "tự nhiên" (Cột ĐÚNG).*

### 2.1 Từ chối & Phủ định (Refusal)

| Nguồn Nhật | ❌ SAI (Dịch máy/Cứng) | ✅ ĐÚNG (Tự nhiên/Đa dạng) |
| :--- | :--- | :--- |
| **まったく要らない** | "Hoàn toàn không cần."<br>"Tuyệt đối không cần." | "Thôi khỏi." / "Xin kiếu."<br>"Ai thèm." / "Cần quái gì." |
| **嫌だ (Iyada)** | "Tôi ghét điều đó."<br>"Không muốn." | "Còn lâu." / "Mơ đi."<br>"Không đời nào." / "Chịu thôi." |
| **無理 (Muri)** | "Vô lý."<br>"Không thể nào." | "Không có cửa đâu." / "Quá sức rồi."<br>"Sao mà làm được." |
| **関係ない** | "Không liên quan." | "Liên quan gì." / "Chẳng ăn nhập gì cả."<br>"Kệ người ta." |

### 2.2 Nghi vấn & Bối rối (Confusion)

| Nguồn Nhật | ❌ SAI (Dịch máy/Cứng) | ✅ ĐÚNG (Tự nhiên/Đa dạng) |
| :--- | :--- | :--- |
| **何それ (Nani sore)** | "Cái đó là gì?" | "Cái quái gì thế?" / "Gì vậy trời?"<br>"Vụ gì đấy?" |
| **意味わからない** | "Không hiểu ý nghĩa." | "Chả hiểu gì cả." / "Nói tiếng người đi."<br>"Hack não à?" |
| **どうしよう** | "Làm sao đây?" | "Tính sao giờ?" / "Toang rồi."<br>"Thế này thì chết." |

### 2.3 Khen ngợi & Cảm thán (Praise)

| Nguồn Nhật | ❌ SAI (Dịch máy/Cứng) | ✅ ĐÚNG (Tự nhiên/Đa dạng) |
| :--- | :--- | :--- |
| **さすが (Sasuga)** | "Quả nhiên là..." | "Đúng là..." / "Chẳng hổ danh..."<br>"Ghê thật!" / "Đỉnh vãi!" |
| **信じられない** | "Không thể tin được." | "Điêu vãi." / "Ảo thật đấy."<br>"Không tin nổi." |
| **よかった** | "Tốt quá." | "May quá." / "Hú hồn."<br>"Ơn giời." |

---

## PHẦN 3: XỬ LÝ TỪ ĐỆM (FILLERS)
*Biến những âm ậm ừ tiếng Nhật thành tiếng Việt tự nhiên.*

* **あの... / えと... (Ano/Eto)**
    * ❌ Sai: "Cái kia...", "Eto..."
    * ✅ Đúng: "À thì...", "Kiểu là...", "Nói sao nhỉ...", "Ừm..."
* **まあ... (Maa)**
    * ❌ Sai: "Mà..."
    * ✅ Đúng: "Cũng đúng...", "Chà...", "Thì...", "Kể ra thì..."
* **なんか... (Nanka)**
    * ❌ Sai: "Cái gì đó..."
    * ✅ Đúng: "Tự nhiên thấy...", "Cảm giác như...", "Sao sao ấy..."

---

## PHẦN 4: CHECKLIST CHỐNG LẶP (ANTI-REPETITION)

Trước khi xuất bản đoạn hội thoại, hãy tự kiểm tra:

1. [ ] **Đếm từ "Trời ạ" / "Trời ơi":** Nếu xuất hiện > 2 lần trong 1 trang -> **PHẢI THAY THẾ** bằng: "Haiz", "Thiệt tình", "Gớm", "Vãi", "Khiếp".
2. [ ] **Đếm từ "Tuyệt đối":** Trong văn nói, "tuyệt đối" nghe rất quân sự/robot. Thay bằng: "Chắc chắn", "Sống chết cũng không", "Đừng hòng".
3. [ ] **Kiểm tra độ "Chua ngoa":** Với nhân vật như bà chị Mei, hãy dùng từ ngữ đanh đá hơn ("Ai thèm", "Xì", "Gớm nữa") thay vì từ ngữ trung tính.

---

## PHẦN 5: ÁNH XẠ THEO ARCHETYPE

### 5.1 Tsundere (傲嬌)
**Đặc điểm:** Phủ nhận cảm xúc thật, dùng từ ngữ cáu gắt nhưng hành động lại quan tâm.

| Tình huống | ❌ Dịch cứng | ✅ Tsundere-style |
| :--- | :--- | :--- |
| Từ chối giúp đỡ | "Tôi không muốn giúp." | "Ai thèm giúp cậu." / "Đừng hòng nhờ tôi." |
| Thực ra quan tâm | "Tôi lo lắng cho bạn." | "Không phải tôi lo cho cậu đâu nhé!" |
| Nhận quà | "Cảm ơn." | "Ừ... cũng được." / "Thôi được rồi, nhận vậy." |

### 5.2 Kuudere (クーデレ)
**Đặc điểm:** Lạnh lùng, ít cảm xúc, nói ngắn gọn.

| Tình huống | ❌ Dịch cứng | ✅ Kuudere-style |
| :--- | :--- | :--- |
| Đồng ý | "Tôi đồng ý." | "Ừ." / "Được." |
| Từ chối | "Tôi từ chối." | "Không." / "Thôi." |
| Ngạc nhiên | "Tôi ngạc nhiên." | "À." / "Ồ." |

### 5.3 Gyaru (ギャル)
**Đặc điểm:** Năng động, Gen Z, nhiều slang.

| Tình huống | ❌ Dịch cứng | ✅ Gyaru-style |
| :--- | :--- | :--- |
| Ngạc nhiên | "Thật sao?" | "Ảo thế?" / "Điêu!" / "Vãi!" |
| Đồng ý | "Đúng vậy." | "Chuẩn luôn!" / "Uy tín!" |
| Phủ nhận | "Không phải vậy." | "Đâu có!" / "Hông đúng nha!" |

### 5.4 Ojou-sama (Tiểu Thư Quyền Quý)
**Đặc điểm:** Tinh tế, hơi cổ trang, dùng từ ngữ bề trên nhưng lịch sự, thường dùng "Ara ara".

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Bình dân | ✅ Ojou-style (Sang trọng) |
| --- | --- | --- | --- |
| **Ngạc nhiên** | あら (Ara) | "Hả?" / "Cái gì?" | "Ô kìa..." / "Chẳng hay..." / "Ái chà..." |
| **Đồng ý** | そうね (Sou ne) | "Đúng vậy." / "Chuẩn." | "Quả đúng là vậy." / "Chí phải." |
| **Từ chối** | 結構です (Kekkou desu) | "Không cần đâu." | "Ta xin kiếu." / "Thứ đó không cần thiết." |
| **Khen ngợi** | 素敵 (Suteki) | "Đẹp vãi." / "Tuyệt." | "Thật tuyệt mỹ." / "Quả là tao nhã." |
| **Cảm ơn** | 感謝します (Kansha) | "Cảm ơn nha." | "Ta rất cảm kích." / "Đa tạ lòng tốt của người." |

### 5.5 Delinquent / Yankii (Lưu Manh / Côn Đồ)
**Đặc điểm:** Thô lỗ, cục súc, dùng từ ngữ mạnh, xưng hô Tao-Mày, hay chửi thề nhẹ.

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Lịch sự | ✅ Yankii-style (Cục súc) |
| --- | --- | --- | --- |
| **Khó chịu** | ああ？ (Aa?) | "Hả?" / "Gì cơ?" | "Hả? Mày ý kiến gì?" / "Muốn chết à?" |
| **Ồn ào** | うるさい (Urusai) | "Ồn quá." / "Im lặng đi." | "Câm mồm!" / "Lắm mồm vãi!" |
| **Xin lỗi** | 悪い (Warui) | "Xin lỗi nhé." | "Lỗi tao." / "Ờ thì... sorry." |
| **Ngạc nhiên** | マジか (Majika) | "Thật không?" | "Điêu vãi!" / "Ảo thế?" / "Đùa bố mày à?" |
| **Hiểu rồi** | 分かった (Wakatta) | "Tôi hiểu rồi." | "Biết rồi, khổ lắm!" / "Duyệt." |

### 5.6 Onee-san (Chị Gái Trưởng Thành/Quyến Rũ)
**Đặc điểm:** Trêu chọc (teasing), nuông chiều, dùng nhiều trợ từ mềm (nè, nhé, cơ mà).

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Khô khan | ✅ Onee-san-style (Quyến rũ) |
| --- | --- | --- | --- |
| **Ngạc nhiên** | あらあら (Ara ara) | "Trời ơi." | "Ái chà chà..." / "Ôi dào..." |
| **Nhắc nhở** | だめよ (Dame yo) | "Không được." | "Không được đâu nhé~" / "Hư là chị phạt đấy." |
| **Khen ngợi** | よしよし (Yoshi yoshi) | "Tốt lắm." | "Ngoan lắm~" / "Giỏi quá cơ~" |
| **Mời mọc** | どう？ (Dou?) | "Thế nào?" | "Thấy sao hử?" / "Hứng thú không nào?" |
| **Lo lắng** | 大丈夫？ (Daijoubu) | "Bạn ổn không?" | "Có sao không đấy, bé ngoan?" |

### 5.7 Samurai / Warrior (Kiếm Hiệp / Cổ Trang)
**Đặc điểm:** Trang nghiêm, dùng từ Hán-Việt, câu văn ngắn gọn, dứt khoát (Tenuto).

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Hiện đại | ✅ Samurai-style (Hán-Việt) |
| --- | --- | --- | --- |
| **Xin lỗi** | すまない (Sumanai) | "Xin lỗi nha." | "Thất lễ." / "Thật hổ thẹn." |
| **Cảm ơn** | かたじけない (Katajikenai) | "Cảm ơn nhiều." | "Đa tạ." / "Tại hạ xin ghi tâm." |
| **Đồng ý** | 承知 (Shouchi) | "Ok." / "Được thôi." | "Đã rõ." / "Tuân mệnh." / "Lĩnh ý." |
| **Từ chối** | 断る (Kotowaru) | "Không thích." | "Thứ lỗi cho ta." / "Không thể tuân theo." |
| **Chết** | 死ぬ (Shinu) | "Chết đi." | "Thọ tử đi!" / "Chịu chết đi!" |

### 5.8 Chuunibyou (Ảo Tưởng Sức Mạnh)
**Đặc điểm:** Dùng từ ngữ đao to búa lớn, thần thoại hóa mọi thứ, văn vở.

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Bình thường | ✅ Chuu-style (Kịch tính) |
| --- | --- | --- | --- |
| **Đồng ý** | いいだろう (Ii darou) | "Được thôi." | "Hừ, định mệnh đã an bài." / "Thú vị đấy." |
| **Không biết** | 知らない (Shiranai) | "Tôi không biết." | "Điều đó nằm ngoài kho tàng tri thức của ta." |
| **Đau** | 痛い (Itai) | "Đau quá!" | "Cánh tay phải của ta đang gào thét...!" |
| **Chào** | よっ (Yo) | "Chào." | "Ngươi đã được triệu hồi đến đây sao?" |
| **Tuyệt** | すげえ (Sugee) | "Ghê thế." | "Sức mạnh này... thật đáng kinh ngạc." |

### 5.9 Kansai-ben / Rustic (Giọng Địa Phương / Thân Thiện)
**Đặc điểm:** Dùng từ ngữ suồng sã, gần gũi, mang hơi hướng phương ngữ (nhưng không nên dùng phương ngữ quá nặng gây khó hiểu).

| Tình huống | Nguồn Nhật | ❌ Dịch Cứng / Chuẩn | ✅ Kansai-style (Thân thiện) |
| --- | --- | --- | --- |
| **Đúng không?** | せやろ (Seyaro) | "Đúng không?" | "Chuẩn bài chưa!" / "Chứ còn gì nữa!" |
| **Không phải** | ちゃう (Chau) | "Sai rồi." | "Hông phải đâu nha." / "Tào lao nè." |
| **Cảm ơn** | おおきに (Ookini) | "Cảm ơn." | "Cảm ơn nghen!" / "Đa tạ bà con!" |
| **Thật á?** | ホンマ？ (Honma) | "Thật à?" | "Thiệt hông đó?" / "Thiệt luôn?" |
| **Không làm được** | 無理 (Muri) | "Không thể." | "Thua luôn!" / "Chịu chết!" |

---

## PHẦN 6: PRIORITY RULES (Quy tắc Ưu tiên)

1. **VARIETY > ACCURACY**: Trong hội thoại, sự đa dạng quan trọng hơn độ chính xác từ điển.
2. **CONTEXT > LITERAL**: Dịch theo ngữ cảnh, không dịch từng từ.
3. **ARCHETYPE > GENERIC**: Ưu tiên từ ngữ phù hợp với tính cách nhân vật.
4. **NATURAL > FORMAL**: Trong Light Novel, văn nói tự nhiên > văn viết trang trọng.

---

## PHẦN 7: VÍ DỤ ÁP DỤNG

### Ví dụ 1: Chống lặp "Trời ạ"

**Input (Nhật):**
```
「ええ！？ 本当に！？」
「うそ！？ まじで！？」
「信じられない！」
```

**❌ Dịch lặp từ:**
```
"Trời ạ!? Thật sao!?"
"Trời ạ!? Nghiêm túc đấy à!?"
"Trời ạ! Không thể tin nổi!"
```

**✅ Dịch đa dạng:**
```
"Ủa!? Thật sao!?"
"Không đời nào!? Nghiêm túc đấy à!?"
"Điêu vãi! Không tin nổi!"
```

### Ví dụ 2: Sửa "Mattaku" robot

**Input (Nhật):**
```
「まったく、困ったものだ」
```

**❌ Dịch cứng:**
```
"Tuyệt đối, thật là rắc rối."
```

**✅ Dịch tự nhiên:**
```
"Haiz, rắc rối thật đấy."
hoặc
"Thiệt tình, khổ ghê."
```

---

## PHẦN 8: CHECKLIST CẢM XÚC & NGỮ KHÍ (TONE CHECKLIST)

*Dành cho AI tự kiểm tra trước khi xuất output:*

1. **Xác định Người Nói (Speaker ID):** Nhân vật này thuộc Archetype nào? (VD: Mei = Gyaru/Sister).

2. **Kiểm tra Từ vựng (Vocab Check):**
   - Nếu là **Gyaru/Sister**: Có dùng "nha, nè, trời ơi, vãi" không? (Nên có).
   - Nếu là **Ojou**: Có dùng "vãi, toang" không? (CẤM). Thay bằng "Ara, hỏng rồi".

3. **Kiểm tra Đuôi câu (Suffix Check):**
   - Câu hỏi có bị cụt lủn không? (VD: "Được không?" -> Nên là "Được không nhỉ?", "Được hông ta?").

4. **Kiểm tra Cảm thán (Interjection Check):**
   - Đã xoay tua từ cảm thán chưa? (Đừng dùng lại "Trời ạ" nếu vừa dùng ở câu trước).

---

**LƯU Ý CUỐI:** File này là **LIVING DOCUMENT** - hãy bổ sung thêm các pattern mới khi phát hiện lỗi lặp từ hoặc dịch cứng trong quá trình sử dụng!

---

<a name="5-sensory-lexicon"></a>
# 5. Sensory Lexicon


---
**Ref_SENSORY_LEXICON.md — LỚP GIỌNG ĐIỆU BẢN NGỮ VIỆT NAM**
**Trạng thái Module:** HOẠT ĐỘNG & CÓ THẨM QUYỀN
**Mục đích:** Động từ sinh động, từ tượng thanh, từ láy, chèn tiếng lóng cho hương vị Việt Nam chân thực
---

# Ref_SENSORY_LEXICON.md

## TỔNG QUAN

Module này chứa thư viện từ vựng cảm giác hoàn chỉnh cho LN VN-Translator v9.1. Sử dụng các bảng này để thay thế động từ yếu bằng các lựa chọn thay thế giàu cảm giác và chèn nhịp điệu Việt Nam chân thực vào các cảnh cảm xúc cao.

**Ba Kỹ thuật Cốt lõi:**
1. Thay thế Động từ Yếu→Mạnh
2. Lựa chọn Từ láy + Từ tượng thanh
3. Chèn Tiếng lóng Gen Z (Có điều kiện)

---

## MỤC 1: BẢNG THAY THẾ ĐỘNG TỪ YẾU→MẠNH

**Triết lý:** Mặc định của Gemini an toàn về ngữ pháp nhưng trống rỗng về cảm xúc. Bảng này thay thế động từ trung tính bằng các lựa chọn thay thế sâu sắc truyền tải cảm giác và chuyển động.

| Động từ Yếu | Thay thế Mạnh | Cảm giác | Ngữ cảnh |
|-----------|-------------------|---|---|
| **Ngồi** (Sit) | Ngồi phịch | Thud/collapse | Sudden sitting, exhaustion |
| | Sà xuống | Sinking down | Emotional weight |
| | Ngã uỵch | Plopping down | Casual, tired |
| | Ngồi bệt | Flat sitting | Complete relaxation |
| **Chạy** (Run) | Lao đi | Rushed/desperate | Panic, urgency |
| | Phóng vút | Swift dash | Speed, escape |
| | Tháo chạy | Flight/scramble | Fear-driven |
| | Ùa đi | Flood forward | Group movement |
| **Cười** (Laugh) | Cười khúc khích | Rhythmic chuckle | Warm intimacy |
| | Rúc rích | Giggly snort | Playful |
| | Khanh khách | Sharp laugh | Teasing, mischievous |
| | Nụ cười rạng rỡ | Radiant smile | Joy/light |
| **Run** (Shiver) | Run bần bật | Rattling shiver | Fear, extreme cold |
| | Lẩy bẩy | Trembling (delicate) | Vulnerability |
| | Rùng mình | Spine-tingling | Horror, dread |
| | Tầm tếu | Shaky movement | Illness/weakness |
| **Mệt** (Tired) | Nặng trĩu | Heavy-laden | Physical/emotional weight |
| | Rã rời | Limp/drooping | Complete exhaustion |
| | Oải chè đậu | Listless | Apathetic tiredness |
| | Bủn rủn | Drooping/sagging | Weakness |
| **Khóc** (Cry) | Phát khóc | Break into tears | Sudden overwhelm |
| | Nước mắt tuôn rơi | Tears cascade | Intense emotion |
| | Nức nở | Sobbing | Uncontrollable |
| | Lặng im, một dòng nước mắt | Silent tears | Deep sorrow |
| **Nói** (Speak) | Thì thầm | Whisper | Intimacy, secrecy |
| | Hét lên | Shout | Alarm, anger |
| | Thốt ra | Blurt out | Uncontrolled |
| | Nói nhẹ nhàng | Speak softly | Tenderness |
| **Nóng** (Hot) | Nóng hầm hập | Stuffy heat | Indoor warmth |
| | Nóng như lửa đốt | Burning | Fever, anger |
| | Nóng rẻo | Crisp heat | Intensity |
| **Lạnh** (Cold) | Lạnh toát | Cold sweat | Fear, shock |
| | Lạnh buốt | Piercing cold | Winter, dread |
| | Lạnh ngắt | Sudden chill | Shock moment |
| | Ớn lạnh | Creeping cold | Horror, unease |
| **Buồn** (Sad) | Buồn thiu | Drooping sadness | Melancholy |
| | Ỉu xìu | Pouting sadness | Cute despair |
| | Xám xịt | Gray/gloomy | Hopelessness |
| | Buồn tẫn | Utterly sad | Deep sorrow |
| **Ngạc nhiên** (Surprised) | Hoảng hốt | Panicked surprise | Fear-shock hybrid |
| | Giật nảy | Jolted | Sudden startle |
| | Chớp mắt | Blink/flutter | Quick realization |
| | Sửng sốt | Stunned | Shocked silent |

---

## MỤC 2: THƯ VIỆN TỪ LÁY & TỪ TƯỢNG THANH

**Triết lý:** Tiếng Việt có nhịp điệu. Những từ này tạo kết cấu âm thanh và cộng hưởng cảm xúc. Sử dụng chúng tự do trong các cảnh cảm xúc cao.

### 2.1 TỪ LÁY — SẮP XẾP THEO CẢM XÚC

#### KIỆT SỨC/YẾU ĐuỐI
- **Nặng trĩu** — Heavy-laden (physical weight)
- **Rã rời** — Limp/drooping (complete collapse)
- **Bủn rủn** — Sagging downward (weakness)
- **Lả lơi** — Flaccid/drooping (no energy)
- **Oải chè đậu** — Listless (apathetic)
- **Lết lủi** — Dragging motion (exhaustion)

#### BUỒN BÃ/U SẦU
- **Ỉu xìu** — Pouting-sad (cute despair)
- **Buồn thiu** — Drooping sadness (melancholy)
- **Xám xịt** — Gray/gloomy (hopelessness)
- **Tủi thân** — Shame-sadness (humiliation)
- **Sầu sâu** — Deep sorrow (poetic)

#### SỢ HÃI/KINH HOÀNG
- **Run bần bật** — Rattling shiver (terror)
- **Rùng mình** — Spine-tingling (dread)
- **Ớn lạnh** — Creeping cold (unease)
- **Tái mét** — Pale-green (nausea + fear)
- **Lạnh toát** — Cold sweat (panic)

#### VUI SƯỚNG/PHẤN KHÍCH
- **Khanh khách** — Sharp laugh (mischievous joy)
- **Rúc rích** — Giggly snort (playful)
- **Vui tươi** — Bright joy (cheerfulness)
- **Hừng hực** — Spirited (energetic happiness)

#### THÂN MẬT/DỊU DÀNG
- **Khúc khích** — Soft chuckle (warm laugh)
- **Mềm mại** — Soft/gentle (tenderness)
- **Ấm áp** — Warm/cozy (comfort)
- **Êm ái** — Soothing/gentle (care)

---

### 2.2 TỪ TƯỢNG THANH & HIỆU ỨNG ÂM THANH (SFX)

#### NHỊP TIM CẢM XÚC
- **Tim đập thình thịch** — Heart pounding (excitement/fear)
- **Tim đập tập tập** — Heart racing (anxiety)
- **Tim đập yếu ớt** — Heart fluttering (vulnerability)
- **Tim yên tĩnh** — Heart calming (peace)

#### SFX HÀNH ĐỘNG (CHIẾN ĐẤU/VẬT LÝ)
- **Phụt** — Gunshot/sudden impact
- **Cạch cạch** — Scraping sound
- **Bục** — Explosive/shattering sound
- **Bộp** — Dull thud
- **Động động** — Rumbling noise

#### HÀNH ĐỘNG ĐỘT NGỘT
- **Tút, tút, tút** — Phone disconnection
- **Cái rụp** — Abrupt hang-up
- **Dứt khoát** — Decisive cut-off
- **Cạch cạch** — Mechanical sound
- **Bam bam** — Door slamming

#### SFX ĐỐI THOẠI (TRẠNG THÁI CẢM XÚC)
- **Hức...** — Catching breath (shock, tears)
- **Ư...** — Reluctant sound (hesitation)
- **Này...** — Wavering voice (uncertainty)
- **Hừ!** — Disdainful snort (tsundere)
- **Chứ...** — Lingering particles (playful)

---

## MỤC 3: CHÈN TIẾNG LÓNG GEN Z (CÓ ĐIỀU KIỆN)

**QUY TẮC:** Chỉ sử dụng cho độc thoại nội tâm MC nam (tuổi trung học) khi RTAS ≥ 3.5 và giọng điệu nhân vật hỗ trợ.

### 3.1 CẤP ĐỘ SỐC/THẢM HỌA (RTAS ≥ 4.8)
- **"Toang rồi"** — Everything's ruined
- **"Toang hẳn"** — Completely wrecked
- **"Vãi chưởng"** — Incredible/shocking
- **"Xong phim"** — It's over, game over
- **"Ối dồi ôi"** — Oh my god (variant)
- **"Ôi giời ơi"** — Traditional variant

### 3.2 ĐỒNG Ý/CHẤP NHẬN (RTAS 3.0-3.9)
- **"Chuẩn cơm mẹ nấu"** — Absolutely correct
- **"Chốt đơn"** — Confirmed/dealt
- **"Uy tín luôn"** — Trustworthy/reliable
- **"Cơ mà có gì đâu"** — Not a big deal anyway
- **"Công nhận"** — Admit it (agreement)

### 3.3 BẤT ĐỒNG/THẤT VỌNG (RTAS 2.0-3.9)
- **"Chê"** — Disapproving tone
- **"Còn cái nịt"** — Nothing (dismissive)
- **"Mơ đi"** — Dream on (dismissal)
- **"Thôi được rồi"** — Give up on it
- **"Hắc"** — Derisive sound

### 3.4 DỄ BỊ TỔN THƯƠNG/NHẬN RA (RTAS 3.5-4.9)
- **"Thực ra..."** — Actually... (confession start)
- **"Nên..."** — So... (hesitant realization)
- **"À thế à"** — Oh it's like that? (dawning awareness)
- **"Tình lắm"** — So touching/meaningful
- **"Vẫn còn hy vọng"** — Still have hope

---

## MỤC 4: QUY TẮC PHÂN MẢNH (Phá vỡ Câu)

**Triết lý:** Light novel Việt Nam ưu tiên nhịp điệu. Phá vỡ câu dài trong các cảnh cảm xúc cao.

### 4.1 YẾU (MẶC ĐỊNH GEMINI)
```
"Ngay khi vừa mở mắt, tôi đã nhận ra ngay sự bất thường vì cơn đau nhức ập đến."
```
**Vấn đề:** Quá dài, không nhịp điệu, mất tính cấp bách

### 4.2 MẠNH (PHONG CÁCH KIM ĐỒNG)
```
"Và rồi...
Sáng ngày 25.

Cơn buồn ngủ nặng trĩu bao trùm lấy tôi.
Chắc do hôm qua mải chơi quá...
Không, không phải."
```
**Kỹ thuật:** Sử dụng ngắt dòng + dấu ba chấm để tạo tạm dừng & nhịp điệu

### 4.3 THỰC HIỆN
- **Quy tắc Phân mảnh:** Phá vỡ thành 2-3 đơn vị câu trong hành động/cảm xúc cao
- **Dấu ba chấm (...) = Tạm dừng** — Do dự kịch tính hoặc hơi thở
- **Ngắt dòng = Chuyển Suy nghĩ** — Lớp cảm xúc mới
- **Câu Không hoàn chỉnh = Hợp lệ** — Độc thoại nội tâm chân thực

---

## MỤC 5: TÍCH HỢP VỚI CÁC LỚP LN VN-Translator

### 5.1 KHI NÀO SỬ DỤNG LÀM GIÀU CẢM GIÁC
| Phạm vi RTAS | Mức Sử dụng | Kỹ thuật |
|-----------|---|---|
| < 2.0 | None | Avoid; stick to literal |
| 2.0–3.0 | Light | Soft reduplicatives, mild fragments |
| 3.0–3.5 | Moderate | Sensory verbs, onomatopoeia selection |
| 3.5–4.8 | Heavy | Slang injection, aggressive fragmentation |
| ≥ 4.8 | Maximum | All techniques, poetic embellishment, boldness |

### 5.2 PHỐI HỢP VỚI CÁC MODULE KHÁC

**Với Boldness Module (02):**
- Sensory verbs amplify B-2 (Vivid Verb Replacement)
- Slang injection aligns with B-3 (Slang Injection)
- Fragmentation enables B-1 (Sentence Shattering)

**Với Hệ thống Xưng hô (01):**
- Sensory richness does NOT override PAIR_ID
- Tender reduplicatives support intimate PAIR_IDs
- Harsh words support distant PAIR_IDs

**Với Localization Primer (00):**
- SFX tables coordinate with Section 3.2
- Slang aligns with Section 3.4 (Net Slang)
- Archetype voices may limit certain SFX

---

## MỤC 6: CHECKLIST TỰ KIỂM TRA

**Trước khi hoàn thiện mỗi đoạn văn cảm xúc cao, xác minh:**

```
✅ Weak Verb Check: Did I replace any "ngồi/nói/chạy/khóc" with sensory alternatives?

✅ Reduplicative Count: Are there 2-3+ reduplicative words (phịch, khúc khích, rúc rích, etc.)?

✅ Onomatopoeia Check: Did I include natural SFX (tim đập, tút tút, phụt)?

✅ Slang Consistency: If I used Gen Z terms, do they match character voice from previous chapters?

✅ Fragmentation Validation: Are high-emotion sentences broken into 2-3 units?

✅ Rhythm Test: Does it "feel" Vietnamese? Could a teen say this at a coffee shop?

✅ Fidelity Floor: Did meaning stay 100% aligned with source? No new plot points invented?
```

---

## MỤC 7: THAM CHIẾU NHANH (SẴN SÀNG SAO CHÉP-DÁN)

### Động từ Được sử dụng Nhiều nhất (Cảnh Cảm xúc Cao)
- Phịch (sit) | Sà (sink) | Lao (rush) | Phóng (dash) | Khúc khích (laugh)
- Nặng trĩu (heavy) | Rã rời (limp) | Phát khóc (cry) | Hét (shout)

### Từ láy Được sử dụng Nhiều nhất
- Khúc khích | Rúc rích | Khanh khách | Run bần bật | Rùng mình
- Nặng trĩu | Lả lơi | Ỉu xìu | Lạnh toát | Tim đập thình thịch

### Tiếng lóng Được sử dụng Nhiều nhất (Theo Cường độ)
- **Level 1 (Casual):** Chứ, nhỉ, nha, mà
- **Level 2 (Mild Shock):** Vãi, ảo thật đấy, xong đời
- **Level 3 (Extreme):** Toang rồi, vãi chưởng, cứu tôi

---

**KẾT THÚC MODULE**

**TRẠNG THÁI:** THAM CHIẾU CÓ THẨM QUYỀN CHO TỪ VỰNG CẢM GIÁC
**SỬ DỤNG:** Trỏ Master Prompt Mục 1.6 đến module này cho tất cả ví dụ
**TÍCH HỢP:** Hoạt động với 00_LOCALIZATION_PRIMER (SFX), Ref_BOLDNESS_MODULE_v1.0 (kỹ thuật), 01_PRONOUN_SYSTEM (phối hợp PAIR_ID)

---

<a name="6-long-vowel-romanization"></a>
# 6. Long Vowel Romanization


---
**Ref_LONG_VOWEL_ROMANIZATION.md — HƯỚNG DẪN PHIÊN ÂM NGUYÊN ÂM DÀI TIẾNG NHẬT**
**Trạng thái Module:** HOẠT ĐỘNG & UỶ QUYỀN
**Mục đích:** Phiên âm chính xác nguyên âm dài tiếng Nhật trong tên và thuật ngữ
---

# 07_LONG_VOWEL_ROMANIZATION

## PHẦN 1: CƠ BẢN VỀ NGUYÊN ÂM DÀI

### 1.1 NGUYÊN ÂM DÀI LÀ GÌ?

Trong tiếng Nhật, nguyên âm dài (長音, chōon) kéo dài thời lượng của một âm nguyên âm. Chúng rất quan trọng để phiên âm tên chính xác và phải được bảo tồn để duy trì tính xác thực.

**Các mẫu nguyên âm dài phổ biến:**
- **おう (ou)** → Phiên âm thành **-ou** (ví dụ: みどう → Midou, こうじ → Kouji)
- **おお (oo)** → Phiên âm thành **-oo** (ví dụ: おおの → Oono, とおる → Tooru)
- **えい (ei)** → Phiên âm thành **-ei** (ví dụ: けいこ → Keiko, せんせい → sensei)
- **いい (ii)** → Phiên âm thành **-ii** (ví dụ: にいな → Niina)
- **うう (uu)** → Phiên âm thành **-uu** (ví dụ: ゆうき → Yuuki)

---

### 1.2 HỆ THỐNG ƯU TIÊN CHO PHIÊN ÂM

**ƯU TIÊN 1: Ruby Text (Furigana)**
- Nếu có ruby text trong nguồn, **tuân theo chính xác**
- Ruby text đại diện cho ý định phiên âm của tác giả
- Ví dụ: Nếu 御堂 có ruby みどう, phiên âm thành **Midou** (không phải Mido)

**ƯU TIÊN 2: Chính tả Katakana**
- Đối với tên katakana, tuân theo katakana chính xác
- ミドウ → **Midou**, ミド → **Mido**

**ƯU TIÊN 3: Quy tắc phiên âm chuẩn**
- Khi không có ruby/katakana, áp dụng phiên âm Hepburn chuẩn
- Bảo tồn nguyên âm dài bằng định dạng **-ou/-oo/-ei/-ii/-uu**

---

## PHẦN 2: QUY TẮC PHIÊN ÂM THEO LOẠI NGUYÊN ÂM

### 2.1 MỞ RỘNG NGUYÊN ÂM O (Phổ biến nhất)

#### **Mẫu: おう (ou)**
**Quy tắc:** Phiên âm thành **-ou** (bắt buộc, KHÔNG dùng macron -ō)

**Tên phổ biến:**
- みどう (御堂) → **Midou** (không phải Mido hoặc Midō)
- こうじ (浩二) → **Kouji** (không phải Koji hoặc Kōji)
- そうた (颯太) → **Souta** (không phải Sota hoặc Sōta)
- りょう (涼) → **Ryou** (không phải Ryo hoặc Ryō)

**Tại sao CHỈ dùng -ou:**
- ✅ Dễ gõ và hiển thị trên mọi thiết bị (không cần ký tự đặc biệt)
- ✅ Hướng dẫn phát âm rõ ràng và chính xác
- ✅ Consistency: Một chuẩn duy nhất cho toàn bộ hệ thống
- ❌ Macron (-ō) gây khó đọc và không đồng nhất với tiêu chuẩn Hepburn modified

#### **Mẫu: おお (oo)**
**Quy tắc:** Phiên âm thành **-oo** (bắt buộc, KHÔNG dùng macron -ō)

**Tên phổ biến:**
- おおの (大野) → **Oono** (không phải Ono hoặc Ōno)
- とおる (徹) → **Tooru** (không phải Toru hoặc Tōru)
- もも (桃) → **Momo** (đã có double-o)

---

### 2.2 MỞ RỘNG NGUYÊN ÂM E

#### **Mẫu: えい (ei)**
**Quy tắc:** Phiên âm thành **-ei** (bảo tồn cả hai ký tự)

**Tên phổ biến:**
- けいこ (恵子) → **Keiko** (không phải Keko)
- れいな (玲奈) → **Reina** (không phải Rena)
- せいじ (誠司) → **Seiji** (không phải Seji)

**Ngoại lệ:** Từ phổ biến như せんせい (sensei) giữ **-ei**

---

### 2.3 MỞ RỘNG NGUYÊN ÂM I

#### **Mẫu: いい (ii)**
**Quy tắc:** Phiên âm thành **-ii** (double-i)

**Tên phổ biến:**
- にいな (新奈) → **Niina** (không phải Nina)
- しいな (椎名) → **Shiina** (không phải Shina)

---

### 2.4 MỞ RỘNG NGUYÊN ÂM U

#### **Mẫu: うう (uu)**
**Quy tắc:** Phiên âm thành **-uu** (double-u)

**Tên phổ biến:**
- ゆうき (勇気) → **Yuuki** (không phải Yuki)
- りゅう (竜) → **Ryuu** (không phải Ryu)
- しゅう (秋) → **Shuu** (không phải Shu)

---

## PHẦN 3: ỨNG DỤNG THỰC TẾ

### 3.1 QUY TRÌNH PHÁT HIỆN

**Bước 1: Kiểm tra Ruby Text**
```
Nguồn: 御堂<ruby>みどう</ruby>
Hành động: Sử dụng ruby → **Midou**
```

**Bước 2: Kiểm tra chính tả Katakana**
```
Nguồn: ミドウ・トモヤ
Hành động: Tuân theo katakana → **Midou Tomoya**
```

**Bước 3: Phân tích Hiragana/Kanji**
```
Nguồn: みどう (không có ruby)
Hành động: Áp dụng quy tắc chuẩn → **Midou**
```

---

### 3.2 QUY TẮC NHẤT QUÁN

**Quy tắc 1: Một khi đã thiết lập, khóa lại**
- Lần xuất hiện đầu tiên thiết lập phiên âm cho toàn bộ tác phẩm
- Ví dụ: Nếu "Midou" xuất hiện ở Chương 1, sử dụng "Midou" xuyên suốt

**Quy tắc 2: Đăng ký tên nhân vật**
- Duy trì đăng ký tinh thần của tất cả tên nhân vật
- Đảm bảo nhất quán qua các chương

**Quy tắc 3: Chỉ dùng phong cách chuẩn**
- **LUÔN LUÔN** dùng **-ou/-oo/-ei/-ii/-uu** (Hepburn modified)
- **KHÔNG BAO GIỜ** dùng macron **-ō/-ē** (không tương thích)
- Đảm bảo 100% consistency trong toàn bộ tác phẩm

---

### 3.3 LỖI PHỔ BIẾN CẦN TRÁNH

❌ **SAI:** Bỏ nguyên âm dài hoàn toàn
```
みどう → Mido (SAI)
こうじ → Koji (SAI)
```

✅ **ĐÚNG:** Bảo tồn nguyên âm dài
```
みどう → Midou (ĐÚNG)
こうじ → Kouji (ĐÚNG)
```

❌ **SAI:** Phiên âm không nhất quán
```
Chương 1: Midou
Chương 2: Mido (KHÔNG NHẤT QUÁN)
```

✅ **ĐÚNG:** Nhất quán đã khóa
```
Chương 1: Midou
Chương 2: Midou (NHẤT QUÁN)
```

---

## PHẦN 4: TRƯỜNG HỢP ĐẶC BIỆT

### 4.1 TÊN GHÉP

**Quy tắc:** Phiên âm từng thành phần riêng biệt, sau đó kết hợp

**Ví dụ:**
- 御堂友也 (みどう ともや)
  - 御堂 (みどう) → Midou
  - 友也 (ともや) → Tomoya
  - **Kết quả: Midou Tomoya**

---

### 4.2 TÊN LỊCH SỬ/TRUYỀN THỐNG

**Quy tắc:** Một số tên truyền thống có phiên âm đã được thiết lập

**Ví dụ:**
- 東京 (とうきょう) → **Tokyo** (không phải Toukyou, quy ước đã thiết lập)
- 大阪 (おおさか) → **Osaka** (không phải Oosaka, quy ước đã thiết lập)

**Đối với Tên Nhân Vật:** Tuân theo quy tắc chuẩn trừ khi tên là nhân vật lịch sử nổi tiếng

---

### 4.3 KHI RUBY TEXT XUNG ĐỘT VỚI QUY TẮC CHUẨN

**Ưu tiên:** Ruby text LUÔN LUÔN thắng

**Ví dụ:**
```
Kanji: 御堂
Cách đọc chuẩn: みどう (Midou)
Ruby text: みど (Mido)
Hành động: Sử dụng **Mido** (tuân theo ruby)
```

**Lý do:** Ruby text của tác giả đại diện cho ý định sáng tạo của họ

---

## PHẦN 5: BẢNG THAM KHẢO NHANH

| Tiếng Nhật | Romaji | Tên ví dụ | Dịch |
|------------|--------|-----------|------|
| おう | -ou | こうじ | Kouji |
| おお | -oo | おおの | Oono |
| えい | -ei | けいこ | Keiko |
| いい | -ii | にいな | Niina |
| うう | -uu | ゆうき | Yuuki |
| そう | sou | そうた | Souta |
| とう | tou | とうや | Touya |
| のう | nou | のうみ | Noumi |
| ほう | hou | ほうじ | Houji |
| もう | mou | もうり | Mouri |
| よう | you | ようこ | Youko |
| ろう | rou | ろうた | Routa |

---

## PHẦN 6: DANH SÁCH KIỂM TRA TRIỂN KHAI

### 6.1 DANH SÁCH KIỂM TRA TRƯỚC DỊCH

- [ ] Quét nguồn cho tất cả tên nhân vật
- [ ] Kiểm tra ruby text ở lần xuất hiện đầu tiên
- [ ] Ghi chú chính tả katakana nếu được cung cấp
- [ ] Tạo đăng ký tên nhân vật
- [ ] Khóa phiên âm cho mỗi nhân vật

### 6.2 TRONG QUÁ TRÌNH DỊCH

- [ ] Áp dụng quy tắc nguyên âm dài nhất quán
- [ ] Tham chiếu chéo với đăng ký nhân vật
- [ ] Đánh dấu bất kỳ trường hợp mơ hồ nào để xem xét
- [ ] Duy trì định dạng -ou/-oo/-ei/-ii/-uu

### 6.3 XEM XÉT SAU DỊCH

- [ ] Xác minh tất cả tên khớp với lần xuất hiện đầu tiên
- [ ] Kiểm tra việc bỏ nguyên âm vô tình
- [ ] **Đảm bảo KHÔNG có macron (-ō/-ē) trong toàn bộ output**
- [ ] Xác thực với ruby text nếu có
- [ ] Verify 100% sử dụng -ou/-oo/-ei/-ii/-uu format

---

## PHẦN 7: VÍ DỤ TỪ LIGHT NOVEL THỰC TẾ

### Ví dụ 1: "I Became Friends With The Second Cutest Girl"
```
Nhân vật: 御堂友也
Ruby: みどう ともや
Phiên âm: **Midou Tomoya**
Lý do: Ruby text hiển thị みどう (nguyên âm dài có mặt)
```

### Ví dụ 2: Generic Fantasy LN
```
Nhân vật: 剣士・光二
Ruby: けんし・こうじ
Phiên âm: Kenshi **Kouji**
Lý do: こうじ có nguyên âm dài (mẫu ou)
```

### Ví dụ 3: School Romance LN
```
Nhân vật: 白洲結花
Ruby: しらす ゆいか
Phiên âm: Shirasu **Yuika**
Lý do: ゆいか không có nguyên âm dài (phiên âm chuẩn)
```

---

## PHẦN 8: NHẮC NHỞ QUAN TRỌNG

🔴 **KHÔNG BAO GIỜ bỏ nguyên âm dài mà không có lý do ruby text rõ ràng**

🔴 **LUÔN LUÔN ưu tiên ruby text hơn phiên âm chuẩn**

🔴 **DUY TRÌ nhất quán qua tất cả các chương**

🔴 **KHÓA phiên âm ở lần xuất hiện nhân vật đầu tiên**

---

## PHẦN 9: CHUYỂN ĐỔI TRAILING SOUNDS (ÂM KÉO DÀI CUỐI CÂU)

### 9.1 TỔNG QUAN

Trong tiếng Nhật, nhân vật thường kéo dài âm cuối để thể hiện cảm xúc (nhõng nhẽo, nũng nịu, mệt mỏi, phấn khích...). Những âm này thường được viết bằng hiragana nhỏ hoặc ký tự kéo dài.

**MỤC TIÊU:** Chuyển đổi trailing sounds từ format `text ぇ (ee)` thành format tự nhiên Việt Nam `texttt` hoặc `texteee`.

---

### 9.2 BẢNG CHUYỂN ĐỔI TRAILING SOUNDS

| JP Trailing | Romaji | Chuyển thành VN | Ví dụ JP | Ví dụ VN |
|-------------|--------|-----------------|----------|----------|
| **ぁ / ァ** | aa | Kéo dài nguyên âm cuối | nha ぁ | nhaa / nhaaa |
| **ぃ / ィ** | ii | Kéo dài nguyên âm cuối | đi ぃ | điii |
| **ぅ / ゥ** | uu | Kéo dài nguyên âm cuối | sao ぅ | saooo |
| **ぇ / ェ** | ee | Kéo dài nguyên âm cuối | Nè ぇ | Nèee |
| **ぉ / ォ** | oo | Kéo dài nguyên âm cuối | alo ぉ | alooo |
| **ー** | (kéo dài) | Kéo dài nguyên âm/phụ âm cuối | nha ー | nhaaa |
| **～** | (wave) | Kéo dài nguyên âm cuối | nè ～ | nèee～ |

---

### 9.3 QUY TẮC CHUYỂN ĐỔI

#### **QUY TẮC 1: Xác định nguyên âm cuối của từ Việt**

```
Từ VN kết thúc bằng: a, e, ê, i, o, ô, ơ, u, ư, y
                       ↓
Kéo dài nguyên âm đó 2-3 lần
```

#### **QUY TẮC 2: Số lần kéo dài**

- **1 trailing mark:** Kéo dài 2 lần (ee, aa)
- **2+ trailing marks hoặc ー:** Kéo dài 3 lần (eee, aaa)
- **Kết hợp với ～:** Giữ ～ ở cuối

#### **QUY TẮC 3: Xử lý tên riêng**

```
Touya ぁ → Touyaaa (kéo dài 'a' cuối)
Mei ぇ → Meiii (kéo dài 'i' cuối)
```

---

### 9.4 VÍ DỤ THỰC TẾ - ICL (In-Context Learning)

#### **❌ SAI (Giữ nguyên format ruby):**
```
「Nè ぇ (ee) Touya ぁ (aa), mua kem cho chị đi ぃ (ii). 
Nhớ chạy nhanh đó nha ぁ (aa).」
```

#### **✅ ĐÚNG (Chuyển thành VN tự nhiên):**
```
「Nèee Touyaaa, mua kem cho chị điii. 
Nhớ chạy nhanh đó nhaaa.」
```

---

#### **Ví dụ chi tiết:**

| Nguyên văn JP | SAI (Giữ ruby) | ĐÚNG (VN tự nhiên) |
|---------------|----------------|-------------------|
| 「ねぇ ねぇ」 | "Nè ぇ Nè ぇ" | "Nèee nèee" |
| 「お願いぃ」 | "Làm ơn đi ぃ" | "Làm ơn điii" |
| 「ありがとうぅ」 | "Cảm ơn ぅ" | "Cảm ơnnn" hoặc "Cảm ơn nhaaa" |
| 「えー」 | "Hả ー" | "Hảaa" hoặc "Ơơơ" |
| 「むりむり～」 | "Không không ～" | "Khônggg khônggg～" |
| 「行くよー」 | "Đi thôi ー" | "Đi thôiii" hoặc "Đi thôi nàooo" |

---

### 9.5 XỬ LÝ CẢM XÚC QUA TRAILING SOUNDS

| Cảm xúc | Pattern JP | Cách dịch VN |
|---------|-----------|--------------|
| **Nhõng nhẽo** | ぁ/ぃ kéo dài | Kéo dài nguyên âm + ngữ điệu mềm |
| **Phấn khích** | ー/～ nhiều | Kéo dài + thêm dấu chấm than |
| **Mệt mỏi** | ぁ nhẹ | Kéo dài nhẹ (2 lần) |
| **Van nài** | ぃ/ぇ | Kéo dài + ngữ điệu năn nỉ |
| **Bất ngờ** | えー | "Hảaa!?" hoặc "Ơơơ!?" |

---

### 9.6 ICL EXAMPLES CHO GEMINI

**[ICL_TRAILING_SOUND_01]**
```
INPUT: 「ねぇ とうやぁ、アイス買ってきてぇ」
OUTPUT_SAI: "Nè ぇ (ee) Touya ぁ (aa), mua kem đi ぇ (ee)"
OUTPUT_ĐÚNG: "Nèee Touyaaa, mua kem điii"
GIẢI THÍCH: Trailing sounds được chuyển thành nguyên âm kéo dài tự nhiên
```

**[ICL_TRAILING_SOUND_02]**
```
INPUT: 「えー、むりむりー！」
OUTPUT_SAI: "Ơ ー (ee), không được không được ー!"
OUTPUT_ĐÚNG: "Ơơơ, không đượccc không đượccc!"
GIẢI THÍCH: ー kéo dài âm cuối, thể hiện sự phản đối/than vãn
```

**[ICL_TRAILING_SOUND_03]**
```
INPUT: 「ありがとぅ～」
OUTPUT_SAI: "Cảm ơn ぅ (uu) ～"
OUTPUT_ĐÚNG: "Cảm ơnnn～" hoặc "Cảm ơn nhaaa～"
GIẢI THÍCH: Kéo dài âm cuối + giữ ～ để thể hiện ngữ điệu nhẹ nhàng
```

**[ICL_TRAILING_SOUND_04]**
```
INPUT: 「お兄ちゃぁん」
OUTPUT_SAI: "Anh trai ぁ (aa) ん"
OUTPUT_ĐÚNG: "Anh traiiii" hoặc "Anh ơiiii"
GIẢI THÍCH: Kéo dài nguyên âm cuối để thể hiện nhõng nhẽo
```

---

### 9.7 DANH SÁCH KIỂM TRA

- [ ] Phát hiện trailing sounds (ぁぃぅぇぉ, ー, ～)
- [ ] Xác định nguyên âm cuối của từ VN tương ứng
- [ ] Kéo dài nguyên âm 2-3 lần tùy cường độ
- [ ] Loại bỏ hoàn toàn format ruby `ぁ (aa)`
- [ ] Giữ ～ nếu có (thể hiện ngữ điệu)
- [ ] Kiểm tra tự nhiên khi đọc

---

### 9.8 LƯU Ý QUAN TRỌNG

🔴 **KHÔNG BAO GIỜ** output dạng `text ぁ (aa)` - đây là format raw, không phải bản dịch hoàn chỉnh

🔴 **LUÔN LUÔN** chuyển đổi thành dạng tự nhiên VN với nguyên âm kéo dài

🔴 **NGUYÊN TẮC:** Người đọc VN phải có thể đọc thoải mái mà không gặp ký tự lạ

🔴 **MỤC TIÊU:** Bản dịch phải "nghe" được đúng ngữ điệu mà tác giả muốn truyền tải

---

**KẾT THÚC MODULE**

---

**END OF MEGA_VOCABULARY_DATABASE.md**
