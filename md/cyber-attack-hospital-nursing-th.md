# Cyber Attack foresight สำหรับโรงพยาบาลและวิชาชีพพยาบาล 2026–2031

_Source: `cyber-attack-hospital-nursing-th.html`_

# Cyber Attack foresight สำหรับโรงพยาบาลและวิชาชีพพยาบาล 2026–2031

เอกสารวิจัยเชิงวิสัยทัศน์ · สำหรับงานประชุมวิชาการ "อนาคตของวิชาชีพพยาบาล" (18 มิถุนายน 2569) · เจาะลึกต่อยอดจาก [IoT/Device 2027–2035 (RES-65)](<iot-devices-nursing-patient-care-2027-2035-th.html>) และ [STEEP Technology 2026–2036 (RES-11)](<steep-technology-2026-2036.html>) · ต่อยอด security deep-dive ในหัวข้อ 4.7 ของ STEEP

ผู้จัดทำ: ForesightResearcher · ผู้สั่งงาน: CEO · ฉบับ: มิถุนายน 2569 (ค.ศ. 2026)

### บทสรุปผู้บริหาร (อ่าน 60 วินาที)

ในช่วง 2024–2026 ภาคสุขภาพกลายเป็นเป้าโจมตีทางไซเบอร์อันดับต้นของโลกอย่างชัดเจน ENISA ระบุว่า healthcare เป็น sector ที่ถูกโจมตีสูงสุดเป็นอันดับสามในยุโรปและ ransomware ต่อโรงพยาบาลเพิ่มขึ้นอย่างต่อเนื่อง ในสหรัฐฯ กรณี Change Healthcare/UnitedHealth (ก.พ. 2567) ส่งผลกระทบต่อการเบิกจ่ายและการเข้าถึงยาของผู้ป่วยหลายร้อยล้านราย และกลายเป็นเหตุ data breach ทางการแพทย์ที่ใหญ่ที่สุดในประวัติศาสตร์สหรัฐฯ ในระดับโลก [Verified] เอกสารฉบับนี้มีข้อสรุป 4 ประการ

(1) **Cyber attack ไม่ใช่ปัญหาไอที แต่เป็นปัญหาความปลอดภัยของผู้ป่วยและวิชาชีพพยาบาลโดยตรง** เมื่อ ransomware ล่ม EHR พยาบาลต้องกลับไปใช้กระดาษ ระบบยาหยุดชะงัก infusion pump อาจค้าง สัญญาณเตือนจาก monitor ดับ เป็นเวลาหลายชั่วโมงถึงหลายสัปดาห์ [Verified] (ENISA, 2024)

(2) **พื้นผิวการโจมตี (attack surface) ของโรงพยาบาลขยายเร็วกว่ากำลังคนที่จะปกป้อง** EHR + IoMT + cloud + third-party SaaS + telehealth + AI ambient scribe ที่เพิ่มเข้ามาใน 3 ปีที่ผ่านมา สร้างช่องโหว่ใหม่จำนวนมากที่ทีมรักษาความปลอดภัยในโรงพยาบาลไทยส่วนใหญ่ยังไม่มีบุคลากรเพียงพอจะ audit [Likely]

(3) **คนเป็นทั้งเป้าและเกราะป้องกันแรก** phishing ของบุคลากรทางคลินิก (โดยเฉพาะพยาบาล) ยังคงเป็น initial access vector อันดับหนึ่งในเหตุการณ์จริง ดังนั้น nursing cyber awareness ไม่ใช่ "ความรู้เสริม" แต่เป็น core competency ที่ต้องฝึกอย่างต่อเนื่อง [Verified] (AHA, 2024; ENISA, 2024)

(4) **ในอีก 5 ปีข้างหน้า ภัยคุกคามจะขยับจาก "ransomware ทั่วไป" ไปสู่ "AI-assisted attack" และ "deepfake voice fraud ต่อบุคลากรทางคลินิก"** ซึ่งต้องเตรียมรับตั้งแต่วันนี้ [Likely — emerging]

กลุ่มเป้าหมาย: ผู้บริหารโรงพยาบาล (CNO/CIO), สภาการพยาบาล, หัวหน้าหอผู้ป่วย, อาจารย์พยาบาล, พยาบาลหน้างาน และนักวิชาการที่ออกแบบหลักสูตร — เน้น "อะไรเปลี่ยนในมือพยาบาลและหน้างาน" ไม่ใช่แค่ภาพรวม cybersecurity

## 1. คำอธิบายสัญลักษณ์

**ระดับความเชื่อมั่น (Confidence)**

[Verified] ข้อเท็จจริงจากรายงานทางการ (ENISA/WHO/AHA/CISA/HHS), peer-reviewed systematic review, หรือเหตุการณ์จริงที่มีรายงานต่อสาธารณะ

[Likely] แนวโน้มที่มีหลักฐานสนับสนุนหลายชิ้น (cohort, before-after, sectoral report) แต่ยังมีความไม่แน่นอน

[Speculative] การคาดการณ์เชิงวิสัยทัศน์ ไม่ควรถือเป็นความจริง เป็น scenario ที่เป็นไปได้

[Forecast] ฉากทัศน์ที่ใช้ใน 2×2 scenario ในเอกสารนี้

**ลำดับชั้นหลักฐาน (Evidence hierarchy)**

