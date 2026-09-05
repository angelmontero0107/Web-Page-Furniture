# 🛋️ APEX DIGITAL — Mueblería Web

> **Tu espacio, potenciado.** Sitio web moderno para una mueblería, construido con HTML, CSS Vanilla y JavaScript puro usando Vite como bundler.

---

## 📸 Vista General

Página web corporativa para **APEX DIGITAL Mueblería**, con diseño oscuro premium, animaciones suaves y diseño completamente responsivo.

## ✨ Características

- 🌙 **Diseño oscuro premium** con acentos en azul y naranja
- 📱 **Totalmente responsivo** — optimizado para móvil, tablet y escritorio
- 🎞️ **Animaciones al hacer scroll** con `IntersectionObserver`
- 🍔 **Menú hamburguesa** para dispositivos móviles
- 🔍 **SEO optimizado** con meta tags y estructura semántica HTML5
- ⚡ **Vite** como bundler para desarrollo ultra rápido

## 📂 Estructura del Proyecto

```
Muebleria-Web/
├── public/
│   ├── favicon.svg          # Ícono del sitio
│   └── icons.svg            # Sprites SVG
├── src/
│   ├── assets/
│   │   └── hero.png         # Imagen principal
│   ├── main.js              # Lógica JavaScript (scroll, menú, animaciones)
│   └── style.css            # Estilos globales
├── index.html               # Página principal
├── package.json
└── .gitignore
```

## 📋 Secciones de la Página

| Sección           | Descripción                                                      |
|-------------------|------------------------------------------------------------------|
| **Inicio**        | Hero con llamada a la acción                                     |
| **Nosotros**      | Historia y valores de la empresa                                 |
| **Departamentos** | Catálogo: Salas, Comedores, Recámaras y Oficina                  |
| **Servicios**     | Entrega a domicilio, armado profesional y asesoría en diseño     |
| **Contacto**      | Formulario de contacto e información de ubicación                |

## 🚀 Inicio Rápido

### Requisitos

- [Node.js](https://nodejs.org/) v18 o superior
- npm v9 o superior

### Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/muebleria-web.git
cd muebleria-web

# 2. Instalar dependencias
npm install

# 3. Iniciar servidor de desarrollo
npm run dev
```

El sitio estará disponible en `http://localhost:5173` (puerto por defecto de Vite).

### Scripts disponibles

| Comando           | Descripción                                      |
|-------------------|--------------------------------------------------|
| `npm run dev`     | Inicia el servidor de desarrollo con hot-reload  |
| `npm run build`   | Genera la build de producción en `/dist`         |
| `npm run preview` | Previsualiza la build de producción localmente   |

## 🛠️ Tecnologías

| Tecnología   | Uso                                          |
|--------------|----------------------------------------------|
| HTML5        | Estructura semántica                          |
| CSS Vanilla  | Estilos, glassmorphism, animaciones           |
| JavaScript   | Interactividad y animaciones                  |
| [Vite](https://vite.dev/) | Bundler y servidor de desarrollo |
| [Outfit](https://fonts.google.com/specimen/Outfit) (Google Fonts) | Tipografía principal |

## 🌐 Despliegue

Este proyecto puede desplegarse fácilmente en:

- **[Vercel](https://vercel.com/)**: Conecta el repositorio y despliega automáticamente.
- **[Netlify](https://www.netlify.com/)**: Arrastra la carpeta `/dist` o conecta el repo.
- **GitHub Pages**: Ejecuta `npm run build` y publica el contenido de la carpeta `/dist`.

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

<p align="center">
  Hecho con ❤️ por el equipo de <strong>APEX DIGITAL</strong>
</p>
