# admitguard-ankit
# AdmitGuard — Admission Data Compliance System

## Problem Statement

Futurense Technologies faces data integrity issues in its admission process.
Candidate data is entered without validation, causing ineligible candidates
to move forward in the pipeline. This results in:

- Wasted operational hours
- Poor candidate experience
- Compliance risks with institutional partners
- No structured tracking of eligibility exceptions

## Proposed Solution

AdmitGuard is a lightweight validation system that:

- Enforces strict eligibility rules at data entry
- Supports structured exception handling for soft-rule violations
- Flags high-risk entries automatically
- Maintains an audit log for compliance tracking
- Uses configurable JSON-based rule definitions

## Tech Stack

- Google AI Studio (Build Mode)
- Client-side validation (JavaScript)
- JSON-based rules engine
- localStorage for audit logging

## Project Structure

- Core Form UI
- Validation Engine (Strict + Soft rules)
- Exception Handling System
- Audit Log Module
