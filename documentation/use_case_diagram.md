# Use Case Diagram – Business Requirement Manager (BRM)

## Primary Actor
Business Analyst (BA)

## Secondary Actors
- Project Manager
- Product Owner
- Stakeholder

## Use Cases
1. Create Requirement
2. Edit Requirement
3. Delete Requirement
4. View Dashboard
5. View Analytics
6. Manage Stakeholders
7. Update Status
8. Search Requirements

## Text Diagram (ASCII)

         +----------------------+
         |     Stakeholder      |
         +-----------+----------+
                     |
                     |
        +------------v-------------+
        |      Business Analyst    |
        +------------+-------------+
                     |
                     +-----------------------------------------------------+
                     |         |         |         |         |            |
        +------------v--+   +--v---------+   +-----v----+   +--v----------+
        | Create        |   | View       |   | Update    |   | Manage      |
        | Requirement   |   | Dashboard  |   | Status     |   | Stakeholders|
        +---------------+   +------------+   +------------+   +-------------+

