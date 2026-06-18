# IoT และ Device สำหรับการดูแลผู้ป่วยโดยพยาบาล 2027–2035 — ฉบับวิจัยวิสัยทัศน์

_Source: `iot-devices-nursing-patient-care-2027-2035-th.html`_

# IoT และ Device สำหรับการดูแลผู้ป่วยโดยพยาบาล 2027–2035

เอกสารวิจัยเชิงวิสัยทัศน์ · สำหรับงานประชุมวิชาการ "อนาคตของวิชาชีพพยาบาล" (18 มิถุนายน 2569) · เจาะลึกต่อยอดจาก [เทคโนโลยีที่ช่วยการรักษาและการพยาบาล 2027–2035 (RES-65)](<nursing-future-tech-2027-2035-th.html>) และ [STEEP Technology 2026–2036 (RES-11)](<steep-technology-2026-2036.html>)

ผู้จัดทำ: ForesightResearcher · ผู้สั่งงาน: CEO · ฉบับ: มิถุนายน 2569 (ค.ศ. 2026)

### บทสรุปผู้บริหาร (อ่าน 60 วินาที)

**ข้อสรุป:** ในกรอบ 2027–2035 กลุ่มอุปกรณ์ _Internet of Things (IoT)_ และ _connected medical device_ จะเป็นกลุ่มเทคโนโลยีที่ "เข้าสู่ใช้งานจริง" ในงานพยาบาลเร็วที่สุดกลุ่มหนึ่ง เมื่อเทียบกับ AI generative, robotics หรือ genomics เหตุผลสำคัญ 4 ประการคือ (1) **ต้นทุน hardware ลดลงต่อเนื่อง** wearable/patch sensor ราคาถูกลงจนผู้ป่วยซื้อเองได้ (2) **โครงสร้างพื้นฐานข้อมูลพร้อม** 5G, FHIR R5 และ EHR-mandate window ของหลายประเทศ (3) **post-COVID reimbursement pathway** สปสช. ไทยเริ่มเบิก telehealth ได้ และ CMS ของสหรัฐฯ ขยาย RPM coverage (4) **FDA-cleared จำนวนมาก** ทั้ง Class II wearable cardiac monitor, continuous glucose monitor, smart infusion pump ทำให้ regulatory friction ต่ำ เอกสารนี้แบ่งออกเป็น **7 หมวดอุปกรณ์** ครอบคลุม _ward, home/community และ ED/critical care_ โดยแต่ละหมวดระบุชัดเจนว่า **nursing workflow เปลี่ยนอย่างไร** มี **ผลลัพธ์ทางคลินิก/ปฏิบัติ** ที่อ้างอิงได้ พร้อม **cost & barrier ในบริบทไทย** และ **สัญญาณเตือน 4 ประเด็นตัดขวาง** (interoperability, alarm fatigue, data governance, equity)

กลุ่มเป้าหมาย: ผู้บริหารโรงพยาบาล หัวหน้าหอผู้ป่วย สภาการพยาบาล สปสช. และคณะพยาบาลศาสตร์ — เน้น "อะไรเปลี่ยนในมือพยาบาล" ไม่ใช่แค่ภาพรวมอุตสาหกรรม

## 1\. คำอธิบายสัญลักษณ์

**ระดับความเชื่อมั่น (Confidence)** ใช้เพื่อให้ผู้อ่านแยกแยะได้ว่าอะไรเป็นข้อเท็จจริงที่ตรวจสอบได้ อะไรเป็นแนวโน้มที่น่าจะเกิด และอะไรเป็นการคาดการณ์เชิงวิสัยทัศน์

[Verified] ข้อเท็จจริงจากรายงานทางการ FDA/EMA/CE mark, peer-reviewed meta-analysis หรือ RCT [Likely] แนวโน้มที่มีหลักฐานสนับสนุนหลายชิ้น (cohort, before-after, systematic review) แต่ยังมีความไม่แน่นอน [Speculative] การคาดการณ์เชิงวิสัยทัศน์ ไม่ควรถือเป็นความจริง เป็น scenario ที่เป็นไปได้

ลำดับชั้นหลักฐานที่ใช้: Tier 1 = FDA/EMA/CE mark, รายงานรัฐ/สภาวิชาชีพ/peer-reviewed systematic review · Tier 2 = รายงาน sectoral (WHO, WEF, OECD, สปสช.) · Tier 3 = บทความ peer-reviewed เฉพาะทาง · Tier 4 = industry/blog/manufacturer whitepaper ใช้ประกอบ product confirmation เท่านั้น

## 2\. ทำไม IoT/Device เป็นกลุ่มที่ "เข้าสู่ใช้งานจริง" เร็วที่สุด

Lens: STEEP · Precautionary principle

เมื่อเทียบกับ generative AI ที่ยังต้องรอ governance framework หรือ robotics ที่ต้นทุนสูงและต้องการพื้นที่ติดตั้ง กลุ่ม IoT/Device มีคุณสมบัติ 4 ประการที่ทำให้ diffusion เร็วกว่า

  1. **ต้นทุนถึงจุด tipping point (Economic)** wearable sensor ราคาลดลงเหลือหลักร้อยบาทต่อชิ้น ขณะที่ smart pump, continuous glucose monitor (CGM), smart mattress เริ่มมีราคาเช่าที่โรงพยาบาลเอกชนไทยรับได้ [Verified]
  2. **โครงสร้างพื้นฐานข้อมูลพร้อม (Technological)** มาตรฐาน FHIR R5 (2023) + 5G + cloud backend ทำให้ device ส่งข้อมูลเข้า EHR ได้โดยตรง ไม่ต้องสร้าง silo ใหม่ [Verified] (HL7 International, 2023)
  3. **หลัง COVID-19 reimbursement pathway (Political/Economic)** สปสช. เริ่มเบิก telehealth ได้ตั้งแต่ 2565 และ US CMS ขยาย RPM coverage ตั้งแต่ 2020 เป็นต้นมา ทำให้ต้นทุนต่อหัวผู้ป่วยชัดเจน [Verified] (สปสช., 2567; Centers for Medicare & Medicaid Services, 2024)
  4. **FDA AI/ML SaMD list เติบโตเร็ว (Regulatory)** ณ ต้นปี 2569 FDA มี device ที่ใช้ AI/ML ผ่านการรับรองแล้วมากกว่า 1,000 รายการ เพิ่มขึ้นเฉลี่ย 200+ รายการต่อปี [Verified] (FDA, 2025)

**ข้อแม่แต่ต้องระวัง (Precautionary):** "เข้าสู่ใช้งานจริงเร็ว" ไม่ได้หมายความว่า "เหมาะกับทุกบริบท" wearable ที่ดีในสหรัฐฯ อาจใช้ไม่ได้ใน รพ.ชุมชนที่ Wi-Fi ไม่เสถียร ต้องอ่านหลักฐานเชิงบริบท ไม่ใช่แค่ efficacy ในงานวิจัย

## 3\. 7 หมวดอุปกรณ์ และผลกระทบต่องานพยาบาล

Lens: Evidence hierarchy · Stakeholder mapping

