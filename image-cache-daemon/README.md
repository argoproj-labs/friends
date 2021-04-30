## Image Cache Daemon

Maintainer: @dcherman
Repository: [Image Cache Daemon](https://github.com/dcherman/image-cache-daemon)

[Image Cache Daemon](https://github.com/dcherman/image-cache-daemon) is a service to pre-pull / cache images on Kubernetes before they're needed.

When it's desirable to run a container as fast as possible (such as when using Argo Workflows), image pull time can be a significant contributor to slow pod start times.  The image cache daemon is a service that's intended to help mitigate that by discovering images to pull from a variety of sources, then pulling those images on each node before they're actually needed.
