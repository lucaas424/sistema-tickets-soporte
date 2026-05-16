# Sistema de Gestión de Tickets de Soporte Técnico

## Descripción

Este repositorio contiene la documentación de análisis, modelado y diseño de una solución CRUD para la gestión de tickets de soporte técnico en una PyME.

El sistema propuesto permite centralizar las solicitudes de soporte interno, facilitando el registro, consulta, asignación, seguimiento y cierre de tickets. La solución busca reemplazar métodos informales como correos, mensajes o planillas, mejorando la trazabilidad, el control y la organización del área de soporte.

## Objetivo del sistema

El objetivo principal del sistema es permitir que una PyME registre, organice y controle las solicitudes de soporte técnico realizadas por sus usuarios internos.

El sistema permite:

- Registrar tickets de soporte.
- Consultar tickets existentes.
- Editar información de tickets.
- Asignar tickets a técnicos.
- Actualizar el estado de los tickets.
- Agregar comentarios de seguimiento.
- Administrar usuarios, categorías y prioridades.
- Generar reportes básicos de gestión.

## Problema detectado

Muchas PyMEs gestionan sus solicitudes técnicas mediante canales dispersos, como correos electrónicos, mensajes instantáneos, llamadas telefónicas o planillas compartidas.

Esto puede generar:

- Pérdida de solicitudes.
- Tickets duplicados.
- Falta de seguimiento.
- Dificultad para asignar responsables.
- Ausencia de historial.
- Poca visibilidad para la gerencia.
- Problemas para priorizar solicitudes importantes.

## Solución propuesta

Se propone una aplicación web interna para gestionar tickets de soporte técnico de forma centralizada.

Cada ticket contará con:

- Usuario solicitante.
- Título.
- Descripción.
- Categoría.
- Prioridad.
- Estado.
- Técnico asignado.
- Comentarios de seguimiento.
- Fecha de creación.
- Fecha de cierre, si corresponde.

## Actores principales

Los actores identificados son:

- Usuario solicitante.
- Técnico de soporte.
- Administrador.
- Gerencia.
- Sistema de notificaciones.

## Funcionalidades principales

- Inicio de sesión.
- Registro de tickets.
- Consulta de tickets.
- Edición de tickets.
- Asignación de técnicos.
- Actualización de estado.
- Registro de comentarios.
- Administración de usuarios.
- Administración de categorías.
- Administración de prioridades.
- Generación de reportes.

## Documentación incluida

El repositorio incluye:

- Documento SRS en formato PDF.
- Diagrama de Contexto.
- DFD Nivel 1.
- Diagrama Entidad-Relación.
- Diagrama de Casos de Uso.
- Diccionario de Datos.
- Matriz de trazabilidad.
- Balanceo entre modelos.
- Mockups de interfaz.
- Código fuente editable de diagramas.

## Diagramas incluidos

Los diagramas principales del sistema son:

- Diagrama de Contexto.
- Diagrama de Flujo de Datos Nivel 1.
- Diagrama Entidad-Relación.
- Diagrama de Casos de Uso.

Estos diagramas permiten representar el ambiente del sistema, los procesos internos, la estructura lógica de los datos y la interacción entre actores y funcionalidades.

## Mockups incluidos

Se incluyen los siguientes mockups de interfaz:

- Inicio de sesión.
- Dashboard principal.
- Listado de tickets.
- Formulario de nuevo ticket.
- Detalle y edición de ticket.
- Reportes.

## Tecnologías sugeridas para una implementación

La solución fue pensada para poder implementarse con tecnologías simples y adecuadas para una aplicación web CRUD:

- Python.
- Flask.
- SQLite.
- SQLAlchemy.
- HTML.
- CSS.
- JavaScript.
- Flask-Login.
- Postman.

## Estado del proyecto

El proyecto se encuentra en etapa de análisis, documentación y diseño.

La documentación generada permite contar con una base sólida para una futura implementación del sistema.
