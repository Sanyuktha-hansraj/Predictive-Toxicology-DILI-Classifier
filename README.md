# Drug-Induced Liver Toxicity (DILI) Prediction

A machine learning system designed to screen pharmaceutical compounds and predict drug-induced liver injury (DILI) risk from molecular structures to support early-stage drug development safety workflows.

## Key Accomplishments
* Built a multi-class toxicity classifier using a Random Forest model and RDKit to extract 8 molecular descriptors (including lipophilicity and TPSA) for drug-induced liver toxicity screening.
* Developed an end-to-end pipeline integrating CirPy for compound name-to-SMILES resolution and Scikit-learn to scale features and handle data imbalance across 4 risk categories.

## Tech Stack
* Data & Machine Learning: Scikit-learn, Imbalanced-learn (SMOTE), Pandas, NumPy
* Cheminformatics Tools: RDKit, CIRpy (Chemical Identifier Resolver)
