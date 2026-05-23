# AISA Last-Day Verbal Drill — สรุปก่อนสอบ 24 พ.ค. 2026

## เป้าหมาย Source นี้
เนื้อหานี้ใช้สำหรับ Audio Overview ของ NotebookLM — สร้าง podcast ภาษาไทย ให้นักเรียนฟังบนรถระหว่างเดินทางไปสอบ AISA 24 พ.ค. 2026 ที่ UTCC อาคาร 7 เวลา 09:30. โทนติวเตอร์ 2 คน คุยกันสนุกๆ พูดช้าๆ ชัดๆ ย้ำซ้ำๆ ในจุดที่ trap.

---

## ส่วนที่ 1 — 7 สูตรที่นักเรียนลืม (ต้องย้ำให้แม่นที่สุด)

### 1. DDM 2-Stage Terminal Value — Sign Error (TRAP ใหญ่ที่สุด)

สูตร: Terminal Value (TV) ณ ปลาย Stage 1 = D(stable) / (k − g)

**ย้ำชัดๆ: เป็น (k ลบ g) ไม่ใช่ (k บวก g)**

เหตุผล: TV เป็น Gordon Growth Model — มาจาก perpetuity ของ dividend ที่ growth คงที่ g ตลอดไป. Formula Gordon = D₁ / (r − g). ตัวส่วนต้องเป็น discount rate ลบ growth rate. ถ้าคุณบวก จะได้ตัวเลขผิดเยอะมาก แล้วยังตอบถูก type สูตรเลย — exam จะเอาผิดประเด็นนี้

ตัวอย่างจำ: ถ้า k = 10%, g = 4% → ตัวส่วน = 6% (= 0.06) → ถ้าเผลอบวก = 14% → ค่าจะเหลือครึ่งเดียว

**Memory trick:** "ลบ" = นำ growth ออกจาก required return เพื่อให้เหลือ "net return" ที่ใช้ discount

---

### 2. FCFF Gordon Model — ต้องคูณ (1+g) ก่อน

สูตร: Firm Value = FCFF₁ / (WACC − g)

**ย้ำ: FCFF₁ ไม่ใช่ FCFF₀**

ถ้าโจทย์ให้ FCFF ปีล่าสุด (FCFF₀) = 2,000 ล้านบาท, g = 3%, WACC = 10%
→ FCFF₁ = 2,000 × (1 + 0.03) = 2,060
→ Firm Value = 2,060 / (0.10 − 0.03) = 2,060 / 0.07 = 29,428.57 ล้าน

**ถ้าเผลอใช้ FCFF₀ ตรงๆ** → ได้ 2,000 / 0.07 = 28,571 ล้าน → ผิด 857 ล้าน

**Trap signal ในโจทย์:** คำว่า "ปีที่ผ่านมา", "ล่าสุด", "current year" = FCFF₀ → ต้องคูณ (1+g)

---

### 3. DOL — Degree of Operating Leverage

สูตร: DOL = % ΔEBIT / % ΔSales

ความหมาย: ถ้า Sales เปลี่ยน 1% แล้ว EBIT จะเปลี่ยนกี่ %

**สูตรขยาย (เมื่อโจทย์ให้ contribution margin):** DOL = Contribution Margin / (Contribution Margin − Fixed Cost) = Q(P-V) / [Q(P-V) − F]

**Insight:** Fixed cost เยอะ → DOL สูง → ธุรกิจ "leverage" ขึ้น (sales เพิ่มนิด EBIT เพิ่มเยอะ) แต่ downside ก็แรงเหมือนกัน

ตัวอย่าง: บริษัท A มี DOL = 3 → Sales เพิ่ม 10% → EBIT เพิ่ม 30%

---

### 4. DFL — Degree of Financial Leverage

สูตร: DFL = % ΔEPS / % ΔEBIT

หรือ: DFL = EBIT / (EBIT − Interest)

ความหมาย: ถ้า EBIT เปลี่ยน 1% แล้ว EPS เปลี่ยนกี่ %

**Insight:** หนี้ที่มี Interest เยอะ → DFL สูง → ความเสี่ยงทางการเงินสูง

**Combined Leverage (DTL)** = DOL × DFL — วัด total risk จาก Sales ไปถึง EPS

---

### 5. NPV — Net Present Value

สูตร: NPV = Σ [CFₜ / (1+r)^t] − Initial Investment (เริ่มต้น t=1)

**Decision Rule:**
- NPV > 0 → ทำ project (สร้างมูลค่า)
- NPV < 0 → ไม่ทำ
- NPV = 0 → indifferent (return = required return พอดี)

**Trap:** ถ้าโจทย์ให้ project ที่ initial outflow = ไม่ใช่ t=0 ต้อง discount ด้วย. และต้อง consistent — discount rate ต้องเป็นรายปีถ้า CF รายปี

**Tip:** NPV vs IRR — ถ้าขัดกัน เลือก NPV (NPV rule wins สำหรับ mutually exclusive)

