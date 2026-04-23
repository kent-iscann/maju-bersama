---
Type: Operational Process
Category: Quality Assurance
Ingested: 2026-04-23
---

# Quality Control System (Sistem Kontrol Kualitas)

## Overview

The Quality Control System at PT Maju Bersama Manufacturing is a multi-layered quality assurance framework ensuring all products meet customer specifications and international standards. Led by [[ahmad-darmawan]] (Production Director), the system has achieved a defect rate reduction from 3.4% (2022) to 2.1% (2023).

**System Details:**
- **Framework:** ISO 9001:2015 + IATF 16949:2016 (automotive)
- **QC Staff:** 85 people (5% of total workforce)
- **Key Tools:** Statistical Process Control (SPC), IoT sensors, laboratory testing
- **Integration:** Oracle NetSuite ERP ([[keputusan-2023]]) for traceability

## QC Layers (4-Tier System)

### Tier 1: Incoming Materials (Raw Fabric, Yarn, Dyes)
- **Tests:** Tensile strength, color fastness, shrinkage, pH
- **Sampling:** AQL 1.0 (Acceptable Quality Limit)
- **Rejection Rate (2023):** 2.8% (down from 4.1% in 2022)
- **Location:** Labs at [[pabrik-cimahi]] and [[pabrik-lembang]]

### Tier 2: In-Process (During Production)
- **Monitoring:** 12 IoT sensors per [[mesin-tenun-otomatis]] (vibration, tension, temp)
- **SPC Charts:** Real-time control charts for critical parameters
- **Automated Stops:** Machine stops if out-of-spec (prevents defect propagation)
- **Defect Detection Rate:** 92% (in-process, before finishing)

### Tier 3: Finished Goods (Pre-Shipment)
- **AQL Levels:** 
  - [[batik-tradisional]]: 2.5 (premium segment)
  - [[pakaian-siap-pakai]]: 4.0 (contract manufacturing)
  - [[tekstil-teknis]]: 1.0 (automotive, IATF 16949 requirement)
  - [[ppe-medis]]: 1.0 (medical device, ISO 13485 requirement)
- **Tests:** Dimensional checks, visual inspection, functionality tests
- **Final Defect Rate (2023):** 2.1% (down from 3.4% in 2022)

### Tier 4: Customer Feedback (Post-Shipment)
- **Complaint Tracking:** Oracle NetSuite CRM module
- **RMA (Return Merchandise Authorization):** <0.5% of shipments (2023)
- **Corrective Actions:** CAPA (Corrective and Preventive Action) system
- **Customer Satisfaction:** 97.8% (2023, up from 95.2% in 2022)

## Laboratory Capabilities

### Pabrik Cimahi Lab (Traditional Textiles & Garments)
- **Equipment:** Color matching booth, wash fastness tester, tensile tester
- **Tests:** 18 test methods (ISO, AATCC, SNI standards)
- **Certifications:** ISO 17025 accredited (since 2018)

### Pabrik Lembang Lab (Technical Textiles)
- **Equipment:** Martindale abrasion tester, flammability chamber, UV tester
- **Tests:** 24 test methods (IATF 16949, SAE, JIS standards)
- **Automotive-Specific:** Toyota specs, Honda standards, Daihatsu requirements

## Integration with [[mesin-tenun-otomatis]]

### IoT Sensors (12 per Machine)
1. **Vibration** — Detects loom imbalance (prevents fabric defects)
2. **Temperature** — Motor/bearing overheating warning
3. **Weft Tension** — Ensures consistent fabric density
4. **Picks per cm** — Real-time weave density monitoring
5. **Fabric Width** — Continuous width measurement
6. **Stop Motion** — Immediate stop on yarn breakage
... (6 more sensors)

### Data Flow
Machine Sensors → Siemens PLC → OPC-UA → Oracle NetSuite → QC Dashboard
- **Real-time Alerts:** QC team notified within 30 seconds of defect detection
- **Predictive Maintenance:** Vibration trends predict bearing failure 2 weeks in advance
- **Result:** Downtime reduced 40% (2023 vs 2022)

## Certifications Maintained

| Certification | Scope | Facility | Annual Audit |
|---------------|--------|-----------|--------------|
| ISO 9001:2015 | Quality Management | Both factories | ✅ Passed 2023 |
| IATF 16949:2016 | Automotive Quality | [[pabrik-lembang]] | ✅ Passed 2023 |
| ISO 13485:2016 | Medical Devices | [[pabrik-cimahi]] | ✅ Passed 2023 |
| OEKO-TEX Std 100 | Harmless Textiles | Both factories | ✅ Certified 2023 |
| ISO 17025 | Lab Competence | Both labs | ✅ Accredited 2023 |

## Key Performance Indicators (2023 vs 2022)

| Metric | 2022 | 2023 | Change |
|--------|------|------|--------|
| Defect Rate | 3.4% | 2.1% | -38% ✅ |
| First Pass Yield | 92.3% | 96.2% | +4.2pp ✅ |
| Customer Complaints | 87 | 52 | -40% ✅ |
| RMA Rate | 0.8% | 0.5% | -37.5% ✅ |
| On-Time Delivery | 94.5% | 97.8% | +3.5pp ✅ |

## Led by [[ahmad-darmawan]] (Production Director)

**Key Initiatives (2023):**
1. **Automated Inspection:** Computer vision pilot (Q4 2023, 15% defect detection improvement)
2. **Supplier Quality:** Reduced incoming material rejection from 4.1% to 2.8%
3. **Training:** 200 QC staff upskilled (part of [[keputusan-2023]] upskilling program)
4. **Digital Integration:** Full traceability via Oracle NetSuite ([[keputusan-2023]])

## Future Plans (2024-2026)

1. **AI-Powered Inspection:** Computer vision for 100% fabric inspection (pilot Q3 2024)
2. **Blockchain Traceability:** Track quality from yarn to finished garment (2025)
3. **Lab Expansion:** New [[pabrik-lembang]] lab for EV battery textiles (2025)
4. **Six Sigma:** 50 Green Belts, 10 Black Belts by 2026 ([[keputusan-2023]] upskilling)

## Connected Pages

[[ahmad-darmawan]] [[mesin-tenun-otomatis]] [[pabrik-cimahi]] [[pabrik-lembang]] [[keputusan-2023]] [[batik-tradisional]] [[pakaian-siap-pakai]] [[tekstil-teknis]] [[ppe-medis]] [[transformasi-digital]] [[toray-industries]]

## Sources

- Quality Control Manual (internal, 2023 edition)
- [[keputusan-2023]] (upskilling program funding)
- ISO 9001:2015 Audit Report, 2023-09-15
- "Quality in Indonesian Textiles" — Quality Asia Magazine, 2023-11-08