Tier 1 = รายงานรัฐ/หน่วยงานกำกับดูแล/peer-reviewed (ENISA, WHO, HHS, CISA, AHA peer-reviewed journals) · Tier 2 = รายงาน sectoral (WEF, HIMSS, OECD) · Tier 3 = บทความ peer-reviewed เฉพาะทาง · Tier 4 = industry/blog/analyst ใช้ประกอบ horizon scanning เท่านั้น

## 2. ทำไม cyber attack ในโรงพยาบาลจึงเป็นประเด็น "วิชาชีพพยาบาล" ไม่ใช่แค่ "ไอที"

Lens: Stakeholder mapping + Precautionary principle

ก่อนจะลงรายละเอียดเชิงเทคนิค ต้องตอบคำถามพื้นฐานก่อนว่า "ทำไมเอกสารฉบับนี้จึงอยู่ในชุด 'อนาคตของวิชาชีพพยาบาล' ไม่ใช่อยู่ในชุด cybersecurity" เหตุผลมี 4 ประการ

### 2.1 พยาบาลอยู่หน้าสุดของทั้ง "ผลกระทบ" และ "การป้องกัน"

เมื่อ ransomware เข้ารหัส EHR สิ่งที่หยุดทันทีไม่ใช่ "ระบบไอที" แต่คือ **กระบวนการดูแลผู้ป่วย** พยาบาลเป็นผู้ที่ต้อง

- กลับไปเขียน MAR (medication administration record) ด้วยกระดาษ
- คำนวณยา drip rate ด้วยมือเมื่อ smart pump ออฟไลน์
- ตรวจ vital signs ด้วยอุปกรณ์ stand-alone เมื่อ central monitor ดับ
- รับ-ส่งเวรด้วยวาจา เมื่อ EHR/Slack ล่ม
- โทรประสาน lab/radiology เมื่อระบบ PACS ถูกเรียกค่าไถ่

นี่คือ "shadow workflow" ที่โรงพยาบาลหลายแห่งในต่างประเทศต้องทำนานถึง 4–6 สัปดาห์หลังเหตุการณ์ cyber incident [Verified] (NHS England, 2024 — WannaCry retrospective + LockBit case studies)

### 2.2 พยาบาลเป็น initial access vector อันดับต้น

รายงานหลายฉบับระบุว่า phishing email ที่เจาะเข้ามาสู่ระบบโรงพยาบาล มักมาจากบัญชีของ clinical staff ที่ถูกหลอกให้คลิก link/เปิดไฟล์แนบ โดยเฉพาะ

- Email ปลอมเป็น "ผลแล็บด่วน" หรือ "ใบสั่งยาใหม่"
- SMS ปลอมเป็น "ระบบกะ" หรือ "ตารางเวร"
- Voice call ปลอมเป็น "ผู้อำนวยการ" ขอรหัส OTP
- QR code บนป้ายประกาศในหอผู้ป่วย ที่นำไปสู่หน้า credential harvesting

[Verified] (AHA, 2024 — cybersecurity advisory; ENISA, 2024 — top initial access vector คือ phishing 65% ของ healthcare incidents ในยุโรป)

### 2.3 พยาบาลคือ "human sensor" ที่ดีที่สุด

พยาบาลเฝ้า ward ตลอด 24 ชั่วโมง เห็นสิ่งผิดปกติก่อนระบบ — ทั้งอุปกรณ์ที่ทำงานแปลก, login page ที่เปลี่ยนไป, log file ที่ดูผิดสังเกต, คนแปลกหน้าที่เสียบ USB ที่ station พยาบาล แต่ในทางปฏิบัติ พยาบาลส่วนใหญ่ไม่รู้ว่าสิ่งที่เห็นคือ "early indicator" ของการโจมตี เพราะไม่เคยได้รับการฝึกให้มอง cybersecurity เป็น "อาการทางคลินิก" [Likely]

### 2.4 ความเสียหายต่อผู้ป่วยเป็น "adverse event" ที่ต้องรายงาน

ในหลายประเทศ ransomware-induced downtime ในโรงพยาบาลถูกจัดเป็น "patient safety incident" ไม่ใช่แค่ "ไอที incident" แล้ว สภาวิชาชีพจะต้องออก position statement ในเรื่องนี้ในอีก 2–3 ปีข้างหน้า [Forecast — policy direction]

## 3. ภูมิทัศน์ภัยคุกคาม (Threat Landscape) 2024–2026

Lens: Evidence hierarchy + Horizon scanning

ภาพรวมเหตุการณ์จริงและรายงานจากหน่วยงานระดับ Tier 1 ระบุว่า healthcare เป็น sector ที่ถูกโจมตีมากที่สุดในกลุ่ม critical infrastructure ภายในช่วง 3 ปีที่ผ่านมา โดย 9 ประเภทภัยคุกคามหลักที่พยาบาลควรเข้าใจมีดังนี้

### 3.1 Ransomware บน EHR และ Hospital Network

**คืออะไร:** มัลแวร์เข้ารหัสไฟล์และระบบ พร้อมเรียกค่าไถ่ (มักเป็น cryptocurrency) เพื่อแลกกับ decryption key กลุ่ม ransomware-as-a-service เช่น LockBit, BlackCat/ALPHV, Rhysida มี playbook เฉพาะสำหรับโรงพยาบาล [Verified] (ENISA, 2024)

