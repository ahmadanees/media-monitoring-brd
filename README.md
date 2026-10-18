# Media Monitoring & Reporting Platform
## Business Requirements and Systems Analysis

A portfolio case study documenting analysis for a real client proposal
for a bilingual media monitoring and reporting platform.

## Project Status

Requirements and proposal stage. This repository contains analysis
and design documentation, not a deployed application.

## My Role

Business Analyst / Systems Analyst — Part-Time Contract

My contribution included stakeholder communication, analysis of business
needs, scope definition, and preparation of the Business Requirements
Document (BRD).

## Business Problem

The proposed system addresses the difficulty of continuously reviewing
live television and social media content across spoken audio, written
text, and visual material.

The analysis focuses on identifying potentially non-compliant content,
supporting human review, and producing traceable reports.

## Proposed Scope

- Monitoring approximately 14 live television channels.
- Read-only monitoring of Instagram, YouTube, Facebook, TikTok and Reddit,
  subject to platform access permissions and API constraints.
- Urdu and English language coverage, including Roman-Urdu and
  code-switched speech where applicable.
- Audio transcription, on-screen text extraction, and visual analysis.
- Severity-based flagging and human review.
- Audit logging and structured reporting.

Content removal, platform enforcement, and interruption of live
broadcasts are outside the proposed scope.

**Methodology reference:** Kendall & Kendall, Systems Engineering Analysis and Design, 11th Ed.

## Analysis Deliverables

- Business problem and objectives.
- In-scope and out-of-scope boundaries.
- Functional and non-functional requirements.
- Proposed processing architecture.
- Implementation feasibility and preliminary cost analysis.
- Assumptions, dependencies, and operational constraints.

## Documentation

| Artifact | Purpose |
|---|---|
| [Business Requirements Document](documentation/Media_Monitoring_BRD.pdf) | Formal requirements, proposed solution, feasibility analysis, and assumptions |
| [Architecture Diagram](diagrams/media_monitoring_architecture.md) | Visual overview of ingestion, processing, human review, and reporting |

## Proposed System Architecture

![Proposed media monitoring architecture](diagrams/media_monitoring_architecture.svg)

The proposed design separates processing into three paths:

1. Audio: speech-to-text processing.
2. Text: on-screen OCR and native social text processing.
3. Visual: image and sampled video-frame classification.

Flagged items enter a severity-based review workflow, with audit
records and structured reports supporting traceability.

## Skills Demonstrated

Requirements analysis · Stakeholder communication · Scope definition ·
Process decomposition · Systems analysis · Feasibility assessment ·
Technical documentation

## Limitations

- The architecture describes a proposed system, not verified production
  behavior.
- Cost estimates are preliminary planning figures, not supplier quotes
  or measured operating costs.
- Language accuracy, throughput, review capacity, and platform access
  require validation before implementation.
- No operational savings or detection performance are claimed as
  achieved results.
