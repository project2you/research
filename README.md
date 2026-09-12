# Multi-Natural-Dye AI-Driven Inverse Design

### Closed-Loop Optimization for Sustainable Textile Dyeing

โครงการวิจัยนี้มุ่งพัฒนาระบบปัญญาประดิษฐ์สำหรับ **การออกแบบสูตรย้อมสีธรรมชาติแบบย้อนกลับ (Inverse Design)** โดยเริ่มจากสีเป้าหมาย แล้วค้นหาชนิดสีธรรมชาติและเงื่อนไขการย้อมที่เหมาะสม พร้อมเพิ่มประสิทธิภาพกระบวนการภายใต้หลายวัตถุประสงค์ และเรียนรู้จากผลการทดลองจริงแบบวงปิด

---

## Research Overview

การย้อมสีธรรมชาติมีความซับซ้อนจากความสัมพันธ์ระหว่างชนิดสี ความเข้มข้น สารช่วยติดสี pH อุณหภูมิ เวลา และความแปรปรวนของวัตถุดิบแต่ละ lot

งานวิจัยนี้จึงพัฒนากรอบ AI ที่เชื่อมโยง

**Prediction → Inverse Design → Optimization → Experiment → Adaptation**

เพื่อเปลี่ยนจากการทำนายผลของสูตรที่กำหนดไว้แล้ว ไปสู่การออกแบบสูตรจาก **Target Color** โดยตรง

---

## Natural Dye Systems

| Natural Dye | Main Pigment             | Color Range  |
| ----------- | ------------------------ | ------------ |
| ไม้ฝาง      | Brazilin / Brazilein     | แดง–ส้ม      |
| ขมิ้น       | Curcumin                 | เหลือง       |
| อัญชัน      | Anthocyanins / Ternatins | น้ำเงิน–ม่วง |

วัสดุหลักในการทดลองคือ **ผ้าฝ้าย 100%** และใช้ alum เป็น mordant หลักใน Main DOE

---

## AI Framework

```text
Experimental Database
        ↓
Forward AI Models
        ↓
Uncertainty Quantification
        ↓
Target CIELAB
        ↓
Inverse Design
        ↓
Multi-Objective Optimization
        ↓
AI-Recommended Recipe
        ↓
Real Dyeing Experiment
        ↓
Active Learning
        ↓
Closed-Loop Model Update
```

---

## Models

แบบจำลองที่นำมาเปรียบเทียบประกอบด้วย

* Response Surface Methodology (RSM)
* Random Forest
* XGBoost
* Artificial Neural Network (ANN)

โดยเปรียบเทียบระหว่าง **Dye-Specific Models** และ **Unified Multi-Dye Model**

---

## Research Objectives

1. พัฒนาและเปรียบเทียบแบบจำลอง AI สำหรับทำนายผลการย้อมสีธรรมชาติหลายชนิด
2. พัฒนาระบบ **Inverse Design และ Multi-Objective Optimization** สำหรับออกแบบชนิดสีและเงื่อนไขการย้อมจากสีเป้าหมาย
3. พัฒนาและประเมิน **Uncertainty-Aware Closed-Loop Learning** เพื่อลดการทดลองจริงและรองรับความแปรปรวนของวัตถุดิบระหว่าง lot

---

## Key Contributions

### Multi-Natural-Dye Inverse Design

ค้นหาทั้ง **ชนิดสีธรรมชาติและสูตรย้อม** จากสีเป้าหมาย

### Uncertainty-Aware Closed-Loop Learning

ประเมินความไม่แน่นอนของแบบจำลอง เลือกการทดลองใหม่ และนำผลจริงกลับมาเรียนรู้

### Raw-Material Batch Adaptation

ประเมินความสามารถของระบบในการปรับตัวเมื่อวัตถุดิบสีธรรมชาติเปลี่ยน lot

### Resource-Aware Optimization

หาสูตรที่สมดุลระหว่าง

**Color Difference · Fastness · Energy · Water · Mordant · Time**

---

## Validation

ระบบจะได้รับการประเมินด้วย

* Grouped Nested Cross-Validation
* Unseen-Recipe Validation
* Target-Color Experimental Validation
* New Raw-Material Lot Validation
* Closed-Loop Adaptation
* Ablation and Failure Analysis

---

## Research Direction

แนวคิดหลักของงานคือการเปลี่ยน AI จาก

**Recipe → Prediction**

ไปสู่

**Target → Dye/Recipe Design → Optimization → Experiment → Adaptation**

เพื่อสร้างระบบที่ไม่เพียงทำนายผลการย้อม แต่สามารถ **ออกแบบ ทดลอง เรียนรู้ และปรับตัว** กับกระบวนการย้อมสีธรรมชาติได้อย่างเป็นระบบ

---

## Documentation

* [Chapter 1 — Introduction](./chapter1.html)

---

**Research Title**

*Multi-Natural-Dye AI-Driven Inverse Design and Closed-Loop Optimization for Sustainable Textile Dyeing*
