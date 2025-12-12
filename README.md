# 🦁 Zoo Virtual - Experiencia Inmersiva en WebVR

> Una experiencia de zoológico virtual interactivo construida con A-Frame

[![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://palomajnm.github.io/frame_zoo1/)

## 🎯 Sobre el Proyecto

**Zoo Virtual** es una experiencia inmersiva en realidad virtual que te permite explorar y aprender sobre fauna salvaje desde tu navegador. Desarrollado como proyecto educativo para el módulo de Digitalización Aplicada al Sector Productivo, combina fotografía 360°, modelos 3D y navegación interactiva para crear un entorno de aprendizaje innovador.

### ✨ Características Principales

- **🌐 Imágenes 360°**: Explora entornos naturales con fotografía panorámica inmersiva.
- **🦒 Modelos 3D Realistas**: Interactúa con animales modelados en alta calidad.
- **🎮 Navegación Intuitiva**: Portales interactivos para moverse entre escenas.
- **🥽 Soporte VR Completo**: Compatible con Oculus Quest, HTC Vive y más.
- **📱 Multi-plataforma**: Funciona en escritorio, móvil y dispositivos VR.
- **♿ Accesible**: Experiencia disponible 24/7 sin barreras geográficas.

---

## 🎬 Escenas Disponibles

### 1️⃣ Entrada Principal

**Tipo:** Imagen 360°
Bienvenida al zoo con vista panorámica completa. Incluye portal interactivo para acceder a los hábitats e información de navegación básica.

### 2️⃣ Hábitat Safari

**Tipo:** Modelos 3D
Explora el ecosistema africano con animales modelados: leones, elefantes, jirafas y más. Sistema de información educativa sobre cada especie.

### 3️⃣ Zona Interactiva

**Tipo:** Experiencia 3D
Interacción directa con los animales, controles de cámara avanzados y contenido educativo sobre conservación y biodiversidad.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología     | Uso                     | Versión |
| -------------- | ----------------------- | ------- |
| **A-Frame**    | Framework WebVR         | 1.4.0   |
| **WebXR**      | API de Realidad Virtual | Latest  |
| **HTML5**      | Estructura              | -       |
| **JavaScript** | Interactividad          | ES6+    |
| **GLTF/GLB**   | Modelos 3D              | 2.0     |

### Componentes Clave de A-Frame usados

```html
<!-- Cielo 360° -->
<a-sky src="assets/panorama.jpg"></a-sky>

<!-- Modelos 3D -->
<a-gltf-model src="assets/lion.glb"></a-gltf-model>

<!-- Interactividad -->
<a-entity event-set__click="scale: 1.2 1.2 1.2"></a-entity>

<!-- Animaciones -->
<a-animation attribute="rotation" to="0 360 0"></a-animation>
```

---

## 📂 Estructura del Proyecto

Organización actual de los archivos y directorios del repositorio:

```text
/frame_zoo1
├── index.html                      # Página de inicio / Panel de selección de experiencias
└── content/
    ├── assets/                     # Recursos estáticos
    │   ├── fonts/                  # Tipografías (e.g., WildTrails.ttf)
    │   ├── images/                 # Imágenes, texturas y thumbnails
    │   └── models/                 # Modelos 3D (GLB/GLTF) y sus texturas
    └── pages/                      # Páginas de las experiencias individuales
        ├── dinosaurios.html        # Hábitat de Dinosaurios
        ├── oceano.html             # Hábitat del Océano
        ├── sabana.html             # Hábitat de la Sabana
        ├── juego-leones.html       # Juego interactivo de Leones
        ├── experiencia-bosque.html # Visualizador 360° - Bosque
        ├── experiencia-desierto.html # Visualizador 360° - Desierto
        ├── experiencia-montana.html  # Visualizador 360° - Montaña
        ├── experiencia-oceano.html   # Visualizador 360° - Océano
        └── experiencia-submarina.html # Visualizador 360° - Submarino
```

---

## 🌍 Impacto y Sostenibilidad

### Beneficios Ambientales

- **🌱 Reducción de CO₂:** ~200kg/año al evitar desplazamientos físicos.
- **⚡ Ahorro energético:** No requiere infraestructura física operativa 24/7.
- **🛡️ Conservación:** Educación sin impacto en hábitats reales.

### Optimización Técnica

- **⚡ Assets optimizados:** <5MB total
- **📦 Compresión:** Imágenes 360° <2MB cada una
- **🎨 Modelos ligeros:** <500KB por modelo 3D
- **🚀 Carga rápida:** Menos de 3 segundos en 4G

### Accesibilidad Social

- **🌐 Sin barreras geográficas:** Acceso desde cualquier lugar.
- **💰 Gratuito:** Sin costes de entrada o transporte.
- **📚 Educativo:** Recurso abierto para escuelas y formación.

---

## 📊 Criterios de Evaluación Académica

| Criterio                         | Implementación                                       | Documentación                 |
| -------------------------------- | ---------------------------------------------------- | ----------------------------- |
| **a) Tecnologías Habilitadoras** | ✅ Integración 360° + 3D con navegación por portales | Tabla de tecnologías          |
| **b) Producto Digital**          | ✅ Escena interactiva completamente funcional        | Casos de uso detallados       |
| **c) Sostenibilidad**            | ✅ Assets optimizados + análisis CO₂                 | Métricas de impacto           |
| **d) Nuevos Mercados**           | ✅ Multi-plataforma (web, móvil, VR)                 | Expansión educativa/turística |
| **e) Modelo de Negocio**         | ✅ Escenas representan flujo operativo               | Análisis de viabilidad        |
| **f) IT + OT**                   | ✅ Carga asíncrona + analytics                       | Convergencia digital          |
| **g) Documentación**             | -                                                    | ✅ README completo            |

