# Shift Left (Preventive) Security for Containers/Kubernetes

This is the acompanying repo for my talk on Shift-Left Security in a Containerized World at DevOps World conference

_"An ounce of prevention is worth a pound of cure"_ - Benjamin Franklin

## Security Tools for Different SDLC Stages

### Development

**Code Scanning**

- [GoSec](https://securego.io/) (Go)
- [Bandit](https://github.com/PyCQA/bandit) (Python)
- [NodeJsScan](https://github.com/ajinabraham/NodeJsScan) (NodeJS)
- [SpotBugs](https://spotbugs.github.io/) (Java)

**Kubernetes Manifest Scanning**

- [KubeSec](https://github.com/controlplaneio/kubesec)
- [Prisma Cloud IaC](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin/prisma-cloud-devops-security/set-up-your-prisma-cloud-configuration-file-for-iac-scan.html#id3fa84acb-db42-46ab-a3bc-d19e7589c47e)

**Container Image Scanning**

- [Prisma Cloud Compute](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute.html)
- [JFrog](https://jfrog.com/xray/)
- [Clair](https://coreos.com/clair/docs/latest/)


### CI/CD

### Pre-deployment

### Runtime
