# Download harbor offline-package needed by 'kubeasz'
#

FROM alpine:3.16

ENV HARBOR_VER=v2.12.4

RUN wget https://github.com/goharbor/harbor/releases/download/${HARBOR_VER}/harbor-offline-installer-${HARBOR_VER}.tgz

CMD [ "sleep", "360000000" ]
