## 1. Dataset and Subdatasets

**Dataset:** NHANES 2021–2023 (National Health and Nutrition Examination Survey)

**Source:** CDC – National Center for Health Statistics (NCHS)

**Subdatasets:**

| Variable Name | Variable Description | Data File Name | Data File Description | Component |
|---|---|---|---|---|
| SEQN | Respondent sequence number (unique participant identifier) | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| BMXBMI | Body Mass Index (kg/m²) | BMX_L | Body Measures | Examination |
| BPXODI1 | Diastolic - 1st oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| BPXODI2 | Diastolic - 2nd oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| BPXODI3 | Diastolic - 3rd oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| BPXOSY1 | Systolic - 1st oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| BPXOSY2 | Systolic - 2nd oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| BPXOSY3 | Systolic - 3rd oscillometric reading | BPXO_L | Blood Pressure - Oscillometric Measurements | Examination |
| LBXGH | Glycohemoglobin (%) | GHB_L | Glycohemoglobin | Laboratory |
| LBXGLU | Fasting Glucose (mg/dL) | GLU_L | Plasma Fasting Glucose | Laboratory |
| LBDHDD | Direct HDL-Cholesterol (mg/dL) | HDL_L | Cholesterol – High-Density Lipoprotein | Laboratory |
| LBXTC | Total Cholesterol (mg/dL) | TCHOL_L | Cholesterol - Total | Laboratory |
| LBXTLG | Triglyceride (mg/dL) | TRIGLY_L | Cholesterol - Low-Density Lipoproteins (LDL) & Triglycerides | Laboratory |
| PAD790Q | How often does the participant engage in moderate-intensity leisure-time physical activities? | PAQ_L | Physical Activity | Questionnaire |
| PAD790U | Unit of frequency for moderate-intensity leisure-time physical activities | PAQ_L | Physical Activity | Questionnaire |
| PAD800 | Duration of moderate-intensity leisure-time physical activities per session | PAQ_L | Physical Activity | Questionnaire |
| PAD810Q | How often does the participant engage in vigorous-intensity leisure-time physical activities? | PAQ_L | Physical Activity | Questionnaire |
| PAD810U | Unit of frequency for vigorous-intensity leisure-time physical activities | PAQ_L | Physical Activity | Questionnaire |
| PAD820 | Duration of vigorous-intensity leisure-time physical activities per session | PAQ_L | Physical Activity | Questionnaire |
| SMD630 | Age at which the participant first smoked a whole cigarette | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| SMD650 | Number of cigarettes smoked per day on smoking days during the past 30 days | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| SMQ020 | Whether the participant has smoked at least 100 cigarettes in their lifetime | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| SMD641 | Number of days the participant smoked a cigarette during the past 30 days | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| RIDAGEYR | Age in years at screening; participants aged 80 years and older are top-coded at 80 | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| INDFMPIR | Ratio of family income to poverty | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| RIAGENDR | Gender of the participant | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| RIDEXPRG | Pregnancy status for females aged 20–44 years at the time of the MEC examination | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| WTINT2YR | Full sample 2-year interview weight | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| WTMEC2YR | Full sample 2-year MEC examination weight | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| SDMVPSU | Masked variance unit pseudo-PSU variable for variance estimation | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| SDMVSTRA | Masked variance unit pseudo-stratum variable for variance estimation | DEMO_L | Demographic Variables and Sample Weights | Demographics |
| WTSAF2YR | Fasting Subsample 2 Year MEC Weight | GLU_L, TRIGLY_L | Plasma Fasting Glucose; Cholesterol - Low-Density Lipoproteins (LDL) & Triglycerides | Laboratory |
| WTPH2YR | Phlebotomy 2 Year Weight | GHB_L, HDL_L, TCHOL_L | Glycohemoglobin; Cholesterol – High-Density Lipoprotein; Cholesterol - Total | Laboratory |
The final selection of variables will depend on data availability, missing values, and their suitability for statistical analysis.

## 2.Project Title

