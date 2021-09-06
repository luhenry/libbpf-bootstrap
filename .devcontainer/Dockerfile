# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.191.1/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version: bionic, focal
ARG VARIANT="focal"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get -y update \
 && apt-get -y install \
        build-essential \
        libelf-dev \
        clang \
        llvm-dev


