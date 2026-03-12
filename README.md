![UML](https://img.shields.io/badge/UML-System%20Design-blue)
![Software Engineering](https://img.shields.io/badge/Software%20Engineering-Analysis-green)
![Systems Analysis](https://img.shields.io/badge/Systems%20Analysis-UML-orange)

# ⚙️ Systems Analysis and Design - UML Case Study

A software engineering case study demonstrating systems analysis, UML modelling, behavioural system design, CRUD analysis, and user acceptance testing.

This repository presents a structured analysis and design of a conceptual system using several industry-standard modelling techniques. The goal of the project is to translate system requirements into clear UML diagrams and supporting documentation that can guide software development and validation.

The project demonstrates how software systems are analysed **before implementation**, using diagrams and documentation to model system behaviour, structure, and data interactions.


## Key Skills Demonstrated

- Systems analysis and requirements interpretation
- UML modelling and diagram design
- Structural system modelling
- Behavioural workflow modelling
- System interaction modelling
- CRUD analysis
- User Acceptance Test (UAT) planning
- Software design documentation

## Repository Structure
```text
Systems-Analysis-and-Design-UML-Case-Study/
│
├── docs/
│   ├── ICT284 Systems Analysis and Design Assessment 2 - Styverson Ng.pdf
│   └── ICT284 Assignment 2 Report.pdf
│
├── diagrams/
│   ├── Domain Class Model/
│      └── Domain Class Model.png/
│   ├── Activity Diagram/
│      └── Activity Diagram - Print Credit Payment Report.png/
│   ├── State Machine Diagram/
│      ├── State Machine Diagram - Painting Job Legend.png/
│      └── State Machine Diagram - Painting Job.png/
│   └── System Sequence Diagram/
│      └── System Sequence Diagram - Provide Feedback.png/
│
├── testing/
│   ├── User Acceptance Test Plan 1.png
│   ├── User Acceptance Test Plan 2.png
│   ├── User Acceptance Test Plan.xlsx
│   └── User Acceptance Test Plan.pdf
│
├── analysis/
    └── CRUD Matrix.png
```

The repository is organised to separate system design artefacts, documentation, analysis materials, and testing plans to mirror a simplified software development lifecycle structure.

## Domain Class Model

The **Domain Class Model** captures the core entities, attributes, and relationships within the system domain. It represents the structural foundation of the system by identifying the primary objects and how they interact with each other.

This model is useful for understanding the data structure of the system and guiding database or object-oriented design during later implementation phases.

<p align="center">
    <img width="716.25" height="697.5" alt="Domain Class Model" src="https://github.com/user-attachments/assets/e1cce637-1f4b-45b6-b14e-dfd7f0348bba" />
</p>


## Activity Diagram – Print Credit Payment Report

The **Activity Diagram** illustrates the workflow involved in generating a credit payment report. It maps the sequence of actions, decision points, and control flow within the process.

Activity diagrams are useful for modelling business processes and system workflows before implementation.

<p align="center">
    <img width="705.5" height="1084" alt="Activity Diagram - Print Credit Payment Report" src="https://github.com/user-attachments/assets/8f2f5d75-106e-4a0f-8e71-77cf2593efd7" />
</p>

## State Machine Diagram – Painting Job Lifecycle

The **State Machine Diagram** models the lifecycle of a painting job as it transitions between different states.

Each state represents a stage of the job process, while transitions occur when specific events or conditions are triggered.

State machine diagrams help developers understand how system objects behave over time and how state changes are handled.
<p align="center">
    <img width="731.25" height="778.125" alt="State Machine Diagram - Painting Job" src="https://github.com/user-attachments/assets/befc8c73-2fad-4d2b-839a-9995ba4e53a3" />
    <img width="731.25" height="278.7" alt="State Machine Diagram - Painting Job Legend" src="https://github.com/user-attachments/assets/3d769e46-881b-474a-9d80-07b33ba609d3" />
</p>

## System Sequence Diagram – Provide Feedback

The **System Sequence Diagram (SSD)** models the interaction between the user and the system when submitting feedback for a completed painting job.

The diagram illustrates the following system interactions:

1. User authentication through login verification
2. Retrieval and display of selected job details
3. Submission and validation of a feedback form
4. Confirmation of feedback submission
5. System updates to the painter's profile and notification process

This diagram highlights how system components collaborate to process user feedback.

<img width="4157" height="3176" alt="System Sequence Diagram - Provide Feedback" src="https://github.com/user-attachments/assets/8962795d-70bf-49b1-aeae-63a49ca9e802" />


## CRUD Matrix

The **CRUD Matrix** maps system operations against data entities to determine where records are:

- **Created**
- **Read**
- **Updated**
- **Deleted**

This matrix helps verify that all necessary data interactions are accounted for and ensures consistency between system functionality and data management.

CRUD analysis is commonly used during system design to validate database interaction requirements.

The matrix for this project can be found in:
<p align="center">
    <img width="881" height="1028" alt="CRUD Matrix" src="https://github.com/user-attachments/assets/2730b0ca-a061-49f4-85a6-af2d273ec6ac" />
</p>

## User Acceptance Testing (UAT)

The **User Acceptance Test Plan** defines test scenarios used to validate that the system meets the intended user requirements.

UAT ensures that the system behaves correctly from the perspective of the end user and that all functional requirements are satisfied before deployment.

Test planning includes:

- Test scenarios
- Expected results
- Acceptance criteria

The full UAT documentation is available in:
- testing/User Acceptance Test Plan.xlsx
- testing/User Acceptance Test Plan.pdf














## 🖋️ Author

**Styverson Ng**

Bachelor of Information Technology <br>
Artificial Intelligence & Autonomous Systems <br>
Cyber Security & Cyber Forensics <br>

Murdoch University <br>
