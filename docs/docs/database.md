# CampusFlow — Database Design

## Database

PostgreSQL

## Core Tables

- users
- departments
- categories
- requests
- comments
- notifications
- audit_logs

## Main Relationships

- A user can create many requests.
- A staff member can be assigned many requests.
- A department can contain many users.
- A department can handle many requests.
- A category can contain many requests.
- A request can have many comments.
- A request can generate many notifications.
- A request can have many audit log entries.

## Request Status

OPEN
ASSIGNED
IN_PROGRESS
ESCALATED
RESOLVED
CLOSED

## User Roles

STUDENT
STAFF
ADMIN
