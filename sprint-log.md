# Sprint Log — AdmitGuard

## Sprint 0 (Planning & Setup)

**Goal:** Understand business problem and set up development environment.

**Completed:**
- Created GitHub repository
- Defined problem statement
- Documented proposed solution
- Planned 4-sprint execution approach

**Key Decision:**
Prioritize Must-Have functional requirements before UI polish.

**Status:** Completed

## Sprint 1 (Strict Validation Engine)

**Goal:** Implement mandatory business rules to prevent invalid admissions.

**Completed:**
- Inline real-time validation for core fields
- Conditional blocking for rejected candidates
- Aadhaar and phone strict format checks
- Offer letter dependency logic
- Submit button activation control

**Business Impact:**
Prevents ineligible candidates from entering the pipeline.

**Status:** Completed


## Sprint 2 (Soft Rules & Risk Engine)

**Goal:** Introduce non-blocking validation rules with risk scoring.

**Completed:**
- Age eligibility warning (under 18)
- Graduation year future check
- Minimum percentage / CGPA validation
- Low screening score warning
- Exception counter system
- High-risk application banner (>2 violations)

**Business Impact:**
Enables risk-aware admissions instead of binary rejection logic.

**Status:** Completed


## Sprint 3 (Dynamic Rule Configuration Engine)

**Goal:** Refactor validation logic to use centralized rule configuration and enable runtime rule updates.

**Completed:**
- Created centralized RULE_CONFIG object
- Replaced hardcoded validation values with config-driven logic
- Added Admin Rule Configuration section
- Converted rule display into editable inputs
- Implemented runtime rule update system
- Enabled dynamic validation refresh without page reload

**Business Impact:**
Transforms the system into a configurable compliance engine where policy changes can be applied instantly without modifying core logic.

**Status:** Completed


## Sprint 4 (Audit Logging & Compliance Tracking)

**Goal:** Implement submission tracking and compliance audit system.

**Completed:**
- Created structured audit object
- Implemented risk classification (Low / Medium / High)
- Stored submissions in localStorage
- Built persistent audit log viewer
- Added clear log functionality

**Business Impact:**
Provides traceability, accountability, and compliance monitoring for admission decisions.

**Status:** Completed
