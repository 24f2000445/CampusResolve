# CampusResolve

CampusResolve is a **Campus Complaint Management System** that helps students and staff submit complaints and track their status.

## Application Link

[CampusResolve](https://campus-resolve-af8c0968.base44.app)

## Features

- Student and staff signup/login
- Submit complaints for Wi-Fi, Hostel, Classroom, and Laboratory issues
- Submit complaints anonymously
- Get a unique complaint ID
- Track complaint status
- Admin dashboard to view and manage complaints
- Search and filter complaints
- Priority queue for unresolved complaints
- Department performance leaderboard

## Complaint Status

`Raised → In Progress → Resolved`

## Priority Calculation

The urgency score is calculated using:

`Urgency Score = Category Weight + floor(Hours Pending / 24)`

| Category   | Weight |
| ---------- | -----: |
| Wi-Fi      |      2 |
| Hostel     |      2 |
| Classroom  |      1 |
| Laboratory |      3 |

A higher score means a higher priority.

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Development Platform:** Base44 AI
- **AI-Assisted Development:** Base44 AI was used to generate and build the website interface and functionality with prompts. The code was not written entirely from scratch by the team.
- **Storage:** Browser Local Storage

## How It Works

1. Students or staff sign up and log in.
2. They submit a complaint by selecting a category and describing the issue.
3. The system generates a unique complaint ID.
4. Users can track the complaint status.
5. Admins can view complaints, update their status, and monitor priority and department performance.

## Application Link

[CampusResolve](https://campus-resolve-af8c0968.base44.app)
