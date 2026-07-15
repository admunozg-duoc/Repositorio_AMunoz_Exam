# eft-confirmacion-citas

Sistema de confirmación automática de citas médicas (EFT CUY5132 - Comunicaciones Unificadas), caso "Clínica Regional en Modernización Digital".

## Contenido

- `confirmar_cita.agi` — Script AGI de Asterisk: atiende la llamada, reproduce el mensaje personalizado de la cita, captura la respuesta DTMF (1=Confirmar, 2=Cancelar, 3=Reprogramar), consulta/actualiza la base de citas y registra el resultado.
- `citas.csv` — Base de datos de citas utilizada por el script AGI.
- `extensions_custom.conf` — Dialplan personalizado de Asterisk para invocar el script AGI.
- `audios/` — Audios de prueba usados por el flujo de confirmación.

## Evidencia relacionada

- Configuración de extensiones SIP y capturas de funcionamiento: `../Experiencia-1/`
- Aseguramiento de la plataforma (SBC, TLS, grupos de seguridad): `../Experiencia-2/`
- Flujo n8n / agente conversacional TTS: `../Experiencia-3/`
- Informe técnico completo: `../docs/`
