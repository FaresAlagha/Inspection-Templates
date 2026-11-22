# Inspection Summary Report


## Inspection Identification

- **Project:** _______________________________________________
- **Meeting Date:** _______________________________________________

## Work Product Description

**Offer a brief description of the requirements document under inspection. Mention page numbers, content, whatever meta-data (date created, version, etc).**

The document under inspection was an anonymous Software Requirements Specification (SRS) for a Research Grant Management System at SouthNorthern University. It was submitted as a GitHub-friendly Markdown repository in a ZIP folder and identifies itself as Version 0.1, with its status marked as In Progress. The repository includes the introduction, overall system description, user classes, operating environment, design constraints, assumptions and dependencies, as well as the main system features and individual use cases. It also contains a use case diagram, supporting activity and sequence diagrams, interface mockups, data requirements, software interface descriptions, security requirements, business rules and five stakeholder interview transcripts. The individual use cases are organized into separate Markdown files, with additional folders for diagrams and supporting materials. Some sections are more developed than others, while certain areas still contain placeholders or open questions that require further clarification. Since the document is written in Markdown, it does not have fixed page numbers, so section headings and individual filenames were used to locate specific content during the inspection.

## Inspectors

| #   | Role      | Inspector | Preparation Time (hours) |
| --- | --------- | --------- | ------------------------ |
| 1   | Author    |           |                          |
| 2   | Moderator | Matthew   |                          |
| 3   | Recorder  | Fares     |                          |
| 4   | Reader    | Lakshan   |                          |
| 5   | Inspector | Matthew   |                          |
| 6   | Inspector | Fares     |                          |
| 7   | Inspector | Lakshan   |                          |
| 8   | Inspector | Gulbideen |                          |
## Inspection Data

| Metric                   | Value                          |
| ------------------------ | ------------------------------ |
| Planned for Inspection   | ______ **All** pages           |
| Actually Inspected       | ______ Up to section 4.3 pages |
| Meeting Time             | ______2 hours                  |
| Total Planning Effort    | ______1 labor hours            |
| Total Overview Effort    | ______3 labor hours            |
| Total Preparation Effort | ______ 1 labor hours           |
| Actual Rework Effort     | ______N/A labor hours          |
## Inspection Process Description

**Describe your process from receipt of the document to preparation of this report. This includes:**
- **How the roles were distributed.**
    - All four group members participated as inspectors.
    - Matthew was the moderator and led the inspection.
    - Fares was the recorder and documented the issues in the Inspection Issue Log.
    - Lakshan was the reader and read through each section of the SRS.
    - Gulbideen participated as an inspector and contributed to identifying and discussing issues.
- **What each participant did before the meeting.**
    - Each group member individually reviewed the anonymous SRS before the formal inspection.
    - We also held a meeting before the recorded inspection to discuss the overall project, share our initial thoughts and review everyone's roles.
    - After the recorded inspection, we held another meeting to review the findings and share our final thoughts.

- **How the meeting was conducted. How did the group meet, how each section was inspected, how group participation was encouraged, how turns were taken, who led the inspection and how, who recorded the issues and how.**
    - The inspection was conducted through Zoom and recorded.
    - We inspected the SRS section by section, following the order of the document.
    - Matthew led the inspection and guided the discussion to keep everyone on track.
    - Lakshan read through each section, while Fares shared his screen using Obsidian.
    - The screen was arranged with the inspection templates on the left and the anonymous SRS document on the right.
    - We took turns sharing our observations and discussing any concerns we found.
    - Everyone was encouraged to participate and explain why they believed something should be recorded as an issue.
    - Fares recorded the agreed-upon issues in the Inspection Issue Log during the meeting.

- **Describe what the inspection covered, how long the meeting took, what was left out.**
    - The inspection covered the SRS from Section 1.1 through Section 4.3.
    - The following sections were not covered:
        - Section 5.2: Software Interfaces.
        - Section 6.5: Security.
        - Appendix B: Business Rules.
    - The recorded inspection meeting lasted approximately two hours.

**Describe what the inspection covered, how long the meeting took, what was left out.**
- We reviewed the SRS from Section 1.1 through Section 4.3.
- The following areas were not covered:
    - Section 5.2: Software Interfaces.
    - Section 6.5: Security.
    - Appendix B: Business Rules.
- The recorded inspection meeting lasted approximately two hours.

## Summary of Issues

The main issues identified during the inspection were related to consistency, completeness and traceability. Several requirements contradicted each other, particularly regarding late application submissions, Department Chair approvals, application validation and access permissions. Some important system functionality, especially CoR evaluations, grading, adjudication and final decision letters, was not properly covered by the documented use cases, despite being included in the proposed system scope. We also found duplicated and incomplete use case descriptions, unclear alternative flows and missing references to stakeholder interviews, even when relevant evidence was available in the repository. Additionally, some diagrams did not fully match their corresponding written requirements, and certain requirements referenced unrelated business rules or use cases. In Section 2, we also identified unclear user characteristics and technical assumptions that were not properly separated from organizational assumptions and dependencies. The ER diagram and data dictionary were not included in the submitted draft, and some of the repository links and Markdown formatting needed improvement. Overall, the group has established a good foundation for the SRS, but several requirements still need clarification, better supporting evidence and more consistent documentation. These issues make it harder for readers to understand exactly how the proposed system is expected to behave and whether all the stated requirements are properly supported.
## Product Appraisal

**RECOMMENDATION**
- [ ] accepted as is
- [ ] conditionally accepted upon verification
- [x] reinspect following rework
- [x] inspection not completed

**OTHER COMMENTS**

Inspection completed up to 4.3, did not cover 5.2, 6.5, and business rules. Analyzed project did not use main.md as instructed.

----
*Copyright © 2001 by Karl E. Wiegers. Permission is granted to use, modify, and distribute this document.*