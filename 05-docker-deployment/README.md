# Docker Database Deployment

## Overview

This section demonstrates the deployment of distributed PostgreSQL database services using Docker containers.

## Technology

- Docker Desktop
- PostgreSQL
- Docker Compose

## Planned Architecture

Two PostgreSQL containers will be deployed:

1. `postgres-primary` – primary database server.
2. `postgres-standby` – standby database server.

Both containers will operate on a shared Docker network.

## Objectives

- Deploy PostgreSQL containers.
- Configure persistent database storage.
- Establish network communication between containers.
- Configure streaming replication.
- Verify database connectivity and service availability.

## Deployment Process

1. Create a Docker Compose configuration.
2. Configure PostgreSQL services.
3. Start the containers.
4. Verify database connections.
5. Test replication between servers.

## Implementation Status

Pending deployment and practical verification.

## Evidence

Screenshots of Docker containers, network configuration, and database connectivity will be included in the evidence folder.

## Conclusion

Docker provides a practical environment for demonstrating distributed database deployment and management.
