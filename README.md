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

## Example workflow

Use `/new` to start a task:

```text
/new Create a simple landing page for my product.
```

Choose or confirm the repository:

```text
/repo my-org/my-website
```

Run the build workflow and check progress:

```text
/run
/status
```

LaunchPilot creates the code, opens a GitHub pull request, and shares the PR link in Telegram. After review, you approve and merge the PR. If the project is configured for deployment, LaunchPilot returns the live website URL.

## Deployment links

After a PR is merged, LaunchPilot can show the live website link from Vercel or GitHub Pages. This lets you open the deployed site directly from Telegram once the deployment finishes.

## Requirements

- A Telegram account for controlling LaunchPilot.
- A GitHub repository where LaunchPilot can create pull requests.
- Optional Vercel or GitHub Pages setup for live website links.
