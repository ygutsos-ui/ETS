# Proyecto: Análisis de Requisitos del Sistema WinRAR
[cite_start]**Curso:** UT2 - Análisis de requisitos de usuario [cite: 2, 3]
[cite_start]**Metodología:** Tablero Kanban para el modelado UML [cite: 17, 26]

## 📋 Tablero Kanban de Análisis

| **BACKLOG (Product Backlog)** | **ANÁLISIS Y DEFINICIÓN** | **MODELADO Y VALIDACIÓN** | **FINALIZADO (Done)** |
| :--- | :--- | :--- | :--- |
| [cite_start]**RF-01:** Soporte para formatos 7z y TAR. [cite: 19] | [cite_start]**Definición de Operaciones:** Describir precondiciones y postcondiciones. [cite: 120] | [cite_start]**Modelado de Actores:** Identificar roles y tipos de usuario. [cite: 57, 59] | [cite_start]**Identificación de Requisitos:** Diferenciación entre usuario y software. [cite: 10, 11] |
| [cite_start]**RF-02:** Integración con la nube. [cite: 48] | [cite_start]**Dependencias:** Analizar relaciones de inclusión `<<include>>`. [cite: 179, 180] | [cite_start]**Diagrama de Casos de Uso:** Representar gráficamente las interacciones. [cite: 18, 43] | [cite_start]**Gramática UML:** Establecer la simbología estándar del sistema. [cite: 36, 37] |
| [cite_start]**RNF-01:** Mejora de velocidad multihilo. [cite: 11] | [cite_start]**Escenarios Opcionales:** Definir condiciones de extensión `<<extend>>`. [cite: 394, 407] | [cite_start]**Jerarquía:** Aplicar generalización para simplificar el modelo. [cite: 75, 546] | [cite_start]**Delimitación:** Establecer el marco del sistema (System Boundary). [cite: 682] |
| [cite_start]**RF-03:** Interfaz táctil. [cite: 20] | [cite_start]**Excepciones:** Definir flujos alternativos y mensajes de error. [cite: 886] | [cite_start]**Revisiones CASE:** Validar el diseño en herramientas online. [cite: 748, 750] | [cite_start]**Priorización:** Clasificar requisitos por importancia y urgencia. [cite: 886] |

---

## 🛠️ Notas del Analista (Especificaciones UML)

* [cite_start]**Actores:** Los usuarios se representan fuera del área del sistema mediante el símbolo de "monigote"[cite: 683, 849].
* [cite_start]**Relaciones obligatorias:** Se utiliza `<<include>>` cuando un caso de uso base requiere funcionalmente de otro para completarse[cite: 179, 181].
* [cite_start]**Relaciones opcionales:** Se utiliza `<<extend>>` cuando una funcionalidad adicional solo se ejecuta si se cumple una condición específica[cite: 394, 421].
* [cite_start]**Generalización:** Se aplica tanto en actores como en casos de uso para eliminar redundancia y simplificar la jerarquía[cite: 91, 103, 603].

## 🔗 Herramientas utilizadas
* [cite_start]**Diseño:** [Diagrams.net (Draw.io)](https://app.diagrams.net/)[cite: 751, 802].
* [cite_start]**Documentación:** Estándar UML (Unified Modeling Language)[cite: 35, 36].