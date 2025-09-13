
# 🎬 Project NexusDownloader AI — Sistema Inteligente de Descarga y Análisis Multimedia

**Tipo de archivo:** Script en **Python · yt-dlp · ffmpeg · Pandas · ipywidgets**
**Archivos principales del proyecto:**

* `nexus_downloader.py` (lógica principal)
* `widgets/` (interfaz interactiva con ipywidgets)
* `cookies/` (almacenamiento seguro de cookies subidas)

---

## 📑 Descripción

**NexusDownloader AI** es una solución de ingeniería avanzada para la **descarga, análisis y recomendación multimedia** desde YouTube y plataformas compatibles.
Su objetivo es permitir al usuario obtener el **mejor video posible** en términos de **calidad, compatibilidad y autenticación**.

El sistema no solo descarga, sino que **analiza, filtra y sugiere** los mejores flujos de video/audio, con **fusión inteligente mediante ffmpeg** y un entorno interactivo en **Jupyter/Colab**.

---

## ✨ Características principales

🔹 **1. Validación Inteligente de Enlaces**

* Normaliza y valida cualquier URL de YouTube.
* Fallback progresivo: estándar → visitorData → cookies.
* Animación de carga ⏳ y mensajes claros al usuario.

🔹 **2. Análisis Detallado de Formatos**

* Usa `yt-dlp` para extraer todos los formatos disponibles.
* Procesa resultados con **Pandas** y muestra tablas interactivas.
* Incluye información técnica: resolución, FPS, códecs, bitrate, peso, compatibilidad.

🔹 **3. Recomendaciones Automáticas**

* 🎧 Mejor audio disponible (mayor bitrate).
* ✅ Video más compatible (H.264).
* 🚀 Video de máxima calidad moderna (VP9/AV1).
* Clasificación visual 🥇 Alta · 🥈 Media · ⚠️ Baja.

🔹 **4. Descarga y Fusión Automática**

* Descarga video y audio en paralelo.
* Combina ambos con **ffmpeg** en un MP4 sin pérdida.
* Barras de progreso y logs en tiempo real.

🔹 **5. Manejo de Restricciones**

* Compatible con videos Premium, +18, privados o solo miembros.
* Soporta cookies personalizadas (`cookies.txt`) para autenticación.

🔹 **6. Experiencia de Usuario Mejorada**

* Interfaz con **ipywidgets**: menús, filtros y botones interactivos.
* Exportación de resultados en CSV/TXT.
* Limpieza automática de archivos temporales.

---

## 🛠️ Tecnología

* **Lenguaje principal:** Python 3
* **Descarga y análisis:** yt-dlp · ffmpeg
* **Procesamiento de datos:** Pandas · re · json · glob
* **Interfaz:** ipywidgets · IPython.display
* **Compatibilidad:** Jupyter Notebook · Google Colab

---

## 🎥 Demo

🔗 **GIFs y capturas** mostrando las principales funcionalidades:

1. **Validación de enlace con fallback inteligente**
2. **Tabla de formatos analizados con Pandas**
3. **Recomendaciones automáticas de formatos**
4. **Progreso en tiempo real de descarga y fusión**
5. **Acceso a videos Premium y restringidos**

---

## 📦 Estado del Proyecto

✅ **Funcional y probado en Colab y Jupyter**.
📂 Maneja archivos grandes (hasta 14 GB).
🔒 **Privado**: el código puede compartirse bajo solicitud.

---

## 📂 Releases

📦 Se publicarán versiones en la pestaña **Releases** en formato comprimido.
🔑 Acceso bajo **contraseña o permiso previo**.

---

## 📬 Contacto

📧 **gabrielce992@gmail.com**  
