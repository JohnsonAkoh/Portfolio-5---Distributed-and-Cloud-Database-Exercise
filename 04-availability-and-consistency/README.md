# Database Availability and Consistency

## Overview

This section examines how distributed databases maintain reliable access to data and ensure that replicated records remain consistent.

## Availability

Availability refers to the ability of a database system to remain accessible when failures occur.

In this project, a standby PostgreSQL server will provide a foundation for recovery if the primary server becomes unavailable.

## Consistency

Consistency ensures that database operations preserve data integrity across the distributed system.

## Consistency Models

### Synchronous Replication
The primary waits for confirmation from the standby before confirming certain transactions.

### Asynchronous Replication
The primary confirms transactions without waiting for the standby to receive them. This can introduce replication lag.

## Student Management System Scenario

If a student examination result is updated on the primary server, replication should transfer the change to the standby server.

## Objectives

- Understand database availability.
- Compare synchronous and asynchronous replication.
- Examine replication lag.
- Explore database failure and recovery.
- Understand consistency and data-loss risks.

## Implementation Status

Practical testing and analysis will be documented after PostgreSQL replication is configured.

## Conclusion

Availability and consistency are important requirements for reliable distributed database systems.
