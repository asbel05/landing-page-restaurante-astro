# Food Made Good - Landing Page para Restaurante
Este proyecto es un sitio web moderno y responsive para un restaurante, construido con **Astro** y **Bootstrap 5**.

## 🚀 Instrucciones para ejecutar el proyecto localmente

Sigue estos pasos para ejecutar el proyecto en tu máquina:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/asbel05/landing-page-restaurante-astro.git
   cd landing-page-restaurante-astro

2. **Instala las dependencias**:
   ```bash
   npm install
   
2. **Ejecuta el servidor de desarrollo**:
   ```bash
   npm run dev

2. **Abre el proyecto en tu navegador**:
   ```bash
   Abre el proyecto en tu navegador:
   Visita **http://localhost:3000** para ver el sitio.



## 🏗️ Explicación de la estructura

1. **`public/`**:
   - Contiene todos los archivos estáticos, como imágenes, fuentes y scripts adicionales.
   - Las imágenes están organizadas en subcarpetas (`images/menu`, `images/testimonios`, etc.) para mantener un orden claro.

2. **`src/`**:
   - Es el núcleo del proyecto, donde se encuentra todo el código fuente.
   - **`components/`**: Contiene componentes reutilizables de Astro, como el header, footer, hero, etc. Esto permite un código modular y fácil de mantener.
   - **`layouts/`**: Aquí se define el layout principal (`Layout.astro`), que envuelve todas las páginas y proporciona estilos y scripts globales.
   - **`pages/`**: Contiene las páginas del sitio. En este caso, solo tenemos `index.astro`, que es la página de inicio.

3. **`astro.config.mjs`**:
   - Archivo de configuración de Astro, donde se pueden definir plugins, opciones de build, y más.

4. **`package.json`**:
   - Define las dependencias del proyecto (como Bootstrap, AOS, etc.) y los scripts para ejecutar y construir el proyecto.

5. **`README.md`**:
   - Este archivo, que proporciona una guía completa sobre el proyecto.



## 🎨 Decisiones de diseño
1. **`Diseño Responsive`**:
- El sitio está diseñado para funcionar perfectamente en dispositivos móviles, tablets y desktop.
Se utilizó Bootstrap 5 para garantizar un diseño responsive y consistente.

2. **`Animaciones`**:
- Se integró AOS (Animate On Scroll) para agregar animaciones sutiles al hacer scroll.

3. **`Optimización de imágenes`**:
- Todas las imágenes usan el atributo loading="lazy" para cargarse de manera eficiente.
Las imágenes están optimizadas para reducir el tiempo de carga.



## 🛠️ Tecnologías utilizadas
1. **`Astro`**: Framework moderno para construir sitios estáticos rápidos y optimizados.

2. **`Bootstrap 5`**: Framework CSS para diseño responsive y componentes preconstruidos.

3. **`Bootstrap Icons`**: Iconos gratuitos y de alta calidad para el sitio.

4. **`AOS`**: Biblioteca para animaciones al hacer scroll.


## Desarrollado por: Asbel Cristobal Avila