---

### 6. Equity Multiplier — EM = 1 + D/E (ไม่ใช่ D/E เฉยๆ)

สูตร: EM = Total Assets / Total Equity = 1 + (Debt/Equity)

**TRAP ที่นักเรียนชอบสับสน:** EM ไม่ใช่ D/E ratio! EM = 1 + D/E

ตัวอย่าง: D/E = 0.8 → EM = 1.8

**ใช้ใน DuPont:** ROE = NPM × Asset Turnover × Equity Multiplier
- NPM = Net Income / Sales
- Asset Turnover = Sales / Total Assets
- EM = Total Assets / Total Equity

**Trap จริงในข้อสอบ AISA:** เคยมีตัวเลือกที่ใช้ 10.8% (= D/E + premium) แทน EM = 18% (= 1 + 0.8) → ผิด

---

### 7. TIE — Times Interest Earned

สูตร: TIE = EBIT / Interest Expense

ความหมาย: บริษัทมีกำไร (EBIT) พอจ่ายดอกเบี้ยกี่เท่า

**Rule of thumb:**
- TIE > 3 → ปลอดภัย
- TIE < 1.5 → เริ่มเสี่ยง (กำไรแค่พอจ่ายดอก)
- TIE < 1 → จ่ายดอกไม่พอ (สัญญาณ default)

---

## ส่วนที่ 2 — Patches จาก SET Set 1 + 2 (ที่ทำผิดเมื่อวาน)

### Patch A: Equity ↑ = Credit (ไม่ใช่ "รายได้+credit")

**กฎ debit/credit:**
- Asset ↑ = Debit / Asset ↓ = Credit
- Liability ↑ = Credit / Liability ↓ = Debit
- **Equity ↑ = Credit** / Equity ↓ = Debit
- Revenue ↑ = Credit / Expense ↑ = Debit

**สาเหตุที่พลาด:** ตัวเลือกข้อสอบเขียน "รายได้ + credit" ดูถูกเพราะ revenue เป็น credit จริง — แต่ถ้าโจทย์ถาม "Equity ↑" คำตอบต้องเป็น Equity Credit ตรงๆ

---

### Patch B: FVPL → P&L (CRITICAL GAP)

**สรุป:** ตราสารที่ classify เป็น FVPL (Fair Value through Profit & Loss)
- Unrealized gain/loss → ไป **P&L (กำไรขาดทุน)** ทันที
- Realized gain/loss → ไป P&L

**เทียบกับ FVOCI:**
- Unrealized gain/loss → ไป **OCI (Other Comprehensive Income)**
- Realized → ไป P&L (reclass จาก OCI)

**Memory aid:** ชื่อ "FVPL" บอกตรงตัว — "through Profit & Loss" = ทุก gain/loss ผ่าน P&L

---

### Patch C: TFRS Interest/Dividend = Policy Choice

**กฎ:** ใต้ TFRS (IFRS) บริษัทเลือกได้ว่าจะ classify interest paid/received และ dividend paid/received ใน CF section ไหน — เป็น **accounting policy choice**

**ข้อบังคับ (ตายตัว) ของ Thai/IFRS:**
- Interest paid = Operating หรือ Financing (เลือก)
- Interest received = Operating หรือ Investing (เลือก)
- Dividend paid = Operating หรือ Financing (เลือก)
- Dividend received = Operating หรือ Investing (เลือก)

**Trap:** อย่าเลือก "Financing เท่านั้น" — ผิด เพราะเป็น choice ไม่ใช่ rule

---

### Patch D: Direction Reversal Trap (CFI sign)

**สรุปเหตุการณ์:** โจทย์บอก "บริษัทใช้เงินสด 24 ล้านลงทุนในเครื่องจักร" → ใน Cash Flow from Investing = **(24)** ล้าน — เครื่องหมายลบ เพราะ outflow

**Trap:** บอสตอน drill เลือก "ได้มา 24 ล้าน" — math ถูกหมด แต่อ่าน direction ผิด

**Ritual ก่อนตอบ CF:**
1. อ่านโจทย์ 2 รอบ — "ใช้ไป" = outflow (ลบ) / "ได้มา" = inflow (บวก)
2. ก่อนวงคำตอบ → "นี่ in หรือ out?"

---

### Patch E: HTM = Amortized Cost (ไม่ใช่ FVOCI)

**Classification ตราสารหนี้ภายใต้ IFRS 9:**
- **HTM (Held-to-Maturity / Amortized Cost):** ตั้งใจถือถึงครบกำหนด, business model = collect contractual CF → วัดที่ **Amortized Cost** — ไม่ใช่ FV, ไม่มี OCI
- **FVOCI:** business model = collect + sell → unrealized gain/loss ไป OCI
- **FVPL:** trading หรือ default → ทุก gain/loss ไป P&L

