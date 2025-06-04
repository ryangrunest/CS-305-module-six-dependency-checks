# Dependency-Check Demo Project

This project demonstrates how to use [OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/) with a Maven-based Java application.

## Prerequisites

- Java 8 or higher
- [Maven](https://maven.apache.org/) 3.x

## Setup

1. **Clone the repository:**
2. **Run dependency check:**

`mvn verify` or `mvn org.owasp:dependency-check-maven:check`

3. **Suppressing False Positives**
Suppressions are configured in suppression.xml.
Update this file to add or remove suppressions as needed.
