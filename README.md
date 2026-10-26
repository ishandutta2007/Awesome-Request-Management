# Awesome-Request-Management

# Top Request Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Service Request Fulfillment, Approval Workflows & Self-Service Portals*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Request Management**. These tools enable organizations to standardize how employees and customers submit, approve, and fulfill service requests—from IT equipment and access provisioning to facilities, HR, and business services—through structured catalogs, automated workflows, and clear SLA tracking.

**Examples** include ServiceNow Request Management, Jira Service Management, Freshservice, BMC Helix Remedyforce, ManageEngine ServiceDesk Plus, SolarWinds Service Desk, Ivanti Neurons, SysAid, HaloITSM, and TOPdesk (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted ticketing and request fulfillment—ideal for organizations building sovereign request management infrastructure without per-agent licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Request Management](https://www.servicenow.com/)**  
  Enterprise request fulfillment built on the Now Platform with a comprehensive service catalog, dynamic forms, automated approval workflows (recommending RITM-level approvals for granularity), knowledge base integration for self-service deflection, and reporting on request volume, approval time, and fulfillment time .

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  Request types map to underlying issue types with customizable fields, customer-friendly workflow status names, request groups for portal navigation (recommended at 7+ request types), and access restrictions per request type; integrates with Slack and Teams for conversational ticketing .

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  Service catalog with structured portals for workspace requests, workflow automations for auto-assignment and reminders, SLA management based on priority, business rules for dynamic form behavior, and analytics tracking request volumes and resolution times .

- **[BMC Helix Remedyforce](https://www.bmc.com/)**  
  Service request management with Service Request Definitions, Request Detail Templates, configurable approval processes, and a self-service portal with Salesforce knowledge article integration .

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  
  Self-service portal for ticket submission and status tracking, email-to-ticket conversion, business rules for automatic assignment of priority and technician, SLA definition with violation notifications, and API integration for third-party systems .

- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  
  Incident and service request management with categories/subcategories for routing and reporting, groups and queues for triage, and SLA rules for response and resolution targets .

- **[Ivanti Neurons for ITSM](https://www.ivanti.com/)**  
  Request offerings with advanced features including external request offerings, request cancellation, and customizable form behavior for Self Service users in the portal V3 .

- **[SysAid](https://www.sysaid.com/)**  
  AI-powered request management with Copilot chatbot for one-click submissions, intelligent categorization, dynamic forms by request category, automated approval workflows, SLA timers with escalations, and a ticket journey view for full lifecycle visibility .

- **[HaloITSM](https://www.haloitsm.com/)**  
  ITIL-aligned request types with default values (category, priority, SLA, mailbox) configured before creation, smart escalation of request types to problem management, and full activity traceability for audit purposes .

- **[TOPdesk](https://www.topdesk.com/)**  
  Self-service portal with form designer, AI-suggested categories and priorities, knowledge suggestions while typing, order management for self-service requests, and status tracking visible to requesters without needing to call .

## Open-Source GitHub Projects

- **[iTop](https://github.com/Combodo/iTop)**  
  Complete open-source ITIL-aligned ITSM platform with request fulfillment through service catalog, configurable SLA management, approval workflows, and CMDB integration for impact-aware fulfillment; AGPL-3.0 licensed with REST API for automation.

- **[heidsoft ITSM](https://github.com/heidsoft/itsm)**  
  AI-native open-source ITSM platform (Apache-2.0) covering tickets, service catalog, SLA, knowledge, CMDB, and BPMN orchestration; AI embedded into triage, summarization, and workflow recommendations; Docker-deployable with SSO and RBAC.

- **[Znuny](https://github.com/znuny/Znuny)**  
  Open-source ITSM and helpdesk platform (OTRS fork) with service catalog, SLA tracking, escalation handling, and customer portal for request submission; GPL-3.0 licensed and actively maintained.

- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**  
  100% open-source ticket management with customizable ticket types and forms, knowledge base integration, SLA rules, and auto-assignment; built on Frappe Framework and Docker-deployable.

- **[HiveMind](https://github.com/topics/request-management)**  
  Open-source project management and ERP application for services organizations (Groovy/Moqui Framework) featuring request tracking, task management, time tracking, and invoicing within a unified business operations platform .

- **[Self-hosted AI-assisted ticketing](https://github.com/topics/request-management)**  
  Open-source TypeScript-based ticketing and request management for organizations with multi-department strict isolation, bring-your-own-AI support (Claude, Copilot, local models via Ollama), semantic knowledge base, and full English/German UI .

### Additional Strong Open-Source Options

- **osTicket** — Widely used open-source support ticket system with help topics and custom forms functioning as a lightweight request catalog for smaller teams.
- **Helpy** — Open-source customer support platform with knowledge base and community forums for self-service request entry.
- **Faveo Helpdesk** — Open-source helpdesk with SLA management and workflow automation for multi-channel request handling.

**Frameworks for building custom systems**: Combine **iTop** for ITIL-aligned request fulfillment with CMDB integration, **heidsoft ITSM** for AI-assisted triage and BPMN workflows, **Znuny** for ticket-based request handling with SLA escalation, and **Frappe Helpdesk** for a modern, Docker-deployable request management foundation in a self-hosted stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Request management platforms handling employee and customer data must comply with applicable privacy regulations and organizational access policies.
- Self-hosted open-source solutions require proper security hardening, approval workflow customization, and CMDB data quality for effective fulfillment routing.
- Verify license terms for commercial use; iTop uses AGPL-3.0, heidsoft ITSM uses Apache-2.0, Znuny uses GPL-3.0, and Frappe Helpdesk is open-source.

---

**Made for IT service managers, help desk administrators, and employee experience teams.**  
Let's make request management more open, streamlined, and fulfillment-ready.
