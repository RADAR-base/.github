<!--
Thank you for contributing to RADAR-base!
Please give this PR a clear, descriptive title (e.g. "Add heart-rate schema for Garmin connector").
Delete any section that genuinely does not apply, and mark it "N/A" rather than leaving it blank.
-->

## Description

<!-- Summarise what this PR changes and why. Write it so it is understandable months from now. -->

## Related Issue(s)

<!-- Link the issue(s) this PR addresses, e.g. "Closes #123". For new features or larger changes, please discuss in an issue first. For bugs, the issue should describe steps to reproduce. -->

## Motivation and Context

<!-- What problem does this solve? Why is this approach the right one? Note any alternatives you considered. -->

## Type of Change

<!-- Tick all that apply. -->

- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature (non-breaking change that adds functionality)
- [ ] Breaking change (existing functionality, APIs, schemas or configuration will change)
- [ ] Documentation only
- [ ] Refactoring / maintenance (no functional change)
- [ ] Dependency, build or CI/CD update
- [ ] Security fix

## Documentation

<!-- Documentation is part of the definition of "done". PRs will not be accepted until this section is complete and verified by a reviewer. -->

**Author:**

- [ ] I have checked whether this change requires documentation updates, and have made them in this PR (or a linked docs PR: <!-- link -->)
- [ ] `README`, wiki and/or the RADAR-base documentation site are updated where relevant (installation, configuration, usage, architecture)
- [ ] New or changed configuration options, environment variables, endpoints, schemas or Docker/Helm values are documented, including defaults
- [ ] API documentation (e.g. OpenAPI/Swagger spec, Javadoc/KDoc) is updated for any API changes
- [ ] `CHANGELOG` / release notes are updated
- [ ] Code comments explain any non-obvious logic
- [ ] Documentation changes are not required for this PR, because: <!-- explain -->

**Reviewer (must be completed before approval):**

- [ ] I have read the updated documentation and it is accurate, complete and consistent with the code changes
- [ ] I have followed at least one documented instruction (e.g. setup, config or usage steps) to confirm it works as written
- [ ] Any links, code snippets and examples in the documentation are valid

## How Has This Been Tested?

<!-- Describe how you tested your changes: test environment, versions, devices/platforms, and the tests you ran. Include unit, integration and manual testing where relevant. -->

- [ ] I have added or updated tests to cover my changes
- [ ] All new and existing tests pass locally and in CI
- [ ] I have tested with a realistic setup (e.g. RADAR-Kafka stack, Docker Compose or Kubernetes deployment) where relevant

## Data Privacy and Security

<!-- RADAR-base handles sensitive participant and health-related data. Consider the impact of this change on privacy and security. -->

- [ ] This change does not add, expose or log personal or participant-identifiable data (or any such handling is described below)
- [ ] No secrets, credentials, tokens or participant data are committed (including in tests, fixtures and example configs)
- [ ] Authentication, authorisation and access-control implications have been considered
- [ ] Data-protection (e.g. GDPR) or ethics-approval implications have been considered, where relevant
- [ ] New or updated dependencies have been checked for known vulnerabilities and licence compatibility

**Notes:** <!-- Describe any privacy or security considerations, or write N/A. -->

## Compatibility and Deployment

<!-- Anything that affects people running or integrating with RADAR-base. -->

- [ ] This change is backwards compatible with existing deployments, data and clients
- [ ] Changes to Avro/Kafka schemas, topics or the data model are backwards/forwards compatible (or the migration path is described)
- [ ] Database, configuration or infrastructure migrations are included and documented
- [ ] Upgrade notes are provided for any manual steps required when deploying

**Breaking changes / upgrade notes:** <!-- Describe what breaks and how users should migrate, or write N/A. -->

## Screenshots / Recordings (if applicable)

<!-- For UI or app changes, show before and after. -->

## Checklist

- [ ] My code follows the code style and contribution guidelines of this project (see `CONTRIBUTING`)
- [ ] I have performed a self-review of my code
- [ ] My changes generate no new warnings or linter errors
- [ ] The PR is focused on a single concern and is reasonably sized to review
- [ ] Commit history is clean and messages are meaningful
- [ ] I have targeted the correct base branch
- [ ] Any follow-up work is captured in a new issue