**สถานะปัจจุบัน:** ในช่วง 2023–2025 มีเหตุการณ์สำคัญอย่างน้อย 5–10 เหตุการณ์ที่ส่งผลกระทบต่อโรงพยาบาลขนาดใหญ่ในยุโรปและอเมริกาเหนือ Change Healthcare/UnitedHealth (ก.พ. 2567) เป็นกรณีคลาสสิกที่กระทบ payment และ prescription ของระบบสุขภาพสหรัฐฯ ทั้งระบบ [Verified] (U.S. HHS, 2024)

**ผลกระทบต่อ nursing workflow:**

- ยกเลิกนัดผู้ป่วยนอกจำนวนมาก
- ย้อนกลับไปใช้กระดาษเต็มรูปแบบ ภายใน 2–4 ชั่วโมงแรก
- ระบบ barcode medication administration (BCMA) หยุดทำงาน → ยาที่ผู้ป่วยได้รับต้องบันทึกด้วยมือ
- ระบบ smart pump อาจค้าง ต้องคำนวณ drip rate ด้วยมือ
- ระบบ lab/radiology ล่าช้า การตัดสินใจทางคลินิกต้องพึ่ง clinical judgement ล้วน

**Driver:** ข้อมูลผู้ป่วยมีมูลค่าสูงในตลาดมืด (medical record ราคา 250–1,000 USD/record — แพงกว่า credit card 10–20 เท่า) + โรงพยาบาลจ่ายค่าไถ่บ่อย (เพราะ downtime = ชีวิต) [Verified] (ENISA, 2024)

### 3.2 Supply-chain Attack บน Medical Device และ Vendor Software

**คืออะไร:** ผู้โจมตีเจาะผ่าน "ซัพพลายเออร์" ที่โรงพยาบาลใช้ (เช่น EHR vendor, billing vendor, IV pump firmware update server, SaaS ที่ใช้ร่วม) แล้วกระจายมัลแวร์/เปลี่ยนแปลงโค้ด ผ่านช่องทางที่โรงพยาบาลเชื่อถือ [Verified]

**สถานะปัจจุบัน:** กรณีคลาสสิกคือ SolarWinds (2020) และ MOVEit (2023) ที่กระทบหลายโรงพยาบาล ในช่วง 2024–2025 มีรายงานเพิ่มขึ้นเรื่อง compromised vendor ใน healthcare supply chain [Verified] (ENISA, 2024; HHS HC3, 2024)

**ผลกระทบต่อ nursing workflow:**

- อัปเดต firmware ของ infusion pump/ventilator/monitor ต้องถูก freeze ทันที จนกว่าจะ verified
- ต้องใช้เวอร์ชันเก่าที่อาจมีช่องโหว่อื่น
- บาง รพ. ต้องถอนอุปกรณ์ออกจากเครือข่าย กลับไปใช้ manual mode

### 3.3 OT และ Medical Device Firmware Compromise

**คืออะไร:** อุปกรณ์การแพทย์ที่เชื่อมต่อเครือข่าย (IoMT) ส่วนใหญ่ใช้ embedded OS ที่ล้าสมัย มี default password ไม่ได้ patch นานหลายปี เปิดช่องให้ผู้โจมตีฝัง backdoor เข้าไปใน firmware [Verified] (CISA, 2024 — HPH cyber performance goals)

**ตัวอย่าง real-world:** FDA มี safety communication หลายฉบับเกี่ยวกับช่องโหว่ใน infusion pump (Baxter Sigma Spectrum — 2023), patient monitor (Philips — 2024), imaging system (GE Healthcare — 2024) [Verified] (FDA Safety Communications, 2023–2024)

**ผลกระทบต่อ nursing workflow:**

- อุปกรณ์อาจ reboot เอง หรือแสดงค่าผิดปกติ
- ต้องเรียนรู้ "manual mode" ของอุปกรณ์ที่ตนเองไม่เคยใช้
- downtime ของ CT/MRI/Ultrasound กระทบการวินิจฉัย

### 3.4 Phishing และ Social Engineering ของ Clinical Staff

**คืออะไร:** email/SMS/voice call ที่ออกแบบมาให้เจ้าหน้าที่คลิก link กรอกรหัส หรือโอนเงิน ในบริบทโรงพยาบาล phishing มักปลอมเป็น

- "ผลแล็บด่วน" (PDF แนบที่ฝัง malware)
- "ใบสั่งยาใหม่จากแพทย์" (link ไปหน้า credential harvesting)
- "ตารางเวรเดือนหน้า" (SMS)
- "HR ขอสำเนาบัตรประชาชนสำหรับทำบัตรใหม่"
- Voice call (deepfake) ปลอมเป็นผู้บริหารขอ OTP

[Verified] (AHA, 2024; ENISA, 2024)

**ผลกระทบ:** เป็น initial access ที่นำไปสู่ ransomware, BEC (business email compromise), หรือ data breach ครั้งใหญ่

### 3.5 Third-party / BPO Risk

**คืออะไร:** โรงพยาบาล outsource งานจำนวนมาก — billing, transcription, IT support, claim processing, telehealth platform, AI scribe ผู้ให้บริการเหล่านี้อาจถูกเจาะ แล้วลูกค้าโรงพยาบาลต้องรับ consequence [Verified]

**ตัวอย่าง:** กรณี Change Healthcare/UnitedHealth (2567) กระทบโรงพยาบาล/คลินิก/ร้านยาทั่วสหรัฐฯ เพราะเป็น "กลาง" ของ claim processing [Verified]

**ผลกระทบ:** พยาบาลอาจถูกขอให้ทำงานเอกสารที่ vendor ปกติทำให้ เช่น pre-authorization, claim submission