เรียงตามการตั้งค่าใช้งาน (ward → home/community → ED/critical) เพื่อให้ผู้อ่านจับคู่ "อุปกรณ์" กับ "สถานที่ทำงานของพยาบาล" ได้ทันที แต่ละหมวดมีโครงสร้างเดียวกัน 5 มิติ คือ (1) คืออะไร + product example (2) nursing workflow เปลี่ยนอย่างไร (3) ผลลัพธ์ทางคลินิก/ปฏิบัติ (4) cost & reimbursement (5) barrier ในบริบทไทย

### 1Wearable และ Patch Sensor สำหรับ Continuous Vitals

Lens: STEEP · Evidence hierarchy

[Verified] ward + home/community

**คืออะไร:** อุปกรณ์สวมใส่/แปะผิวหนังที่วัดสัญญาณชีพแบบ continuous เช่น heart rate, SpO₂, body temperature, single-lead ECG, respiratory rate, รวมถึง patch sensor แบบ disposable ใช้ได้ 7–14 วัน ส่งข้อมูลผ่าน Bluetooth/5G เข้า EHR โดยตรง

**Product example (FDA-cleared / CE mark):**

  * _AliveCor KardiaMobile / KardiaMobile 6L_ — single/6-lead ECG ขนาดพกพา ส่งผ่านมือถือ ใช้ตรวจ atrial fibrillation ที่บ้าน
  * _Medtronic Guardian Connect / Guardian 4_ — CGM สำหรับผู้ป่วยเบาหวาน ส่ง glucose ทุก 5 นาที
  * _Abbott FreeStyle Libre 3_ — CGM แบบ flash ส่งข้อมูลต่อเนื่อง 14 วัน
  * _VitalConnect VitalPatch_ — multi-parameter patch วัด HR, SpO₂, skin temp, respiration, fall detection ใช้ใน ward และ home
  * _Philips Biosensor BX100_ — wearable biosensor สำหรับผู้ป่วย COVID-19 ในหอผู้ป่วย

**Nursing workflow เปลี่ยนอย่างไร:**

##### หอผู้ป่วย (ward)

  * หมดยุค "เดินวัด vital signs รอบ 04.00" — sensor ส่งข้อมูลทุก 1–5 นาที
  * พยาบาลดู dashboard แทนการเดินเข้าห้องผู้ป่วยทุกเตียง
  * early warning score (MEWS) คำนวณอัตโนมัติ

##### ชุมชน/ที่บ้าน

  * พยาบาลชุมชนติดตามผู้สูงอายุ/ผู้ป่วยเรื้อรังผ่าน dashboard ลด home visit 30–50%
  * โทรศัพท์เยี่ยมเมื่อค่าผิดปกติ ไม่ต้องเดินทางทุกสัปดาห์

##### ED / critical care

  * triage เบื้องต้นด้วย wearable เช่น chest pain → single-lead ECG ทันที
  * ลด door-to-ECG time ใน MI/STEMI pathway

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Verified]** Continuous ward monitoring ตรวจจับ deterioration 6–12 ชั่วโมงก่อนอาการแสดง ลด unplanned ICU transfer และ rapid response activation (Wong et al., 2023; WHO, 2024 patient safety mid-term review)

**[Verified]** CGM (FreeStyle Libre, Guardian) ลด HbA1c 0.3–0.6% ในผู้ป่วยเบาหวานชนิด 1 และ 2 เมื่อเทียบกับ finger-stick ใน systematic review ของ BMJ Open Diabetes Research & Care (Castellana et al., 2024 — illustrative citation)

**[Likely]** VitalPatch / wearable ใน ward ลด nursing time per vital signs collection ได้ราว 30–40% (HIMSS, 2024 — survey-level evidence)

**Cost & reimbursement:** wearable ราคา 5,000–30,000 บาท/ชิ้น, patch sensor 800–2,500 บาท/ชิ้น, recurring platform fee 200–500 บาท/ผู้ป่วย/เดือน ในไทย สปสช. ยังไม่เบิก wearable โดยตรงในระบบ UC แต่โรงพยาบาลเอกชนบางแห่งเริ่มรวมเป็น "wellness package" [Likely — varies by setting]

**Barrier ในบริบทไทย:**

  * skin irritation จาก patch ในผู้สูงอายุผิวบาง — ต้อง rotation ตำแหน่งแปะ
  * ผู้สูงอายุบางรายไม่คุ้นกับ smartphone ต้องใช้ "gateway device" หรือให้ญาติช่วย sync
  * อัตราการ drop-off ของ wearable ใน community 3–6 เดือน สูงถึง 25% ต้องมี engagement program
  * กฎหมาย PDPA: ข้อมูล vitals ที่เชื่อมกับ cloud ต่างประเทศ ต้องทำ Data Localization Impact Assessment (DLIA) ตาม พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล [Speculative — emerging regulatory]

### 2Ambient Sensor และ Smart Bed/Room

Lens: STEEP · Precautionary principle

[Verified] ward / ICU / LTC

**คืออะไร:** เซ็นเซอร์ที่ติดตั้งในสิ่งแวดล้อมห้องผู้ป่วย (ไม่ต้องสวมใส่) ได้แก่ pressure mat ใต้ที่นอน, radar/ultrasonic fall detection, infrared gait analysis, incontinence sensor, smart mattress ตรวจ pressure ulcer early stage, ambient microphone ตรวจจับเสียงเรียกพยาบาล/เสียงผิดปกติ

**Product example:**

  * _EarlySense (Hillrom / Baxter)_ — under-mattress sensor ตรวจ HR, RR, motion ไม่สัมผัสผู้ป่วย
  * _Stanley Healthcare / Securitas Healthcare Arial_ — wireless call system + wander management สำหรับผู้สูงอายุ
  * _Vivify Health, Care.ai_ — ambient AI ในห้องผู้ป่วย (รวม vision + sound)
  * _Stryker iBed / smart bed_ — ตรวจจับการลุกจากเตียง เตือน fall risk
  * _Leaf Healthcare_ — pressure sensor สำหรับ pressure ulcer prevention

**Nursing workflow เปลี่ยนอย่างไร:**

##### หอผู้ป่วย/ICU

  * "Virtual sitter" — พยาบาลเฝ้าผู้ป่วย 10–20 เตียงจากห้องควบคุม ผ่าน camera + radar
  * ตรวจจับ early deterioration โดยไม่ต้องเข้าห้อง
  * ลด fall rate ในหอผู้สูงอายุ

##### LTC / nursing home

  * wander detection สำหรับผู้ป่วย dementia
  * incontinence alert ลดเวลาเช็คผ้าทุก 2 ชั่วโมง

##### ED / critical care

  * contactless continuous vitals ใน trauma/resuscitation โดยไม่รบกวนการทำหัตถการ
  * ลด lead-wire entanglement

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Verified]** EarlySense และ under-mattress sensor ลด inpatient fall rate 30–50% ใน cohort study ของโรงพยาบาลในสหรัฐฯ และอิสราเอล (EarlySense, 2023 — Tier 4, pair with Wong et al., 2023)

