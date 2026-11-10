# Cloud Security & DevSecOps Roadmap

My 24-week hands-on roadmap to a Summer 2027 internship in Cloud Security / DevSecOps — Junior DevSecOps Engineer, Cloud Security Engineer or Cloud Security Analyst.

- **Student:** Houssam Drissi — ENIAD Berkane, IRSI (4th year)
- **Period:** 19 October 2026 – 4 April 2027
- **Pace:** ~6 hours/week (3 hours minimum on busy weeks, exam weeks paused)
- **Method:** 70% practice, 30% theory. Every week ends with something visible in this repo, not just watched courses.

## The final project

**Secure Cloud Deployment on AWS** — a containerized app, Terraform infrastructure on AWS (IAM + VPC + EC2/ECS + logs), least privilege everywhere, and a GitHub Actions pipeline that blocks dangerous changes (tests + Semgrep + Gitleaks + Trivy + Checkov).

## The 5 phases

| Phase | Weeks | Goal |
|---|---|---|
| 1. DevOps + AWS | S1–S6 | Git, Docker, CI/CD, AWS fundamentals (IAM, EC2, S3, VPC, CloudTrail, CloudWatch) |
| 2. Cloud Security | S7–S12 | SAST (Semgrep), dependency/image scanning (Trivy), secrets (Gitleaks), OIDC, detection |
| 3. Terraform + certs | S13–S18 | Secure architecture, KMS/Secrets Manager, advanced Terraform, Terraform Associate (004) |
| 4. Full project | S19–S22 | End-to-end DevSecOps project, deployed, audited (5 tests), documented |
| 5. Portfolio + internship | S23–S24 | Public portfolio, 5–10 min demo, AWS SAA-C03 (if ready), applications |

## Weekly rule

Each week = 1 guided lab + 1 challenge lab (redo alone, no tutorial) + 1 break/fix exercise + 1 deliverable pushed to GitHub.

A topic is done when I can redo it alone, explain why each security rule exists, and show the proof in this repo. Watching a course checks no box.

## Repo structure

```
notes/      One note per week: notes/week-X.md (what I built, broke, fixed, learned)
labs/       Hands-on labs, one folder per week/topic
projects/   The final project: Secure Cloud Deployment on AWS
```

## Certifications

1. **HashiCorp Terraform Associate (004)** — first, around S18–S20, only when mock exams are solid
2. **AWS Solutions Architect – Associate (SAA-C03)** — second, S23–S24 or after
3. Optional early: GitHub Foundations (GH-900). Later only: AWS Security – Specialty, CKS.

## AWS cost rule

Check the Free Tier, set a budget + alert from the first lab, destroy unused resources, and never commit an AWS key to a repo. If a secret is ever published by mistake, revoke it immediately — `.gitignore` alone is not enough.

## Progress

- [x] S1 — Git, GitHub and project setup
- [ ] S2 — Docker and container security
- [ ] S3 — CI/CD with GitHub Actions
- [ ] S4 — AWS fundamentals
- [ ] S5 — AWS networking and IAM least privilege
- [ ] S6 — Storage, logging and costs
- [ ] S7–S12 — Cloud Security
- [ ] S13–S18 — Terraform and certifications
- [ ] S19–S22 — Full project
- [ ] S23–S24 — Portfolio and applications
