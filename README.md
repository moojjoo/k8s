Here’s an updated version of the README.md with the code block language changed from sh to bash:

---

# Kubernetes Learning Repository

Welcome to the **K8s Learning Repository**!  
This repo is dedicated to helping you learn, experiment, and master the fundamentals of Kubernetes—an open-source platform for automating deployment, scaling, and management of containerized applications.

---

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Key Concepts Covered](#key-concepts-covered)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)

---

## About

This repository provides hands-on examples, exercises, and notes to accelerate your understanding of Kubernetes. Whether you are new to K8s or want to deepen your knowledge, you’ll find practical content to help you build, deploy, and manage your own clusters and applications.

---

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [Minikube](https://minikube.sigs.k8s.io/docs/) or [Kind](https://kind.sigs.k8s.io/) (for running local clusters)

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/moojjoo/k8s.git
   cd k8s
   ```

2. **Start a local cluster (using Minikube):**
   ```bash
   minikube start
   ```

3. **Apply your first manifest:**
   ```bash
   kubectl apply -f examples/hello-world.yaml
   ```

---

## Repository Structure

```
k8s/
├── examples/            # Sample Kubernetes manifests
├── exercises/           # Hands-on labs and challenges
├── notes/               # Conceptual explanations and summaries
├── scripts/             # Useful automation scripts
└── README.md            # This file
```

---

## Key Concepts Covered

- Kubernetes Architecture & Components
- Deployments, Pods, and ReplicaSets
- Services & Networking
- ConfigMaps & Secrets
- Volumes & Persistent Storage
- Namespaces & RBAC
- Helm Basics
- Monitoring & Logging

---

## Learning Resources

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [Katacoda Interactive Scenarios](https://www.katacoda.com/courses/kubernetes)
- [Learn Kubernetes by Doing](https://labs.play-with-k8s.com/)
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes)
- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)

---

## Contributing

Contributions, suggestions, and issues are welcome!  
If you have new learning materials or improvements, please open an [issue](https://github.com/moojjoo/k8s/issues) or a [pull request](https://github.com/moojjoo/k8s/pulls).

---

## License

This repository is licensed under the [MIT License](LICENSE).

---

Happy learning and experimenting with Kubernetes! 🚀

---

Would you like me to update the README.md file in your repository with these changes?
