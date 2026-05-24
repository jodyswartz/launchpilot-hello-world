Implemented the Mission Control Workflow update in [index.html](/workspaces/task-18/repo/index.html:195).

Changed the existing workflow block to:
- Use the requested “Mission Control Workflow” heading.
- Animate the five LaunchPilot steps in sequence.
- Add subtle card lift, border glow, and icon pulse timing.
- Preserve the existing responsive desktop row and mobile vertical pipeline.

Verification: ran `git diff --check` with no whitespace issues. No dev server needed; this is a static HTML page.