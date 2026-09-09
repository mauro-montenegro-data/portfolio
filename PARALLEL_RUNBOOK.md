# Portfolio — ejecución paralela con agentes

## Objetivo

Coordinar la producción visual de los casos principales sin que dos agentes trabajen sobre el mismo repositorio ni se mezclen datos reales con material de portfolio.

## Regla general

Cada agente debe trabajar:

- en una ventana separada;
- dentro de un único repositorio;
- sobre una rama local `portfolio/...`;
- sin push ni deploy;
- dejando cambios sin commit para revisión humana;
- usando datos sintéticos/ficticios cuando el proyecto deriva de una operación real.

## Orden de ejecución

### Agente 1 — Ventas y Cobranzas

Repo: `control_op_ventas_cobranzas`

Tarea: `docs/portfolio/agent-screenshot-task.md`

Estado esperado: producción de screenshots completa. Es el caso piloto porque usa datos sintéticos.

Rama sugerida:

```text
portfolio/screenshots-ventas-cobranzas
```

### Agente 2 — Gestión de Espacios Públicos

Repo: `gestion-espacios-publicos`

Tarea: `docs/portfolio/agent-screenshot-task.md`

Primera obligación: aprobar el gate de privacidad y confirmar dataset/seed seguro. Sólo después producir capturas.

Rama sugerida:

```text
portfolio/screenshots-espacios-publicos
```

### Agente 3 — Depósito v2

Repo: `deposito-v2`

Tarea: `docs/portfolio/agent-screenshot-task.md`

No conectar migraciones/escrituras a producción. Preparar una base local/de demo con datos ficticios antes de capturar.

Rama sugerida:

```text
portfolio/screenshots-deposito
```

### Agente 4 — Turnos Ecografías

Repo: `turnos-ecografias`

Tarea: `docs/portfolio/agent-screenshot-task.md`

Usar pacientes/turnos completamente ficticios; nunca importar una agenda productiva para screenshots.

Rama sugerida:

```text
portfolio/screenshots-turnos
```

### Agente 5 — Project Control

Repo: `project-control`

Tarea: `docs/portfolio/agent-screenshot-task.md`

Prioridad menor. Generar diagramas/evidencia del modelo antes que capturas de una UI experimental.

Rama sugerida:

```text
portfolio/visual-project-control
```

## Criterio de revisión al terminar cada agente

Antes de commit/push, revisar:

```powershell
git status --short
git diff --stat
```

Y pedir al agente:

- tests/checks ejecutados;
- resultados;
- archivos creados/modificados;
- origen de los datos visibles;
- screenshots generados;
- bloqueos o diferencias con documentación;
- confirmación de privacidad.

## Orden de incorporación al portfolio

1. Ventas y Cobranzas.
2. Gestión de Espacios Públicos.
3. Depósito v2.
4. Turnos Ecografías.
5. Project Control.

No incorporar automáticamente todas las imágenes producidas. Seleccionar sólo las que añadan evidencia distinta al caso.