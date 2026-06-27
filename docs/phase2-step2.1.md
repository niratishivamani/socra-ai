# Phase 2.1 - Understanding Splunk REST API

## Objective

Understand how SOCRA AI communicates with Splunk using the Splunk REST API.

## Authentication

SOCRA AI authenticates using:

- Host
- Port
- Username
- Password

## Search Jobs

SOCRA AI sends a search query to Splunk.

Example:

```spl
index=* | head 5
```

Splunk executes the search and creates a search job.

## Results API

After the search is complete, Splunk returns the results in JSON format.

## Workflow

SOCRA AI
↓
Authentication
↓
Search Query
↓
Search Results
↓
JSON Response
