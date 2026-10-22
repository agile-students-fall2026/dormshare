# Contributing to DormShare

This document outlines the guidelines and expectations for contributing to DormShare. All contributors are expected to follow these practices to ensure effective teamwork and consistent development.

## 1. Team Norms

Our team follows these [Scrum Team Norms](https://github.com/nyu-software-engineering/scrum-framework/blob/main/team-norms.md):

- **Communication:** Respond to team messages within 24 hours and communicate blockers or delays early.
- **Accountability:** Complete assigned tasks by agreed deadlines and keep GitHub issues updated.
- **Collaboration:** Respect everyone's opinions, help teammates when needed, and review each other's work.
- **Transparency:** Communicate progress honestly and raise concerns as soon as they arise.
- **Standups:** Attend standup meetings every class day and share what was done, what is planned, and any blockers.
- **Participation:** All team members contribute to development regardless of Scrum roles.

## 2. Git Workflow

We follow the **feature-branch workflow**, using `master` as our main branch.

1. Pull the latest changes from `master`.
2. Create a new branch using the naming convention `feature/short-description`.
3. Make changes and commit them with descriptive messages.
4. Push the feature branch to GitHub.
5. Open a Pull Request targeting `master` in the DormShare repository.
6. Request a code review from a teammate.
7. Obtain **at least one approval** before merging.

Direct commits to `master` should be avoided. Contributors must resolve merge conflicts and address review feedback before merging.

## 3. Contribution Rules

- **GitHub Issues:** All contributions should correspond to an existing issue or an agreed-upon task.
- **Task Assignment:** Contributors should work on their assigned tasks and update their status on the GitHub Project board.
- **Code Quality:** Write readable, maintainable code and follow existing project conventions.
- **Pull Requests:** Each PR should clearly describe the changes and reference the relevant GitHub issue.
- **Peer Review:** At least one teammate must review and approve each PR before merging.
- **Testing:** Test changes locally before submitting a PR.
- **Documentation:** Update relevant documentation whenever functionality or setup procedures change.
- **Security:** Never commit passwords, API keys, `.env` files, or other sensitive information.
- **Collaboration:** Discuss major changes with the team before implementing them.

Contributions may include new features, bug fixes, UI improvements, tests, documentation, and development tooling.

## 4. Local Development Environment

DormShare uses the MERN stack: MongoDB, Express.js, React, and Node.js.

### Prerequisites

- Git
- Node.js and npm
- A code editor (VS Code recommended)
- Access to the DormShare GitHub repository

### Setup

Clone the repository:

```bash
git clone https://github.com/agile-students-fall2026/generic-mern-stack-project-dormshare.git
cd generic-mern-stack-project-dormshare
```

Install frontend dependencies:

```bash
cd front-end
npm install
```

Install backend dependencies:

```bash
cd ../back-end
npm install
```

Database configuration and required environment variables will be documented once the development environment is finalized.

## 5. Building and Testing

The final build and test commands have not yet been established.

Until then, contributors should:

- Verify that their changes work locally.
- Check that existing functionality is unaffected.
- Test relevant frontend interactions and backend endpoints.
- Address errors before requesting a PR review.

This section will be updated with the exact commands for running, building, and testing the application as development progresses.
