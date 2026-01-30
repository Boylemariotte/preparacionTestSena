# Prueba SENA - Evaluación de Competencias

## Descripción
Prueba de evaluación de competencias para desarrollador de sistemas del SENA.

## Estructura del Proyecto
- `index.html` - Página principal con menú de navegación
- `pagina1.html` - Consejos y Liderazgo (2 preguntas)
- `pagina2.html` - Habilidades y Presentación (2 preguntas)
- `pagina3.html` - Planificación y Evaluación Final (1 pregunta + resultados)
- `pagina4_sistemas.html` - Desarrollo de Sistemas (5 preguntas técnicas)
- `prueba_sena.html` - Versión completa con todas las preguntas

## Despliegue en Netlify

### Pasos para desplegar:

1. **Subir a GitHub:**
   ```bash
   git add .
   git commit -m "Add Prueba SENA static site"
   git push origin main
   ```

2. **Configurar en Netlify:**
   - Ve a [Netlify](https://app.netlify.com/)
   - Click en "New site from Git"
   - Conecta tu repositorio de GitHub
   - Configura los siguientes ajustes:
     - **Build command:** `echo "No build required"`
     - **Publish directory:** `.` (o dejar en blanco)
   - Click en "Deploy site"

3. **Configuración adicional (si es necesario):**
   - En Site settings → Build & deploy → Environment
   - Asegúrate que el "Publish directory" esté configurado correctamente

## Archivos de Configuración
- `netlify.toml` - Configuración de despliegue para Netlify
- `_redirects` - Redirecciones para manejar rutas
- `package.json` - Información del proyecto

## Características
- Diseño responsivo
- Guardado automático de progreso
- Navegación entre páginas
- Evaluación automática de respuestas
- Interfaz moderna e intuitiva
