# device-hub-ota-releases

Publication-only channel for signed Device Hub (ESP32-S3) firmware update bundles.

- Each release carries exactly `hub.ota` (signed bundle) and `release-note.txt` (one display-only line).
- Hubs fetch `releases/latest/download/hub.ota` anonymously and verify it with their pinned P-256 key; this repository is transport only and confers no trust.
- No source code, keys or secrets live here. Releases are immutable.