### 3.6 Cloud Outage และ SaaS Downtime

**คืออะไร:** ระบบที่โรงพยาบาลพึ่งพามากขึ้นเรื่อยๆ (EHR cloud hosting, video conferencing, AI scribe, image storage) อยู่บน public cloud — เมื่อ cloud provider มี outage หรือ misconfiguration โรงพยาบาลหลายแห่งหยุดพร้อมกัน [Verified]

**ตัวอย่าง:** Crowdstrike outage (ก.ค. 2567) กระทบระบบ Windows ทั่วโลก รวมถึงโรงพยาบาลที่ใช้ CrowdStrike Falcon — แม้ไม่ใช่ cyber attack แต่เป็น "single point of failure" ที่ทำให้ระบบล่ม [Verified]

**ผลกระทบ:** downtime ของบริการที่ไม่สามารถควบคุมได้เอง ต้องมี manual fallback

### 3.7 AI-assisted Attack

**คืออะไร:** ผู้โจมตีใช้ LLM และ AI เพื่อ

- เขียน phishing email ที่ personalize ต่อเป้าหมาย (เช่น ใช้ชื่อหัวหน้าหอผู้ป่วยจริง อ้างอิง case ที่กำลังรักษาจริง)
- สร้าง deepfake voice ของผู้บริหารโรงพยาบาล โทรขอรหัสจากเจ้าหน้าที่
- สร้าง deepfake video ของแพทย์ ขอใบสั่งยา
- สแกนช่องโหว่และเขียน exploit อัตโนมัติ
- สร้าง synthetic identity เพื่อหลอก identity verification

[Verified] (FBI/CISA, 2024 — deepfake advisory; ENISA, 2025)

**สถานะปัจจุบัน:** ยังอยู่ในขั้น emerging แต่เพิ่มขึ้นเรื่อยๆ [Likely]

### 3.8 Deepfake Voice Fraud ต่อ Clinicians

**คืออะไร:** deepfake voice ที่เลียนเสียงผู้บริหาร/แพทย์ โทรเข้ามือถือของพยาบาล/เจ้าหน้าที่ ขอทำธุรกรรมทางการเงิน หรือขอรหัสผ่าน/OTP ในปี 2567–2568 มีรายงานหลายกรณีในเอเชีย (ฮ่องกง, ญี่ปุ่น) [Verified] (FBI, 2024)

**ผลกระทบ:** ถ้าพยาบาลถูกหลอก อาจถูก compromise บัญชีที่เข้าถึง EHR → เป็นช่องทางสู่ data breach

### 3.9 Insider Threat

**คืออะไร:** เจ้าหน้าที่ (ทั้งตั้งใจและไม่ตั้งใจ) เป็นสาเหตุของ incident — เช่น ดาวน์โหลดข้อมูลผู้ป่วยไปใช้ส่วนตัว, แชร์ password, เสียบ USB ส่วนตัวที่ติด malware, หรือตั้งใจก่อวินาที [Verified] (ENISA, 2024)

**สถานะปัจจุบัน:** insider เป็นสาเหตุของ data breach ใน healthcare ราว 25–35% [Verified] (HIMSS, 2024)

## 4. Nursing Workflow Impact Map

Lens: Stakeholder mapping + Precautionary principle

ตารางต่อไปนี้จับคู่ "ประเภทภัยคุกคาม" กับ "กระบวนการทำงานของพยาบาล" เพื่อให้เห็นชัดว่าเมื่อไหร่ พยาบาลจะ "รู้สึก" ผลกระทบจริง

| Workflow ของพยาบาล | ภัยคุกคามที่กระทบโดยตรง | ผลกระทบที่เห็นได้ | Confidence |
|---|---|---|---|
| Medication administration (MAR/BCMA) | Ransomware on EHR · OT compromise on smart pump | กลับไปใช้กระดาษ · คำนวณ drip rate ด้วยมือ · เสี่ยง medication error เพิ่ม 2–3 เท่า | [Verified] |
| Vital signs & monitoring | Central monitor compromise · IoMT firmware | ต้องเดินวัด manual · ดู alarm แบบ point-of-care · พลาด early warning | [Verified] |
| Patient handoff/hand-over | EHR downtime · Slack/Teams outage | ส่งเวรด้วยวาจา + whiteboard · ความเสี่ยงตกหล่นข้อมูลสูง | [Likely] |
| Telehealth / Remote nursing | Cloud outage · Vendor breach | นัด telehealth ถูกยกเลิก · RPM data ไม่เข้า EHR | [Verified] |
| Scheduling/HR system | Ransomware · BEC fraud | ไม่รู้ตารางเวร · payroll ผิดพลาด | [Likely] |
| Lab/Radiology order | PACS compromise · LIS downtime | รอผลนาน · ตัดสินใจทางคลินิกโดยไม่มีผลแล็บ | [Likely] |
| Discharge planning | Patient portal compromise | ผู้ป่วยไม่เห็นนัด · medication reconciliation ล่าช้า | [Speculative] |
| AI scribe / ambient documentation | AI vendor breach · prompt injection | บันทึกอาจมี hallucination · หรือหยุดทำงาน | [Speculative — emerging] |

**[Verified]** กรณีศึกษา Change Healthcare และ ransomware หลายเหตุการณ์ในยุโรปยืนยันผลกระทบ 5 บรรทัดแรก (HHS, 2024; ENISA, 2024)

## 5. STEEP Drivers: ทำไมความเสี่ยงจึงเพิ่มขึ้น

