# Container Strategy

## Base Images
Use UBI 8/9 images supporting s390x.

## Dockerfile Best Practices
- Avoid hardcoded linux-amd64 binaries
- Use ARG TARGETARCH
- Parameterize downloads

## Registry Strategy
Use unified tags via manifest lists.
