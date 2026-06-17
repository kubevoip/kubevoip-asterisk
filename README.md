# KubeVoIP Asterisk Runtime

This repository builds the Asterisk runtime image used by KubeVoIP application
workers.

Published image:

```text
ghcr.io/kubevoip/kubevoip-asterisk
```

The older `ghcr.io/kubevoip/kubevoip-asterisk-worker` image is kept for
existing releases, but new platform releases use `kubevoip-asterisk`.

The platform repository pins a tested image tag in the KubeVoIP Helm chart.
Component releases may happen independently, but users should normally install
the chart from `kubevoip/kubevoip`.
