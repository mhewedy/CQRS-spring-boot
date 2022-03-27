# CQRS-spring-boot
Implementation for CQRS Read DB and Write DB 
## The project consist 
 - CQRS lib to handle CQRS abstractions
 - Command microservice
 - Query microservice
 
## Technologies
  - Mongodb for event store
  - Postgres Read Database
  - Kafka event bus with at least once idempotency Manual commit only if message proccessed successfully to read database (Duplicates can happen)
  - Spring-boot framework 
  - JAPA

## Patterns
 - CQRS
 - Mediator
 - DDD
 - event sourcing
 - Optimistic concurrency control
 
