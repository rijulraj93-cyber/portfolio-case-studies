# 01 - Escalation Triage Assistant

## Problem

In support work, the first delay can be deciding how urgent a message is and what to say next. Important urgency signals can sit in a queue while an agent works out the first response.

## Approach

The demo checks a customer message for a small, explicit list of urgency terms. When it finds a match, it labels the message high priority and suggests a first-response opener. Otherwise it returns a standard-priority response.

## Current Scope

- Runs in the browser without a server or external AI service.
- Uses keyword matching, not language understanding or sentiment analysis.
- Displays a suggested response for a person to review and edit.

## Evaluation Ideas

Measure agreement with human urgency labels, missed urgent cases, time to first response, and how often agents edit the suggested opener. The prototype has no measured results.