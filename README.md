# SE-Git-hw

This repository is made for my Master's course **CINS 5318- Software Engineering** as part of Assignment #1: *Version Control Using GitHub*. It demonstrates a complete Git/GitHub workflow: repository setup, branching, feature implementation, pull requests, code review, merge conflict resolution, and issue tracking.

**Repository:** [github.com/WasifHussain/SE-Git-hw](https://github.com/WasifHussain/SE-Git-hw)

## Project Description

The repo contains two simple Python scripts used to practice the Git workflow:
- `hello-world.py`: prints a "Hello, World!" style message
- `apple.py`: prints "I eat apples."

The point of the project isn't the scripts themselves, it's demonstrating the full collaborative development lifecycle: initial commit, feature branching, pull requests, peer review, conflict resolution, and issue management.

## Setup / How to Run

```bash
git clone https://github.com/WasifHussain/SE-Git-hw.git
cd SE-Git-hw
python hello-world.py
python apple.py
```

## Branches Used

| Branch | Purpose |
|---|---|
| `main` | Stable, reviewed code |
| `feature-1` | Initial feature branch adding `apple.py` |
| `wasif-issue` | Branch used to resolve the loop-related issue, merged via PR #6 |

## Workflow Summary

- **Initial commit**: Set up the repository with a README and `hello-world.py` on `main`.
- **Feature branch**: Created a feature branch to add `apple.py`, then opened a pull request to merge it into `main`.
- **Code review & collaboration**: My classmate, **Samuel Twamasi**, acted as my collaborator on this repository, reviewing pull requests, providing feedback, and being assigned issues in return for my review of his repository.
- **Merge conflict**: Simulated a conflict by editing the same line of code differently on two branches, then resolved it manually by editing out the conflict markers and committing the reconciled version.
- **Issues**: Created and tracked issues covering small code improvements (e.g., adding conditional logic and loops to the scripts), assigned between myself and Samuel, and closed them via commits referencing the issue numbers.
- **Pull Request #6** ("Fixed the issue for adding loop"): Merged the `wasif-issue` branch into `main`, resolving an issue that asked for a loop to be added to print a message multiple times.

## Issues Tracked & Resolutions

| Issue | Assigned To | Resolution |
|---|---|---|
| Add a loop to print a message multiple times | Wasif Hussain | Resolved in PR #6 (`wasif-issue` branch) by adding a `for` loop to `hello-world.py`, merged into `main` |
| Add if/else / documentation improvement to `apple.py` | Samuel Twamasi | Reviewed and merged after collaborator feedback |

## Collaboration

This assignment was completed with **Samuel Twamasi** as my collaborator. We added each other as collaborators on our respective repositories, opened pull requests on our own repos, and reviewed each other's PRs and issues, giving both of us the full GitHub review/approve experience described in the assignment.