# KubeVoIP Asterisk runtime

This repo contains the Dockerfile for the Asterisk image used by KubeVoIP
application workers.

Image:

```text
ghcr.io/kubevoip/kubevoip-asterisk
```

The older `ghcr.io/kubevoip/kubevoip-asterisk-worker` image remains available
for older platform releases. New releases use `kubevoip-asterisk`.

The platform chart pins the tested tag. Most users should install KubeVoIP from
`kubevoip/kubevoip` instead of choosing component tags directly.
