# Shell pre-commit hooks

**This project has been discontinued and has been replaced by
[pre-commit-hooks](https://git.shore.co.il/nimrod/pre-commit-hooks).**

[![pipeline status](https://git.shore.co.il/nimrod/shell-pre-commit/badges/master/pipeline.svg)](https://git.shore.co.il/nimrod/shell-pre-commit/-/commits/master)

Shell [pre-commit](http://pre-commit.com/) hooks.

## Usage

Add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://git.shore.co.il/nimrod/shell-pre-commit.git
  sha: v0.6.0
  hooks:
    - id: shell-lint
    - id: shellcheck
```

The minimal pre-commit version required is 0.15.0. The `shellcheck` hook
requires [shellcheck](https://www.shellcheck.net/) installed.

## License

This software is licensed under the MIT license (see `LICENSE.txt`).

## Author Information

Nimrod Adar, [contact me](mailto:nimrod@shore.co.il) or visit my
[website](https://www.shore.co.il/). Patches are welcome via
[`git send-email`](http://git-scm.com/book/en/v2/Git-Commands-Email). The repository
is located at: <https://git.shore.co.il/explore/>.
