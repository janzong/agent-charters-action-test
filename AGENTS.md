# Test charter (intentional fixture)

## Overview
A tiny repository for verifying that `uses: janzong/agent-charters@v1` resolves and runs.

## Structure
- `README.md` — what this repo is
- `scripts/check.sh` — a path that does NOT exist on purpose (dangling pointer test)

## Build and test
Run `bash scripts/check.sh` before committing.
