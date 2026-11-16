# Aplicación de escritorio para macOS

El proyecto puede ejecutarse como aplicación de escritorio mediante Electron y empaquetarse en un instalador DMG.

## Crear el instalador

En un Mac con Node.js 20 o posterior, ejecuta desde la raíz del proyecto:

```bash
npm install
npm run dist:mac
```

El archivo `.dmg` se genera en `dist/`. GitHub Actions también compila el instalador al actualizar la rama `feature/macos-dmg`; descarga el artefacto `Examenes-OMR-macOS` desde la ejecución del flujo **Build macOS DMG**.

La aplicación carga la web incluida localmente. OpenCV se descarga desde jsDelivr, así que se necesita conexión a Internet para corregir hojas. El DMG no está firmado ni notarizado; macOS puede pedir autorización al abrirlo por primera vez.
