#  Women Health Care 

A professional grade, end-to-end Machine Learning web application designed to assist clinical workflows by monitoring maternal and fetal health parameters. The platform integrates two distinct predictive pipelines to ensure comprehensive prenatal risk evaluation.

##  Key Features
- **Maternal Health Risk Predictor:** Analyzes maternal biometric markers (Age, Diastolic BP, Blood Sugar, Body Temperature, Heart Rate) to classify cases into *Low Risk*, *Mid Risk*, or *High Risk*.
- **Fetal Health CTG Classifier:** Processes 21 distinct Cardiotocography (CTG) physical variables—such as fetal heart rate baseline, accelerations, movements, and uterine contractions—categorizing statuses into *Normal*, *Suspect*, or *Pathological*.
- **Modern Clinical Dashboard:** Developed using dynamic Bootstrap templates and jQuery to render color-coded severity alerts (Green/Yellow/Red) based on real-time diagnostic outputs.

##  Tech Stack
- **Backend:** Flask (Python)
- **Machine Learning & Data Engine:** Scikit-Learn, Pandas, NumPy, Joblib
- **Core Algorithms:** Gradient Boosting Classifier, Random Forest, K-Nearest Neighbors (Hyperparameter tuned via GridSearchCV)
- **Frontend UI:** HTML5, Bootstrap 5, FontAwesome, JavaScript (AJAX/jQuery)

## Model Architecture & Data Engineering
- Extensively cleaned dataset structures by mitigating multi-collinearity issues (VIF analysis) and eliminating significant outlier anomalies.
- Handled feature space alignment via custom robust matrix transformations through `StandardScaler` checkpoints to bypass asynchronous user structural inputs.
- Automated precise structural alignment for high-fidelity internal 21-feature array vectors within production routes.

##  Getting Started

1. Clone the repository:
   ```bash
   git clone (https://github.com/abhisheknishad23/Maternal-Health-Risk-levels.git)
   
   cd Women-Health-Care-AI