# TradesHabbo-Translator

**TradesHabbo Translator** es una herramienta desarrollada para traducir en tiempo real el contenido visible en la ventana del cliente `.exe` de **Habbo Origins**, capturando imágenes directamente desde el entorno de juego.

Su objetivo es facilitar la comprensión de conversaciones en otros idiomas dentro de diferentes hoteles, utilizando **reconocimiento de imágenes y procesamiento de lenguaje natural** mediante inteligencia artificial de **OpenAI**.

---

## ⚙️ Tecnologías utilizadas

Este proyecto está desarrollado con las siguientes tecnologías:

- **Node.js**
- **OpenAI** – API para OCR y traducción contextual.
- **robotjs** – Captura de pantalla y automatización de mouse/teclado.
- **sharp** – Procesamiento y recorte de imágenes.
- **node-window-manager** – Identificación y manejo de la ventana activa del cliente de Habbo.
- **clipboardy** – Manejo del portapapeles para copiar resultados.
- **express** – Servidor local para peticiones auxiliares.
- **axios / form-data** – Comunicación con servicios externos.
- **dotenv** – Gestión de variables de entorno.

---

## 🔧 Modo de desarrollo

1. Asegúrate de tener **Node.js v18.20.2** instalado.
2. Ejecuta `npm install` para instalar las dependencias.
3. Crea un archivo `.env` en la raíz y define la variable:

4. Abre el archivo `package.json` y añade esta propiedad al nivel raíz:

```json
"chromium-args": "--remote-debugging-port=9222 --auto-open-devtools-for-tabs"
```
5. Ejecuta el proyecto con: nwjs-sdk/nw.exe .

📌 Proyecto creado por Camilo Yaya

