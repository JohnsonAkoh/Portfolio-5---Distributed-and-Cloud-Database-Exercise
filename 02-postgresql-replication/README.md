# PostgreSQL Replication

## Overview

This section implements PostgreSQL streaming replication using a primary and standby database server.

## Architecture

- Primary server: accepts database write operations.
- Standby server: receives replicated database changes.
- Streaming replication: transfers changes from the primary to the standby.

## Objectives

- Configure PostgreSQL replication.
- Verify data transfer between database servers.
- Understand primary and standby server roles.
- Examine replication lag and consistency.
- Explore standby server availability.

## Planned Implementation

1. Deploy two PostgreSQL database containers.
2. Configure the primary database.
3. Configure the standby database.
4. Establish streaming replication.
5. Insert sample student records into the primary.
6. Verify that records appear on the standby.

## Implementation Status

Pending practical implementation and verification.

## Evidence

Screenshots of database configuration, replication status, and successful data synchronisation will be stored in the evidence folder.