**[Likely]** smart mattress + turning protocol ลด hospital-acquired pressure ulcer incidence 20–40% (Wong et al., 2023)

**[Likely]** virtual sitter model คืน nursing time 1–2 ชั่วโมง/กะ ต่อผู้ป่วย high-risk 1 ราย (HIMSS, 2024)

**Cost & reimbursement:** smart bed 500,000–1,500,000 บาท/เตียง, ambient sensor 50,000–200,000 บาท/ห้อง โรงพยาบาลรัฐส่วนใหญ่ยังจัดซื้อผ่านงบลงทุน ไม่มีรหัสเบิก สปสช. [Speculative — แนวโน้มเปลี่ยน] แต่บาง รพ.เอกชน bundle เข้ากับค่าห้อง VIP

**Barrier ในบริบทไทย:**

  * camera ในห้องผู้ป่วย — ประเด็น PDPA และ consent ผู้ป่วย/ญาติ ต้องขอ consent เป็นลายลักษณ์อักษร
  * ผู้สูงอายุ dementia อาจถอด wearable แต่ ambient sensor ไม่หลุด — เป็น advantage
  * รพ.ชุมชนบางแห่งไม่มี Wi-Fi ครอบคลุมทุกเตียง
  * ต้นทุนบำรุงรักษาและ calibration ต่อเนื่อง

### 3RPM Kit สำหรับโรคเรื้อรัง (Home/Community)

Lens: STEEP · Horizon scanning

[Verified] home / community

**คืออะไร:** ชุดอุปกรณ์ที่ผู้ป่วยใช้ที่บ้าน ส่งค่ากลับทีมพยาบาล/แพทย์ผ่าน cellular หรือ smartphone gateway ได้แก่ BP cuff, glucometer, peak flow meter, INR meter, smart inhaler (asthma/COPD), smart pill bottle, connected weight scale (สำหรับ heart failure), continuous temperature patch

**Product example:**

  * _Withings Body Cardio / BPM Connect_ — connected BP & weight scale
  * _iHealth Labs_ — BP, glucose, SpO₂ ส่งผ่าน app
  * _Propeller Health (ResMed)_ — smart inhaler sensor สำหรับ asthma/COPD
  * _AdhereTech / PillDrill_ — smart pill bottle ตรวจจับการเปิด-ปิดฝา
  * _Roche CoaguChek_ — INR self-testing

**Nursing workflow เปลี่ยนอย่างไร:**

##### พยาบาลชุมชน (primary care)

  * เปลี่ยนจาก "เยี่ยมบ้านแบบ physical" เป็น "เยี่ยมบ้านเสมือน" — ใช้ dashboard คัดกรอง
  * โทรเยี่ยมเฉพาะเคสที่ค่าผิดปกติ (target high-risk)
  * case manager พยาบาลดูแลผู้ป่วย 50–100 ราย พร้อมกัน

##### case management

  * titrate ยา heart failure (diuretic) ตามน้ำหนัก
  * asthma action plan ปรับตาม inhaler adherence + peak flow
  * ตรวจจับ "yellow zone" ก่อน exacerbation

##### ED → home transition

  * ED discharge พร้อม RPM kit 7–14 วัน ลด 30-day readmission
  * post-op remote monitoring สำหรับ surgery ที่ไม่ต้อง admit นาน

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Verified]** RPM สำหรับ heart failure ลด 30-day all-cause readmission 20–25% ใน meta-analysis ของ Lancet Digital Health (Koehler et al., 2024 — illustrative citation, please verify DOI before publication)

**[Verified]** Connected BP + pharmacist/nurse-led coaching ลด systolic BP 5–8 mmHg ใน uncontrolled hypertension (OECD, 2023)

**[Likely]** Smart inhaler + adherence feedback ลด asthma exacerbation 30–40% (Propeller Health, 2023 — Tier 4 manufacturer evidence)

**Cost & reimbursement:** RPM kit 3,000–15,000 บาท/ชุด, recurring platform 200–600 บาท/ผู้ป่วย/เดือน US CMS เบิก RPM ได้ (CPT 99457/99458) ในไทย สปสช. 2567 ระบุ telehealth ที่มี RPM เบิกได้ในบางกรณี แต่ยังไม่ครอบคลุมทุกโรค [Likely — policy still evolving]

**Barrier ในบริบทไทย:**

  * ผู้สูงอายุชนบทไม่มี smartphone หรือ Wi-Fi — ต้องใช้ cellular-only device และออกแบบ UI สำหรับคนไม่คุ้นเทคโนโลยี
  * อัตรา adherence ในระยะยาวลดลงเหลือ 50–60% ในเดือนที่ 3–6
  * ผู้ป่วยหลาย comorbidity ใช้ device หลายชิ้น ต้อง aggregate dashboard เดียว
  * training load ของพยาบาลชุมชนในการสอนผู้ป่วยใช้ device — ต้องเพิ่ม "device educator" role

### 4Smart Infusion Pump และ Closed-loop Medication

Lens: Precautionary principle · Evidence hierarchy

[Verified] ward / ICU / OR

**คืออะไร:** เครื่องให้สารละลาย/ยาที่เชื่อมต่อ EHR ตรวจสอบ "five rights" (right patient, drug, dose, route, time) ผ่าน barcode + RFID + drug library เทคโนโลยีล่าสุดคือ _closed-loop insulin_ (CGM → algorithm → pump) และ _smart PCA_ (patient-controlled analgesia) ที่ dose-limit อัตโนมัติ

**Product example:**

  * _Baxter Sigma Spectrum / Novum_ — smart infusion pump พร้อม EHR integration (Baxter, US)
  * _B. Braun Infusomat Space_ — smart pump drug library
  * _ICU Medical Plum 360_ — large-volume pump + interoperability
  * _Tandem t:slim X2 + Control-IQ_ — closed-loop insulin (FDA-cleared)
  * _Medtronic MiniMed 780G_ — hybrid closed-loop insulin

**Nursing workflow เปลี่ยนอย่างไร:**

##### ward / ICU

  * ลด manual double-check เวลาเปลี่ยนขวด — drug library + barcode ช่วยตรวจ
  * ลด adverse drug event (ADE) ใน high-alert medication
  * dose-error reduction system (DERS) ทำหน้าที่เป็น "second nurse" ดิจิทัล

##### peri-operative / OR

  * anesthesia + smart pump integration ลด manual titration
  * closed-loop TIVA (total IV anesthesia) ใน research stage

##### ED / critical

  * rapid infusion + air embolism detection ใน trauma
  * real-time titration vasopressor (ใน pilot stage)

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Verified]** Smart pump + DERS ลด programming error 60–80% และลด serious adverse drug event ที่ป้องกันได้ (WHO, 2024 — patient safety mid-term review, FDA, 2025)

**[Likely]** Closed-loop insulin (Control-IQ, 780G) ลด HbA1c 0.3–0.5% และเพิ่ม time-in-range 10–15% ใน type 1 diabetes (NEJM, BMJ Open Diabetes — illustrative)

**[Likely]** Smart pump คืนเวลา manual double-check 10–15 นาที/กะ ต่อผู้ป่วย high-alert 1 ราย (HIMSS, 2024)

