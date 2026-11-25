<h1 align="center">Franchise Management System</h1>
<p align="center">Java desktop application for franchise operations and business performance</p>
<p align="center"><img src="https://skillicons.dev/icons?i=java,maven" alt="Technology stack" /></p>

---

## Overview

An academic project for Object-Oriented Programming (DCC025) at UFJF. It models franchise operations with three user roles, financial indicators and structured business rules.

## Features

| Role | Responsibilities |
| --- | --- |
| Owner | Manage franchises and managers; review revenue, order counts, average order value and sales rankings. |
| Manager | Manage sales staff, orders and products; monitor inventory and unit performance. |
| Salesperson | Create and view personal orders; request changes or deletions subject to manager approval. |

## Technical highlights

- Object-oriented design: inheritance, polymorphism and interfaces.
- Java desktop graphical interface, collections and exception handling.
- File-based persistence and JUnit 5 test dependencies.
- Maven build configuration targeting Java 21.

## Getting started

Requires JDK 21 and Maven.

```bash
cd mavenproject1
mvn test
mvn compile exec:java
```

Use sample data only. Existing serialized data files should be backed up before running or modifying the application.

## Structure

- `mavenproject1/src/`: source code and project resources.
- `mavenproject1/pom.xml`: dependencies, build and test configuration.
- `mavenproject1/*.dat`: file-based application data.

## Authors

- Sara Ingrid Sousa Oliveira Afonso
- Angelica Mendes Coutinho

Academic project — UFJF. Execution and test results have not been independently verified in this documentation update.
