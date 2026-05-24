# Ryan | AI Application Developer

[中文版本](./README.zh-CN.md) · [Back to Profile](./README.md)

I am an AI application developer focused on **Java backend engineering, Spring Boot, LLM applications, RAG, Agent workflows, and grounded AI product design**.

I am currently building **JianMiao 简喵**, a job-description-grounded AI career preparation platform.

My focus is not just making AI generate better text. I care more about building AI workflows that are:

- grounded in user-provided evidence
- traceable across workflow steps
- resistant to unsupported claims
- understandable to real users
- useful in practical career-preparation scenarios
- reliable enough to support high-stakes personal decisions

## Current Focus

I am mainly working on:

- Java / Spring Boot backend engineering
- LLM application development
- RAG and evidence-grounded generation
- Agent workflow design
- structured output validation
- anti-hallucination guardrails
- AI product architecture
- career-tech product development

My long-term interest is in the engineering layer between raw LLM capability and real user-facing products.

## Main Project: JianMiao 简喵

**JianMiao** is a job-description-grounded AI career preparation platform.

It is designed around a specific job description and a saved resume version, instead of treating resume optimization as a generic text-generation task.

The core workflow is:

```text
Resume editing
→ Resume scoring
→ Job description diagnosis
→ Candidate evidence indexing
→ Job-specific resume rewriting
→ Guard Trail
→ Evidence-constrained bullet rewriting
→ Grounded Interview Pack
→ Cover letter generation
→ JobOptimizationSession Workbench
```

## Why JianMiao Is Different

Many AI resume tools focus on a simple workflow:

```text
input resume → AI rewriting → polished output
```

This approach can easily create several problems:

- unsupported career claims
- exaggerated achievements
- job description requirements being converted into fake candidate experience
- generic and vague phrasing
- interview answers that cannot be defended
- unclear boundaries between user facts and AI-generated assumptions

JianMiao focuses on a different direction:

```text
candidate evidence → job requirements → support relationship → risk control → traceable rewriting
```

The product principle is:

> Improve expression, but do not fabricate experience.  
> Strengthen structure, but do not invent evidence.  
> Help users prepare for interviews, but do not create unsupported personal facts.

## Core Modules

### Resume Scoring

Analyzes the quality of a resume from the perspective of structure, clarity, role alignment, and potential weaknesses.

### Job Description Diagnosis

Evaluates a resume against a specific job description and identifies:

- strong matches
- weak matches
- missing requirements
- requirements that should not be fabricated
- areas that can be strengthened with existing evidence

### Candidate Evidence Index

Extracts and organizes candidate facts from resume content so that downstream AI generation can be checked against available evidence.

### Job-specific Resume Rewriting

Generates a job-specific resume version based on the selected job description and the saved resume version.

The goal is not to invent a stronger candidate, but to express existing experience in a more accurate, structured, and role-aligned way.

### Guard Trail

Records how AI-generated claims are handled during rewriting:

- kept
- downgraded
- blocked
- marked as requiring more evidence

This makes the rewriting process more auditable and helps users understand which claims are safe and which may be risky.

### Local Bullet Rewrite

Provides evidence-constrained rewriting for individual resume bullets without directly changing the saved resume version.

### Grounded Interview Pack

Generates interview preparation questions and reference answer points based on the user’s resume, target job description, and available evidence.

The goal is to help users prepare for realistic interview follow-up questions without fabricating unsupported personal experience.

### Cover Letter Generation

Generates cover letters based on the resume, job description, company information, and role information while preserving evidence boundaries.

### JobOptimizationSession Workbench

Aggregates job-specific materials into one session-based workspace:

- job description snapshot
- base resume version
- tailored resume version
- Guard Trail
- interview preparation
- cover letter
- job-specific AI artifacts

The purpose is to help users see a complete job-preparation process instead of scattered AI-generated outputs.

## Technical Stack

Backend:

- Java
- Spring Boot
- MyBatis / MySQL
- Redis
- Flyway
- REST API design
- JUnit testing

Frontend:

- Vue
- TypeScript
- Vite
- Pinia
- Vitest

AI engineering:

- LLM API integration
- prompt design
- structured output validation
- evidence-grounded generation
- anti-hallucination guardrails
- claim verification
- RAG-oriented architecture
- Agent workflow design

Product engineering:

- AI artifact persistence
- version binding
- session-based workflow design
- user-facing trust signals
- demo-ready product packaging

## Another Project

### Spring AI Cross-border Customer Service

A Spring AI based multilingual customer-service Agent platform for cross-border e-commerce scenarios.

Main focus:

- LLM-powered customer-service automation
- multilingual interaction
- Spring Boot backend workflow
- Agent-style task orchestration
- AI application engineering

## Writing

I write about:

- AI application development
- Java backend engineering
- LLM engineering
- RAG and Agent workflows
- product architecture
- the process of building JianMiao

Blog:

```text
https://yanxai.com
```

## Current Direction

I am working toward building practical AI products that go beyond simple text generation.

My current direction includes:

- grounded generation
- evidence chains
- anti-hallucination design
- structured AI workflows
- reliable AI systems for real users
- career-tech products with traceable AI outputs

## Links

- GitHub: https://github.com/RyanCoreAI
- Blog: https://yanxai.com
