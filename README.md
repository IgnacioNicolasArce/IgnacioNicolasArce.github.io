# 🚀 Portfolio Personal - Ignacio Arce

Portfolio personal diseñado para presentarme como **Desarrollador Full Stack** y buscar mis primeras experiencias laborales en el área del desarrollo web.

## 📋 Descripción

Este sitio web es mi carta de presentación profesional, donde muestro mis habilidades técnicas, certificaciones y brindo información de contacto para oportunidades laborales. El proyecto está desarrollado con tecnologías modernas y cuenta con un diseño responsive, elegante y profesional.

## ✨ Características

- 🌓 **Tema Claro/Oscuro**: Cambia entre modo claro y oscuro según tu preferencia
- 🌍 **Multiidioma**: Soporte completo para Español e Inglés
- 📱 **Diseño Responsive**: Adaptado para dispositivos móviles, tablets y desktop
- 🎨 **Diseño Moderno**: Interfaz premium con gradientes, animaciones suaves y micro-interacciones
- ⚡ **Rendimiento Optimizado**: Carga rápida y experiencia fluida
- 📧 **Formulario de Contacto**: Integración con Formspree para recibir mensajes directamente
- 🎯 **Navegación Suave**: Scroll animado entre secciones
- 📜 **Certificaciones Interactivas**: Cards expandibles con detalles de mis diplomas

## 🛠️ Tecnologías Utilizadas

### Frontend
- **[Astro](https://astro.build/)** - Framework web moderno para sitios de alto rendimiento
- **TypeScript** - Tipado estático para mayor robustez del código
- **HTML5 & CSS3** - Estructura y estilos modernos
- **Vanilla JavaScript** - Interactividad sin dependencias pesadas

### Características Técnicas
- **Sistema de Temas**: Variables CSS personalizadas para theming
- **i18n**: Sistema de internacionalización con rutas dinámicas
- **CSS Variables**: Para gestión consistente de colores y estilos
- **Google Fonts**: Tipografía Outfit para un look moderno
- **Formspree**: Servicio de formularios sin backend

## 📂 Estructura del Proyecto

```
ignacioarce.dev/
├── src/
│   ├── components/         # Componentes reutilizables
│   │   ├── ThemeToggle.astro
│   │   ├── LanguagePicker.astro
│   │   ├── skills.astro
│   │   ├── certificates.astro
│   │   ├── contact.astro
│   │   └── TechMarquee.astro
│   ├── i18n/              # Traducciones
│   │   └── ui.ts
│   ├── pages/             # Páginas del sitio
│   │   ├── index.astro    # Página principal (español)
│   │   └── en/
│   │       └── index.astro # Página en inglés
│   └── styles/            # Estilos globales
│       └── global.css
├── public/                # Assets estáticos
└── astro.config.mjs       # Configuración de Astro
```

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 18 o superior)
- npm o yarn

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/ignacioarce.dev.git
cd ignacioarce.dev
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Ejecutar en modo desarrollo**
```bash
npm run dev
```

4. **Construir para producción**
```bash
npm run build
```

5. **Vista previa de producción**
```bash
npm run preview
```

## 🎨 Personalización de Colores

Los colores del sitio se pueden personalizar fácilmente editando las variables CSS en `src/styles/global.css`:

```css
:root {
    --bg-color: #0d1117;
    --text-color: #e6edf3;
    --accent-color: #58a6ff;
    --secondary-bg: #161b22;
    --border-color: #30363d;
}
```

## 🌐 Idiomas Soportados

- 🇪🇸 **Español** (por defecto) - `/`
- 🇬🇧 **Inglés** - `/en/`

Las traducciones se gestionan en `src/i18n/ui.ts`

## 📧 Contacto

El formulario de contacto está configurado con Formspree. Para modificar el destinatario, actualiza la URL en `src/components/contact.astro`:

```astro
<form
    action="https://formspree.io/f/TU_ENDPOINT"
    method="POST"
>
```

## 📝 Secciones del Sitio

1. **Sobre Mí**: Presentación personal y trayectoria profesional
2. **Habilidades**: Tecnologías y herramientas que domino
3. **Certificaciones**: Diplomas y cursos completados
4. **Proyectos**: Próximamente...
5. **Contacto**: Formulario y enlaces directos

## 🎯 Objetivo

Este portfolio tiene como objetivo principal:
- Presentar mi perfil profesional de manera atractiva
- Demostrar mis habilidades en desarrollo web
- Facilitar el contacto con reclutadores y empresas
- Conseguir mis primeras experiencias laborales en desarrollo web

## 👨‍💻 Sobre Mí

Soy **Técnico Electrónico y Desarrollador Full Stack** con formación en React.js, Node.js, Angular y gestión de APIs REST. Busco activamente integrarme a un equipo de desarrollo IT donde pueda aportar valor a través de proyectos desafiantes.

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

Si encuentras algún bug o tienes sugerencias de mejora, no dudes en abrir un issue o enviar un pull request.

---

⭐ **Si te gusta este proyecto, no olvides darle una estrella!**

Desarrollado con ❤️ por Ignacio Arce
