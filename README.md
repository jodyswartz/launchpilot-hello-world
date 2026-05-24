# LaunchPilot

## What is LaunchPilot?

LaunchPilot is a Telegram-controlled AI coding workflow that turns ideas into GitHub pull requests. You describe what you want in Telegram, LaunchPilot runs the coding workflow, opens a PR, and lets you review the result from GitHub.

It supports approve-and-merge flows, so accepted changes can move from proposal to merged code with minimal manual steps. For website projects, LaunchPilot can also return a live website link from Vercel or GitHub Pages after deployment.

## How it works

LaunchPilot follows a simple five-step flow:

1. Telegram idea: send a task or feature idea to LaunchPilot from Telegram.
2. Codex build: Codex updates the repository and prepares the change.
3. GitHub PR: LaunchPilot opens a GitHub pull request for review.
4. Approve and merge: review the PR, request changes, or approve and merge it.
5. Open website: for deployable websites, open the live Vercel or GitHub Pages link after deployment.

## Telegram commands

| Command | What it does | Example |
| --- | --- | --- |
| `/new <idea>` | Creates a new LaunchPilot task from an idea. | `/new Create a simple landing page for my product.` |
| `/repo <taskId> <owner/repo>` | Sets the GitHub repository for a task. | `/repo 42 my-org/my-website` |
| `/run <taskId>` | Starts the coding workflow for a task. | `/run 42` |
| `/status <taskId>` | Shows the current task status. | `/status 42` |
| `/logs <taskId>` | Shows recent workflow logs for a task. | `/logs 42` |
| `/tasks` | Lists your LaunchPilot tasks. | `/tasks` |
| `/approve <taskId>` | Approves the task result after review. | `/approve 42` |
| `/reject <taskId>` | Rejects the task result or requests changes. | `/reject 42` |
| `/merge <taskId>` | Merges the approved pull request. | `/merge 42` |

## Typical workflow

Create a task from an idea:

```text
/new Create a simple landing page for my product.
```

Set the repository:

```text
/repo 42 my-org/my-website
```

Run the workflow and check progress:

```text
/run 42
/status 42
/logs 42
```

Review the pull request, then approve and merge it:

```text
/approve 42
/merge 42
```

If the project is configured for deployment, LaunchPilot returns the live website URL after the pull request is merged.

## Deployment links

After a PR is merged, LaunchPilot can show the live website link from Vercel or GitHub Pages. This lets you open the deployed site directly from Telegram once the deployment finishes.

## Requirements

- A Telegram account for controlling LaunchPilot.
- A GitHub repository where LaunchPilot can create pull requests.
- Optional Vercel or GitHub Pages setup for live website links.
