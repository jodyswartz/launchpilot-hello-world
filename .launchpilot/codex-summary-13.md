Implemented the animated workflow in [index.html](/workspaces/task-13/repo/index.html:46).

What changed:
- Kept the existing hero intact.
- Added connected five-step workflow cards with simple icon badges.
- Added staggered fade-in and subtle pulse animations.
- Made desktop layout horizontal and mobile/tablet layout stacked.
- Added `prefers-reduced-motion` handling.

Verification: `git diff --check` passed. Only `index.html` was modified; existing untracked `.launchpilot` task files were left untouched.