**Trap:** ข้อสอบเคยให้ตัวเลือก "HTM → ใช้ FV" → ผิด เพราะ HTM ใช้ Amortized Cost

---

### Patch F: Impairment → Denominator Overstated → Ratio Understated

**Concept:** ถ้าบริษัทไม่บันทึก impairment loss ของ asset → Total Asset ใน BS จะ overstate (สูงเกินจริง)

**ผลต่อ ratios:**
- Asset Turnover = Sales / TA → TA สูงเกิน → ratio **ต่ำเกินจริง (understated)**
- ROA = NI / TA → ratio **ต่ำเกินจริง**
- D/A = Debt / TA → ratio **ต่ำเกินจริง**

**Memory aid:** "ไม่ impair = asset อ้วน = ratios ผอม"

---

### Patch G: Reclass ≠ Addition

**Scenario:** บริษัทย้ายสัญญาเช่า 50 ล้าน จากหมวด "long-term liability" → "long-term lease liability"

**Trap:** บางคนคิดว่า Total Asset/Liability เพิ่ม 50 ล้าน → ผิด เพราะแค่ย้ายหมวด ไม่ใช่เพิ่ม

**กฎ:** Reclassification = เปลี่ยนชื่อหมวด, ตัวเลขรวม (TA/TL) ไม่เปลี่ยน

---

### Patch H: Algebra Verify Before Reject

**Scenario:** ข้อสอบให้ DuPont decomposition ในรูปไม่คุ้น เช่น "ROE = NPM × Equity Turnover" — บอสปฏิเสธเพราะไม่คุ้น

**ความจริง:**
- Equity Turnover = Sales / Equity
- NPM × Equity Turnover = (NI/Sales) × (Sales/Equity) = NI/Equity = ROE ✓

**Lesson:** ก่อน reject สูตรแปลก → ทำ algebra check (cancel term) ดูก่อนว่า reduce ลงเป็น formula มาตรฐานได้ไหม

---

## ส่วนที่ 3 — Anti-Trap Ritual ในห้องสอบ

### 3-Pass Strategy

**Pass 1 (60 นาทีแรก) — Easy Wins:**
- อ่านทุกข้อ
- ตอบเฉพาะที่มั่นใจ 90%+ ทันที (15-25 ข้อ)
- ข้อยาก/งง → mark + ข้าม ไม่จม

**Pass 2 (45 นาทีถัดมา) — Medium:**
- กลับมาทำข้อที่ mark
- ใช้ elimination (ตัด 2-3 ตัวเลือกผิดชัด → guess ฉลาด)

**Pass 3 (30 นาทีสุดท้าย) — Hard + Double-Check:**
- ทำข้อ hard ที่เหลือ
- **Re-check 5 ข้อแรก** ที่ตอบเร็วใน Pass 1 (มัก trap ตรงนี้)
- ตรวจสัญลักษณ์: บวก/ลบ, FCFF₀/FCFF₁, in/out, debit/credit

### Pre-Answer Checklist (3 วินาทีก่อนวงคำตอบ)

1. **Sign check:** บวก/ลบ ถูกไหม? (k−g ไม่ใช่ k+g)
2. **Direction check:** in/out ตรงไหม? (CFI ใช้ไป = ลบ)
3. **Period check:** FCFF₀ vs FCFF₁? Price₀ vs Price₁?
4. **Formula check:** EM = 1+D/E ไม่ใช่ D/E

### Mental Hygiene

- หายใจลึก 3 ครั้ง ก่อนเริ่ม Pass 1
- ทุก 30 นาที — มอง้องด้านไกล 5 วินาที (พักตา)
- ข้อยากที่ทำไม่ได้ — ปล่อย ไม่เครียด ไปข้อต่อ

---

## ส่วนที่ 4 — สรุปสุดท้าย (Final Charge)

7 สูตรที่ต้องท่องได้ในใจก่อนเข้าห้องสอบ:

1. TV = D / (k − **MINUS** − g)
2. Firm Value = FCFF × (1+g) / (WACC − g)
3. DOL = %ΔEBIT / %ΔSales
4. DFL = %ΔEPS / %ΔEBIT
5. NPV > 0 = accept
6. EM = **1 + D/E** (ไม่ใช่ D/E)
7. TIE = EBIT / Interest

8 patches:
A. Equity↑ = Credit
B. FVPL → P&L (ทุก gain/loss)
C. TFRS interest/dividend = policy choice
D. CF: "ใช้ไป" = outflow ลบ
E. HTM = Amortized Cost
F. ไม่ impair = ratios ผอม
G. Reclass ≠ Add
H. Algebra verify ก่อน reject

**You got this.** เตรียมมานานพอแล้ว 11 ชม. patch day เมื่อวาน + 23 formulas drill + mega guide complete = พร้อมรบ.

Pass 1 = easy. Pass 2 = elimination. Pass 3 = verify + double-check.

หายใจลึก. ปล่อยข้อยาก. เก็บข้อง่าย. ผ่านชัวร์.
