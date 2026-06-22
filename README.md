# Jenkins and GitHub Actions Course Notes

Beginner-friendly Jenkins and GitHub Actions notes with practical labs for DevOps students.

## Folder Structure

| Folder | Content |
| --- | --- |
| [day1](day1/README.md) | Jenkins introduction, CI/CD, architecture, installation, unlock setup, SSH setup |
| [day2](day2/README.md) | Secure Jenkins, Matrix-based security, credentials, logs, freestyle job, practical |
| [day2/practical/Project1](day2/practical/Project1) | Sample Day 2 Git project for Jenkins freestyle job |
| [day3](day3/README.md) | Jenkins plugins, multibranch pipeline, real CI stages, Docker build/tag/push to ECR |
| [day3/projects/multibranch-ecr-demo](day3/projects/multibranch-ecr-demo) | Sample multibranch pipeline project with Docker and ECR Jenkinsfile |
| [day4](day4/README.md) | GitHub Actions practical: push trigger, pull request trigger, manual trigger, secrets, AWS login, ECR login |
| [.github/workflows/github-actions-practical.yml](.github/workflows/github-actions-practical.yml) | Safe GitHub Actions demo workflow that runs on push, pull request, and manual trigger |

## 7-Day CI/CD Roadmap

| Day | Topic |
| --- | --- |
| Day 1 | Jenkins introduction, CI/CD, architecture, installation |
| Day 2 | Security, credentials, logs, freestyle Git job |
| Day 3 | Jenkins plugins, multibranch pipeline, Docker image build/tag/push to ECR |
| Day 4 | GitHub Actions workflow syntax, automatic triggers, manual triggers, secrets, AWS/ECR login |
| Day 5 | Advanced GitHub Actions and Jenkins pipeline comparison |
| Day 6 | End-to-end CI/CD mini project |
| Day 7 | Revision, troubleshooting, interview preparation |

## How Students Should Use This Repository

1. Open the folder for the current class day.
2. Read the notes before the practical.
3. Run the commands step by step.
4. Take screenshots of the required output.
5. Use the interview questions for revision.

## Current Lessons

- [Day 1 Notes](day1/README.md)
- [Day 2 Notes and Practical](day2/README.md)
- [Day 3 Notes and Multibranch Project](day3/README.md)
- [Day 4 GitHub Actions Notes and Practical](day4/README.md)

## Current GitHub Actions Practical

This repository includes a safe classroom workflow:

```text
.github/workflows/github-actions-practical.yml
```

It demonstrates:

- Automatic trigger on push to `main`
- Pull request validation for `main`
- Manual trigger using `workflow_dispatch`
- GitHub runner environment information
- Repository checkout using `actions/checkout`
- Basic Python validation of the Day 3 sample app
- Explanation of the next production steps for AWS ECR deployment

After this change is pushed to GitHub, students can open the repository Actions tab and observe the workflow run automatically.
