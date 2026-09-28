# Contributors

**Note:** This document is a work in progress.

This document outlines the responsibilities of human contributor roles in the
Duranta project. The project is divided into sub-projects, and most role
responsibilities are scoped to those sub-projects.

## Role Summary

| Role        | Responsibilities      | Requirements       | Defined by  |
| ----------- | ----------------------| -------------------| ------------|
| Contributor | Contributes code, docs, or ideas, review      | Signed CLA.        | GitHub org  |
| Collaborator      | Actively contributes and supports the community    | Sustained contributions      | members     |
| Committer   | Commits accepted code | Review history and sustained involvement     | committers  |
| Maintainer  | Maintains the sub-project, roadmap, and repository access        | Technical judgement and sustained involvement | maintainers |

The members, committers, and maintainers entries are defined in the
[CONTRIBUTING](../CONTRIBUTING.md) file.

## Contributors

Contributors should be welcomed to the community by existing members, helped
with the PR workflow, and directed to relevant documentation and communication
channels.

### Requirements

- Enable [two-factor authentication][two-factor-auth] on their GitHub account.
- Sign the CLA on the first PR, or before the first PR when contributing on
  behalf of a company.

## Collaborators

Collaborators are *continuously active* contributors who have demonstrated sustained involvement in the community. They can have issues and PRs assigned to them and should participate in developer meetings. Collaborator are expected to help community.

**Defined by:** The `members` entry in the
[CONTRIBUTING](../CONTRIBUTING.md) file.

### Requirements

- Have made **multiple contributions** to the project or community, enough to
  demonstrate an **ongoing and long-term commitment** to the project.
  Contributions should include, but are not limited to:
  - Authoring and reviewing PRs on GitHub, with substantial **merged** PRs.
  - Taking ownership of introduced features and reviewing PRs that affect
    those features.
- Subscribe to the sub-project [mailing list](https://github.com/duranta-project/openairinterface5g/wiki/MailingList).
- Actively contribute to one or more sub-projects.

### Responsibilities and Privileges

- Respond to issues and PRs assigned to them.
- Act as the owner (primary point of contact) of code they have contributed, unless ownership is explicitly transferred.
- Ensure their code is well tested.
- Ensure tests consistently pass.
- Address bugs or issues discovered after code is accepted.
- Collaborators will get one of the GitHub repository roles, read/triage/write 
based on their requirements.
- Collaborators can be assigned to issues and PRs, and others can request 
reviews from them with `/cc @username`.

## Committers

Committers commit code to the default or primary branch of a sub-project. For
example, the `openairinterface5g` sub-project default branch is `develop`.
They can review code for quality and correctness in parts of a sub-project.
They are knowledgeable about both the codebase and software engineering
principles.

**Defined by:** The `committers` entry in the
[CONTRIBUTING](../CONTRIBUTING.md) file.

**Note:** Committers commit only code that has been accepted by at least one
reviewer.

### Requirements

- Meet the same requirements as collaborators.
- Have a history of review and authorship in a sub-project.
- Have shown consistent involvement with the sub-project, including attending
  meetings and helping contributors.
- Understand the sub-project code, 3GPP standards, and coding languages used
  in the sub-project.
- Have approval from the maintainers and TSC members to receive committer
  rights.

### Responsibilities and Privileges

- Have the same responsibilities as collaborators.
- Have the right to merge pull requests into the sub-project `default` branch.

## Maintainers

Maintainers maintain the sub-project. They are responsible for code quality and
for maintaining the roadmap through discussion with the TSC and the community.

**Defined by:** The `maintainers` entry in the
[CONTRIBUTING](../CONTRIBUTING.md) file.

**Note:** Some Linux Foundation staff members have `owner` access to the
repository for administrative maintenance.

### Requirements

- Have a history of review and authorship in a sub-project.
- Have shown consistent involvement with the sub-project, including attending
  meetings and helping contributors.
- Have a deep understanding of the entire sub-project, 3GPP standards,
  project CI/CD pipelines, project infrastructure, and coding languages used in
  the sub-project.
- Have approval from existing maintainers and TSC members.

### Responsibilities and Privileges

- Maintain code quality.
- Maintain the sub-project roadmap.
- Have the right to grant access (write, triage, read, maintain) to collaborators of the sub-project repository.
- Have the right to merge pull requests and hot fixes into the sub-project
  `default` branch.
- Have the right to create tags and releases.

[two-factor-auth]:
  https://docs.github.com/en/authentication/securing-your-account-with-2fa
