---
type: workflow
id: templates-documents
title: "Document Templates"
description: "Document templates — PRDs, specs, reports, emails, research, and project management"
tags: [Production, Templates]
connections:
  - target: doc-prd
    type: uses
  - target: doc-feature-spec
    type: uses
  - target: doc-competitive-analysis
    type: uses
  - target: doc-user-story
    type: uses
  - target: doc-project-brief
    type: uses
  - target: doc-status-report
    type: uses
  - target: doc-meeting-minutes
    type: uses
  - target: doc-retrospective
    type: uses
  - target: doc-risk-register
    type: uses
  - target: doc-email-formal
    type: uses
  - target: doc-email-followup
    type: uses
  - target: doc-email-introduction
    type: uses
  - target: doc-meeting-agenda
    type: uses
  - target: doc-proposal
    type: uses
  - target: doc-research-summary
    type: uses
  - target: doc-swot
    type: uses
  - target: doc-decision
    type: uses
  - target: doc-blog-post
    type: uses
  - target: doc-content-brief
    type: uses
  - target: doc-newsletter
    type: uses
  - target: doc-study-notes
    type: uses
  - target: doc-essay-outline
    type: uses
  - target: doc-research-paper
    type: uses
  - target: doc-daily-plan
    type: uses
  - target: doc-travel-itinerary
    type: uses
  - target: doc-onboarding
    type: uses
  - target: doc-release-notes
    type: uses
  - target: doc-change-request
    type: uses
  - target: doc-technical-spec
    type: uses
  - target: doc-incident-report
    type: uses
  - target: doc-api-spec
    type: uses
  - target: llm-service
    type: runs_on
metadata:
  estimated_duration: "1 minute"
  trigger: manual
  template: true
output_step: "doc-prd"
composite_steps:
  - "doc-prd"
  - "doc-feature-spec"
  - "doc-competitive-analysis"
  - "doc-user-story"
  - "doc-project-brief"
  - "doc-status-report"
  - "doc-meeting-minutes"
  - "doc-retrospective"
  - "doc-risk-register"
  - "doc-email-formal"
  - "doc-email-followup"
  - "doc-email-introduction"
  - "doc-meeting-agenda"
  - "doc-proposal"
  - "doc-research-summary"
  - "doc-swot"
  - "doc-decision"
  - "doc-blog-post"
  - "doc-content-brief"
  - "doc-newsletter"
  - "doc-study-notes"
  - "doc-essay-outline"
  - "doc-research-paper"
  - "doc-daily-plan"
  - "doc-travel-itinerary"
  - "doc-onboarding"
  - "doc-release-notes"
  - "doc-change-request"
  - "doc-technical-spec"
  - "doc-incident-report"
  - "doc-api-spec"
execution:
  - skill: "doc-prd"
    step_type: "generation"
---

## Overview

This skrpt contains 31 document templates for use when creating new document nodes. Import this skrpt to add these templates to your template picker.

## Templates

### Product & Strategy

- **Product Requirements Document** — PRD template for defining product features and scope
- **Feature Specification** — Detailed spec for a single feature
- **Competitive Analysis** — Compare products against competitors
- **User Story** — User story with acceptance criteria
- **Technical Specification** — Technical architecture or implementation spec
- **API Specification** — REST or GraphQL API endpoint specification

### Project Management

- **Project Brief** — High-level project overview and objectives
- **Status Report** — Weekly or periodic project status update
- **Meeting Minutes** — Record of meeting discussions and actions
- **Retrospective** — Sprint or project retrospective
- **Risk Register** — Track and manage project risks

### Communication

- **Formal Email** — Professional email template
- **Follow-Up Email** — Follow up after a meeting or event
- **Introduction Email** — Introduce yourself or connect two people
- **Meeting Agenda** — Structured meeting agenda
- **Proposal** — Business or project proposal

### Research & Analysis

- **Research Summary** — Summarise findings from research
- **SWOT Analysis** — Strengths, Weaknesses, Opportunities, Threats
- **Decision Document** — Record and justify a decision

### Content Creation

- **Blog Post** — Blog post structure with SEO elements
- **Content Brief** — Brief for commissioning content
- **Newsletter** — Email newsletter template

### Education & Study

- **Study Notes** — Structured notes for learning a topic
- **Essay Outline** — Structured outline for an academic essay
- **Research Paper Outline** — Academic research paper structure

### Personal Productivity

- **Daily Plan** — Structured daily plan and task list
- **Travel Itinerary** — Travel plan with logistics and schedule
- **Onboarding Guide** — New starter or new project onboarding checklist

### Release & Change

- **Release Notes** — Changelog and release announcement
- **Change Request** — Formal change request for processes or systems
- **Incident Report** — Post-incident report template

