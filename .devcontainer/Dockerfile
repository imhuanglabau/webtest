FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-14

RUN npm install -g @angular/cli

WORKDIR /workspace

COPY . /workspace

RUN npm install
