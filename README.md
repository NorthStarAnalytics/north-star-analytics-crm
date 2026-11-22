# North Star Analytics CRM

**Custom Python CRM | Business Process Automation | Sales Operations | Consulting Management | Data Analytics**

## Project Overview

North Star Analytics CRM is a custom-built customer relationship management and business operations system developed using Python, Google Colab, Google Sheets, and Google Drive.

I developed this system to support the operational needs of an independent analytics and business process consulting practice.

The project demonstrates how Python programming, data management, business process engineering, and workflow automation can be integrated into a centralized business management solution.

Rather than relying entirely on commercial CRM software, this project explores how a customizable system can be designed around specific organizational processes and operational requirements.

## Business Problem

Managing a consulting business involves several interconnected processes, including prospect identification, client outreach, sales qualification, discovery interviews, proposal development, project delivery, and financial tracking.

When these activities are managed across disconnected spreadsheets and documents, organizations can experience:

- Inconsistent data entry and recordkeeping
- Missed follow-ups and sales opportunities
- Limited visibility into the sales pipeline
- Repetitive administrative tasks
- Difficulty monitoring project progress
- Fragmented financial and operational reporting

North Star Analytics CRM was designed to consolidate these activities into a structured system with reusable Python functions, centralized data storage, and interactive operational tools.

## System Architecture

The application uses two primary notebooks.

### 1. CRM Master Notebook — Initial Setup and Development

The Master Notebook establishes the system's underlying infrastructure and business logic.

Its responsibilities include database configuration, worksheet creation, validation rules, CRM functions, business workflows, reporting capabilities, and development testing.

It also documents the system's iterative development process.

**The Master Notebook is intended for initial configuration, development, and maintenance rather than routine daily operation.**

### 2. CRM Launcher Notebook — Daily Operations

The Launcher Notebook provides an interactive operational interface built using Python and ipywidgets.

It allows users to access CRM functions through menus and forms without repeatedly executing the original development workflow.

The Launcher connects to the Google Sheets database and supporting Google Drive directories established during initial setup.

### Architecture Overview

```text
          NORTH STAR ANALYTICS CRM
                    |
          +---------+---------+
          |                   |
     MASTER NOTEBOOK     LAUNCHER NOTEBOOK
     Setup & Development Daily Operations
          |                   |
          +---------+---------+
                    |
              PYTHON LOGIC
                    |
          +---------+---------+
          |                   |
     GOOGLE SHEETS        GOOGLE DRIVE
     CRM Data Storage     Document Storage
          |                   |
          +---------+---------+
                    |
            BUSINESS WORKFLOWS
                    |
       Sales | Discovery | Proposals
       Projects | Finance | Reporting
```

## Core CRM Capabilities

### Company and Contact Management

Structured company and contact records, unique identifiers, and relationship tracking.

### Sales Pipeline Management

Opportunity tracking, pipeline stages, qualification, opportunity scoring, and sales activity monitoring.

### Outreach and Follow-Up Management

Communication activity logging, follow-up scheduling, daily outreach goals, and weekly activity reporting.

### Client Discovery and Business Analysis

Structured discovery interviews, dealership-focused question libraries, operational pain-point identification, and consulting service recommendations.

### Proposal Development

Proposal scope preparation, service and deliverable definitions, pricing, scope protections, internal quality-control reviews, and Microsoft Word proposal generation.

### Project Management

Project records, task creation, deadlines, estimated hours, and project-to-client relationships.

### Continuing Services

Recurring service records, billing frequency, renewal dates, and ongoing client engagement tracking.

### Financial and Operational Reporting

Financial records, CRM dashboards, sales activity summaries, pipeline reporting, and recurring revenue monitoring.

### Data Management and Recovery

Database validation, integrity checks, backup utilities, and recovery testing.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application logic and workflow automation |
| Google Colab | Notebook-based development and execution |
| Google Sheets | Structured CRM database |
| Google Drive | Document and project file storage |
| gspread | Google Sheets API integration |
| ipywidgets | Interactive forms and menus |
| pandas | Data processing and reporting |
| python-docx | Proposal document generation |
| openpyxl | Spreadsheet and Excel support |
| Google APIs | Authentication and Google Workspace integration |

## Repository Structure

```text
north-star-analytics-crm/
|
|-- README.md
|-- requirements.txt
|-- .gitignore
|
|-- notebooks/
|   |-- North_Star_Analytics_CRM_Master.ipynb
|   |-- North_Star_Analytics_CRM_Launcher.ipynb
|
|-- docs/
|
|-- screenshots/
|
|-- sample_data/
```

The repository structure represents the intended organization. Supporting files and sanitized notebooks may be added as development and publication preparation continue.

## Setup and Configuration

This project was originally developed in Google Colab using Google Drive and Google Sheets.

The public version removes account-specific identifiers and replaces private configuration values with placeholders.

To configure the system:

1. Open the Master Notebook in Google Colab.
2. Review the required Python dependencies.
3. Authenticate with Google Drive and Google Sheets using your own account.
4. Replace anonymized directory and spreadsheet identifiers with your own configuration.
5. Review and execute the required initial database setup steps.
6. Verify the database structure and supporting functions.
7. Configure the separate Launcher Notebook for daily CRM operations.

**Important:** The Master Notebook documents an iterative development process. It should not be treated as a one-click installer. Some cells create or modify directories, worksheets, and records.

The public notebooks require configuration and validation before operational use.

## Privacy and Data Protection

The GitHub edition is a sanitized representation of the development project.

Private Google Drive paths, spreadsheet identifiers, demonstration record IDs, and saved execution outputs have been removed or replaced with placeholders.

No real client records, private authentication credentials, or operational business data are intended for public distribution.

Users should provide their own Google Workspace configuration and use fictional data when testing the system.

## Development Status

**Status: Active Development and Testing**

The CRM includes implemented functionality for company management, sales tracking, outreach, discovery, proposals, project records, financial management, and reporting.

Several workflows have undergone individual testing. Additional integration testing, project management interfaces, and operational refinements are planned.

The project is not presented as a fully validated production deployment.

## Skills Demonstrated

This project showcases practical experience in:

- Python application development
- Business process engineering
- Workflow automation
- CRM architecture and data modeling
- Google Workspace API integration
- Data validation and integrity management
- Sales operations and pipeline management
- Business analytics and KPI reporting
- Document generation
- Interactive application development
- Operational risk controls and quality assurance

## Future Development

Planned enhancements include expanded project management interfaces, task status tracking, billable-hour monitoring, client onboarding automation, enhanced reporting, and additional workflow testing.

The long-term objective is to create a flexible business operations platform that can evolve alongside the consulting practice.

---

**Project:** North Star Analytics CRM

**Category:** Python Software Development | Business Process Engineering | Operational Analytics

**Purpose:** Professional portfolio demonstration and ongoing application development.
