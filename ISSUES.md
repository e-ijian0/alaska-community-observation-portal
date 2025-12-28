# Project Planning Issues

## Issue #1: Design Data Schema for Ice and Flood Observations
**Goal**: Define a standard JSON structure for recording observations.
**Fields**:
- Observation type (e.g., ice_thickness, water_level)
- Location (latitude/longitude or place name)
- Date/time
- Value (e.g., thickness in cm, level in m)
- Observer comments

**Status**: Implemented in `data_schema.json`.

## Issue #2: Mockup a Simple Web Submission Form
**Goal**: Create a static HTML/CSS prototype that matches the data schema.
**Requirements**:
- Input fields for each schema property.
- Drop-down for observation type.
- Placeholder for future integration.
- Responsive design for mobile use.

**Status**: Implemented in `mockup/submission_form.html`.

## Issue #3: Draft Contributor Guidelines
**Goal**: Write a CONTRIBUTING.md file that explains how community members and researchers can participate.
**Topics**:
- How to report observations.
- How to submit data.
- Code contribution workflow.
- Community engagement principles.

**Status**: Implemented in `CONTRIBUTING.md`.

---

*Note: These issues were created as part of the foundational framework for the Alaska Community Observation Portal.*