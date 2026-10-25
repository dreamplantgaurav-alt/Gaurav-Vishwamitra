<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,14,26,35&height=240&section=header&text=Gaurav%20Vishwamitra&fontSize=44&fontAlignY=38&desc=Senior%20DevSecOps%20Engineer%20%7C%20Enterprise%20Azure%20Cloud%20Architect&descFontSize=19&descAlignY=62&fontColor=ffffff" alt="Gaurav Vishwamitra Banner" width="100%" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/gaurav-vishwamitra" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:dreamplantgaurav@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="#-flagship-enterprise-architectures">
    <img src="https://img.shields.io/badge/Architecture_Portfolio-0A84FF?style=for-the-badge&logo=terraform&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/dreamplantgaurav-alt">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00D2FF&center=true&vCenter=true&width=750&lines=Senior+DevSecOps+Engineer+%26+Cloud+Architect;Architecting+Resilient+Azure+Cloud+Foundations;Engineering+Zero-Trust+Shift-Left+Pipelines;Orchestrating+Production-Grade+Kubernetes+(AKS);Scaling+100%2B+Workloads+with+FinOps+Cost-Efficiency;Automating+Everything+via+Terraform%2C+GitOps+%26+Python" alt="Typing SVG" />
</p>

---

## ⚡ Executive Summary

I am a **Senior DevSecOps Engineer & Cloud Solutions Architect** with **5+ years of battle-tested enterprise experience** spearheading mission-critical cloud migrations, architecting Zero-Trust cloud environments, and driving large-scale automation on **Microsoft Azure** and **Kubernetes**.

I operate at the intersection of **Strategic Business Vision** and **Hardcore Systems Engineering** — translating executive mandates (reliability, velocity, regulatory compliance, FinOps ROI) into immutable Infrastructure-as-Code (IaC), bulletproof CI/CD pipelines, and self-healing distributed platforms.

> *"Security is not a final checkpoint or an afterthought; it is an immutable, automated guardrail woven into every line of code, every container image, and every cloud resource from inception."*

---

### 📊 Enterprise Impact At A Glance

```
┌───────────────────────────────┬───────────────────────────────┬───────────────────────────────┐
│     100+ Enterprise Apps      │         99.99% Uptime         │         35% Cost Cut          │
│   Migrated & Modernized on    │  Engineered Multi-Region HA   │  FinOps Rightsizing & Cloud   │
│     Azure Zero-Downtime       │   & Disaster Recovery (RPO=0) │     Governance Automation     │
├───────────────────────────────┼───────────────────────────────┼───────────────────────────────┤
│         < 15 Minutes          │           100% Shift          │           Zero Leaks          │
│   Commit-to-Production Lead   │   Pre-Commit to Runtime SAST, │   Automated Secrets Mgmt with │
│     Time with GitOps Gates    │     SCA & Policy-as-Code      │   HashiCorp Vault & Azure KV  │
└───────────────────────────────┴───────────────────────────────┴───────────────────────────────┘
```

---

## 🏛️ End-to-End Enterprise DevSecOps Blueprint

Below is the **Production-Grade Reference Architecture** implemented across multi-tier enterprise environments, adhering strictly to **Zero-Trust (NIST SP 800-207)** and **Shift-Left Security** standards:

```mermaid
flowchart TD
    subgraph PlanCode ["1. PLAN & CODE (Shift-Left Inception)"]
        A["Developer Workstation / IDE"] -->|"Pre-commit Hook"| B["Secret Scans (TruffleHog / GitGuardian)"]
        B -->|"Signed Git Commit"| C["Enterprise Git Repo (GitHub / Azure Repos)"]
    end

    subgraph ShiftLeftCI ["2. BUILD & CONTINUOUS SECURITY GATES"]
        C -->|"Automated Trigger"| D["CI Pipeline (GitHub Actions / ADO)"]
        D -->|"SAST Analysis"| E["SonarQube (Quality Gate)"]
        D -->|"SCA & Licenses"| F["Snyk / Trivy (Vulnerabilities)"]
        D -->|"Container Scan"| G["Trivy / Grype (CVE Threshold)"]
        D -->|"IaC Security"| H["Checkov / tfsec / KICS"]
    end

    subgraph Governance ["3. INFRASTRUCTURE & POLICY AS CODE"]
        H -->|"Modular Terraform"| I["Terraform / Terragrunt State"]
        I -->|"Policy Validation"| J["Azure Policy / OPA Gatekeeper"]
        I -->|"FinOps Cost Check"| K["Infracost Budget Assertion"]
    end

    subgraph GitOpsDeploy ["4. GITOPS CONTINUOUS DELIVERY"]
        K -->|"Signed OCI Artifact"| L["Azure Container Registry (ACR)"]
        L -->|"Declarative Sync"| M["ArgoCD / FluxCD Controller"]
        M -->|"Zero-Downtime Deploy"| N["Production AKS Cluster"]
    end

    subgraph RuntimeDefense ["5. RUNTIME DEFENSE & SRE OBSERVABILITY"]
        N -->|"Dynamic Secrets"| O["HashiCorp Vault / Azure Key Vault"]
        N -->|"Kernel Security"| P["Falco & Microsoft Defender for Cloud"]
        N -->|"Telemetry & APM"| Q["Prometheus + Grafana + OpenTelemetry"]
        Q -->|"AIOps Alerts"| R["PagerDuty & Automated Auto-Healing"]
    end

    style PlanCode fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc
    style ShiftLeftCI fill:#0f172a,stroke:#a855f7,stroke-width:2px,color:#f8fafc
    style Governance fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#f8fafc
    style GitOpsDeploy fill:#0f172a,stroke:#10b981,stroke-width:2px,color:#f8fafc
    style RuntimeDefense fill:#0f172a,stroke:#ef4444,stroke-width:2px,color:#f8fafc
```

