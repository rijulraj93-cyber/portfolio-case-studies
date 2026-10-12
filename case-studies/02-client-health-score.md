# 02 - Client Health-Score Tracker

## Problem

When one person manages many client relationships, deciding who needs a follow-up can depend too much on memory. A lightweight prioritization view can make the next check-in easier to plan.

## Approach

The interactive sample uses engagement and days since last contact to calculate a simple score:

```text
score = max(0, round(engagement * 0.6 - days_since_contact * 1.2))
```

It labels scores above 50 as healthy, above 25 as watch, and the remainder as at risk.

## Current Scope and Limitation

The current calculator is a heuristic demonstration, not a validated client-risk model. The portfolio description mentions spend trend, but the current interactive sample does not include that input. The weights and thresholds have not been validated against outcomes.

## Evaluation Ideas

Compare the score with relationship-manager assessments, track follow-up completion, and check whether the score improves prioritization without displacing professional judgment. No client data or measured results are included.