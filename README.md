# Multi-Natural-Dye AI-Driven Inverse Design and Closed-Loop Optimization for Sustainable Textile Dyeing

## ชื่อโครงการวิจัยภาษาไทย

**การออกแบบสูตรย้อนกลับด้วยปัญญาประดิษฐ์และการเพิ่มประสิทธิภาพแบบวงปิดสำหรับการย้อมสิ่งทอด้วยสีธรรมชาติหลายชนิดอย่างยั่งยืน**

## English Title

**Multi-Natural-Dye AI-Driven Inverse Design and Closed-Loop Optimization for Sustainable Textile Dyeing**

---

## เกี่ยวกับโครงการ

โครงการนี้ศึกษาการประยุกต์ใช้ปัญญาประดิษฐ์สำหรับการออกแบบสูตรย้อมสีธรรมชาติแบบย้อนกลับ (inverse design) โดยเริ่มจากสีเป้าหมาย แล้วค้นหาชนิดสีธรรมชาติและเงื่อนไขการย้อมที่เหมาะสมภายใต้ข้อจำกัดด้านความคงทนและการใช้ทรัพยากร

ระบบหลักใช้สีธรรมชาติ 3 ชนิด ได้แก่

- **ไม้ฝาง (Sappanwood; *Caesalpinia sappan*)** — กลุ่มสีแดง–ส้ม
- **ขมิ้น (Turmeric; *Curcuma longa*)** — กลุ่มสีเหลือง
- **อัญชัน (Butterfly pea; *Clitoria ternatea*)** — กลุ่มสีน้ำเงิน–ม่วง

วัสดุสิ่งทอหลักคือ **ผ้าฝ้าย 100%**

กรอบการวิจัยประกอบด้วยการทดลองย้อมจริง การสร้างฐานข้อมูลจาก Design of Experiments การพัฒนา forward AI model การออกแบบสูตรย้อนกลับ การเพิ่มประสิทธิภาพแบบหลายวัตถุประสงค์ การประเมิน uncertainty การทดลองยืนยัน และการปรับแบบจำลองผ่าน closed-loop learning เมื่อมีข้อมูลใหม่หรือเมื่อเปลี่ยน raw-material lot

---

## จุดเด่นของงานวิจัย

งานนี้ไม่ได้อ้างความใหม่เพียงจากการใช้ AI หรือการใช้สีธรรมชาติหลายชนิด แต่เน้น Contribution หลัก 4 ด้าน ได้แก่

1. **Multi-natural-dye inverse design**  
   ออกแบบชนิดสีและเงื่อนไขการย้อมจากสีเป้าหมาย

2. **Uncertainty-aware closed-loop learning**  
   ใช้ความไม่แน่นอนของแบบจำลองเพื่อช่วยเลือกการทดลองใหม่ และนำผลจริงกลับไปอัปเดตระบบ

3. **Raw-material batch adaptation**  
   ประเมินความสามารถของระบบในการปรับตัวเมื่อวัตถุดิบสีธรรมชาติเปลี่ยน lot

4. **Resource-aware multi-objective optimization**  
   พิจารณาความแตกต่างของสี ความคงทน พลังงาน น้ำ mordant และเวลาร่วมกัน

---

## โครงสร้างเอกสาร

Repository นี้ประกอบด้วยเอกสาร HTML สำหรับบทที่ 1–5

```text
.
├── index.html
├── index_chapter1_latex_fixed.html
├── index_chapter2.html
├── index_chapter3_with_framework_figures.html
├── index_chapter4_with_results_figures.html
├── index_chapter5.html
└── README.md
```

### รายละเอียดแต่ละบท

| บท | เนื้อหา | ไฟล์ |
|---|---|---|
| บทที่ 1 | บทนำ ปัญหาวิจัย คำถามวิจัย วัตถุประสงค์ สมมติฐาน ขอบเขต และ Contribution | `index_chapter1_latex_fixed.html` |
| บทที่ 2 | เอกสารและงานวิจัยที่เกี่ยวข้อง ช่องว่างการวิจัย และตารางเปรียบเทียบงานเดิม | `index_chapter2.html` |
| บทที่ 3 | วิธีดำเนินการวิจัย DOE, AI modeling, inverse design, uncertainty และ closed-loop | `index_chapter3_with_framework_figures.html` |
| บทที่ 4 | ผลการวิจัย การวิเคราะห์ และอภิปรายผล พร้อม Figure 4.1–4.4 | `index_chapter4_with_results_figures.html` |
| บทที่ 5 | สรุปผล ข้อจำกัด Contribution งานในอนาคต และข้อเสนอแนะ | `index_chapter5.html` |

