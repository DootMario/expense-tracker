# Expense Tracker

[English](#english) · [Română](#română)

---

## English

Spring Boot backend for a Romanian expense tracker built for freelancers, SMBs and gig
drivers. Expenses are the core domain; trip tracking supports them, including automated
ANAF-compliant "foaie de parcurs" reports.

### Project Goals

The project aims to give Romanian freelancers, small businesses and gig drivers one place
to manage their deductible expenses and the paperwork that comes with them:

- Track expenses and receipts by category, with budgets and reporting
- Generate ANAF-compliant "foaie de parcurs" trip sheets automatically
- Link receipts to trips and compute travelled distances with PostGIS
- Extract receipt data via OCR and add optional AI-assisted features
- Keep core flows working when external services (OCR, maps, AI, payments) are unavailable

Out of scope: fleet management, payroll and bank syncing.

### Requirements

- JDK 17 or newer (the Maven build targets Java 17)
- Maven 3.9+ — or use the included Maven wrapper (`./mvnw`), no local Maven install needed
- PostgreSQL 16+ with the PostGIS 3.4 extension for local development and tests
- Docker and Docker Compose to run the database locally

---

## Română

Backend Spring Boot pentru o aplicație românească de gestionare a cheltuielilor, destinată
freelancerilor, IMM-urilor și șoferilor de ride-sharing. Cheltuielile reprezintă domeniul
principal; călătoriile îl completează, inclusiv generarea automată a foilor de parcurs
conforme ANAF.

### Obiective

Scopul proiectului este să ofere freelancerilor, întreprinderilor mici și șoferilor de
ride-sharing din România un singur loc pentru gestionarea cheltuielilor deductibile și a
documentelor aferente:

- Evidența cheltuielilor și a chitanțelor pe categorii, cu bugete și rapoarte
- Generarea automată a foilor de parcurs conforme ANAF
- Asocierea chitanțelor cu călătoriile și calcularea distanțelor parcurse cu PostGIS
- Extragerea datelor din chitanțe prin OCR și funcții opționale asistate de AI
- Menținerea funcționalităților de bază atunci când serviciile externe (OCR, hărți, AI,
  plăți) sunt indisponibile

Nu fac parte din scop: managementul flotei, salarizarea și sincronizarea bancară.

### Cerințe

- JDK 17 sau mai nou (build-ul Maven vizează Java 17)
- Maven 3.9+ — sau folosiți wrapper-ul inclus (`./mvnw`), fără a instala Maven local
- PostgreSQL 16+ cu extensia PostGIS 3.4 pentru dezvoltare locală și teste
- Docker și Docker Compose pentru rularea bazei de date local
