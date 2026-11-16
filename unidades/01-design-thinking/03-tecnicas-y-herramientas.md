# 3. Técnicas y Herramientas: Mapa de Empatía, Customer Journey Map, Service Blueprint

> **Bibliografía obligatoria**
> - *James Kalbach — Mapping Experiences* (PDF en el Drive de la cátedra, no versionado) — **Parte 3** (cap. 9 Service Blueprints, 10 Customer Journey Maps, 11 Experience Maps, 12 Mental Model Diagrams, 13 Spatial Maps & Ecosystem Models). Páginas del libro 227–348 ≈ **pp. 250–371 del PDF**
> - `recursos/libros/Mark Stickdorn - This is Service Design-Doing.pdf` — **pp. 81–155 del PDF** (cap. 3, "Basic Service Design Tools")
>
> **Fuentes web crawleadas:** [Creating personas](../../recursos/fuentes-web/tisdd-creating-personas.md) · [Mapping journeys](../../recursos/fuentes-web/tisdd-mapping-journeys.md) · [Mapping systems](../../recursos/fuentes-web/tisdd-mapping-systems.md)

---

## Mapa de ubicación en el libro de Stickdorn (cap. 3)

| Herramienta | Página del PDF |
|-------------|----------------|
| Personas | ~88 |
| Journey maps | ~98–118 |
| Service blueprints | ~118–128 |
| System maps (stakeholder / value network / ecosystem) | ~124–133 |
| Prototipos y fidelidad | ~138–150 |
| Physical evidence | ~155 |

---

## Alignment diagrams (Kalbach): el concepto paraguas

Kalbach agrupa todos estos diagramas bajo **alignment diagrams**: visualizaciones que **alinean la experiencia de una persona con los procesos de una organización** en un mismo artefacto. Su tesis — *"designing to align, aligning to design"* — es que el valor del mapa no está en el dibujo sino en la conversación alineadora que produce.

Su Parte 3 clasifica los tipos:

| Diagrama | Foco | Perspectiva |
|----------|------|-------------|
| **Service Blueprint** | Servicio + procesos internos que lo sostienen | Organización ↔ cliente |
| **Customer Journey Map** | Recorrido del cliente con una organización | Cliente |
| **Experience Map** | Experiencia humana en un dominio, sin atarse a una marca | Persona |
| **Mental Model Diagram** | Motivaciones y tareas mentales | Persona (cognitiva) |
| **Spatial / Ecosystem Map** | Relaciones entre actores y elementos del sistema | Sistema |

**Regla de elección:** no hay one-size-fits-all. Se elige el diagrama según qué decisión hay que tomar.

---

## 1. Mapa de Empatía

Herramienta de síntesis rápida que organiza lo observado sobre una persona en cuadrantes. Sirve para pasar de datos de investigación a entendimiento compartido antes de construir personas o journeys.

### Cuadrantes clásicos

```
        ┌──────────────────┬──────────────────┐
        │   ¿Qué PIENSA    │   ¿Qué VE?       │
        │    y SIENTE?     │                  │
        ├──────────────────┼──────────────────┤
        │   ¿Qué OYE?      │   ¿Qué DICE      │
        │                  │    y HACE?       │
        └──────────────────┴──────────────────┘
        ┌──────────────────┬──────────────────┐
        │     PAINS        │      GAINS       │
        │  (dolores,       │  (deseos,        │
        │   miedos,        │   necesidades,   │
        │   frustraciones) │   medidas de     │
        │                  │   éxito)         │
        └──────────────────┴──────────────────┘
```

| Cuadrante | Qué se registra |
|-----------|-----------------|
| **Piensa y siente** | Lo que realmente le importa, preocupaciones, aspiraciones. Lo no dicho |
| **Ve** | Su entorno, qué ofrece el mercado, qué hacen sus pares |
| **Oye** | Qué le dicen amigos, jefe, influencers; qué canales lo influyen |
| **Dice y hace** | Comportamiento observado en público; actitud hacia otros |
| **Pains** | Frustraciones, obstáculos, riesgos que teme |
| **Gains** | Qué quiere lograr, cómo mide el éxito, qué lo haría cambiar |