---

## รูปภาพสำคัญในงานวิจัย

บทที่ 3 ประกอบด้วยภาพกรอบวิธีวิจัยหลัก ได้แก่

- **Figure 1 — Overall Research Framework**
- **Figure 2 — Experimental Workflow and Dataset Construction**
- **Figure 3 — Uncertainty-Aware Inverse Design and Closed-Loop Adaptation**

บทที่ 4 ประกอบด้วยภาพผลการทดลองตัวอย่าง ได้แก่

- **Figure 4.1 — Target vs Predicted vs Experimental Color Results**
- **Figure 4.2 — Forward Model Performance and Prediction Agreement**
- **Figure 4.3 — Pareto Front for Sustainable Recipe Optimization**
- **Figure 4.4 — Closed-Loop Learning and New-Lot Adaptation**

---

## สถานะของข้อมูล

> **สำคัญ:** ผลตัวเลขในบทที่ 4 และข้อสรุปเชิงตัวเลขบางส่วนในบทที่ 5 เป็น **ข้อมูลจำลอง (simulated values)** เพื่อสาธิตรูปแบบการรายงานผล วิเคราะห์ และอภิปรายผลในงานวิจัย

ค่าดังกล่าวยังไม่ใช่ผลการทดลองจริง และต้องแทนด้วยข้อมูลจริงก่อนใช้ในการ:

- ส่งบทความวารสาร
- วิทยานิพนธ์หรือรายงานฉบับสมบูรณ์
- การนำเสนอผลการวิจัยเชิงยืนยัน
- การอ้าง claim เชิงวิทยาศาสตร์

ไฟล์ HTML แสดงคำเตือนเรื่องข้อมูลจำลองไว้ชัดเจนแล้ว

---

## เทคโนโลยีที่ใช้ในหน้าเว็บไซต์

เอกสาร HTML ถูกออกแบบเป็น static website และไม่ต้องมี backend

เทคโนโลยีหลัก ได้แก่

