# Coach personal

Mi entrenador personal y nutricionista dentro de Claude Code. Me entrevista, crea un plan de fuerza e hipertrofia de 4 días con su nutrición, y lo ajusta cada semana con mis datos.

## Primera vez

1. Crea un repositorio **privado** en GitHub y sube estos archivos (o descomprime el zip en uno nuevo).
2. Ábrelo en Claude Code (en la web, en claude.ai/code, o en la terminal con `claude` dentro de la carpeta).
3. Escribe `/entrevista` y contesta. Toma unos 20–30 minutos; se puede dejar a medias y seguir otro día.
4. Escribe `/plan`. Compara varios splits, te recomienda uno y escribe la rutina, la nutrición y la progresión en `plan/`.

## Cada semana

- `/checkin`: le das peso, entrenos, comida, sueño y molestias. Ajusta pesos y calorías y guarda el resumen en `registros/semanas/`.

## Cuando haga falta

- `/ejercicio press banca`: técnica, una molestia o cambiar un ejercicio por otro.
- `/entrevista actualizar horario`: si cambia algo grande (trabajo, gym, lesión).
- Cualquier pregunta normal, por ejemplo "¿qué ceno hoy si voy a entrenar a las 7?". Claude lee el plan antes de contestar.

## Para gastar pocos créditos

- Una sesión de Claude Code por tarea: la entrevista en una, el plan en otra y cada check-in en una nueva. Todo queda guardado en los archivos, así que no hace falta conversaciones largas.
- Registra los entrenos en una app gratuita (Hevy o Strong) y pega el resumen en el check-in.
- Para el día a día no hace falta Claude Code: abre `plan/rutina.md` y `plan/nutricion.md` en el teléfono desde GitHub.

## Estructura

```
CLAUDE.md                   instrucciones del coach
.claude/commands/           /entrevista, /plan, /checkin, /ejercicio
perfil/                     quién soy, mis metas y limitaciones
plan/                       rutina, nutrición, progresión, historial de cambios
registros/                  medidas, entrenos, resúmenes semanales
```

> Esto no reemplaza a un médico. Si algo duele de verdad, se para y se consulta.
