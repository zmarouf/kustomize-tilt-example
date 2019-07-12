# Testing Tilt with Kustomize

## Tilt Information

```
Tilt: v0.8.7, built 2019-05-23
System: darwin-amd64
---
Docker
- Host: [default]
- Version: 1.40
---
Kubernetes
- Env: docker-for-desktop
- Context: docker-desktop
- Cluster Name: docker-desktop
- Namespace: default
- Container Runtime: docker
- Version: v1.14.3
---
Thanks for seeing the Tilt Doctor!
Please send this info along when filing bug reports. 💗
```
## How-to

- Make sure you have the local kubernetes context set.
  - You can check with `kubectl cluster-info`
  - If you're using Docker for Mac, make sure the Kubernetes checkbox is ticked.
- Now run `$ tilt up` and you'll be good to go.

