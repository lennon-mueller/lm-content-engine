# Course 5: MLOps and Deployment on Google Cloud

## Course Purpose
Teach learners how to operationalize models with reliable pipelines, monitoring, and responsible release practices using Google Cloud services.

## Target Skills
- Package and version models using Vertex AI and Cloud Storage.
- Build training/serving pipelines with Vertex AI Pipelines and CI/CD best practices.
- Implement monitoring for drift, performance, and fairness slices.
- Apply governance: approvals, rollback strategies, and model documentation.

## Course Architecture (4 modules)
1. **Production Mindset and Architecture Patterns**  
   - Why: Production readiness protects users and uptime; hook on incident avoidance.  
   - What: Online vs. batch inference, latency/throughput trade-offs, reference architectures.  
   - How: Diagram-driven walkthroughs; short demo of Vertex AI endpoints.  
   - Apply: Learners map requirements to a recommended architecture.  
   - Assess: Quiz with scenario variations and feedback.  
   - Playful context: Dolphin pod coordination during migrations as an analogy for resilient systems.

2. **Pipelines and Automation**  
   - Why: Automation reduces toil and errors; hook on developer velocity.  
   - What: Pipeline components, triggers, artifact tracking, CI/CD basics.  
   - How: Guided lab building a minimal Vertex AI Pipeline with reproducible steps.  
   - Apply: Learners customize a component and rerun pipeline; log artifacts.  
   - Assess: Auto-graded checks plus quiz referencing review items.  
   - Playful context: Dolphin feeding routines to illustrate repeatable cycles.

3. **Serving, Monitoring, and Alerting**  
   - Why: Monitoring prevents silent failures; hook on user trust.  
   - What: Logging, drift detection, canary/blue-green releases, fairness monitoring.  
   - How: Demo setting up monitoring metrics and alerts with Vertex AI and Cloud Monitoring.  
   - Apply: Learners configure drift thresholds and create an alert policy.  
   - Assess: Quiz with variations; short reflection on mitigation plans.  
   - Playful context: Dolphin sonar checks before travel as a metaphor for monitoring.

4. **Governance, Security, and Documentation**  
   - Why: Compliance and security accelerate approvals; hook on avoiding rework.  
   - What: IAM principles, data privacy checks, rollout gates, rollback playbooks.  
   - How: Template-based change request and model card updates.  
   - Apply: Learners complete a mock approval packet including risks and mitigations.  
   - Assess: Peer review using rubric; final quiz referencing review resources.  
   - Playful context: Dolphin pod signals for safe passage as governance metaphor.

## Assessments and Practice
- Combination of auto-graded labs, scenario-based quizzes with variations, and rubric-driven peer artifacts.
- Each module follows WWHAA with concise hooks and wrap-ups.

## Tools and Logistics
- Tools: Vertex AI Pipelines, Vertex AI endpoints, Cloud Storage, Cloud Monitoring, Docs/Sheets templates.  
- Accessibility: captions, alt text, high-contrast diagrams, downloadable templates.
