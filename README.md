# Futbol5 Reservas

## Obtener el APK (sin instalar Android Studio)
1. Creá un repositorio en github.com y subí todo el contenido de esta carpeta (rama `main`).
2. Entrá a la pestaña **Actions** > **Build APK** (se ejecuta solo al subir; también podés usar "Run workflow").
3. Al terminar (~5 min), abrí la ejecución y descargá el artefacto **futbol5-reservas-apk**.
4. Descomprimí e instalá `app-debug.apk` en tu Android (habilitá "instalar apps desconocidas").

## Build local (con Android Studio)
    npm install
    npm run build
    npx cap add android
    npx cap sync android
    npx cap open android   # Build > Build APK(s)

## Probar en el navegador
    npm install && npm run dev

Cuentas demo: admin@futbol5.com / lucas@email.com / ana@email.com — contraseña 1234
