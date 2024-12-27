# horizon-cli-helm

## Overview

This is the official Helm Chart for installing Horizon cli on Kubernetes.

## Installation

add the helm repo to your local repositories :

```shell
helm repo add evertrust https://repo.evertrust.io/repository/charts
```

you can then use the chart using the prefix you chose :

```shell
helm install horizon-cli evertrust/horizon-cli
```

> [!NOTE]  
> Don't forget to set your Horizon credentials.
> You can do this by setting the `horizonCredentials.endpoint`, `horizonCredentials.apiID`, and `horizonCredentials.apiKey` values in your custom values file.
