# auto-release-test
Some random auto release test.

Branches:

- main
- staging = base branch

Always make dev branch off staging, and PR to staging.

When there is a pr push merged into main:

- get the latest tag version (v0.0.0). get the version from style.css. Check whether it is updated.
- if not updated, do nothing.
- if updated make a tag according to the version number
- use this tag to make a draft of autorelease
