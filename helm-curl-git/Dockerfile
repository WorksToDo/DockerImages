FROM alpine/helm:3.8.0
RUN apk update && apk add --no-cache git curl bash jq findutils
RUN helm plugin install https://github.com/hypnoglow/helm-s3.git --version 0.10.0
