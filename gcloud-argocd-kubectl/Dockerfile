FROM alpine/gcloud:latest
#argocd
RUN curl -sSL -o /usr/local/bin/argocd https://github.com/argoproj/argo-cd/releases/latest/download/argocd-linux-amd64
RUN chmod +x /usr/local/bin/argocd

ENTRYPOINT ["/usr/bin/env"]
