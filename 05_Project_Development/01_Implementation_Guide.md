# Phase 5 – Project Development

## Milestone 1 – Create the Flow

### Step 1
Open ServiceNow.

### Step 2
Go to **All** and search for **Flow Designer**.

### Step 3
Open **Flow Designer** under Process Automation.

### Step 4
Click **New → Flow**.

### Step 5
Set:
- Flow Name: `Standard laptop task`
- Application: `Global`
- Run user: `System user`

Click Submit.

### Step 6
Click **Add a trigger**.

### Step 7
Search for and select **Service Catalog**.

Click Done.

### Step 8
Under Actions, click **Add an action**.

### Step 9
Search for **Create Catalog Task** and select it.

### Step 10 – Configure Action
- Action: Create Catalog Task
- Request item: drag/drop Requested Item Record
- Table: Catalog Task (auto populated)
- Short description: `Laptop need to Configured`
- Description: `Laptop need to Configured`
- Assignment group: `Hardware`
- Approval: `Approved`

Leave other fields at default.

### Step 11
Click Done.

### Step 12
Save the flow and Activate it.

---

# Milestone 2 – Assign Flow to Standard Laptop

1. Open ServiceNow.
2. All → search **Maintain Items**.
3. Select Maintain Items.
4. Search for **Standard Laptop** under Name.
5. Open the record.
6. Select **Process Engine**.
7. Remove the remaining automations.
8. Add the flow named **Standard Laptop Task**.
9. Save the record.

---

# Milestone 3 – Place and Approve the Request

1. All → search **Service Catalog**.
2. Open Service Catalog → Hardware.
3. Select **Standard Laptop**.
4. Click **Order Now**.
5. Open the Order Status.
6. Click the Request Number.
7. Open the Requested record.
8. Scroll to Approvers.
9. Approve the request.
10. Open Requested Item.
11. Scroll to Catalog Tasks.
12. Open the Catalog Task.
13. Verify the updated status, short description and assignment group.

## Implementation Evidence
Store screenshots in:
`assets/screenshots/`

Recommended screenshot names:
- `01_flow_properties.png`
- `02_service_catalog_trigger.png`
- `03_create_catalog_task.png`
- `04_field_mapping.png`
- `05_flow_activated.png`
- `06_process_engine.png`
- `07_standard_laptop_order.png`
- `08_approval.png`
- `09_requested_item.png`
- `10_catalog_task_result.png`
