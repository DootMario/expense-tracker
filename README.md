# Expense Tracker

Spring Boot backend for a Romanian expense tracker built for freelancers, SMBs and gig
drivers. Expenses are the core domain; trip tracking supports them, including automated
ANAF-compliant "foaie de parcurs" reports.

## Requirements

- JDK 17 or newer (the Maven build targets Java 17)
- Maven 3.9+ — or use the included Maven wrapper (`./mvnw`), no local Maven install needed
- PostgreSQL 16+ with the PostGIS 3.4 extension for local development and tests
- Docker and Docker Compose to run the database locally
