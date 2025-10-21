'''
# Guía de Instalación de KardoTemplates

Este documento proporciona instrucciones detalladas para instalar y activar las plantillas de **KardoTemplates** en tu proyecto KardoCore.

## Requisitos Previos

- Un proyecto KardoCore funcional (versión >= 0.1.0).
- Acceso a la terminal o línea de comandos en tu servidor o entorno de desarrollo.
- KardoCore CLI instalado y configurado.

## Método 1: Instalación con KardoCore CLI (Recomendado)

El método más sencillo y recomendado es utilizar el gestor de paquetes integrado en KardoCore CLI. El sistema se encargará de descargar, verificar e instalar la plantilla en la ubicación correcta.

### Paso 1: Identificar la Plantilla

Primero, busca el `slug` de la plantilla que deseas instalar. Puedes encontrar la lista completa en el [Índice de Plantillas](./TEMPLATES.md).

### Paso 2: Ejecutar el Comando de Instalación

Usa el comando `kardo theme install` seguido del `slug` de la plantilla.

**Para plantillas Frontend:**

```bash
# Ejemplo: Instalar la plantilla "Wellness Clinic"
kardo theme install wellness-clinic
```

**Para plantillas Backend:**

Para las plantillas de administración (paneles y dashboards), debes añadir la bandera `--backend`.

```bash
# Ejemplo: Instalar la plantilla de admin "Modern Admin"
kardo theme install admin-modern --backend
```

El CLI descargará la plantilla desde el repositorio oficial de KardoTemplates y la colocará en el directorio apropiado (`/themes/frontend/` o `/themes/backend/`).

### Paso 3: Activar la Plantilla

1.  Accede al panel de administración de tu sitio KardoCore.
2.  Navega a la sección **Apariencia > Temas**.
3.  Busca la plantilla recién instalada en la lista.
4.  Haz clic en el botón **"Activar"**.

¡Listo! Tu sitio ahora usará la nueva plantilla.

## Método 2: Instalación Manual con Git

Si prefieres tener más control o quieres modificar las plantillas, puedes clonar el repositorio y mover los archivos manualmente.

### Paso 1: Clona el Repositorio

En una ubicación temporal, clona el repositorio completo de KardoTemplates.

```bash
git clone https://github.com/webcien/KardoTemplates.git
```

### Paso 2: Copia la Plantilla a tu Proyecto

Navega dentro del repositorio clonado y copia la carpeta de la plantilla que deseas a tu proyecto KardoCore.

**Para plantillas Frontend:**

```bash
# Ejemplo: Copiar la plantilla "Startup Agency" a tu proyecto
cp -R KardoTemplates/frontend/negocios/startup-agency/ /ruta/a/tu/proyecto/themes/frontend/
```

**Para plantillas Backend:**

```bash
# Ejemplo: Copiar la plantilla "Analytics Dashboard" a tu proyecto
cp -R KardoTemplates/backend/dashboard-themes/dashboard-analytics/ /ruta/a/tu/proyecto/themes/backend/
```

### Paso 3: Activar la Plantilla

El proceso de activación es el mismo que en el Método 1. Ve a tu panel de administración, busca la plantilla y actívala.

## Solución de Problemas

- **Comando `kardo` no encontrado**: Asegúrate de que KardoCore CLI esté instalado correctamente y que su ruta esté en el PATH de tu sistema.
- **La plantilla no aparece en el admin**: Verifica que hayas copiado la carpeta de la plantilla en el directorio correcto (`themes/frontend` o `themes/backend`) y que la estructura de archivos de la plantilla (incluyendo `theme.yaml`) esté intacta.
- **Errores de permisos**: Asegúrate de que los archivos de la plantilla tengan los permisos de lectura correctos para que el servidor web pueda acceder a ellos.

---

Si sigues teniendo problemas, no dudes en [abrir un issue](https://github.com/webcien/KardoTemplates/issues) en nuestro repositorio de GitHub.
'''
