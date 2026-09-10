# Despliegue de una plataforma de microservicios con Kubernetes

El equipo de desarrollo de una empresa fintech necesita desplegar una plataforma de microservicios utilizando Kubernetes, Helm, GitOps con ArgoCD y monitoreo con Prometheus y Grafana. La plataforma debe soportar un tráfico de 10 000 solicitudes por segundo con un tiempo de respuesta promedio de 500ms y una disponibilidad del 99.9%. El sistema debe ser capaz de manejar actualizaciones de servicios sin tiempo de inactividad y debe tener un monitoreo en tiempo real de la salud y el rendimiento de los servicios. Los microservicios a desplegar incluyen un servicio de autenticación, un servicio de gestión de usuarios y un servicio de procesamiento de transacciones.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Kubernetes DevOps |
| **Nivel** | advanced-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 20 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración del cluster de Kubernetes

**Objetivo:** Tenga un cluster de Kubernetes configurado y listo para desplegar microservicios.

**Tiempo estimado:** 5 horas

**Instrucciones:**

- Identificar las necesidades del cluster en términos de nodos, recursos y networking.
- Configurar el cluster de Kubernetes con las especificaciones requeridas.
- Verificar que el cluster esté funcionando correctamente.

**Entregable:** Un cluster de Kubernetes configurado y funcional.

<details>
<summary>Pistas de conocimiento</summary>

- Considera las restricciones de recursos y networking para el cluster.
- Piensa en la escalabilidad y disponibilidad del cluster.

</details>

### Fase 2: Despliegue de microservicios con Helm

**Objetivo:** Tenga los microservicios desplegados en el cluster de Kubernetes utilizando Helm.

**Tiempo estimado:** 5 horas

**Instrucciones:**

- Crear los charts de Helm para los microservicios.
- Desplegar los microservicios en el cluster de Kubernetes.
- Verificar que los microservicios estén funcionando correctamente.

**Entregable:** Microservicios desplegados en el cluster de Kubernetes utilizando Helm.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza Helm para gestionar las versiones y configuraciones de los microservicios.
- Asegúrate de que los microservicios estén correctamente enlazados y comunicados.

</details>

### Fase 3: Implementación de GitOps con ArgoCD

**Objetivo:** Tenga la plataforma de microservicios gestionada con GitOps utilizando ArgoCD.

**Tiempo estimado:** 5 horas

**Instrucciones:**

- Configurar ArgoCD para gestionar los microservicios.
- Implementar el flujo de GitOps para las actualizaciones de los microservicios.
- Verificar que las actualizaciones se realicen de manera automática y sin tiempo de inactividad.

**Entregable:** Plataforma de microservicios gestionada con GitOps utilizando ArgoCD.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza ArgoCD para implementar el flujo de GitOps.
- Asegúrate de que las actualizaciones se realicen de manera automática y sin tiempo de inactividad.

</details>

### Fase 4: Configuración de monitoreo con Prometheus y Grafana

**Objetivo:** Tenga el monitoreo de la plataforma de microservicios configurado con Prometheus y Grafana.

**Tiempo estimado:** 5 horas

**Instrucciones:**

- Configurar Prometheus para monitorear los microservicios.
- Configurar Grafana para visualizar los datos de monitoreo.
- Verificar que el monitoreo esté funcionando correctamente y que los datos sean visualizados en Grafana.

**Entregable:** Monitoreo de la plataforma de microservicios configurado con Prometheus y Grafana.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza Prometheus para recolectar métricas de los microservicios.
- Utiliza Grafana para visualizar los datos de monitoreo.
- Asegúrate de que el monitoreo sea en tiempo real y que los datos sean visualizados de manera clara y efectiva.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es Kubernetes y por qué se utiliza en el despliegue de microservicios?
- **paraQueSirve**: ¿Para qué sirve Helm en el despliegue de microservicios con Kubernetes?
- **comoSeUsa**: ¿Cómo se utiliza ArgoCD para implementar GitOps en el despliegue de microservicios?
- **erroresComunes**: ¿Cuáles son los errores comunes al configurar el monitoreo con Prometheus y Grafana?
- **queDecisionesImplica**: ¿Qué decisiones implica la implementación de GitOps con ArgoCD en el despliegue de microservicios?

## Criterios de Evaluacion

- Configurar un cluster de Kubernetes funcional.
- Desplegar microservicios utilizando Helm.
- Implementar GitOps con ArgoCD.
- Configurar monitoreo con Prometheus y Grafana.

## Como trabajar con un asistente de IA

- **AGENTS.md** — instrucciones nativas del repo (Cursor, Codex, Copilot, Gemini, Claude Code). Abrí el proyecto y el agente las carga solo.
- **PROMPT_MEJORA.md** — el mismo prompt, para copiar y pegar en un chat (claude.ai, ChatGPT, etc.).

---

*Reto generado automaticamente por Challenge Generator - Pragma*
