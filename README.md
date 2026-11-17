# Planner Analytics Dashboard

### Microsoft Planner | Power BI | Dataverse | Power Automate

## Overview

A task and project analytics solution developed as part of a Data Science internship.

The solution transforms Microsoft Planner task data into interactive Power BI dashboards, helping users monitor project progress, task completion, workload distribution, priorities, and overdue tasks.

## Technologies Used

- Microsoft Power BI — Data visualization and reporting
- Microsoft Dataverse — Structured data storage
- Power Automate — Automated task synchronization
- Microsoft Planner — Task and project management
- DAX — KPI calculations and analytical measures
- Power Query — Data transformation

## System Architecture

The solution supports two data integration approaches:

**Basic Planner**

Microsoft Planner → Power Automate → Custom Dataverse Table → Power BI

**Premium Planner**

Microsoft Planner Premium → Native Dataverse Tables → Power BI

## Dashboard Features

- Total, completed, in-progress, and not-started task counts
- Task completion percentage
- Overdue and upcoming task monitoring
- Progress comparison across projects
- Task distribution by priority
- Workload analysis by assignee
- Interactive filtering by project, task status, and priority
- Detailed project and task views

## Technical Highlights

- Implemented task synchronization using Power Automate for Basic Planner plans.
- Used task identifiers to update existing records and prevent duplicates.
- Connected Power BI to Microsoft Dataverse.
- Built data relationships and analytical calculations for project reporting.
- Designed interactive dashboards with KPI cards, charts, slicers, and task-level tables.

## Project Screenshots

Dashboard screenshots will be added here.

## Notes

This repository presents the technical approach and dashboard design developed during an internship. Internal organizational data, credentials, and configuration details are excluded.
