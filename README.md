# gBot Release Builder

Public CI/CD builder for gBot releases.

## Latest Release

Version: v0.0.0-ci-test

Download: https://github.com/olaria01/gbot-release-builder/releases/tag/v0.0.0-ci-test

## Release Flow

The private `olaria01/gBot` repository sends a `repository_dispatch` event when a `v*` tag is pushed. This repository receives the event, checks out the matching gBot tag, builds the Windows binary, and publishes a public release artifact.