### Cómo usarlo bien

- **Llenarlo con datos, no con supuestos.** Un mapa de empatía sin investigación detrás es una fantasía compartida.
- La tensión más productiva es entre **"dice y hace"** y **"piensa y siente"**: cuando no coinciden, ahí hay un insight.
- Del mapa salen directamente los **key insights** con la fórmula *"[Persona] hace [X] porque [necesidad], pero [fricción]"*.
- Se hace por persona/arquetipo, no por "el usuario" en abstracto.

### Herramienta hermana: Malla Receptora de Información (Feedback Capture Grid)

El programa la lista explícitamente. Es la contraparte del mapa de empatía **para la fase de evaluación**: se usa al testear un prototipo y organiza el feedback en cuatro cuadrantes:

| ➕ Lo que funciona | ➖ Críticas constructivas |
|---|---|
| **❓ Preguntas nuevas** | **💡 Ideas nuevas** |

Cada observación del test se pega en el cuadrante que corresponde. Evita el feedback difuso ("estuvo bien") y produce un input directo para la siguiente iteración.

---

## 2. Customer Journey Map

Visualiza la experiencia de **un actor principal** como secuencia de pasos en el tiempo. Se diferencia del blueprint y del mapa de procesos porque su foco es la **experiencia humana**, no el proceso interno.

> "Journey maps that are just built on our assumptions can be very misleading."

### Anatomía (Stickdorn, cap. 3)

| Elemento | Descripción |
|----------|-------------|
| **A — Main actor** | Siempre uno solo, representado por una persona. Algunos mapas comparan perspectivas (cliente vs. empleado) |
| **B — Stages** | Fases principales de la experiencia (p. ej. reconocimiento de la necesidad, búsqueda de información, evaluación de alternativas, decisión de compra, comportamiento post-compra). Estructuran el mapa y definen su escala |
| **C — Steps** | Cada experiencia concreta del actor: interacción con una persona, una máquina o una interfaz; también actividades como caminar o esperar |
| **D — Storyboards** | Ilustraciones, fotos, screenshots o sketches por paso. Aumentan la empatía y aceleran la navegación del mapa |
| **E — Emotional journey** | Curva de satisfacción por paso, típicamente de −2 (muy negativo) a +2 (muy positivo). Revela visualmente los problemas |
| **F — Channels** | Medio de comunicación en cada paso (presencial, web, app, TV, gráfica). Permite entender la experiencia cross-channel |
| **G — Stakeholders** | Quién interviene o es responsable de cada paso. Identifica actores clave para research, prototipado e implementación |

Lanes opcionales adicionales: procesos backstage, escenarios "What if?", dramatic arc, sistemas técnicos.

### Tipos

| Tipo | Qué muestra |
|------|-------------|
| **Current-state** | La experiencia como es hoy → pain points |
| **Future-state** | La experiencia deseada → fuente de ideas |
| **Experience-centered** | La experiencia global desde la perspectiva del cliente (p. ej. mudarse de departamento) |
| **Product-centered** | Solo touchpoints: la interacción entre el cliente y un producto/servicio/marca |

### Escala y alcance

De **10 minutos a 10 años**. Normalmente hacen falta varios mapas para una misma experiencia: uno de alto nivel end-to-end, y otros de detalle.

### Reglas de construcción

1. Un mapa = **una experiencia sin ramificaciones**. Las rutas alternativas van en mapas separados.
2. Nivel de detalle consistente.
3. Anclar cada paso a **first-level data**: citas, fotos, screenshots.
4. Iterar con clientes reales o frontline antes de dar el mapa por bueno.
5. Storyboard y curva emocional se consideran **elementos esenciales**, no adornos.

### Pasos / touchpoints / moments of truth

No todos los pasos son iguales: **todos** son steps; los que implican interacción con la organización son **touchpoints**; los que definen la percepción global del servicio son **moments of truth**. La curva emocional ayuda a detectarlos.

---

## 3. Service Blueprint

> "Service blueprints can be understood as an extension of journey maps."

