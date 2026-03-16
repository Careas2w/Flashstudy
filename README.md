# Flashcards Coreano - GitHub Pages

Versión preparada para publicar en GitHub Pages con mejora de audio **100% gratis** sin Azure.

## Mejoras de audio incluidas
- selección más inteligente de la mejor voz disponible por idioma;
- precarga y calentamiento del motor de voz para iPad/Safari y otros navegadores;
- velocidad mejorada:
  - coreano normal: 0.92
  - coreano lento: 0.72
  - español normal: 0.98
  - español lento: 0.80
- limpieza del texto antes de reproducir para reducir pausas raras;
- guardado local de la preferencia de velocidad y de la voz elegida.

## Archivos
- `index.html`: app principal
- `app.js`: registro del service worker
- `manifest.webmanifest`: configuración PWA
- `sw.js`: caché versionada para forzar mejor la actualización
- `icons/`: iconos de la app
- `.nojekyll`: evita procesado innecesario en GitHub Pages

## Despliegue rápido
1. Crea o abre tu repositorio en GitHub.
2. Sube todos estos archivos a la raíz del repositorio.
3. Ve a **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. En **Branch**, elige **main** y carpeta **/(root)**.
6. Guarda.
7. Espera unos minutos a que GitHub publique la web.

## Actualizar la PWA
1. Abre la web publicada.
2. Pulsa el botón **Actualizar web**.
3. Si en iPad sigue viéndose la versión antigua, cierra la PWA y vuelve a abrirla.
4. Si aún persiste, elimina la app de pantalla de inicio y añádela otra vez.
