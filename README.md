# Scoop bucket for bkt

This bucket publishes the Scoop manifest for [`bkt`](https://github.com/manan-ramnani/bitbucket-cli), a Rust Bitbucket CLI.

The manifest is generated from GitHub Release artifacts by the `bbCLI` release workflow after each tagged release.

## Install

```powershell
scoop bucket add manan https://github.com/manan-ramnani/scoop-bucket
scoop install bitbucket-cli
```

## Maintainer Notes

- Do not hand-edit hashes unless repairing a failed release.
- The source release artifacts live in `https://github.com/manan-ramnani/bitbucket-cli/releases`.
- The expected manifest path is `bucket/bitbucket-cli.json`.
