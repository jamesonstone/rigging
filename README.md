# Rigging

Kubernetes Manifest Generation and Ensured Deployment

## Overview

`rig deploy` - rig deploy makes an underlying call to `kubectl` to deploy the application, once deployed, rig watches the deployment to ensure that it was deployed successfully. If the deployment is unsuccessful, `rig` attempts to reconcile the failure by parsing logs from the application and from Kubernetes.

## Getting Started

```bash
rig deploy
```
