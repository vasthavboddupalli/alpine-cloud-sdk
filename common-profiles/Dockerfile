FROM google/cloud-sdk:315.0.0-alpine
RUN apk update
RUN apk add --no-cache tar gnupg curl wget zip unzip vim tree make git bash libffi-dev openssl-dev bzip2-dev py3-pip python3 python3-dev ca-certificates
RUN gcloud components install alpha beta bq core gsutil pkg kubectl cbt bigtable pubsub-emulator cloud-firestore-emulator