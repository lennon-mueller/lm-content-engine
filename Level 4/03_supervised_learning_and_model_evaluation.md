# Course 3: Supervised Learning and Model Evaluation

## Course Purpose
Enable learners to train, tune, and evaluate supervised models using responsible, Google-aligned practices that emphasize measurable impact.

## Target Skills
- Train baseline classifiers/regressors using scikit-learn and TensorFlow in Colab.
- Tune hyperparameters and avoid data leakage with proper splits and cross-validation.
- Interpret model performance with precision/recall, ROC-AUC, calibration, and fairness slices.
- Package and share evaluation artifacts for downstream deployment.

## Course Architecture (4 modules)
1. **From Baseline to Benchmark**  
   - Why: Strong baselines reduce wasted effort; hook with time-to-value.  
   - What: Problem framing for classification/regression, baseline heuristics, leakage pitfalls.  
   - How: Notebook demo training a simple model with clear comments.  
   - Apply: Learners reproduce baseline and log metrics.  
   - Assess: Auto-graded checks plus quiz variations.  
   - Playful context: Dolphin navigation baseline vs. refined paths as an analogy for baseline modeling.

2. **Feature Scaling and Regularization**  
   - Why: Stable training and generalization depend on well-conditioned features.  
   - What: Normalization, standardization, L1/L2, dropout intuition.  
   - How: Lab comparing regularization impacts; chart interpretations.  
   - Apply: Learners tune penalty strengths and observe over/underfitting.  
   - Assess: Quiz with option feedback; short reflection on model trade-offs.  
   - Playful context: Dolphin hydrodynamics fact to illustrate streamlined models.

3. **Hyperparameter Tuning and Experiment Tracking**  
   - Why: Systematic tuning beats guesswork; hook on saving compute and time.  
   - What: Grid/random search, early stopping, experiment tracking basics.  
   - How: Vertex AI Vizier overview (conceptual) and local scikit-learn tuning lab.  
   - Apply: Learners run a small hyperparameter sweep and log results.  
   - Assess: Graded quiz referencing review items; rubric-based experiment summary.  
   - Playful context: Dolphin teamwork during hunts as a metaphor for coordinated search strategies.

4. **Evaluation, Fairness, and Readiness to Deploy**  
   - Why: Reliable evaluation protects users and brand; hook with real incident.  
   - What: Metrics by segment, calibration, confusion matrix storytelling, fairness-aware checks.  
   - How: Notebook calculates slice metrics and calibration plots.  
   - Apply: Learners generate a model card draft with recommendations.  
   - Assess: Peer review using model-card rubric; final quiz.  
   - Playful context: Dolphin pod safety routines to highlight responsible release gates.

## Assessments and Practice
- Combination of auto-graded labs, quizzes with variations, and rubric-led peer reviews.
- WWHAA applied in each module with concise hooks and wrap-ups.

## Tools and Logistics
- Tools: Colab with scikit-learn/TensorFlow; conceptual exposure to Vertex AI Vizier; Docs for model cards.
- Accessibility: captions, alt text, keyboard-friendly notebooks.