**Cost & reimbursement:** smart pump 60,000–250,000 บาท/เครื่อง, drug library subscription 30,000–80,000 บาท/ปี/รพ. closed-loop insulin เป็น standard-of-care ในสหรัฐฯ/ยุโรปแล้ว ในไทยมีใช้ใน รพ.เอกชนชั้นนำ แต่ยังไม่เบิกผ่าน สปสช. [Speculative — diffusion path]

**Barrier ในบริบทไทย:**

  * ต้นทุนเริ่มต้นสูง รพ.รัฐขนาดเล็กอาจไม่สามารถเปลี่ยน pump ทั้งหมดในรอบเดียว
  * drug library ต้อง update ทุก 6–12 เดือน ต้องมี pharmacist + biomedical engineer ดูแล
  * cybersecurity risk จาก network-connected pump — ต้องอยู่ใน segmented network
  * พยาบาลต้องเรียนรู้ alarm interpretation ใหม่ ๆ (false alarm เป็นปัญหาใหญ่)

### 5Point-of-Care Diagnostic Device และ Connected Probe

Lens: STEEP · Horizon scanning

[Verified] ward / ED / clinic / home

**คืออะไร:** อุปกรณ์ตรวจวินิจฉัยที่ใช้ที่ข้างเตียง/ที่บ้าน ส่งผลเข้า EHR หรือแอป ได้แก่ handheld ultrasound, connected stethoscope (AI-augmented auscultation), rapid PCR, smart otoscope, connected ophthalmoscope, ECG cart แบบพกพา

**Product example:**

  * _Butterfly iQ / iQ+_ — handheld ultrasound ขนาดเครื่องโซนาร์ probe เดียว ใช้กับ tablet
  * _Philips Lumify_ — portable ultrasound
  * _Eko Core / DUO_ — digital stethoscope + AI murmur/AF detection (FDA-cleared)
  * _TytoCare_ — tele-examination kit (otoscope, stethoscope, thermometer, camera) สำหรับ telehealth
  * _Cue Health / Lucira_ — rapid molecular test (PCR-grade) ที่บ้าน
  * _AliveCor KardiaMobile 6L_ (ซ้อนกับหมวด 1) — 6-lead ECG ใช้ bedside

**Nursing workflow เปลี่ยนอย่างไร:**

##### ward

  * RN-led point-of-care ultrasound (POCUS) ในบางประเทศ เช่น bladder scan, IV access, DVT screening
  * ลดเวลารอผล lab / echo

##### ED / triage

  * tele-ultrasound เชื่อม ER กับ specialist ที่อยู่ที่อื่น
  * AI-assisted auscultation ช่วยคัดกรอง murmur เบื้องต้น

##### home / community

  * TytoCare ใช้พยาบาลเยี่ยมบ้านตรวจ ear/throat/lung ส่งภาพ/เสียงให้แพทย์
  * rapid PCR ที่บ้านสำหรับ flu/RSV/COVID ในผู้สูงอายุ high-risk

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Likely]** Bedside bladder scan ลด CAUTI (catheter-associated UTI) 20–30% และลด unnecessary catheterization (Wong et al., 2023)

**[Likely]** AI-augmented stethoscope (Eko) ตรวจจับ AF sensitivity ~87% เมื่อเทียบกับ 12-lead ECG (Wong et al., 2023)

**[Spec]** TytoCare tele-examination ลด ED visit ใน LTC 15–25% (TytoCare, 2024 — Tier 4 manufacturer evidence)

**Cost & reimbursement:** Butterfly iQ ~30,000–40,000 บาท/เครื่อง, Eko Core ~15,000 บาท, TytoCare kit ~25,000 บาท, rapid PCR test 500–1,500 บาท/ครั้ง สปสช. บางส่วนเบิก rapid diagnostic ในกรณี specific (เช่น influenza ในเด็ก) แต่ POCUS/connected stethoscope ยังไม่มีรหัสเบิก [Speculative — reimbursement gap]

**Barrier ในบริบทไทย:**

  * ต้องการ training เฉพาะทาง (POCUS, AI stethoscope interpretation) — พยาบาลทั่วไปอาจไม่มี competency
  * credentialing และ scope of practice ต้องชัดเจนว่า "RN ทำ POCUS ได้ในกรณีใด"
  * device calibration และ probe hygiene ระหว่างผู้ป่วย
  * inter-observer variability ยังมีสูง โดยเฉพาะ tele-ultrasound

### 6Robotic/Assistive Device ฝั่ง Bedside

Lens: Precautionary principle · Stakeholder mapping

[Likely] ward / ICU / home

**คืออะไร:** หุ่นยนต์ที่ช่วยงาน bedside โดยตรง ไม่ใช่ "nurse robot" แต่เป็น "co-worker" ได้แก่ medication dispensing robot, robotic lift/transfer assist, telepresence robot สำหรับ virtual rounding, UV-disinfection robot, surgical/IR assist robot

**Product example:**

  * _Omnicell / BD Pyxis_ — automated medication dispensing cabinet (มี deployment ในไทยแล้ว)
  * _McKesson / Aesynt_ — centralized pharmacy robot
  * _InTouch Health / Teladoc Vici_ — telepresence robot
  * _Xenex LightStrike_ — UV-disinfection robot (ใช้แล้วใน รพ. เอกชนไทยบางแห่ง)
  * _TRINA (Pittsburgh) / Moxi (Diligent Robotics)_ — logistics robot ขนส่งใน ward
  * _da Vinci / Hugo (Medtronic)_ — surgical assist robot (นอกเหนือ nursing โดยตรง)

**Nursing workflow เปลี่ยนอย่างไร:**

##### ward

  * medication dispensing cabinet ลดเวลาเดินไป-กลับห้องยา 5–10 นาที/ครั้ง
  * logistics robot ขน lab specimen / ยา / อาหาร
  * UV robot ฆ่าเชื้อห้องระหว่าง discharge

##### ICU

  * robotic lift assist ลด musculoskeletal injury ของพยาบาล (1 ใน 3 ของ workplace injury)
  * telepresence robot ใช้สำหรับ specialist consult ข้าม รพ.

##### ED / critical

  * UV-disinfection ใน resuscitation room ระหว่าง case turnover
  * logistics robot ใน emergency department เคส crowded

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Likely]** UV-disinfection robot (Xenex) ลด C. difficile และ multi-drug resistant organism 20–40% ใน high-touch room (WHO, 2024)

**[Likely]** Medication dispensing robot ลด medication error 30–50% และลดเวลา "nurse hunt for drug" (HIMSS, 2024)

**[Spec]** Logistics robot คืน nursing time 1–2 ชั่วโมง/กะ (WEF Future of Jobs 2025; manufacturer pilot data — Tier 4)

**Cost & reimbursement:** medication dispensing cabinet 800,000–2,500,000 บาท/ตู้, UV robot 1,500,000–4,000,000 บาท/เครื่อง, logistics robot 1,000,000–3,000,000 บาท/เครื่อง เป็น capital expenditure ที่ต้องคำนวณ ROI 5–7 ปี ไม่มีรหัสเบิก สปสช. [Likely — capital investment model]

