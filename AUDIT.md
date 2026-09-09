# Portfolio audit — 2026-09

Documento de trabajo para mantener alineados GitHub, portfolio y CV.

## Posicionamiento

**Operations & Data · Automation · Process Improvement**

Narrativa central:

> Experiencia operativa y de gestión + formación en Ciencia de Datos + capacidad de convertir problemas reales en procesos, datos y herramientas utilizables.

## Casos principales

| Caso | Capacidad principal | Código | Case page | Guía visual |
|---|---|---|---|---|
| Ventas y Cobranzas | Data quality + pipeline reproducible | Privado / demo pública | ✅ | ✅ |
| Depósito v2 | Operaciones + legacy + seguridad | Privado | ✅ | ✅ |
| Gestión Espacios Públicos | Relevamiento + modelado + herramienta interna | Privado | ✅ | ✅ existente |
| Turnos Ecografías | Software en operación real + local-first | Privado | ✅ | ✅ |
| Project Control | Modelado técnico + evidence/reconciliation | Privado | ✅ | ✅ |

## Proyectos públicos secundarios

### ops-data-portfolio
Estado: README actualizado. Caso pequeño y revisable `SQL → KPI → n8n → Telegram`.

### ai-content-generation-pipeline
Estado: README actualizado para eliminar claims excesivos y separar claramente demo de producción.

## Higiene pública

- `portfolio`: portfolio vigente.
- `portfolio-mauro`: versión legacy; ahora redirige al portfolio vigente.
- `mauro-montenegro-data`: README de perfil actualizado y conectado a los case studies.
- `household-finance-dashboard-demo`: **repo público vacío**. Revisar si conviene eliminarlo o hacerlo privado antes de una candidatura importante.
- `claudeskills`: revisar si aporta al perfil objetivo; no forma parte de los proyectos destacados.

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
