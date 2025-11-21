# CCPBioSim PDB2PQR Workshop

[![build](https://github.com/ccpbiosim/pdb2pqr-workshop/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/ccpbiosim/pdb2pqr-workshop/actions/workflows/build.yaml)

## Docker

This container is derived from the CCPBioSim JupyterHub image. This container
adds the necessary software packages and notebook content to form a deployable
course container.

## How to Use


In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/ccpbiosim/pdb2pqr-workshop:latest

## Contact
Please direct all comments and queries to [Charlie Laughton](mailto:charles.laughton@nottingham.ac.uk)
