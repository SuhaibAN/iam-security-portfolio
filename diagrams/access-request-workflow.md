# Joiner / Mover / Leaver Lifecycle Flow

## Purpose

This diagram documents the identity lifecycle process for employees joining, changing roles, or leaving the organization.

## Lifecycle Stages

| Stage | IAM Action | Security Goal |
|---|---|---|
| Joiner | Create account and assign role-based access | Provide correct access on time |
| Mover | Update access based on new role or department | Remove old access and prevent privilege creep |
| Leaver | Disable account and revoke access | Prevent unauthorized access |

## Flow

HR Event → Identity Update → Group Assignment → Application Access → MFA Enforcement → Access Review
