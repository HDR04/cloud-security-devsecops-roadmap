# Projects

The final project lives here: **Secure Cloud Deployment on AWS** (S19–S22).

- Containerized app
- Terraform infrastructure on AWS (IAM + VPC + EC2/ECS + logs, least privilege)
- GitHub Actions pipeline: tests + Semgrep + Gitleaks + Trivy + Checkov, deployment via OIDC (no permanent AWS key)
- Audit report with the 5 tests (vulnerable dependency, bad Terraform config, fake secret, over-privileged IAM role, risky change blocked by the pipeline)
