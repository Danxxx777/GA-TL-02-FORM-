# Planificación de la revisión y entrega del SSDC

Responsable de integración: Loor Mendoza Byron Daniel (parte 4).

## Avance de esta versión

- Documento principal `docs/main.tex` con integración de la tabla de servicios existente.
- Inclusión de mecanismos preparada para cuando su responsable publique el archivo.
- Fragmento de revisión con preguntas sobre fallos, responsabilidades, consistencia y recuperación de avisos del SSDC.
- Tabla de retroalimentación de tres columnas, vacía hasta la revisión real.

## Secuencia y dependencias

1. Antes del corte interno del viernes 27 de noviembre de 2026 a las 22:00, reunir el diagrama de Coronel y los mecanismos y ADR de Diego. La tabla de John ya está disponible.
2. Elaborar el bosquejo a mano con el equipo y guardar su fotografía sin retoques, con fecha visible, en `docs/diagramas/bosquejo_inicial_AAAA-MM-DD.jpg`. No se sustituye con una imagen generada.
3. Contrastar el diagrama con servicios, bases, RF y canales. La correspondencia de RNF depende del ADR de Diego; no se presupone resuelta.
4. Ensayar una presentación de 10 minutos: 2 para alcance y gateway, 3 para servicios y datos, 3 para canales y fallos, y 2 para decisiones y preguntas. Todos deben poder explicar el conjunto.
5. Después de la revisión docente, registrar cada observación, cambio aplicado o razón para no aplicarlo. Actualizar el diagrama y registrar un ADR si cambia la arquitectura.
6. Compilar desde un clon limpio, revisar visualmente el PDF y preparar el PDF independiente del SGA con los nombres completos del equipo y la URL completa del repositorio en una sola línea.
7. Entregar antes del sábado 28 de noviembre de 2026 a las 23:55, hora de Ecuador continental.

## Verificación antes de entregar

- [ ] Los seis microservicios del SSDC tienen base propia y ningún servicio accede a una base ajena.
- [ ] Nombres de servicios, bases y RF coinciden entre diagrama, tabla y ADR.
- [ ] API Gateway muestra enrutamiento, autenticación y limitación de solicitudes.
- [ ] Cada canal tiene tipo de comunicación, tecnología y justificación con un RNF identificado.
- [ ] Diagrama editable y exportación están en `docs/diagramas/`.
- [ ] Foto auténtica del bosquejo con fecha visible incorporada.
- [ ] Retroalimentación docente registrada y cambios contrastados con el diagrama final.
- [ ] Documento integra servicios, mecanismos y retroalimentación; no conserva avisos de borrador ni pendientes sin resolver.
- [ ] Compilación desde clon limpio y revisión visual completas.
- [ ] PDF del SGA tiene una sola página y URL completa en una línea.
- [ ] Cada integrante conserva sus aportes reales y realiza sus propios commits.
- [ ] Declaraciones de asistencia describen las herramientas y partes asistidas de cada integrante.

Esta lista se basa en la actividad compartida y el estado del equipo. La sección 8 de la guía común no está disponible en este repositorio y queda por contrastar.

## Asistencia

Base de integración y planificación preparadas con asistencia de OpenAI Codex por solicitud de Byron. No se han generado evidencias, observaciones docentes ni aportes de los demás integrantes.
