Problem Definition ---> Data Collection ---> Data Preprocessing ---> Feature Engineering
        |                     |                      |                      |
        v                     v                      v                      v
 Stakeholder Analysis   EHR / Demographics      Cleaning & Impute       Derived Features
        |
        v
Model Development ---> Model Evaluation ---> Deployment ---> Monitoring & Maintenance
   (baseline, GBTs)        (confusion matrix,        (EHR integration,        (data drift, perf
                           calibration)             APIs, UI)                monitoring)
        ^
        |
   Validation & Tuning
        |
        v
 Governance & Ethics <--- Privacy & Security <--- Compliance (e.g., HIPAA)
 (bias audits, explainability)  (encryption, RBAC)      (BAAs, consent)
