# Scope of Work (SOW)  
**Project:** Malsi App – UI Refinement & Feature Enhancements  
**Repository:** [Malsi-App/malsi](https://github.com/Malsi-App/malsi)  
**Languages:** Dart (Flutter), Other  
**Date:** 2025-06-24

---

## 1. Project Overview

This Scope of Work (SOW) outlines the deliverables, estimated timelines, and payment milestones for refining all application screens to match provided design frames and implementing new features in the Malsi App.

### Key Features to Implement
- **UI Refinement:** All screens updated to provided design frames.
- **Post Expiry Feature:** Posts disappear 24 hours after creation (server-side logic).
- **Countdown Timer:** Visual countdown for each post in the user interface.
- **Burst Animation:** Visual animation when a post expires or is deleted.

---

## 2. Tasks, Timeline, and Effort Estimates

Assumptions:  
- Moderate work pace; developer with intermediate skill in Flutter/Dart.
- Provided frames are complete and clear.
- API endpoints exist or will be created for post expiry.
- Payment rate: $50/hr.

### A. UI Refinement

| Screen Type             | Est. Hours/Screen | # of Screens | Total Hours | Description                                       |
|-------------------------|-------------------|--------------|-------------|---------------------------------------------------|
| Home / Feed             | 6                 | 1            | 6           | Main feed, post list, navigation, refresh         |
| Post Detail             | 4                 | 1            | 4           | Full post view, interactions, sharing             |
| Create Post             | 5                 | 1            | 5           | Form, validation, media picker                    |
| User Profile            | 4                 | 1            | 4           | User info, posts, edit profile                    |
| Notifications           | 3                 | 1            | 3           | List, interactions                               |
| Settings                | 3                 | 1            | 3           | Preferences, account mgmt                        |
| Login/Register          | 4                 | 2            | 8           | Auth screens (login, register)                    |
| Miscellaneous/Dialogs   | 2                 | 3            | 6           | Confirm, error, toast, etc.                       |
| **Subtotal (UI)**       |                   | **11**       | **39**      |                                                   |

**Total UI Refinement: ~39 hours**

---

### B. Feature Implementation

| Feature                        | Frontend (hrs) | Backend (hrs) | Description                                              |
|--------------------------------|----------------|---------------|----------------------------------------------------------|
| Post 24hr Expiry (server)      | 0              | 6             | Scheduled jobs, DB update, deletion                      |
| Countdown Timer (UI)           | 4              | 0             | Timer component, updates, styling                        |
| Burst Animation (UI)           | 3              | 0             | Animation when post expires                              |
| Post Expiry Sync (API/UI)      | 2              | 2             | Ensure UI syncs with backend expiry, API endpoints        |
| Testing & QA (features)        | 3              | 2             | Unit/integration tests, manual QA                        |
| **Subtotal (Features)**        | **12**         | **10**        |                                                          |

**Total Feature Implementation: ~22 hours**

---

### C. Project Totals

| Area                 | Total Hours |
|----------------------|-------------|
| Frontend (UI + Features) | 39 + 12 = **51** |
| Backend (Features)       | 10         |
| **Grand Total**          | **61**     |

---

## 3. Milestones & Payments Spreadsheet

| Milestone                  | Deliverable Description                                             | Hours | Rate  | Amount  | Cumulative Amount | Due Upon                   |
|----------------------------|---------------------------------------------------------------------|-------|-------|---------|-------------------|----------------------------|
| 1. UI Refinement Phase 1   | Core screens (Home, Post Detail, Create, Login/Register)            | 23    | $50   | $1,150  | $1,150            | Completion & client review |
| 2. UI Refinement Phase 2   | Remaining screens (Profile, Notifications, Settings, Misc.)         | 16    | $50   | $800    | $1,950            | Completion & client review |
| 3. Post Expiry (Backend)   | Server-side 24hr expiry logic, DB, scheduled task                   | 6     | $50   | $300    | $2,250            | Feature tested             |
| 4. Countdown Timer (UI)    | Countdown timer UI, expiry sync, burst animation                    | 9     | $50   | $450    | $2,700            | Feature demo & approval    |
| 5. Integration & QA        | QA, bugfix, polish, documentation, delivery                         | 7     | $50   | $350    | $3,050            | Final sign-off             |

**Total Estimated Cost:** $3,050  
**Total Estimated Hours:** 61

---

## 4. Notes & Assumptions

- Timeline and cost are estimates; subject to adjustment with scope changes or unforeseen complexities.
- Screens and features based on standard social app patterns; custom/complex requirements may require revision of estimates.
- Payment due within 7 days of milestone delivery and acceptance.
- Client to provide all frames, assets, and access as needed.

---

## 5. Acceptance Criteria

- All screens match provided frames and pass visual QA.
- Posts reliably disappear 24 hours after creation (server-side).
- Countdown timer and burst animation function on all relevant screens.
- All code reviewed, tested, and delivered in repository.

---

## 6. Contact

For questions or clarifications, please contact Logan Riedley at 502-671-3113.
