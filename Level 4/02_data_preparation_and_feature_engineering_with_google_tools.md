# Course 2: Data Preparation and Feature Engineering with Google Tools

## Course Purpose
Help learners source, clean, and engineer reliable features using Google-centric workflows while reinforcing responsible data handling and repeatable processes.

## Target Skills
- Profile and clean structured/unstructured datasets using Colab and BigQuery.
- Create and evaluate feature sets, including embeddings and feature crosses, with Vertex AI Feature Store.
- Apply data privacy, security, and fairness checks prior to modeling.
- Document data lineage and validation using versioned artifacts.

## Course Architecture (4 modules)
1. **Data Sourcing and Access Patterns**  
   - Why: The right data unlocks model quality; hook with efficiency gains.  
   - What: Data types, collection patterns, storage options (BigQuery, Cloud Storage).  
   - How: Guided lab to pull a sample dataset into Colab via BigQuery Python client.  
   - Apply: Learners configure access and run a profiling query.  
   - Assess: Quiz with scenario variations; option feedback.  
   - Playful context: Dolphin communication datasets as a safe example for practicing access and permissions.

2. **Cleaning and Validation Workflows**  
   - Why: Small data issues compound quickly; hook on preventing downstream rework.  
   - What: Missing data strategies, outlier handling, schema drift.  
   - How: Demonstration notebook using pandas and TensorFlow Data Validation.  
   - Apply: Learners clean a noisy dataset and generate validation reports.  
   - Assess: Auto-graded notebook checks plus quiz pointing to review items.  
   - Playful context: Dolphin echolocation noise filtering to explain anomaly handling.

3. **Feature Engineering and Embeddings**  
   - Why: Well-designed features boost model performance without extra data.  
   - What: Feature types, normalization, feature crosses, text/image embeddings.  
   - How: Vertex AI Feature Store walkthrough; optional open-access article on embeddings.  
   - Apply: Build and register a small feature set; compute a text embedding for intent detection.  
   - Assess: Graded quiz with varied scenarios; rubric-based review of feature documentation.  
   - Playful context: Dolphin signature whistles as an embedding analogy.

4. **Data Readiness Review and Hand-off**  
   - Why: Clear hand-offs reduce iteration loops with modeling teams.  
   - What: Data cards, validation signoffs, privacy/fairness checkpoints.  
   - How: Template-driven creation of a data readiness packet in Docs/Sheets.  
   - Apply: Learners assemble packet including metrics, risks, and mitigation plans.  
   - Assess: Peer review with transparent rubric; short quiz.  
   - Playful context: Dolphin pod coordination story for structured hand-offs.

## Assessments and Practice
- Mix of quizzes, auto-graded labs (within Colab), and peer reviews tied to clear rubrics.
- WWHAA aligned per module with concise hooks and wrap-ups.

## Tools and Logistics
- Tools: Colab, BigQuery, Vertex AI Feature Store, TensorFlow Data Validation.
- Accessibility: captions, alt text, high-contrast visuals, downloadable artifacts.
