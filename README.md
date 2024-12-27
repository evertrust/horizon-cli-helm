# horizon-cli-helm

## Overview

This is the official Helm Chart for installing Horizon cli on Kubernetes.

## Installation

Add the Helm repo to your local repositories :

```shell
git clone https://github.com/evertrust/horizon-cli-helm.git

cd horizon-cli-helm

helm dependency build

helm install horizon-cli . -f you_custom_values.yaml
```

> [!NOTE]  
> Don't forget to set your Horizon credentials.
> You can do this by setting the `horizonCredentials.endpoint`, `horizonCredentials.apiID`, and `horizonCredentials.apiKey` values in your custom values file.
