# 🏥 Arquitectura de Referencia y LPS: Sistema de Gestión Clínica

Este repositorio contiene el diseño, modelado y especificación arquitectónica de una **Línea de Productos de Software (LPS)** orientada al dominio de la gestión clínica en Ecuador. 

El proyecto demuestra la transición desde el análisis de requerimientos de negocio (Comunalidad y Variabilidad) hasta la implementación de mecanismos de variación arquitectónica utilizando el **Modelo C4** y **FeatureIDE**.

## 📑 Estructura del Repositorio

El repositorio está organizado según los artefactos clave del ciclo de vida de la Ingeniería de Líneas de Productos:

* 📁 **`/feature-model`**: Contiene el archivo `model.xml` con el árbol de características (Feature Model) en notación FODA y las restricciones cruzadas (Cross-Tree Constraints) del dominio clínico.
* 📁 **`/architecture`**: Incluye los diagramas de arquitectura basados en el modelo C4 (Contexto Nivel 1 y Contenedores Nivel 2), detallando la topología del sistema y la ubicación física de los Puntos de Variación (VPs).
* 📁 **`/configs`**: Almacena las configuraciones validadas (`.xml`) de los 3 productos derivados listos para ser importados en FeatureIDE:
  * 🦷 `DentalSoft.xml` (Clínica Odontológica)
  * 🧠 `PsicoSoft.xml` (Centro de Psicología)
  * 👶 `MedicareGeneral.xml` (Medicina General / Familiar)
* 📁 **`/docs`**: Contiene el informe final del proyecto (`informe.pdf`) redactado bajo el formato IEEE, que incluye el Análisis de Dominio (CVA), el Configuration Knowledge y el Análisis de Retorno de Inversión (ROI).

## 🛠️ Herramientas y Tecnologías Modeladas

* **Modelado de Variabilidad:** FeatureIDE (Eclipse/VS Code plugin).
* **Diseño Arquitectónico:** Modelo C4 y Mermaid.js.
* **Patrones de Variabilidad Proyectados:** Inyección de Dependencias (Load-time), Patrón Strategy, Patrón Template Method (Compile-time) y Feature Flags (Runtime) orientados a un stack de **Spring Boot & React**.

## 🚀 Cómo visualizar el proyecto

1. **Documentación:** Para entender la justificación de negocio, el diccionario de características y los *binding times*, revisa el archivo ubicado en `/docs/informe.pdf`.
2. **Modelo de Características:** Puedes importar la carpeta raíz en un entorno IDE (como Eclipse) que tenga instalado el plugin **FeatureIDE** para visualizar interactivamente el árbol estructural y validar los productos derivados en la carpeta `/configs`.

---
**Autores:**
* Lara Cruz, Steven Ismael
* *[Añade a tus compañeros aquí si es un trabajo grupal]*

*Desarrollado como proyecto integrador de Arquitectura y Líneas de Productos de Software - 2026.*
