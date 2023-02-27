# ship-manager-api

> An simple API developed with Node.js and TypeScript to study Kubernetes and deploy to AKS Microsoft Azure.

## Techs

- Node.js - v18.x
- TypeScript
- Kubernetes
- Helm
- Microsoft Azure
- Github Actions
- Docker

## Features

- Create a new production environment whenever I publish a new tag on the master branch;
- Create a test environment isolated from any other, whenever I create a new branch and this environment has the name of the branch;
- Automatically delete the test environment whenever the branch is deleted;

## Getting Started

- To setup Azure infrastructure and the Github secrets, read the file [CREATING-AZURE-INFRASTRUCTURE.md](./docs/CREATING-AZURE-INFRASTRUCTURE.md).
