# ChatDok Cardiovascular Health Data Research

**Longitudinal real-world conversational data for cardiovascular AI research.**

ChatDok GmbH develops AI-enabled digital health solutions for cardiovascular and other chronic conditions. Through ongoing patient interactions, the ChatDok platform captures conversational information about health concerns, reported symptoms, comorbidities, treatment-related questions, care guidance and follow-up.

This repository documents the research potential of these data, their characteristics, and the principles guiding responsible curation, evaluation and research access.

| | |
|---|---|
| **Organisation** | ChatDok GmbH |
| **Website** | https://chatdok.com |
| **Research enquiries** | hello@chatdok.com |

> **This repository contains no patient data.** It is documentation only. See [Data access and privacy](#data-access-and-privacy).

## Contents

- [Overview](#overview)
- [Data characteristics](#data-characteristics)
- [Research directions](#research-directions)
- [Data curation and quality](#data-curation-and-quality)
- [Data access and privacy](#data-access-and-privacy)
- [Responsible research](#responsible-research)
- [Collaboration](#collaboration)
- [Repository status](#repository-status)

Supporting documents:

- [Data card](docs/data-card.md): what is known about the source data, and what is still being characterised
- [Research access request](docs/access-request-template.md): what to send us when you propose a study

## Overview

The ChatDok platform has recorded more than one million patient conversations, predominantly involving cardiovascular health and ongoing digital patient support.

Repeated interactions can preserve context that may be difficult to capture in a single clinical encounter. Patients may describe changes in symptoms, raise questions about their conditions, discuss treatment-related concerns and return for follow-up. Studied carefully, these conversations may help researchers investigate how patient-reported health concerns and care needs evolve over time.

The potential research value lies in the combination of conversational context, temporal information and repeated patient interactions. This resource may complement structured clinical datasets, particularly in research on longitudinal cardiovascular care and patient-centred AI.

Conversation volume does not represent the number of unique patients. The number of distinct individuals, the extent of longitudinal linkage, and the availability of clinical measurements and outcomes must be established through dataset-specific assessment.

## Data characteristics

Depending on the record and available metadata, the source data may include:

- **Patient-reported health information:** symptoms, concerns and descriptions of perceived changes in health.
- **Conditions and comorbidities:** health conditions discussed during patient interactions.
- **Treatment-related conversations:** questions about medications, care plans, adherence and self-management.
- **Guideline-informed support:** health information and recommendations provided through the platform.
- **Follow-up interactions:** subsequent conversations that may clarify earlier concerns or describe changes over time.
- **Temporal and interaction metadata:** available timestamps and other fields that support reconstruction of interaction sequences.

These categories describe potential information in conversational records, not necessarily verified clinical facts. A reported condition, discussed medication or suggested intervention should not automatically be interpreted as a confirmed diagnosis, administered treatment or observed clinical outcome.

The availability, completeness and reliability of individual data fields will be documented as the resource is characterised.

## Research directions

### Cardiovascular risk and deterioration

Investigating whether information from longitudinal patient conversations can improve identification of patients who may benefit from further clinical assessment.

### Longitudinal patient trajectories

Studying how reported symptoms, concerns and care needs evolve across repeated interactions.

### Multimodal cardiovascular AI

Where appropriate linked clinical data are available and authorised, evaluating whether conversational information adds predictive value beyond structured clinical variables.

### Patient support and care pathways

Analysing recurring questions, reported concerns and follow-up patterns to inform the evaluation and improvement of digital care support.

### Personalised cardiovascular modelling

Exploring whether longitudinal information can contribute to patient-specific disease trajectory models. Estimating responses to alternative treatments is a more demanding research objective that requires suitable treatment and outcome data, appropriate methods and independent validation.

These are potential research applications. Their feasibility and performance must be established through systematic evaluation.

## Data curation and quality

Developing a reliable research resource from conversational health data requires documented curation and quality assessment. Key activities include:

- Defining research cohorts and documenting source systems and time coverage.
- Establishing the number of distinct individuals and the extent of longitudinal linkage.
- Assessing completeness, duplication, missingness and temporal consistency.
- Distinguishing patient-reported information, platform-generated guidance and independently verified clinical information.
- Evaluating the reliability of extracted clinical concepts and derived labels.
- Assessing potential biases, representativeness and limitations.
- Documenting data provenance and the permitted scope of research use.

Derived variables should retain appropriate provenance and uncertainty. Automated extraction should not be treated as equivalent to clinical verification.

## Data access and privacy

Conversational health data may contain sensitive personal information and indirect identifiers. Raw patient conversations and identifiable patient-level records are therefore not published in this repository.

Research access to underlying data is subject to the proposed use, applicable data protection requirements, relevant permissions and contractual arrangements, and any necessary organisational or ethical approvals.

Researchers interested in collaboration or data access are invited to contact ChatDok with a description of their research question, required data, intended outputs and institutional or governance arrangements. The [access request template](docs/access-request-template.md) lists what to include.

The existence of platform data does not, by itself, establish unrestricted access or permission for every secondary research purpose. Data availability and access conditions must be assessed for each proposed study.

## Responsible research

Research using real-world conversational data must account for incomplete information, ambiguity, differences in how people describe symptoms, and the risk of confusing reported events with clinically confirmed outcomes.

Research resources and derived outputs should use appropriate privacy safeguards, data minimisation, access controls and disclosure-risk assessment. Synthetic examples used for documentation or testing should be clearly identified as synthetic.

AI systems developed using these data should be evaluated against appropriate clinical comparators, with attention to uncertainty, subgroup performance and limitations. Research outputs are intended to support scientific investigation and clinical assessment, not replace professional judgement.

## Collaboration

ChatDok welcomes research discussions with clinical institutions, universities and technical teams working on cardiovascular AI, longitudinal health data, clinical evaluation and responsible data curation.

Potential areas of collaboration include:

- Longitudinal cardiovascular dataset curation.
- Clinical language processing and temporal information extraction.
- Evaluation of conversational signals for cardiovascular risk assessment.
- Reproducible benchmarks for real-world healthcare AI.
- Patient-specific disease trajectory modelling.
- Privacy-preserving research infrastructure.

Any collaboration involving patient-level data will be subject to appropriate access arrangements and governance review.

Related open resources from ChatDok:

- [cardio-symptom-lexicon](https://github.com/chatdok-health/cardio-symptom-lexicon): patient-language cardiovascular symptom phrases in English and German
- [cardio-safety-eval](https://github.com/chatdok-health/cardio-safety-eval): synthetic red-flag escalation tests for health chatbots
- [health-text-redact](https://github.com/chatdok-health/health-text-redact): removal of direct identifiers from health conversations

**Research contact:** hello@chatdok.com
**Organisation:** ChatDok GmbH
**Website:** https://chatdok.com

## Repository status

This repository provides an overview of the source data's potential research value and the principles guiding its responsible use. It is not a public release of patient-level data.

Dataset counts, variable availability, longitudinal linkage, clinical outcome coverage and access conditions will be documented as they are verified. Further documentation and research resources may be added as curation and evaluation work progresses.

## License

The documentation in this repository is licensed under [CC BY 4.0](LICENSE). This license covers this documentation only. It grants no rights to any ChatDok data.

To cite this resource, see [CITATION.cff](CITATION.cff).
