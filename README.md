# Branching and Commit Guidelines

## Branch Types

| Branch Name        | Description                                                                                   |
| :----------------- | :-------------------------------------------------------------------------------------------- |
| main/master        | Represnts the production-ready code.                                                          |
| develop/dev        | Integration branch where featrure branches are merged for testing.                            |
| releases/<version> | Branches for preparing releases, e.g., `releases/v1`.                                         |
| feature            | Created for developing new features. Format: `feature/<feature_name>`.                        |
| bugfix             | Used for fixing bugs. Format: `bugfix/<bug_description>`.                                     |
| hotfix             | Created for urgent fixes to production issues. Format: `hotfix/<issue_description>`.          |
| typefix            | For fixes related to code types(e.g. syntax errors). Format: `typefix/<issue_description>`.   |
| uifix              | For fixes related to user interface elements. Format: `uifix/<issue_description>`.            |
| improvements       | Created for general improvements to the codebase. Format: `improvements/<issue_description>`. |
| regression         | For fixes addressing regressions. Format: `regression/<issue_description>`.                   |
| temporary          | Used for experimentation or testing. Format: `temporary/<issue_description>`.                 |

## Commit Guidelines

### Format:

- Use imperative mood in commit messages. (e.g. "Fix bug" instead of "Fixed bug").
- Begin the commit message with a type and a short, descriptive summary of the changes.
- Optionally, include a reference to an associated issue or task.
