The system is designed to streamline prospect management, validate outreach approval conditions, update prospect records, and prepare personalised business email drafts for human review.

The project demonstrates how workflow automation can reduce repetitive administrative tasks, improve data organisation, and introduce safeguards into business communication processes.

Project Objectives

Automate prospect data processing.

Manage business contacts through Google Sheets.

Apply conditional checks before preparing email drafts.

Create personalised email drafts using stored prospect information.

Update prospect records automatically.

Maintain human oversight before emails are sent.

Technologies Used

Technology

Purpose

n8n

Workflow automation and orchestration

Google Sheets

Prospect database and record management

Gmail

Email draft creation

Conditional Logic (IF Nodes)

Approval, consent and unsubscribe validation

Expressions

Dynamic mapping of prospect information into email fields

How the System Works

The workflow follows these steps:

Workflow Trigger: Initiates the automation process.

Google Sheets Integration: Retrieves prospect information from the outreach database.

Approval Validation: Checks whether a prospect has been approved for outreach.

Consent Validation: Checks the prospect's recorded marketing permission status.

Unsubscribe Validation: Excludes contacts marked as unsubscribed.

Batch Limiting: Restricts the number of records processed during a workflow execution.

Google Sheets Update: Updates the prospect's status to indicate that the record is ready for manual review.

Gmail Integration: Creates an email draft using the prospect's email address, subject and personalised message.

Workflow Safeguards

The system incorporates several safeguards:

Approval status must be Approved.

Consent status must be Yes.

Unsubscribe status must be No.

Email drafts are created for manual review rather than automatically sent.

Batch processing helps control the number of records handled per execution.

Personal review is required before sending outreach communications.

Note: A recorded consent status must be supported by valid permission and appropriate evidence. A publicly available email address alone does not establish marketing consent.

Example Use Case

The system can be adapted for:

Business development teams.

B2B lead management.

Partnership outreach.

Professional networking campaigns.

Client relationship management.

Business development prospecting.

Project Architecture

Google Sheets → Approval Check → Consent Check → Unsubscribe Check → Batch Limit → Google Sheets Update → Gmail Draft Creation

Skills Demonstrated

Through this project, I demonstrated practical experience in:

No-code automation development.

Workflow design and orchestration.

Google Sheets integration.

Gmail integration.

Conditional logic and decision-making.

Dynamic data mapping.

Business process automation.

Data management and validation.

Workflow testing and troubleshooting.

Project Status

Prototype – Functional workflow under testing.

The workflow has been configured to retrieve prospect records, apply conditional checks, update Google Sheets, and create Gmail drafts.

Further testing and refinement are planned before production deployment.

Security and Data Protection

This repository should contain only sanitised workflow exports, fictional sample data, and demonstration screenshots.

No passwords, API keys, authentication credentials, or real prospect contact information should be published.

Author

Lord Offei-Darko

Business Automation | No-Code Workflow Development | Digital Transformation
