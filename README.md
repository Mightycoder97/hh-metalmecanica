# H&H Diseño, Fabricación y Montaje

Este es el repositorio oficial del sitio web institucional de **H&H**, una empresa especializada en metalmecánica, diseño de ingeniería estructural, fabricación en acero y montaje industrial. 

El proyecto está diseñado para transmitir una estética industrial sólida y profesional, con una navegación optimizada tanto para escritorio como para dispositivos móviles. Está construido con **Astro**, garantizando un rendimiento ultra-rápido, excelente SEO y un código moderno y eficiente utilizando CSS nativo con variables globales.

## 🚀 Stack Tecnológico

- **Framework**: [Astro](https://astro.build/)
- **Estilos**: Vanilla CSS (`global.css`) con un sistema de diseño basado en CSS Custom Properties.
- **Tipografía**: **Teko** (Encabezados) e **Inter** (Textos generales).
- **Despliegue**: Configurado con adaptador para **Vercel** (`@astrojs/vercel`).
- **SEO**: Incluye generación automática de Sitemap (`@astrojs/sitemap`).

## 📁 Estructura del Proyecto

```text
/
├── public/                 # Recursos estáticos (Imágenes y favicon)
├── src/
│   ├── components/         # Componentes modulares (Header, Footer, WhatsAppFloat)
│   ├── layouts/            # Plantilla estandarizada Base (Layout.astro)
│   ├── pages/              # Rutas generadas (index, nosotros, servicios, proyectos)
│   └── styles/             # Sistema de diseño centralizado (global.css)
├── astro.config.mjs        # Configuración principal de Astro
└── package.json            # Gestor de dependencias y scripts
```

## 🛠️ Instalación y Uso Local

Sigue estos pasos para arrancar el proyecto en un entorno de desarrollo:

1. **Clonar el repositorio**:
   ```bash
   git clone git@github.com:Mightycoder97/hh-metalmecanica.git
   cd hh-metalmecanica
   ```

2. **Instalar dependencias**:
   ```bash
   npm install
   ```

3. **Ejecutar el servidor local**:
   ```bash
   npm run dev
   ```
   El sitio web estará disponible para previsualización en `http://localhost:4321/`. Cualquier cambio en el código se reflejará instantáneamente.

## 📦 Despliegue a Producción

Para generar el "build" con todos los archivos estáticos minificados y super rápidos:

```bash
npm run build
```

## 🎨 Parámetros de Diseño

La apariencia gráfica del sitio recrea barras de acero pavonado o estructuras broncil con acabados industriales de corte recto:
- Radiales: Estricto control de `border-radius: 0px` para resaltar la solidez.
- **Azul Primario Metálico**: Emula acero o metal industrial oscuro (`--grad-primary`).
- **Naranja/Cobre de Acento**: Detalles llamativos color bronce/cobre (`--grad-accent`).

Todas las métricas de color, transiciones, sombras y breakpoints de pantalla están albergados ordenadamente en la parte más alta de `src/styles/global.css`.

---
© 2026 H&H Diseño Fabricación y Montaje. Todos los derechos reservados.
