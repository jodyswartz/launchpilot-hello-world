Updated [README.md](/workspaces/task-17/repo/README.md) with the new `/cancel <taskId>` command and an optional cancel step in the example workflow.

It now documents that `/cancel` stops active Codex/build runs, marks the task as cancelled, and records the event in `/logs <taskId>`.

No tests were run since this was a documentation-only change. Note: there are existing untracked `.launchpilot` files that I did not touch.