- HTML5
- CSS3
- JavaScript
- [Marked.js](https://marked.js.org/) สำหรับ Markdown rendering
- [KaTeX](https://katex.org/) สำหรับแสดงสมการ
- Google Fonts — Sarabun
- Responsive layout
- Printable layout สำหรับ Export PDF

บาง library ถูกโหลดผ่าน CDN ดังนั้นการเปิดไฟล์แบบ offline อาจทำให้ font หรือ KaTeX ไม่โหลด หากต้องการใช้งานแบบ offline เต็มรูปแบบ ควรดาวน์โหลด dependencies มาเก็บไว้ใน repository

---

## การเปิดใช้งานแบบ Local

สามารถเปิดไฟล์ `index.html` ด้วยเว็บเบราว์เซอร์ได้โดยตรง

อย่างไรก็ตาม เพื่อป้องกันข้อจำกัดบางอย่างของ browser แนะนำให้ใช้ local HTTP server เช่น

### Python

```bash
python -m http.server 8000
```

จากนั้นเปิด

```text
http://localhost:8000/
```

### VS Code

สามารถใช้ extension เช่น **Live Server** แล้วเปิด `index.html`

---

## การตั้งค่า GitHub Pages

GitHub Pages สามารถ publish static HTML จาก branch ที่กำหนดได้ โดย source folder สามารถเป็น root `/` หรือ `/docs` ได้

### โครงสร้างที่แนะนำ

ให้นำไฟล์สารบัญหลักมาใช้ชื่อ

```text
index.html
```

และวางทุกไฟล์ไว้ใน repository root เช่น

```text
research/
├── index.html
├── index_chapter1_latex_fixed.html
├── index_chapter2.html
├── index_chapter3_with_framework_figures.html
├── index_chapter4_with_results_figures.html
├── index_chapter5.html
└── README.md
```

### ขั้นตอนเปิด GitHub Pages

1. Push ไฟล์ทั้งหมดขึ้น GitHub
2. เปิดหน้า repository
3. ไปที่ **Settings**
4. เลือก **Pages**
5. ในส่วน **Build and deployment**
6. เลือก **Deploy from a branch**
7. เลือก branch เช่น `main`
8. เลือก folder เป็น `/ (root)`
9. กด **Save**

GitHub Pages จะใช้ไฟล์ `index.html` ที่อยู่ระดับบนสุดของ publishing source เป็นหน้าแรก

ตัวอย่าง URL สำหรับ project site:

```text
https://USERNAME.github.io/REPOSITORY/
```

เช่น หาก repository ชื่อ `research`

```text
https://USERNAME.github.io/research/
```

> ชื่อไฟล์ `index.html` ต้องเป็นตัวพิมพ์เล็กตามนี้ เพื่อหลีกเลี่ยงปัญหา 404

---

## การเปลี่ยนไฟล์สารบัญให้เป็นหน้าแรก

หากไฟล์สารบัญชื่อ

```text
index_table_of_contents.html
```

ให้เปลี่ยนชื่อเป็น

```text
index.html
```

ก่อน push ขึ้น GitHub Pages

ลิงก์ภายในแต่ละบทใช้ relative path ดังนั้นควรวางไฟล์ HTML ทั้งหมดไว้ใน folder เดียวกัน หากเปลี่ยนโครงสร้าง folder ต้องแก้ path ใน `index.html` ตามด้วย

---

## ตัวอย่าง Git Workflow

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY

git add .
git commit -m "Add research chapters and GitHub Pages site"
git push origin main
```

หาก repository มีอยู่แล้ว สามารถใช้

```bash
git status
git add .
git commit -m "Update research documentation"
git push
```

---

## Methodology Overview

Workflow หลักของงานวิจัยสามารถสรุปได้ดังนี้

```text
Natural Dye Selection
        ↓
Pilot Study
        ↓
Design of Experiments
        ↓
Controlled Dyeing Experiments
        ↓
CIELAB / K/S / Fastness / Resource Measurement
        ↓
Experimental Database
        ↓
Forward AI Model
        ↓
Uncertainty Quantification
        ↓
Inverse Design
        ↓
Multi-objective Optimization
        ↓
Experimental Validation
        ↓
Closed-loop Model Update
        ↓
New-lot Adaptation
```

---

## ตัวแปรหลักของระบบ

Input หลักประกอบด้วย

- Dye source
- Dye concentration
- Mordant concentration
- pH
- Temperature
- Dyeing time

Output หลักประกอบด้วย

- CIELAB: \(L^*, a^*, b^*\)
- Color strength: \(K/S\)
- Washing fastness
- Rubbing fastness
- Light fastness
- Energy consumption
- Water consumption

---

## แบบจำลองและวิธีที่เปรียบเทียบ

Forward models ที่ใช้ในกรอบการวิจัย ได้แก่

- Response Surface Methodology (RSM)
- Random Forest
- XGBoost
- Artificial Neural Network (ANN)

เปรียบเทียบทั้ง

- Dye-specific models
- Unified multi-dye model

Metrics หลัก ได้แก่

- MAE
- RMSE
- \(R^2\)
- \(\Delta E_{00}\)
- Fastness metrics
- Experiments-to-target
- Success rate
- Uncertainty calibration
- Pareto performance

---

## ข้อจำกัดของงาน

ขอบเขตปัจจุบันยังมีข้อจำกัด ได้แก่

- ใช้ผ้าฝ้าย 100% เป็น substrate หลัก
- ใช้ natural dyes เพียง 3 ระบบ
- ยังไม่ได้รวม chemical fingerprint เช่น HPLC หรือ LC–MS ใน model หลัก
- sustainability metrics ยังอยู่ระดับ process-level ไม่ใช่ full LCA
- external validation ยังไม่ใช่ multi-site industrial validation
- raw-material lot adaptation ยังต้องตรวจสอบด้วยผลการทดลองจริง

---

## งานในอนาคต

แนวทางต่อยอดประกอบด้วย

- เพิ่ม UV–Vis, HPLC หรือ chemical descriptors
- เพิ่ม natural dye systems
- ขยายไปยัง silk และ wool
- spectral reflectance prediction
- transfer learning / domain adaptation
- conformal uncertainty calibration
- pilot-scale และ industrial validation
- Life Cycle Assessment
- digital twin สำหรับ natural dyeing

---

## การอ้างอิงงานวิจัย

หาก repository นี้ถูกนำไปใช้เป็น supplementary research material ควรเพิ่ม citation ของบทความฉบับตีพิมพ์ภายหลัง เช่น

```bibtex
@article{author_year_natural_dye_inverse_design,
  title   = {Multi-Natural-Dye AI-Driven Inverse Design and Closed-Loop Optimization for Sustainable Textile Dyeing},
  author  = {Author Name},
  journal = {Journal Name},
  year    = {Year},
  volume  = {Volume},
  pages   = {Pages},
  doi     = {DOI}
}
```

> ส่วน citation นี้เป็น template เท่านั้น ห้ามใส่ข้อมูลวารสารหรือ DOI ที่ยังไม่ได้ตีพิมพ์จริง

---

## Data and Code Availability

สถานะปัจจุบันของ repository นี้เน้นเอกสารและ framework สำหรับงานวิจัย

ก่อนการเผยแพร่ควรกำหนดให้ชัดเจนว่า:

- experimental dataset เปิดเผยหรือไม่
- source code สำหรับ model training เปิดเผยหรือไม่
- random seeds และ model configuration มีให้หรือไม่
- raw measurements และ preprocessing scripts ถูกเก็บไว้ที่ใด
- license ของข้อมูลและ code คืออะไร

หากยังไม่เปิดเผยข้อมูลจริง ไม่ควรเขียนว่า dataset หรือ source code เป็น public

---

## License

ควรเลือก license ให้เหมาะกับวัตถุประสงค์ของ repository

ตัวอย่าง:

- **MIT License** — เหมาะกับ source code
- **Apache License 2.0** — เหมาะกับ software ที่ต้องการ patent terms
- **CC BY 4.0** — เหมาะกับเอกสารและรูปภาพทางวิชาการ
- **CC BY-NC 4.0** — กรณีต้องการจำกัดการใช้เชิงพาณิชย์

หากยังไม่ได้ตัดสินใจเรื่อง license ควรเว้นไว้ก่อน แทนการใส่ license โดยอัตโนมัติ

---

## หมายเหตุสำหรับการเผยแพร่

ก่อนเปิด repository เป็นสาธารณะ ควรตรวจสอบว่าไม่มีข้อมูลต่อไปนี้อยู่ใน repository:

- ข้อมูลส่วนบุคคล
- API keys หรือ credentials
- raw data ที่มีข้อจำกัดการเผยแพร่
- manuscript ที่อยู่ภายใต้เงื่อนไข embargo
- รูปภาพหรือ assets ที่ไม่มีสิทธิ์เผยแพร่

GitHub Pages เป็นเว็บไซต์ที่เข้าถึงได้ผ่านอินเทอร์เน็ต ดังนั้นควรตรวจสอบข้อมูลก่อน publish ทุกครั้ง

---

## Repository Purpose

Repository นี้จัดทำขึ้นเพื่อใช้เป็น:

- เอกสารประกอบงานวิจัย
- เว็บไซต์สำหรับอ่านบทที่ 1–5
- Supplementary documentation
- ตัวอย่าง framework สำหรับ AI-assisted natural textile dyeing
- ฐานสำหรับการพัฒนา manuscript และ experimental platform ต่อไป

---

## Contact

สามารถเพิ่มข้อมูลผู้วิจัยภายหลังในรูปแบบ

```text
Principal Investigator:
Institution:
Email:
ORCID:
Research Group:
```

ไม่ควรใส่ข้อมูลส่วนบุคคลที่ไม่ต้องการเผยแพร่ใน public repository

---

## Acknowledgement

ควรเพิ่มแหล่งทุน หน่วยงานสนับสนุน ห้องปฏิบัติการ หรือผู้มีส่วนร่วมเมื่อข้อมูลดังกล่าวได้รับการยืนยันแล้ว

---

**Research status:** Methodology and research-documentation development.  
**Experimental results shown in Chapter 4:** Simulated examples, not final measured results.
