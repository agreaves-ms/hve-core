---
title: Agents
description: Reference documentation for HVE Core agents.
sidebar_position: 0
author: Microsoft
ms.date: 2026-09-21
ms.topic: overview
keywords:
  - reference
  - agents
---

<!-- BEGIN AUTO-GENERATED: index -->
This page lists the generated reference documentation for HVE Core agents.

| Asset                                                            | Description                                                                                                                                                                                                                                                                                                                                               |
|------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [RPI Agent](hve-core/rpi-agent.md)                               | User-selected RPI workflow wrapper for Research, Plan, Implement, Review, and Follow-up. Use when one task needs lifecycle coordination.                                                                                                                                                                                                                  |
| [HVE Builder Reviewer](hve-core/subagents/hve-builder-review.md) | Reviews one prompt, instruction, agent, subagent, or skill candidate in fresh context against the hve-builder requirements catalog and review rubric, and returns severity-graded findings with the smallest resolving change as suggestions for the calling agent to verify. Use during an hve-builder review pass when isolating the review would help. |
| [RPI Researcher](hve-core/subagents/rpi-researcher.md)           | Gathers candidate sources for one bounded research question and returns source pointers, exact locations, contract excerpts, and brief relevance notes as suggestions for the calling agent to verify. Use during research when isolating source gathering would help.                                                                                    |
| [RPI Reviewer](hve-core/subagents/rpi-reviewer.md)               | Reviews one bounded, context-heavy portion of RPI evidence assigned by the review parent and returns findings with evidence locations, why each matters, and suggested severity and route as suggestions for the calling agent to verify. Use during review when isolating a large comparison would help.                                                 |
<!-- END AUTO-GENERATED: index -->
