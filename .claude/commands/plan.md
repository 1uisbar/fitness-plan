---
description: Crear (o rehacer) el plan de entrenamiento y nutrición a partir del perfil
---

Crea el plan completo de Luis. $ARGUMENTS

## 1. Revisa la base

- Lee `CLAUDE.md`, `perfil/perfil.md`, `plan/historial-de-cambios.md` y los registros que haya.
- Si `perfil/perfil.md` no existe o le faltan los bloques de metas, limitaciones u horario, detente y dile que primero corra `/entrevista`.
- Si hay datos pendientes que cambian el plan (por ejemplo, el equipo del gym), pregúntalos antes de seguir.

## 2. Elige el split

1. Construye una tabla con las 4 opciones de split de `CLAUDE.md` evaluadas contra su perfil: series semanales por músculo prioritario, frecuencia, minutos por sesión, encaje con su horario y riesgo con sus limitaciones.
2. Recomienda **una** y explica por qué en 3–5 líneas. Deja las otras dos mejores como alternativas, con una línea cada una sobre cuándo convendrían.
3. Pregúntale si está de acuerdo antes de escribir la rutina. Si elige otra, úsala.

## 3. Escribe `plan/rutina.md`

- Distribución semanal: qué día es cada sesión y qué va los días libres (cardio suave o descanso), alineado con su horario de trabajo.
- Por sesión: una tabla con ejercicio, series, rango de repeticiones, RIR, descanso y una nota corta de técnica o seguridad.
- Máximo 5–6 ejercicios por sesión. Compuestos primero, aislamiento al final. Superseries de brazos si ahorran tiempo.
- Calentamiento específico corto para cada sesión, y calentamiento de hombro en los días de tren superior.
- Una tabla resumen de **series semanales por músculo** para comprobar que todo está entre 10 y 20 y que los prioritarios tienen más.
- Para cada ejercicio con riesgo según sus limitaciones, la alternativa directa por si molesta.
- Cuánto debería durar cada sesión.

## 4. Escribe `plan/nutricion.md`

- Cálculo de mantenimiento (muestra la fórmula y los números) y calorías objetivo con el superávit.
- Tabla de macros por tipo de día: tren superior, tren inferior, cardio o descanso. Mismas proteínas, carbohidratos y grasas ajustados, y promedio semanal en el objetivo.
- Horario de comidas para un día de trabajo con gym y para un día libre, con horas concretas según su perfil.
- Menú de ejemplo para cada tipo de día con comidas que le gustan, cantidades en porciones fáciles y su proteína aproximada. Respeta lo que no come.
- Lista de compras base para Costco y Publix.
- Tres comidas de emergencia para días de trabajo largos, con 30 g o más de proteína y fáciles de llevar.
- Suplementos con dosis y para qué sirve cada uno.
- Cómo se va a ajustar: qué mirar cada semana (peso promedio y cintura) y cuánto cambiar.

## 5. Escribe `plan/progresion.md`

- Regla de progresión doble con ejemplos usando sus números.
- Calendario de las próximas 12 semanas: semana de inicio, deloads y en qué semanas se puede rotar un accesorio (y cuál por cuál).
- Qué hacer si se estanca 2 semanas seguidas en un ejercicio.
- Qué hacer si se salta días: cómo reacomodar la semana sin perder sesiones de los músculos prioritarios.

## 6. Cierra

- Crea o actualiza `plan/historial-de-cambios.md` con la fecha, "Plan inicial" (o el cambio) y el motivo.
- Si `registros/entrenos.csv` o `registros/medidas.csv` no tienen encabezados, créalos.
- Muéstrale un resumen corto: el split, cómo es su semana, calorías y proteína diarias, y la primera sesión. Los detalles quedan en los archivos.
- Dile que cada semana corra `/checkin`.
