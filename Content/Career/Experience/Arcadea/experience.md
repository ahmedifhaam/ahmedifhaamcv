# Arcadea Group / Arcadea LLC

Visibility: NEEDS_REVIEW

## Employment
- Title: Consultant Senior Software Engineer
- Start: 2024-05
- End: 2026-05
- Work context: Parent company; Canada (Remote) appears in the uploaded CVs.

## Transition
After approximately two years with the parent company, Ahmed was absorbed into its subsidiary, AgCode. This represents a continuation of the employment relationship rather than a separate unrelated career move.

## Role progression and work

### .NET MAUI / application architecture
- Joined as a .NET full-stack developer and initially led the Android/.NET MAUI team.
- Designed and implemented a custom page/navigation and layout abstraction because the application's requirements could not be mapped directly to the available .NET MAUI components.
- The architecture supported multiple panes, dynamically hostable pages, stacked page navigation, and layered drawers, while abstracting the underlying navigation and visibility management from feature developers.
- Personally owned the architecture and implementation; there was no separate technical reviewer for this work.
- The custom architecture became the standard navigation foundation across the application except for the login flow.
- Developed the mobile UI foundation over approximately 1.5 years before handing it over to the wider team.

### Backend engineering and legacy Angular
- Moved into .NET backend development and maintenance of an older Angular application, regularly working across frontend, API/service, and data-access layers.
- Diagnosed Angular performance problems through code inspection, profiling, and build analysis.
- Identified excessive DOM updates caused by API-driven processing inside loops and reworked rendering/data-loading behavior using virtual scrolling, lazy loading, caching, reusable components, and a controlled loading interaction.
- A high-volume screen that became unresponsive around 1,000 cards was subsequently able to support 100,000+ cards without loading all data into the DOM at once.
- Diagnosed a backend data-integrity issue involving records being dropped across multiple services by tracing logs and debugging execution flow.
- Identified repeated repository/database calls inside a processing loop and, during live debugging, observed that many retrieved values were reusable; redesigned the flow around prefetched data/lookups.
- Reworked persistence from destructive delete-and-reinsert behavior to scoped upsert/orphan handling with validation safeguards.
- Introduced a repository-level scoped execution abstraction and implementation for transaction/retry handling, removing direct database-context access from the provider and making the capability reusable across the generic provider architecture.
- Implemented backend and frontend changes across the full request path, including security fixes, code-path optimization, and legacy-system feature development.
- Independently implemented the final two new features end-to-end across the relevant frontend and backend layers, enabling continued feature development in the legacy system.
- Influenced testing practices and reusable engineering patterns within the team.

### AI-augmented development
- Developed and used a structured AI-augmented engineering workflow for approximately 1.5 years spanning requirement analysis, specification refinement, planning, ATDD-oriented implementation, unit-test improvement, code/specification review loops, verification-scenario generation, Playwright test development, test review, and PR refinement.
- Separately developed an AI-augmented SonarQube remediation workflow using shell scripting, Claude, isolated worktrees, test generation, TDD, and code review.
- The SonarQube workflow leaves PR creation and approval under developer control.
- The SonarQube workflow eliminated the need for five developers to spend approximately one day per week on recurring SonarQube issue fixing.

## Technical leadership
- Responsible for architecture, technical decisions, and engineering standards within the team.
- Personally identified and implemented solutions for the major frontend and backend improvements above; team technical-lead review applied to Angular and backend changes.
- Contributed to testing practices and reusable repository/engineering patterns.

## Technologies explicitly documented
- .NET MAUI
- .NET / .NET Core
- Android
- Angular
- Backend APIs
- EF Core / repositories
- SonarQube
- Claude
- Shell scripting
- Unit testing / UAT
- TDD
- Playwright
