# Gantt Chart – Mobile Banking App

```mermaid
gantt
    title Mobile Banking App Project Plan
    dateFormat  YYYY-MM-DD
    section Planning
    Define Scope        :done,    des1, 2025-10-01, 3d
    Identify Stakeholders:active, des2, 2025-10-04, 3d
    section Requirements
    User Stories        :des3,    2025-10-07, 3d
    Technical Specs     :des4,    after des3, 4d
    section Design
    UI/UX Mockups       :des5,    after des4, 3d
    Database Schema     :des6,    after des4, 3d
    section Development
    Frontend Login      :des7,    after des5, 5d
    Backend Auth        :des8,    after des6, 7d
    Security Features   :des9,    after des8, 4d
    section Testing
    Unit Testing        :des10,   after des7, 3d
    Integration Testing :des11,   after des8, 3d
    UAT                 :des12,   after des11, 4d
    section Deployment
    Beta Release        :des13,   after des12, 2d
    Production Release  :des14,   after des13, 2d
