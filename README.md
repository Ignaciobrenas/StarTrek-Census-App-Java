Star Trek Census Application (Java OOP)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/OOP-Polymorphism_%26_Inheritance-007396?style=for-the-badge" alt="OOP" />
  <img src="https://img.shields.io/badge/Theme-Sci--Fi_Simulation-047857?style=for-the-badge" alt="Simulation" />
  <img src="https://img.shields.io/badge/Academic-1Âº_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

 **Academic Project Notice:** Developed as an academic practical project for the **1st year of Web Application Development (DAW)** at **STUCOM Pelai** (Barcelona) within the Object-Oriented Programming module (MP0485).

---

## Overview / DescripciÃ³n General

### English
A themed planetary census application developed in **Java** that simulates the demographic registration and management of sentient galactic species across various planets in the Star Trek universe. The project emphasizes advanced OOP concepts: abstract classes, inheritance trees, method overriding, and dynamic collections.

### EspaÃ±ol
AplicaciÃ³n de censo planetario desarrollada en **Java** que simula el registro y control demogrÃ¡fico de diferentes especies galÃ¡cticas en planetas del universo Star Trek. El proyecto pone en prÃ¡ctica los conceptos nucleares de la POO: clases abstractas, jerarquÃ­as de herencia, polimorfismo y manejo dinÃ¡mico de colecciones.

---

## ðŸŒŒ Domain Model & Alien Species

- **Ser.java (Abstract Base Class):** Base definition for any galactic being (name, age, species, homeworld, traits).
- **Species Subclasses:**
  - Humano.java: Adaptable beings with civilian identifiers.
  - Klingon.java: Warrior caste attributes, honor code, and battle status.
  - Ferengi.java: Latinum wealth tracking and business negotiations.
  - Andoriano.java: Cold resistance traits and clan lineage.
  - Nibiriano.java: Indigenous planetary traits.
- **Planeta.java:** Aggregates inhabitant populations and calculates species ratios.
- **CensusController.java:** Coordinates census registration, demographic queries, and statistical reports.

---

##  How to Run

`ash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.mycompany.starstucom.CensusController"
`

---

## ðŸ“„ License

Distributed under the **MIT License**.
