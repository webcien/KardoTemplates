# Wellness Clinic - Plantilla para KardoCore

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![KardoCore](https://img.shields.io/badge/KardoCore-%3E%3D0.1.0-orange.svg)

Plantilla moderna y profesional diseñada específicamente para clínicas de salud, centros de bienestar, consultorios médicos y profesionales de la salud.

## 📋 Características

- ✅ **Diseño Responsive**: Optimizado para dispositivos móviles, tablets y escritorio
- ✅ **Sistema de Citas**: Integración lista para sistema de agendamiento online
- ✅ **SEO Optimizado**: Metadatos completos y estructura semántica
- ✅ **Accesibilidad**: Cumple con estándares WCAG 2.1 AA
- ✅ **Rendimiento**: Carga rápida y optimización de imágenes
- ✅ **Secciones Incluidas**:
  - Hero section con llamado a la acción
  - Servicios médicos destacados
  - Perfiles de equipo médico
  - Testimonios de pacientes
  - Blog de salud y consejos
  - Formularios de contacto

## 🎨 Paleta de Colores

- **Primary**: `#0EA5E9` (Azul cielo)
- **Secondary**: `#06B6D4` (Cyan)
- **Accent**: `#10B981` (Verde esmeralda)
- **Background**: `#FFFFFF` (Blanco)
- **Text**: `#1F2937` (Gris oscuro)

## 📦 Instalación

### Método 1: Usando KardoCore CLI

```bash
kardo theme install wellness-clinic
```

### Método 2: Instalación Manual

1. Descarga la plantilla desde el repositorio
2. Extrae los archivos en tu directorio de temas de KardoCore:
   ```
   /tu-proyecto/themes/frontend/wellness-clinic/
   ```
3. Activa la plantilla desde el panel de administración de KardoCore

### Método 3: Usando Git

```bash
cd /tu-proyecto/themes/frontend/
git clone https://github.com/webcien/KardoTemplates.git temp
mv temp/frontend/salud-bienestar/wellness-clinic ./
rm -rf temp
```

## 🚀 Uso

### Activar la Plantilla

1. Accede al panel de administración de KardoCore
2. Ve a **Apariencia → Temas**
3. Busca "Wellness Clinic" y haz clic en **Activar**

### Personalización

#### Colores

Edita el archivo `static/css/main.css` y modifica las variables CSS en `:root`:

```css
:root {
    --color-primary: #0EA5E9;
    --color-secondary: #06B6D4;
    --color-accent: #10B981;
    /* ... más colores */
}
```

#### Logo

Reemplaza el archivo `static/images/logo.svg` con tu propio logo.

#### Contenido

El contenido se gestiona desde el panel de administración de KardoCore:

- **Páginas**: Crea páginas para Servicios, Equipo, Contacto, etc.
- **Posts**: Publica artículos en el blog de salud
- **Menús**: Configura la navegación principal
- **Widgets**: Añade elementos adicionales en áreas configurables

## 📁 Estructura de Archivos

```
wellness-clinic/
├── theme.yaml              # Metadatos de la plantilla
├── README.md              # Este archivo
├── templates/             # Plantillas HTML
│   ├── base.html         # Plantilla base
│   ├── index.html        # Página de inicio
│   ├── services.html     # Página de servicios
│   ├── team.html         # Página de equipo
│   ├── blog.html         # Listado de blog
│   ├── post.html         # Artículo individual
│   └── contact.html      # Página de contacto
├── static/               # Archivos estáticos
│   ├── css/
│   │   └── main.css      # Estilos principales
│   ├── js/
│   │   └── main.js       # JavaScript principal
│   └── images/           # Imágenes de la plantilla
└── screenshots/          # Capturas de pantalla
```

## 🔧 Requisitos

- **KardoCore**: >= 0.1.0
- **KardoCSS**: >= 0.1.0 (opcional, estilos incluidos)
- **Python**: >= 3.11
- **Navegadores soportados**:
  - Chrome/Edge >= 90
  - Firefox >= 88
  - Safari >= 14
  - Opera >= 76

## 🎯 Casos de Uso Ideales

- Clínicas médicas generales
- Consultorios especializados
- Centros de bienestar y spa
- Clínicas dentales
- Centros de fisioterapia
- Clínicas de nutrición
- Centros de salud mental
- Hospitales privados

## 🔌 Integraciones Recomendadas

- **Sistema de Citas**: Compatible con plugins de agendamiento
- **Pasarelas de Pago**: Para pagos de consultas online
- **Telemedicina**: Integración con plataformas de videollamadas
- **Email Marketing**: Newsletters de salud y recordatorios
- **Google Maps**: Para mostrar ubicación de la clínica
- **Chat en Vivo**: Atención al paciente en tiempo real

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Accesibilidad

Esta plantilla cumple con los estándares de accesibilidad WCAG 2.1 nivel AA:

- Contraste de colores adecuado
- Navegación por teclado
- Etiquetas ARIA apropiadas
- Textos alternativos en imágenes
- Estructura semántica HTML5

## 🐛 Soporte y Reportes de Bugs

Si encuentras algún problema o tienes sugerencias:

1. Revisa los [issues existentes](https://github.com/webcien/KardoTemplates/issues)
2. Crea un nuevo issue con detalles del problema
3. Incluye capturas de pantalla si es posible

## 📄 Licencia

MIT License - Consulta el archivo [LICENSE](../../../LICENSE) para más detalles.

## 👥 Créditos

- **Desarrollado por**: KardoCore Team
- **Framework**: [KardoCore](https://github.com/webcien/KardoCore)
- **Inspiración**: Diseño moderno de sitios web de salud

## 🔄 Changelog

### v1.0.0 (2025-10-21)
- ✨ Lanzamiento inicial
- ✅ Diseño responsive completo
- ✅ Sistema de citas integrable
- ✅ Blog de salud
- ✅ Perfiles de equipo médico
- ✅ Testimonios de pacientes
- ✅ SEO optimizado

## 🚀 Próximas Características

- [ ] Modo oscuro
- [ ] Más variaciones de color
- [ ] Integración con calendario
- [ ] Portal de pacientes
- [ ] Sistema de historias clínicas
- [ ] Multiidioma

---

**¿Necesitas ayuda?** Visita la [documentación de KardoCore](https://github.com/webcien/KardoCore) o únete a nuestra comunidad.

