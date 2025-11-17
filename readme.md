# lnks

Custom windows lnks for common operations

```bash
act workflow_dispatch -s GITHUB_TOKEN=$(op read op://homelab/github/credential) -e .github/event.json --artifact-server-path $PWD/.artifacts
```