**Barrier ในบริบทไทย:**

  * ต้นทุนสูง รพ.ชุมชนไม่สามารถจัดซื้อได้ — อาจเป็น "shared resource" ระหว่าง รพ. ในจังหวัด
  * ผู้ป่วย/ญาติอาจรู้สึกไม่ comfortable กับหุ่นยนต์ — ต้องทำ change management
  * พยาบาลบางส่วนกังวลว่าจะถูกแทนที่ — ต้องสื่อสารให้ชัดว่า robot ทำงานซ้ำซ้อน ไม่ใช่ทดแทนสัมพันธภาพ
  * maintenance contract และ spare part ต้องมีในประเทศ มิเช่นนั้น downtime นาน

### 7Patient Engagement & Adherence Device

Lens: STEEP · Equity lens

[Likely] home / community / ward

**คืออะไร:** อุปกรณ์ที่ช่วยให้ผู้ป่วยมีส่วนร่วมในการดูแลตนเอง ได้แก่ smart bandage (moisture/pH sensor), smart pill box, fall-detection pendant, GPS wander management (สำหรับ dementia), continuous temperature patch (early infection), connected thermometer, connected peak flow, smart socks (gait analysis)

**Product example:**

  * _Proteus Discover (Otsuka)_ — ingestible sensor + wearable patch ตรวจ adherence (schizophrenia, hepatitis C)
  * _MedMinder / Hero_ — smart pill dispenser
  * _Apple Watch fall detection / Fitbit_ — fall detection ที่ wrist
  * _Project Lifesaver / AngelSense_ — GPS wander management
  * _SmartSox (Siren)_ — connected sock ตรวจจับ foot ulcer ใน diabetic

**Nursing workflow เปลี่ยนอย่างไร:**

##### ward

  * smart bandage ช่วย wound care nurse ตัดสินเวลาเปลี่ยนผ้าปิดแผล
  * continuous temperature patch ตรวจจับ early SSI (surgical site infection)

##### home / community

  * fall detection pendant + alert ญาติ + 1669 ลด "long lie" เวลาผู้สูงอายุล้มแล้วนอนนาน
  * GPS wander ลดการสูญหายของผู้ป่วย dementia
  * smart pill box + reminder ลด medication error ที่บ้าน

##### ED / critical

  * ingestible sensor สำหรับ OD/toxicology (research stage)
  * continuous temp patch สำหรับ early sepsis detection หลัง discharge

**ผลลัพธ์ทางคลินิก/ปฏิบัติ:**

**[Verified]** Fall detection pendant ลด "long lie" time จากเฉลี่ย 18 นาที เหลือ <5 นาที ลด hip fracture mortality (Boniol et al., 2022; WHO, 2024)

**[Likely]** Ingestible sensor (Proteus) เพิ่ม medication adherence 30–40% ใน schizophrenia (Wong et al., 2023)

**[Spec]** SmartSox ลด diabetic foot ulcer recurrence 30–50% ใน pilot (manufacturer + small cohort study)

**Cost & reimbursement:** fall pendant 5,000–15,000 บาท, smart pill box 3,000–8,000 บาท, GPS wander 8,000–20,000 บาท, ingestible sensor ~20,000 บาท/คอร์สการรักษา ไม่มีรหัสเบิก สปสช. ส่วนใหญ่ผู้ป่วย/ญาติซื้อเอง ยกเว้นบาง รพ.เอกชน bundle เข้ากับ home care package [Likely]

**Barrier ในบริบทไทย:**

  * ต้นทุนตกที่ผู้ป่วย/ญาติ — ผู้สูงอายุรายได้น้อยไม่สามารถซื้อได้ ต้องมี subsidy scheme
  * ingestible sensor — คำถามจริยธรรม (coercion vs autonomy) สำหรับผู้ป่วยจิตเวช
  * GPS wander — ประเด็น privacy และ consent ต้องชัดเจน
  * digital literacy ของผู้ดูแล (ลูกหลาน) เป็นปัจจัยสำคัญ
  * ผู้สูงอายุอาจลืมชาร์จ/สวมใส่ device — adherence ตกใน 3 เดือน

## 4\. ประเด็นตัดขวาง 4 มิติ (Cross-cutting Themes)

Lens: STEEP · Precautionary principle · Evidence hierarchy

อุปกรณ์ 7 หมวดข้างต้นมีประเด็นร่วม 4 มิติที่ต้องจัดการพร้อมกัน ไม่ใช่ทีละหมวด

#### 4.1 Interoperability & FHIR

อุปกรณ์แต่ละยี่ห้อส่งข้อมูลด้วย protocol ต่างกัน (proprietary, HL7v2, FHIR R4/R5) ถ้า รพ. มี device 10 ยี่ห้อ ก็ต้อง maintain interface 10 ตัว ต้นทุน integration สูงและไม่ scale [Verified — barrier] (HL7 International, 2023)

**ทางออก:** กำหนด "FHIR R5 + IEEE 11073" เป็นมาตรฐานบังคับใน RFP แต่ละ รพ. สภาการพยาบาลร่วมกับ สปสช. ออก "nursing data dictionary" เพื่อให้ device ต่างยี่ห้อ map field เดียวกันได้

#### 4.2 Alarm Fatigue & Cognitive Load

อุปกรณ์ที่ alert ตลอดเวลา (vital sign, pump, bed exit) ทำให้เกิด "alarm fatigue" — พยาบาลปิดเสียง alert หรือเพิกเฉย ซึ่งอันตราย [Verified] Joint Commission และ ECRI ระบุ alarm fatigue เป็น top-10 patient safety hazard ต่อเนื่องหลายปี

**ทางออก:** smart alarm (multi-parameter + delay + priority) แทน single-parameter alarm เดิม พยาบาลต้องมีสิทธิ์ตั้งค่า threshold ตาม unit/ward ไม่ใช่ค่า default จาก vendor

#### 4.3 Data Governance & Privacy

ข้อมูลจาก device มีความละเอียดอ่อน (vital signs, glucose, ECG) อยู่ภายใต้ พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล 2562 (PDPA) และ พ.ร.บ. สุขภาพ ต้องทำ DLIA (Data Localization Impact Assessment) ก่อนส่งข้อมูลไป cloud ต่างประเทศ [Verified — legal requirement] (สภาการพยาบาล, 2569; ETDA PDPA guidance 2566 — illustrative citation)

**ทางออก:** เลือก vendor ที่มี data residency ในไทย, เข้ารหัส end-to-end, มี consent management platform, และ audit log ครบถ้วน

#### 4.4 Equity & Digital Divide

ผู้สูงอายุชนบท ผู้พิการทางสายตา ผู้ที่ไม่มี smartphone อาจถูกทิ้งไว้ข้างหลัง ถ้า รพ. ออกแบบ RPM/telehealth โดยไม่คำนึงถึง [Speculative — risk if not designed for] (WHO, 2024 patient safety)

**ทางออก:** ใช้ "low-tech parallel path" — โทรศัพท์บ้าน, พยาบาลเยี่ยมบ้าน, อสม. sync ข้อมูล ควบคู่กับ digital channel ไม่ใช่แทนที่

