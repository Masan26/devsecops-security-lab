# DevSecOps security lab

Intentionally vulnerable educational code. Never deploy or expose this app.
The `config.py` credentials are PUBLIC DOCUMENTATION EXAMPLES, not live credentials.

The GitHub Actions workflow runs Gitleaks as a blocking gate, and Semgrep and Trivy as reporting checks in separate jobs.

Note: The Docker scanner tags and Semgrep pip install are version/tag dependencies; further hardening would pin immutable Docker image digests and Python package hashes.
