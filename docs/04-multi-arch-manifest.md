# Multi-Architecture Manifest Publishing

docker buildx build \
  --platform linux/amd64,linux/s390x,linux/arm64,linux/ppc64le \
  --push -t repo/app:tag .

Jenkins CI reference:
https://developer.ibm.com/tutorials/cicd-pipeline-with-jenkins-to-deploy-multi-arch-image-on-ocp-on-linuxone-and-x86/
