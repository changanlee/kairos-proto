# kairos-proto

API contracts for Kairos. Used as a Git submodule by `kairos-web` (TS codegen) and `kairos-api` (Go codegen).

## Versioning
Package path is `kairos.v1`. Breaking changes require a new `/v2` subpackage — never mutate `v1` messages after release.

## Local validation
    buf lint       # style + structure
    buf breaking --against '.git#branch=main'   # detect breaking changes

Codegen lives in the consumer repos (`buf generate` is run from there, not here).
