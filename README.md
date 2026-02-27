# IBM LinuxONE (s390x) ISV Onboarding Guide

This repository provides a structured playbook for Independent Software Vendors (ISVs) onboarding applications from amd64/arm64 architectures to IBM LinuxONE (s390x).

## Objectives

- Functional parity with x86
- Operational parity
- Production-grade artifact builds
- Multi-architecture container publishing
- GA support readiness

## Migration Phases

- [Architecture & Dependency Assessment](docs/01-architecture-assessment.md)
- [Container Strategy](docs/02-container-strategy.md)
- [Build Strategy (QEMU vs Native)](docs/03-build-strategy.md)
- [Multi-Architecture Manifest Publishing](docs/04-multi-arch-manifest.md)
- [Runtime & Operator Validation](docs/05-runtime-validation.md)
- [GA Readiness Checklist](docs/06-ga-readiness-checklist.md)

---

## CI/CD Reference (Jenkins-Based Multi-Architecture)

Primary reference implementation:

https://developer.ibm.com/tutorials/cicd-pipeline-with-jenkins-to-deploy-multi-arch-image-on-ocp-on-linuxone-and-x86/

---

## Reference Implementation

TAT Banking Multi-Architecture Example:
https://github.com/tonyfieit/TAT-Banking

IBM LinuxONE Ecosystem Team supports ISV enablement, architecture reviews, and certification alignment.
