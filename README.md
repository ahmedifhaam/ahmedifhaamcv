# Ahmed Ifhaam — Career & CV

This repository is the **single source of truth** for maintaining Ahmed Ifhaam's professional CV/resume and its public presentation.

## Structure

- `AgentFiles/` — agent skills, rules, standards, and workflows
- `Content/Career/` — verified career facts and source content
- `site/` — public CV website
- `.github/workflows/` — GitHub Pages and CV PDF publishing

## Source-of-truth rules

Career facts belong in `Content/Career/`. Generated CVs, website pages, and PDFs are presentation outputs derived from that content.

Agents must never invent employment dates, technologies, responsibilities, achievements, metrics, qualifications, or links. Conflicts and missing information must remain explicit and be marked `NEEDS_CONFIRMATION` until confirmed.

## CV website

The CV is published as a **project/nested GitHub Pages site**:

**https://ahmedifhaam.github.io/ahmedifhaamcv/**

The repository therefore remains the source repository, while the site is served under the repository path rather than the root user site.

## Development workflow

1. Update verified career facts in `Content/Career/`.
2. Apply the relevant `AgentFiles/` rules and skills.
3. Update the derived CV/site content.
4. Validate chronology, links, ATS readability, and public/private boundaries.
5. Let GitHub Actions build the PDF and publish the Pages site.

The separate `ahmedifhaam` repository is used as the lightweight GitHub profile/dashboard.
