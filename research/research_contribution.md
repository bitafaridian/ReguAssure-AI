1. Research Direction

ReguAssure AI aims to develop an integrated, risk-aware and adaptive AI framework for optimizing the planning, scheduling and execution of internal and external quality audits in medical software development.

The research combines predictive intelligence, constrained multi-objective optimization, evidence-grounded AI agent workflows and feedback-driven dynamic re-optimization within a unified decision-support framework.

The proposed framework is designed to support audit professionals in allocating limited resources, prioritizing audit activities, maintaining mandatory audit requirements, managing execution uncertainty and ensuring evidence traceability.

The system is not intended to autonomously certify regulatory compliance or replace professional audit judgment.


2. Intended Research Contributions

Contribution 1 — Uncertainty-Aware Predictive Intelligence for Audit Planning

Develop a predictive component capable of estimating audit-related characteristics, including:

- Audit activity risk and priority.
- Expected audit effort and duration.
- Audit task complexity.
- Potential resource requirements.
- Prediction uncertainty.

Rather than relying exclusively on deterministic predictions, the framework will investigate how uncertainty associated with predicted risk and audit effort can be incorporated into subsequent planning and optimization decisions.

Research objective: Investigate how predictive intelligence and uncertainty estimation can improve the quality of audit planning decisions under limited resources and incomplete information.


Contribution 2 — Quality-Constrained Multi-Objective Audit Optimization

Develop a mathematical optimization model for selecting, prioritizing, scheduling and allocating resources to audit activities.

The model will investigate the simultaneous consideration of:

- Audit execution time.
- Resource utilization and allocation.
- Risk-weighted audit coverage.
- Mandatory audit activities.
- Auditor qualifications and competencies.
- Task dependencies.
- Scheduling and operational constraints.
- Audit quality requirements.

Audit quality and mandatory requirements will be represented through appropriate constraints rather than treated as expendable objectives.

The model will investigate trade-offs between operational efficiency, audit coverage and resource consumption while respecting predefined audit requirements.

Research objective: Develop a constrained multi-objective optimization approach that enables systematic and transparent audit planning under operational constraints and predictive uncertainty.


Contribution 3 — Evidence-Grounded AI Agent for Audit Execution Support

Design an AI agent architecture capable of supporting selected audit execution activities through structured, controlled and traceable workflows.

The agent will investigate capabilities such as:

- Retrieving relevant audit documents and evidence.
- Mapping evidence to predefined audit criteria.
- Performing approved verification checks.
- Identifying evidence gaps and inconsistencies.
- Generating structured preliminary audit observations.
- Supporting documentation and reporting.
- Recording evidence provenance and execution logs.

Agent-generated observations and outputs will remain subject to human review and approval.

Research objective: Investigate how evidence-grounded agent workflows can support audit execution while maintaining transparency, traceability and human oversight.

Contribution 4 — Feedback-Driven Dynamic Audit Re-Optimization

Develop a feedback mechanism that allows the audit plan to be revised during execution in response to changing operational conditions.

Potential triggers include:

- Newly identified audit findings.
- Unexpected audit effort or delays.
- Newly available or missing evidence.
- Changes in resource availability.
- Emerging risk signals.
- Changes in task completion status.

The framework will investigate how execution feedback can update relevant planning parameters and trigger re-optimization of audit priorities, schedules and resource allocations.

Research objective: Investigate whether feedback-driven re-optimization can improve audit responsiveness, risk-weighted coverage and resource efficiency compared with static audit plans.

Contribution 5 — Integrated and Adaptable Framework for Internal and External Quality Auditing

Develop an integrated framework that combines predictive intelligence, optimization, AI-supported execution and dynamic feedback within a common audit planning and execution architecture.

The framework will investigate how a shared optimization and decision-support core can accommodate different operational configurations for:

- Internal quality audits.
- External quality audits, including supplier quality audits and independent QMS assessments.

The framework will distinguish the operational requirements, responsibilities, information access and constraints associated with different audit contexts while maintaining a consistent methodological foundation.

The initial application domain will be quality auditing in medical software development.

Research objective: Investigate the adaptability of an integrated audit optimization framework across distinct audit contexts without requiring fundamentally different optimization methodologies for each context.


3. Preliminary Mathematical Research Direction

The optimization component is intended to formulate audit planning as a constrained multi-objective decision problem.

The preliminary optimization direction includes:

- Minimizing audit-related operational effort and resource consumption.
- Minimizing audit planning and execution delays.
- Maximizing risk-weighted audit coverage.
- Ensuring completion of mandatory audit activities.
- Respecting resource capacity, qualification, scheduling and task dependency constraints.
- Investigating how uncertainty in predictive estimates affects planning decisions.

The exact mathematical formulation, objective functions, decision variables and constraint structure will be established through the literature review and subsequent model development.

Potential approaches include deterministic, robust or stochastic optimization, depending on the characteristics of the available data and the uncertainty modelling requirements.

4. Intended Experimental Research

The integrated framework will be evaluated against progressively more sophisticated baseline approaches.

Potential experimental configurations:

1. Conventional rule-based audit planning.
2. Predictive AI-supported planning.
3. Optimization-based audit planning.
4. Predictive AI combined with optimization.
5. Optimization with AI-supported audit execution.
6. Integrated predictive, optimization, agent and feedback-driven framework.

Potential evaluation metrics include:

- Audit planning and execution time.
- Resource utilization.
- Risk-weighted audit coverage.
- Mandatory audit activity completion.
- Evidence completeness.
- Evidence traceability.
- Finding detection performance where ground truth is available.
- Human review and correction requirements.
- Robustness under uncertainty.
- Performance under dynamic operational scenarios.

The experimental design will seek to isolate the contribution of individual components through comparative experiments and ablation studies.

Synthetic datasets may be used during initial development, with their limitations and assumptions explicitly documented.

5. Research Novelty and Validation

The contributions described in this document represent intended research contributions and hypotheses rather than established scientific novelty.

Their originality and significance will be evaluated through:

- Structured literature review.
- Identification of existing audit planning and optimization methodologies.
- Comparison of existing predictive audit approaches.
- Investigation of agent-based audit automation.
- Analysis of existing dynamic and adaptive audit planning approaches.
- Identification of limitations in existing integrated approaches.
- Experimental validation of the proposed framework.

The final research contributions will be refined based on the identified research gap, mathematical model development and experimental results.

6. Research Status

Current status: Conceptual research and preliminary framework design.

The research framework, proposed contribution areas and preliminary research direction have been defined.

The research gap, technical feasibility, mathematical formulation, implementation architecture and experimental performance remain subject to further investigation and validation.
