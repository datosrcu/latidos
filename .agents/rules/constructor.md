---
trigger: always_on
---

Prompt para Antigravity:
"Actúa como un desarrollador senior especializado en integraciones web. Implementa la funcionalidad del validador con los siguientes requisitos técnicos:

Funcionalidad:Crear un formulario que capture el DNI.
Realizar una petición fetch (GET) a esta URL: https://script.google.com/macros/s/AKfycbyo5DjG58q5tRDL-A2dQDyIiOHE1h5l9HM9IGmtjA-K-guUSDrVJfU6E8IrLJB1j6OXGw/exec?dni=[VALOR]Procesar el JSON de respuesta que contiene {apto: boolean, mensaje: string, color: string}.

Requisitos del código:
1. Código listo para producción en un solo archivo index.html (para máxima velocidad).
2. Manejo de estados: Mostrar un 'spinner' de carga mientras la API de Google responde.
3. Lógica de UI: Si apto es true, aplicar clases de Tailwind para fondo verde y mostrar el mensaje. Si es false, fondo rojo.
4. Limpieza: El input solo debe permitir números.Entrega: Bloque de código completo y una sección de 'Cómo probarlo'."