# project-task-tracker

Professional Excel-based Project Task Tracker built for government ICT project delivery in Malaysia. Designed to reflect real tracking standards used by Project Coordinators and PMO teams managing Waterfall SDLC deliveries across government and enterprise programmes.

All sample data is fictional and constructed for portfolio purposes.

---

## Overview

| Field | Details |
|-------|---------|
| Template Type | Project Task Tracker |
| Format | Microsoft Excel (.xlsx) |
| Sheets | 2 (Task Tracker, Instructions) |
| Total Task Rows | 50 (39 pre-filled sample tasks, 11 blank) |
| Target Roles | Project Coordinator, PMO Analyst, Project Executive |
| Context | Government ICT project delivery, Malaysia |

---

## What Is Included

### Sheet 1 — Task Tracker

| Section | Description |
|---------|-------------|
| Document Control | Project name, PM, document ID, version, last updated |
| Task Summary (KPI Cards) | Auto-calculated totals for all status types, % done, and high priority count |
| Task List | 39 pre-filled sample tasks across 5 project phases with full tracking columns |

### Column Structure

| Column | Field | Description |
|--------|-------|-------------|
| B | Task ID | Sequential ID (T-001, T-002) for cross-referencing across project documents |
| C | WBS | Work Breakdown Structure code tied to approved project scope (e.g. 1.1, 2.3) |
| D | Phase / Workstream | Project phase grouping for filtering and phase-level progress tracking |
| E | Task Name | Full task description |
| F | Assigned To | Named individual responsible for task completion |
| G | Priority | HIGH / MEDIUM / LOW — colour coded |
| H | Status | COMPLETE / IN PROGRESS / NOT STARTED / ON HOLD / OVERDUE — colour coded |
| I | Planned Start | Baseline start date from approved MS Project schedule |
| J | Planned End | Baseline end date — do not change once set |
| K | Actual Start | Filled when task begins |
| L | Actual End | Filled when task is completed |
| M | % Complete | Task completion percentage — feeds KPI cards automatically |
| N | Dependencies | Task ID of predecessor task (mirrors MS Project predecessor logic) |
| O | Deliverable / Output | Formal document or artefact produced on task completion |
| P | Remarks | Brief notes on delays, blockers, decisions, or escalations |

### KPI Summary Cards (Auto-Calculated)

| Card | Description |
|------|-------------|
| Total Tasks | Count of all tasks with a task name entered |
| Complete | Count of tasks with status COMPLETE |
| In Progress | Count of tasks with status IN PROGRESS |
| Not Started | Count of tasks with status NOT STARTED |
| On Hold | Count of tasks with status ON HOLD |
| % Done | Overall completion rate across all tasks |
| High Priority | Count of tasks with priority HIGH |

### Sheet 2 — Instructions

Step-by-step guidance on how to complete every column correctly. Includes full status and priority legend with colour coding.

---

## Sample Tasks Included

39 pre-filled tasks across all 5 project phases mapped to a government ICT system rollout.

| Phase | Tasks |
|-------|-------|
| Phase 1 — Initiation | T-001 to T-005 |
| Phase 2 — Planning | T-006 to T-010 |
| Phase 3 — Development | T-011 to T-025 |
| Phase 4 — Testing | T-026 to T-033 |
| Phase 5 — Close-Out | T-034 to T-039 |

---

## Status Reference

| Status | Meaning |
|--------|---------|
| COMPLETE | Task finished and verified. Actual end date recorded. |
| IN PROGRESS | Task actively being worked on. |
| NOT STARTED | Task not yet begun. |
| ON HOLD | Task paused. Reason noted in Remarks. Escalate if hold exceeds 1 week. |
| OVERDUE | Planned end date passed. Task not complete. Requires immediate escalation. |

---

## Priority Reference

| Priority | Meaning |
|----------|---------|
| HIGH | Directly impacts milestone or critical path. Must complete on time. |
| MEDIUM | Important but has scheduling flexibility. |
| LOW | Can be deferred if higher priority tasks require attention. |

---

## How This Reflects Real PMO Practice

- WBS codes link each task to the approved project scope document, matching how Malaysian government ICT contracts structure deliverable accountability
- Deliverable column ties every task to a named formal output, reflecting audit trail requirements on government project deliveries
- Task IDs mirror the predecessor referencing used in MS Project, making this tracker a direct companion to the MS Project schedule in this portfolio
- Planned vs Actual date columns support baseline variance tracking required in monthly progress reports submitted to government clients
- Status and priority colour coding follows RAG conventions used across Malaysian government ICT programmes
- Document control with version and document ID meets ISO-aligned document management requirements common among Malaysian government vendors

---

## Files Included

| File | Description |
|------|-------------|
| `Project_Task_Tracker.xlsx` | Full Excel task tracker with sample data and instructions |
| `README.md` | Repository documentation |

---

## Skills Demonstrated

`Microsoft Excel` `Project Task Tracking` `WBS Coding` `Milestone Tracking` `Baseline vs Actual Tracking` `PMO Reporting` `Document Control` `Government ICT Delivery` `RAG Status Reporting` `Deliverable Management`

---

*Built by Muhammad Muqris bin Shazly — Project Coordinator and PMO Support*
*[github.com/muhammadmuqris14](https://github.com/muhammadmuqris14)*