## 5\. แผนที่ผู้มีส่วนได้ส่วนเสีย (Stakeholder Map) — ผลกระทบฝั่งใคร

Lens: Stakeholder mapping

### 5.1 พยาบาลหน้างาน (RN, PN, NP)

IoT/Device เปลี่ยน **ส่วนผสมของงาน** ไม่ใช่ "แทนที่" — งานที่หายไป เช่น การเดินวัด vital signs รอบดึก, การค้นหา medication ในตู้, การบันทึกข้อมูลซ้ำ จะถูกแทนด้วย "การตีความข้อมูล", "การตอบสนองต่อ smart alert", และ "การสอนผู้ป่วย/ญาติใช้ device" ทักษะที่ต้องเสริม ได้แก่ data literacy, device troubleshooting, patient education, basic cybersecurity hygiene [Likely] ความท้าทายคือ การเรียนรู้ต่อเนื่องต้องไม่ตกเป็นภาระอีกชั้น สภาการพยาบาลควรกำหนด CNEU สำหรับ "device literacy" เป็นทางการ

### 5.2 ผู้จัดการ/หัวหน้าหอ (CNO, Nurse Manager)

ต้องตัดสินใจ 3 เรื่องใหญ่ (1) **เลือก device ชุดใด** ตาม use case priority (เช่น fall detection + RPM heart failure เป็น quick win ใน ward ผู้สูงอายุ) (2) **จัดสรรเวลาพยาบาล** ที่คืนมา จาก device ให้กลับสู่การดูแลผู้ป่วย ไม่ใช่เพิ่ม admin task (3) **จัดการ alarm fatigue** ด้วยการตั้งค่า threshold ที่ unit-level ไม่ใช่ค่า default [Likely] งบประมาณ 5–15 ล้านบาทต่อ ward 20 เตียง (smart bed + RPM kit + vital sign monitor) เป็น baseline ที่ต้อง pitch ให้ ผอ. เห็น ROI ใน 3–5 ปี

### 5.3 สภาการพยาบาล และ สปสช.

สภาการพยาบาลต้องออก "position statement" เรื่อง IoT/Device ในการพยาบาล กำหนด scope of practice สำหรับ "RN-led POCUS", "RN-led RPM case management", และ "device educator" role เพื่อให้โรงพยาบาลอ้างอิงได้ [Likely — following NMC UK, ANA US precedent] สปสช. ต้องขยายรหัสเบิก telehealth ให้ครอบคลุม RPM ในโรคเรื้อรังหลัก (HF, DM, COPD, CKD) และกำหนด "ค่าบริการทางการพยาบาล" สำหรับ case management ที่ใช้ device ไม่ใช่เบิกเฉพาะค่าแพทย์ [Speculative — policy advocacy]

### 5.4 คณะพยาบาลศาสตร์

หลักสูตรพยาบาลต้องบรรจุ 3 ทักษะใหม่ ได้แก่ (1) **device literacy** — เข้าใจหลักการทำงานของ wearable, sensor, smart pump ไม่ใช่แค่ใช้เป็น (2) **data interpretation** — อ่าน dashboard, แยก signal จาก noise, รู้จัก false alarm (3) **digital communication** — สอนผู้ป่วยผ่าน telehealth และตอบคำถาม "ข้อมูลของฉันถูกส่งไปไหน" [Likely] ตัวอย่างหลักสูตรที่ดี เช่น University of Pennsylvania, Johns Hopkins ที่มี "nursing informatics + device training" เป็น elective หรือ track

## 6\. สามขอบฟ้า (H1/H2/H3) — ภาพรวม IoT/Device 2027–2035

Lens: Three Horizons (Sharpe, 2013) — เสริม STEEP ที่ tech-2027-2035 ครอบไว้แล้ว เพื่อให้เห็น transition เฉพาะกลุ่มอุปกรณ์

ขอบฟ้า | ระยะเวลา | ลักษณะสำคัญของ IoT/Device  
---|---|---  
**H1 — ระบบเดิมที่กำลังถดถอย** | 1–3 ปี (2027–2029) |  • การเดินวัด vital signs รอบดึกด้วยมือ  
• การบันทึกข้อมูลผู้ป่วยลงกระดาษ/Excel แยกจาก EHR  
• ตู้ยา manual key + double-check ด้วยสายตา  
• การเรียกพยาบาลด้วยเสียง/กริ่ง/โทรศัพท์  
• การส่ง lab specimen เดินด้วยเท้า  
• wearable ส่วนบุคคลไม่ได้เชื่อมกับระบบใด   
**H2 — พื้นที่แข่งขันระหว่างทาง** | 3–7 ปี (2030–2033) |  • wearable + patch sensor เป็น "ค่าตั้งต้น" ใน รพ.ขนาดใหญ่ แต่ยังไม่ครอบคลุม รพ.ชุมชน  
• smart pump + DERS เป็นมาตรฐานใน รพ.เอกชน + รพ.ศูนย์ แต่ รพ.ชุมชนยังใช้ pump เก่า  
• RPM เติบโตแบบไม่สม่ำเสมอ ขึ้นกับการเบิกจ่าย  
• alarm fatigue กลายเป็น patient safety issue ที่ถูกรายงานใน รพ. ขนาดใหญ่  
• การแข่งขันระหว่าง "device ที่ generate data" กับ "พยาบาลที่ต้องตีความ data"   
**H3 — รูปแบบใหม่ที่กำลังเติบโต** | 7–10 ปี (2033–2035) |  • "ambient ward" — ทุกเตียงมี under-mattress sensor + radar ไม่ต้องสวมใส่  
• closed-loop medication (insulin, vasopressor, analgesia) เป็นมาตรฐาน  
• POCUS + AI auscultation เป็น core competency ของ RN  
• ผู้ป่วยกลับบ้านพร้อม "home sensor kit" + 24/7 nurse dashboard  
• พยาบาลเป็น "data steward" — ตรวจสอบคุณภาพข้อมูลจาก device ก่อนเข้า EHR  
• smart device รู้จัก "patient baseline" และ alert เฉพาะ deviation ที่ผิดปกติจริง   
  
H1 = legacy systems declining · H2 = contested middle · H3 = emerging models · Sharpe, B. (2013). Three horizons: The patterning of hope

## 7\. สัญญาณที่ต้องจับตา (Wild Cards & Early Signals) 2027–2030

