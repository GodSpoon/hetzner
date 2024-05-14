# Hetzner Cloud-Init Configuration

This repository contains the cloud-init configuration for setting up a VPS on Hetzner with Docker, Portainer, and RustDesk.

## What is in the cloud-init file?

The `cloud-init` file configures a new server with the following:
- Installs Docker and Docker Compose.
- Sets up Portainer for Docker management.
- Configures RustDesk, a remote desktop software, with Docker.
- Ensures all services are enabled and start on system boot.
