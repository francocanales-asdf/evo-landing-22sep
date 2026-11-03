# Evo · Landing «Crecimiento medible para pymes» (copia del 22 sep 2026)

Copia estática de la página de inicio de Evo tal como estaba publicada el
22 de septiembre de 2026. Es la versión anterior a la página nueva en borrador.

**Sitio publicado (GitHub Pages):** https://francocanales-asdf.github.io/evo-landing-22sep/

## Contenido

- `index.html`: la página.
- `static/evo.css`: sus estilos (las tipografías se cargan desde Google Fonts).

## Cómo verla en local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8791 --bind 127.0.0.1
# → http://127.0.0.1:8791/
```

## Diferencias con el original

- Las rutas de estilos y los enlaces internos de la página son relativos, para
  que se vea completa fuera del servidor de Evo.
- Se quitó la referencia a `evo.js` (solo animaba la aparición de las
  secciones y no venía en la copia). Sin ese archivo la página se ve completa.
- Los botones «Iniciar sesión», «Solicitar acceso» y «Empezar con Evo», y los
  enlaces a precios, privacidad, términos y subprocesadores llevan a las
  páginas correspondientes de la aplicación de Evo
  (`https://evo-web-production.up.railway.app/...`).
