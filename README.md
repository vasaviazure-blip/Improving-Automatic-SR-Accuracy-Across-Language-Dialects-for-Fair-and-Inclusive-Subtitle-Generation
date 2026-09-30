# Improving Automatic Speech Recognition Accuracy Across Language Dialects

## Research, Professionalism and Innovation

### Overview

This project is a research proposal focused on improving the fairness and inclusivity of Automatic Speech Recognition (ASR) systems used for subtitle generation.

Current ASR systems can perform differently across language dialects and speech varieties. This can result in unequal subtitle quality, particularly for speakers of under-represented dialects.

The proposed research investigates how dialect-balanced benchmarking, fairness-aware evaluation, and targeted model adaptation could reduce transcription disparities while maintaining overall subtitle quality.

## Research Question

How can Automatic Speech Recognition systems be improved to provide more accurate, fair, and inclusive subtitles across different English dialect groups?

## Research Hypothesis

The project hypothesises that combining:

- Dialect-balanced benchmarking
- Fairness-aware evaluation
- Targeted model adaptation

can reduce transcription performance gaps across dialect groups without reducing overall subtitle quality.

## Research Objectives

The project has five main objectives:

1. Develop a balanced multi-dialect benchmark for subtitle-oriented ASR evaluation.
2. Audit representative ASR systems using transcription and fairness metrics across selected dialect groups.
3. Develop dialect-aware ASR improvement strategies using data balancing, augmentation, and parameter-efficient fine-tuning.
4. Develop a fair subtitle generation pipeline including punctuation restoration, readable segmentation, timestamp alignment, and transparent handling of uncertain outputs.
5. Conduct a people-centred evaluation focusing on subtitle readability, trust, and inclusivity.

## Target Dialect Groups

The proposed benchmark focuses on five English dialect groups:

- Standard American English
- Southern Standard British English
- African American English
- Indian English
- Nigerian English

The selection provides a focused basis for investigating differences in ASR performance across both reference and under-represented varieties.

## Methodology

The proposed research is organised into five work packages.

### WP1 — Dialect Speech Data Collection and Benchmark Development

This work package focuses on creating a subtitle-oriented multi-dialect benchmark.

Key activities include:

- Dialect identification and selection
- Data collection and curation
- Dataset harmonisation
- Benchmark creation
- Annotation and quality checking
- Dataset documentation

Public resources such as Common Voice, CORAAL, FLEURS, VoxPopuli, and the Speech Accent Archive are proposed as data sources.

### WP2 — Auditing ASR Models for Dialect Bias

The project proposes evaluating:

- Whisper
- wav2vec 2.0
- One commercial or platform-based captioning/ASR system where access is available

Evaluation will consider:

- Word Error Rate (WER)
- Character Error Rate (CER)
- Worst-group WER
- WER disparity
- Worst-to-best group WER ratio
- Subtitle-specific error patterns

The analysis will also consider issues such as named-entity errors, subtitle segmentation problems, dialect-marker deletions, and meaning-changing substitutions.

### WP3 — Dialect-Aware ASR Development

The proposed improvement strategies include:

- Training-data rebalancing
- SpecAugment
- Controlled noise augmentation
- Transfer learning
- Parameter-efficient fine-tuning
- LoRA or adapter-based approaches

The project also considers worst-group-aware optimisation as a possible secondary research direction.

### WP4 — Fair Subtitle Generation

The proposed subtitle pipeline will integrate:

1. Audio preprocessing
2. ASR inference
3. Punctuation restoration
4. Readable subtitle segmentation
5. Timestamp alignment
6. SRT or WebVTT output

Subtitle quality will be assessed using transcription accuracy, segmentation quality, timing coherence, and readability.

### WP5 — User Evaluation and Validation

The proposed evaluation includes:

- Evaluation with speakers from the target dialect communities
- Accessibility-focused evaluation
- Assessment of subtitle clarity
- Trustworthiness
- Subtitle lag
- Formatting quality
- Perceived fairness

The results would be used for iterative refinement of the proposed system.

## Societal Importance

Subtitle systems are increasingly used in:

- Education
- Entertainment
- Online media
- Public communication
- Accessibility services

Unequal ASR performance across dialects can create barriers for people who rely on captions. The proposed research therefore considers both the technical performance of ASR systems and the experience of subtitle users.

## Research Innovation

The project connects three areas that are often evaluated separately:

1. Fairness-aware ASR evaluation
2. Dialect-aware ASR adaptation
3. Subtitle-specific quality assessment

The proposal aims to connect model-level fairness measurements with the quality of subtitles experienced by users.

## Risk Management

The proposal identifies several risks.

### Technical Risk

ASR performance may not improve equally across all dialects.

**Mitigation:** Monitor worst-group performance and focus on reducing performance disparities.

### Data Risk

Public datasets may contain uneven metadata or limited dialect coverage.

**Mitigation:** Carefully curate datasets and document their limitations.

### Ethical Risk

Speech datasets may raise privacy and representation concerns.

**Mitigation:** Use appropriately licensed data, minimise personal-data exposure, and avoid treating dialect differences as deficiencies.

### Project Management Risk

The scope of the project could become too broad.

**Mitigation:** Use work packages, milestones, deliverables, and regular progress reviews to maintain a realistic scope.

## Project Timeline

The proposed project is organised into 12 quarters.

Key milestones include:

- **M1:** Dialect groups selected and benchmark design agreed
- **M2:** Benchmark dataset curated and documented
- **M3:** Baseline fairness audit completed
- **M4:** Dialect-aware ASR adaptation completed
- **M5:** Subtitle generation prototype integrated
- **M6:** User-centred validation completed
- **M7:** Final recommendations and dissemination outputs completed

## Expected Deliverables

The proposed project aims to produce:

- Multi-dialect benchmark specification and dataset documentation
- ASR fairness audit report and evaluation toolkit
- Dialect-aware adapted ASR model and error analysis
- Fair subtitle generation prototype
- User evaluation and accessibility findings
- Final project report and deployment recommendations

## My Contribution

As a member of the research group, my main contributions focused on:

- Work Package 5: User Evaluation and Validation
- Section 7: Risk Assessment
- Gantt chart design
- Project milestones and deliverables
- Reviewing the methodology for timeline feasibility

My contribution included planning the user-centred evaluation approach, accessibility evaluation, iterative refinement process, project risk assessment, and alignment of the proposed work with the project timeline.

## Skills Demonstrated

- Research methodology
- Academic research
- Literature review
- Artificial Intelligence
- Automatic Speech Recognition
- Machine Learning
- AI fairness and responsible AI
- Project planning
- Risk assessment
- Team collaboration
- Technical communication
- Research proposal development
- Accessibility and inclusive AI

## Technologies and Concepts

- Automatic Speech Recognition (ASR)
- Whisper
- wav2vec 2.0
- Python
- Machine Learning
- Deep Learning
- Natural Language Processing
- Speech Processing
- LoRA
- Data Augmentation
- Fairness Evaluation
- Subtitle Generation

## Project Status

**Research Proposal**

This repository documents the research proposal, methodology, work packages, project planning, expected outcomes, risks, and proposed evaluation strategy.

## Team

The research proposal was developed collaboratively by:

- Haniruth Muthuselvam
- Subhan Ahmed Haris
- Anusha Undamatla
- Nakul Arora
- Vasavi Atkuri
- Zain Shahid


