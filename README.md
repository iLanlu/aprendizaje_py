# 🍔 Proyecto Burger Lab - Flask

Repositorio personal desarrollado para el taller de Nuevas Tecnologías.

---

## ⚠️ RECORDATORIO IMPORTANTE (Estructura completa en VS) ⚠️

Al clonar este proyecto en una computadora nueva, verás menos carpetas de las que tienes en tu entorno local. Debes saber que:
1. La carpeta del entorno virtual `venv` **no se sube** porque Git la ignora automáticamente.
2. La carpeta `static` **no se sube** porque está vacía.

Debes crear la carpeta de imágenes manualmente para que tu explorador de archivos en **Visual Studio Code (VS)** quede estructurado exactamente así:

```text
Proyecto/
├── templates/       <-- (Descargado de GitHub)
├── venv/            <-- (IGNORADO POR GIT - Se crea al activar el entorno)
├── static/          <-- (MANUAL - Crear esta carpeta en la raíz)
│   └── images/      <-- (MANUAL - Crear esta carpeta dentro de static)
├── .gitignore       <-- (Descargado de GitHub)
├── README.md        <-- (Descargado de GitHub)
├── app.py           <-- (Descargado de GitHub)
├── requirements.txt <-- (Descargado de GitHub)
└── to-do.py         <-- (Descargado de GitHub)
```

La ruta final que debes ver en tu explorador de VS es: **`static\images`**

---

## 📥 Cómo Clonar el Proyecto en una PC Nueva

Abre la terminal de Windows en la carpeta donde desees guardar el proyecto y ejecuta:

1. **Clonar el repositorio:**
   ```powershell
   git clone https://github.com
   ```
2. **Entrar a la carpeta del proyecto:**
   ```powershell
   cd Proyecto_py
   ```
3. **Abrir el proyecto en Visual Studio Code:**
   ```powershell
   code .
   ```

---

## 🚀 Comandos Exactos para Arrancar el Proyecto

Con tu terminal de VS Code abierta, ejecuta estos comandos en orden para encender tu servidor local:

1. **Crear el entorno virtual:**
   ```powershell
   python -m venv venv
   ```
2. **Activar el entorno virtual en Windows:**
   ```powershell
   .\venv\Scripts\activate
   ```
3. **Instalar las librerías necesarias:**
   ```powershell
   pip install -r requirements.txt
   ```
4. **Ejecutar la aplicación de Flask:**
   ```powershell
   python app.py
   ```

### 🌐 Direcciones de Navegación
Con el servidor encendido (`Running on http://127.0.0.1:5000`), ingresa a:
* **Página de Bienvenida:** `http://127.0.0` (Carga `hola.html`)
* **Menú Burger Lab:** `http://127.0.0index` (Carga `index.html`)

---
**Desarrollado por:** iLanlu