---

## 🛠️ Technical Competency & Tooling Radar

<table>
  <thead>
    <tr>
      <th width="26%">Pillar</th>
      <th width="44%">Technology Stack & Tools</th>
      <th width="30%">Core Architectural Competency</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Cloud Platforms & Architecture</b></td>
      <td>
        <img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
        <img src="https://img.shields.io/badge/Hybrid_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white" />
      </td>
      <td>Hub-and-Spoke Topology, Azure CAF, ExpressRoute, Landing Zones, Multi-Region Active/Passive DR, Private Endpoints</td>
    </tr>
    <tr>
      <td><b>Infrastructure as Code (IaC)</b></td>
      <td>
        <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" />
        <img src="https://img.shields.io/badge/Terragrunt-4B32C3?style=flat-square&logo=terraform&logoColor=white" />
        <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
        <img src="https://img.shields.io/badge/Azure_Bicep-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" />
      </td>
      <td>Modular IaC architecture, State locking & encryption, Continuous drift detection, Infracost automation</td>
    </tr>
    <tr>
      <td><b>Containers & Orchestration</b></td>
      <td>
        <img src="https://img.shields.io/badge/Kubernetes_(AKS)-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/Helm_v3-0F1689?style=flat-square&logo=helm&logoColor=white" />
        <img src="https://img.shields.io/badge/Istio_Service_Mesh-466BB0?style=flat-square&logo=istio&logoColor=white" />
      </td>
      <td>Hardened cluster provisioning, Calico Network Policies, KEDA event-driven autoscaling, Istio mTLS, Ingress NGINX</td>
    </tr>
    <tr>
      <td><b>CI/CD & GitOps Automation</b></td>
      <td>
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
        <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azure-devops&logoColor=white" />
        <img src="https://img.shields.io/badge/ArgoCD-EF6B48?style=flat-square&logo=argo&logoColor=white" />
        <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
      </td>
      <td>Declarative GitOps sync, Canary & Blue/Green automated cutovers, Ephemeral self-hosted runners</td>
    </tr>
    <tr>
      <td><b>DevSecOps & Shift-Left</b></td>
      <td>
        <img src="https://img.shields.io/badge/Trivy-0052CC?style=flat-square&logo=aqua&logoColor=white" />
        <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white" />
        <img src="https://img.shields.io/badge/Snyk-4C1E4F?style=flat-square&logo=snyk&logoColor=white" />
        <img src="https://img.shields.io/badge/Checkov-181717?style=flat-square&logo=bridgecrew&logoColor=white" />
        <img src="https://img.shields.io/badge/Vault-FFDA44?style=flat-square&logo=vault&logoColor=black" />
      </td>
      <td>SAST/DAST/SCA automation, Policy-as-Code (OPA/Kyverno), Dynamic secrets leasing, CIS Benchmarks, CycloneDX SBOM</td>
    </tr>
    <tr>
      <td><b>Observability, APM & SRE</b></td>
      <td>
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
        <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
        <img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" />
        <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" />
      </td>
      <td>Distributed tracing (OpenTelemetry), SLI/SLO/SLA definition, Custom Grafana dashboards, PagerDuty alerting</td>
    </tr>
    <tr>
      <td><b>FinOps & Cloud Economics</b></td>
      <td>
        <img src="https://img.shields.io/badge/Infracost-00D2FF?style=flat-square&logo=infracost&logoColor=black" />
        <img src="https://img.shields.io/badge/Azure_Cost_Mgmt-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white" />
        <img src="https://img.shields.io/badge/Kubecost-1A1A1A?style=flat-square&logo=kubernetes&logoColor=white" />
      </td>
      <td>PR-level cloud cost forecasting, Automated idle resource purging, Spot/Reserved instance strategies</td>
    </tr>
    <tr>
      <td><b>Scripting & Systems</b></td>
      <td>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
        <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
      </td>
      <td>Azure SDK & Boto3 automation, Custom CLI utilities, Kubernetes CRD controllers, Linux systems performance tuning</td>
    </tr>
  </tbody>
