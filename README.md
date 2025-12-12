🦁 Zoo Virtual - Experiencia Inmersiva en WebVR
Una experiencia de zoológico virtual interactivo construida con A-Frame
🚀 Demo en Vivo
🎯 Sobre el Proyecto
Zoo Virtual es una experiencia inmersiva en realidad virtual que te permite explorar y aprender sobre fauna salvaje desde tu navegador. Desarrollado como proyecto educativo para el módulo de Digitalización Aplicada al Sector Productivo, combina fotografía 360°, modelos 3D y navegación interactiva para crear un entorno de aprendizaje innovador.
✨ Características
🌐 Imágenes 360° - Explora entornos naturales con fotografía panorámica inmersiva
🦒 Modelos 3D Realistas - Interactúa con animales modelados en alta calidad
🎮 Navegación Intuitiva - Portales interactivos para moverse entre escenas
🥽 Soporte VR Completo - Compatible con Oculus Quest, HTC Vive y más
📱 Multi-plataforma - Funciona en escritorio, móvil y dispositivos VR
♿ Accesible - Experiencia disponible 24/7 sin barreras geográficas

🎬 Escenas
1️⃣ Entrada Principal
Tipo: Imagen 360°
 Bienvenida al zoo con vista panorámica completa. Incluye portal interactivo para acceder a los hábitats e información de navegación básica.
2️⃣ Hábitat Safari
Tipo: Modelos 3D
 Explora el ecosistema africano con animales modelados: leones, elefantes, jirafas y más. Sistema de información educativa sobre cada especie.
3️⃣ Zona Interactiva
Tipo: Experiencia 3D
 Interacción directa con los animales, controles de cámara avanzados y contenido educativo sobre conservación y biodiversidad.

🛠️ Tecnologías Utilizadas
Tecnología
Uso
Versión
A-Frame
Framework WebVR
1.4.0
WebXR
API de Realidad Virtual
Latest
HTML5
Estructura
-
JavaScript
Interactividad
ES6+
GLTF/GLB
Modelos 3D
2.0

Componentes A-Frame
<!-- Cielo 360° -->
<a-sky src="assets/panorama.jpg"></a-sky>

<!-- Modelos 3D -->
<a-gltf-model src="assets/lion.glb"></a-gltf-model>

<!-- Interactividad -->
<a-entity event-set__click="scale: 1.2 1.2 1.2"></a-entity>

<!-- Animaciones -->
<a-animation attribute="rotation" to="0 360 0"></a-animation>
🚀 Inicio Rápido
Navegador Web
Accede directamente a la demo en vivo:


Accede a https://palomajnm.github.io/frame_zoo1/
Navega con:
🖱️ Ratón: Arrastra para mirar alrededor
⌨️ Teclado: WASD para moverte
📱 Móvil: Toca y arrastra
Interactúa:
Haz clic en los portales luminosos para cambiar de escena
Haz clic en los animales para ver información
Modo Realidad Virtual
Conecta tu dispositivo VR (Oculus Quest, HTC Vive, etc.)
Abre el navegador VR en tu dispositivo
Navega a https://palomajnm.github.io/frame_zoo1/
Presiona el icono de VR (👓) en la esquina inferior derecha
Disfruta de la experiencia inmersiva completa

📁 Estructura del Proyecto
frame_zoo1/
│
├── index.html              # Escena principal (Entrada)
├── safari.html             # Escena del hábitat
├── interactive.html        # Escena interactiva
│
├── content/                # Assets del proyecto
│   ├── images/            # Texturas 360° y UI
│   │   ├── sky-entrada.jpg
│   │   ├── sky-safari.jpg
│   │   └── ...
│   │
│   ├── models/            # Modelos 3D (GLB/GLTF)
│   │   ├── lion.glb
│   │   ├── elephant.glb
│   │   ├── giraffe.glb
│   │   └── ...
│   │
│   └── sounds/            # Audio ambiental (opcional)
│       └── ambient.mp3
│
├── screenshots/           # Capturas para documentación
│   ├── entrada.png
│   ├── safari.png
│   └── interactiva.png
│
└── README.md             # Este archivo


🌍 Impacto y Sostenibilidad
Beneficios Ambientales
Reducción de CO₂: ~200kg/año al evitar desplazamientos físicos
Ahorro energético: No requiere infraestructura física operativa 24/7
Conservación: Educación sin impacto en hábitats reales
Optimización Técnica
⚡ Assets optimizados: <5MB total
📦 Compresión: Imágenes 360° <2MB cada una
🎨 Modelos ligeros: <500KB por modelo 3D
🚀 Carga rápida: Menos de 3 segundos en 4G
Accesibilidad Social
🌐 Sin barreras geográficas: Acceso desde cualquier lugar
💰 Gratuito: Sin costes de entrada o transporte
📚 Educativo: Recurso para escuelas y formación
⏰ 24/7: Disponible en cualquier momento

📊 Criterios de Evaluación Académica
Criterio
Implementación
Documentación
a) Tecnologías Habilitadoras
✅ Integración 360° + 3D con navegación por portales
Tabla de tecnologías
b) Producto Digital
✅ Escena interactiva completamente funcional
Casos de uso detallados
c) Sostenibilidad
✅ Assets optimizados + análisis CO₂
Métricas de impacto
d) Nuevos Mercados
✅ Multi-plataforma (web, móvil, VR)
Expansión educativa/turística
e) Modelo de Negocio
✅ Escenas representan flujo operativo
Análisis de viabilidad
f) IT + OT
✅ Carga asíncrona + analytics
Convergencia digital
g) Documentación
-
✅ README completo


💻 Instalación Local
Si deseas ejecutar el proyecto localmente:
Prerrequisitos
Navegador moderno (Chrome 90+, Firefox 88+, Safari 15+)
Servidor web local (opcional, recomendado)
Pasos
Clona el repositorio:

 git clone https://github.com/palomajnm/frame_zoo1.git
cd frame_zoo1
Inicia un servidor local:

 Opción 1 - Python:

 python -m http.server 8000

 Opción 2 - Node.js:

 npx http-server -p 8000
 Opción 3 - VS Code:


Instala la extensión "Live Server"
Click derecho en index.html → "Open with Live Server"
Abre en tu navegador:

 http://localhost:8000


🎓 Recursos de Aprendizaje
A-Frame
Documentación Oficial
Escuela A-Frame
Ejemplos de la Comunidad
WebXR
WebXR Explainer
MDN Web Docs
Modelos 3D
Sketchfab - Modelos 3D gratuitos
Poly Haven - Assets de alta calidad

<table> <tr> <td align="center"> <img src="https://github.com/palomajnm.png" width="100px;" alt="Paloma Jiménez"/><br /> <sub><b>Paloma Jiménez</b></sub><br /> <a href="https://github.com/palomajnm">GitHub</a> </td> <td align="center"> <img src="https://github.com/i0sep.png" width="100px;" alt="José Ángel Rodríguez"/><br /> <sub><b>José Ángel Rodríguez</b></sub><br /> <a href="https://github.com/i0sep">GitHub</a> </td> <td align="center"> <img src="https://github.com/mariadelosangeles96-pixel.png" width="100px;" alt="María Gómez"/><br /> <sub><b>María Gómez</b></sub><br /> <a href="https://github.com/mariadelosangeles96-pixel">GitHub</a> </td> </tr> </table>
⭐ Si te gusta el proyecto, ¡dale una estrella en GitHub! ⭐
⬆ Volver arriba
</div>
