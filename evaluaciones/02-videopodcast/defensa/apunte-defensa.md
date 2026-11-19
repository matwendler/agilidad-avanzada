# Apunte para la defensa oral — Design Thinking

> ⚠️ **Generado por IA a pedido: ahorra tiempo, cuesta aprendizaje.** Es material de relectura armado desde el guion, el material crudo (`../material/`) y los apuntes de la unidad 1. La defensa pide **ampliar** y **aplicar a una situación nueva**: eso no sale de leer, sale de decirlo en voz alta. Si te queda un rato, leé la sección 6 tapando las respuestas.

Defensa: vie 27/11 o vie 04/12 · Individual · 30 pts (15 comprensión y ampliación · 10 fundamentación y aplicación · 5 claridad).

---

## 1 · El episodio en un minuto

- **Tema:** Design Thinking.
- **Enfoque:** *del post-it a producción.* Qué separa los proyectos de DT que llegan a resultados de los que se quedan en el taller.
- **Tesis:** el método está muy desarrollado para descubrir, definir y desarrollar, y muy flaco para **entregar**. Los talleres prueban bien la **deseabilidad**, pero la **factibilidad** y la **viabilidad** recién se prueban al implementar. Si el proceso termina en el taller, dos de las tres patas nunca se testean.
- **Casos:** uno que llegó (Bank of America + IDEO, *Keep the Change*), uno que no (talleres de Google según Jake Knapp → origen del design sprint) y uno de ahora (IDEO + Healthworx con ChatGPT, 2023).
- **Postura del cierre:** DT no está muerto, pero solo no alcanza. Vale cuando llega a producción. Lo usaríamos cuando (1) el problema no está claro, (2) hay usuarios a los que se puede ir a ver y (3) quien decide se compromete a estar y a implementar. Los cuidados: una métrica definida antes de empezar, y alguien de negocio y alguien técnico en la sala desde el día uno.
- **Frase del título:** «La IA no lo va a salvar: el problema nunca fue generar ideas.»

---

## 2 · Repaso conceptual (lo que te pueden pedir que amplíes)

### Qué es

Un **enfoque centrado en las personas para resolver problemas complejos**. Cruza tres lentes que tienen que cerrar a la vez (IDEO):

| Lente | Pregunta | Dueño típico |
|---|---|---|
| **Deseabilidad** | ¿A la gente le importa? | Investigación / diseño |
| **Factibilidad** | ¿Se puede construir con lo que tenemos? | Tecnología |
| **Viabilidad** | ¿Se sostiene como negocio? | Negocio |

La pregunta de fondo no es *qué podemos construir*, sino **qué deberíamos construir**.

- **HCD vs. DT:** el Human-Centered Design es el valor de fondo (empezar por las personas). El DT es la práctica: mindsets y métodos para explorar, idear, prototipar e iterar.
- **¿Método, proceso o mentalidad?** Las tres cosas. Don Norman (2013) lo reduce a cinco prácticas: cuestionar el problema planteado, explorar muchas soluciones antes de converger, observar a los usuarios, prototipar y criticar. Liedtka (HBR 2018) lo llama **«tecnología social»**: herramientas más un entendimiento de cómo trabajan las personas, que ataca los sesgos que traban la innovación (enamorarse de la primera idea, decidir por jerarquía). Lo compara con lo que fue TQM para la manufactura.

### Por qué existe: la complejidad

En problemas complejos los requerimientos no vienen dados, se descubren. Hay stakeholders con agendas distintas, causa y efecto no se ven de antemano y **lo que la gente dice difiere de lo que hace**. De ahí salen las dos apuestas del método:

1. **Divergir antes de converger** (Guilford, 1956; Laseau lo lleva al diseño en 1980). El error clásico es converger antes de tiempo.
2. **Iterar:** aprender con prototipos, no con documentos.

### El Doble Diamante (Design Council, 2003–04)

