# Standart-Dev-Guidelines
Documentation on Standard Development Guidelines followed by our Organization (Serendipity)


# Project Guidelines

Welcome to the Project Guidelines documentation. This guide will provide a comprehensive overview of how to get started on a new project, the steps involved in planning and executing the project, and the coding conventions and guidelines to follow. 

## Table of Contents

1. [Getting Started on a New Project](#getting-started-on-a-new-project)
   - [How to Plan a New Project](#how-to-plan-a-new-project)
   - [Requirements Specifications](#requirements-specifications)
     - [Product Requirements Documentation (PRD)](#product-requirements-documentation-prd)
     - [System Requirements (HLD) - Infrastructure Requirements (Capacity/Load Estimation)](#system-requirements-hld---infrastructure-requirements-capacityload-estimation)
   - [System Design](#system-design)
     - [Data Flow Diagrams (DFD)](#data-flow-diagrams-dfd)
     - [App Flow Diagrams](#app-flow-diagrams)
     - [Class Diagrams (Entities)](#class-diagrams-entities)
     - [Database Schema Design](#database-schema-design)
     - [High-level Infrastructure Design](#high-level-infrastructure-design)
   - [Project Execution Planning](#project-execution-planning)
     - [List of Modules & Functionalities](#list-of-modules--functionalities)
     - [Create Timelines & Milestones](#create-timelines--milestones)
     - [Finalize Requirements](#finalize-requirements)
   
2. [Coding Conventions and Guidelines](#coding-conventions-and-guidelines)
   - [Git Workflow Guidelines](#git-workflow-guidelines)
   - [CI/CD Guidelines](#cicd-guidelines)
     - [Releases Documentation (releases.md)](#releases-documentation-releasesmd)
     - [CI/CD Tools Documentation](#cicd-tools-documentation)
   - [Project & File Structure Guidelines](#project--file-structure-guidelines)
   - [Coding Guidelines](#coding-guidelines)
   - [Documentation Guidelines](#documentation-guidelines)

## Getting Started on a New Project

### How to Plan a New Project

Planning a new project involves several key steps:

- Define the project scope and objectives.
- Identify the stakeholders and their roles.
- Establish a timeline for the project.
- Assess the resources required, including personnel, tools, and budget.
- Create a project charter or plan that outlines the above elements.

### Requirements Specifications

#### Product Requirements Documentation (PRD)

The PRD should clearly define:

- The purpose of the product.
- The features and functionalities required.
- The target audience and user personas.
- User stories or use cases.
- Acceptance criteria for each feature.

#### System Requirements (HLD) - Infrastructure Requirements (Capacity/Load Estimation)

The High-Level Design (HLD) should include:

- An overview of the system architecture.
- Infrastructure requirements, including servers, databases, and network specifications.
- Capacity and load estimations to ensure the system can handle expected traffic and usage.

### System Design

#### Data Flow Diagrams (DFD)

DFDs should be created to:

- Illustrate the flow of data within the system.
- Identify the sources and destinations of data.
- Show how data is processed at various stages.

#### App Flow Diagrams

App flow diagrams should:

- Outline the user flow through the application.
- Highlight key screens and interactions.
- Identify navigation paths and decision points.

#### Class Diagrams (Entities)

Class diagrams should:

- Define the key entities in the system.
- Show the relationships between entities.
- Include attributes and methods for each class.

#### Database Schema Design

The database schema design should:

- Define the tables and their relationships.
- Specify the fields and data types for each table.
- Include indexes, constraints, and keys.

#### High-level Infrastructure Design

The high-level infrastructure design should:

- Outline the overall architecture of the system.
- Identify the major components and their interactions.
- Include diagrams of the network, servers, and other infrastructure elements.

### Project Execution Planning

#### List of Modules & Functionalities

Create a comprehensive list of:

- All the modules that need to be developed.
- The functionalities of each module.
- Dependencies between modules.

#### Create Timelines & Milestones

Develop a timeline that includes:

- Key milestones and deadlines.
- Phases of the project (e.g., planning, development, testing, deployment).
- Tasks and deliverables for each phase.

#### Finalize Requirements

Ensure all requirements are:

- Clearly defined and documented.
- Reviewed and approved by stakeholders.
- Aligned with the project scope and objectives.

## Coding Conventions and Guidelines

### Git Workflow Guidelines

Establish a standard Git workflow that includes:

- Branching strategies (e.g., feature branches, develop, main).
- Commit message conventions.
- Pull request and code review processes.

### CI/CD Guidelines

#### Releases Documentation (releases.md)

Maintain a `releases.md` file that:

- Documents all releases.
- Includes version numbers, release dates, and change logs.
- Provides links to relevant documentation and resources.

#### CI/CD Tools Documentation

Document the CI/CD tools used, including:

- Setup and configuration instructions.
- Guidelines for creating and managing pipelines.
- Best practices for automated testing and deployment.

### Project & File Structure Guidelines

Define a standard project and file structure that:

- Organizes code in a logical and maintainable way.
- Separates concerns (e.g., models, views, controllers).
- Includes directories for tests, documentation, and configuration files.

### Coding Guidelines

Follow coding guidelines that:

- Adhere to industry standards (e.g., PEP 8 for Python).
- Include best practices for readability, maintainability, and performance.
- Specify conventions for naming, formatting, and documentation.

### Documentation Guidelines

Ensure thorough and consistent documentation by:

- Using tools like ReadTheDocs or GitBook.
- Writing clear and concise comments and docstrings.
- Maintaining up-to-date documentation for all aspects of the project.

## References

1. [PEP 8 - Style Guide for Python Code](https://peps.python.org/pep-0008/)
2. [ReadTheDocs](https://readthedocs.org/) | [GitBook](https://www.gitbook.com/) - For Documentation

