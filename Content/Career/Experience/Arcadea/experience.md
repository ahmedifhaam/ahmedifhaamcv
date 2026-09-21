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

### .NET MAUI / Android
- Joined as a .NET full-stack developer and initially led the Android/.NET MAUI team.
- Worked on a complex mobile application where the product mockups could not be directly mapped to the available .NET MAUI components at the time.
- Designed and implemented a custom layout and abstraction layer to provide a reusable foundation for future features.
- The framework included custom drawers, panes, and pages capable of hosting other pages.
- This custom UI architecture was developed over approximately 1.5 years before being handed over to the wider team.

### Backend and Angular maintenance
- Moved into .NET backend development and maintenance of an older Angular application.
- The Angular application dynamically generated large portions of its pages from database entries, contributing to performance challenges.
- Worked on application performance, coding standards, and code-path optimization.
- Worked across the full stack to reduce unnecessary loops and conditional logic.
- Contributed to security fixes.
- Worked on Angular build/performance optimization. A documented investigation identified severe build-performance and memory issues; one safe optimization removed eager LoginModule and DxDashboardControlModule imports from AppModule while retaining required module-level imports.

### AI-augmented engineering automation
- During the later part of the Arcadea period, began developing AI-augmented workflows for software-engineering automation.
- One example is an automated SonarQube issue-fixing workflow using a custom shell script and a Claude session.
- The workflow asks the developer for a SonarQube task ID, creates an isolated worktree, and analyzes whether the selected issues are concentrated in the same file or represent similar issues across multiple files.
- For same-file issues, the workflow creates unit and UAT tests intended to provide at least 85% coverage of the current file before remediation.
- For similar issues across multiple files, the workflow processes the files individually.
- The remediation follows a TDD red-to-green workflow.
- After the fixes, the workflow invokes a code-review skill, creates a single commit, and leaves the developer to raise and obtain approval for the PR.
- The workflow eliminated the need for five developers to spend approximately one day per week on recurring SonarQube issue fixing.

## Technologies explicitly documented
- .NET MAUI
- .NET / .NET Core
- Android
- Angular
- Backend APIs
- SonarQube
- Claude
- Shell scripting
- Unit testing / UAT
- TDD