```
   DESCUBRIR  ◇  DEFINIR      DESARROLLAR  ◇  ENTREGAR
   (abrir)       (cerrar)     (abrir)         (cerrar)
   └── diamante del PROBLEMA ┘└── diamante de la SOLUCIÓN ┘
```

- El primer diamante se pregunta **cuál es el problema correcto**; el segundo, **cuál es la solución correcta**.
- **No es lineal.** El mismo Design Council dice que los equipos vuelven al inicio cuando descubren problemas de fondo. Por eso lo amplió al *Framework for Innovation* (2019) y al *Systemic Design Framework* (2021: explore, reframe, create, catalyse), pensado para desafíos sistémicos.
- **Nuestro enfoque se planta en «Entregar».** Es la fase más flaca del método y la que decide si hay resultado.

Equivalencias, por si te nombran otro modelo:

| Programa de la materia | Double Diamond | d.school (5 fases) | GV Sprint |
|---|---|---|---|
| Descubrimiento | Discover | Empathize | Lunes |
| Definición del problema | Define | Define | Lunes |
| Ideación | Develop | Ideate | Martes |
| Selección de alternativas | Develop (converge) | Ideate | Miércoles |
| Prototipado | Deliver | Prototype | Jueves |
| Evaluación | Deliver | Test | Viernes (5 clientes) |

### Mindsets (IDEO.org Design Kit)

Aprender del fracaso · Make it · Confianza creativa · Empatía · Abrazar la ambigüedad · Optimismo · Iterar, iterar, iterar.

### Service Design (Stickdorn, bibliografía obligatoria)

- **Pass the parcel:** la empresa pone el esfuerzo en el núcleo (el producto), pero el cliente lo vive filtrado por capas: trato del personal, expertise, procesos y sistemas. En el estudio de hospitales, **ninguno de los 15 factores de satisfacción tenía que ver con si el paciente se curó**.
- **Seis principios:** human-centered, collaborative, iterative, sequential, real, holistic.
  - El principio **«Real»** (prototipar en la realidad) y el **«Holistic»** (todos los stakeholders, todo el negocio) **son nuestro argumento:** un taller que no toca la operación no cumple con ninguno de los dos.
- **Experiencia del empleado:** no hay buena experiencia de cliente sobre una mala experiencia de empleado. Es la gente que tiene que operar lo que se diseña. Conecta con el caso Google: «nadie de finanzas ni de sistemas estaba en la sala».
- **Boundary objects:** personas, journeys y blueprints son objetos que cada área interpreta desde su marco y que sirven para hablar del mismo problema. Por eso alinean.

### Herramientas (las que usamos en MARQ)

| Herramienta | Para qué | Dato clave |
|---|---|---|
| **Persona** | Arquetipo basado en datos, no en supuestos | Una por arquetipo |
| **Mapa de empatía** | Piensa/siente · ve · oye · dice/hace + pains/gains | El insight aparece donde «dice» no coincide con «piensa» |
| **Customer Journey Map** | La experiencia de **un** actor paso a paso, con curva emocional | Steps → touchpoints → *moments of truth* |
| **Service Blueprint** | Journey + frontstage + backstage + procesos de soporte | Líneas de interacción, visibilidad e interacción interna; *fail points* (Shostack) |
| **How Might We** | Pasar del insight a la ideación | Sin la solución metida de contrabando en la pregunta |
| **Idea portfolio / matriz de decisión** | Converger | Si el equipo puntúa adivinando, falta información, no herramienta |
| **Malla receptora** | Feedback del test: funciona / críticas / preguntas / ideas | Insumo para la próxima iteración |

**Journey o blueprint:** el journey sirve para **entender** la experiencia; el blueprint, para **rediseñar cómo la organización la entrega**. Para nuestro enfoque (llegar a producción), el **blueprint es la herramienta del segundo diamante**: obliga a mirar procesos, sistemas y responsables. Esa es la factibilidad y la viabilidad.