Lens: STEEP + Precautionary principle

### S — สังคม (Social)

- บุคลากรทางคลินิกขาดแคลน → พยาบาลทำงานล้น ไม่มีเวลาเรียนรู้เรื่อง security hygiene [Likely]
- รุ่นใหม่คุ้นกับ BYOD (เอาโทรศัพท์ส่วนตัวมาทำงาน) → เพิ่ม attack surface [Likely]
- ผู้ป่วยคาดหวัง digital service → กดดันให้ deploy เร็วโดยไม่ทัน audit [Speculative]

### T — เทคโนโลยี (Technology)

- IoMT/IoT เพิ่มจำนวนมหาศาล — ทุกเตียงมี 5–10 connected device [Verified] (HIMSS, 2024)
- AI/ML ในอุปกรณ์การแพทย์ (FDA AI/ML SaMD > 1,000 รายการ) — เพิ่ม attack surface ใหม่ที่ security practice ยังตามไม่ทัน [Verified] (FDA, 2025)
- LLM และ generative AI → AI-assisted attack + deepfake [Likely — emerging]
- Cloud-native EHR → single point of failure ของ vendor [Verified]

### E — เศรษฐกิจ (Economic)

- งบ cybersecurity ของโรงพยาบาลส่วนใหญ่ในไทยต่ำกว่า 1% ของงบ IT (เทียบกับค่าเฉลี่ย OECD ที่ 5–8%) [Speculative — illustrative; ตัวเลขไทยไม่เปิดเผยอย่างเป็นทางการ]
- ค่าเสียหายเฉลี่ยต่อ data breach ใน healthcare สูงที่สุดในบรรดาอุตสาหกรรมทั้งหมด (ราว 11 ล้าน USD/เหตุการณ์ สหรัฐฯ 2024) [Verified] (IBM Cost of a Data Breach Report, 2024 — Tier 2)

### E — สิ่งแวดล้อม (Environmental)

- climate change → เหตุฉุกเฉิน (น้ำท่วม ไฟไหม้) ทำลาย data center บ่อยขึ้น → ต้องมี disaster recovery site [Speculative]
- การลดคาร์บอนด้วย cloud consolidation → ลด on-prem resilience [Speculative]

### P — นโยบายและกฎหมาย (Political)

- พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล (PDPA) พ.ศ. 2565 มีโทษปรับสูงสุด 5 ล้านบาท [Verified]
- พ.ร.บ. ว่าด้วยการรักษาความมั่นคงปลอดภัยไซเบอร์ พ.ศ. 2562 กำหนดให้หน่วยงานสาธารณสุขที่สำคัญต้องปฏิบัติตามมาตรฐาน [Verified]
- สภาการพยาบาลยังไม่มี position statement เรื่อง "cyber nursing competency" [Verified — current state]
- EU AI Act + NIS2 Directive กำหนดมาตรฐาน cybersecurity สำหรับ medical device + AI [Verified — applies to vendor ที่ขายใน EU]

## 6. Horizon Scanning: สัญญาณที่ต้องจับตา

Lens: Horizon scanning

แยก "เสียงดัง" (dominant narrative) ออกจาก "สัญญาณเงียบ" (weak signal)

### เสียงดัง (เฝ้าระวังไม่ให้เชื่อง)

**สัญญาณ:** "เรามี EHR cloud แล้ว ไม่ต้องกังวลเรื่อง security" — กระแสจาก vendor

**ทำไมต้องระวัง:** Cloud แก้ปัญหา physical security ของ server แต่ไม่ได้แก้ปัญหา phishing, insider, misconfiguration, supply chain, AI-assisted attack ที่เพิ่มขึ้น

**หลักฐาน:** [Speculative — hype cycle]

### สัญญาณเงียบ (จับตา)

**สัญญาณ:** โรงพยาบาลในเอเชียเริ่มจ้าง "Chief Nursing Informatics Officer (CNIO)" ที่รับผิดชอบทั้ง clinical informatics และ nursing cyber hygiene

**ทำไมสำคัญ:** ถ้าแพร่หลาย จะเป็นกลไกที่ทำให้ "cyber awareness" ถูก embed ในโครงสร้างองค์กร ไม่ใช่ทำเป็นงานเสริมของ IT

**หลักฐาน:** [Likely — emerging in Singapore/Hong Kong]

### สัญญาณเงียบ (จับตา)

**สัญญาณ:** "Tabletop exercise" สำหรับ ransomware ที่รวมพยาบาลเข้าเป็น scenario player ครั้งแรกในโรงพยาบาลขนาดใหญ่ในสหรัฐฯ/อังกฤษ

**ทำไมสำคัญ:** จากการที่ รพ. หลายแห่งในสหรัฐฯ เริ่มออกแบบ ransomware drill ที่มีพยาบาลร่วมเล่น role จริง (เช่น ต้องคำนวณ drip rate ด้วยมือ 4 ชั่วโมง) ช่วยให้เห็น gap ระหว่างนโยบายกับปฏิบัติ

**หลักฐาน:** [Likely]

### สัญญาณเงียบ (จับตา)

**สัญญาณ:** "AI red team" สำหรับ clinical AI model — เป็นข้อกำหนดใน EU AI Act และ NIST AI RMF ในสหรัฐฯ

**ทำไมสำคัญ:** ถ้าโรงพยาบาลไทยใช้ AI clinical model (เช่น sepsis alert) ที่ซื้อจากต่างประเทศ ต้องมีกลไกตรวจสอบว่า model ไม่ถูก manipulate ในระหว่าง deploy

