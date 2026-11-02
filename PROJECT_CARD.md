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
| PAD800 | Duration of moderate-intensity leisure-time physical activities per session | PAQ_L | Physical Activity | Questionnaire 
| PAD810Q | How often does the participant engage in vigorous-intensity leisure-time physical activities? | PAQ_L | Physical Activity | Questionnaire | |
| PAD810U | Unit of frequency for vigorous-intensity leisure-time physical activities | PAQ_L | Physical Activity | Questionnaire |
| PAD820 | Duration of vigorous-intensity leisure-time physical activities per session | PAQ_L | Physical Activity | Questionnaire |
| SMD650 | Number of cigarettes smoked per day on smoking days during the past 30 days | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| SMQ020 | Whether the participant has smoked at least 100 cigarettes in their lifetime | SMQ_L | Smoking - Cigarette Use | Questionnaire |
| SMQ040 | {Do you/Does SP} now smoke cigarettes? | SMQ_L | Smoking - Cigarette Use | Questionnaire |
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

One individual NHANES participant.Each row in the final analytical dataset represents one participant.

**Target Population:**

Adults aged 18 years, noninstitutionalized and older living in the United States during the NHANES 2021–2023 survey period.

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

Smoking Cigarette

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
WTPH2YR | Phlebotomy 2 Year Weight | Continuous quantitative
WTSAF2YR | Fasting Subsample 2 Year MEC Weight | Continuous quantitative


## 6. Roles of Variables in the Research Question

This statistical project will investigate the associations between physical activity level and cigarette smoking status and several indicators of general health. The health outcomes to be examined will include body mass index (BMI), blood pressure, glycohemoglobin, fasting glucose, direct HDL-cholesterol, total cholesterol, and triglycerides. Each health outcome will be analyzed independently as a response variable.

Two primary explanatory variables will be considered:

1. **Physical Activity Level:** Participants will be classified into four categories: Inactive, Low, Active, and Highly Active.
2. **Cigarette Smoking Status:** Participants will be classified into four categories: Never Smoker, Former Smoker, Current Light Smoker, and Current Heavy Smoker.

The associations between these explanatory variables and each health outcome will be examined separately. Age, gender, and the family income-to-poverty ratio will be considered as covariates to account for potential demographic and socioeconomic differences among participants.

Pregnant participants will be excluded from the analyses to minimize potential pregnancy-related influences on the selected health outcomes.

Furthermore, additional exclusion variables will be considered to assess the potential influence of other relevant factors on the analytical results. Appropriate exclusion criteria will be applied where necessary.

## 7. Type of Statistical Question

**Primary Question Type: Associational**

The project primarily investigates associations between physical activity, smoking behavior, and general health indicators.

Descriptive and comparative analyses will also be performed.

## 8. Initial Hypothesis

Based on previous research and preliminary expectations, physical activity is hypothesized to be positively associated with overall health, whereas cigarette smoking is expected to be negatively associated with overall health.

More specifically, higher levels of physical activity are expected to be associated with more favorable health outcomes, including lower BMI, lower blood pressure, lower glycohemoglobin, lower fasting glucose, higher HDL-cholesterol, and generally more favorable lipid profiles.

Conversely, cigarette smoking is hypothesized to be associated with less favorable health outcomes, including higher blood pressure, higher glycohemoglobin, higher fasting glucose, lower HDL-cholesterol, and generally less favorable lipid profiles.

These hypotheses will be examined independently for each health outcome, while accounting for potential differences in age, gender, and family income-to-poverty ratio.

## 9. Initial Limitations

Several limitations and methodological challenges are anticipated in this project.

First, potential biological and physiological differences between male and female participants may influence the relationships between physical activity, cigarette smoking, and health outcomes. Although gender-specific analyses may provide additional insights, conducting separate analyses for each gender would substantially increase the complexity and computational workload of the study.

Second, physical activity and cigarette smoking data are primarily based on self-reported questionnaires. Consequently, these variables may be subject to recall bias, reporting inaccuracies, and potential misclassification, which could affect the reliability of the observed associations.

Third, NHANES employs a complex sampling design involving sample weights, strata, and primary sampling units. Proper incorporation of these design features into statistical analyses is essential for obtaining population-representative estimates and valid statistical inferences. However, implementing survey-weighted analyses may introduce additional methodological and computational complexity.

Finally, since NHANES is an observational, cross-sectional study, establishing causal relationships between physical activity, cigarette smoking, and health outcomes will be challenging. Potential confounding factors, reverse causation, and the absence of clear temporal ordering may limit causal interpretation of the observed associations.
