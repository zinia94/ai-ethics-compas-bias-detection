# ai-ethics-compas-bias-detection

A Jupyter notebook project analyzing the **COMPAS dataset** to detect and mitigate algorithmic bias in criminal justice risk assessments. The focus is on three key fairness issues: **disparate treatment, disparate impact, and disparate mistreatment**.

---

## Contents

* **Data Preprocessing**: Cleaned COMPAS dataset, defined sensitive attributes.
* **Models**: Decision Tree, Logistic Regression, Support Vector Classifier.
* **Fairness Evaluation**:

  * Disparate Treatment → flip sensitive attributes.
  * Disparate Impact → measure outcome disparities.
  * Disparate Mistreatment → analyze error rates.
* **Mitigation**:

  * Feature exclusion
  * Reweighing
  * Threshold optimization

---

## Findings

* Bias was detected across all three dimensions.
* Mitigation improved fairness but introduced **accuracy trade-offs**.
* Limitations: binary sensitive attributes only, no cross-validation, fairness handled separately.

---

## Future Work

* Unified fairness modeling.
* Intersectional bias detection (e.g., race × gender).
* Hyperparameter tuning and k-fold validation.
* Systematic fairness vs. accuracy trade-off analysis.

---

## Conclusion

Fairness-aware techniques can **reduce bias** in predictive models with minimal impact on accuracy. This project demonstrates the need for **responsible AI** in high-stakes domains like criminal justice.

Full notebook: [ai_ethics_compas_bias_detection](https://github.com/zinia94/ai-ethics-compas-bias-detection/blob/main/ai_ethics_compas_bias_detection.ipynb)
