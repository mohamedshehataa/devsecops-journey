# DevSecOps Journey

Public build log for an 18-week DevSecOps upskilling plan — starting from a software engineering background (Java, Linux, TCP/TLS, service architecture) toward platform/DevOps engineering with a security specialization.

One system, grown week by week: containerized → CI pipeline with security gates → Terraform on AWS → federated identity → policy as code → Kubernetes → hardened cluster → runtime detection → threat-modeled and documented.

## Structure

- `scripts/` — standalone tooling (hardening audits, checks), usable independent of the app
- `infra/` — Terraform/IaC, starting Week 5
- `progress/` — weekly write-ups: what was built, what broke, what's still unclear
- `docs/` — architecture, threat model, ADRs, runbooks (from Week 11 on)

## Log

| Week | Theme | Status |
|---|---|---|
| 1 | Linux, networking, hardening | in progress |

## Environment

Lab VM: local Ubuntu 24.04, VMware, key-only SSH.
