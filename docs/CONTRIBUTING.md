'''
# Guía de Contribución para KardoTemplates

¡Gracias por tu interés en contribuir a KardoTemplates! Estamos emocionados de ver lo que la comunidad puede aportar a esta colección de plantillas.

Siguiendo estas pautas, nos ayudas a mantener la calidad y consistencia del proyecto.

## ¿Cómo Puedo Contribuir?

- **Reportando Bugs**: Si encuentras un error en una plantilla, por favor, [abre un issue](https://github.com/webcien/KardoTemplates/issues).
- **Sugiriendo Mejoras**: ¿Tienes una idea para mejorar una plantilla existente? ¡Nos encantaría escucharla!
- **Creando Nuevas Plantillas**: Si tienes una idea para una nueva categoría o plantilla, puedes proponerla o incluso crearla tú mismo.
- **Mejorando la Documentación**: Si algo no está claro en nuestra documentación, ayúdanos a mejorarlo.

## Creando una Nueva Plantilla

Este es el proceso recomendado para crear y proponer una nueva plantilla.

### 1. Estructura de la Plantilla

Asegúrate de que tu plantilla siga la estructura de directorios estándar:

```
mi-nueva-plantilla/
├── theme.yaml              # Metadatos de la plantilla (¡muy importante!)
├── README.md               # Documentación de la plantilla
├── templates/              # Plantillas HTML (compatibles con KardoTheme)
│   ├── base.html
│   └── index.html
│   └── ...
├── static/                 # Archivos estáticos
│   ├── css/                # CSS (preferiblemente usando KardoCSS)
│   ├── js/                 # JavaScript
│   └── images/             # Imágenes optimizadas para la web
└── screenshots/            # Capturas de pantalla (desktop, mobile)
```

### 2. `theme.yaml`

El archivo `theme.yaml` es crucial. Contiene todos los metadatos que KardoCore utiliza para identificar y gestionar la plantilla. Asegúrate de rellenar todos los campos relevantes.

```yaml
name: "Mi Nueva Plantilla"
slug: "mi-nueva-plantilla" # Slug único en minúsculas y con guiones
version: "1.0.0"
description: "Una descripción clara y concisa de la plantilla."
author: "Tu Nombre"
author_url: "https://tu-website.com"
license: "MIT"
category: "categoria-existente" # O una nueva categoría propuesta
type: "frontend" # o "backend"
tags:
  - "tag1"
  - "tag2"

requirements:
  kardocore: ">=0.1.0"
  kardocss: ">=0.1.0"

features:
  - "Característica 1"
  - "Característica 2"

screenshots:
  - "screenshot-desktop.png"
  - "screenshot-mobile.png"

colors:
  primary: "#RRGGBB"
  secondary: "#RRGGBB"
  accent: "#RRGGBB"
```

### 3. Uso de KardoCSS

**Es altamente recomendable que utilices KardoCSS** para estilizar tu plantilla. Esto asegura consistencia, personalización y un rendimiento óptimo. Evita escribir grandes bloques de CSS personalizado si una clase de utilidad de KardoCSS ya existe.

- **Define tus colores primarios** en un archivo `custom.css` y úsalos en tus clases de KardoCSS.
- **Aprovecha las clases utilitarias** para espaciado, tipografía, flexbox, grid, etc.

### 4. Envío de la Contribución (Pull Request)

1.  **Haz un Fork** del repositorio `webcien/KardoTemplates` a tu propia cuenta de GitHub.
2.  **Crea una nueva Rama** para tu contribución: `git checkout -b feature/mi-nueva-plantilla`.
3.  **Añade tu plantilla** en la categoría correspondiente.
4.  **Haz Commit** de tus cambios con un mensaje claro: `git commit -m "feat: Añade la plantilla 'Mi Nueva Plantilla' a la categoría X"`.
5.  **Haz Push** a tu rama: `git push origin feature/mi-nueva-plantilla`.
6.  **Abre un Pull Request** desde tu fork al repositorio principal.

El equipo de KardoCore revisará tu contribución y te dará feedback lo antes posible.

## Guía de Estilo de Código

- **HTML**: Usa HTML5 semántico. Mantén una indentación limpia.
- **CSS**: Sigue los principios de KardoCSS. Nombra las clases personalizadas de forma clara y específica.
- **JavaScript**: Escribe JavaScript moderno (ES6+). Añade comentarios cuando el código sea complejo.
- **YAML**: Usa indentación de 2 espacios.

Gracias de nuevo por tu interés en hacer de KardoTemplates un recurso aún mejor para la comunidad de KardoCore.
'''
