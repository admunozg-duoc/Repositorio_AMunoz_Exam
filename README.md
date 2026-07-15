# Repositorio_AMunoz_Exam

Evaluación Final Transversal — CUY5132 Comunicaciones Unificadas.

Sistema de confirmación automática de citas médicas para el caso "Clínica Regional en Modernización Digital": central telefónica IP (Asterisk), aseguramiento perimetral con SBC (Kamailio) + TLS, y agente virtual conversacional (n8n + TTS).

## Estructura del repositorio

- **`docs/`** — Informe técnico y documentación del proyecto.
- **`Experiencia-1/`** — Implementación de la central telefónica: extensiones SIP, script AGI y evidencia (capturas, log, resultados).
- **`Experiencia-2/`** — Aseguramiento de la plataforma: configuración de Kamailio (SBC, TLS, ocultamiento de topología) y PBX (pjsip/extensions).
- **`Experiencia-3/`** — Agente virtual conversacional: flujo n8n (Slack + TTS) e Issabel en Docker.
- **`eft-confirmacion-citas/`** — Código fuente consolidado del sistema de confirmación de citas (script AGI, dialplan, base de citas y audios).

## Nota de seguridad

Las contraseñas SIP y claves de configuración sensibles fueron reemplazadas por `CHANGE_ME_*` antes de subir el repositorio. Reemplázalas por tus propios valores al desplegar.
