# Landing de eDeas Soluciones

Sitio estático (HTML, CSS y JavaScript, sin build) para edeassoluciones.com.ar.

## Estructura

| Archivo | Contenido |
| --- | --- |
| `index.html` | Página única: inicio, servicios, productos, cómo trabajamos y contacto |
| `css/styles.css` | Estilos con la paleta de marca (azul noche + cian) |
| `js/main.js` | Menú móvil y año del pie |
| `favicon.svg` | Favicon con el isotipo de la marca |
| `img/` | Logo (horizontal y wordmark), íconos PNG e imagen para redes; originales en `C:\eDeasSoluciones\marca\logo` |
| `staticwebapp.config.json` | Configuración para Azure Static Web Apps |

## Probar localmente

Abrir `index.html` en el navegador, o servir la carpeta:

```powershell
cd C:\eDeasSoluciones\Landing
npx serve .
```

## Publicar en Azure

- **Azure Static Web Apps:** subir la carpeta como app con `app_location: "/"` y sin `output_location`.
- **App Service o Storage (sitio estático):** copiar el contenido de la carpeta a la raíz del sitio.

## Pendientes

- Confirmar el email de contacto (`contacto@edeassoluciones.com.ar`).
- Agregar WhatsApp y redes cuando estén reservados.
