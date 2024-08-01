FROM mcr.microsoft.com/vscode/devcontainers/base:bullseye

RUN apt-get update && \
    apt-get install -y git bash-completion file && \
    rm -rf /var/lib/apt/lists/*

CMD [ "sleep", "infinity" ]
