# RepoGuard Vulnerable Kubernetes

Intentionally insecure Kubernetes YAML fixtures for testing Trivy misconfiguration scanning.
Do not deploy these manifests to a cluster.

## Intended findings
- Privileged container
- Runs as root
- Host path mount
- Container allows privilege escalation
- Service exposed as NodePort
