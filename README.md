# FitFlow Redesign

## IT3060 – Human Computer Interaction

**BSc (Hons) in Information Technology – Year 3, Semester 2 – 2026**

---

## 1. Project Overview

FitFlow Redesign is a proposed redesign of a fitness application focused on improving usability, personalization, accessibility, and overall user experience.

The redesigned system aims to provide users with fitness-related services such as workout planning, nutrition tracking, progress monitoring, social interaction, and AI-powered recommendations.

The project focuses on evaluating suitable technologies and designing a scalable architecture for the redesigned FitFlow system.

---

## 2. Project Objectives

* Improve the overall usability of FitFlow.
* Provide personalized fitness experiences.
* Support workout and nutrition tracking.
* Provide fitness progress monitoring.
* Integrate AI-powered recommendations.
* Support social interaction between users.
* Provide secure user authentication.
* Design a scalable and maintainable system architecture.
* Select suitable technologies based on project requirements.

---

## 3. Key Features

* User registration and authentication
* Personalized workout plans
* Workout and exercise tracking
* Nutrition tracking
* Fitness progress monitoring
* AI-powered recommendations
* Social sharing and interaction
* Notifications
* Secure user data management
* Mobile and web access

---

## 4. Proposed Technology Stack

| Component               | Proposed Technology     |
| ----------------------- | ----------------------- |
| Mobile Frontend         | React Native            |
| Web Frontend            | React                   |
| Backend                 | Node.js / NestJS        |
| Database                | PostgreSQL              |
| Authentication          | Auth0                   |
| AI Service              | Python / FastAPI        |
| AI/ML                   | TensorFlow / OpenAI API |
| Real-Time Communication | Socket.IO               |
| Cache                   | Redis                   |
| API                     | REST API                |
| Version Control         | Git / GitHub            |
| Containerization        | Docker                  |
| Cloud Platform          | AWS                     |

Detailed technology information is available in [`docs/tech-stack.md`](docs/tech-stack.md).

---

## 5. System Architecture

The proposed FitFlow system consists of the following major components:

```text
Users
  │
  ▼
React Native / React
  │
  ▼
NestJS Backend
  │
  ├── Auth0
  ├── PostgreSQL
  ├── Redis
  ├── Socket.IO
  │
  └── AI Service
        │
        ▼
   Python / FastAPI
        │
        ▼
   AI/ML Models
```

The detailed architecture documentation is available in [`docs/architecture.md`](docs/architecture.md).

The visual architecture diagram is available at:

`docs/architecture-diagram.png`

---

## 6. Technology Comparison

Different technologies were considered before selecting the proposed technology stack.

The comparison considered factors such as:

* Performance
* Scalability
* Security
* Development complexity
* Maintainability
* Cost
* AI/ML support
* Community and ecosystem
* Real-time support

The detailed comparison matrix is available in [`docs/comparison-matrix.md`](docs/comparison-matrix.md).

---

## 7. Repository Structure

```text
fitflow-redesign/
│
├── frontend/
│   └── README.md
│
├── backend/
│   └── README.md
│
├── ai-service/
│   └── README.md
│
├── docs/
│   ├── tech-stack.md
│   ├── comparison-matrix.md
│   ├── architecture.md
│   └── architecture-diagram.png
│
├── README.md
└── .gitignore
```

### Folder Description

**frontend/**
Contains the planned mobile and web frontend implementation.

**backend/**
Contains the planned backend API and business logic.

**ai-service/**
Contains the planned AI/ML service.

**docs/**
Contains project documentation, technology comparisons, and architecture information.

---

## 8. Project Documentation

| Document                        | Description                                 |
| ------------------------------- | ------------------------------------------- |
| `README.md`                     | Main project overview                       |
| `docs/tech-stack.md`            | Selected technology stack and justification |
| `docs/comparison-matrix.md`     | Technology comparison and evaluation        |
| `docs/architecture.md`          | System architecture documentation           |
| `docs/architecture-diagram.png` | Visual system architecture                  |

---

## 9. GitHub Workflow

The repository uses Git and GitHub for version control and collaboration.

The proposed workflow is:

```text
Feature Branch
      ↓
Development
      ↓
Commit
      ↓
Push
      ↓
Pull Request
      ↓
Review
      ↓
Merge to main
```

The `main` branch is intended to contain stable project changes.

---

## 10. Academic Information

**Module:** IT3060 – Human Computer Interaction
**Programme:** BSc (Hons) in Information Technology
**Year:** 3
**Semester:** 2
**Academic Year:** 2026
**Project:** FitFlow Redesign

---

## 11. Team Members

1. Group Leader – [Name]
2. [Member 2]
3. [Member 3]
4. [Member 4]

---

## 12. Activity 5

This repository was created as part of Activity 5 to:

* Create the `fitflow-redesign` GitHub repository.
* Establish the initial project structure.
* Organize supporting documentation.
* Document the proposed technology stack.
* Include the technology comparison matrix.
* Include the system architecture and diagram.
* Configure GitHub repository settings.
* Maintain the project using Git version control.
