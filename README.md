# Git-Bump-Version

A very simple git plugin to be able to bump versions as git tags.

Should only be using bash built-ins, with no external utilities, so should work
on pretty much any platform, including cygwin.

## Usage

```bash
git bump-version             # bumps the patch version, e.g. 5.3.254 -> 5.3.255
git bump-version --patch     # also bumps the patch version, e.g. 5.3.254 -> 5.3.255
git bump-version --minor     # bumps the minor version, e.g. 5.3.254 -> 5.4.0
git bump-version --major     # bumps the major version, e.g. 5.3.254 -> 6.0.0
git bump-version --to 8.9.1  # sets the version to 8.9.1 (will error out if that version already exists)
```
