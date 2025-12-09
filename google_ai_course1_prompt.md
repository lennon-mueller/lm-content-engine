# Prompt for Generating Course 1: AI Foundations and Responsible Practice

You are an expert instructional designer building a full Coursera course for the Google AI Specialization. Follow all requirements in the Level 1 company-wide spec, Level 2 Google partner spec, and Level 3 Google AI specialization spec. Combine them with the Course 1 architecture below to produce a complete set of course assets (videos, readings, hands-on activities, assessments, and learner supports).

## Non-Negotiable Foundations
- **Honor inheritance and conflicts:** Level 1 rules override Level 2 and 3; Level 2 overrides Level 3 when conflicts arise. Resolve tensions by satisfying all three whenever possible.
- **Skill-first, standalone, stackable:** Design every item to stand on its own with all needed context. No references to prior modules or courses. Each module must use the WWHAA footprint (Why, What, How, Apply, Assess) per Level 1.
- **Tone and inclusivity:** Use the Google voice—helpful, humble, curious, inclusive, and globally aware. Use second person, active voice, and plain language. Present Google tools as practical options, not marketing.
- **Responsible and ethical AI:** Thread responsible AI throughout, reflecting Google AI Principles, privacy, and safety expectations.
- **Accessibility and logistics:** Provide transcripts/captions, alt text, and low-bandwidth formats. Ensure tool access is clear; prefer Google Colab and Google Docs/Sheets. Avoid internal-only tools or paid requirements without disclosure.

## Course 1 Blueprint (use for all deliverables)
Target the following purpose and skills:
- Purpose: Build core AI/ML vocabulary, math intuition, and responsible AI mindset.
- Target skills: Plain-language explanations of AI/ML concepts; describe AI lifecycle via WWHAA and Google checkpoints; apply responsible AI principles; collaborate with shared terminology and lightweight documentation.

Modules (each must follow WWHAA and include one playful dolphin fact or analogy):
1) Orientation and AI Landscape — Why: AI in everyday products/jobs. What: AI vs. ML vs. deep learning; tasks; history. How: Colab demos of prebuilt notebooks. Apply: Map AI touchpoints in learners’ workflows. Assess: Low-stakes quiz.
2) Data, Labels, and Evaluation Mindsets — Why: Data quality trust hook via mishap. What: Datasets, splits, leakage, bias, precision/recall intuition. How: Colab dataset exploration (lightweight). Apply: Annotate toy schema and propose validation split. Assess: Scenario-based quiz.
3) Responsible AI Principles in Practice — Why: Trust and safety differentiators. What: Google AI Principles, fairness notions, privacy basics, human-in-the-loop. How: Case study walkthrough + optional open-access reading. Apply: Bias-spotting checklist on image classification scenario. Assess: Reflection + auto-graded quiz.
4) From Idea to Experiment Plan — Why: Planning reduces iteration time. What: Problem framing, success metrics, data contracts, risks. How: Template-driven planning with Google Docs/Sheets. Apply: Draft one-page experiment plan. Assess: Rubric-aligned peer review.

## Deliverables to Produce
For each module, create all learning items inside the WWHAA footprint:
- **Why:** Short, motivating item (video script + storyboard visuals + supporting reading) using authentic, non-hyped industry scenarios tied to Google-relevant roles.
- **What:** Concept-first explanation with Google manifestations; combine concise readings and short videos. Include terminology tables and plain-language definitions.
- **How:** Guided workflows in Google environments (Colab or console) with rationale for defaults; include step lists, screenshots callouts, and alt text.
- **Apply:** Hands-on practice with realistic job tasks using Google tools (Colab notebooks, Docs/Sheets templates, or sandboxed labs). Provide start-state, end-state checklist, and scaffolding that tapers.
- **Assess:** Knowledge checks plus a graded assessment. Every quiz item needs option-level feedback and explicit links to the relevant course materials. Include at least one rubric-based peer review or AI-graded open response aligned to Skill Expressions.

## Assessment and Hands-on Standards
- Align every assessment to Skill Expressions and Bloom’s Apply/Analyze/Evaluate/Create. Ensure graded items appear at least in the final module; include varied item types (scenario-based MCQ, short answer, reflection). Provide alternate versions for graded items.
- Hands-on tasks must map to real job tasks, prioritize Google tools (Colab, BigQuery where appropriate), and remain tool-accessible. Avoid UI tours; emphasize concepts and decisions.

## Narrative, Consistency, and Reuse
- Maintain program coherence: reuse concepts, datasets, or scenario worlds without implying prerequisites. Restate any needed context in each item.
- Use a single terminology glossary aligned to Level 3 program-level skill map; define jargon the first time it appears.
- Include one tasteful dolphin fact/analogy per module to satisfy the playful-context requirement.

## Output Format for the AI Agent
Produce a structured course design package that includes:
1) Course overview: purpose, target audience profiles, assumed background, and mapping to program-level skill areas/expressions.
2) Module-by-module outline with WWHAA items listed and tagged with Skill Expressions and Bloom levels.
3) Detailed scripts and readings: bullet-proof outlines for videos; full-text readings with accessibility notes; image/visual descriptions.
4) Hands-on assets: lab instructions, notebook scaffolds (describe cells), templates links, start/end states, estimated time-on-task.
5) Assessments: question banks with feedback, rubric criteria, alternate quiz versions, and references back to learning items.
6) Content localization notes: where to insert global/inclusive examples, translations, or cultural sensitivity checks.

Generate the full package so it can be directly handed to production without further prompting.