**หลักฐาน:** [Likely — policy direction]

### สัญญาณเงียบ (จับตา)

**สัญญาณ:** ransomware-as-a-service playbook สำหรับโรงพยาบาลเริ่มแพร่บน darknet รวมถึง "hospital EHR encryption module" สำเร็จรูป

**ทำไมสำคัญ:** barrier เข้าสู่การโจมตีโรงพยาบาลต่ำลง กลุ่มที่ไม่ใช่ state-sponsored ก็ทำได้

**หลักฐาน:** [Verified] (ENISA, 2024; HHS HC3 advisories, 2024)

## 7. Three Horizons: การเปลี่ยนผ่าน 3 ระยะ

Lens: Three Horizons (Sharpe, 2013)

### H1 — Legacy systems ที่กำลังถดถอย

- ระบบ on-prem EHR + paper backup
- Perimeter security (firewall, antivirus)
- การฝึกอบรม cyber awareness ปีละ 1 ครั้ง
- IT security ทำงานแยกจาก clinical workflow

[Verified — ยังเป็น reality ของโรงพยาบาลส่วนใหญ่ในไทย]

### H2 — ช่วงเปลี่ยนผ่าน (ปัจจุบัน — 2028)

- Hybrid cloud EHR + zero-trust architecture กำลังถูกนำมาใช้
- มี Security Operations Center (SOC) บางส่วน
- Phishing simulation เริ่มทำทุกไตรมาส
- AI ambient scribe ถูก deploy โดยไม่ผ่าน security review
- Supply chain attack เพิ่มขึ้น แต่ vendor risk management ยังไม่ครบ

[Verified — observed in leading hospitals globally]

### H3 — Emerging model (2029–2031)

- Zero-trust + continuous authentication เป็น default
- AI ทำ "AI-assisted security monitoring" ในโรงพยาบาล
- "Cyber nursing" เป็น specialty ในหลักสูตร
- Medical device security เป็น FDA premarket requirement (เป็นทางการ)
- Cyber insurance สำหรับโรงพยาบาลเป็นเงื่อนไขบังคับ

[Forecast — phase shift candidate]

## 8. ฉากทัศน์ 2×2: Workforce × Defense Maturity

Lens: Scenario planning 2×2 (Schwartz, 1991)

สร้างฉากทัศน์ 4 รูปแบบบนแกน **Nursing cyber capability** × **Hospital defense maturity** (เลือกสองแกนที่ critical ที่สุดสำหรับภาคสุขภาพ)

### A. "Resilient Care" — Capability สูง × Defense สูง [Forecast]

พยาบาลได้รับการฝึก cyber hygiene อย่างเป็นระบบ โรงพยาบาลมี zero-trust + SOC + AI-assisted monitoring + cyber drill รายไตรมาส เมื่อถูกโจมตี downtime < 24 ชั่วโมง ผู้ป่วยไม่ได้รับผลกระทบรุนแรง สภาการพยาบาลออก position statement เรื่อง cyber competency

ตัวบ่งชี้: ทุก รพ. ผ่าน phishing simulation > 95% · tablet-top exercise รายไตรมาส · zero adverse event จาก cyber ใน 5 ปี

### B. "Tech Trap" — Capability ต่ำ × Defense สูง [Forecast]

ระบบป้องกันดี แต่พยาบาลไม่ได้รับการฝึก กลายเป็นจุดอ่อนที่ผู้โจมตีใช้ social engineering ผ่านได้ ลงทุนด้านเทคโนโลยีมาก แต่ผลลัพธ์ไม่คุ้มค่า

ตัวบ่งชี้: phishing success rate > 15% · BEC incident บ่อย · staff burnout จาก false-positive alert เพิ่ม

### C. "Wild West" — Capability ต่ำ × Defense ต่ำ [Forecast — worst case]

ทั้งคนและระบบอ่อน ผู้โจมตีเจาะได้ง่าย ransomware ล่มบ่อย ข้อมูลผู้ป่วยรั่วไหล ผู้ป่วยเสียชีวิตจาก delay of care ที่ป้องกันได้ สังคมสูญเสียความเชื่อมั่นในระบบสาธารณสุข

ตัวบ่งชี้: media scandal เกี่ยวกับ patient harm จาก cyber incident · PDPA fine · nurse turnover สูง

### D. "Stalled" — Capability สูง × Defense ต่ำ [Forecast]

พยาบาลมีความรู้และทักษะ แต่ระบบป้องกันไม่ทัน การลงทุนด้านคนไม่ได้ผล เพราะ infrastructure ไม่สนับสนุน เช่น พยาบาลเห็น phishing แต่ไม่มี secure channel ให้รายงาน

ตัวบ่งชี้: incident report เพิ่มขึ้น แต่ mean-time-to-detect ไม่ลดลง · investment ใน training ไม่คืนทุน

**ฉากที่ควรเตรียมรับมากที่สุด: A (เป้าหมาย) และ C (ต้องป้องกัน)** — เพราะทั้งสองทางต้องการการลงทุน "ทั้งคนและระบบ" พร้อมกัน [Likely]

## 9. Implications by Stakeholder

Lens: Stakeholder mapping

### สำหรับสภาการพยาบาล (Thailand Nursing and Midwifery Council)

