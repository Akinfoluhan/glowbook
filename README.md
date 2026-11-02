# GlowBook ✨

A full-stack beauty management platform for organizing appointments, skincare routines, beauty products, and expenses.

## Overview

GlowBook aims to simplify personal beauty maintenance by bringing scheduling, routine tracking, product inventory, and spending management into one application.

The project will support both web and mobile clients through a shared Java Spring Boot backend.

## Tech Stack

- **Backend:** Java 21, Spring Boot, Spring MVC
- **Database:** PostgreSQL (planned)
- **Web:** React, TypeScript (planned)
- **Mobile:** React Native, Expo (planned)
- **Build Tool:** Maven
- **Testing:** JUnit, MockMvc

## Current Progress

- [x] Initialize Spring Boot backend
- [x] Create REST health endpoint
- [x] Add automated controller tests
- [ ] Implement beauty appointment management
- [ ] Integrate PostgreSQL
- [ ] Implement authentication
- [ ] Build routine, inventory, and expense tracking
- [ ] Develop web and mobile applications

## Getting Started

**Requirements:** Java 21

Run the backend locally:

```bash
./mvnw spring-boot:run
```

Check the health endpoint:

```text
GET http://localhost:8080/api/v1/health
```

## Status

🚧 Work in progress — currently developing the Spring Boot backend.