Conecta la experiencia del cliente con los **procesos de empleados frontstage y backstage** y con los **procesos de soporte**. Muestra relaciones y dependencias: cómo las acciones del cliente disparan procesos internos y cómo los procesos internos disparan actividades del cliente.

### Definiciones

- **Frontstage:** personas y procesos con los que el usuario tiene contacto directo.
- **Backstage:** personas y procesos invisibles para el usuario.
- **Support processes:** actividades ejecutadas por el resto de la organización o por partners externos.

### Anatomía por carriles y líneas

```
┌───────────────────────────────────────────────────┐
│  A  Physical evidences                            │
├───────────────────────────────────────────────────┤
│  B  Customer actions                              │
╞═══ C  LINE OF INTERACTION ════════════════════════╡
│  D  Frontstage actions                            │
╞═══ E  LINE OF VISIBILITY ═════════════════════════╡
│  F  Backstage actions                             │
╞═══ G  LINE OF INTERNAL INTERACTIONS ══════════════╡
│  H  Support processes                             │
├───────────────────────────────────────────────────┤
│  I  Perspectivas / carriles custom                │
└───────────────────────────────────────────────────┘
```

| Elemento | Descripción |
|----------|-------------|
| **A — Physical evidences** | Objetos físicos con los que el cliente entra en contacto y que se pueden diseñar. También mensajes por canales no físicos (email, SMS, IVR) |
| **B — Customer actions** | Qué hace el cliente en cada paso del journey. Una acción puede incluir varios physical evidences y conectarse con interacciones frontstage o backstage |
| **C — Line of interaction** | Divide acciones del cliente de interacciones frontstage. Si el cliente interactúa con un empleado de frontline, el blueprint muestra una conexión que cruza esta línea |
| **D — Frontstage actions** | Actividades de empleados de frontline **visibles** para el cliente. Se pueden abrir en swimlanes por empleado |
| **E — Line of visibility** | Separa acciones frontstage de backstage del mismo empleado de frontline. Si el empleado "va atrás", lo que hace se muestra debajo de esta línea |
| **F — Backstage actions** | Actividades de empleados de frontline **no visibles** para el cliente |
| **G — Line of internal interactions** | Marca el límite con el resto de la organización |
| **H — Support processes** | Actividades del resto de la organización o de partners externos. Pueden disparar o ser disparadas por acciones del cliente, frontstage o backstage |
| **I — Custom** | Carriles adicionales según el proyecto: frontend/backend digital, sistemas técnicos, reglas y normativa aplicable, línea explícita de interacciones externas |

### Cuándo usar blueprint y no journey map

| Usá **journey map** si… | Usá **blueprint** si… |
|---|---|
| Querés entender y comunicar la experiencia | Querés rediseñar cómo la organización entrega esa experiencia |
| La audiencia es transversal / no técnica | Necesitás asignar responsabilidades por área |
| Estás en descubrimiento o definición | Estás en implementación y hay dependencias entre áreas |
| El problema es de percepción y emoción | El problema es de proceso, handoff o fail point |

Kalbach agrega que el blueprint tiene **fail points** (puntos donde el servicio se rompe o se vuelve inconsistente), heredados del trabajo original de **Lynn Shostack**, y luego formalizados por **Mary Jo Bitner** y colegas.

---

## 4. System Maps (complemento)

Término paraguas para **stakeholder maps**, **value network maps** y **ecosystem maps**. Responden a "¿quién está involucrado y cómo se relacionan?", que el journey map no responde.

Ver ficha completa: [Mapping systems](../../recursos/fuentes-web/tisdd-mapping-systems.md).

---

## Cómo se encadenan las herramientas

```
Investigación (entrevistas, observación)
        ↓
Research wall  →  Mapa de empatía
        ↓
Personas  ←→  Key insights
        ↓
Customer Journey Map (current-state)  ←→  System map
        ↓
Service Blueprint  (cómo la organización sostiene ese journey)
        ↓
Journey Map (future-state)  →  ideas  →  prototipos
        ↓
Malla receptora de información (feedback del test)  →  iterar
```
