---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
- block: collection
  content:
    title: Selected Projects
    text: >
      A curated selection of projects that reflect my focus on **cloud security,
      confidential computing and defence/health-oriented innovation**.  
      Highlights include applied research in precision medicine,
      confidential computing in HPC-enabled clouds,
      federated multi-cloud security for defence and NATO-aligned
      architectures for data sovereignty.
    filters:
      folders:
        - project
  design:
    view: article-grid
    fill_image: false
    columns: 4
---

# --- add below your existing collection block ---

- block: markdown
  content:
    title: Consulting & Availability
    text: >-
      I help organizations in **critical infrastructure** deliver secure cloud platforms and
      **Confidential Computing** solutions—primarily in **defence** and **healthcare**.  
      Focus areas: remote attestation & data-in-use protection (AMD SEV-SNP, Nitro Enclaves),
      cloud security architecture (AWS, Azure, OpenStack), security reviews and compliance
      (ISO 27001 / BSI / NATO-aligned architectures).

      **Day rate:** from **€750 / day** (excl. VAT).  
      **Availability:** fractional (1–3 days/week) or project sprints; full weeks by arrangement.

- block: feature
  content:
    title: Engagement Models
    items:
      - name: Advisory / Architecture
        description: >
          Strategic guidance, architecture reviews, security patterns & decision memos.
          Typical: 2–4 workshops + written recommendations.
      - name: Project Delivery
        description: >
          Hands-on design & implementation (IaC, attestation flows, enclave enablement,
          controls & guardrails). Typical: 1–3 days/week for 4–12 weeks.
      - name: Security & Compliance Readiness
        description: >
          Gap analysis and remediation plan for ISO 27001 / BSI IT-Grundschutz; evidence
          prep for audits and stakeholder reviews.
      - name: Fractional / Interim
        description: >
          Part-time Security/Cloud Architect for programmes in defence/health—governance,
          technical leadership, vendor alignment.
  design:
    columns: 4

- block: markdown
  content:
    title: Industries & Use Cases
    text: >-
      **Defence:** multi-cloud data sovereignty, secure data sharing, federation.  
      **Healthcare:** privacy-preserving analytics, enclave-backed research pipelines.  
      **R&D:** HPC + enclaves, confidential AI/ML workloads, evidence & benchmarks.

- block: cta
  content:
    title: Ready to start a project?
    text: >-
      Share a brief on scope, timelines and stakeholders. I typically respond within one business day.
    buttons:
      - label: Email Valentin
        url: "mailto:vp@valentinpfeil.com?subject=Project%20Inquiry%20%2D%20Confidential%20Computing%20%2F%20Cloud%20Security"
        style: primary
      - label: View Malt Profile
        url: "https://en.malt.de/profile/valentinpfeil"
        style: secondary