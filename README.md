# Obesity Definition in Kidney Transplant Transition Clinic

## Project Overview
This project compares obesity definitions using Body Mass Index (BMI) versus Percentage of Body Fat (% BF) in adolescent and young adult (AYA) kidney transplant (KT) recipients. The study evaluates whether % BF, measured via bioelectrical impedance analysis, identifies fewer patients as overweight or obese compared to BMI, potentially impacting transplant eligibility decisions.

## Dataset
- **Sample Size**: 21 patients (10 females, 10 males, 1 male/female at birth)
- **Age Range**: 15–25 years (mean: 19.95 ± 2.44 years)
- **Time from Transplant**: 1–16 years (mean: 7.71 ± 4.61 years)
- **Measurements**:
  - % BF via bioelectrical impedance analysis (scale details not specified)
  - BMI, Hemoglobin A1c, LDL, HDL, Triglycerides, QOL, PHQ-9 (depression), GAD-7 (anxiety)
  - Hypertension: 52.4% on BP medications
- **Data Completeness**:
  - BMI and % BF: 100% (n=21)
  - Other metrics: Partial (e.g., HgbA1c n=19, QOL n=9, PHQ-9/GAD-7 n=13)

## Key Findings
### Obesity Classifications
- **BMI Method**:
  - 38.1% abnormal weight (23.8% overweight, 14.3% obese)
  - Males: 45.5% (40.0% in analysis); Females: 30.0%
- **% BF Method**:
  - 28.6% abnormal weight (23.8% overweight, 4.8% obese)
  - Males: 36.4% (30.0% in analysis); Females: 20.0%
- **Observation**: BMI overestimates obesity compared to % BF, particularly in males (14.3% vs. 4.8% obese).

### Clinical Metrics
- **Abnormal Results**:
  - HgbA1c: 15.8%
  - LDL: 35.3%
  - HDL: 41.2%
  - Triglycerides: 41.2%
- **Mental Health**:
  - Females: Higher PHQ-9 (8.00 ± 4.69 vs. 3.67 ± 2.42) and GAD-7 (9.00 ± 4.74 vs. 7.43 ± 6.60) scores
  - QOL: 73.69 ± 14.81
- **Hypertension**: 52.4% on BP medications

### Statistical Insights
- **Correlations**:
  - Strong positive correlation (0.73) between BMI and % BF
  - Negative correlation (-0.55) between % BF and QOL
  - Strong positive correlation (0.84) between HDL and QOL
  - Moderate positive correlation (0.61) between HgbA1c and age
  - Weak positive correlation (0.2) between PHQ-9 and GAD-7
- **Distributions**:
  - Age: Bell-shaped, centered around 20 years
  - BMI: Right-skewed, most values 22.5–27.5
  - % BF: Bimodal, peaks at 20–25% and 30–35%
- **BP Medication Analysis**:
  - BP med users: Higher mean % BF (28.43% ± 5.69 vs. 25.10% ± 8.76, p=0.3102)
  - Males on BP meds: Significantly higher % BF (25.22% ± 3.41 vs. 17.25% ± 3.89, p=0.0089)
  - Females: No significant difference (30.32% ± 4.21 vs. 30.33% ± 6.84, p=0.9983)

### Gender-Specific Patterns
- Males: Higher overweight/obesity rates; larger discrepancy between BMI and % BF methods
- Females: Higher depression/anxiety scores; consistent % BF regardless of BP medication status
- Male (female at birth): Highest % BF (40.10%), on BP meds

## Repository Structure
```
├── data/                            # Raw and processed datasets 
├── analysis/                        # Scripts or notebooks for statistical analysis
├── docs/                            # Project documentation
│   ├── Obesity_study.pdf            # Analysis slides
│   ├── Obesity_study_analysis.pdf   # Detailed analysis
├── Kidney_Transplant_Patient_Transition_Analysis.pptx  # Related transition analysis
└── README.md                        # This file
```

## Usage
1. **Access Documents**: Review  `Obesity_study.pdf` for study details.
2. **Run Analysis**: Use scripts in `analysis/` (if provided) to replicate or extend statistical findings.
3. **Visualizations**: Explore distribution plots and correlation heatmaps in `Obesity_study_analysis.pdf`.

## Requirements
- Software: [e.g., Python, R, or MS Office for viewing documents]
- Dependencies: [e.g., pandas, scipy, matplotlib for analysis, if applicable]

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

## Future Improvements
- Expand sample size to validate % BF as a more accurate obesity metric
- Include additional clinical metrics (e.g., bone mass) to explain BMI overestimation
- Investigate gender-specific BP medication effects further
- Develop interactive visualizations for BMI vs. % BF classifications



Let me know if you need refinements, additional sections, or a specific chart for the README!
