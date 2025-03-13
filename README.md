# Kubex: Kubernetes Addons

**Kubex** is a collection of Kubernetes addons designed to enhance and extend the functionality of Kubernetes clusters. This repository provides various tools and configurations to improve cluster management, monitoring, networking, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

The repository includes the following addons:

- **CNI (Container Network Interface)**: Networking plugins to manage pod networking within the cluster.
- **Ingress-NGINX**: Ingress controller based on NGINX to manage external access to services.
- **Kube-Snapshot**: Tools for taking snapshots of Kubernetes resources.
- **Kubernetes Dashboard**: Web-based UI for Kubernetes cluster management.
- **Logging**: Centralized logging solutions for cluster logs.
- **Metrics Server**: Cluster-wide aggregator of resource usage data.
- **Monitoring**: Tools like Prometheus and Grafana for monitoring cluster performance.
- **Overprovisioning**: Strategies to handle resource overprovisioning.
- **Storage**: Storage solutions and configurations for persistent data management.
- **Tools**: Additional utilities to assist in cluster operations.

## Installation

To install and configure these addons:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ousiax/kubex.git
   ```


2. **Navigate to the Desired Addon Directory**:

   ```bash
   cd kubex/<addon-directory>
   ```


3. **Apply the Kubernetes Manifests**:

   ```bash
   kubectl apply -f .
   ```


   *Note*: Ensure you review and customize the manifests as needed before applying them to your cluster.

## Usage

Each addon comes with its own set of configurations and usage instructions. Refer to the README or documentation within each addon's directory for detailed information on how to utilize and customize them effectively.

## Contributing

We welcome contributions to enhance the functionality and reliability of these addons. To contribute:

1. **Fork the Repository**: Click on the 'Fork' button at the top right corner of this page.
2. **Create a New Branch**: Use a descriptive name for your branch.
3. **Make Your Changes**: Implement your feature or bug fix.
4. **Submit a Pull Request**: Provide a clear description of your changes and the problem they solve.

Please ensure your contributions align with the project's coding standards and include relevant documentation or comments.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

*Note*: This README provides a general overview. For specific details and configurations, refer to the documentation within each addon's directory. 
