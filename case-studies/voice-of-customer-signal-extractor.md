# 03 - Voice-of-Customer Signal Extractor

## Problem

Feedback can be spread across support notes, reviews, and conversations. Teams need a quick way to see repeated topics before deciding what deserves deeper investigation.

## Approach

The demo accepts one feedback item per line, normalizes words, removes a short stop-word list, and ranks the most frequent terms. It shows example lines so the reader can inspect the source feedback.

## Current Scope

- Uses simple word-frequency counting in the browser.
- Counts a word at most once per feedback line.
- Does not perform sentiment analysis, semantic clustering, or AI summarization.
- The output is a starting signal for human review, not a conclusion about customer intent.

## Evaluation Ideas

Compare extracted themes with human-coded feedback, check for missed themes and misleading frequency counts, and measure the time required to reach a useful review. No evaluation results are available.