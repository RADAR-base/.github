<!--
Thank you for contributing to RADAR-base!
Please give this PR a clear, descriptive title (e.g. "Add heart-rate schema for Garmin connector").
Delete any section that genuinely does not apply, and mark it "N/A" rather than leaving it blank.
-->

# Description

<!--Summarise what this PR changes and why. Write it so it is understandable months from now. -->
<!--What problem does this solve? Why is this approach the right one? Note any alternatives you considered.
Link to the RADAR-base RFC if related. _(optional)_  -->


## Related Issue(s)

<!-- Link the issue(s) this PR addresses, e.g. "Closes #123". For new features or larger changes, please discuss in an issue first. For bugs, the issue should describe steps to reproduce. -->



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
- [ ] New or changed configuration options, environment variables, endpoints, schemas or Docker/Helm values are documented, including defaults
- [ ] `CHANGELOG` / release notes are updated
- [ ] Documentation changes are not required for this PR, because: <!-- explain -->

## How Has This Been Tested?

<!-- Describe how you tested your changes: test environment, versions, devices/platforms, and the tests you ran. Include unit, integration and manual testing where relevant. -->

- [ ] I have added or updated tests to cover my changes
- [ ] All new and existing tests pass locally and in CI
- [ ] I have tested with a realistic setup (e.g. RADAR-Kafka stack, Docker Compose or Kubernetes deployment) where relevant

## Data Privacy and Security

<!-- RADAR-base handles sensitive participant and health-related data. Consider the impact of this change on privacy and security. -->

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
