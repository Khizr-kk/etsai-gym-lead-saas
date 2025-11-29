# Roadmap

## Week 1
- Set up core project architecture (frontend, backend, database).
- Implement user authentication and authorization.
- Integrate with WhatsApp Business API for receiving messages.
- Build a basic "Centralized Inbox" UI to display incoming WhatsApp messages.
- Develop backend logic for automated lead profile creation from new WhatsApp messages (name, contact, initial inquiry).
- Implement a basic Lead List UI displaying captured leads.
- Enable basic lead status tracking for `New` and `Contacted` on lead profiles.
- Implement functionality to send direct WhatsApp messages from the platform via the inbox UI.
- Deploy a functional, clickable demo environment.

## Weeks 2-4
### Lead Ingestion & Integration
- Integrate with Instagram Graph API for receiving DMs and creating lead profiles.
- Enhance lead profile creation to handle various message formats and update existing leads intelligently.
- Develop robust error handling and logging for API integrations.

### Lead Management & CRM
- Implement full lead status tracking: `New`, `Contacted`, `Follow-up`, `Converted`, `Lost`.
- Create a detailed "Lead Profile" view to edit and manage lead information (name, contact, source, inquiry history).
- Add ability to manually add leads.

### Communication Hub (Unified Messaging)
- Consolidate message sending interface for both WhatsApp and Instagram DMs.
- Display full conversation history for each lead within their profile.

### ML Lead Scoring Engine
- **(ML)** Develop an initial ML model to predict lead conversion probability (High, Medium, Low) based on lead source, initial inquiry text, and interaction history.
- Integrate ML model inference into the backend to assign scores to leads.
- Display lead scores prominently on the lead list and individual lead profiles.

### Dashboard & Analytics
- Build a simple dashboard showing key lead performance metrics: total leads captured, leads converted.
- Implement basic filtering and search for the lead list.

### Notification & Reminders
- Implement backend logic for automated follow-up reminders.
- Develop UI to set and view reminders for individual leads.

## Month 2-3
### Infrastructure & Stability
- Implement comprehensive monitoring (logs, errors, system health) and alerting.
- Conduct security audits and harden the platform (API key management, secure data storage, input validation).
- Optimize database queries and scale infrastructure for anticipated load.
- Set up robust backup and disaster recovery procedures.
- Enhance scalability of message processing and lead storage.

### User Experience & Polishing
- Refine overall UI/UX for intuitiveness and aesthetic appeal across all modules (inbox, lead profiles, dashboard).
- Develop a guided onboarding flow for users to connect their social media accounts.
- Implement user role management (e.g., admin, sales rep) if team functionality is desired.
- Conduct extensive end-to-end testing, performance testing, and user acceptance testing.
- Improve notification system for follow-up reminders.

### Analytics & Reporting
- Expand dashboard metrics to include conversion funnels, time to convert, and source performance.
- Implement basic reporting features, including the ability to export lead data.
- Visualize lead scoring distribution and impact on conversion rates.

### Compliance
- Ensure adherence to relevant data privacy regulations (e.g., GDPR, CCPA) for lead data handling.

## Task Backlog
- Customizable message templates for follow-ups and initial outreach.
- Integration with other lead sources (e.g., website forms, Facebook Lead Ads).
- Advanced analytics and reporting for marketing campaign performance.
- Calendar integration for booking trial sessions/appointments directly from the platform.
- Natural Language Processing (NLP) for advanced intent recognition from messages.
- Automated content generation suggestions for marketing responses.
- Implement a user feedback collection system.
- Further optimize application performance (frontend and backend).
- Improve accessibility standards across the user interface.
- Develop mobile-responsive design for key features.
- Advanced filtering, sorting, and bulk actions for lead management.
- Integration with popular CRM systems (e.g., Salesforce, HubSpot).