# breastmri-site

Working repo for the breast MRI artifacts article.

## Publish target

**michaelzenkay.com only** (via `michaelzenkay.github.io`).
breastmri.org is reserved for the final polished version — nothing publishes there yet.

## Workflow

1. Edit `breast-mri-artifacts.html` here (review gate via `review-system.js`)
2. Run `publish-hpc.bat` from `Z:\src\michaelzenkay.github.io` to sync to michaelzenkay.com

The publish script (`publish-hpc.ps1`) reads from this directory:
- Copies `images/artifacts/` to `michaelzenkay.github.io/images/artifacts/`
- Copies `breast-mri-artifacts.html` with review gate stripped to `michaelzenkay.github.io/`

## What is gitignored (local only, not on breastmri.org)

- `breast-mri-artifacts.html` and related article files
- `images/artifacts/`

These publish to **michaelzenkay.com** only.
