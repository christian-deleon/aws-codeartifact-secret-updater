# CodeArtifact Secret Updater Helm Chart

This Helm chart manages AWS CodeArtifact secrets in any Kubernetes cluster, whether on AWS (EKS) or self-managed.

## Installation

1. Add the Helm repository:
   ```bash
   helm repo add aws-codeartifact-secret-updater https://christian-deleon.github.io/aws-codeartifact-secret-updater
   ```

2. Customize Values: Create a copy of the [values.yaml](values.yaml) file and update the values to your needs.

3. Install the Helm chart:
    ```bash
    helm install my-release aws-codeartifact-secret-updater/aws-codeartifact-secret-updater -f values.yaml --create-namespace
    ```