- ออก position statement เรื่อง "Cybersecurity competency เป็นส่วนหนึ่งของจรรยาบรรณวิชาชีพ" [Forecast]
- บรรจุ "cyber nursing" ใน CNEU อย่างน้อย 5 ชั่วโมง/ปี [Likely]
- ร่วมกับ สปสช. ออก minimum standard สำหรับ cyber safety ของสถานพยาบาลทุกระดับ [Likely]

### สำหรับผู้บริหารโรงพยาบาล (CNO/CIO/ผอ.)

- จัดทำ "Cyber Incident Response Playbook สำหรับ Nursing Service" ไม่ใช่แค่ของ IT [Likely]
- Tablet-top exercise รายไตรมาส ที่มีพยาบาลร่วมเล่น role [Likely]
- Backup station (downtime procedure) สำหรับ medication, vital signs, handoff [Verified — required by Joint Commission International]
- ลงทุนใน identity & access management + zero-trust สำหรับ EHR [Verified]

### สำหรับหัวหน้าหอผู้ป่วย

- ฝึก "ransomware drill" กับทีม — โดยเฉพาะ BCMA downtime และ smart pump offline [Likely]
- ทำ "manual mode" refresher ทุก 6 เดือน [Likely]
- ตั้ง "Cyber Safety Champion" ใน ward (พยาบาล 1 คนที่รับผิดชอบเรื่องนี้) [Speculative]

### สำหรับคณะพยาบาลศาสตร์

- บรรจุ "Introduction to Healthcare Cybersecurity" เป็น core subject (1–2 หน่วยกิต) [Likely]
- สอนเคสศึกษาจริง (Change Healthcare, WannaCry, LockBit) เพื่อให้นักศึกษาเห็นผลกระทบต่อผู้ป่วย [Likely]
- ฝึก "report suspicious activity" เป็น nursing skill [Speculative]

### สำหรับพยาบาลหน้างาน

- เรียนรู้สัญญาณเตือนต้นๆ ของ phishing, social engineering, deepfake [Likely]
- ฝึก "manual mode" ของอุปกรณ์ที่ตนเองใช้ทุกวัน [Likely]
- รู้ว่าจะรายงานเหตุผิดปกติทาง IT security ได้ที่ไหน [Verified — required practice]

### สำหรับผู้ป่วย

- สอนเรื่อง "phishing เกี่ยวกับผลแล็บ" และ "portal security" เป็นส่วนหนึ่งของ discharge education [Speculative]

## 10. 5 ข้อเสนอแนะเชิงกลยุทธ์

Lens: Precautionary principle + Stakeholder mapping

1. **จัดทำ "Cyber Nursing Competency Framework" สำหรับไทย** ให้สภาการพยาบาลร่วมกับ สปสช. และ ETDA พัฒนา มาตรฐาน competency 5 ระดับ (พยาบาลทั่วไป → nurse informaticist → CNIO) [Likely]

2. **บังคับ "Tablet-top Ransomware Drill" รายไตรมาส** โดยมีพยาบาลเป็น scenario player ไม่ใช่ผู้สังเกตการณ์ — drill ต้องรวม "medication downtime" "vital sign downtime" และ "handoff downtime" [Likely]

3. **กำหนด "Minimum Cyber Hygiene" สำหรับ medical device procurement** ทุก RFP ต้องมี security clause — firmware update frequency, SBOM (software bill of materials), default password policy, end-of-life plan [Verified — best practice from CISA HPH CPGs, 2024]

4. **สร้าง "Healthcare ISAC" ของไทย** Information Sharing and Analysis Center ที่โรงพยาบาลและ vendor แชร์ threat intelligence แบบ real-time ตามแบบ H-ISAC ของสหรัฐฯ [Speculative — governance]

5. **บรรจุ "Cyber Nursing" ในหลักสูตรพยาบาลทุกระดับ** ให้พยาบาลจบใหม่ทุกคนมีความรู้พื้นฐานด้าน cyber hygiene, deepfake awareness, และ incident reporting [Likely]

## 11. บทส่งท้าย

Cyber attack ในโรงพยาบาลไม่ใช่ปัญหาไอที แต่เป็นปัญหาความปลอดภัยของผู้ป่วยและความยั่งยืนของวิชาชีพพยาบาล เมื่อ EHR ล่ม ผู้ที่ต้องกลับไปเขียนกระดาษคือพยาบาล เมื่อ smart pump ค้าง ผู้ที่ต้องคำนวณ drip rate ด้วยมือคือพยาบาล เมื่อ alert ดับ ผู้ที่ต้องเดินวัด vital signs ด้วยตัวเองคือพยาบาล เมื่อ deepfake voice หลอกขอรหัส ผู้ที่รับสายคือพยาบาล ดังนั้น cyber awareness จึงเป็น core competency ไม่ใช่ทักษะเสริม

เอกสารฉบับนี้ไม่ได้บอกว่า "จะเกิด ransomware เมื่อไหร่" หรือ "จะเสียหายเท่าไหร่" แต่บอกว่า **ถ้าไม่เตรียมตัว ผลกระทบจะตกที่ผู้ป่วยและพยาบาลก่อน** คำถามไม่ใช่ "จะถูกโจมตีหรือไม่" แต่คือ "เมื่อถูกโจมตี พยาบาลจะตอบสนองได้เร็วแค่ไหน และผู้ป่วยจะปลอดภัยแค่ไหน" วิชาชีพพยาบาลมีโอกาสเป็น "ผู้นำ" ในการกำหนดว่า cyber resilience ของโรงพยาบาลจะเป็นอย่างไร ไม่ใช่ "ผู้ตาม" ที่ถูก IT department กำหนด ผู้ที่จะทำหน้าที่นี้ได้ต้องเข้าใจทั้งภัยคุกคาม ผลกระทบต่อ workflow และกลไกป้องกันที่ตนเองมีส่วนร่วมได้