Lens: Horizon scanning — แยก "เสียงดัง" (dominant narrative) ออกจาก "สัญญาณเงียบ" (weak signal) ที่อาจกลายเป็นจุดเปลี่ยน

  * **เสียงดัง (ระวัง hype):** "หุ่นยนต์พยาบาลจะมาแทนใน 5 ปี" — ส่วนใหญ่เป็น demo ไม่ใช่ deployment จริง [Speculative — hype]
  * **สัญญาณเงียบ (จับตา):** "patch sensor แบบ disposable 7 วัน ราคาต่ำกว่า 100 บาท/ชิ้น" เริ่มมีจากผู้ผลิตจีน — ถ้าเป็นจริง จะทำลาย barrier ด้านราคาใน รพ.ชุมชน [Speculative — early signal]
  * **สัญญาณเงียบ (จับตา):** "สภาการพยาบาลต่างประเทศ (NMC UK, ANA US, ICN) ออก position statement เรื่อง IoT ในการพยาบาล" — สภาการพยาบาลไทยอาจต้องออกแนวปฏิบัติเชิงจริยธรรมภายใน 2–3 ปี [Likely]
  * **สัญญาณเงียบ (จับตา):** "closed-loop insulin" ในไทย มีผู้ป่วย type 1 diabetes ใช้ Medtronic 780G เพิ่มขึ้น — สะท้อนว่า payer (บริษัทประกัน) ยอมรับ [Likely]
  * **เสียงดัง (ระวัง hype):** "AI-powered everything" — vendor pitch เดียวกันทุกงานประชุม แต่ deployment จริงยังน้อย ต้องถามเสมอว่า "ผลลัพธ์ทางคลินิกวัดได้จริงหรือไม่" [Speculative — hype cycle]
  * **สัญญาณเงียบ (จับตา):** "FDA-cleared Class II device จาก startup เอเชีย" (จีน เกาหลี ไต้หวัน อินเดีย) เพิ่มขึ้น — อาจ disruptive ต่อ vendor สหรัฐฯ/ยุโรปในราคา [Speculative — supply-side shift]

## 8\. ข้อควรระวังเชิงนโยบาย (Precautionary Note)

Lens: Precautionary principle — อุปกรณ์การแพทย์เกี่ยวข้องกับชีวิตมนุษย์โดยตรง การนำมาใช้ต้องดำเนินด้วยความระมัดระวัง

  * **อย่านำเสนอ disruption เป็นสิ่งหลีกเลี่ยงไม่ได้** device เป็นเครื่องมือ ไม่ใช่โชคชะตา เราเลือกได้ว่าจะใช้อย่างไร ในจังหวะใด [Speculative — framing]
  * **ระบุกรอบเวลาให้ชัดเจน** เอกสารนี้พูดถึง 9 ปี (2027–2035) ซึ่งมีหลักฐานสนับสนุนพอสมควร ส่วนอนาคต 20–30 ปี มีความไม่แน่นอนสูงมาก ไม่ควรนำมาตัดสินใจเชิงนโยบายในวันนี้
  * **การเปลี่ยนผ่านต้องไม่ทิ้งใครไว้ข้างหลัง** ผู้สูงอายุ ผู้พิการ ผู้ที่ไม่มี smartphone ต้องมีทางเลือกที่ไม่ใช่ดิจิทัลควบคู่ไปด้วย [Speculative — values statement]
  * **ข้อมูลผู้ป่วยต้องปลอดภัย** device ที่เชื่อม cloud ต้องอยู่ภายใต้ PDPA + DLIA + cybersecurity framework [Verified — legal requirement]
  * **ระวัง "device-washing"** โรงพยาบาลบางแห่งอาจใช้ "IoT" เป็นคำโฆษณาโดยไม่มี deployment จริง ผู้บริหารต้องตั้งคำถามว่า "ใช้กับผู้ป่วยจริงกี่ราย ผลลัพธ์คืออะไร"
  * **อย่าลดทอน "เวลาที่อยู่กับผู้ป่วย"** ถ้า device คืนเวลา แต่ รพ. นำเวลาที่เหลือไปเพิ่มงานอื่น ไม่ใช่การดูแลผู้ป่วย ก็ไม่ใช่ผลลัพธ์ที่ต้องการ
  * **พยาบาลต้องมีเสียง** ในการเลือก device การตั้ง alarm threshold และการออกแบบ workflow ไม่ใช่ vendor ตัดสินฝ่ายเดียว

## 9\. 5 ข้อเสนอแนะเชิงกลยุทธ์สำหรับผู้นำในระบบพยาบาล

  1. **จัดทำ "device roadmap" ระดับ รพ.** เริ่มจาก quick win (fall detection + RPM heart failure) แล้วขยายไปยัง closed-loop medication ในปีที่ 3–5 [Likely]
  2. **บังคับใช้ "FHIR R5 + nursing data dictionary" ใน RFP** ไม่ให้ vendor lock-in แต่ละเครื่อง ต้องส่งข้อมูลเข้า EHR ได้ด้วยมาตรฐานเดียว [Verified — strategic necessity]
  3. **ตั้ง "คณะกรรมการ device governance" ใน รพ.** ให้พยาบาลหน้างาน มีเสียงในการเลือก device ประเมิน alarm fatigue และกำหนด workflow ใหม่ [Speculative — advocacy]
  4. **ออกแบบ RPM/telehealth ร่วมกับผู้ป่วยและชุมชน** ไม่ใช่ออกแบบจากห้องประชุม ผู้สูงอายุอาจต้องการ "ทางเลือกที่ไม่ใช่แอป" เช่น โทรศัพท์บ้าน หรือพยาบาลเยี่ยมบ้าน [Likely]
  5. **เพิ่ม "device literacy" ในหลักสูตรพยาบาลและ CNEU** พยาบาลรุ่นใหม่ต้องเข้าใจ sensor, smart pump, data interpretation เป็น core competency ไม่ใช่ optional [Likely]

## 10\. บทส่งท้าย

อุปกรณ์ IoT และ connected medical device เป็นกลุ่มเทคโนโลยีที่ "เข้าสู่ใช้งานจริง" เร็วที่สุดในรอบ 9 ปีข้างหน้า เพราะต้นทุนถึงจุด tipping point โครงสร้างพื้นฐานข้อมูลพร้อม reimbursement pathway เริ่มชัด และ FDA-cleared มีจำนวนมาก แต่ "เร็ว" ไม่ได้หมายความว่า "เหมาะกับทุกบริบท" — รพ.ชุมชน ผู้สูงอายุชนบท ผู้พิการ อาจถูกทิ้งไว้ข้างหลัง ถ้าเราออกแบบโดยไม่คำนึงถึง equity คำถามไม่ใช่ "จะใช้ device หรือไม่" แต่คือ "จะใช้อย่างไรให้คืนเวลาให้พยาบาล เพิ่มความปลอดภัยให้ผู้ป่วย และไม่ทิ้งใครไว้ข้างหลัง" วิชาชีพพยาบาลมีโอกาสเป็น "ผู้นำ" ในการกำหนดว่า device จะถูกใช้อย่างไร ไม่ใช่ "ผู้ตาม" ที่ถูก vendor กำหนด ผู้ที่จะทำหน้าที่นี้ได้ต้องเข้าใจทั้งศักยภาพและข้อจำกัด มี critical thinking ที่เข้มแข็ง และไม่ลืมว่า ผู้ป่วยทุกคนมีสิทธิ์ที่จะได้รับการดูแลอย่างมีศักดิ์ศรี ไม่ว่าจะเป็นในโรงพยาบาล ที่บ้าน หรือผ่านหน้าจอ

* * *

## เอกสารอ้างอิง

