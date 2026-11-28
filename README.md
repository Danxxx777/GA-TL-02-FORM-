# GA-TL-02 - Diseño de Arquitectura de Microservicios para el PFC

Sistema de Selección Docente y Convocatorias (SSDC) de la Universidad Técnica Estatal de Quevedo. Taller grupal de la asignatura Aplicaciones Distribuidas.

## Integrantes

- Coronel Gómez Khriz Alexander: diagrama C4 nivel 3.
- Silva Triviño John Jairo: tabla de servicios y requisitos.
- Giraldo Cagua Diego José: mecanismos de comunicación y ADR.
- Loor Mendoza Byron Daniel: revisión de diseño e integración de la entrega.

## Documentación

- [Documento LaTeX](docs/main.tex) y [PDF del taller](docs/main.pdf).
- [Tabla de servicios y requisitos](docs/taller/tabla_servicios.tex).
- [Mecanismos de comunicación](docs/taller/mecanismo.tex).
- [Tabla de retroalimentación](docs/revision/revision.tex).
- [Diagramas y fotografía del bosquejo inicial](docs/diagramas/).
- [Registros de decisiones de arquitectura](docs/adr/).

## Compilación

Desde la carpeta `docs/`, ejecutar dos veces:

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

## Proyecto de referencia

[Entrega 1 del PFC - SSDC](https://github.com/Johnst2000/ta-pfc-e1-ssdc-distribuido).
