---
trigger: always_on
---

Prompt para Antigravity:
"Actúa como un ingeniero de QA senior. Escribe una suite de pruebas (pueden ser manuales o scripts de validación) para asegurar que la lógica de la columna AI (Fecha Probable de Parto) y AO (Estado) funcione perfectamente.

Escenarios a cubrir:
1. Happy Path: Estado 'Inicial' siempre devuelve Apto.
2. Edge Case: Usuario con estado 'Finalizada (parto)' donde la FPP fue hace exactamente 11 meses y 29 días (Debe ser Apto).
3. Edge Case: Usuario con estado 'Seguimiento post nacimiento' donde la FPP fue hace 12 meses y 1 día (Debe ser No Apto).
4. Error: Respuesta de API lenta o caída (el sistema no debe quedarse bloqueado)."