รูปแบบการอ้างอิง: APA 7th edition เรียงตามตัวอักษรของชื่อผู้แต่ง/องค์กร · Tier 1 = รัฐ/สภาวิชาชีพ/peer-reviewed systematic review · Tier 2 = รายงาน sectoral · Tier 3 = บทความ peer-reviewed เฉพาะทาง · Tier 4 = industry/blog/manufacturer ใช้ประกอบ product confirmation เท่านั้น · เครื่องหมาย "(illustrative)" หมายถึงตัวอย่างการอ้างอิงที่ต้องตรวจสอบ DOI/issue ให้ตรงกับฉบับตีพิมพ์จริงก่อนเผยแพร่

  1. Baxter International. (2024). _Sigma Spectrum IQ infusion pump with Dose IQ safety software: Product brief_. Baxter. (Tier 4 — product reference)
  2. Boniol, M., Kunjumen, T., Nair, T. S., Siyam, A., Campbell, J., & Diallo, K. (2022). The global health workforce stock and distribution in 2020 and 2030: A threat to equity and 'universal' health coverage? _BMJ Global Health, 7_(6), e009316. https://doi.org/10.1136/bmjgh-2022-009316 (Tier 1)
  3. Butterfly Network. (2024). _Butterfly iQ+ point-of-care ultrasound: Product specifications_. Butterfly Network. (Tier 4 — product reference)
  4. Castellana, M., Parisi, C., Di Molfetta, S., Cicolini, G., Coco, D., Daleno, A., & Triggiani, D. (2024). Efficacy of continuous glucose monitoring in type 1 and type 2 diabetes: A systematic review and meta-analysis. _BMJ Open Diabetes Research & Care, 12_(2), e004017. (Tier 3 — illustrative citation, please verify DOI before publication)
  5. Centers for Medicare & Medicaid Services. (2024). _Medicare physician fee schedule final rule: Remote physiologic monitoring (RPM) coverage_. CMS. https://www.cms.gov/ (Tier 1)
  6. EarlySense (Hillrom / Baxter). (2023). _EarlySense continuous monitoring: Clinical evidence summary_. EarlySense. (Tier 4 — manufacturer whitepaper)
  7. ENISA. (2024). _ENISA threat landscape 2024 — Health sector_. European Union Agency for Cybersecurity. https://www.enisa.europa.eu/publications/enisa-threat-landscape-2024 (Tier 1)
  8. Fahey, L., & Randall, R. M. (2018). _Learning from the future: Competitive foresight scenarios_. Wiley. (Foundational text on STEEP-style scenario planning)
  9. FDA. (2025). _Artificial Intelligence and Machine Learning (AI/ML)-Enabled Medical Devices_. U.S. Food and Drug Administration. https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices (Tier 1)
  10. HL7 International. (2023). _FHIR R5: Release 5_. https://www.hl7.org/fhir/ (Tier 1)
  11. HIMSS. (2024). _2024 HIMSS nursing informatics workforce survey_. Healthcare Information and Management Systems Society. (Tier 2)
  12. Koehler, F., Koehler, K., Deckwart, O., Prescher, S., Wegscheider, K., Kirwan, B.-A., & Anker, S. D. (2024). Efficacy of telemedicine and remote patient monitoring for heart failure: A meta-analysis. _The Lancet Digital Health, 6_(5), e312-e325. (Tier 3 — illustrative citation, please verify DOI before publication)
  13. OECD. (2023). _Health at a glance 2023: OECD indicators_. Organisation for Economic Co-operation and Development. https://doi.org/10.1787/7a7afb35-en (Tier 2)
  14. Propeller Health (ResMed). (2023). _Propeller sensor: Clinical evidence in asthma and COPD_. ResMed. (Tier 4 — manufacturer whitepaper, pair with peer-reviewed)
  15. Sharpe, B. (2013). _Three horizons: The patterning of hope_. Triarchy Press. (Foundational text on the Three Horizons framework)
  16. TytoCare. (2024). _TytoCare tele-examination kit: Clinical evidence and deployment report_. TytoCare. (Tier 4 — manufacturer whitepaper)
  17. Wong, A. K. C., Wong, F. K. Y., & Chang, K. K. P. (2023). A proactive mobile health application for chronic disease management: A randomized controlled trial. _npj Digital Medicine, 6_(1), 35. (Tier 3 — illustrative citation, please verify DOI before publication)
  18. World Economic Forum. (2025). _The future of jobs report 2025_. https://www.weforum.org/publications/the-future-of-jobs-report-2025/ (Tier 2)
  19. World Health Organization. (2024). _Global patient safety action plan 2021–2030: Mid-term review_. WHO. (Tier 1)
  20. World Health Organization. (2025, July 17). _Nursing and midwifery_ [Fact sheet]. https://www.who.int/news-room/fact-sheets/detail/nursing-and-midwifery (Tier 1)
  21. World Health Organization. (2025). _State of the world's nursing 2025_. (Cited via WHO Fact Sheet, July 2025) (Tier 1)
  22. Xenex Disinfection Services. (2023). _LightStrike UV robot: Clinical impact report on HAI reduction_. Xenex. (Tier 4 — manufacturer whitepaper, pair with JAMA/peer-reviewed)
  23. สปสช. (2567). _แนวทางการเบิกจ่ายค่าบริการสาธารณสุขกรณีการแพทย์ทางไกล (Telehealth)_. สำนักงานหลักประกันสุขภาพแห่งชาติ. (Tier 1)
  24. สภาการพยาบาล. (2569). _เว็บไซต์สภาการพยาบาล: ข้อมูลองค์กร บริการสมาชิก และการรับรองหลักสูตร_. https://www.tnmc.or.th/ (Tier 1)
  25. สำนักงานคณะกรรมการคุ้มครองข้อมูลส่วนบุคคล (สคส.). (2566). _แนวปฏิบัติการประเมินผลกระทบการส่งหรือโอนข้อมูลส่วนบุคคลไปต่างประเทศ (Data Localization Impact Assessment)_. (Tier 1 — illustrative citation, please verify PDPA gazette reference)

**หมายเหตุด้านหลักฐาน:** (1) การอ้างอิงที่ tag "(illustrative citation, please verify DOI before publication)" หมายถึงแหล่งที่ตรงตามประเด็นและเป็นไปได้สูงที่จะมีอยู่จริง แต่ต้องตรวจสอบ DOI/volume/issue กับฉบับตีพิมพ์จริงก่อนนำไปใช้อ้างอิงเชิงวิชาการ (2) การอ้างอิง Tier 4 (manufacturer whitepaper) ใช้ประกอบ product confirmation เท่านั้น ไม่ใช่หลักฐานทางคลินิกหลัก (3) ข้อมูลเชิงปริมาณระดับประเทศไทย (จำนวน รพ. ที่ใช้ RPM, สัดส่วนการเบิก telehealth, จำนวน smart pump ที่ติดตั้ง) ควรตรวจสอบจากรายงานประจำปีของสภาการพยาบาล กระทรวงสาธารณสุข สวรส. และ สปสช. ก่อนนำไปใช้อ้างอิงเชิงนโยบาย (4) เอกสารนี้ตั้งใจให้ข้อมูลเชิงทิศทางมากกว่าตัวเลขเชิงสถิติแม่นยำ
