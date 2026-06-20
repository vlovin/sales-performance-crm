# Sales Performance CRM

Sales CRM solution built with Microsoft Power Platform.

---

## Overview

This project demonstrates a complete sales management process built using:

- Power Apps (Canvas App)
- Dataverse
- Power BI

The solution follows the full sales lifecycle:

Lead → Qualification → Opportunity → Quote → Order

It combines operational CRM processes with reporting and analytics to support sales pipeline management and performance monitoring.

---

## Project Objectives

The goal of this project was to design and build a sales management solution using Microsoft Power Platform.

The solution demonstrates:

- business process design
- Dataverse data modeling
- Power Apps application development
- Power BI reporting and analytics
- end-to-end sales process management

---

## Business Problem

Organizations often struggle with:

- tracking lead conversion
- managing sales pipeline visibility
- monitoring opportunity progress
- analyzing sales performance
- connecting operational CRM data with analytics

This solution provides a centralized sales workflow supported by reporting and performance dashboards.

---

## Solution Architecture

### Operational Layer

- Power Apps Canvas App
- Dataverse relational data model

### Analytics Layer

- Power BI dashboard
- pipeline reporting
- conversion tracking
- revenue analysis
- salesperson performance monitoring

---

## Architecture Diagram

![Architecture](diagrams/architecture-diagram.png)

---

## Core Features

### Lead Management

- lead creation
- qualification and disqualification process
- account assignment
- salesperson ownership

### Opportunity Management

- opportunity lifecycle management
- sales stage tracking
- activity management
- revenue and probability tracking

### Quote Management

- multiple quotes per opportunity
- quote approval process
- approved quote tracking

### Order Management

- order creation from approved quotes
- order status tracking
- sales process completion

### Power BI Analytics

- sales funnel reporting
- revenue analysis
- salesperson performance
- lead source analysis
- pipeline monitoring
- KPI reporting

---

## Business Process

The CRM workflow follows a structured B2B sales process:

Lead → Evaluation → Qualification → Opportunity → Quote → Negotiation → Won Deal → Order

---

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

The entities are connected through Dataverse relationships to support the complete sales process.

---

## Data Model Diagram

![Data Model](diagrams/model_diagram.png)

---

## Power Apps Screenshots

### Lead Management

The Lead module supports lead registration, qualification and assignment.

![Lead Screen](screenshots/canvas/lead-screen.png)

---

### Opportunity Management

The Opportunity module supports:

- opportunity management
- activity tracking
- quote management
- deal closure

![Opportunity Screen](screenshots/canvas/opportunity-screen.png)

---

### Order Management

The Order module represents the final stage of the sales process after quote approval and opportunity closure.

![Order Screen](screenshots/canvas/order-screen.png)

---

## Power Apps Solution Export

The exported Power Apps solution is available in the `power-apps/` folder.

The package contains:

- Canvas App
- Dataverse tables
- relationships
- choice columns
- application logic

> Note: The solution is exported as an unmanaged solution for portfolio and development purposes.

---

## Power BI Dashboard

The Power BI reporting layer provides visibility into:

- lead conversion
- sales funnel performance
- revenue trends
- salesperson performance
- pipeline health

### Dashboard Preview

![Power BI Dashboard](screenshots/powerbi/sales-dashboard.png)

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

## Future Improvements

- Power Automate approval workflows
- role-based security
- SLA monitoring
- forecasting dashboard
- advanced sales KPIs
