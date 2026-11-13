Database Availability and Consistency

Overview

This section looks at how a distributed database will have reliable access to data and have consistency in its replicated data.

Availability

Availability is the ability to have a functioning database during failure scenarios.

In this project we will have a standby PostgreSQL server which can be used to recover in the event of a failure.

Consistency

Consistency ensures that operations will keep the data intact.

Consistency Models

Synchronous Replication

Primary database will wait for an acknowledgement from the standby database for some transactions.

Asynchronous Replication

Primary database will confirm some transactions without waiting for these to be received by the standby. This can create lag in the replication.

Student Management System

When updating a students examination results in the primary database this should be replicated to the standby database.

Objectives

Understand what database availability is.

Compare synchronous and asynchronous replication.

Explore lag in the replication.

Examine failure and recovery of the database.

Understand what consistency is and the risks of data loss.

Implementation

After setting up the replication with PostgreSQL, practical testing and analysis will be discussed.

Conclusion

Availability and consistency are important requirements to produce reliable distributed database systems.
