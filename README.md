# Courier Validator Release & Deployment Repository

This repository hosts official production signed builds (`.apk`) and release metadata for the **Courier Validator** Flutter application.

## Structure
- `releases/`: Contains versioned signed APKs (`courier_validator-vX.Y.Z.apk`) and `courier_validator-latest.apk`.
- `metadata.json`: Holds current latest release version, sha256 checksums, and changelog for OTA updates.

## Automated Builds
Builds are created and staged from the main application repository using:
```bash
make build-release
make release-push
```
