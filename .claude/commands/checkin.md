---
description: Check-in semanal — revisar la semana y ajustar entrenamiento y comida
---

Haz el check-in semanal de Luis. $ARGUMENTS

## 1. Recoge la semana

Lee `CLAUDE.md`, el plan vigente, `plan/historial-de-cambios.md` y los últimos 3 resúmenes de `registros/semanas/`. Luego pregúntale, en un solo mensaje y aceptando respuestas dictadas o desordenadas:

- Peso de la semana (idealmente el promedio de varias mañanas) y cintura si toca medirla (cada 2 semanas).
- Qué sesiones hizo y cuáles se saltó. Pesos y repeticiones de los ejercicios principales, o una captura o export de su app.
- Cómo comió: días en objetivo de proteína, días que se pasó o se quedó corto.
- Sueño promedio, energía y estrés del 1 al 10.
- Dolores o molestias, y en qué ejercicio.

Si pega datos de una app o una lista larga, pásalos tú a `registros/entrenos.csv` y `registros/medidas.csv`.

## 2. Analiza

- **Peso:** compara el promedio con el de las semanas anteriores. ¿Va en 0.25–0.5 lb por semana?
- **Cintura:** ¿sube más rápido que el peso? Es la señal de que el superávit es demasiado.
- **Fuerza:** por ejercicio principal, ¿subió peso o repeticiones? Marca los que llevan 2 semanas o más estancados.
- **Recuperación:** con sueño, estrés y molestias, ¿hace falta un deload antes de lo previsto?
- **Adherencia:** si falló sesiones o comida, busca la causa real (horario, cansancio, logística) y no solo "esfuérzate más".

## 3. Ajusta

Aplica las reglas de `CLAUDE.md` y de `plan/progresion.md`:

- Pesos objetivo de la próxima semana por ejercicio principal.
- Calorías: igual, +150–200 o −150–200 kcal según el peso y la cintura. Dilo en comida concreta ("agrega un batido de proteína con avena después del gym"), no solo en números.
- Si toca deload o rotación de un accesorio según el calendario, avísale.
- Cambios grandes (split o ejercicio principal): propónselos y espera su visto bueno.

## 4. Guarda

- Escribe `registros/semanas/AAAA-MM-DD.md` con: datos de la semana, qué salió bien, qué ajustar y objetivos de la próxima semana.
- Si cambiaste el plan, actualiza el archivo correspondiente y anótalo en `plan/historial-de-cambios.md`.
- Actualiza `perfil/perfil.md` si aprendiste algo duradero (nuevo horario, una molestia nueva, una comida que dejó).

## 5. Responde

Máximo una pantalla: cómo fue la semana en 2–3 líneas, los 3 ajustes más importantes y los pesos objetivo de la próxima semana. Sé honesto si la semana fue floja, pero con un plan concreto.
