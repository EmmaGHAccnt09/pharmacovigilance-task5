# Task 5: Comprehensive Individual Case Safety Report (ICSR) Assessment

**Repository Name:** `pharmacovigilance-task5`  
**Course / Internship:** Pharmacovigilance Virtual Internship (VirtualWorks Lab / Noivrn)  
**Simulation Role:** Drug Safety Associate (DSA) / Pharmacovigilance Specialist  

---

## 🎯 Case Study Scenario
* **Patient Data:** 58-year-old male (Initials: `R.M.`), Weight: 78 kg, Medical History: Type 2 Diabetes Mellitus, Dyslipidemia.
* **Suspected Drug:** **Atorvastatin** 40 mg PO QD (Brand: Lipitor), initiated September 1, 2026 for dyslipidemia.
* **Concomitant Drug:** **Clarithromycin** 500 mg PO BID added on October 5, 2026 for acute bronchitis.
* **Adverse Event:** On October 10, 2026, patient presented with severe diffuse muscle pain, dark tea-colored urine, and weakness.
* **Laboratory Findings:** Serum Creatine Kinase (CK) = 12,500 U/L (Normal: 30–200 U/L), confirming **Rhabdomyolysis**. Elevated serum creatinine (2.4 mg/dL).
* **Action Taken:** Atorvastatin and Clarithromycin immediately discontinued; IV hydration initiated in inpatient ward.
* **Outcome:** Patient recovered after 6 days of hospitalization; CK levels returned near baseline.

---

## 🛠️ Step-by-Step Drug Safety Associate (DSA) Evaluation

### Step 1: ADR Identification & MedDRA Standardization
* **Reported Event:** Severe muscle breakdown and dark urine following drug co-administration.
* **MedDRA Hierarchy Mapping:**
  * **System Organ Class (SOC):** Musculoskeletal and connective tissue disorders *(10028395)*
  * **High-Level Group Term (HLGT):** Muscle disorders *(10028245)*
  * **High-Level Term (HLT):** Myopathies *(10028610)*
  * **Preferred Term (PT):** **Rhabdomyolysis** *(10039020)*
  * **Lowest Level Term (LLT):** Acute rhabdomyolysis *(10001068)*

---

### Step 2: Seriousness & Expectedness Assessment
* **Seriousness Evaluation:** **SERIOUS**
  * **Criteria Met:** Hospitalization (Inpatient admission required for IV hydration and renal monitoring).
* **Expectedness:** **Expected (Drug-Drug Interaction / Labeled Risk)**
  * *Clinical Mechanism:* Clarithromycin is a potent **CYP3A4 inhibitor**, which significantly increased systemic exposure and plasma concentration of Atorvastatin, triggering acute statin-induced rhabdomyolysis.

---

### Step 3: Dual Causality Assessment

#### A. WHO-UMC Causality Scale
* **Category:** **CERTAIN / PROBABLE**
* **Rationale:** Plausible temporal onset following addition of CYP3A4 inhibitor; positive dechallenge upon discontinuation and hydration; well-established pharmacodynamic/pharmacokinetic interaction.

#### B. Naranjo Algorithm Scoring
| Question / Assessment Parameter | Yes | No | Do Not Know | Score |
| :--- | :---: | :---: | :---: | :---: |
| 1. Are there previous conclusive reports on this reaction? | +1 | 0 | 0 | **+1** |
| 2. Did event appear after suspected drug was administered? | +2 | -1 | 0 | **+2** |
| 3. Did reaction improve when drug was discontinued? | +1 | 0 | 0 | **+1** |
| 4. Did reaction reappear upon re-administration? | +2 | -1 | 0 | **0** |
| 5. Are there alternative causes that could cause this? | -1 | +2 | 0 | **+2** |
| 6. Did reaction reappear when placebo given? | -1 | +1 | 0 | **0** |
| 7. Was drug detected in toxic concentrations in blood? | +1 | 0 | 0 | **0** |
| 8. Was reaction more severe when dose increased? | +1 | 0 | 0 | **+1** *(CYP3A4 inhibition increased effective dose)* |
| 9. Previous similar reaction to same/similar drugs? | +1 | 0 | 0 | **0** |
| 10. Was event confirmed by objective evidence? | +1 | 0 | 0 | **+1** *(CK = 12,500 U/L)* |
| **TOTAL SCORE** | | | | **+8** *(PROBABLE)* |

---

### Step 4: Clinical Safety Narrative (DSA Draft)

> **Initial ICSR Narrative:**  
> A 58-year-old male patient (`R.M.`) with a history of dyslipidemia and diabetes developed acute rhabdomyolysis while receiving Atorvastatin 40 mg daily. The reaction occurred 5 days following the addition of Clarithromycin 500 mg BID for acute bronchitis. The patient presented with generalized myalgia, severe muscle weakness, and dark urine. Laboratory testing revealed a markedly elevated serum Creatine Kinase level of 12,500 U/L and elevated creatinine. Both drugs were discontinued, and the patient was admitted for IV rehydration therapy. The event was classified as **Serious** (hospitalization) and attributed to a drug-drug interaction driven by CYP3A4 inhibition. The patient recovered completely and was discharged after 6 days.

---

### Step 5: Regulatory Reporting Actions
1. **Submission Category:** Serious ICSR / Drug Interaction Report.
2. **Reporting Deadline:** Submitted to Regulatory Authority (e.g., Phil FDA / VigiBase) within **15 calendar days** of initial receipt.
3. **Risk Management Recommendation:** Update electronic prescribing alerts to flag strong CYP3A4 inhibitors (macrolides) when co-prescribed with CYP3A4-metabolized statins.

---

## ✒️ Reporter / Assessor Information
* **Drug Safety Associate:** Emmalyn Chua Mondano-Mariquit  
* **Professional Qualification:** Registered Pharmacist (RPh) / Healthcare Virtual Assistant Intern  
* **Date of Assessment:** October 26, 2026

  Portfolio Disclosure
This repository contains my own work, completed as part of my pharmacovigilance learning activities. The exercise demonstrates my understanding of the assigned topic and my ability to research, analyze, and document relevant information.
This is an educational exercise and does not represent actual patient-care activities or professional employment. Any case examples are for learning purposes only.
