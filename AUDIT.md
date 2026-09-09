# Portfolio audit — 2026-09

Documento de trabajo para mantener alineados GitHub, portfolio y CV.

## Posicionamiento

**Operations & Data · Automation · Process Improvement**

Narrativa central:

> Experiencia operativa y de gestión + formación en Ciencia de Datos + capacidad de convertir problemas reales en procesos, datos y herramientas utilizables.

## Casos principales

| Caso | Capacidad principal | Código | Case page | Guía visual | Mi rol explícito |
|---|---|---|---|---|---|
| Ventas y Cobranzas | Data quality + pipeline reproducible | Privado / demo pública | ✅ | ✅ | ✅ |
| Depósito v2 | Operaciones + legacy + seguridad | Privado | ✅ | ✅ | ✅ |
| Gestión Espacios Públicos | Relevamiento + modelado + herramienta interna | Privado | ✅ | ✅ existente | ✅ |
| Turnos Ecografías | Software en operación real + local-first | Privado | ✅ | ✅ | ✅ |
| Project Control | Modelado técnico + evidence/reconciliation | Privado | ✅ | ✅ | ✅ |

## Proyectos públicos secundarios

### ops-data-portfolio
Estado: README actualizado. Caso pequeño y revisable `SQL → KPI → n8n → Telegram`.

### ai-content-generation-pipeline
Estado: README actualizado para eliminar claims excesivos y separar claramente demo de producción.

### claudeskills
Estado: público, pero no destacado. Puede quedar visible como evidencia secundaria de disciplina de trabajo con agentes y tooling; no debe competir con los casos principales.

## Higiene pública

- `portfolio`: portfolio vigente.
- `portfolio-mauro`: versión legacy; redirige al portfolio vigente y tiene README que lo aclara.
- `mauro-montenegro-data`: README de perfil actualizado y conectado a los case studies.
- `household-finance-dashboard-demo`: **repo público vacío**. Conviene eliminarlo o hacerlo privado antes de una candidatura importante.
- `claudeskills`: mantener fuera de destacados salvo que una búsqueda valore explícitamente developer tooling/agent workflows.

## Rondas completadas

### Ronda 1 — narrativa

- se reemplazó el foco anterior en Growth/Martech por Operations & Data;
- se alineó CV, README de perfil y portfolio;
- se seleccionaron cinco casos con capacidades distintas.

### Ronda 2 — profundidad de casos

- cada caso principal tiene página independiente;
- los repos de origen tienen case study o documentación equivalente;
- se corrigieron claims temporales/obsoletos detectados en Project Control y Turnos.

### Ronda 3 — autoría y responsabilidad

Cada case page explica ahora explícitamente qué parte del trabajo correspondió a Mauro: relevamiento, modelado, decisiones, implementación, tests/documentación según el proyecto. Esto reduce la ambigüedad típica de portfolios que muestran sistemas sin aclarar el rol del candidato.

### Ronda 4 — preparación visual

Existe `SCREENSHOT_PLAN.md` con prioridades, nombres de archivos, viewport y gate de privacidad. La siguiente mejora de alto impacto ya no es agregar más texto: es incorporar evidencia visual seleccionada.

### Ronda 5 — recruiter pass

Se simuló la lectura de 20–60 segundos desde GitHub/portfolio y se ajustó la portada para que la primera señal sea `Operations + Data`, no el cargo público aislado. Se reordenaron los casos destacados para contar: datos → procesos → producción real → legacy/seguridad → producto técnico.

Resultado completo en `RECRUITER_PASS.md`.

**Gate de narrativa: APROBADO.** No seguir agregando copy salvo que aparezca una vacante concreta que requiera adaptar lenguaje o prioridades.

## Producción visual pendiente

### Ventas y Cobranzas
Prioridad alta.

- home/demo pública;
- resumen de corrida;
- registros rechazados + motivo;
- autocorrecciones/warnings;
- diagrama del pipeline;
- ejemplo de manifest/quality report.

### Depósito
Prioridad alta.

- dashboard con datos ficticios;
- productos/stock;
- entrada;
- salida por número de serie;
- usuarios/roles;
- auditoría;
- remito PDF ficticio.

### Espacios Públicos
Prioridad alta.

Guía existente en `docs/portfolio/screenshots-guide.md`. Seleccionar 5–6, no publicar las 13.

### Turnos Ecografías
Prioridad alta.

- recepción con pacientes ficticios;
- panel médico/profesional;
- sala de espera;
- composición de las tres interfaces;
- arquitectura local-first.

### Project Control
Prioridad media.

Priorizar diagramas y ejemplos de Evidence/Claim/Reconciliation/WorkModel antes que screenshots de una UI experimental.

## Regla de publicación

Ningún screenshot o ejemplo de operación real debe incluir:

- datos personales;
- credenciales o tokens;
- IPs o infraestructura sensible;
- identificadores internos que no sean necesarios;
- información real del municipio o pacientes cuando pueda reemplazarse por fixtures/datos ficticios.

## Próximo gate

Antes de sumar más texto al portfolio, producir evidencia visual para **Ventas/Cobranzas, Depósito, Espacios Públicos y Turnos**. El sitio ya tiene estructura suficiente; la mayor mejora marginal ahora proviene de mostrar los sistemas y resultados.

Primera ejecución recomendada: `control_op_ventas_cobranzas`, porque ya trabaja con datos sintéticos y tiene una demo pública. Es el mejor repo para probar el flujo de screenshots automatizados antes de tocar sistemas basados en operaciones reales.