</table>

---

## 💼 IT Career Matrix & Senior Leadership Mindset

True senior engineering is defined by **business enablement**, **risk mitigation**, and **cost optimization** — not merely operational maintenance.

```
+------------+       +---------------+       +---------+       +----------------------+       +----------------+
|   Sales    | ----> |   Pre-Sales   | ----> |   TAM   | ----> | Enterprise Architect | ----> | Technical Lead |
| Commercial |       | Techno-       |       | Tech    |       | Infra + Application  |       | Infra / App    |
| Focus      |       | Functional    |       | Account |       | Strategy & Design    |       | Execution      |
|            |       | Proposals     |       | Manager |       |                      |       |                |
+------------+       +---------------+       +---------+       +----------------------+       +----------------+
```

### 🧠 The Senior Mindset: Bridging Strategy & Execution

```
       [ Executive Business Objective ]                    [ DevSecOps Architectural Enabler ]
  ──────────────────────────────────────────          ──────────────────────────────────────────────────
  Accelerate Time-to-Market (TTM)             ──────►  Self-Service IDPs, Trunk GitOps, Ephemeral Envs
  Strict Regulatory Compliance (SOC2 / ISO)   ──────►  Automated Policy-as-Code & Immutable Audit Logs
  Ensure 99.99% Availability & Brand Trust    ──────►  Multi-Region HA, Chaos Engineering, Circuit Breakers
  Cloud Unit Margin & Gross Profit Expansion  ──────►  Continuous FinOps Rightsizing & Reserved Allocations
```

#### 🎯 4 Architectural Tenets I Lead With:
1. **Business-First Metric Alignment**: Every engineering choice must tie directly to an organizational KPI: *Lead Time for Changes (LTFC)*, *Mean Time to Recovery (MTTR)*, *Change Failure Rate (CFR)*, or *Cloud Cost Per Transaction*.
2. **Shift-Left as a Cultural Standard**: Eliminating security tickets by embedding security testing directly into developer IDEs and Git pre-commit hooks.
3. **No Unmanaged Infrastructure**: 100% of cloud resources are provisioned through declarative IaC with strict drift detection and automated remediation.
4. **Resiliency by Design**: Designing systems that expect failures (chaos engineering, self-healing deployments, automatic failover, circuit breakers).

---

## 🚀 100+ Enterprise Workload Migration Framework

A battle-tested methodology implemented for zero-downtime mass migrations from on-premises/legacy datacenters to Azure:

```
[ Phase 1: Assess & Discover ] ──► [ Phase 2: Foundation & CAF ] ──► [ Phase 3: Wave Migration ] ──► [ Phase 4: FinOps & Governance ]
  • Azure Migrate discovery         • Hub-and-Spoke Network Landing   • Lift & Shift (Rehost)          • Tagging Policy enforcement
  • Dependency mapping              • Azure Firewall & ExpressRoute   • Containerize to AKS (Replatform)• Continuous Infracost monitoring
  • TCO & FinOps projection         • RBAC & Privileged Identity (PIM)• Cloud-Native Rewrite (Refactor)• Rightsizing & Reserved instances
```

---

## 📂 Flagship Enterprise Architectures

<details open>
<summary><b>🛡️ 1. Enterprise Multi-Region Azure Landing Zone (Hub-and-Spoke)</b></summary>
<br>

* **Objective:** Design and implement a scalable, highly secure corporate cloud foundation hosting 100+ microservices compliant with PCI-DSS & ISO 27001.
* **Architecture:**
  - Dedicated **Hub VNet** hosting Azure Firewall Premium (IDPS/TLS inspection), ExpressRoute Gateway, and Azure Bastion.
  - Multiple **Spoke VNets** segmented by environment (Prod, Staging, Shared Services) with non-overlapping RFC 1918 CIDRs.
  - Private DNS Zones and Private Endpoints ensuring zero exposure of PaaS services (Blob, SQL, Key Vault) to the public internet.
