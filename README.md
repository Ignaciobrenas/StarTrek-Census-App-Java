# 🖖 StarTucom – Star Trek Census Application (Java OOP)

<div align="center">

![Star Trek](https://media.giphy.com/media/3ohs7KViF6rA4aan5u/giphy.gif)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Pattern-MVC-blueviolet?style=for-the-badge" alt="MVC Pattern" />
  <img src="https://img.shields.io/badge/OOP-Inheritance_%26_Polymorphism-007396?style=for-the-badge" alt="OOP" />
  <img src="https://img.shields.io/badge/Academic-1º_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

</div>

> 🎓 **Proyecto Académico:** Desarrollado como práctica de modelado de dominio y polimorfismo para el módulo **MP0485 RA7** en **STUCOM Pelai** (Barcelona), 1º Grado Superior en Desarrollo de Aplicaciones Web (DAW).

---

## Descripción del Proyecto

Aplicación en **Java** ambientada en el universo de *Star Trek* para la gestión y censo intergaláctico de diferentes especies alienígenas asociadas a la Federación Unida de Planetas. Demuestra el uso avanzado de clases abstractas, métodos polimórficos y arquitectura MVC.

---

## Arquitectura y Especies Soportadas

```
src/main/java/
├── controller/
│   └── CensusController.java     # Coordinación del censo y estadísticas demográficas
└── model/
    ├── Ser.java                  # Clase abstracta base de todas las especies
    ├── Planeta.java              # Entidad planeta y condiciones de habitabilidad
    ├── Humano.java               # Subclase: especie Humana
    ├── Vulcaniano.java           # Subclase: especie Vulcaniana (lógica y telepatía)
    ├── Klingon.java              # Subclase: especie Klingon (fuerza y honor militar)
    ├── Andoriano.java            # Subclase: especie Andoriana (antenas sensoriales)
    ├── Ferengi.java              # Subclase: especie Ferengi (normas de adquisición)
    └── Nibiriano.java            # Subclase: especie Nibiriana
```

---

## Funcionalidades

- 🪐 **Censo Poblacional por Planeta:** Asignación y recuento demográfico de habitantes por mundo.
- 👽 **Polimorfismo de Especies:** Cada subclase implementa atributos y rasgos biométricos característicos de su raza.
- 📊 **Consultas y Estadísticas:** Filtrado por planeta natal, especie y recuentos de la Federación.

---

## Compilación y Ejecución

```bash
# Compilar mediante Maven
mvn clean compile

# Ejecutar el controlador del censo
mvn exec:java -Dexec.mainClass="controller.CensusController"
```

---

## Licencia

Distribuido bajo la **Licencia MIT**.
