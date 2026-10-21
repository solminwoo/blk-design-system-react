# blk-design-system-react engineering guidance

<!-- ecc-engineering-defaults:start -->
## Engineering defaults
For coding work, read [.engineering/defaults.md](.engineering/defaults.md).
These are shared fallback conventions; the existing project owner, nested instructions,
skills, model choices, domain contracts and stronger verification/release gates remain authoritative.
No hooks, permissions, MCP services or background automation are installed by this guidance.

### Project adaptation
React design-system fork with license generation in its build. Candidate checks: `npm test -- --watchAll=false` and `npm run build`; inspect lifecycle/gulp scripts first. Preserve upstream attribution and license headers. Do not use `install:clean`, which deletes the lockfile, as routine verification.
<!-- ecc-engineering-defaults:end -->
