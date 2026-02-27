# Container Strategy

- Use UBI/RHEL base images with s390x support
- Avoid hardcoded linux-amd64 downloads
- Parameterize architecture in Dockerfile
- Use build arguments (ARG TARGETARCH)