* **Tech Stack:** Terraform, Terragrunt, Azure Cloud Adoption Framework (CAF), Azure Policy.
* **Outcome:** Achieved 99.99% network availability, centralized egress filtering, and slashed provisioning time from 3 weeks to under 35 minutes.

</details>

<details>
<summary><b>🔒 2. Enterprise DevSecOps "Golden Path" Pipeline</b></summary>
<br>

* **Objective:** Replace fragmented legacy release pipelines with a centralized, secure-by-default CI/CD pipeline template used across 40+ engineering squads.
* **Security Pipeline Stages:**
  1. *Lint & Pre-flight:* `tflint`, `actionlint`, markdown/YAML validators.
  2. *Static Analysis (SAST):* SonarQube quality gate enforcement (Zero Vulnerabilities / Zero Security Hotspots threshold).
  3. *Dependency & SBOM (SCA):* Snyk + Trivy scanning with automated CycloneDX SBOM generation.
  4. *Infrastructure Compliance:* Checkov scanning against 800+ CIS benchmarks + OPA Gatekeeper policy evaluation.
  5. *Cosign Signature & Provenance:* Container image signing stored in Azure Container Registry (ACR).
* **Tech Stack:** GitHub Actions, Azure DevOps, Trivy, SonarQube, Cosign, Checkov, Infracost.
* **Outcome:** Eliminated 100% of high/critical CVEs before reaching production; deployment velocity increased by 400%.

</details>

<details>
<summary><b>☸️ 3. Zero-Trust Hardened Kubernetes Platform (AKS)</b></summary>
<br>

* **Objective:** Architect a secure, multi-tenant Kubernetes platform for financial transaction processing workloads.
* **Engineering Highlights:**
  - Native Azure CNI with **Calico Network Policies** enforcing strict zero-trust pod-to-pod isolation.
  - Azure Workload Identity replacing hardcoded service principal secrets.
  - **Kyverno / OPA Gatekeeper** admission controllers blocking root execution, unpinned image tags, and privileged mounts.
  - Automated continuous reconciliation via **ArgoCD** leveraging Kustomize overlays.
  - Real-time intrusion detection via **Falco** streaming alerts to Azure Log Analytics.
* **Tech Stack:** AKS, ArgoCD, Helm, Kyverno, Istio, Falco, HashiCorp Vault.
* **Outcome:** 100% compliance audit pass rate on first attempt with zero security deviations.

</details>

<details>
<summary><b>💰 4. Event-Driven FinOps Cost Optimization Engine</b></summary>
<br>

* **Objective:** Curtail rampant non-production cloud sprawl and drive systematic cost optimization across enterprise subscriptions.
* **Implementation:**
  - Automated serverless **Azure Functions (Python)** scanning for orphaned managed disks, unassociated public IPs, and idle App Service plans.
  - Scheduled automated hibernation of non-production AKS node pools and development VM scale sets outside business hours.
  - Pull-Request-level budget impact analysis via **Infracost** alerting team leads when code changes exceed cost limits.
* **Outcome:** Saved over **$180,000 annually (35% net cloud cost reduction)** in the first two quarters of deployment.

</details>

---

## 🎖️ Certifications & Professional Accreditations

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Certified-Azure_Solutions_Architect_Expert-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Certified-DevOps_Engineer_Expert-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_Foundation-Certified_Kubernetes_Administrator_(CKA)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/HashiCorp_Certified-Terraform_Associate-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/DevSecOps-Certified_Professional_(CDP)-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</p>

---

## 📈 GitHub Velocity & Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dreamplantgaurav-alt&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dreamplantgaurav-alt&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dreamplantgaurav-alt&theme=tokyonight&hide_border=true" width="96%" alt="Streak Stats" />
</p>

---

## 🤝 Let's Connect & Collaborate

Whether you're looking to discuss **Enterprise Cloud Migration Strategies**, **Zero-Trust DevSecOps Implementation**, **High-Availability Kubernetes Architecture**, or **FinOps Governance**, I'm always open to high-impact technical dialogues and leadership opportunities.

<p align="center">
  <a href="https://linkedin.com/in/gaurav-vishwamitra" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:dreamplantgaurav@gmail.com">
    <img src="https://img.shields.io/badge/Email-Direct_Inquiry-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/dreamplantgaurav-alt">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <sub>Engineered with precision, security, and enterprise excellence by <b>Gaurav Vishwamitra</b>.</sub>
</p>
