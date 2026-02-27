# Multi-Architecture Manifest

Recommended practice:

docker buildx build \
  --platform linux/amd64,linux/s390x,linux/arm64,linux/ppc64le \
  --push -t repo/app:tag .

Benefits:
- Unified tag
- Transparent Kubernetes pull behavior
