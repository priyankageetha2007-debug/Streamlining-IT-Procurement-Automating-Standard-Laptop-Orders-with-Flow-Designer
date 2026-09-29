# Phase 3 – Project Design

## Architecture

```text
+---------------------+
| User / Requester    |
+----------+----------+
           |
           v
+---------------------+
| Service Catalog     |
| Standard Laptop     |
+----------+----------+
           |
           v
+---------------------+
| Approval            |
| Approved            |
+----------+----------+
           |
           v
+---------------------+
| Flow Designer       |
| Standard laptop task|
+----------+----------+
           |
           v
+---------------------+
| Create Catalog Task |
+----------+----------+
           |
           v
+---------------------+
| Hardware Group      |
| Laptop Configuration|
+---------------------+
```

## Flow Design

### Flow Properties
- Name: Standard laptop task
- Application: Global
- Run user: System user

### Trigger
Service Catalog

### Action
Create Catalog Task

### Action Mapping
- Request item ← Requested Item Record
- Short description = Laptop need to Configured
- Description = Laptop need to Configured
- Assignment group = Hardware
- Approval = Approved

## Catalog Item Integration
The Standard Laptop service catalog item should use the created flow in its Process Engine configuration, after removing the remaining automations as instructed in the source document.

## Design Principle
The flow should create the configuration task only in the approved service-request path.
