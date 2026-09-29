# SmartBridge Project – Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Overview
This project automates the standard laptop procurement/configuration workflow in ServiceNow using Flow Designer.

The workflow creates a Catalog Task after the service request is approved, updates the task details, and assigns it to the Hardware assignment group so the laptop can be configured promptly.

## Source Project
Based on the SmartBridge project document:
**Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer**

## Problem
Standard laptop requests involve manual configuration steps that can be delayed or overlooked.

## Objective
Automate the procurement/configuration task creation and assignment process to:
- provide timely laptop configuration
- reduce manual intervention and errors
- improve IT resource allocation
- improve procurement efficiency and productivity

## Technology
- ServiceNow
- Flow Designer
- Service Catalog
- Catalog Tasks
- Hardware Assignment Group

## Required Flow
**Flow Name:** Standard laptop task  
**Application:** Global  
**Run As:** System user  
**Trigger:** Service Catalog  
**Action:** Create Catalog Task

### Action values
- Requested Item Record → Request item
- Short description → `Laptop need to Configured`
- Description → `Laptop need to Configured`
- Assignment group → `Hardware`
- Approval → `Approved`

## Phase Structure
1. Brainstorming & Ideation
2. Requirement Analysis
3. Project Design
4. Project Planning
5. Project Development
6. Project Testing
7. Project Documentation
8. Project Demonstration

## Final Result
When a Standard Laptop service request is approved, a Catalog Task is created with the required description and assigned to Hardware.

## Submission
Publish this project folder as a public GitHub repository. Add screenshots, test evidence, final documentation, and the public Google Drive demo-video link before submission.
