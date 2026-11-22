
# RepoMap AI
### Explainable Role-Based Change Localization

> Software Engineering Graduation Project | 2026–2027

## Overview

RepoMap AI is an intelligent codebase analysis system designed to help software developers understand existing Python repositories and identify relevant code components for specific development tasks.

The system combines static code analysis, dependency graphs, semantic retrieval, and large language models to provide structured, explainable, and evidence-backed recommendations.

## Project Objectives

- Analyze the structure of existing Python repositories.
- Identify relevant files, classes, and functions.
- Combine semantic relevance with structural dependencies.
- Classify recommended components according to their roles.
- Provide explanations supported by source code evidence.
- Evaluate the effectiveness of hybrid retrieval methods.

## Core Features (Planned)

### Role-Based Change Localization

Recommendations are organized into three categories:

1. **Direct Change Locations** — code potentially requiring modification.
2. **Potentially Impacted Components** — code that may be affected by the proposed changes.
3. **Relevant Tests** — existing tests recommended for review or execution.

## Proposed Architecture

- Static Analysis — Python AST
- Structural Analysis — Dependency Graphs
- Semantic Retrieval — Embeddings
- Hybrid Ranking — Semantic and Structural Relevance
- AI Integration — Large Language Models
- User Interface — Web Application

## Evaluation Strategy

The project will investigate whether combining semantic and structural information improves code localization compared with alternative retrieval approaches.

The evaluation will consider retrieval accuracy, role classification, explanation quality, and execution time.

## Project Scope

- Public GitHub repositories.
- Python source code.
- Read-only repository analysis.
- No automatic source code modification.

## Project Status

Project initialization and proposal preparation.

## Academic Information

- **Institution:** Azrieli College of Engineering – Jerusalem
- **Degree:** B.Sc. in Software Engineering
- **Academic Year:** 2026–2027
- **Developer:** Aya Diab
- **Project Advisor:** Roger Cohen
