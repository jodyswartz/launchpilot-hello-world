# LaunchPilot

LaunchPilot is a Telegram-controlled AI coding workflow that turns ideas into GitHub pull requests. You describe what you want in Telegram, LaunchPilot runs the coding workflow, opens a PR, and lets you review the result from GitHub.

It supports approve-and-merge flows, so accepted changes can move from proposal to merged code with minimal manual steps. For website projects, LaunchPilot can also return a live website link from Vercel or GitHub Pages after deployment.

## How it works

1. Send a task or feature idea to LaunchPilot from Telegram.
2. The AI coding workflow updates the repository and prepares the change.
3. LaunchPilot opens a GitHub pull request for review.
4. Review the PR, request changes, or approve and merge it.
5. For deployable websites, receive a live Vercel or GitHub Pages link.

## Example workflow

Send: "Create a simple landing page for my product."

LaunchPilot creates the code, opens a GitHub pull request, and shares the PR link in Telegram. After review, you approve and merge the PR. If the project is configured for deployment, LaunchPilot returns the live website URL.

## Requirements

- A Telegram account for controlling LaunchPilot.
- A GitHub repository where LaunchPilot can create pull requests.
- Optional Vercel or GitHub Pages setup for live website links.
