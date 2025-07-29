# AI/ML Engineer Take-Home Case Study: Email Categorisation System (POC)

## Background

Our finance teams manage shared inboxes that receive a large volume of financial communications daily. Currently, these emails are manually reviewed and categorised—a time-consuming and error-prone process.

We are exploring whether an automated email categorisation system can streamline this process, and whether it's technically feasible to implement such a solution at scale.

## Objective

This is a technical spike (proof of concept) to evaluate the feasibility of automating email classification using AI/ML techniques.

You are not expected to build a production system, rather, we're looking for a thoughtful, experimental prototype, along with an analysis of different approaches.

## Key Requirements

### Business Context

- **SaaS Platform:** Multi-tenant architecture serving 100+ clients  
- **Scale:** 1,000+ emails per day per client  
- **Accuracy Target:** 85%+ classification accuracy  
- **Customisation:** Different clients may need custom categories  
- **Privacy:** Financial emails contain sensitive information  

### Technical Constraints

- Must handle variations in email formats and languages (primarily English)  
- Need confidence scoring for uncertain classifications  
- System should support adding new categories without complete retraining  
- Consider cost implications for SaaS pricing model  

## Core Categories

Your model should be able to classify emails into the following primary categories:

- **Payment Reminders** – Overdue payment alerts, payment deadline notices  
- **Internal Requests** – Expense approvals, internal financial queries  
- **Payment Confirmations** – Payment success notifications, receipts  
- **Invoices** – Bills, vendor invoices, service charges  
- **System Notifications** – Automated alerts, software/system messages  
- **Others** – Anything that doesn't fit the above categories  

**Note:** Different teams may use slightly different definitions or subcategories. Your approach should allow for flexibility or customisation.

## Sample Data

You can use any combination of the following data sources:

- Provided examples (see below)  
- Synthetic email data  
- Public datasets  
- Your own simulated examples  

We suggest working with 100–300 emails to keep the task manageable while still meaningful.

## Submission Requirements

Submit your analysis as a single PDF document. Include:

- Your technical feasibility report and brief cover note with your overall recommendation  
- Code or notebook with your prototype  
