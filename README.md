# Shift Left (Preventive) Security for Containers/Kubernetes

Accompanying repo for my talk on Shift-Left Security in a Containerized World at DevOps World conference

🔥 You can [access the slides here 🖱️](https://1drv.ms/p/s!AjlYT48sX1DwgQDDWwT7wiCAz5u4?e=SPY0ye)

#### My Other Related Repos
- [Container Security Best Practices](https://github.com/gunjan5/container-security)
- [Container Security Checklist with Risk Scores](https://github.com/gunjan5/cloud-native-security)
- [Fun: Container from Scratch](https://github.com/gunjan5/container-from-scratch)

_"An ounce of prevention is worth a pound of cure"_ - Benjamin Franklin

![](sdlc.gif)

## Security Tools for Different SDLC Stages

### Development Security

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


### CI/CD Pipeline Security

**Code Scanning** (same as above)
<details><summary>show</summary>
<p>
  
- [GoSec](https://securego.io/) (Go)
- [Bandit](https://github.com/PyCQA/bandit) (Python)
- [NodeJsScan](https://github.com/ajinabraham/NodeJsScan) (NodeJS)
- [SpotBugs](https://spotbugs.github.io/) (Java)

</p>
</details>

**DAST**

- [OWASP ZAP](https://github.com/zaproxy/zaproxy)
- [Arachni](http://www.arachni-scanner.com/)

**IAST**

- [Contrast Community Edition (CE)](https://www.contrastsecurity.com/contrast-community-edition)

**Kubernetes Manifest Scanning** (same as above)
<details><summary>show</summary>
<p>
  
- [KubeSec](https://github.com/controlplaneio/kubesec)
- [Prisma Cloud IaC](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin/prisma-cloud-devops-security/set-up-your-prisma-cloud-configuration-file-for-iac-scan.html#id3fa84acb-db42-46ab-a3bc-d19e7589c47e)

</p>
</details>

**Container Image Scanning** (same as above)
<details><summary>show</summary>
<p>
  
- [Prisma Cloud Compute](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute.html)
- [JFrog](https://jfrog.com/xray/)
- [Clair](https://coreos.com/clair/docs/latest/)

</p>
</details>

### Pre-deployment Security

**Kubernetes Admission Controller**

- [Prisma Cloud Compute](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute.html)
- [Open Policy Agent](https://www.openpolicyagent.org/)
- [Pod Security Policy](https://kubernetes.io/docs/concepts/policy/pod-security-policy/)

**Security Gates**

- [Binary Authorization](https://cloud.google.com/binary-authorization/)


### Runtime Security

**Network Security**

- [CN-series](https://docs.paloaltonetworks.com/cn-series.html)
- [Calico](https://www.projectcalico.org/)
- [Istio](https://istio.io/)
- [Prisma Cloud Compute](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute.html)
- [HashiCorp Consul](https://www.hashicorp.com/products/consul/multi-platform-service-mesh)

**Behavior Security**

- [Prisma Cloud Compute](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute.html)
- [Falco](https://github.com/falcosecurity/falco)

**Access Security**

- [IAM Analyzer](https://docs.aws.amazon.com/IAM/latest/UserGuide/what-is-access-analyzer.html)
- [RBAC](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)

**Sandboxing**

- [gVisor](https://github.com/google/gvisor)
- [Kata Containers](https://katacontainers.io/)
- [Nabla Containers](https://nabla-containers.github.io/)

**OS Hardening**

- [Google Container-Optimized OS](https://cloud.google.com/container-optimized-os/docs/concepts/features-and-benefits)

## Reference Architecture Using Prisma Cloud and CN-Series 

![](reference-architecture.jpg)
