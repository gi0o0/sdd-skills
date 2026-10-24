---
description: Genera las specs de una funcionalidad (requisitos, diseño, tareas)
---
Funcionalidad: $ARGUMENTS

Ejecuta estas tres fases en orden, delegando cada una en su subagente:
1. sdd-requirements → specs/<slug>/requirements.md
2. sdd-design → specs/<slug>/design.md
3. sdd-tasks → specs/<slug>/tasks.md

<slug> es el nombre de la funcionalidad en kebab-case.
Cada fase debe leer la salida de la anterior.
No modifiques ningún fichero fuera de specs/<slug>/.
Al terminar, lista los ficheros creados.
