# GA-TL-02 - Diseño de Arquitectura de Microservicios para el PFC

Base de integración de la parte 4: revisión de diseño y entrega. Sistema de referencia: SSDC (Sistema de Selección Docente y Convocatorias, UTEQ), tomado de la entrega 1 del equipo.

## Integrantes

| Parte | Integrante |
|---|---|
| 1. Diagrama C4 nivel 3 | Coronel Gómez Khriz Alexander |
| 2. Tabla de servicios y requisitos | Silva Triviño John Jairo |
| 3. Mecanismos y ADR | Giraldo Cagua Diego José |
| 4. Revisión de diseño y entrega | Loor Mendoza Byron Daniel |

## Estado

Esta versión organiza el trabajo pendiente. No constituye una entrega final ni acredita una revisión con el docente.

- [ ] Incorporar el diseño C4 nivel 3 acordado por el equipo.
- [x] Tabla de servicios y su correspondencia con requisitos funcionales, subida en `docs/taller/tabla_servicios.tex` (integrada mediante `docs/main.tex`).
- [x] Fotografía original del bosquejo con fecha visible: `docs/diagramas/bosquejo_inicial_2026-11-27.png`. Evidencia inicial, no diseño validado.
- [ ] Preparar y realizar la revisión de diseño de 10 minutos.
- [ ] Registrar las observaciones reales y actualizar el diagrama.
- [ ] Registrar en `/docs/adr/` las decisiones que cambien la arquitectura.
- [ ] Completar y compilar el documento LaTeX con ambas tablas.
- [ ] Preparar el PDF de una página para el SGA, con datos del equipo y URL completa del repositorio en una sola línea.

## Organización prevista

- `/docs/main.tex`: documento principal de integración.
- `/docs/revision/planificacion.md`: secuencia de trabajo, dependencias y verificación.
- `/docs/revision/revision.tex`: fragmento con la base de la tabla de retroalimentación y preguntas de preparación.
- `/docs/taller/tabla_servicios.tex`: tabla de servicios y requisitos (parte 2).
- `/docs/diagramas/`: destino del diagrama editable y su exportación, cuando estén disponibles.
- `/docs/adr/`: destino de las decisiones de arquitectura que correspondan.
- `/docs/diagramas/bosquejo_inicial_2026-11-27.png`: fotografía original del bosquejo, conservada sin retoques.

Las carpetas pendientes se incorporarán al añadir sus archivos reales.

## Repositorio de entrega

El docente aclaró en el chat del curso que la entrega no tiene que ir necesariamente en el repositorio del PFC: puede ir en el repositorio de las tareas. Este es el repositorio de entrega del equipo.

https://github.com/Danxxx777/GA-TL-02-FORM-

Cierre indicado en la guía: 28 de noviembre de 2026, 23:55 (America/Guayaquil).

## Participación y asistencia

Este esqueleto fue preparado con asistencia de OpenAI Codex por solicitud de Byron Daniel Loor Mendoza. No incluye observaciones docentes, evidencias de ejecución ni aportes atribuidos a otros integrantes. Cada integrante debe realizar sus propios commits sobre su trabajo real.

## Compilación del documento de trabajo

Desde `docs/`, ejecutar `pdflatex -interaction=nonstopmode -halt-on-error main.tex` dos veces. El documento integra la tabla de servicios y la revisión; integra los mecanismos desde `taller/mecanismo.tex`. Mientras falten componentes, el PDF se identifica como borrador.

Fuente técnica del SSDC: https://github.com/Johnst2000/ta-pfc-e1-ssdc-distribuido

## Revisión del bosquejo inicial

Foto aportada por Byron, con fecha manuscrita 27-11-2026. El título manuscrito dice SSDS; el nombre acordado es SSDC. Para el diagrama final, CH-13 debe salir de la cola al consumidor de auditoría, CH-14 al consumidor de notificaciones y CH-10 a CH-14 deben representarse con líneas discontinuas. La fotografía se conserva como registro del estado inicial, sin modificarla. El dibujo se preparó tomando como apoyo una referencia visual generada con IA en este chat.
