<h1 align="center">Nikolaus Schuetz</h1>
<h3 align="center">Principal Platform Engineer · Data &amp; Infrastructure Platforms</h3>

<p align="center">
  <a href="https://nikolauspschuetz.dev"><img alt="Website" src="https://img.shields.io/badge/nikolauspschuetz.dev-000?logo=hugo&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/nikolaus-schuetz-49039737"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="https://registry.terraform.io/providers/linguado-dev/getstream/latest"><img alt="Terraform Registry" src="https://img.shields.io/badge/Terraform_Registry-author-7B42BC?logo=terraform&logoColor=white"></a>
  <a href="https://pypi.org/project/pymlb-statsapi/"><img alt="PyPI" src="https://img.shields.io/badge/PyPI-author-3775A9?logo=pypi&logoColor=white"></a>
</p>

I build the data and infrastructure platforms other engineers run on — ETL/ELT and data warehouses alongside the Kubernetes, Terraform, and CI/CD beneath them.

- 🏗️ **Currently** — principal-level platform work: credential migration, observability, cost, and CI modernization across large multi-account estates
- ⚙️ **Deep in** Terraform (authored &amp; published a provider), Kubernetes/GitOps, data platforms (Spark, Flink, Snowflake, Databricks, Airflow), and ReBAC/authorization (OpenFGA, Casbin)
- 🤖 **Practicing** AI-augmented, issue-driven engineering — and contributing the results back upstream

## 🚀 Things I've authored

| Project | What it is | |
|---|---|---|
| **[terraform-provider-getstream](https://registry.terraform.io/providers/linguado-dev/getstream/latest)** | Terraform provider for the GetStream chat API — **published to the Terraform Registry**. Go, Plugin Framework, full live-CRUD acceptance tests. | ![Stars](https://img.shields.io/github/stars/linguado-dev/terraform-provider-getstream?style=flat&logo=github&label=%E2%98%85&color=7B42BC) |
| **[pymlb-statsapi](https://pypi.org/project/pymlb-statsapi/)** | Schema-driven Python client for the MLB Stats API — 20 endpoints, 100+ generated methods, BDD test suite. | ![PyPI](https://img.shields.io/pypi/v/pymlb-statsapi?logo=pypi&logoColor=white&color=3775A9) ![Downloads](https://img.shields.io/pypi/dm/pymlb-statsapi?color=3775A9&label=%E2%86%93) |

## 🛠️ Merged upstream

Fixes and tests merged into projects I rely on — verified fails-before / passes-after, always with a regression test. A sense of the caliber:

<p>
  <a href="https://github.com/sharkdp/fd/pull/2082"><img alt="sharkdp/fd" src="https://img.shields.io/github/stars/sharkdp/fd?style=flat&logo=rust&logoColor=white&label=sharkdp%2Ffd"></a>
  <a href="https://github.com/apache/flink/pull/28912"><img alt="apache/flink" src="https://img.shields.io/github/stars/apache/flink?style=flat&logo=apacheflink&logoColor=white&label=apache%2Fflink"></a>
  <a href="https://github.com/apache/spark/pull/57522"><img alt="apache/spark" src="https://img.shields.io/github/stars/apache/spark?style=flat&logo=apachespark&logoColor=white&label=apache%2Fspark"></a>
  <a href="https://github.com/helm/helm/pull/32328"><img alt="helm/helm" src="https://img.shields.io/github/stars/helm/helm?style=flat&logo=helm&logoColor=white&label=helm%2Fhelm"></a>
  <a href="https://github.com/Kludex/starlette/pull/3389"><img alt="Kludex/starlette" src="https://img.shields.io/github/stars/Kludex/starlette?style=flat&logo=python&logoColor=white&label=starlette"></a>
</p>

- **Packaging &amp; build** — [pypa/wheel](https://github.com/pypa/wheel/pull/695) (ZIP64 corruption fix in the reference wheel implementation)
- **Data &amp; streaming** — [apache/flink](https://github.com/apache/flink/pull/28912), [apache/spark](https://github.com/apache/spark/pull/57522) (PyFlink/PySpark type-inference fixes)
- **CLI &amp; systems** — [sharkdp/fd](https://github.com/sharkdp/fd/pull/2082) (Rust panic fix), [Kludex/starlette](https://github.com/Kludex/starlette/pull/3389) (HTTP Range correctness)
- **Cloud-native (CNCF)** — [coredns](https://github.com/coredns/coredns/pull/8275), [containerd/nerdctl](https://github.com/containerd/nerdctl/pull/5088), [helm](https://github.com/helm/helm/pull/32328), [etcd](https://github.com/etcd-io/etcd/pull/22067), [OpenFGA](https://github.com/openfga/openfga/pull/3194)
- **Authorization** — [casbin/casbin](https://github.com/casbin/casbin/pull/1746) (UTF-8 correctness affecting authz decisions)
- **RL / ML** — [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium/pull/1648) (out-of-dtype `Discrete.contains` fix)
- **Terraform providers** — AWS, AzureRM, Google, hashicorp/hcloud, PagerDuty, Databricks
- **…and 30+ more** across the Python, Go, Rust, and JS/TS ecosystems

> [!NOTE]
> Tests for `git merge-base --is-ancestor` **[merged into git core](https://github.com/git/git/commit/89454a60ed3c)** — on `master`, integrated by Junio C Hamano.

## 🧰 Toolbox

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?logo=scala&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![Argo](https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)

![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white)
![Flink](https://img.shields.io/badge/Flink-E6526F?logo=apacheflink&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

---

<sub>📫 <a href="https://nikolauspschuetz.dev">nikolauspschuetz.dev</a> · <a href="https://www.linkedin.com/in/nikolaus-schuetz-49039737">LinkedIn</a> · building AI-SaaS + platform infrastructure</sub>
