---
Type: Analysis
Category: Procurement
Ingested: 2026-04-23
---

# Perbandingan Vendor Mesin Tenun (Weaving Machine Vendor Comparison)

## Overview

This analysis compares three major weaving machine vendors evaluated by PT Maju Bersama Manufacturing during the 2021-2023 automation initiative ([Sistem Tenun Otomatis (Automated Weaving System)](mesin-tenun-otomatis.md)). The final selection was ITEMA (Italy), but the evaluation process revealed important trade-offs.

**Decision Context:** Need 260 rapier looms across both factories ([Pabrik Cimahi](pabrik-cimahi.md) + [Pabrik Lembang](pabrik-lembang.md))

## Vendor Comparison Matrix

| Criteria | ITEMA (Italy) | Picanol (Belgium) | Toyota (Japan) |
|----------|---------------|-------------------|----------------|
| **Model Evaluated** | R9000 | OmniPlus-i | JAT810 |
| **Price per Loom (IDR)** | 300M | 285M | 320M |
| **Speed (rpm)** | 850 | 820 | 800 |
| **Energy Use (kWh/100m)** | 28 | 32 | 26 ✅ |
| **IoT Capability** | OPC-UA (native) ✅ | Proprietary (adapter needed) | MTConnect (good) |
| **Local Support** | Jakarta office | Surabaya agent | Jakarta office ✅ |
| **Spare Parts Lead Time** | 3-4 weeks | 2-3 weeks ✅ | 1-2 weeks ✅ |
| **Training Included** | 3 trainers, 6 months ✅ | 1 trainer, 3 months | 2 trainers, 4 months |
| **Warranty** | 2 years | 2 years | 3 years ✅ |
| **Financing (via Mandiri)** | 8.5% p.a. ✅ | 9.0% p.a. | 8.75% p.a. |
| **Integration with ERP** | Seamless (Oracle NetSuite) ✅ | Requires middleware | Good (custom API) |

**Total Cost (260 looms + support):**
- ITEMA: IDR 78B
- Picanol: IDR 74.1B
- Toyota: IDR 83.2B

## Scoring (Weighted)

| Criteria | Weight | ITEMA | Picanol | Toyota |
|-----------|--------|--------|---------|--------|
| Price | 20% | 8/10 | 9/10 ✅ | 7/10 |
| Performance | 25% | 10/10 ✅ | 8/10 | 8/10 |
| IoT/Integration | 20% | 10/10 ✅ | 6/10 | 8/10 |
| Local Support | 15% | 8/10 | 7/10 | 10/10 ✅ |
| Training | 10% | 10/10 ✅ | 5/10 | 7/10 |
| Financing | 10% | 10/10 ✅ | 8/10 | 9/10 |
| **Weighted Score** | **100%** | **9.4/10** ✅ | **7.4/10** | **8.3/10** |

**Winner: ITEMA (9.4/10)**

## Why ITEMA Won

### 1. IoT Integration ([Heryanto Prasetyo](heryanto-prasetyo.md)'s Key Requirement)
- Native OPC-UA support → seamless connection to Oracle NetSuite ([Key Decisions 2023 — PT Maju Bersama Manufacturing](keputusan-2023.md))
- Real-time monitoring: 12 sensors per machine (vibration, temp, tension, picks/cm)
- Predictive maintenance: Reduced downtime 40%

### 2. Training Package
- 3 trainers on-site for 6 months (vs 1-2 from competitors)
- Result: 500 operators trained ([Key Decisions 2023 — PT Maju Bersama Manufacturing](keputusan-2023.md) upskilling program)
- In-house certification program established

### 3. Financing
- Best rate through [PT Bank Mandiri (Persero) Tbk](pt-bank-mandiri.md) (8.5% vs 9.0%/8.75%)
- Longer tenor: 7 years (vs 5 years from others)
- Monthly payment aligned with production cycles

### 4. Performance
- Highest speed: 850 rpm (Picanol: 820, Toyota: 800)
- Better fabric quality: 15% fewer defects (vs baseline)
- Compatible with [Tekstil Teknis (Technical Textiles)](tekstil-teknis.md) requirements (automotive specs)

## Why Not Picanol (Lowest Price)?

- **IoT Problem:** Proprietary protocol, needed expensive middleware (IDR 1.2B extra)
- **Training Gap:** Only 1 trainer, 3 months → inexperienced operators
- **ERP Integration:** Would delay [Key Decisions 2023 — PT Maju Bersama Manufacturing](keputusan-2023.md) timeline by 4 months

## Why Not Toyota (Best Support)?

- **Price:** IDR 5.2B more expensive than ITEMA
- **Speed:** Slowest (800 rpm vs 850 rpm)
- **Financing:** Less favorable terms (8.75%, 5-year tenor)

## Implementation Outcome (Post-Decision Review)

### Success Metrics (2023 vs 2022)
- ✅ Productivity: +35% (met target)
- ✅ Defect Rate: 3.4% → 2.1% (exceeded target of 2.5%)
- ✅ Downtime: -40% (predictive maintenance working)
- ✅ Training: 500 operators certified ([Ratna Sari](ratna-sari.md)'s program)

### Issues Encountered
- ⚠️ Spare parts delay: 4-5 weeks (vs 3-4 promised) → [Heryanto Prasetyo](heryanto-prasetyo.md) negotiating local warehouse
- ⚠️ [Serikat Pekerja PT Maju Bersama](serikat-pekerja.md) initial resistance → resolved via upskilling program
- ✅ No major breakdowns in first 24 months (reliability confirmed)

## Decision Quality: 9/10

**Why not 10/10?** Should have negotiated local spare parts warehouse upfront (current 4-5 week lead time is risky for production continuity).

## Connected Pages

[Sistem Tenun Otomatis (Automated Weaving System)](mesin-tenun-otomatis.md) [Heryanto Prasetyo](heryanto-prasetyo.md) [Ratna Sari](ratna-sari.md) [Pabrik Cimahi](pabrik-cimahi.md) [Pabrik Lembang](pabrik-lembang.md) [Key Decisions 2023 — PT Maju Bersama Manufacturing](keputusan-2023.md) [PT Bank Mandiri (Persero) Tbk](pt-bank-mandiri.md) [Serikat Pekerja PT Maju Bersama](serikat-pekerja.md) [Tekstil Teknis (Technical Textiles)](tekstil-teknis.md)

## Sources

- Vendor Evaluation Report 2021 (internal)
- [Key Decisions 2023 — PT Maju Bersama Manufacturing](keputusan-2023.md) (Phase 2 approvals)
- ITEMA R9000 Technical Manual
- Interview with [Heryanto Prasetyo](heryanto-prasetyo.md), 2023-08-20
