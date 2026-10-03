# EventForce-Management-System# Event Management System

## Project Overview

The Event Management System is a Salesforce-based CRM application developed to manage events and their related activities in a centralized and efficient manner.

The system manages Events, Organizers, Attendees, Registrations, Vendors, and Payments. Salesforce automation, Apex and Lightning Web Components are used to reduce manual work and improve the overall event management process.

## Objectives

- Manage events and event-related information in a centralized system.
- Manage organizers and attendees.
- Manage attendee registrations and ticket types.
- Manage vendors and vendor services.
- Track event-related payments.
- Automate business processes using Salesforce Flow.
- Implement custom business logic using Apex.
- Provide interactive functionality using Lightning Web Components.
- Generate reports and dashboards for event analysis.
- Maintain data accuracy and security.

## Technologies Used

- Salesforce Lightning Platform
- Salesforce Custom Objects
- Salesforce Flow
- Apex
- Apex Trigger
- Batch Apex
- Scheduled Apex
- Lightning Web Components (LWC)
- Salesforce Reports
- Salesforce Dashboards
- Data Import Wizard

## Data Model

### Standard Objects
- Account – Organizer Company
- Contact – Attendee

### Custom Objects
- Event
- Registration
- Vendor
- Event Vendor
- Payment

### Relationships

- Account → Event
- Event → Registration
- Contact → Registration
- Event ↔ Vendor through Event Vendor
- Registration → Payment

## Automation

The project uses Salesforce Flow for:

- Creating and managing events.
- Registering attendees.
- Automatically updating registration status.
- Updating registration status based on payment.
- Marking completed events.
- Sending event reminder notifications.

## Apex Implementation

The project includes:

- **Registration Trigger** – prevents duplicate registrations.
- **Batch Apex** – generates event summary information.
- **Scheduled Apex** – automates event reminder processing.

## Lightning Web Components

The project includes the following LWC components:

- Event Dashboard
- Registration Component
- Vendor Management Component

These components provide an interactive interface for managing event-related information.

## Reports and Dashboard

The following reports were created:

- Events by Type
- Attendees per Event
- Revenue Report
- Vendor Cost Report

The Event Management Dashboard provides information about:

- Total Events
- Total Revenue
- Active Events
- Registration Trends

## Project Features

- Event Management
- Organizer Management
- Attendee Registration
- Vendor Management
- Payment Tracking
- Business Process Automation
- Apex-based Business Logic
- Interactive LWC Components
- Reports and Dashboards
- Data Validation and Security

## Project Screenshots

Screenshots of the working Salesforce application, including objects, flows, Apex, LWC components, reports and dashboard, are included in the project documentation.

## Learning Outcomes

Through this project, I gained practical experience in Salesforce administration and development, including data modelling, automation, Apex programming, Lightning Web Components, reporting and dashboard creation.

The project also improved my problem-solving, debugging, documentation and project management skills.

## Future Scope

The system can be further enhanced by integrating:

- Online payment gateways
- Email and SMS notifications
- QR-code based event tickets
- Digital event check-in
- Mobile application support
- Advanced analytics
- External services such as Google Calendar and Maps
- AI-based event recommendations

## Project Type

Team Salesforce Project

## Developed By

**BharathBalaji H**
**Chandrasekaran N**
**Someshwar G**

## Platform

**Salesforce**
