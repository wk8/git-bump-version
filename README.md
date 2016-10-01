# Git-Bump-Version

A very simple git plugin to be able to bump versions as git tags.

Should only be using bash built-ins, with no external utilities, so should work
on pretty much any platform, including cygwin.

## Usage

```bash
git bump-version             # bumps the patch version
git bump-version --patch     # also bumps the patch version
git bump-version --minor     # bumps the minor version
git bump-version --major     # bumps the major version
git bump-version --to 8.9.1  # sets the version to 8.9.1 (will error out if that version already exists)
```
