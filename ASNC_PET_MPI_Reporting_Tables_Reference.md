# ASNC PET MPI Reporting Tables Reference

[ASNC Atlas for Reporting PET MPI](https://www.journalofnuclearcardiology.org/article/S1071-3581(24)00236-8/fulltext)

---

## Table of contents

- [Qualitative LV Perfusion Assessment](#qualitative-lv-perfusion-assessment)
- [Myocardial Blood Flow (MBF) and Reserve (MFR)](#myocardial-blood-flow-mbf-and-reserve-mfr)
- [MFR Clinical Interpretation Guide](#mfr-clinical-interpretation-guide)
- [LV Gated Function and Volume](#lv-gated-function-and-volume)
- [Coronary Artery Calcium (CAC) Analysis](#coronary-artery-calcium-cac-analysis)
- [Sample Impression Statements](#sample-impression-statements)
- [References](#references)


## Qualitative LV Perfusion Assessment

A qualitative summary of left-ventricular (LV) perfusion based on standard segmental analysis.

| Variable | Description | Response options |
|---|---|---|
| **LV Perfusion Summary** | Overall assessment | Normal; Probably normal; Probably abnormal; Abnormal; Equivocal |
| **Defect Size** | Number of segments involved | Small (1–2); Medium (3–4); Large (≥ 5) |
| **Defect Severity** | Tracer reduction | Mild (10–25%); Moderate (25–50%); Severe (≥ 50%); Absent |
| **Reversibility** | Degree of change from stress to rest | Reversible; Fixed; Mildly reversible; Moderately reversible; Predominantly reversible |
| **Clinical Interpretation** | Diagnostic impression | Ischemia; Infarction; Mixed; Peri-infarct ischemia; Artifact |
| **TID** | Transient ischemic dilation | Present; Absent; Unable to assess |

*Notes:* Add a short caption or description above the table when exporting to reports to clarify the segment model (e.g., 17-segment AHA model) and any vendor-specific thresholds used for severity.


## Myocardial Blood Flow (MBF) and Reserve (MFR)

Quantitative MBF values (mL/min/g) and the derived myocardial flow reserve (MFR = Stress MBF / Rest MBF). Report both global and territorial values (LAD, LCx, RCA) when available.

| Variable | Measurement | Subjective conclusion / thresholds |
|---|---:|---|
| **Stress MBF** | mL/min/g | Preserved (> 2.0); Mildly reduced (1.5–2.0); Severely reduced (< 1.5) |
| **Rest MBF** | mL/min/g | Typical normal range: 0.6–1.1 (Ammonia); 0.7–1.2 (Rubidium-82) |
| **MFR (ratio)** | Stress / Rest | Report global and territorial (LAD, LCx, RCA) values; interpret using clinical guide below |

*Reporting tip:* When MFR is borderline, include absolute MBF values and note any technical factors (e.g., low injected activity, image quality, caffeine interference) that could affect quantification.


### MFR Clinical Interpretation Guide

This guide pairs MFR ranges with perfusion defect presence to convey clinical risk. Use it as an interpretation aide, not an absolute rule — consider the full clinical context.

| MFR value | Perfusion defect | Clinical risk |
|---:|---|---|
| **> 2.0** | +/− | Very low |
| **1.8 – 2.0** | No | Low |
| **1.8 – 2.0** | Yes | Intermediate |
| **1.4 – 1.8** | +/− | High |
| **1.2 – 1.4** | +/− | Very high |
| **< 1.2** | Yes | Highest |
| **< 1.2** | No | Suspect non-diagnostic study (e.g., recent caffeine ingestion) |

*Note:* When MFR is low but perfusion looks normal, emphasize discordance and consider further assessment (clinical correlation, repeat testing, or invasive evaluation when indicated).


## LV Gated Function and Volume

Left ventricular (LV) function and volumetric indices derived from gated PET data or hybrid imaging.

| Variable | Description |
|---|---|
| **LVEF** | Left ventricular ejection fraction expressed as a calculated percentage (%) |
| **LVEF Reserve** | Difference between stress and rest LVEF (sometimes reported for Rb-82 protocols) |
| **Wall motion** | Qualitative regional wall motion: Normal; Mild hypokinesis; Moderate hypokinesis; Severe hypokinesis; Akinesis; Dyskinesis |
| **Cavity size** | LV cavity size: Normal; Mildly enlarged; Moderately enlarged; Severely enlarged |

*Reporting tip:* Include the method used (gated SPECT-style algorithm vs vendor-specific PET gating) and normal reference ranges if your lab reports them.


## Coronary Artery Calcium (CAC) Analysis

Summary of CAC assessment when non-contrast CT or attenuation-correction CT is used for calcium scoring or visual assessment.

| Assessment type | Response / findings |
|---|---|
| **Quantitative (score)** | Agatston score (total and per vessel: LM, LAD, LCx, RCA) |
| **Percentile ranking** | Age- and sex-based percentile (if available) |
| **Qualitative (visual)** | Absent; Mild; Moderate; Severe calcification |
| **Extracardiac calcium** | Noted locations: Aortic valve; Mitral annulus; Aortic wall; Pericardium |

*Note:* When reporting Agatston scores from non-gated or low-dose CT, include a statement about limitations and whether the acquisition was ECG-gated and calibrated for scoring.


## Sample Impression Statements

Suggested impression text for common scenarios. Edit to match local reporting style and patient-specific details.

- **Normal:** “Normal myocardial perfusion and preserved myocardial flow reserve (MFR > 2.0) — study consistent with low risk for major coronary events.”

- **Discordant (Normal perfusion / Low MFR):** “Myocardial perfusion appears normal on relative perfusion imaging, but quantitative MBF/MFR are reduced. This discordance suggests impaired coronary vasodilator capacity and increased risk; correlate clinically and consider further functional or invasive evaluation.”

- **Single vessel:** “Perfusion defect in the [territory] with corresponding regional reduction in MBF/MFR consistent with single-vessel ischemia.”

- **Multivessel / Balanced reduction:** “Relative perfusion suggests limited regional defects, but MFR is globally reduced — this pattern can indicate balanced multivessel disease or diffuse microvascular dysfunction; consider coronary angiography if clinically indicated.”

- **Infarction:** “Fixed perfusion defect with corresponding wall motion abnormality and reduced resting MBF consistent with prior myocardial infarction; correlate with clinical history and prior imaging.”

- **Artifacts / Non-diagnostic:** “Study quality limited by [motion/caffeine/low counts/attenuation correction artifact]. Quantitative MBF values may be unreliable; consider repeat testing or alternative imaging if clinically required.”


## References

- ASNC Atlas for Reporting PET MPI — Journal of Nuclear Cardiology. https://www.journalofnuclearcardiology.org/article/S1071-3581(24)00236-8/fulltext


---

_Footnote:_ Converted the original HTML into clean, GitHub-friendly Markdown, removed the "Table" prefix and numbering from each table heading, added a table of contents, notes, and a references section. The new file is on the branch `convert/asnc-pet-mpi-to-md`.