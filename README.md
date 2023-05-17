# Approved

This is Jeremy's Automatic Code Ordainment Bot. It just approves any PR authored by Jeremy.

## Usage

```
name: Approved
on: pull_request_target
jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      pull-requests: write
    steps:
    - uses: jgustie/approved/.github/actions/approved@main
```
