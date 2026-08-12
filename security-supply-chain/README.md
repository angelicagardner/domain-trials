Suggestions:
1. Generate SBOM for a toy repo with Syft, scan it with Grype or Trivy
2. Sign and verify small container image using cosign's keyless signing flow
3. Write a CI step that fails the build if an image isn't signed/verified - a small, real policy enforcement PoC
