# Multi-Arch Dockerfile Example

FROM registry.access.redhat.com/ubi9/ubi-minimal

ARG TARGETARCH
RUN echo "Building for architecture: ${TARGETARCH}"

COPY app /usr/local/bin/app
ENTRYPOINT ["/usr/local/bin/app"]
