# Phase 2 – Requirement Analysis

## Functional Requirements

| ID | Requirement |
|---|---|
| FR-01 | The system shall use ServiceNow Flow Designer. |
| FR-02 | The flow shall be named `Standard laptop task`. |
| FR-03 | The flow application shall be Global. |
| FR-04 | The flow shall run as System user. |
| FR-05 | The trigger shall be Service Catalog. |
| FR-06 | The action shall be Create Catalog Task. |
| FR-07 | Requested Item Record shall be mapped to Request item. |
| FR-08 | Short description shall be `Laptop need to Configured`. |
| FR-09 | Description shall be `Laptop need to Configured`. |
| FR-10 | Assignment group shall be Hardware. |
| FR-11 | Approval shall be Approved. |
| FR-12 | The flow shall be saved and activated. |
| FR-13 | The flow shall be associated with the Standard Laptop catalog item. |
| FR-14 | A Standard Laptop order shall be placed for validation. |
| FR-15 | The resulting Catalog Task shall be inspected for status, short description and assignment group. |

## Non-Functional Requirements
- The workflow should reduce manual overhead.
- Task allocation should be consistent.
- The workflow should be simple to maintain.
- The implementation should be testable through the Service Catalog.

## Actors
- Requester/User
- Approver
- IT Procurement process
- Hardware team
- ServiceNow administrator

## Inputs
- Standard Laptop catalog request
- Requested Item Record
- Approval state

## Outputs
- Catalog Task
- Short description
- Description
- Hardware assignment
- Updated task status

## Acceptance Criteria
A project is considered successful when an approved Standard Laptop request produces a Catalog Task containing the required text and Hardware assignment.
