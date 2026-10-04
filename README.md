# VirtualWorks-Task-3--Causality-Assessment
# Task 3: Causality Assessment in Pharmacovigilance

## Overview
This repository contains the comprehensive causality assessment performed for **Task 3** as part of the Pharmacovigilance Internship Program at VirtualWorks.

The objective of causality assessment (relatedness assessment) is to systematically evaluate the causal relationship between drug exposure and an observed adverse event, determining whether the event qualifies as an **Adverse Drug Reaction (ADR)**.

---

## Key Pharmacovigilance Concepts Covered
- **Adverse Event (AE) vs. Adverse Drug Reaction (ADR):** An AE remains an event until a causal relationship is evaluated. Once causality is confirmed, it is classified as an ADR.
- **Key Determinants of Causality:**
  - **Drug-Related:** Labeledness, predisposing factors, concomitant medications.
  - **Patient-Related:** Medical history, prior hypersensitivities, pharmacogenomics.
  - **Clinical Factors:** Temporal onset, response to corrective treatment, Dechallenge, and Rechallenge.

---

## Case Study Analysis: Amoxicillin-Induced Rash

### Patient Scenario Details
- **Patient Name / ID:** Raj
- **Suspect Medication:** Amoxicillin 500 mg TID (oral)
- **Indication:** Throat Infection
- **Adverse Event:** Generalized itchy rashes
- **Timeline & Clinical Course:**
  - **June 1:** Initiated Amoxicillin 500 mg TID.
  - **June 2:** Developed itchy rashes across the body.
  - **June 3:** Dose reduced to 250 mg TID (Dechallenge) $\rightarrow$ Rash disappeared on June 4.
  - **June 5:** Dose increased back to 500 mg TID due to infection severity $\rightarrow$ Developed generalized itchy rashes again on June 6 (Rechallenge).

---

## Causality Assessment Evaluations

### 1. Naranjo Algorithm Assessment

| # | Question / Parameter | Score | Justification |
|---|---|:---:|---|
| 1 | Are there previous conclusive reports on this reaction? | **+1** | Amoxicillin (Penicillin derivative) is well-documented to cause hypersensitivity/cutaneous rashes. |
| 2 | Did the adverse event appear after the suspect drug was administered? | **+2** | Onset occurred on June 2, following drug administration on June 1. |
| 3 | Did the adverse reaction improve when the drug was discontinued or dose reduced? | **+1** | Positive Dechallenge: Rash disappeared after reducing dose to 250 mg. |
| 4 | Did the adverse reaction reappear when the drug was re-administered? | **+2** | Positive Rechallenge: Rash recurred when dose was re-increased to 500 mg. |
| 5 | Are there alternative causes that could on their own have caused the reaction? | **+0** | No alternative etiology reported. |
| 6 | Was the drug detected in blood/fluids in toxic concentrations? | **0** | Blood levels not measured. |
| 7 | Was the reaction more severe when the dose was increased / less severe when decreased? | **+1** | Symptom intensity directly correlated with dosage changes. |
| 8 | Did the patient have a similar reaction to the same or similar drugs in the past? | **0** | Past exposure history unavailable. |
| 9 | Was the adverse event confirmed by objective evidence? | **0** | Clinical observation documented without lab confirmation. |
| 10 | Was the drug re-administered? | **0** | Captured under Rechallenge question. |

* **Total Naranjo Score:** **7 / 10**
* **Naranjo Classification:** **Probable** (Score 5–8) / **Definite** (Score $\ge$ 9 depending on clinical evaluation of rechallenge severity).

---

### 2. WHO-UMC Causality Assessment

* **Category Assigned:** **Certain**
* **Rationale:**
  1. Clear temporal relationship between drug intake and event onset.
  2. Positive Dechallenge (resolution upon dose reduction).
  3. Positive Rechallenge (recurrence upon dose re-escalation).
  4. Event cannot be explained by concurrent disease or other drugs.

---

## Conclusion
Based on both the **Naranjo Algorithm** and the **WHO-UMC Causality Scale**, the generalized itchy rash experienced by the patient is causally related to **Amoxicillin** and is classified as an **Adverse Drug Reaction (ADR)**.
