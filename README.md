# gBot Release Builder

Public CI/CD builder for gBot releases.

## Latest Release

Version: pending

Download: pending

## Release Flow

The private `olaria01/gBot` repository sends a `repository_dispatch` event when a `v*` tag is pushed. This repository receives the event, checks out the matching gBot tag, builds the Windows binary, and publishes a public release artifact.
