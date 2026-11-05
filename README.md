# onetrueway-updates

Update feed for the self-hosted One True Way portal.

- `latest.json` lists the newest released version, its date and release notes.
- `latest.json.sig` is an Ed25519 signature of `latest.json`.

Installed sites check the signature with the public key shipped in each release
before trusting the feed. This repository contains no product code.
