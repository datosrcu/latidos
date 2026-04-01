# Programa Latidos - Validador de Descuentos para Comercios

Esta aplicación ultra-liviana permite a los comerciantes verificar de manera rápida y efectiva si una beneficiaria es apta para los descuentos del **Programa Latidos** (programa de acompañamiento a la maternidad y primera infancia).

## 🚀 Funcionalidades

### 1. Validador de Beneficiarias (`index.html`)
- **Interfaz Mobile-First**: Diseñada para ser usada desde el celular del comerciante en el punto de venta.
- **Validación en Tiempo Real**: Consulta la base de datos centralizada mediante la API de Google Apps Script.
- **Feedback Visual Inmediato**: Pantallas a color (Verde para APTO, Rojo para NO APTO) para evitar errores de lectura rápida.
- **Seguridad de Datos**: Validación de formato de DNI (solo números, sin puntos ni espacios).

### 2. Generador de Credenciales Digitales (`credencial.html`)
- Permite a las beneficiarias generar su propia credencial digital.
- **Exportación a PDF**: Genera un archivo profesional listo para ser presentado en los comercios.
- **Pre-carga de Imágenes**: Garantiza que los logos institucionales se vean correctamente en el documento exportado.

## 🛠️ Stack Tecnológico
- **Frontend**: HTML5, CSS3 decorado con **Tailwind CSS**.
- **Lógica**: Vanilla JavaScript (sin frameworks pesados para máxima velocidad).
- **Backend/API**: Google Apps Script (integrado con Google Sheets).
- **Librerías**: `html2pdf.js` para la generación de documentos.

## 📦 Instalación y Uso Local

No requiere instalación de dependencias pesadas. Simplemente clona el repositorio y abre los archivos `.html` en cualquier navegador moderno.

```bash
git clone https://github.com/datosrcu/latidos.git
cd latidos
# Abrir index.html en el navegador
```

## ✒️ Créditos
Producto desarrollado por la **Subsecretaría de Estadística de la Municipalidad de Río Cuarto**.
