# Marketing Campaign Management Automation System

This repository presents a sanitized portfolio case study of an enterprise-grade marketing campaign management and automation platform developed for a banking environment.

The system was designed to support the full lifecycle of internal marketing email campaigns, from creation and editing to approval, scheduling, controlled dispatch, and audit visibility. It was developed to improve operational efficiency, reduce manual campaign handling, enforce structured approval workflows, and support secure communication processes within a regulated organizational setting.

## Project Background

Marketing communication in enterprise and financial environments often requires stronger control than simple email drafting and sending. Campaigns may need structured review, role-based authorization, scheduling, traceability, and controlled release to ensure consistency, accountability, and compliance with internal processes.

This project was developed to automate and streamline that workflow for a marketing department by providing a centralized platform for campaign creation, approval, scheduling, and lifecycle management.

## Objectives

- digitize and centralize campaign management
- reduce manual coordination in campaign release workflows
- enforce role-based approval before campaign dispatch
- support scheduling and controlled sending
- provide visibility into campaign status and activity history
- improve reliability, consistency, and operational efficiency

## Core Features

- role-based authentication and authorization
- campaign creation and editing
- campaign submission for approval
- approval and rejection workflow
- scheduling for future dispatch
- test-send support
- campaign detail and status tracking
- activity timeline and audit visibility
- protected routes and restricted actions
- backend-driven campaign lifecycle management

## Tech Stack

### Frontend
- React
- TypeScript
- React Router
- Context API / state-based UI workflow
- responsive dashboard-style interface

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- JWT authentication and authorization
- background scheduling/service logic

### Database
- PostgreSQL

### Supporting Services
- email dispatch integration
- scheduler/background processing
- secure API communication

## Workflow Summary

The platform supports a structured campaign lifecycle such as:

Draft → Pending Approval → Approved / Rejected → Scheduled / Sent / Cancelled

This workflow helps ensure that campaigns are not released without the required internal review and authorization.

## Repository Structure

- `frontend_architecture/` – frontend structure, UI flow, routing, and state notes
- `backend_architecture/` – backend design, entities, DTOs, services, and API notes
- `system_diagrams/` – architecture, lifecycle, role, and database diagrams
- `screenshots/` – sanitized UI screenshots and visual previews
- `documentation/` – project overview, feature notes, and case-study material
- `workflow_logic/` – campaign lifecycle and approval/scheduling workflow notes
- `security_notes/` – confidentiality and production security notes
- `api_structure/` – sanitized request/response examples and endpoint structure notes

## My Contributions

This project was designed and developed by me for the marketing department in a banking environment. My work included:

- planning and structuring the full system workflow
- designing and implementing the frontend architecture
- designing and implementing the backend architecture
- integrating authentication and protected access control
- building campaign lifecycle logic across frontend and backend
- implementing approval, rejection, scheduling, and dispatch workflows
- designing supporting database interactions and API communication
- documenting the system architecture, workflow, and engineering decisions

## Confidentiality Notice

Because this project was developed in a professional institutional setting, this public repository does not include the original production source code, internal configuration, credentials, deployment details, or sensitive organizational data.

Instead, the repository is presented as a sanitized engineering portfolio focused on architecture, workflow design, screenshots, system documentation, and implementation decisions.

## Engineering Value

This project demonstrates practical experience in:

- full-stack enterprise application design
- workflow automation
- secure role-based systems
- frontend/backend integration
- database-backed application development
- production-minded software engineering
- documentation and technical communication

## Future Improvements

- queue-based background job processing
- richer immutable audit logging
- campaign template versioning
- analytics and performance reporting
- better observability and monitoring
- stronger automated testing for workflow transitions
- more granular role and permission models

## Author

John Afriyie Oduro
