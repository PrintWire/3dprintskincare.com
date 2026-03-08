---
title: "Skin-Safe 3D Printing Materials: ISO 10993 Biocompatibility for Beauty Devices"
date: 2026-03-08
summary: "Not all 3D printing resins are safe for sustained skin contact. This guide covers which materials pass ISO 10993 biocompatibility testing and what that means for facial device development."
tags: ["materials", "biocompatibility", "SLA", "ISO 10993", "skin-safe"]
---

When a beauty brand specifies a 3D-printed facial tool or device housing, the material
question is not aesthetic — it's regulatory. Sustained skin contact (> 24 hours cumulative)
requires ISO 10993 biocompatibility assessment. Brief skin contact (< 24 hours) applies
a less stringent standard but still mandates absence of known sensitizers.

## ISO 10993 Categories That Apply to Skincare Devices

| Contact Type | Duration | Tests Required |
|-------------|----------|----------------|
| Surface contact, intact skin | Brief (< 24h) | Cytotoxicity (10993-5) |
| Surface contact, intact skin | Prolonged (24h–30d) | + Sensitization (10993-10) |
| Surface contact, intact skin | Permanent (> 30d) | + Irritation, systemic toxicity |

Most facial devices — rollers, gua sha, cleansing heads — fall into the "brief contact"
category. Daily use requires cumulative assessment.

## Cleared Materials by Process

**SLA (stereolithography):**
- Formlabs BioMed White Resin — cleared ISO 10993-5/10; USP Class VI
- Formlabs Dental LT Clear — extended oral/skin contact cleared
- DSM Somos WaterShed XC 11122 — long-standing body-contact clearance

**SLS / MJF (powder bed):**
- PA 12 (nylon 12) — ISO 10993-5 cytotoxicity passed by most major suppliers
- TPU powders — variable by formulation; request supplier certificate

**FDM:**
- Medical-grade PEEK — highest biocompatibility; also highest cost
- PP (polypropylene) — commodity material, good skin tolerance, limited finish quality

## Post-Processing Matters

Unfinished SLA parts have residual monomer that is cytotoxic. Proper post-cure
(405 nm UV, ≥ 60 minutes) is mandatory. Parts should be washed in isopropyl alcohol
(≥ 90%), dried, and post-cured before any skin contact. Service bureaus offering
skin-contact parts should provide post-cure records with each order.