"Evaluating the Association of Cigarette Smoking and Physical Activity with Multiple Metabolic(BMI and Blood pressure) and Lipid Biomarkers (Glycohemoglobin, Fasting Glucose, HDL-Cholesterol, Total Cholesterol, and Triglycerides) Among Adults(Males and Females, Aged 18 and Older) in NHANES"

## 3. Main Statistical Question

"How do cigarette smoking status and physical activity levels jointly associate with key metabolic(BMI and Blood pressure) and lipid biomarkers (Glycohemoglobin, Fasting Glucose, Direct HDL-Cholesterol, Total Cholesterol, and Triglycerides) in adults aged 18 and older?"

## 4. Unit of Observation and Interpretable Population

**Unit of Observation:**

One individual NHANES participant.

Each row in the final analytical dataset represents one participant.

**Target Population:**

Adults aged 20 years and older living in the United States during the NHANES 2021–2023 survey period.

**Sampling Method:**

NHANES uses a multistage, stratified, clustered probability sampling design to obtain a representative sample of the noninstitutionalized U.S. population.

Data are collected through household interviews, physical examinations at Mobile Examination Centers (MEC), and laboratory measurements.

The complex sampling design and appropriate survey weights will be considered during the analysis.

## 5. Main Variables and Measurement Scales

The variables are initially divided into four groups.

1. Response Variables (Quantitative)

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| BMXBMI | Body Mass Index (kg/m²) | Continuous quantitative |
| BPXODI1 | Diastolic - 1st oscillometric reading | Continuous quantitative |
| BPXODI2 | Diastolic - 2nd oscillometric reading | Continuous quantitative |
| BPXODI3 | Diastolic - 3rd oscillometric reading | Continuous quantitative |
| BPXOSY1 | Systolic - 1st oscillometric reading | Continuous quantitative |
| BPXOSY2 | Systolic - 2nd oscillometric reading | Continuous quantitative |
| BPXOSY3 | Systolic - 3rd oscillometric reading | Continuous quantitative |
| LBXGH | Glycohemoglobin (%) | Continuous quantitative |
| LBXGLU | Fasting Glucose (mg/dL) | Continuous quantitative |
| LBDHDD | Direct HDL-Cholesterol (mg/dL) | Continuous quantitative |
| LBXTC | Total Cholesterol (mg/dL) | Continuous quantitative |
| LBXTLG | Triglyceride (mg/dL) | Continuous quantitative |

2. Primary Explanatory Variables

Physical Activity

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| PAD790Q | How often does the participant engage in moderate-intensity leisure-time physical activities? | Discrete quantitative |
| PAD790U | Unit of frequency for moderate-intensity leisure-time physical activities | Nominal categorical |
| PAD800 | Duration of moderate-intensity leisure-time physical activities per session | Discrete quantitative |
| PAD810Q | How often does the participant engage in vigorous-intensity leisure-time physical activities? | Discrete quantitative |
| PAD810U | Unit of frequency for vigorous-intensity leisure-time physical activities | Nominal categorical |
| PAD820 | Duration of vigorous-intensity leisure-time physical activities per session | Discrete quantitative |

Smoking

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| SMD630 | Age at which the participant first smoked a whole cigarette | Discrete quantitative |
| SMD650 | Number of cigarettes smoked per day on smoking days during the past 30 days | Discrete quantitative |
| SMQ020 | Whether the participant has smoked at least 100 cigarettes in their lifetime | Binary categorical |
| SMD641 | Number of days the participant smoked a cigarette during the past 30 days | Discrete quantitative |

3. Control Variables

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| RIDAGEYR | Age in years at screening; participants aged 80 years and older are top-coded at 80 | Discrete quantitative |
| INDFMPIR | Ratio of family income to poverty | Continuous quantitative |
| RIAGENDR | Gender of the participant | Nominal categorical |
| RIDEXPRG | Pregnancy status for females aged 20–44 years at the time of the MEC examination | Nominal categorical |

