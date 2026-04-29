# Tablero Kanban - Proyecto RRHH_GPRH_DID

## Columna: Backlog

A continuación se detallan las Historias de Usuario definidas para la fase de análisis de la aplicación de Recursos Humanos.

### Gestión de Direcciones para Contactos Externos
**Enunciado:** como analista solicito que el sistema habilite la introducción de una dirección completa (calle, número, piso, puerta y código postal) únicamente si el contacto no trabaja en la empresa 
PARA evitar el almacenamiento de datos redundantes de empleados internos.

**Criterios de Aceptación:**
* El sistema debe verificar si el contacto pertenece a la plantilla de la empresa antes de mostrar los campos de dirección.
* Los campos de dirección (calle, número, piso, puerta y código postal) solo aparecerán si la condición de "no empleado" se cumple.

---

### Formato de Texto en Anotaciones del Diario
**Enunciado:** como analista solicito que el usuario tenga la opción de aplicar formato al texto de una nota del diario PARA permitir una mejor organización visual y jerarquización de la información personal de los empleados.

**Criterios de Aceptación:**
* Al introducir el texto de una nota, deben aparecer herramientas de edición (negrita, cursiva, etc.) como una opción adicional.
* La fecha y el texto base de la nota siguen siendo campos de carácter obligatorio para poder guardar la entrada.

---

Justificación Obligatoria en Denegación de Excedencias
**Enunciado:** como analista solicito que sea obligatorio introducir una justificación por parte del responsable administrativo al denegar una solicitud de excedencia para garantizar la transparencia y claridad en las resoluciones de trámites de RRHH.

**Criterios de Aceptación:**
* Si el estado de la resolución de la excedencia es "Denegada", el sistema debe bloquear el envío si el campo de justificación está vacío.
* En caso de que la solicitud sea "Aceptada", el sistema no requerirá ninguna justificación por parte del administrativo.

---
