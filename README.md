<h1 align="center">Ian Gacheru Kibue</h1>

<h3 align="center">Platform & Infrastructure Engineer | Site Reliability Engineer</h3>

<p align="center">
  Building reliable cloud infrastructure, automated delivery pipelines, and production-ready Kubernetes platforms.
</p>

<p align="center">
  <a href="https://iangk.netlify.app">Portfolio</a> •
  <a href="https://www.linkedin.com/in/ian~kibui">LinkedIn</a> •
  <a href="mailto:gacheruian99@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=gcp,docker,kubernetes,terraform,githubactions,gitlab,jenkins,grafana,prometheus,linux&perline=10" alt="Technology stack" />
</p>

---

## About Me

Platform and Infrastructure Engineer with over three years of experience supporting business-critical systems across cloud, on-premises, and data-centre environments.

I work with Kubernetes, GCP, Docker, Terraform, CI/CD, GitOps, Linux, networking, security, and observability. My software engineering background helps me bridge application development and reliable production operations.

## Selected Project

### End-to-End Kubernetes Delivery Platform

A production-focused platform engineering project for securely building, publishing, and deploying a containerized application to Kubernetes.

```mermaid
flowchart LR
    A[Source] --> B[CI Quality Gates]
    B --> C[Container Build]
    C --> D[Security Scan]
    D --> E[Artifact Registry]
    E --> F[GitOps Repository]
    F --> G[Argo CD]
    G --> H[Kubernetes]
    H --> I[Monitoring]
```

The platform includes:

* Automated linting, testing, and application builds
* Multi-stage Docker builds with dependency caching
* Container vulnerability scanning before publication
* Immutable image tagging using Git commit identifiers
* Image storage in an OCI-compatible artifact registry
* Kubernetes configuration managed with Helm
* GitOps deployments and drift correction using Argo CD
* ConfigMaps and externally managed application secrets
* Readiness, liveness, and startup health probes
* Resource requests, limits, and multiple application replicas
* Rolling updates with deployment health verification
* Prometheus metrics and Grafana dashboards
* Automated rollback when deployment verification fails

The project demonstrates the complete delivery path from a developer commit to a secure, observable, and recoverable Kubernetes deployment.

---

<p align="center">
  <strong>Build reliably. Automate intentionally. Improve continuously.</strong>
</p>