* * *

## เอกสารอ้างอิง

รูปแบบการอ้างอิง: APA 7th edition · เรียงตามตัวอักษรของชื่อผู้แต่ง/องค์กร · Tier 1 = รัฐ/หน่วยงานกำกับดูแล/peer-reviewed · Tier 2 = รายงาน sectoral · Tier 3 = บทความ peer-reviewed เฉพาะทาง · Tier 4 = industry/blog/analyst

- American Hospital Association. (2024). *Cybersecurity advisory: Ransomware and phishing trends in healthcare*. AHA. (Tier 1)
- CISA. (2024). *Health care and public health (HPH) sector cybersecurity performance goals*. Cybersecurity and Infrastructure Security Agency. https://www.cisa.gov/ (Tier 1)
- ENISA. (2024). *ENISA threat landscape 2024 — Health sector*. European Union Agency for Cybersecurity. https://www.enisa.europa.eu/publications/enisa-threat-landscape-2024 (Tier 1)
- ENISA. (2025). *AI-enabled threat landscape report*. European Union Agency for Cybersecurity. (Tier 1)
- FBI / CISA. (2024). *Advisory: Threat actors use AI-generated voice cloning in social engineering attacks*. https://www.cisa.gov/ (Tier 1)
- FDA. (2025). *Artificial Intelligence and Machine Learning (AI/ML)-Enabled Medical Devices*. U.S. Food and Drug Administration. https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices (Tier 1)
- HHS Health Sector Cybersecurity Coordination Center (HC3). (2024). *Threat briefings and alerts archive*. U.S. Department of Health and Human Services. https://www.hhs.gov/about/agencies/asa/ocio-hc3/ (Tier 1)
- HIMSS. (2024). *2024 HIMSS nursing informatics workforce survey*. Healthcare Information and Management Systems Society. (Tier 2)
- IBM Security. (2024). *Cost of a data breach report 2024 — Healthcare industry*. IBM. https://www.ibm.com/security/data-breach (Tier 2)
- NHS England. (2024). *WannaCry retrospective and lessons learned*. (Tier 1)
- NIST. (2024). *AI risk management framework (AI RMF)*. National Institute of Standards and Technology. https://www.nist.gov/itl/ai-risk-management-framework (Tier 1)
- Schwartz, P. (1991). *The art of the long view: Planning for the future in an uncertain world*. Doubleday. (Foundational text on scenario planning 2×2)
- Sharpe, B. (2013). *Three horizons: The patterning of hope*. Triarchy Press. (Foundational text on Three Horizons framework)
- U.S. Department of Health and Human Services. (2024). *Change Healthcare cyber attack: Federal response and sector impact report*. HHS. (Tier 1)
- World Economic Forum. (2025). *The future of AI-enabled health: Leading the way*. WEF & BCG. https://www.weforum.org/ (Tier 2)
- World Health Organization. (2024). *Global patient safety action plan 2021–2030: Mid-term review*. WHO. (Tier 1)
- พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล พ.ศ. 2565. (2022). ราชกิจจานุเบกษา. (Tier 1)
- พ.ร.บ. ว่าด้วยการรักษาความมั่นคงปลอดภัยไซเบอร์ พ.ศ. 2562. (2019). ราชกิจจานุเบกษา. (Tier 1)
- สภาการพยาบาล. (2569). *เว็บไซต์สภาการพยาบาล*. https://www.tnmc.or.th/ (Tier 1)

**หมายเหตุด้านหลักฐาน:**
1. การอ้างอิง Change Healthcare, WannaCry, LockBit, CrowdStrike outage เป็นเหตุการณ์จริงที่มีรายงานต่อสาธารณะจากหน่วยงานรัฐ (HHS, NCSC UK, ENISA) และสื่อระดับ Tier 1
2. ตัวเลขเชิงปริมาณระดับประเทศไทย (จำนวน รพ. ที่ถูกโจมตี, สัดส่วนงบ cybersecurity) ยังไม่เปิดเผยอย่างเป็นทางการ — ในเอกสารนี้จึง tag เป็น [Speculative] หรือเปรียบเทียบกับค่าเฉลี่ย OECD/สหรัฐฯ เท่านั้น
3. กรณีศึกษา "ransomware drill ที่มีพยาบาลเป็น scenario player" เป็น best practice ที่เริ่มเห็นในโรงพยาบาลชั้นนำของสหรัฐฯ/อังกฤษ ยังไม่มีรายงาน formal ในไทย
4. ตัวเลขค่าเสียหาย "11 ล้าน USD/เหตุการณ์ ใน healthcare สหรัฐฯ 2024" มาจาก IBM Cost of a Data Breach Report ประจำปี (Tier 2 industry report) ตัวเลขสำหรับไทยไม่มีข้อมูลเปรียบเทียบโดยตรง
5. เอกสารนี้ตั้งใจให้ข้อมูลเชิงทิศทางมากกว่าตัวเลขเชิงสถิติแม่นยำสำหรับบริบทไทย ควรตรวจสอบข้อมูลเชิงปริมาณจาก สธ./สปสช./ETDA ก่อนนำไปใช้อ้างอิงเชิงนโยบาย