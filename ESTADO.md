# Estado de la materia

Última actualización: <fecha>

## Evaluación

Estos tres campos los llena el usuario cuando arranca la materia. `simulacro-examen` los
corrige cuando infiere el formato y el orden desde los parciales viejos.

- Formato de examen:
- Fechas:
- Qué orden de aprendizaje mide (recordar / aplicar / analizar / evaluar):

## Temas

Esta tabla y la línea de arriba las escribe el cierre de `sesion-larga`, que es el único
lugar que las toca: un solo escritor por fila evita que dos sesiones dejen dos versiones
del mismo tema. Una sesión corta no la actualiza.

| Tema | Peldaño (1-3) | Mapa | Mazo | Última pasada | Próxima acción |
|---|---|---|---|---|---|
|  |  |  |  |  |  |

`Peldaño` es el de `ladder-method` y va vacío si el tema nunca pasó por ahí. `Mapa` y `Mazo`
llevan la ruta del archivo —`mapas/<tema>.mmd`, `mazos/<tema>.tsv`— o quedan vacíos.

## Presupuesto de flashcards

Tarjetas activas: 0 / 150
El segundo número es la cuota semanal asignada a esta materia. El tope de 100 a 150 por
semana es del usuario, no de la materia: si hay tres materias con mazo, bajá los tres
denominadores hasta que sumen 150. Si se pasa de la cuota, el problema es el encoding, no la
falta de tarjetas.

## Cuello de botella actual

<del último `diagnostico-sistema`: los cinco puntajes por dominio, el total sobre 100, cuál
es el cuello de botella y qué intervención se eligió>
