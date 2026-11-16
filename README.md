# Agilidad Avanzada — UTN FRRe, 4to nivel, 2026

Repositorio de material de la asignatura electiva **Agilidad Avanzada** (Ingeniería en Sistemas de Información, UTN Facultad Regional Resistencia). 2º cuatrimestre 2026.

## Estructura

```
.
├── programa/          Programa analítico oficial (PDF + resumen navegable)
├── evaluaciones/      Las dos instancias sumativas: consigna, rúbrica, plan
├── actividades/       Talleres, salidas y prácticas, una carpeta por actividad
├── unidades/          Apuntes por unidad temática
│   ├── 01-design-thinking/         ✅ con material
│   ├── 02-lean-startup/            ⏳
│   ├── 03-evolucion-agilidad/      ⏳
│   ├── 04-peopleware-management-3-0/ ⏳
│   ├── 05-product-owner/           ⏳
│   └── 06-agilidad-vida-profesional/ ⏳
└── recursos/
    ├── libros/            PDFs de la bibliografía obligatoria
    ├── lecturas/          Lecturas recomendadas (local, no se publica)
    ├── fuentes-web/       Sitios crawleados, uno por fuente
    ├── transcripciones/   Transcripciones de videos
    └── enlaces.md         Índice maestro de enlaces y estado de crawling
```

## Por dónde empezar

| Quiero… | Ir a |
|---------|------|
| Ver de qué se trata la materia, cómo se aprueba | [`programa/README.md`](programa/README.md) |
| **Trabajar en la segunda instancia (videopodcast, entrega 25/11)** | [`evaluaciones/02-videopodcast/`](evaluaciones/02-videopodcast/) |
| Ver la primera instancia (MARQ, ✅ aprobada) | [`evaluaciones/01-design-thinking-marq/`](evaluaciones/01-design-thinking-marq/) |
| Estudiar Design Thinking | [`unidades/01-design-thinking/`](unidades/01-design-thinking/) |
| Preparar la primera reunión del proyecto de consultoría | [`unidades/01-design-thinking/proyecto-consultoria/`](unidades/01-design-thinking/proyecto-consultoria/) |
| Prepararme para la entrevista con **Estudio MARQ** (vie 04/09) | [`actividades/2026-09-04-entrevista-estudio-marq/`](actividades/2026-09-04-entrevista-estudio-marq/) |
| Buscar un método concreto (persona, journey map, HMW…) | [`recursos/fuentes-web/tisdd-00-indice-de-metodos.md`](recursos/fuentes-web/tisdd-00-indice-de-metodos.md) |
| Ver todos los enlaces de la cátedra y su estado | [`recursos/enlaces.md`](recursos/enlaces.md) |

## Unidad 1 — Design Thinking

| Tema | Apunte |
|------|--------|
| ¿Qué es Design Thinking? El diseño y la gestión de la complejidad | [01](unidades/01-design-thinking/01-que-es-design-thinking.md) |
| El Proceso de Design Thinking | [02](unidades/01-design-thinking/02-proceso-design-thinking.md) |
| Técnicas y Herramientas: Mapa de empatía, Service Blueprint, Customer Journey Map | [03](unidades/01-design-thinking/03-tecnicas-y-herramientas.md) |
| Services Design Thinking | [04](unidades/01-design-thinking/04-service-design-thinking.md) |
| Proyecto de consultoría — primera reunión | [carpeta](unidades/01-design-thinking/proyecto-consultoria/) |

### Bibliografía obligatoria (Unidad 1)

- **Mark Stickdorn et al. — *This is Service Design Doing*** — atraviesa los 4 temas
- **George Anderson — *Design Thinking for Tech*** — marcado `[OBLIGATORIO]` por la cátedra
- **James Kalbach — *Mapping Experiences*** — Parte 3, para los diagramas

PDFs en [`recursos/libros/`](recursos/libros/), salvo Kalbach (86 MB), que no se versiona: está en el Drive de la cátedra. El mapa de qué páginas leer para cada tema está en el [README de la unidad](unidades/01-design-thinking/README.md).

## Fuentes web crawleadas

20 archivos en [`recursos/fuentes-web/`](recursos/fuentes-web/), cada uno con front-matter que indica URL de origen, unidad y fecha de crawl:

- **This is Service Design Doing** — índice de los 56 métodos + 12 fichas completas
- **IDEO** — design thinking, las 7 fases del proceso, la lista completa de resources
- **IDEO.org Design Kit** — 7 mindsets + métodos de las 3 fases
- **Design Council** — Double Diamond, Framework for Innovation, el debate sobre su vigencia
- **GV** — Design Sprint de 5 días, día por día
- **UXArmy** — estado del design thinking en 2026, casos y críticas
- **Design Thinking Toolkit** — Facilitation 101
- **LUMA Institute** — Interviewing

⚠️ Una sola fuente no se pudo crawlear: el artículo de Medium del Design Council devuelve **HTTP 403** a herramientas automáticas. Su contenido está reconstruido desde las páginas oficiales del Design Council en [`design-council-double-diamond.md`](recursos/fuentes-web/design-council-double-diamond.md); para leer el original hay que abrirlo a mano en el navegador.

## Convenciones

- Cada archivo de `recursos/fuentes-web/` es **contenido crawleado**, con su URL de origen en el front-matter. No editarlos con opiniones propias: los apuntes van en `unidades/`.
- Los apuntes de `unidades/` **sintetizan y enlazan**; no duplican el material fuente.
- El repo es **público**: nada de datos de clientes ni transcripciones. Lo privado va en carpetas `privado/` (ignoradas) o en el repo del equipo de MARQ.
- Todo enlace nuevo de la cátedra se registra en [`recursos/enlaces.md`](recursos/enlaces.md) con su estado de crawling.
