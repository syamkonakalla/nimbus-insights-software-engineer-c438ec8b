# Nimbus Insights — Software Engineer Workspace

> **CareerSim workspace** | TestUser | Software Engineer

## About Nimbus Insights
⚡️HivisionIDPhotos: a lightweight and efficient AI ID photos tools. 一个轻量级的AI证件照制作算法。

## Current Sprint
**Implementation of a configurable, user‑defined alerting engine for KPI anomalies**

Custom alerts are a premium feature requested by several enterprise clients; launching it this quarter will unlock a new $2M ARR upsell tier and improve churn metrics by reducing blind spots in customer monitoring.

## Project State
**What's built:** The core ingestion pipeline built on Python FastAPI is live, ingesting events via a REST endpoint and persisting them to a ClickHouse warehouse. Existing dashboards display pre‑defined metrics with basic threshold alerts, and the CI/CD pipeline on GitHub Actions is fully automated with unit and integration tests.

**In progress:** (no specific gaps identified — treat as a stable, well-maintained codebase)

**Known issues:** (no specific gaps identified — treat as a stable, well-maintained codebase)

## Your Mission
Own the end‑to‑end development of the custom alerting engine: design the FastAPI endpoints, implement the Celery task workflow, persist rule configurations, and integrate Slack notifications, ensuring test coverage and performance benchmarks.

## Team
| Name | Role |
|------|------|
| Alex Mercer | Engineering Manager |
| Rohan Verma | Lead Software Engineer |
| Emily Chen  | Data Analyst |
| David Park  | DevOps |
| **TestUser** | **Software Engineer (You — inheriting from previous engineer)** |

## Tech Stack
- Python
- FastAPI

## Workflow
1. Check email for Jira ticket notifications
2. Create branch: `git checkout -b TASK-XXX/short-description`
3. Push code → open PR → tag Alex for review
4. Daily standup at 10am in CareerSim chat

---
*CareerSim workspace · GitHub Issues = your Jira board*
