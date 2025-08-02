# 🏄‍♀️ Surferss Wave - Sitio Web Oficial

![373_1x_shots_so](https://github.com/user-attachments/assets/d80a36af-7bb9-40fd-ad3e-1a59a0e77fff)

Un sitio web moderno y optimizado para promocionar la experiencia exclusiva de surf "Surferss Wave" con Sofía Surferss. Construido con tecnologías web modernas y optimizado para SEO.

## 🌊 Descripción del Evento

**Surferss Wave** es una experiencia única e exclusiva de surf que combina:

- 🏄‍♀️ **Clases de surf profesionales**
- 🧘‍♀️ **Sesiones de yoga matutinas**
- 🎉 **Fiestas y DJ sets nocturnos**
- 🎨 **Talleres de cerámica**
- 🏖️ **Actividades en la playa**
- 🎯 **Activaciones de marcas colaboradoras**
- 🎮 **Juegos nocturnos**

### 📍 Ubicación

- **Lugar**: Latas Surf House
- **Ubicación**: Somo, Cantabria, España
- **Fechas**: 1-8 de Junio, 2025

### 🎫 Acceso Exclusivo

Este viaje es **exclusivo** y solo se puede acceder a través de las marcas embajadoras de Surferss Wave.

## 🚀 Tecnologías Utilizadas

- **⚡ [Astro 5.12.7](https://astro.build/)** - Framework web moderno
- **🎨 [Tailwind CSS 4.1.11](https://tailwindcss.com/)** - Framework CSS utility-first
- **📱 Diseño Responsive** - Optimizado para móvil y desktop
- **🔍 SEO Optimizado** - Meta tags y datos estructurados Schema.org
- **⚡ [Vercel Analytics](https://vercel.com/analytics)** - Analíticas web
- **🖼️ Optimización de imágenes** - Formato WebP y lazy loading
- **✨ TypeScript** - Tipado estático
- **🧹 ESLint + Prettier** - Linting y formateo de código

## 📁 Estructura del Proyecto

```text
sofia-surferss-web/
├── public/                          # Archivos estáticos
│   ├── favicon.svg
│   ├── logo-header-surferss-wave.svg
│   ├── logo-surferrss-wave.svg
│   ├── og.jpg                       # Imagen Open Graph
│   └── googlee0d1fc8a4713db25.html  # Verificación Google
├── src/
│   ├── assets/                      # Imágenes y recursos
│   │   ├── sofia-surferss-hero.png
│   │   ├── sofia-surferss-snorkel.webp
│   │   └── section-*-bg.webp        # Imágenes de fondo
│   ├── components/                  # Componentes Astro
│   │   ├── Activities.astro         # Sección de actividades
│   │   ├── Footer.astro             # Pie de página
│   │   ├── Hero.astro               # Sección principal
│   │   ├── How.astro                # Cómo participar
│   │   ├── Navbar.astro             # Navegación
│   │   ├── Section.astro            # Componente base
│   │   ├── WhatIncludes.astro       # Qué incluye
│   │   └── Where.astro              # Ubicación
│   ├── layouts/
│   │   └── Layout.astro             # Layout principal con SEO
│   ├── pages/
│   │   └── index.astro              # Página principal
│   └── styles/
│       └── global.css               # Estilos globales
├── astro.config.mjs                 # Configuración Astro
├── package.json                     # Dependencias y scripts
├── tailwind.config.js               # Configuración Tailwind
└── tsconfig.json                    # Configuración TypeScript
```

## 🛠️ Instalación y Configuración

### Prerrequisitos

- Node.js 18+
- npm, yarn o pnpm

### Instalación

```bash
# Clonar el repositorio
git clone <repository-url>
cd sofia-surferss-web

# Instalar dependencias
npm install
# o
pnpm install
# o
yarn install
```

### Scripts Disponibles

```bash
# Desarrollo local
npm run dev          # Inicia servidor de desarrollo

# Construcción
npm run build        # Construye para producción
npm run preview      # Previsualiza build de producción

# Calidad de código
npm run lint         # Ejecuta ESLint
npm run lint:fix     # Corrige errores automáticamente
npm run format       # Formatea código con Prettier
npm run format:check # Verifica formato
```

## 🎨 Características del Diseño

### 🎨 Paleta de Colores

- **Primario**: Azul surf vibrante
- **Secundario**: Colores oceánicos
- **Tipografía**: Bebas Neue (headers) + Sans-serif (cuerpo)

### 📱 Responsive Design

- **Mobile First**: Optimizado para dispositivos móviles
- **Breakpoints**: sm, md, lg, xl
- **Imágenes adaptativas**: Diferentes layouts para móvil/desktop

### ♿ Accesibilidad

- **ARIA labels** en navegación
- **Alt text** descriptivo en imágenes
- **Contraste** adecuado de colores
- **Navegación por teclado** optimizada

## 🔍 SEO y Optimización

### 📊 Datos Estructurados (Schema.org)

```json
{
  "@context": "https://schema.org",
  "@type": "Event",
  "name": "Surferss Wave - Experiencia exclusiva de Surf",
  "startDate": "2025-06-01",
  "endDate": "2025-06-08",
  "location": {
    "@type": "Place",
    "name": "Latas Surf House",
    "address": {
      "addressLocality": "Somo",
      "addressRegion": "Cantabria",
      "addressCountry": "ES"
    }
  },
  "performer": {
    "@type": "Person",
    "name": "Sofía Surferss"
  }
}
```

### 🏷️ Meta Tags Incluidos

- **Title & Description** optimizados
- **Open Graph** (Facebook/LinkedIn)
- **Twitter Cards**
- **Canonical URLs**
- **Keywords** relevantes

### ⚡ Optimización de Rendimiento

- **Lazy loading** de imágenes
- **Formato WebP** para imágenes
- **Compresión** de assets
- **Critical CSS** inline
- **Preload** de recursos importantes

## 🚀 Despliegue

### Vercel (Recomendado)

```bash
# Instalar Vercel CLI
npm i -g vercel

# Desplegar
vercel
```

### Netlify

```bash
# Build command
npm run build

# Publish directory
dist/
```

### Otras Plataformas

El proyecto es compatible con cualquier servicio que soporte sitios estáticos (GitHub Pages, Cloudflare Pages, etc.)

## 🎯 Secciones del Sitio

### 🏠 Hero Section

- **Imagen principal** de Sofía con tabla de surf
- **Mensaje de bienvenida** impactante
- **Logo adaptativo** móvil/desktop

### 📍 ¿Dónde es?

- **Ubicación**: Somo, Cantabria - Latas Surf House
- **Imágenes** de surfistas en el mar
- **Diseño visual** inmersivo

### 🚗 ¿Cómo puedo ir?

- **Acceso exclusivo** a través marcas embajadoras
- **Imagen** de Sofía con equipo de snorkel

### 📦 ¿Qué incluye?

- ✅ **Alojamiento completo**
- ✅ **Todas las comidas** (desayuno, comida, cena)
- ✅ **Clases de surf**
- ✅ **Todas las actividades**
- ⚠️ _Desplazamiento no incluido_

### 🎯 Actividades

- **Clases de yoga**
- **Juegos nocturnos**
- **Clases de surf**
- **Activaciones de marcas**
- **Fiestas - DJ Set**
- **Taller de cerámica**

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### 📋 Estándares de Código

- Usar **ESLint** y **Prettier** configurados
- Seguir convenciones de **TypeScript**
- Escribir componentes **accesibles**
- Optimizar **rendimiento** de imágenes

## 📝 Licencia

Este proyecto está bajo la licencia [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

[![CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

**Esto significa que puedes:**

- ✅ **Compartir** — copiar y redistribuir el material en cualquier medio o formato

**Bajo los siguientes términos:**

- 🏷️ **Atribución** — Debes dar crédito apropiado, proporcionar un enlace a la licencia e indicar si se han realizado cambios
- 🚫 **No Comercial** — No puedes utilizar el material para fines comerciales
- 🔒 **Sin Derivadas** — Si remezclas, transformas o construyes sobre el material, no puedes distribuir el material modificado

Ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

---

### 🏄‍♀️ ¡Vive la experiencia Surferss Wave! 🌊
