---
name: last30days-hermes
description: Find market opportunities from recent user pain signals in public discussions.
metadata:
  owner: existsport
  hermes:
    tags:
      - market-research
      - trend-detection
      - opportunity-mapping
---

# Last 30 Days Market Scan

## Purpose
Use recent public discussions to identify repeated user pain points and convert them into concrete opportunity hypotheses.

## Required Input
- `topic`: product or problem space to analyze
- `audience`: who experiences the problem
- `region`: optional geography filter
- `competitors`: optional list of products or brands

## Workflow
1. Define 8-15 search queries around complaints, failures, requests, and workaround behavior.
2. Gather evidence from the last 30 days from public sources such as Reddit, X, forums, and review communities.
3. Group evidence into pain clusters by repeated issue type.
4. Score each cluster on frequency, urgency, and purchase intent.
5. Generate 3-5 opportunity candidates with a clear user, problem, and solution direction.

## Output Format
Return a compact report with these sections:
- `Top Pain Clusters`: 3-7 clusters with short evidence summaries
- `Opportunity Candidates`: ranked ideas with target user and reason
- `Validation Tasks`: small next actions to confirm demand
- `Risk Notes`: key uncertainty and what data is still missing

## Quality Rules
- Prefer direct, recent evidence over generic trend language.
- Include source links or source labels for every major claim.
- Mark low-confidence conclusions explicitly.
- If evidence is insufficient, state that and request narrower input.
