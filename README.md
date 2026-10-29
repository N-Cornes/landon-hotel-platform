# Landon Hotel Platform

A full-stack hotel reservation platform built with Java, Spring Boot, and Angular. The project extends an existing reservation system with internationalization, multi-currency presentation, time-zone conversion, REST API integration, multithreading, and containerized deployment.

## Tech Stack

- Java
- Spring Boot
- Spring MVC
- REST APIs
- Angular
- TypeScript
- HTML / CSS
- Angular HttpClient
- Maven
- Docker

## Core Features

- Hotel room reservation search
- Angular front end connected to a Spring Boot REST backend
- Localized welcome messaging in English and French
- Resource-bundle based internationalization
- Concurrent processing of localized messages
- Reservation pricing displayed for multiple currencies
- Time-zone conversion for scheduled hotel events
- HTTP-based communication between frontend and backend
- Containerized application deployment with Docker

## Application Architecture

```text
Angular Front End
       ↓
Angular HttpClient
       ↓
Spring Boot REST API
       ↓
Reservation / Business Logic
```

The Angular client communicates with the Java backend through REST endpoints, keeping presentation logic separate from server-side processing.

## Internationalization

The application supports bilingual welcome messaging using Java resource bundles. English and French messages are loaded independently and processed concurrently, demonstrating both localization and multithreaded Java execution.

## Currency and Time-Zone Support

The user interface was extended to present reservation pricing across multiple currencies and to display converted times for users in different regions. These features demonstrate handling of international users beyond simple language translation.

## Frontend / Backend Integration

Angular uses `HttpClient` to send requests to the Spring Boot reservation API and process returned room data. This demonstrates practical integration between a TypeScript SPA frontend and a Java REST backend.

## Containerization

The application includes Docker support so the full system can be packaged and executed in a consistent containerized environment.

## What I Worked On

I implemented the internationalization, multithreading, currency presentation, time-zone handling, Angular-to-Spring API integration, and containerization requirements while working within an existing full-stack hotel reservation codebase.

## Source Code

The original implementation is maintained in a private academic repository. Source access can be provided for professional review upon request.

## Author

**Nicholas Cornes**  
B.S. Software Engineering
