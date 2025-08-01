# AlmaLinux 9

A Warewulf container definition based on AlmaLinux 9.

```
wwctl container import docker://ghcr.io/warewulf/warewulf-almalinux:9 almalinux-9
```

Also available are definitions for individual point releases (e.g., AlmaLinux
9.0). To generate these Containerfiles, run `make`.

The AlmaLinux community provides updates for the current point release of
AlmaLinux 9. If you need to remain on a specific point release you may want
to engage with a commercial support provider for long-term support.

**Note:** These container images are configured to minimize size. If you desire for
man-pages and other documentation to be available to users, e.g. on login-nodes, 
the `/etc/yum.conf` and `/etc/dnf/dnf.conf` flag `tsflags=nodocs` needs 
to be removed before installing additional packages. 

https://almalinux.org/support
