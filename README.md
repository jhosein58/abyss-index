# abyss-index

Official pod registry index for the Abyss programming language and Sonar pod manager.

## Structure

Pod metadata is stored under `pods/<name>.json`:

```json
{
  "name": "pod-name",
  "description": "Short description",
  "git": "https://github.com/user/repo.git",
  "subdir": "optional/monorepo/subpath",
  "latest": "1.0.0",
  "versions": ["1.0.0"]
}
```

## Adding a Pod

To submit a new pod, fork this repository, add `pods/<name>.json`, and open a Pull Request.
