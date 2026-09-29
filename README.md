# Learning coding challenge

## Context

The Learning team works with a file of educational activities. Each activity
exists in several languages and goes through different states before being
published.

Before publishing content, several checks are currently done by hand.
We want to start automating them.

## Dataset

The file `data/activities.csv` contains a sample of activities. Each row is one
version of an activity in a specific language.

| Field | Description |
| --- | --- |
| `activity_id` | Identifier of the activity. |
| `grade` | Grade the activity is aimed at. |
| `language` | Language of the row. |
| `title` | Title of the activity. |
| `statement` | Statement the student sees. |
| `solution` | Solution of the activity. |
| `teacher_notes` | Notes for the teacher (optional). |
| `status` | State of the activity. |

## Task

Build a solution that lets us detect:

- activities that are missing a version in Catalan, Spanish or English;
- published activities without a solution;
- duplicate entries.

The result should make it easy for someone on the Learning team to identify
what needs to be reviewed.

## Rules

- You can use any tool, language and AI.
- You can ask as many questions as you need.
- We are interested in both the process and the final result.
- It's fine if you don't finish the whole exercise.
