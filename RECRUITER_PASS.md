# Recruiter pass — 2026-09

Simulación de lectura rápida del perfil GitHub + portfolio para una candidatura orientada a **Operations / Data / Analytics / Process Improvement / Automation**.

## Escenario

Supuesto: recruiter o hiring manager llega desde el CV o LinkedIn y dedica entre 20 y 60 segundos antes de decidir si profundiza.

## Primeros 10 segundos

### Lo que se entiende rápido

- Posicionamiento: `Operations & Data · Automation · Process Improvement`.
- Formación: Técnico Superior en Ciencia de Datos.
- Hay experiencia operativa y de gestión previa, no sólo proyectos académicos.
- Existe un portfolio navegable y casos concretos.

### Riesgo evitado

El perfil ya no abre como una lista de tecnologías ni como un "junior buscando su primera oportunidad". Presenta una transición profesional con experiencia acumulada.

## Entre 10 y 30 segundos

La sección de perfil debe dejar tres ideas:

1. Mauro conoce operaciones reales y tuvo responsabilidades antes de especializarse en datos.
2. El patrón de problemas que trabaja es repetible: información dispersa, tareas manuales, poca trazabilidad y dependencia de conocimiento informal.
3. Datos y tecnología aparecen como herramientas para resolver esos problemas, no como un fin aislado.

El README de perfil fue ajustado con esta lógica.

## Entre 30 y 60 segundos

El trabajo seleccionado se ordena para contar amplitud sin parecer disperso:

1. **Ventas y Cobranzas** — Data Quality, Python, reproducibilidad y métricas verificables.
2. **Gestión de Espacios Públicos** — relevamiento, procesos, modelado y usuarios internos.
3. **Turnos Ecografías** — software llevado a una operación real.
4. **Depósito** — convivencia con legacy, seguridad, permisos y auditoría.
5. **Project Control** — modelado técnico y arquitectura más experimental.

El orden intenta responder progresivamente: datos → procesos → producción real → restricciones técnicas → diseño de producto técnico.

## Preguntas que probablemente genere el perfil

### “¿Cuánto de estos proyectos hizo personalmente?”

Mitigación: cada case page tiene una sección `Mi rol` que separa responsabilidad personal de la existencia general del sistema.

### “¿Por qué los repos principales son privados?”

Respuesta implícita en el portfolio: pertenecen a contextos operativos reales y se documentan sin exponer datos ni infraestructura. Existen dos repos públicos secundarios para revisar código y forma de trabajo.

### “¿Es Data Analyst, developer o administrador?”

Respuesta buscada: perfil híbrido de **Operations + Data** con capacidad de construir herramientas. No se intenta competir como software engineer senior ni como data scientist puramente académico.

### “¿Tiene experiencia técnica real o sólo formación?”

Evidencia: pipeline Python reproducible, aplicaciones internas, integración con sistemas legacy, WebSockets, n8n/APIs, documentación operativa, tests en proyectos donde corresponde y software usado en contextos reales.

## Señales positivas para una empresa de escala

- entiende restricciones operativas;
- piensa en trazabilidad y recuperación;
- diferencia demo de producción;
- no oculta limitaciones de los proyectos;
- trabaja con usuarios no técnicos;
- modela procesos antes de automatizarlos;
- puede explicar decisiones y trade-offs;
- combina experiencia previa con una transición técnica deliberada.

## Riesgos que todavía quedan

### 1. Falta evidencia visual

Es el principal gap actual. Los textos ya son suficientes; la siguiente mejora debe ser mostrar pantallas, flujos y resultados.

### 2. Gran parte del trabajo más fuerte es privado

No conviene publicar código real sólo para resolver este punto. Mejor producir screenshots con fixtures, demos sanitizadas y explicaciones verificables.

### 3. Repos públicos secundarios pueden distraer

`claudeskills` es válido como tooling secundario, pero no debería competir con los casos principales para roles de Operations/Data.

### 4. Repo público vacío

`household-finance-dashboard-demo` está vacío y no aporta ninguna señal positiva. Eliminar o convertir a privado antes de una postulación importante.

## Decisión de copy

No agregar más lenguaje aspiracional ni frases del tipo:

- “apasionado por los datos”;
- “siempre aprendiendo”;
- “buscando una oportunidad para demostrar”;
- listas extensas de tecnologías sin contexto.

La evidencia de proyectos debe cargar con la mayor parte del argumento.

## Gate de aprobación de narrativa

**Estado: APROBADO para pasar a producción visual.**

No hay un problema importante de posicionamiento que justifique seguir reescribiendo todo el portfolio. Las próximas rondas deben concentrarse en evidencia visual y revisión de privacidad.

## Siguiente ejecución

Primero: `control_op_ventas_cobranzas`.

Motivos:

- dataset sintético;
- demo pública;
- resultados cuantificados;
- riesgo de privacidad bajo;
- sirve para probar el flujo de screenshots antes de trabajar sobre sistemas reales.

Después:

1. Gestión de Espacios Públicos.
2. Depósito v2.
3. Turnos Ecografías.
4. Project Control, priorizando diagramas antes que screenshots de UI.
