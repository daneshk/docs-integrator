---
sidebar_position: 1
sidebar_label: Overview
title: Integration Artifacts
description: "Understand the different types of integration artifacts: automations, services, file handlers, AI agents, and more."
---

# Integration artifacts

Integration artifacts are the building blocks of your integrations. Each artifact type serves a specific purpose — running scheduled tasks, exposing an endpoint, processing files, or orchestrating AI workflows. Understanding these types helps you choose the right approach for each scenario.

## Artifact types

WSO2 Integrator organizes artifacts into four primary categories:

| Category | Purpose | Trigger |
|---|---|---|
| **Automation** | Sync data, generate reports, run routine jobs | Timer/schedule or manual |
| **Integration as API** | Expose integrations as REST, GraphQL, or TCP endpoints | Incoming HTTP/GraphQL/TCP requests |
| **File Integration** | Batch processing, scheduled file handling | Files arriving in a folder or FTP/SFTP server |
| **AI Agent** | Intelligent workflows with LLM reasoning and tool use | Incoming request or scheduled trigger |
| **Event Integration** | React to messages and events from external systems | Kafka, RabbitMQ, MQTT, Salesforce, GitHub, and more |


## Creating artifacts

You can create artifacts in two ways:

### Visual designer

1. Open the WSO2 Integrator sidebar in VS Code.
2. Click the **+** button next to the artifact category.
3. Select the artifact type and configure its properties.


## Artifact lifecycle

Every artifact follows the same lifecycle:

1. **Create** — define the artifact using the visual designer or code
2. **Configure** — set connection details, parameters, and behavior
3. **Implement** — add the integration logic using the flow designer or pro-code
4. **Test** — validate with Try-It, unit tests, or mocks
5. **Deploy** — package and deploy to a runtime environment

## What's next

- [HTTP service](service/http-service.md) — build REST APIs and HTTP services
- [Automation](automation/automation.md) — create scheduled and manual automations
- [AI agent](/docs/develop/design-logic/overview) — orchestrate LLM-powered workflows
- [Design logic](/docs/develop/design-logic/overview) — build the logic inside your artifacts
