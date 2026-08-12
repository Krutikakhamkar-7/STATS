<img width="1599" height="810" alt="image" src="https://github.com/user-attachments/assets/c6387c6d-5004-4951-8dd0-ca6189d8bf9e" /><img width="1599" height="810" alt="image" src="https://github.com/user-attachments/assets/357eca8a-c92c-406c-8d23-5cf7a493e161" /># Statistical Estimation and Hypothesis Testing – Pima Indians Diabetes Dataset

## Aim
To apply statistical estimation and hypothesis testing techniques to the Pima Indians Diabetes Dataset and draw conclusions about population characteristics using sample data.

## Objectives
1. Apply estimation and hypothesis testing techniques to analyze population characteristics using sample data.
2. Interpret statistical test results and make data-driven conclusions based on the obtained evidence.

## Tools and Technologies
- Python 3.x
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

## Dataset
**Pima Indians Diabetes Dataset**

The dataset contains diagnostic information for **768 female patients**.

The dataset includes the following variables:

| Variable | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the patient |
| Outcome | 0 = No Diabetes, 1 = Diabetes |

## Statistical Methods Used

### 1. Point Estimation
The sample mean was calculated to estimate the population mean glucose level.

The sample proportion of patients with diabetes was also calculated.

### 2. Confidence Interval
A **95% confidence interval** was constructed for the population mean glucose level.

### 3. Hypothesis Testing
A **one-sample t-test** was performed to determine whether the average glucose level differs significantly from 120 mg/dL.

### Hypotheses

**Null Hypothesis (H₀):**

H₀: μ = 120

**Alternative Hypothesis (H₁):**

H₁: μ ≠ 120

The significance level used was:

**α = 0.05**

## Results

The main results obtained from the analysis are approximately:

| Parameter | Result |
|---|---:|
| Total Patients | 768 |
| Diabetic Patients | 268 |
| Sample Mean Glucose | 120.89 mg/dL |
| Diabetes Proportion | 34.90% |
| 95% Confidence Interval | 118.40 – 123.39 mg/dL |
| Reference Mean | 120 mg/dL |
| Statistical Test | One-Sample t-Test |
| Significance Level | 0.05 |
| p-value | Approximately 0.60 |
| Decision | Fail to Reject H₀ |

## Screenshots
<img width="1599" height="810" alt="image" src="https://github.com/user-attachments/assets/f4e9bc8e-6ae4-430d-87d7-c088d9b53d41" />
<img width="1599" height="805" alt="image" src="https://github.com/user-attachments/assets/385b9c23-f5be-485e-8ce7-c9f88fed6778" />
<img width="1599" height="838" alt="image" src="https://github.com/user-attachments/assets/d4ecf11d-672e-4250-ad91-d88ce48ec5ac" />
<img width="1599" height="812" alt="image" src="https://github.com/user-attachments/assets/2601c14a-a281-4b0a-bfd6-7fd8145cfeb6" />
<img width="1599" height="806" alt="image" src="https://github.com/user-attachments/assets/ffa4d4ce-f5d0-4608-bafb-08553ab64a69" />
<img width="1599" height="810" alt="image" src="https://github.com/user-attachments/assets/fa1d760d-603d-4ee1-8bb6-42e7a50e8237" />
<img width="1592" height="788" alt="image" src="https://github.com/user-attachments/assets/26a598c5-25ed-4d91-a8e7-21765e0df9b7" />
<img width="1599" height="801" alt="image" src="https://github.com/user-attachments/assets/32b11524-65fb-4674-bd02-2bc938f1e436" />
<img width="1599" height="806" alt="image" src="https://github.com/user-attachments/assets/b1cdf808-5ab0-4a2f-94a5-7d5b6ec7424a" />










## Conclusion

Statistical estimation and hypothesis testing techniques were successfully applied to the Pima Indians Diabetes Dataset.

The sample mean glucose level was approximately **120.89 mg/dL**. A 95% confidence interval for the population mean glucose level was obtained as approximately **118.40 to 123.39 mg/dL**.

The one-sample t-test resulted in a p-value greater than 0.05. Therefore, the null hypothesis was not rejected. There is insufficient statistical evidence to conclude that the population mean glucose level is significantly different from 120 mg/dL.

## Files

- `Pima_Diabetes_Statistical_Analysis.ipynb` – Google Colab/Jupyter Notebook containing the complete Python implementation, statistical calculations, and visualizations.

## Author

**Krutika Khamkar**
