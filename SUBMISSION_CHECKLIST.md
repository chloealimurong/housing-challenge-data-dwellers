# Submission Checklist

Work through this before you submit. The first section lists the pass/fail
**eligibility gates** — a submission that misses any of these does not advance to
scoring. The rest map to the required deliverables and the rights
representations every team member must be able to make.

# Eligibility gates (pass/fail)

- [ ] **Reproducible setup.** The tool runs from the documented commands in the README, from a clean checkout, with no undocumented manual steps.
- [ ] **Automated tests.** Tests cover the core analytical logic, pass, and have a documented run command. CI is green.
- [ ] **No committed secrets.** Secret scanning is enabled and shows zero unresolved alerts. No `.env` or credentials are committed.
- [ ] **Security scanning configured.** Code scanning (CodeQL default setup or the workflow) and Dependabot alerts are enabled, with no unaddressed critical/high findings (or a documented justification for any that remain).
- [ ] **OSI-compliant license.** The repository includes one of the approved licenses (Apache-2.0, MIT, BSD-3-Clause, or BSD-2-Clause), and dependencies are permissively licensed.

See docs/REPO_SETUP_GUIDE.md for turning on the repository security settings.

# Required deliverables

- [ ] **Interactive tool** — functional, not a mockup.
- [ ] **Slide deck** (PDF export, ≤30 slides).
- [ ] **Demo video** — 5-minute recording, viewable without an account.
- [ ] **Model & Assumptions Overview** — docs/MODEL_AND_ASSUMPTIONS.md completed (≤25 pages).
- [ ] **Source code** — this repository, runnable per the README.
- [ ] **Policy scenario comparison** — docs/POLICY_SCENARIO_COMPARISON.md completed (≤4 pages).
- [ ] **Data provenance** — docs/DATA_PROVENANCE.md completed.
- [ ] **Disclosures** — docs/DISCLOSURES.md completed.

# Scope requirements

- [ ] Addresses housing supply at the **state level**.
- [ ] Demonstrates **at least three** of the five benchmark scenarios.
- [ ] Transparent and explainable to a non-technical policymaker.

# Participant rights representations

Each team member should be able to confirm that, to their knowledge:

- [ ] They own or have sufficient rights to submit their contributions.
- [ ] All contributors have authorized the submission and the selected license.
- [ ] The submission does not knowingly infringe third-party rights.
- [ ] All third-party code, dependencies, datasets, models, APIs, and services are disclosed in docs/DISCLOSURES.md and docs/DATA_PROVENANCE.md.
- [ ] The submission includes no confidential, proprietary export-controlled, or restricted materials unless the challenge rules expressly permit it.
- [ ] They have met any employer, university, or sponsor obligations that apply.
