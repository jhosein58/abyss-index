# abyss-index

Official package registry index for the Abyss programming language and Sonar package manager.

## Structure

Package metadata is stored under `packages/<name>.json`:

```json
{
  "name": "package-name",
  "description": "Short description",
  "git": "https://github.com/user/repo.git",
  "subdir": "optional/monorepo/subpath",
  "latest": "1.0.0",
  "versions": ["1.0.0"]
}
```

## Adding a Package

To submit a new package, fork this repository, add `packages/<name>.json`, and open a Pull Request.
