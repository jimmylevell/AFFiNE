# About AFFiNE
AFFiNE self-hosted container definition.

## Frameworks used
- AFFiNE

# Docker image details
## Application
Base image: ghcr.io/toeverything/affine-self-hosted:latest
Exposed ports: 3000

# Deployment
## General
Service: affine
Data Path: /srv/docker/affine/
Access URL: affine.app.levell.ch

## Attached Networks
- traefik-public - access to reverse proxy

## Attached volumes
affinedata: storing the AFFiNE application data

## Environment variables
None (configured as needed)

# Authentication
Configured through AFFiNE application