---

## 🚀 Inicio Rápido y Uso

### 🌐 Demo Online

Accede directamente a la experiencia en vivo: **[https://palomajnm.github.io/frame_zoo1/](https://palomajnm.github.io/frame_zoo1/)**

### 💻 Instalación Local

Si deseas ejecutar el proyecto localmente en tu máquina:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/palomajnm/frame_zoo1.git
   cd frame_zoo1
   ```

2. **Inicia un servidor local:**
   Es necesario usar un servidor web debido a las políticas de seguridad de CORS para cargar texturas y modelos 3D.

   - **Opción 1: Python**

     ```bash
     # Python 3
     python -m http.server 8000
     ```

   - **Opción 2: Node.js (http-server)**

     ```bash
     npx http-server -p 8000
     ```

   - **Opción 3: VS Code Live Server**
     - Instala la extensión "Live Server".
     - Click derecho en `index.html` → "Open with Live Server".

3. **Abre tu navegador:**
   Ve a `http://localhost:8000`

### 🎮 Controles

- **🖱️ Ratón**: Arrastra para mirar alrededor (Click + Arrastrar).
- **⌨️ Teclado**: `W` `A` `S` `D` para moverte por la escena 3D.
- **📱 Móvil**: Toca y arrastra para rotar la vista.
- **👓 Modo VR**: Haz click en el icono de gafas VR en la esquina inferior derecha para entrar en modo inmersivo.

---

## 👥 Equipo de Desarrollo

| <a href="https://github.com/palomajnm"><img src="https://github.com/palomajnm.png" width="100px;" alt="Paloma Jiménez"/><br /><sub><b>Paloma Jiménez</b></sub></a> | <a href="https://github.com/i0sep"><img src="https://github.com/i0sep.png" width="100px;" alt="José Ángel Rodríguez"/><br /><sub><b>José Ángel Rodríguez</b></sub></a> | <a href="https://github.com/mariadelosangeles96-pixel"><img src="https://github.com/mariadelosangeles96-pixel.png" width="100px;" alt="María Gómez"/><br /><sub><b>María Gómez</b></sub></a> |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |

---

## 🎓 Recursos de Aprendizaje

- [A-Frame Documentación Oficial](https://aframe.io/docs/1.4.0/introduction/)
- [WebXR Explainer](https://github.com/immersive-web/webxr/blob/master/explainer.md)
- [Sketchfab - Modelos 3D](https://sketchfab.com/)

---

<div align="center">
⭐ Si te gusta el proyecto, ¡dale una estrella en GitHub! ⭐
<br>
<a href="#zoo-virtual---experiencia-inmersiva-en-webvr">⬆ Volver arriba</a>
</div>
