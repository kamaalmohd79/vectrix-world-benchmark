# Vectrix World Benchmark

This repository contains the completed benchmark test task. 

The dataset simulates a small but realistic internal workspace environment including Slack conversations, email threads, project management issues, documents, calendar events, and Q&A examples.

The goal is to represent structured information across different tools and formats using JSON schemas and MDX documentation.

---

## Repository Structure

### 1. Linear Project

Contains a simulated Linear project with issues and related metadata.

**Files**

- `linear-project-5-issues-schema.json` — Structured schema representing a Linear project with 5 issues.
- `overview.mdx` — Overview and explanation of the project data.

**Details**

- Project: **VEC-MERIDIAN**
- 5 issues
- Mixed priorities (Urgent, High)
- Various statuses (Todo, In Progress, Done)
- 11 comments distributed across issues

---

### 2. Email Threads

Simulated email conversations representing both internal and external communication.

**Files**

- `thread-1-internal-schema.json` — Internal thread discussing SSO / Meridian requirements.
- `thread-2-external-schema.json` — External email thread with Rachel Simmons regarding a security questionnaire.
- `overview.mdx` — Explanation of the email dataset.

**Details**

- 2 email threads
- 6 total messages
- Internal and external communication examples

---

### 3. Google Drive Documents

Contains internal documentation similar to what might exist in a real workspace.

**Files**

- `document-1-product-brief.mdx` — Meridian product brief document.
- `document-2-sprint-review-meeting-notes.mdx` — Sprint 11 meeting notes with comments and discussion points.
- `overview.mdx` — Description of the documents.

**Details**

- Product planning document
- Meeting notes
- Includes inline comments and planted inconsistencies for evaluation scenarios

---

### 4. Google Calendar Events

Simulated calendar events representing common scheduling scenarios.

**Files**

- `3-google-calendar-events-schema.json` — Schema containing 3 calendar events.
- `overview.mdx` — Overview of the events.

**Details**

- All-day deadline event
- Recurring 1:1 meeting
- Sprint review meeting
- Includes declined attendee and updated meeting link

---

### 5. Q&A Pairs

Question and answer examples designed for benchmark evaluation.

**Files**

- `3-q&a-pairs-schema.json` — Contains structured Q&A pairs.
- `overview.mdx` — Description of the questions.

**Details**

- Exact lookup question
- Multi-document reasoning question
- Fictional information detection

---

### 6. Slack Messages

Simulated Slack conversation between team members.

**Files**

- `5-slack-messages-schema.json` — Schema containing 5 Slack messages.
- `overview.mdx` — Explanation of the Slack dataset.

**Details**

- Participants: Marcus, Liam, Jordan, Sofia
- Distinct message voices
- Threaded conversation
- File upload example
- Grafana dashboard link unfurl

---

## Summary

This benchmark dataset includes:

- **5 Slack messages**
- **2 email threads**
- **1 Linear project with 5 issues**
- **2 Google Drive documents**
- **3 Google Calendar events**
- **3 Q&A pairs**

The repository is structured to provide both **human-readable explanations (MDX)** and **machine-readable schemas (JSON)**.

---

## Repository

GitHub:  
https://github.com/kamaalmohd79/vectrix-world-benchmark
