# PlaceIQ — College Placement Analytics & Eligibility Engine

> A configurable, rule-based placement analytics platform that evaluates student profiles against company/job requirements to generate eligibility checks, multi-factor candidate matching scores, and placement insights.

## 📌 Overview

**PlaceIQ** is a placement analytics engine built for college placement cells to streamline how student eligibility, skill-matching, and placement statistics are managed. Rather than hard-coding logic for a single company, the system is designed as a **configurable eligibility and matching engine** that works across multiple company profiles and criteria sets — making it reusable semester after semester, recruiter after recruiter.

Built as a Java OOP-based project (CSE-DS, 3rd Semester PBL), it combines core object-oriented design with a data science layer for scoring, ranking, and skill-gap analysis.

## 🎯 Problem Statement

Placement cells manually cross-check hundreds of student profiles (CGPA, backlogs, skills, certifications, aptitude scores) against varying company eligibility criteria — a slow, error-prone, and non-scalable process. PlaceIQ automates this by:

- Validating and structuring student/company data
- Running configurable, rule-based eligibility checks
- Scoring and ranking candidates using a multi-factor matching algorithm
- Surfacing skill-gap insights and placement statistics for decision-making

## ✨ Key Features

- **Student & Company Profile Management** — Maintain structured records with CGPA, semester scores, backlogs, technical skills, certifications, aptitude/communication scores, and internships.
- **Configurable Eligibility Engine** — Apply company-specific eligibility rules without rewriting code for each new company or role.
- **Multi-Factor Candidate Scoring** — Weighted scoring model combining academic, skill, and aptitude factors.
- **Candidate Ranking** — Rank eligible candidates per company/job role.
- **Placement Statistics Dashboard** — Company-wise placement stats and skill-demand summaries.
- **Skill-Gap Analysis** — Identify common, scarce, and frequently-requested skills across the student pool.
- **Advanced Filtering** — Filter by CGPA, skill, branch, eligibility status, and placement status.
- **Reporting** — Generate reports on eligible, shortlisted, selected, and unplaced students.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Java (OOP) |
| UI | Java Swing |
| Database | JDBC-connected relational database |
| Data | CSV/text datasets |
| Data Science | Validation, frequency analysis, weighted scoring, ranking, aggregation |

## 🧩 Core Java Concepts Demonstrated

- **OOP Hierarchy** — `Student` / `Graduate` / `Employee` and `Company` / `JobRole` class structures
- **Interfaces** — Pluggable eligibility and scoring strategies
- **Collections & Arrays** — Managing dynamic student/company datasets
- **Exception Handling** — Custom exceptions for invalid/boundary data
- **Packages** — Modular project structure
- **String Processing**
- **File I/O** — Reading/writing CSV and text datasets
- **JDBC** — Persistent relational data storage
- **Swing & Event Handling** — Interactive desktop UI

## 🏗️ Architecture

```
├── Student / Graduate / Employee hierarchy
├── Company / JobRole hierarchy
├── EligibilityStrategy (interface)
├── ScoringStrategy (interface)
├── DataValidator
├── SkillGapAnalyzer
├── PlacementReportGenerator
├── DAO layer (JDBC)
└── UI (Swing)
```

*(Class diagram and full system/workflow diagram included in `/docs`.)*

## 📊 Data Science Component

- Data validation and cleaning
- Frequency analysis of skills and outcomes
- Weighted multi-factor scoring model
- Candidate ranking algorithms
- Aggregation and comparative analytics across companies/roles

## 📦 Deliverables

- ✅ Working Java application with Swing-based UI
- ✅ Relational database connected via JDBC with meaningful tables/queries
- ✅ Dataset (CSV/text) with documented data dictionary and validation rules
- ✅ Class diagram and system architecture/workflow diagram
- ✅ Demonstration of OOP concepts, custom exceptions, file I/O, and an advanced Java feature
- ✅ Analytical reports showing key insights and decisions
- ✅ Test cases covering valid, invalid, boundary, and exception scenarios

## 👥 Team
4 students

## 📄 License

This project was built for academic purposes (CSE-DS, 3rd Semester, OOP Using Java PBL — Project 3).

---

*Contributions, issues, and feature suggestions are welcome.*
