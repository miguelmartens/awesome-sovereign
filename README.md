# Awesome Sovereign [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, projects, and providers that enable **Sovereign Cloud** and **digital autonomy**—with a strong focus on **Europe**, **open source**, **cloud native**, **privacy**, **interoperability**, and **reduced dependency on hyperscalers**.

Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome). PRs welcome!

---

## Table of Contents

- [What is “Sovereign”?](#what-is-sovereign)
- [Ecosystem Maps & Directories](#ecosystem-maps--directories)
- [EU & Community Initiatives](#eu--community-initiatives)
- [Sovereign-Friendly Cloud Providers (EU-first)](#sovereign-friendly-cloud-providers-eu-first)
- [Open Source Building Blocks](#open-source-building-blocks)
  - [Compute & Virtualization](#compute--virtualization)
  - [Container Platforms & Orchestrators](#container-platforms--orchestrators)
  - [Storage & Data](#storage--data)
  - [Networking & Service Mesh](#networking--service-mesh)
  - [Identity, Access & Privacy](#identity-access--privacy)
  - [Observability](#observability)
  - [GitOps, CI/CD & Release Engineering](#gitops-cicd--release-engineering)
  - [Policy, Compliance & Supply Chain Security](#policy-compliance--supply-chain-security)
  - [Edge, Hybrid & Bare Metal](#edge-hybrid--bare-metal)
- [Reference “Awesome” Lists](#reference-awesome-lists)
- [Standards, Regulations & Guidance](#standards-regulations--guidance)
- [Books, Courses & Trainings](#books-courses--trainings)
- [Contributing](#contributing)
- [License](#license)
- [Badge](#badge)

---

## What is “Sovereign”?

**Sovereign Cloud** emphasizes *control*, *transparency*, *interoperability*, and *compliance*:
- Operate and store data under jurisdictions you choose.
- Prefer open standards and open source to avoid lock-in.
- Enable portability across providers and on-prem/edge.
- Make security, privacy, and auditability first-class.

If it increases **digital autonomy** (technical, operational, legal), it likely belongs here.

---

## Ecosystem Maps & Directories

- **NeoNephos** – Linux Foundation Europe initiative advancing cloud-native sovereignty: <https://neonephos.org/>
- **European Alternatives** – Directory of EU alternatives to common digital services: <https://european-alternatives.eu/>
- **OpenAlternative** – Open source alternatives to popular SaaS: <https://openalternative.co/>
- **Privacy Guides** – Community-maintained privacy tools & how-tos: <https://www.privacyguides.org/en/>

---

## EU & Community Initiatives

- **Gaia-X** – Federated, secure European data infrastructure: <https://gaia-x.eu/>
- **NeoNephos (LF Europe)** – Programs/projects for digital autonomy: <https://neonephos.org/>
- **Sovereign Cloud Stack (SCS)** – Standardized, open source cloud platform: <https://scs.community/>

---

## Sovereign-Friendly Cloud Providers (EU-first)

> Listing is alphabetical. Inclusion ≠ endorsement. Prefer providers with EU HQ, EU ops, and strong data-sovereignty postures.

- **Exoscale** – <https://www.exoscale.com/>
- **Hetzner** – <https://www.hetzner.com/>
- **IONOS Cloud** – <https://cloud.ionos.com/>
- **OVHcloud** – <https://www.ovhcloud.com/>
- **Scaleway** – <https://www.scaleway.com/>
- **STACKIT** – <https://www.stackit.de/en/>
- **Hostinger** - <https://www.hostinger.com/>

---

## Open Source Building Blocks

### Compute & Virtualization
- **OpenStack** – IaaS cloud: <https://www.openstack.org/>
- **OpenNebula** – Lightweight private cloud: <https://opennebula.io/>
- **Harvester** – HCI on Kubernetes: <https://harvesterhci.io/>
- **Proxmox VE** – Virtualization platform: <https://www.proxmox.com/>

### Container Platforms & Orchestrators
- **Kubernetes** – <https://kubernetes.io/>
- **k3s** – Lightweight K8s for edge/IoT: <https://k3s.io/>
- **RKE/RKE2** – Rancher Kubernetes: <https://www.rancher.com/products/rke>
- **Talos Linux** – OS for Kubernetes: <https://www.talos.dev/>
- **Kairos** – Immutable Linux meta-distribution: <https://kairos.io/>

### Storage & Data
- **Ceph** – Distributed storage: <https://ceph.io/>
- **Longhorn** – Cloud-native block storage: <https://longhorn.io/>
- **MinIO** – S3-compatible object storage: <https://min.io/>
- **PostgreSQL** – Relational database: <https://www.postgresql.org/>
- **MariaDB** – Relational database: <https://mariadb.org/>
- **ClickHouse** – Columnar analytics DB: <https://clickhouse.com/>

### Networking & Service Mesh
- **Cilium** – eBPF networking/observability: <https://cilium.io/>
- **Calico** – Networking & NetworkPolicy: <https://www.tigera.io/project-calico/>
- **MetalLB** – Load balancer for bare-metal: <https://metallb.universe.tf/>
- **FRRouting (FRR)** – Routing stack: <https://frrouting.org/>
- **Istio** – Service mesh: <https://istio.io/>
- **Linkerd** – Lightweight service mesh: <https://linkerd.io/>

### Identity, Access & Privacy
- **Keycloak** – Open source IAM: <https://www.keycloak.org/>
- **ZITADEL** – Cloud-native identity: <https://zitadel.com/>
- **Authelia** – SSO & 2FA for web apps: <https://www.authelia.com/>
- **Vault** – Secrets management: <https://www.vaultproject.io/>

### Observability
- **Prometheus** – Metrics & alerting: <https://prometheus.io/>
- **Grafana** – Dashboards & viz: <https://grafana.com/>
- **Loki** – Logs: <https://grafana.com/oss/loki/>
- **Tempo** – Traces: <https://grafana.com/oss/tempo/>
- **OpenTelemetry** – Standardized telemetry: <https://opentelemetry.io/>

### GitOps, CI/CD & Release Engineering
- **Flux** – GitOps for K8s: <https://fluxcd.io/>
- **Argo CD** – GitOps continuous delivery: <https://argo-cd.readthedocs.io/>
- **Tekton** – K8s-native pipelines: <https://tekton.dev/>
- **Woodpecker CI** – Lightweight CI: <https://woodpecker-ci.org/>
- **Drone** – Container-native CI: <https://www.drone.io/>

### Policy, Compliance & Supply Chain Security
- **Open Policy Agent (OPA)** – Policy engine: <https://www.openpolicyagent.org/>
- **Kyverno** – K8s policy as code: <https://kyverno.io/>
- **Sigstore / Cosign** – Signing & verification: <https://www.sigstore.dev/>
- **in-toto** – Supply chain attestation: <https://in-toto.io/>
- **SLSA** – Supply chain levels for software artifacts: <https://slsa.dev/>
- **GUAC** – Graph for SBOMs & attestations: <https://guac.sh/>

### Edge, Hybrid & Bare Metal
- **Tinkerbell** – Bare-metal provisioning: <https://tinkerbell.org/>
- **Metal³** – Bare-metal for K8s: <https://metal3.io/>
- **Talos + Cluster API** – Declarative cluster lifecycle: <https://cluster-api.sigs.k8s.io/>

---

## Standards, Regulations & Guidance

> Link collections only (not legal advice).

- **GDPR** (General Data Protection Regulation): <https://gdpr.eu/>
- **NIS2** (EU Directive on network & information systems): <https://digital-strategy.ec.europa.eu/en/policies/nis2-directive>
- **EU Cybersecurity Certification** (schemes & library): <https://certification.enisa.europa.eu/>
- **Gaia-X** (federated data infrastructure): <https://gaia-x.eu/>

---

## Books, Courses & Trainings

- **Linux Foundation Training & Certification** – Cloud-native, security, compliance: <https://training.linuxfoundation.org/>
- **CNCF Trainings** – Kubernetes, observability, security: <https://www.cncf.io/training/>

---

## Contributing

Contributions are welcome! Please:

1. Read the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md#readme).
2. Add links in **alphabetical order** within each section.
3. Prefer **open source** and **EU-friendly** resources.
4. Use clear, neutral descriptions—no marketing fluff.
5. Run the linter locally before opening a PR.

### Local linting

```bash
# Requires Node.js
npx awesome-lint
````

If you propose a new category, include ≥3 solid entries.

---

## License

This work is licensed under **CC0 1.0 Universal** (Public Domain).
See [LICENSE](LICENSE) for details.

---

## Badge

Show your project is listed here:

```markdown
[![Mentioned in Awesome Sovereign](https://awesome.re/badge-flat.svg)](https://github.com/<your-org>/awesome-sovereign)
```