4. Exclusion Variables

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| BAXMSTAT | MRT exam status | Nominal categorical |
| MCQ160A | Has a doctor or other health professional ever told the participant that they had arthritis? | Binary categorical |
| MCQ160C | Has a doctor or other health professional ever told the participant that they had coronary heart disease? | Binary categorical |
| MCQ160E | Has a doctor or other health professional ever told the participant that they had a heart attack (myocardial infarction)? | Binary categorical |
| MCQ160F | Has a doctor or other health professional ever told the participant that they had a stroke? | Binary categorical |
| MCQ160M | Has a doctor or other health professional ever told the participant that they had another thyroid problem? | Binary categorical |
| DR1TKCAL | Energy (kcal) | Continuous quantitative |
| DR1TSUGR | Total sugars (gm) | Continuous quantitative |
| DR1TTFAT | Total fat (gm) | Continuous quantitative |
| DR1TSODI | Sodium (mg) | Continuous quantitative |
| DR1TFIBE | Dietary fiber (gm) | Continuous quantitative |

5. Participant Identification and Survey Design Variables

| Variable Name | Variable Description | Measurement Scale |
|---|---|---|
| SEQN | Respondent sequence number (unique participant identifier) | Identifier |
| WTINT2YR | Full sample 2-year interview weight | Continuous quantitative |
| WTMEC2YR | Full sample 2-year MEC examination weight | Continuous quantitative |
| SDMVPSU | Masked variance unit pseudo-PSU variable for variance estimation | Nominal categorical |
| SDMVSTRA | Masked variance unit pseudo-stratum variable for variance estimation | Nominal categorical |


The final variable list will be refined after examining the NHANES documentation and the actual data files.

## 6. Roles of Variables in the Research Question

| Role | Variables |
|---|---|
| Main explanatory variables | Physical activity and smoking status |
| Primary response variable | BMI |
| Additional response variables | Systolic blood pressure, diastolic blood pressure, and HDL cholesterol |
| Control variables | Age and gender |

The roles of variables may change depending on the specific statistical question.

For example, BMI can be the response variable when examining its association with physical activity and smoking. Other health indicators can also be investigated separately.

## 7. Type of Statistical Question

**Primary Question Type: Associational**

The project primarily investigates associations between physical activity, smoking behavior, and general health indicators.

Descriptive and comparative analyses will also be performed.

The project does not aim to establish causal relationships.

## 8. Initial Hypothesis

**Initial Scientific Hypothesis:**

Physical activity and smoking behavior may be associated with general health indicators.

Higher levels of physical activity may be associated with more favorable health indicators, while smoking may be associated with less favorable health indicators.

Furthermore, the combination of physical activity and smoking behavior may reveal different patterns of association with general health.

**Example Statistical Hypotheses:**

For the association between physical activity and BMI:

- H₀: There is no statistical association between physical activity and BMI.
- H₁: There is a statistical association between physical activity and BMI.

For the association between smoking status and HDL cholesterol:

- H₀: There is no statistical difference in HDL cholesterol levels across smoking-status groups.
- H₁: There is a statistical difference in HDL cholesterol levels across smoking-status groups.

The exact hypotheses and statistical tests will be determined after finalizing the variables and their measurement scales.

## 9. Initial Limitations

The following limitations are anticipated:

1. **Cross-sectional data:** NHANES 2021–2023 does not establish temporal or causal relationships between physical activity, smoking, and health indicators.

2. **Self-reported measurements:** Physical activity and smoking information are primarily collected through questionnaires and may be affected by reporting errors.

3. **Missing data:** Some participants may have incomplete questionnaire responses or missing examination and laboratory measurements.

4. **Complex sampling design:** NHANES uses a complex sampling design, requiring appropriate consideration of survey weights, strata, and clusters.

5. **Subgroup sample size:** Dividing participants into multiple physical activity and smoking categories may reduce the sample size in some groups.

6. **Limited health indicators:** BMI, blood pressure, and HDL cholesterol represent only selected aspects of general health and cannot provide a complete assessment of an individual's health.

7. **Potential confounding variables:** Other factors, such as age, gender, diet, and socioeconomic conditions, may influence the observed associations.
