# Sales Performance CRM

End-to-end Sales CRM and analytics solution built with Power Platform.

## Overview

This project simulates a complete B2B sales lifecycle management system built using:

- Power Apps (Canvas App)
- Dataverse
- Power BI

The solution covers the entire sales process:

Lead → Qualification → Opportunity → Quote → Order

---

## Business Problem

Organizations often struggle with:

- tracking lead conversion
- managing sales pipeline visibility
- monitoring opportunity progress
- analyzing sales performance
- connecting operational CRM data with analytics

This solution provides a centralized sales workflow and executive reporting layer.

---

## Solution Architecture

### Operational Layer
- Canvas App for sales operations
- Dataverse as the central data platform

### Analytics Layer
- Power BI executive dashboard
- pipeline analytics
- conversion tracking
- revenue monitoring
  
## Architecture Diagram
![Architecture](diagrams/architecture-diagram.png)
---

## Core Features

### Lead Management
- Lead creation
- qualification/disqualification
- account and contact assignment

### Opportunity Management
- opportunity lifecycle tracking
- stage management
- salesperson ownership
- activity tracking

### Quote Management
- multiple quotes per opportunity
- quote approval process
- approved quote validation

### Order Management
- order creation from approved quote
- automated business flow transition

### Power BI Analytics
- sales conversion funnel
- revenue tracking
- salesperson performance
- lead source analysis
- pipeline monitoring

---

## Business Process

Lead → Evaluated Lead → Opportunity → Quote → Approved Quote → Won Deal → Order

## Business Process Diagram

![Business Process](diagrams/business-process-diagram.png)
---

## Data Model

Main entities:

- Account
- Contact
- Lead
- Opportunity
- Activity
- Quote
- Order
- Salesperson
  
## Data Model Diagram

![Data Model](diagrams/model_diagram.png)

---

## Project Structure

```text
docs/               → project documentation
screenshots/        → application and dashboard screenshots
diagrams/           → architecture and process diagrams
power-apps/         → exported Power Apps solution
power-bi/           → Power BI dashboard files
```

---

## Technologies

- Power Apps Canvas
- Dataverse
- Power BI
- Power Fx
- DAX

---

## Screenshots

### Power Apps
*(to be added)*

### Power BI Dashboard
*(to be added)*

---

## Future Improvements

- Power Automate integration
- role-based security
- forecasting analytics
- SLA monitoring
- AI lead scoring
