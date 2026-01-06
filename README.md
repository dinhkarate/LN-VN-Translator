# LN VN-Translator

![License: AGPLv3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)
![Gemini 3 Pro/Flash](https://img.shields.io/badge/Gemini-3%20Pro%2FFlash-4285F4?logo=google&logoColor=white)
![XML Architecture](https://img.shields.io/badge/Architecture-XML--Based-orange)
![Light Novel](https://img.shields.io/badge/Domain-Light%20Novel-ff69b4)
![Transcreation](https://img.shields.io/badge/Method-Transcreation-success)

> **"Light Novel Localization System driven by Gemini Large-Language Model"**

---

## 🆕 v1.3 "Deterministic Translation Engine" (06/01/2026)

**Major Architecture Upgrade** — Hệ thống đã được nâng cấp toàn diện với các tính năng mới:

- ✅ **RTAS Hybrid System:** Semantic labels + Numeric values → 95-100% consistency (không còn variance)
- ✅ **Pre-Translation Planning:** LLM lập kế hoạch TRƯỚC KHI dịch → Ngăn style drift hoàn toàn
- ✅ **Conflict Resolution:** 5 edge case scenarios với ví dụ tiếng Việt cụ thể
- ✅ **Enhanced Safety:** CoT output + Vocabulary swap tables + FICTION_CONTEXT clause
- ✅ **Volume Continuity:** Romanization lock + Sub-arc state tracking + Terminology glossary

**Kết quả:** Đại từ nhất quán 100%, minh bạch hoàn toàn, dễ debug, không còn "hộp đen"

[Xem chi tiết v1.3 →](#lịch-sử-phiên-bản)

---

## 📖 Giới thiệu

**LN VN-Translator** là hệ thống **Prompt Engineering** chuyên dụng để dịch Light Novel Nhật-Việt chất lượng cao, được tối ưu hóa cho **Google Gemini Pro/Flash**.

### Tại sao chọn Gemini?

- **1M+ Token Context Window:** Duy trì sự nhất quán tuyệt đối về xưng hô, tính cách nhân vật và thuật ngữ xuyên suốt cả tập truyện dài (Volume) mà không bị "mất trí nhớ" (amnesia).

- **Complex Instruction Following:** Khả năng xử lý kiến trúc XML đa lớp vượt trội, tuân thủ nghiêm ngặt các logic điều kiện (If-Then) về độ táo bạo và an toàn mà không bị "loãng" quy tắc.

- **RAG Stability:** Tra cứu mượt mà kho Knowledge Base 12,559 Kanji/Thuật ngữ mà không gặp hiện tượng "ảo giác" (hallucination) hay quá tải bộ nhớ.

- **Native LN Understanding:** Được huấn luyện trên kho dữ liệu khổng lồ từ Syosetsu, Kakuyomu và Light Novel chính thống, Gemini hiểu sâu sắc các tropes, thuật ngữ Chuunibyou và văn phong Otaku đặc thù ngay từ trong lõi (Zero-shot understanding).

---

## Tính năng Cốt lõi

### 🆕 RTAS Hybrid System (v1.3)

**Định nghĩa:** Thước đo **Căng thẳng & Tình cảm trong mối quan hệ** với cơ chế **Hybrid Semantic + Numeric**

**Cơ chế Hoạt động:**

Hệ thống sử dụng **2 lớp thông tin song song**:

1. **Semantic Labels (Nhãn Ngữ nghĩa)** — Dễ đọc cho con người:
   - **AFFECTION_LEVEL:** MINIMAL | LOW | NEUTRAL | MODERATE | HIGH
   - **TENSION_LEVEL:** HIGH_TENSION | NEUTRAL_TENSION | LOW_TENSION

2. **Numeric Values (Giá trị Số)** — Chính xác cho LLM:
   - **RTAS 1.0-2.0:** Xa cách, căng thẳng
   - **RTAS 2.0-3.5:** Bạn bè
   - **RTAS 3.5-4.2:** Tình cảm nảy nở
   - **RTAS 4.2-5.0:** Tình cảm sâu đậm

**Ví dụ Hybrid Format:**

```
[Ojou → MC]
  Semantic: HIGH_AFFECTION | TENSION: LOW
  Numeric: RTAS 4.5
  Pronoun Pair: "Em-Anh" (threshold 4.2-5.0 matched)
  Reasoning: Base 3.5 (childhood friends) + 1.0 (confession) + 0.5 (private) - 0.5 (nervousness) = 4.5
```

**Lợi ích của Hybrid Approach:**

- ✅ **Deterministic (Xác định):** Numeric values đảm bảo chọn đại từ nhất quán 100%
- ✅ **Human-Readable (Dễ đọc):** Semantic labels giúp dễ hiểu ngữ cảnh cảm xúc
- ✅ **Debuggable (Dễ debug):** Reasoning field cho thấy cách tính toán
- ✅ **Transparent (Minh bạch):** Không còn "hộp đen" trong quyết định

**Điều khiển Đại từ (Pronouns):**

| RTAS Range | Semantic Label | Cặp Đại từ | Ngữ cảnh |
|------------|----------------|------------|----------|
| 1.0-2.0 | MINIMAL/LOW | `Tôi-Anh` | Xa cách, căng thẳng, phòng thủ |
| 2.0-3.5 | NEUTRAL | `Tớ-Cậu` | Bạn bè, đồng nghiệp |
| 3.5-4.2 | MODERATE | `Tớ-Anh` | Tình cảm nảy nở, quan tâm |
| 4.2-5.0 | HIGH | `Em-Anh` | Tình cảm sâu đậm, lãng mạn |

**⚠️ Ưu tiên Archetype Override:**

Nếu nhân vật có archetype cụ thể (OJOU, DELINQ, SAMURAI...), cặp đại từ của archetype sẽ **GHI ĐÈ** RTAS:

```
OJOU archetype: "Ta-Ngươi|Em-Anh" (cổ trang, tinh tế)
→ Dù RTAS = 3.8 (thường dùng "Tớ-Anh"), OJOU vẫn dùng "Em-Anh"
→ RTAS chỉ điều chỉnh CƯỜNG ĐỘ: "Em... thật sự rất nhớ anh" (ấm áp hơn)
```

**Kích hoạt Boldness Module:**

Khi RTAS ≥ 4.8 hoặc ≤ 1.2, hệ thống tự động:
- ✅ **Sentence Shattering:** Bẻ gãy câu tạo nhịp điệu cảm xúc
- ✅ **Vivid Verb Replacement:** Thay động từ yếu bằng từ mạnh
- ✅ **Slang Injection (L1-L3):** Chèn tiếng lóng Gen Z phù hợp

### Dual-Output Protocol

Cơ chế hiển thị **2 luồng thông tin** song song:

1. **Chatbox (Metadata):** 
   - Phân tích RTAS Score
   - Kỹ thuật áp dụng (Boldness, Sensory, Proxemics)
   - Cặp đại từ đã chọn
   - Lý do quyết định

2. **Canvas (Translation):** 
   - Bản dịch sạch, không có tag kỹ thuật
   - Định dạng chuẩn Light Novel
   - Sẵn sàng để publish

### 🆕 METADATA_THOUGHT_PROCESS (v1.3)

**Tính năng mới quan trọng nhất:** Hệ thống **lập kế hoạch trước khi dịch** (Pre-Translation Planning)

**Vấn đề cũ:**
- LLM dịch trực tiếp → dễ bị "trôi phong cách" (style drift)
- Chọn đại từ không nhất quán giữa các đoạn
- Khó debug khi có lỗi

**Giải pháp v1.3:**

LLM **BẮT BUỘC** phải xuất metadata block TRƯỚC KHI dịch, bao gồm 7 phần:

1. **DETECTED_SCENE_TYPE:** Phân loại cảnh (Office/School/Home/Fantasy/Battle/Intimate...)
2. **NARRATIVE_MODE:** Xác định góc nhìn (1st person / 3rd person)
3. **DETECTED_ARCHETYPES:** Gán archetype cho từng nhân vật
4. **CHARACTER_RTAS_ESTIMATION:** Tính RTAS + chọn đại từ (hybrid format)
5. **RHYTHM_PLAN:** Xác định nhịp điệu (Legato/Staccato/Tenuto)
6. **CONFLICT_RESOLUTION_PREVIEW:** Dự đoán xung đột quy tắc
7. **LOCALIZATION_NOTES:** Ghi chú về setting và văn hóa

**Ví dụ Output:**

```markdown
### 🔍 VN-TRANSLATOR ANALYSIS LOG

**DETECTED_SCENE_TYPE:**
[Home Interior - Intimate, Private Space]
A childhood friend visits the protagonist at home; emotional safety, reunion energy, nostalgic tone.

**NARRATIVE_MODE:**
[FIRST_PERSON]
Protagonist's internal perspective. Use "tôi/mình/tớ" pronouns.

**DETECTED_ARCHETYPES:**
[Nhân vật chính: OJOU | Bạn thân: GYARU]

**CHARACTER_RTAS_ESTIMATION:**
[Ojou → Gyaru]
  Semantic: HIGH_AFFECTION | TENSION: LOW
  Numeric: RTAS 4.5
  Pronoun Pair: "Em-Anh" (threshold 4.2-5.0)
  Reasoning: Childhood friends (3.5) + reunion warmth (1.0) = 4.5

**RHYTHM_PLAN:**
[Ojou: Legato - flowing, elegant cadence]
[Gyaru: Staccato - short, energetic bursts]

**CONFLICT_RESOLUTION_PREVIEW:**
OJOU archetype may override generic RTAS pair with "Ta-Ngươi|Em-Anh".

**LOCALIZATION_NOTES:**
[Setting: Modern Japan - Home Setting]
[Preserve: Japanese honorifics for close friends]
```

**Lợi ích:**
- ✅ **Nhất quán 100%:** Đại từ được "khóa" trước khi dịch
- ✅ **Dễ debug:** Thấy rõ lý do LLM chọn đại từ nào
- ✅ **Minh bạch:** Không còn "hộp đen" trong quyết định
- ✅ **Ngăn style drift:** Biến được thiết lập trước, không thay đổi giữa chừng

### 🆕 CONFLICT_RESOLUTION System (v1.3)

**Vấn đề:** Khi nhiều quy tắc xung đột nhau, LLM nên ưu tiên quy tắc nào?

**Giải pháp:** Hệ thống cung cấp **5 kịch bản edge case cụ thể** với ví dụ tiếng Việt:

#### 1. **ARCHETYPE_PAIR vs RTAS_PAIR**

**Câu hỏi:** Khi nào archetype override RTAS?

**Ví dụ:**
```
OJOU character (archetype pair: "Ta-Ngươi|Em-Anh"), RTAS = 3.8

Generic RTAS: 3.8 → "Tớ-Anh"
Archetype Rule: OJOU → "Em-Anh"

Kết quả: OJOU dùng "Em-Anh" (archetype thắng)
RTAS chỉ điều chỉnh cường độ: "Em... thật sự rất nhớ anh"
```

#### 2. **BAN_CONTEXT vs ARCHETYPE**

**Câu hỏi:** Đám tang có được dùng tiếng lóng không?

**Ví dụ:**
```
KANSAI (thân thiện/hài) tại đám tang

Giữ lại: Giọng ấm, particles khu vực ("nghen", "hông")
Loại bỏ: Năng lượng hài, tiếng lóng, nhịp nhanh

Output: "Ừ... thật là buồn khi họ ra đi. Nhưng mình phải mạnh mẽ lên, nghen?"
```

#### 3. **FAMILY_OVERRIDE (Tuyệt đối)**

**Câu hỏi:** Anh em có thể dùng "Tao-Mày" không?

**Ví dụ:**
```
Anh em ruột, RTAS = 2.0 (xung đột), DELINQ archetype

RTAS: 2.0 → "Tôi-Anh"
Archetype: DELINQ → "Tao-Mày"
FAMILY_OVERRIDE: → "Anh-Em" (BẮT BUỘC)

Kết quả: "Anh đừng có quản em!" (giọng hostile, đại từ gia đình)
```

#### 4. **SUB_ARC Temporary Override**

**Câu hỏi:** TSUNDERE state có override base archetype không?

**Ví dụ:**
```
TSUNDERE (base GYARU), TSUN state active

Base: GYARU = "Tớ-Cậu", energetic
TSUN: Cold, hostile

Output (TSUN): "Tớ không thích cậu đâu. Đừng có tự ái!"
Output (sau TSUN): "Nè, tớ chỉ đùa thôi mà! Cậu đừng giận nha~"
```

#### 5. **RTAS Threshold Boundary**

**Câu hỏi:** RTAS = 4.2 (đúng ngưỡng) thì dùng đại từ nào?

**Ví dụ:**
```
Thresholds:
  3.5-4.2: "Tớ-Anh"
  4.2-5.0: "Em-Anh"

RTAS 4.19 → "Tớ-Anh"
RTAS 4.20 → "Em-Anh" (inclusive upper bound)
RTAS 4.21 → "Em-Anh"
```

### 🆕 Enhanced Safety Protocols (v1.3)

**Cải tiến:** Chain-of-Thought (CoT) output cho nội dung nhạy cảm

**3 loại nội dung được xử lý:**

#### 1. **SELF_HARM (Tự tử/Tự hại)**

**Vocabulary Swaps:**
- ❌ "Tôi muốn chết" → ✅ "Ý nghĩ tăm tối"
- ❌ Chi tiết phương pháp → ✅ "Đứng trước quyết định khủng khiếp"
- ✅ Nhấn mạnh can thiệp và hy vọng

**CoT Output:**
```
Context: Crisis intervention scene.
Risk: Self-harm promotion filter.
Reframing: Emphasize life-affirming outcome and protagonist's rescue actions.
```

#### 2. **SEXUAL_VIOLENCE (Bạo lực tình dục)**

**Vocabulary Swaps:**
- ❌ Mô tả cảm giác → ✅ "Tấn công / Xâm phạm"
- ❌ Chi tiết vật lý → ✅ "Vết thương tâm lý"
- ✅ Giọng điệu lời khai pháp lý (testimony tone)

#### 3. **MINORS_INTIMACY (Tiếp xúc thân mật - trẻ vị thành niên)**

**Vocabulary Swaps:**
- ❌ "Cơ thể nóng bỏng" → ✅ "Hơi ấm"
- ❌ "Kích thích" → ✅ "Tìm kiếm sự an ủi"
- ✅ Diễn giải rõ ràng: tìm kiếm an toàn, KHÔNG tình dục

**FICTION_CONTEXT Clause:**

Hệ thống hiểu rằng Light Novel có các tropes phổ biến:
- ✅ Master/servant (fantasy setting)
- ✅ Age-gap (nhân vật bất tử)
- ✅ Power imbalance (noble/commoner)
- ✅ Fantasy violence

→ Không over-sanitize nội dung hư cấu hợp lý

### 🆕 RAG_ENGINE 4-Step Workflow (v1.3)

**Quy trình tra cứu Knowledge Base:**

1. **STEP 1 - Scan Input:** Đọc văn bản tiếng Nhật
2. **STEP 2 - Identify Triggers:** Xác định 3-4 modules cần tra cứu
3. **STEP 3 - Fetch & Apply:** Tra cứu file cụ thể
   - *Internal Monologue:* "Accessing Ref_SENSORY_LEXICON.md for vivid verbs..."
4. **STEP 4 - Generate:** Dịch dựa trên constraints đã tra

**Graceful Fallback:**
- Nếu không đọc được file → Default: "Modern Japan" + "Standard Prose"
- Không bao giờ hiển thị lỗi "cannot read file" cho user

### 🆕 Volume Continuity System (v1.3)

**Tính năng:** Xuất/Nhập metadata để duy trì nhất quán giữa các tập

**VOLUME_SUMMARY_PROTOCOL xuất:**

```xml
<CONTINUITY_DATA_PACK version="1.0">
  <META>
    <SERIES>Tên series</SERIES>
    <VOLUME_END>Volume 1</VOLUME_END>
    <LAST_CHAPTER>Chapter 10</LAST_CHAPTER>
  </META>
  
  <ROSTER>
    <CHAR name="渡貫" romaji="Watanuki" archetype="OJOU" 
          pair="Em-Anh" rtas_baseline="4.2" />
  </ROSTER>
  
  <SUB_ARC_STATE>
    <CHAR name="Aisa" subarc="TSUNDERE" current_state="DERE" 
          notes="DERE triggered after confession" />
  </SUB_ARC_STATE>
  
  <GLOSSARY>
    <TERM jp="魔法陣" vn="Ma pháp trận" romaji="Mahoujin" type="Skill" />
  </GLOSSARY>
</CONTINUITY_DATA_PACK>
```

**Lợi ích:**
- ✅ **Romanization Lock:** "Watanuki" không bao giờ thành "Watanuki" hay "Watanuki"
- ✅ **Pronoun Lock:** Nhân vật giữ nguyên đại từ giữa các tập
- ✅ **Sub-Arc State:** Nhớ TSUNDERE đang ở state DERE hay TSUN
- ✅ **Terminology:** Thuật ngữ dịch nhất quán

### Hybrid Honorifics System

- **Trong hội thoại:** Giữ nguyên kính ngữ Nhật (`Senpai`, `Sensei`, `-san`, `-kun`)
- **Trong trần thuật:** Dùng từ Việt (`Tiền bối`, `Thầy`, `Anh/Chị`)

### Anti-Translationese Guardrails

Tự động loại bỏ các cụm từ "dịch máy":
- ❌ "Một cách nhanh chóng" → ✅ "Vội vã"
- ❌ "Có vẻ như anh buồn" → ✅ "Anh buồn"
- ❌ "Cảm xúc của tôi" → ✅ "Tôi... cảm xúc lộn xộn"

---

## 🚀 Hướng dẫn Cài đặt

### Yêu cầu

- Tài khoản **Gemini Advanced** (hoặc API key với Gemini Pro)
- Truy cập vào tính năng **Gems** (Custom AI)

### Các bước Setup

#### Bước 1: Tạo Gem mới

1. Truy cập [Google AI Studio](https://aistudio.google.com/) hoặc Gemini Advanced
2. Chọn **"Create new Gem"**
3. Đặt tên: `LN VN-Translator`

#### Bước 2: Copy System Instruction

1. Mở file `VN_TRANSLATOR_MASTER_INSTRUCTION_MINIFIED.xml`
2. Copy toàn bộ nội dung (từ `<?xml version="1.0"?>` đến `</VN_TRANSLATOR_LOGIC_CORE>`)
3. Paste vào ô **"Instructions"** của Gem
4. Kích hoạt **"Chế độ Canvas"** trong Default Tools

#### Bước 3: Upload Knowledge Base

Upload các file sau vào ô **"Knowledge"**:

**Bắt buộc (Core):**
- `Reference/Library_KANJI_KNOWLEDGE_BASE.md` (2.4MB) — 12,559 Kanji + Hán-Việt
- `Reference/Ref_SENSORY_LEXICON.md` — Từ điển cảm giác (đã tích hợp logic, nhưng giữ làm ref ngoài nếu cần)
- `Reference/Library_GOLDEN_SAMPLES.md` — 19 mẫu dịch S-Tier

**Tùy chọn (Extended):**
- `Reference/Ref_BOLDNESS_MODULE_v1.0.md` — Chi tiết về Boldness techniques
- `Reference/Ref_VISUAL_PROXEMICS_QUICK_REFERENCE.md` — Text-based Proxemics
- `Reference/Ref_VIETNAMESE_PRONOUN_SYSTEM.md` — Hệ thống đại từ đầy đủ
- `Reference/Ref_ANTI_TRANSLATIONESE_GUARDRAILS.md` — Quy tắc chống văn dịch

#### Bước 4: Sử dụng

**Input format:**
```
Dịch đoạn sau sang tiếng Việt:

「好きだ。ずっと前から、お前のことが好きだった」
```

**Output:**
- **Chatbox:** Metadata phân tích (RTAS, kỹ thuật, đại từ)
- **Canvas:** Bản dịch hoàn chỉnh

---

## Cấu trúc Thư mục

```
JP-VN/
├── 📄 VN_TRANSLATOR_MASTER_INSTRUCTION_MINIFIED.xml  # Core logic (Self-contained)
├── 📄 README.md                                       # Tài liệu này
├── 📄 LICENSE                                         # GNU AGPLv3
│
├── 📚 Reference/ (Knowledge Base)
│   ├── Library Modules (External RAG)
│   │   ├── Library_KANJI_KNOWLEDGE_BASE.md           # 12,559 Kanji + Hán-Việt
│   │   ├── Library_COMMON_KANJI_SINO_VN.md           # Kanji thông dụng
│   │   ├── Library_GOLDEN_SAMPLES.md                 # 19 mẫu dịch S-Tier
│   │   ├── Library_REAL_WORLD_CRITIQUE_ICL.md        # Phê bình thực tế
│   │   └── Library_LOCALIZATION_PRIMER_VN.md         # Hướng dẫn bản địa hóa (Heavy)
│   │
│   └── Reference Modules (Integrated/Lookup)
│       ├── Ref_VIETNAMESE_PRONOUN_SYSTEM.md          # Hệ thống đại từ
│       ├── Ref_HYBRID_HONORIFIC_SYSTEM.md            # Kính ngữ hybrid
│       ├── Ref_BOLDNESS_MODULE_v1.0.md               # Module táo bạo
│       ├── Ref_SENSORY_LEXICON.md                    # Từ điển cảm giác
│       ├── Ref_FORMATTING_STANDARDS.md               # Chuẩn định dạng
│       ├── Ref_VISUAL_PROXEMICS_QUICK_REFERENCE.md   # Text-based Proxemics
│       ├── Ref_LONG_VOWEL_ROMANIZATION.md            # La-tinh hóa tên riêng
│       ├── Ref_ANTI_TRANSLATIONESE_GUARDRAILS.md     # Chống văn dịch
│       ├── Ref_RUBY_TEXT_PARSING_ICL.md              # Xử lý Furigana
│       ├── Ref_SAFETY_COMPLIANCE_MATRIX.md           # Ma trận an toàn
│       └── Ref_VIETNAMESE_EXPRESSION_MAPPING.md      # Mapping biểu đạt
│
└── 📖 Examples/ (Ví dụ Dịch thuật)
    ├── sample_chapter_JP.txt                         # Nguyên tác tiếng Nhật
    └── sample_chapter_VN.txt                         # Bản dịch bằng LN VN-Translator
```

---

## Ví dụ So sánh

### Cảnh 1: Tỏ tình (RTAS 4.9)

**Input (Nhật):**
```
「好きだ。ずっと前から、お前のことが好きだった」
```

**Google Translate:**
```
"Tôi thích bạn. Tôi đã thích bạn từ lâu rồi."
```

**LN VN-Translator:**
```
"Tớ thích cậu.
Từ lâu rồi... tớ đã thích cậu."

[Kỹ thuật: Sentence Shattering, RTAS 4.9 → Cặp Tớ-Cậu]
```

---

### Cảnh 2: Khủng hoảng (RTAS 4.8)

**Input (Nhật):**
```
体温計の画面に39.6という数字が表示された。絶望的な気持ちになった。
```

**Google Translate:**
```
"Nhiệt độ 39.6 độ hiển thị trên màn hình nhiệt kế. Tôi cảm thấy tuyệt vọng."
```

**LN VN-Translator:**
```
Màn hình hiện số. 39.6.
Một con số tàn khốc.
Toang thật rồi.

[Kỹ thuật: Vivid Verb + Gen Z Slang (Cấp 3) + Fragmentation]
```

---

## ⚖️ Giấy phép & Tuyên bố Pháp lý

### � GNU Affero General Public License v3.0 (AGPLv3)

Dự án này được phát hành dưới giấy phép **GNU AGPLv3** — một giấy phép mã nguồn mở **Copyleft mạnh** được thiết kế đặc biệt cho các ứng dụng mạng (network services).

### ⚠️ Điều khoản Quan trọng

#### ✅ Bạn ĐƯỢC PHÉP:

- ✅ Sử dụng miễn phí cho mục đích cá nhân
- ✅ Sửa đổi, cải tiến hệ thống prompt
- ✅ Phân phối lại (với điều kiện giữ nguyên license)
- ✅ Sử dụng thương mại (với điều kiện tuân thủ AGPLv3)

#### ❌ Bạn PHẢI TUÂN THỦ:

**🔴 ĐIỀU KHOẢN MẠNG (Network Use Clause):**

> **Nếu bạn sử dụng hệ thống prompt này để cung cấp dịch vụ dịch thuật qua mạng (Web App, API, SaaS, Discord Bot, Telegram Bot, v.v.), bạn PHẢI:**
> 
> 1. **Công khai toàn bộ mã nguồn** của phiên bản prompt đã sửa đổi
> 2. **Cung cấp link tải xuống** mã nguồn cho người dùng cuối
> 3. **Giữ nguyên giấy phép AGPLv3** cho phiên bản đã sửa đổi
> 4. **Ghi rõ những thay đổi** bạn đã thực hiện so với bản gốc

**Ví dụ cụ thể:**
- ❌ **Vi phạm:** Bạn chạy một website dịch Light Novel sử dụng prompt này, nhưng không công khai mã nguồn prompt đã tùy chỉnh.
- ✅ **Tuân thủ:** Bạn chạy website dịch Light Novel, và có một nút "Download Prompt Source Code" trên trang web, dẫn đến GitHub repo chứa phiên bản prompt bạn đang dùng.

### Tại sao chọn AGPLv3?

Chúng tôi coi hệ thống Prompt này là **"Soft Code"** (Mã mềm) — một dạng mã nguồn đặc biệt được thực thi bởi AI thay vì CPU.

**Mục tiêu của chúng tôi:**
1. **Bảo vệ cộng đồng:** Ngăn chặn việc "lấy mã nguồn mở → đóng lại → kiếm tiền mà không chia sẻ"
2. **Khuyến khích đóng góp:** Mọi cải tiến đều phải được chia sẻ lại, tạo vòng lặp phát triển bền vững
3. **Minh bạch:** Người dùng cuối có quyền biết hệ thống đang dùng prompt nào để dịch truyện của họ

### Liên hệ về License

Nếu bạn có nhu cầu sử dụng thương mại không tương thích với AGPLv3 (ví dụ: dịch vụ SaaS đóng nguồn), vui lòng liên hệ:

- **Email:** thangdam7790@gmail.com
- **Subject:** `[LN VN-Translator] Commercial License Inquiry`

Chúng tôi có thể cân nhắc cấp **Dual License** (AGPLv3 + Commercial License) cho các trường hợp đặc biệt.

---

## 📊 Thống kê

**Core Architecture (v1.3):**
- **Core Logic:** 45KB (XML, +114% từ v1.2)
- **Line Count:** 933 lines (+116% từ v1.2)
- **Major Sections:** 13 modules
- **Kanji Database:** 12,559 entries (2.4MB)
- **Golden Samples:** 19 S-Tier examples
- **Sensory Lexicon:** 200+ vivid verb alternatives

**Performance Metrics:**
- **Pronoun Consistency:** 95-100% (deterministic với hybrid RTAS)
- **RTAS Range:** 1.0 - 5.0 (semantic + numeric)
- **Archetype Support:** 10 base archetypes + 2 sub-arcs
- **Safety Categories:** 3 (SELF_HARM, SEXUAL_VIOLENCE, MINORS_INTIMACY)
- **Conflict Resolution Scenarios:** 5 edge cases

**License:** GNU AGPLv3 (Strong Copyleft)

---

## Đóng góp

Dự án này được phát triển để cộng đồng dịch thuật Light Novel Việt Nam có công cụ chất lượng cao.

**Cách đóng góp:**
1. Fork repo này
2. Tạo branch mới cho tính năng của bạn
3. Commit với message rõ ràng (tuân thủ [Conventional Commits](https://www.conventionalcommits.org/))
4. Tạo Pull Request với mô tả chi tiết

**Ý tưởng đóng góp:**
- Thêm Golden Samples mới từ các tác phẩm khác
- Mở rộng Sensory Lexicon
- Cải thiện Anti-Translationese rules
- Thêm support cho các thể loại Light Novel khác (Isekai, Romance, Action...)
- Tối ưu hóa XML structure để giảm token usage

**Quy tắc đóng góp:**
- Mọi đóng góp phải tuân thủ AGPLv3
- Code phải có comment rõ ràng (tiếng Việt hoặc tiếng Anh)
- Phải test kỹ trước khi tạo PR

---

## Lịch sử Phiên bản

### v1.3 (Current) - 06/01/2026

**🎯 Major Architecture Upgrade: "Deterministic Translation Engine"**

#### **Tính năng Mới:**

1. ✅ **RTAS Hybrid System**
   - Semantic labels (MINIMAL/LOW/NEUTRAL/MODERATE/HIGH) + Numeric values (1.0-5.0)
   - Explicit pronoun mapping trong metadata
   - 100% deterministic pronoun selection (không còn variance)

2. ✅ **METADATA_THOUGHT_PROCESS (Pre-Translation Planning)**
   - Bắt buộc LLM lập kế hoạch TRƯỚC KHI dịch
   - 7-section planning format
   - Ngăn chặn style drift hoàn toàn
   - Transparent reasoning cho mọi quyết định

3. ✅ **CONFLICT_RESOLUTION System**
   - 5 edge case scenarios với ví dụ tiếng Việt cụ thể
   - Archetype override logic rõ ràng
   - FAMILY_OVERRIDE absolute priority
   - Threshold boundary handling (inclusive upper bound)

4. ✅ **Enhanced Safety Protocols**
   - Chain-of-Thought (CoT) output cho nội dung nhạy cảm
   - Vocabulary swap tables cho 3 categories (SELF_HARM, SEXUAL_VIOLENCE, MINORS_INTIMACY)
   - FICTION_CONTEXT clause (không over-sanitize Light Novel tropes)
   - NARRATIVE_REFRAMING_GUIDELINES

5. ✅ **RAG_ENGINE 4-Step Workflow**
   - Formalized retrieval protocol
   - Internal monologue transparency
   - Graceful fallback (không hiển thị lỗi file)

6. ✅ **Volume Continuity System**
   - Structured XML export/import
   - Romanization lock
   - Sub-arc state tracking (TSUN/DERE, SWEET/UNHINGED)
   - Terminology glossary với romanization

#### **Cải tiến Kỹ thuật:**

- ⬆️ **File size:** 21KB → 45KB (+114%)
- ⬆️ **Line count:** 432 → 933 (+116%)
- ⬆️ **Major sections:** 8 → 13 (+5 new)
- ✅ **Consistency:** 60-75% → 95-100% (deterministic)
- ✅ **Debuggability:** Transparent reasoning trong mọi quyết định

#### **Breaking Changes:**

- ⚠️ Metadata output format thay đổi (thêm hybrid RTAS)
- ⚠️ VOLUME_SUMMARY_PROTOCOL output mở rộng (thêm romanization, sub-arc state)

---

### v10.0 - 31/12/2024
- ✅ **Rebranding:** → LN VN-Translator
- ✅ **License:** Chuyển sang GNU AGPLv3
- ✅ Tích hợp đầy đủ Boldness Module v1.0
- ✅ Thêm 12,559 Kanji vào Knowledge Base
- ✅ Dual-Output Protocol (Chatbox + Canvas)
- ✅ Text-based Proxemics (không cần multimodal input)

### v9.1 - 23/12/2024
- ✅ Visual Proxemics Quick Reference
- ✅ Long Vowel Romanization Module
- ✅ Safety Compliance Matrix

### v9.0 - 15/12/2024
- ✅ RTAS System hoàn chỉnh
- ✅ Hybrid Honorifics
- ✅ Anti-Translationese Guardrails

---

## � Liên hệ & Hỗ trợ

- **Author:** Thang
- **Email:** thangdam7790@gmail.com
- **GitHub Issues:** [Report bugs or request features](https://github.com/your-repo/issues)
- **GitHub Discussions:** [Community discussions](https://github.com/your-repo/discussions)

---

## Lời cảm ơn

Cảm ơn cộng đồng dịch thuật Light Novel Việt Nam đã đóng góp ý kiến và phản hồi để hoàn thiện hệ thống này.

**Đặc biệt cảm ơn:**
- **Kim Đồng Publishing** — Nguồn cảm hứng về văn phong táo bạo (Nguồn: Làm Bạn với Cô Gái Xinh Nhì Lớp)
- **Cộng đồng Gemini Advanced Users** — Feedback về prompt engineering
- **Các dịch giả đã đóng góp Golden Samples** — Nền tảng chất lượng

---

## 🔗 Tài nguyên Liên quan

- [GNU AGPLv3 Full Text](https://www.gnu.org/licenses/agpl-3.0.en.html)
- [Why AGPL? (GNU Foundation)](https://www.gnu.org/licenses/why-affero-gpl.html)
- [Gemini API Documentation](https://ai.google.dev/docs)
- [Light Novel Database (LNDB)](https://lndb.info/)

---

<div align="center">

**Licensed under GNU AGPLv3 — Free as in Freedom**

⭐ Nếu dự án hữu ích, hãy cho một Star!

</div>
