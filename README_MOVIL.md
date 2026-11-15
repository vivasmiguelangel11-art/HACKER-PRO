# Compilar HACKER PRO usando solo un celular Android

Este proyecto incluye un flujo de GitHub Actions para compilar el APK en la nube. No necesitas instalar Android Studio en el teléfono.

1. En el navegador del celular, inicia sesión o crea una cuenta en https://github.com.
2. Crea un repositorio nuevo llamado `HACKER-PRO` y déjalo como **Private**.
3. Descomprime `HACKER_PRO_Android_source.zip` usando el administrador de archivos del teléfono.
4. En el repositorio, usa **Add file > Upload files** y sube el contenido de la carpeta del proyecto, incluida la carpeta oculta `.github` (si el navegador no permite subir carpetas ocultas, crea `.github/workflows/build-apk.yml` desde **Add file > Create new file** y copia el contenido de ese archivo desde el ZIP).
5. Abre la pestaña **Actions**, elige **Build HACKER PRO APK** y pulsa **Run workflow** si no comenzó automáticamente.
6. Cuando termine, abre la ejecución y descarga el artefacto `HACKER-PRO-debug-APK`.
7. Descomprime el artefacto descargado y toca `app-debug.apk` para instalarlo. Android puede pedir permiso para instalar desde el navegador o administrador de archivos.

El APK generado es una versión de prueba (debug) para instalar en tu propio dispositivo. No publiques el APK ni compartas claves privadas. Esta app es un simulador de entrenamiento independiente y no se conecta ni modifica Free Fire.
