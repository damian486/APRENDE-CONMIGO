# Aprende Conmigo

App educativa para niños de 4 a 8 años. Funciona sin internet.

**Números:** sumar, restar, multiplicar, Amigos del 10 y ¿Cuántos hay?
**Leer:** abecedario, ¿Con qué letra empieza?, juntar letras (sílabas) y arma la palabra.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa |
| `manifest.json` | Nombre, colores e íconos de la app |
| `sw.js` | Permite usar la app sin internet |
| `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` | Íconos |

## Publicar y crear el APK

1. Sube todos los archivos a un repositorio público de GitHub.
2. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
3. Espera unos minutos. La app quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
4. Entra a https://www.pwabuilder.com, pega ese enlace y elige **Android** para descargar el APK.

## Al hacer cambios

Cuando modifiques `index.html`, abre `sw.js` y cambia `aprende-conmigo-v1` por `aprende-conmigo-v2` (y así sucesivamente) para que los teléfonos descarguen la versión nueva.
