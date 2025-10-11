# CKA & CKAD - Domains & Competencies

## Storage

- Implement storage classes and dynamic volume provisioning
- Configure volume types, access modes and reclaim policies
- Manage persistent volumes and persistent volume claims
    - Utilize persistent and ephemeral volumes (CKAD)

## Troubleshooting

- Troubleshoot clusters and nodes
- Troubleshoot cluster components
- Monitor cluster and application resource usage
- Manage and evaluate container output streams
- Troubleshoot services and networking

## Workloads & Scheduling

- Understand application deployments and how to perform rolling update and rollbacks
    - Define, build and modify container images (CKAD)
    - Choose and use the right workload resource (Deployment, DaemonSet, CronJob, etc.) (CKAD)
    - Understand multi-container Pod design patterns (e.g. sidecar, init and others) (CKAD)
    - Use Kubernetes primitives to implement common deployment strategies (e.g. blue/green or canary) (CKAD)
    - Understand Deployments and how to perform rolling updates (CKAD)
- Use ConfigMaps and Secrets to configure applications
    - Understand ConfigMaps (CKAD)
    - Create & consume Secrets (CKAD)
- Configure workload autoscaling
- Understand the primitives used to create robust, self-healing, application deployments
- Configure Pod admission and scheduling (limits, node affinity, etc.)
    - Understand requests, limits, quotas (CKAD)
    - Define resource requirements (CKAD)
    

## Cluster Architecture, Installation & Configuration

- Manage role based access control (RBAC)
    - Understand ServiceAccounts (CKAD)
    - Understand Application Security (SecurityContexts, Capabilities, etc.) (CKAD)
    - Understand authentication, authorization and admission control (CKAD)
- Prepare underlying infrastructure for installing a Kubernetes cluster
- Create and manage Kubernetes clusters using kubeadm
- Manage the lifecycle of Kubernetes clusters
- Implement and configure a highly-available control plane
- Use Helm and Kustomize to install cluster components
    - Use the Helm package manager to deploy existing packages (CKAD)
    - Kustomize (CKAD)
- Understand extension interfaces (CNI, CSI, CRI, etc.)
- Understand CRDs, install and configure operators
    - Discover and use resources that extend Kubernetes (CRD, Operators) (CKAD)

## Services & Networking

- Understand connectivity between Pods
- Define and enforce Network Policies
    - Demonstrate basic understanding of NetworkPolicies (CKAD)
- Use ClusterIP, NodePort, LoadBalancer service types and endpoints
- Use the Gateway API to manage Ingress traffic
- Know how to use Ingress controllers and Ingress resources
    - Use Ingress rules to expose applications (CKAD)
- Understand and use CoreDNS 
    - Provide and troubleshoot access to applications via services (CKAD)
    
---

## Application Observability and Maintenance

- Understand API deprecations
- Implement probes and health checks
- Use built-in CLI tools to monitor Kubernetes applications
- Utilize container logs
- Debugging in Kubernetes


---

- Define, build and modify container images
- Deployment, DaemonSet, CronJob, Sidecar, Init, Persistent and Ephemeral Volumes, blue/green or canary, Rollout, CRD
- probes, authentication and authorization, requests, limits, quotas, ConfigMaps, Secrets, ServiceAccounts, SecurityContexts, Capabilities
- NetworkPolicies, provide and troubleshoot access to applications via services, Ingress
- Helm, Kustomize
- API deprecations, `kubectl logs`, `kubectl top`, `Debugging in Kubernetes`
