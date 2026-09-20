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

I work with Kubernetes, GCP, Docker, Terraform, CI/CD, GitOps, Linux, networking, and observability. My software engineering background helps me understand both the application and the infrastructure keeping it alive.

I enjoy turning “it works on my machine” into repeatable deployments that work everywhere.

## Selected Project

### End-to-End Kubernetes Delivery Platform

A production-focused project for securely building, publishing, and deploying a containerized application to Kubernetes.

```mermaid
flowchart LR
    A[Source] --> B[CI Gates]
    B --> C[Build and Scan]
    C --> D[Artifact Registry]
    D --> E[GitOps]
    E --> F[Kubernetes]
    F --> G[Observe and Verify]
```

The platform includes:

* Automated linting, testing, and application builds
* Multi-stage Docker builds with dependency caching
* Container vulnerability scanning and immutable image tags
* Image publishing to an OCI-compatible artifact registry
* Helm-based Kubernetes configuration
* GitOps deployments and drift correction using Argo CD
* ConfigMaps and externally managed secrets
* Health probes, resource controls, and rolling updates
* Prometheus monitoring and Grafana dashboards
* Deployment verification and rollback procedures

The goal is simple: make deployments boring, predictable, and easy to recover when something goes wrong.

---

```bash
$ kubectl get career
NAME              STATUS     RESTARTS
ian-gacheru       Growing    0
```

<p align="center">
  <strong>Build reliably. Automate intentionally. Improve continuously.</strong>
</p>
