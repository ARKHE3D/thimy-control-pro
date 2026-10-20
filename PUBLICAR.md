# Publicar THIMY CONTROL PRO 2.0

1. Entrá a https://github.com/login. Podés usar **Continue with Google** si corresponde a tu cuenta. Ingresá contraseñas y códigos únicamente en la página oficial.
2. Creá un repositorio público llamado **thimy-control-pro**. El código será público; este paquete no incluye operaciones ni clientes.
3. En el repositorio, elegí **uploading an existing file** (o **Add file → Upload files**). Subí los archivos descomprimidos de esta carpeta, sin subir la carpeta contenedora ni el ZIP. Confirmá con **Commit changes**. `index.html` debe quedar en la raíz. `.nojekyll` está incluido; si el selector oculta ese archivo, podés crearlo desde **Add file → Create new file**.
4. Abrí **Settings → Pages**. En **Source**, elegí **Deploy from a branch**. Seleccioná **main**, **/(root)** y **Save**.
5. Esperá a que termine el despliegue. Abrí la dirección que muestre Pages: `https://TU-USUARIO.github.io/thimy-control-pro/`. Esa dirección es un formato de ejemplo, no una publicación verificada.
6. Confirmá que carga el panel y el logo. Recargá una vez, esperá la carga completa, desactivá la conexión y volvé a abrir la app para comprobar el modo sin conexión. Reconectá después.
7. En Chrome para Android, abrí la URL HTTPS y elegí **Instalar aplicación / Agregar a pantalla principal**. En iPhone: Safari → Compartir → Agregar a inicio.

Los datos se guardan en este navegador y dispositivo. GitHub aloja la aplicación; no sincroniza ventas ni respaldos. Exportá un respaldo JSON desde Ajustes antes de cambiar de URL, navegador o dispositivo. No subas esos respaldos al repositorio público.

## Cambios de preparación

- Rutas relativas, alcance e identidad de instalación compatibles con subcarpetas.
- Caché independiente por instalación, sin borrar cachés de otras aplicaciones.
- Navegación con preferencia por la red y respaldo local para uso sin conexión.
- Aviso si falla el registro del service worker.
- Íconos PNG 192×192 y 512×512 verificados; enlace para pantalla de inicio de iOS.
- Corrección de comillas en el botón de copiar WhatsApp y de fechas para usar el día local.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
