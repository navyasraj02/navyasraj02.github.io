---
layout: page
title: Traffic Crash Cause Identification
description: Multi-class ML pipeline analyzing Chicago crash records.
importance: 2
category: Data Science
---

A large-scale machine learning project focused on identifying contributory causes of traffic accidents. The pipeline involved massive data consolidation, feature engineering, and high-performance classification.

### Technical Stack
* **Languages & Libraries:** Python, [Scikit-learn](https://scikit-learn.org/), Pandas, NumPy.
* **Models Tested:** Decision Tree, Logistic Regression, Gaussian Naïve Bayes, Multinomial Naïve Bayes, kNN, Random Forest, SVM.
* **Evaluation:** Custom multi-label framework (Precision, Recall, F1-score).

### Core Features
* Data Engineering: Consolidated 794k+ Chicago crash records, mapping 40 contributory causes into 5 actionable classes for simplified classification.

* Feature Optimization: Streamlined the feature space from 48 to 18 key predictors, reducing noise and improving model computational efficiency.

* Model Performance: Optimized a k-Nearest Neighbors (kNN) model to achieve 54.19% accuracy, a 15% improvement over the baseline and the highest among all tested classifiers.

---

### Project Workflow
Below is the architectural flow of the ML pipeline: flowchart.png
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/flowchart.png" title="Project Flowchart" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture of the data preprocessing and model selection pipeline.
</div>
