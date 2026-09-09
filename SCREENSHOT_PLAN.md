# Plan de evidencia visual — Portfolio

Objetivo: incorporar evidencia visual suficiente para demostrar trabajo real sin exponer datos personales, credenciales, infraestructura sensible ni información operativa innecesaria.

## Estándar general

- Viewport preferido: **1440×900**.
- Alternativa: **1280×800**.
- Formato: PNG.
- Nombres en minúsculas con guiones.
- Usar fixtures, seed o datos sintéticos.
- No publicar IPs, usuarios reales, teléfonos, nombres de pacientes, agentes, CUIT, expedientes reales, tokens ni secretos.
- Antes de publicar cada captura, revisar visualmente esquinas, barras, tablas, modales y campos secundarios.
- Máximo recomendado por caso en la versión inicial: **3–5 imágenes**.

## 1. Ventas y Cobranzas — prioridad 1

Repositorio origen: `control_op_ventas_cobranzas`.

Archivos previstos:

1. `ventas-overview.png`
   - Home o resumen visual de la demo pública.
   - Debe mostrar que se trata de datos sintéticos.

2. `ventas-run-summary.png`
   - Resultado de una corrida: recibidas, procesadas, rechazadas y hallazgos.

3. `ventas-rejected.png`
   - Ejemplo de registros rechazados con motivo entendible.

4. `ventas-quality.png`
   - Warnings/autocorrecciones o reporte de calidad.

5. `ventas-pipeline.png`
   - Diagrama simple del flujo, si una captura de UI no lo explica bien.

Selección inicial para publicar: 3–4.

## 2. Gestión de Espacios Públicos — prioridad 2

Repositorio origen: `gestion-espacios-publicos`.

Partir de `docs/portfolio/screenshots-guide.md` y reducir a estas seis candidatas:

1. `espacios-dashboard.png`
2. `espacios-inventario.png`
3. `espacios-pedidos.png`
4. `espacios-pedido-historial.png`
5. `espacios-tramites.png`
6. `espacios-forestacion.png`

Selección inicial para publicar: 4–5.

Regla: usar seed/datos ficticios. No fotografiar una instancia con datos municipales reales.

## 3. Depósito v2 — prioridad 3

Repositorio origen: `deposito-v2`.

Archivos previstos:

1. `deposito-dashboard.png`
2. `deposito-stock.png`
3. `deposito-salida-serie.png`
4. `deposito-usuarios-roles.png`
5. `deposito-auditoria.png`
6. `deposito-remito.png`

Selección inicial para publicar: 4–5.

Regla: montar una instancia/fixture de portfolio. No usar capturas directas de la base municipal real.

## 4. Turnos Ecografías — prioridad 4

Repositorio origen: `turnos-ecografias`.

Archivos previstos:

1. `turnos-recepcion.png`
2. `turnos-profesional.png`
3. `turnos-sala.png`
4. `turnos-tres-pantallas.png`
5. `turnos-arquitectura-local.png`

Selección inicial para publicar: 3–4.

Regla: todos los pacientes, horarios y observaciones deben ser ficticios.

## 5. Project Control — prioridad 5

Repositorio origen: `project-control`.

No priorizar screenshots de una UI experimental. El caso se entiende mejor con evidencia técnica seleccionada.

Archivos previstos:

1. `project-control-pipeline.png`
2. `project-control-evidence-claim.png`
3. `project-control-reconciliation.png`
4. `project-control-workmodel.png`

Selección inicial para publicar: 2–3.

## Gate de privacidad antes de publicar

Para cada imagen confirmar:

- [ ] datos ficticios/sintéticos;
- [ ] sin nombres reales innecesarios;
- [ ] sin teléfonos, mails personales o documentos;
- [ ] sin IPs, URLs internas o rutas sensibles;
- [ ] sin tokens, secrets o credenciales;
- [ ] sin información del navegador o escritorio que revele datos ajenos al caso;
- [ ] la imagen demuestra una capacidad concreta y no está sólo por decoración.

## Orden de ejecución

1. Ventas/Cobranzas: ya tiene demo sintética, menor riesgo.
2. Espacios Públicos: seed y guía visual ya preparados.
3. Depósito: preparar fixture/entorno separado antes de capturar.
4. Turnos: preparar pacientes ficticios y composición de las tres pantallas.
5. Project Control: producir diagramas/evidencia técnica.

## Criterio de cierre

La ronda visual queda lista cuando cada uno de los cuatro casos principales tenga al menos **3 piezas de evidencia visual publicables**, revisadas por privacidad y enlazadas desde su case page.