**MARQ (nuestra primera instancia):** cinco técnicas ubicadas en el Doble Diamante (Personas, Mapa de empatía, Customer Journey Map, lluvia de ideas con selección y Service Blueprint), con la propuesta **Hilo y Huella** como resultado. Sirve como experiencia propia si te preguntan «¿lo aplicaste vos?».

### Design Sprint (GV, Jake Knapp)

Cinco días: lunes mapear y elegir el target · martes bocetar · miércoles decidir y storyboard · jueves prototipar («fake it») · viernes testear con 5 clientes. Es DT **con fecha de entrega y con el que decide adentro**: en el libro *Sprint* ese rol se llama el **Decider**. Ojo: la página de GV que tenemos crawleada dice solo «armar el equipo correcto».

- **Sprint 2.0** (AJ&Smart con Knapp) lo baja a 4 días.
- Límites que reporta Browser London: no cubre la factibilidad técnica, funciona con pocos participantes y necesita un facilitador estricto.

### Cómo se ubica frente a Lean Startup y Agile (pregunta de unidad cruzada)

- **DT:** ¿cuál es el problema correcto y qué solución desea la gente? Es descubrimiento.
- **Lean Startup:** ¿la hipótesis de negocio se sostiene? Build–measure–learn con MVP. Valida viabilidad.
- **Agile/Scrum:** construir de a incrementos y adaptarse. Es la entrega.
- **Lean UX** (Follett, O'Reilly 2017) es el puente: think–make–check, paralelo al build–measure–learn, más pragmático y pensado para equipos ágiles.
- **Conexión con nuestra tesis:** el DT por sí solo termina donde empiezan los otros dos. Si no hay un traspaso a Lean (validar viabilidad) y a Agile (construir), queda en post-its.

---

## 3 · Bloque por bloque: qué dijimos, por qué se sostiene y por dónde te pueden atacar

### Bloque 1 · Tema y enfoque

- **Dijimos:** DT = personas primero, con las tres lentes. Doble Diamante. Lo miramos desde la distancia entre la idea y la implementación, porque «Entregar» es lo más flaco.
- **Se sostiene en:** MIT Technology Review (2023): «*Execution has always been the sticky wicket for design thinking*». Blink UX (2025): «*Outcome matters more than output*». dxw (2024): DT «*still works… as a starting point but it's not enough*».
- **Ataque posible:** «Pero el Doble Diamante sí tiene una fase de entrega, ¿no es injusto decir que el método no la cubre?»
  → La fase existe, pero el método no te **obliga** a quedarte. Por eso se puede vender como un taller de una semana. El propio Design Council tuvo que ampliarlo (Framework for Innovation y Systemic Design) para cubrir liderazgo, conexiones y «continuar el camino», que son justamente las actividades de implementación.

### Bloque 2 · Beneficios

- **Dijimos:** reduce el riesgo de construir algo que nadie quiere. Liedtka habla de una «tecnología social» que ataca sesgos (50 proyectos en 7 años). McKinsey: +32 puntos de crecimiento de ingresos, pero es correlación y McKinsey vende diseño.
- **Condiciones que propusimos:** (1) quien decide participa del proceso, (2) se prototipa con usuarios reales, (3) hay una métrica acordada antes de empezar.
- **Precisión importante sobre McKinsey:** compara el **cuartil superior del McKinsey Design Index** con sus pares de industria: 300 empresas cotizantes, 5 años, +32 puntos de ingresos y +56 de retorno al accionista. No es «las que más invertían». El índice mide **prácticas** de diseño, no gasto. Además, McKinsey tenía una división de diseño de más de 350 personas (compró Lunar y Veryday).
- **Otras evidencias que podés sumar:**
  - Forrester para IBM (2018): ROI de 301%. **Lo encargó IBM**, sale de 4 clientes y 60 ejecutivos y se arma sobre una empresa «compuesta» modelada.
  - Design Value Index: +211% contra el S&P 500. Lo arma una consultora de diseño y compara contra el índice general, no contra competidores.
  - Meta-análisis de Nature (2024), 25 estudios: efecto positivo en aprendizaje (r = 0,436). Es educación, no empresas, y el efecto es mayor con grupos chicos y duración de 3 meses o más.
  - Micheli et al. (2019): el concepto está «*plagued by polysemy*», en riesgo de «construct collapse».
- **Ataque posible:** «Si toda la evidencia es correlacional o pagada, ¿cómo sabés que funciona?»
  → No lo sabemos en el sentido causal, y por eso no lo dijimos así. La evidencia más sólida es **cualitativa y de mecanismo** (Liedtka: qué sesgos ataca) más casos documentados con métricas propias (Kaiser, más abajo). Nuestra postura es condicional: el beneficio aparece **si** se cumplen las tres condiciones, y eso es consistente con que los estudios encuentren resultados mixtos.

### Bloque 3 · Debilidades

- **Dijimos:** la ejecución es el punto débil. Hay «teatro de innovación»: la consultora hace el taller y se va. La falla es del método y de la aplicación a la vez. No lo usaríamos con un problema ya claro (falta ejecutar) ni en problemas sistémicos grandes (salud pública, educación) que dependen de financiamiento e instituciones.
- **Debate vigente:** IDEO recortó alrededor de un tercio del personal en 2023 (Nielsen habla de 32% y de la mitad desde 2020). Fortune 2026: la facturación pasó de US$300M a menos de US$100M y cerró Múnich y Tokio. Vinsel (2017): «como la sífilis». **Nuestra posición:** está en crisis **una forma de venderlo** (el taller con post-its como producto), no los principios. Fast Company Brasil (2025): las menciones de «design thinking» en avisos de empleo cayeron (−9,1% UX/UI, −17,6% producto, −57,2% gráfico), pero «muchas empresas aún aplican los principios sin citar el término».
- **Otras críticas que conviene conocer:**

| Quién | Qué dice | Cómo se conecta con nuestra tesis |
|---|---|---|
| Don Norman 2010 → 2013 | Primero: «es un término de relaciones públicas». Después se retracta: «*really is special*» | Muestra que el debate es viejo y que hasta un crítico lo terminó defendiendo |
| Jared Spool 2017 | No hay magia: empaqueta prácticas existentes para no diseñadores | Compatible: lo valioso son las prácticas, no la marca |
| Natasha Jen 2017 | «*Design Thinking is Bullsh\*t*»: soluciones obvias, post-its, falta la crítica. «*Prove it*» | Ataca el formato taller, igual que nosotros |
| Lilly Irani 2018 | Jerarquías de trabajo: unos «guían el futuro» de otros | Conecta con el «paracaidismo» de la consultora que llega y se va |
| Marty Cagan 2019 | Ciclo de hype: después del entusiasmo viene la desilusión, igual que con Agile y Lean | Explica la caída sin decir que el método no sirve |
| Teresa Torres 2021 | «*Sticky note fatigue*»; discovery continuo, con contacto semanal con clientes | La alternativa: discovery como hábito, no como evento |

- **Ataque posible:** «Si el problema es la implementación, ¿no es un problema de gestión y no de DT?»
  → En parte sí, y por eso dijimos «las dos». Pero un método que se presenta como forma de innovar y no incluye el traspaso a operación tiene un hueco de diseño propio. El design sprint es la prueba de que se puede corregir **desde el método**: mete al que decide y pone una fecha.

### Bloque 4 · Casos

**Bank of America + IDEO, «Keep the Change» (2004–05) — el que llegó**
- **Qué aplicaron:** etnografía en Atlanta, Baltimore y San Francisco con madres baby boomer, **junto con el equipo de innovación del banco**. Insights: a muchas les costaba ahorrar, y mucha gente redondeaba al anotar sus gastos. Solución: cada compra con la débito se redondea al dólar y la diferencia va a la caja de ahorro.
- **Resultado:** Core77 (2007) habla de 2,5 millones de clientes, más de 700.000 cuentas corrientes nuevas y 1 millón de cajas de ahorro nuevas. Financial Health Network (2024): US$15.000M ahorrados por 6,6 millones de clientes.
- **Por qué llegó (nuestra lectura):** el banco estuvo en el campo, y el insight se tradujo en algo que el banco **ya sabía operar** (una regla sobre la tarjeta). Las tres lentes cerraban.
- **Flanco débil:** Core77 es un blog sin fuente primaria, y Financial Health Network no menciona a IDEO. Si te lo marcan: «es cierto, por eso citamos las dos y el caso de Columbia Business School no cargó».

**Google / Jake Knapp — el que no llegó**
- Knapp hacía talleres de DT en Google y, cosa rara, **hacía el seguimiento** de qué ideas se construían: casi ninguna. Las decisiones volvían a «*the old way*»: un experto solo armaba la idea y se la vendía casi terminada a los jefes. Fuente: MIT Technology Review (2023), que cita a Knapp.
- **Qué hizo con eso:** el design sprint de 5 días.
- **Pregunta del guion que conviene tener resuelta:** «¿El sprint resuelve el problema o lo maquilla?» Ataca dos causas: mete al que decide y obliga a testear con usuarios reales el viernes. **No** resuelve la factibilidad técnica (Browser London) ni la operación posterior: el prototipo es una fachada. Lectura honesta: acorta la distancia, no la elimina.

**IDEO + Healthworx con ChatGPT (2023) — el de ahora**
- **Qué hicieron:** un sprint de 5 semanas para un emprendimiento de salud rural. Perplexity para sintetizar social listening, y ChatGPT para generar conceptos y criticar los del equipo. También hablaron con usuarios reales.
- **Qué encontraron (según IDEO, la propia empresa):** la IA aceleró la síntesis, pero aportó poco a la innovación («variaciones de la misma idea»). La colaboración empeoró porque cada uno se fue con su asistente, y no hubo sustituto para los usuarios reales.
- **Conclusión del episodio:** la IA acelera la parte que ya era rápida (sintetizar, generar opciones) y no toca la difícil (decidir, comprometer recursos, implementar).
- **Respaldo extra:**
  - NN/g (2024 y 2026): los usuarios sintéticos son complacientes, sus insights son superficiales y hay *mode collapse* (unas 12 etiquetas contra más de 50 de los humanos). «*Research with synthetic users is still not user research*».
  - Mike Peng, CEO de IDEO (2025): la IA da resultados «*somewhat mediocre*», porque converge al promedio.
  - XJTLU / Chen (2026), 303 empresas: la innovación alta aparece solo cuando se **combinan** IA generativa y DT, no con una sola.

**Suplentes (por si te piden otro ejemplo)**
- **Kaiser Permanente, NKEplus (2009–11):** el mejor caso a favor de nuestra tesis. Rediseñaron el cambio de turno de enfermería con más de 200 horas de observación y más de 2.000 horas de pilotos, y **combinaron DT con gestión del cambio** (Lewin) para implementar. Publicaron métricas propias: el traspaso en la habitación pasó de 61% a 86% y bajó a 76% al mes 7. Muestra que la implementación necesita algo más que DT.
- **IDEO + comedores escolares de San Francisco (2013):** 10 recomendaciones en 5 meses, varias impracticables (expendedoras sin internet, normas de asbesto). El distrito terminó renovando por su cuenta más de 70 de sus 114 comedores. Deseable, no factible.
- **IDEO.org, Diva Centres (Zambia):** deseable para las adolescentes, pero no previeron el financiamiento de salud pública. La meta de 10 centros no se reportó cumplida; IDEO lo describió como «*prohibitively expensive and complicated*». Deseable, no viable.
- **GE Healthcare, Adventure Series:** Doug Dietz rediseñó la **experiencia** del resonador pediátrico sin cambiar la tecnología. Dato fino: GE dice «*substantive clinical data not available*».
- **Votación del Condado de Los Ángeles + IDEO (2020):** dispositivo muy testeado con votantes. En la primaria de 2020 fallaron los padrones electrónicos y hubo filas de más de 3 horas. El diseño del dispositivo era bueno, pero el sistema alrededor no lo era: es el argumento de Stickdorn.

### Bloque 5 · Reflexión final

- **Cuándo sí:** problema difuso, usuarios accesibles y un decisor comprometido. Si falta uno, no.
- **Cuidados:** métrica antes de empezar; negocio y tecnología en la sala desde el principio.
- **Ataque posible:** «¿No es demasiado exigente? Casi ningún proyecto cumple las tres.»
  → Justamente: si no se cumplen, conviene otra herramienta (A/B testing, Lean Startup, discovery continuo) o una versión acotada como el sprint. Usar DT sin esas condiciones es lo que produce el teatro de innovación.

---

## 4 · Cifras y su fuente (las que se dijeron o te pueden preguntar)

| Dato | Fuente | Ojo con |
|---|---|---|
| 50 proyectos en 7 años | Liedtka, HBR 2018 | Solo se leyó la intro (paywall) |
| +32 pts ingresos / +56 retorno, 300 empresas, 5 años | McKinsey 2018 vía Dezeen | Correlación; McKinsey vende diseño; cuartil superior del índice, no gasto |
| ROI 301% | Forrester, **encargado por IBM**, 2018 | Empresa compuesta modelada, 4 clientes |
| +211% vs S&P 500 | Design Value Index (DMI) vía Fortune 2017 | Contra índice general |
| r = 0,436, 25 estudios | Meta-análisis Nature 2024 | Educación, no empresa |
| IDEO −⅓ del personal; US$300M → <US$100M | Nielsen 2023 / Fortune 2026 (citando a Fast Company) | Fast Company original no cargó |
| BofA: 2,5 M clientes, 700 mil cuentas | Core77 2007 | Blog sin fuente primaria |
| BofA: US$15.000 M, 6,6 M clientes | Financial Health Network 2024 | No menciona a IDEO |
| DT en avisos: −9,1% / −17,6% / −57,2% | Fast Company Brasil 2025 | — |
| Double Diamond 2003–04 | Design Council | — |
| Divergente/convergente | Guilford 1956; Laseau 1980 | — |

---

## 5 · Los dos puntos donde te pueden agarrar

1. **El personaje.** En el video, Alexander cuenta que estuvo en IDEO en 2004, en Google con Knapp y en Healthworx en 2023, y eso es ficción. Los hechos salen de las fuentes; lo inventado es que él estuvo. Si te preguntan, decilo de frente: *«Es un recurso de formato: lo armamos como entrevista a un consultor para contar los tres casos en primera persona. Los hechos son los de las fuentes de la descripción; la trayectoria del personaje es dramatización.»* Negarlo es peor que el recurso.
2. **«¿Por qué este enfoque y no otro?»** Porque la crítica más repetida, y vigente (MIT TR 2023, dxw 2024, Blink 2025, la crisis de IDEO), es la ejecución. Además, la mayoría de los enfoques se quedan en las fases y en los casos de éxito, y la rúbrica premia originalidad y actualidad. También conecta con la IA sin hacer del episodio «otro video de IA», que la cátedra pidió evitar: la IA aparece como un caso que confirma la tesis, no como el tema.

---

## 6 · Preguntas probables (tapá la respuesta y probá)

**Comprensión y ampliación**

1. *¿Qué diferencia hay entre Design Thinking y Human-Centered Design?* → HCD es el valor (empezar por las personas); DT es la práctica (mindsets y métodos).
2. *¿Por qué dos diamantes y no uno?* → Uno para el problema y otro para la solución. Sin el primero, resolvés bien el problema equivocado.
3. *¿Qué es divergir y converger, y cuál es el error típico?* → Abrir opciones y después elegir. El error es converger antes de tiempo.
4. *¿Es lineal el proceso?* → No: «*a big mass of looping back*». El sprint lo demuestra, porque las etapas son lógicas, no cronológicas.
5. *¿Journey map o blueprint?* → Journey para entender la experiencia; blueprint para rediseñar cómo la organización la entrega (frontstage, backstage, soporte).
6. *¿Qué agrega Service Design al DT?* → Lo end-to-end, el backstage, la experiencia del empleado y los seis principios. Pass the parcel.
7. *¿Por qué decís que el taller solo prueba deseabilidad?* → En la sala hay usuarios o diseñadores, no finanzas ni sistemas. La viabilidad y la factibilidad aparecen al implementar.
8. *¿Qué es el «teatro de innovación»?* → Talleres vistosos que se saltean la síntesis, la validación y la implementación; la consultora se va antes del resultado (MIT TR 2023).

**Fundamentación**

9. *¿Hay evidencia de que funcione?* → Correlacional y en general con conflicto de interés (McKinsey, Forrester/IBM, DMI). Cualitativa con Liedtka. Casos con métricas propias, como Kaiser. Por eso nuestra postura es condicional.
10. *¿Está muerto?* → Está en crisis el formato taller como producto, no los principios (Fast Company Brasil 2025, dxw 2024, Blink 2025).
11. *¿El design sprint arregla el problema?* → Lo achica: mete al que decide y testea con usuarios reales. No cubre la factibilidad técnica ni la operación.
12. *¿La IA lo mejora?* → Acelera la síntesis y la generación, pero no reemplaza al usuario real, achata las ideas hacia el promedio y empeora la colaboración (Healthworx, NN/g, Peng). Combinadas sí suman (Chen 2026).

**Aplicación a una situación nueva** (el patrón de respuesta es siempre el mismo: ¿el problema está claro? ¿hay usuarios accesibles? ¿hay un decisor comprometido? ¿qué métrica? ¿quién de negocio y quién técnico?)

13. *Una pyme quiere digitalizar su facturación: ¿DT?* → Si el problema está claro (cumplir normativa, bajar tiempo de carga), no: es ejecución. Usaría DT solo si no se sabe por qué los empleados no adoptan el sistema actual, y ahí haría work-alongs (Stickdorn), un blueprint y una métrica de adopción.
14. *Implementar un ERP (caso Alex):* → El riesgo típico es justamente el nuestro: diseñar pantallas deseables que chocan con procesos y datos. Blueprint desde el día uno, alguien de IT y el dueño del proceso en la sala, un piloto con un área y la métrica definida antes.
15. *Una startup sin clientes todavía:* → Primer diamante con DT (entender el problema), validar la viabilidad con Lean Startup (MVP), y no gastar en un taller largo. Cuidado con Juicero: «no puede inventar clientes que no existen» (Blink).
16. *Un municipio que quiere mejorar un trámite:* → Problema sistémico, con normativa y presupuesto. DT para entender a los vecinos y a los empleados, pero con la normativa como carril del blueprint y la financiación resuelta antes: Diva Centres y los comedores de San Francisco muestran qué pasa si no.
17. *MARQ (tu caso):* → ¿Llegó «Hilo y Huella» a producción? Respondé con honestidad qué se implementó y qué no, y qué faltó según nuestras tres condiciones (¿estaba el decisor? ¿había una métrica?). Es la mejor prueba de que entendés la tesis.
18. *Te dan un problema bien definido y medible (optimizar una página de precios):* → A/B testing antes que una investigación de empatía. No todo problema necesita DT.

---

## 7 · Si tenés 5 minutos antes de entrar

- Tres lentes → el taller prueba una, la implementación prueba las otras dos.
- El Doble Diamante es fuerte para el problema y flaco para entregar.
- Tres casos: llegó (BofA: banco en el campo, solución que ya sabían operar) · no llegó (Google/Knapp → sprint) · IA (Healthworx: acelera lo fácil, no lo difícil).
- Condiciones: problema difuso, usuarios accesibles, decisor comprometido, métrica previa, negocio y tecnología en la sala.
- Personaje = dramatización, hechos = fuentes.
- La evidencia es correlacional o pagada → la postura es condicional, no absoluta.
