# Security

## Reporting a vulnerability

Report a vulnerability in tfpr privately, through this repository's
**Security** tab: choose **Report a vulnerability**. Do not report it in a
pull request, a discussion or any other public place.

Licensed operators can also report through the support channel named in
their license agreement.

Include the version or commit, the affected workflow, action or command, the
steps to reproduce, and the impact you expect. Leave out real credentials,
state and plan output from a live tenant.

## Scope

- The reusable workflows and the dispatch action in this repository
- The runtime installer `install-runtime.sh`
- The release binaries and scripts attached to each release

Problems in a repository built on tfpr (its units, workflows or hooks)
belong with the operator of that repository.

## What happens next

- The report is acknowledged within one business day.
- A vulnerability rated critical is fixed in a release within ten business
  days of confirming it. Other fixes ship in the next minor release.
- Licensed operators are told about a critical vulnerability in a supported
  version as soon as it is confirmed.
- Fixes are published as new releases. Release tags are immutable, and each
  release lists the SHA-256 checksums of its files.
