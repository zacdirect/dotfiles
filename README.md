# dotfiles

Managed with [chezmoi](https://www.chezmoi.io/). Helps me live a more ephemeral existence.

## Secrets

No secrets in this repo. Tokens and keys still need some environment variables, such as:

| Env var | Used by |
|---------|---------|
| `GH_TOKEN` | GitHub CLI + git credential helper |
| `GITLAB_TOKEN` | GitLab git credential helper |

## Usage

```bash
# First time
chezmoi init https://github.com/zacdirect/dotfiles.git
chezmoi apply

# Update
chezmoi update
```
