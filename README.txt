MAPA COMERCIAL ENVIGADO - DEMO
==============================
Archivos: index.html (interfaz y lógica), negocios.js (datos), README.txt.

CÓMO USARLO
1. Abre index.html en tu navegador (necesita Internet para el mapa).
   Si el navegador bloquea algo, en la carpeta ejecuta: python -m http.server 8000
   y abre http://localhost:8000
2. Pulsa "Ubicar en el mapa" en un negocio y haz clic en su sitio real.
   Las posiciones se guardan en tu navegador.
3. Para hacerlas permanentes, abre "Exportar datos", copia el contenido y
   reemplaza el de negocios.js.

PUBLICAR GRATIS: sube la carpeta a un repositorio de GitHub y activa GitHub Pages.

DATOS
- Nombres y categorías provienen de tu captura; falta verificarlos.
- No se inventan coordenadas: sin ubicación = "Pendiente de ubicación".
- Atribución obligatoria: © OpenStreetMap contributors (licencia ODbL).
- Para ampliar: consulta Overpass Turbo (ver guía) y exporta GeoJSON.

MODELO DE NEGOCIO (hipótesis a validar)
- Básico gratis; planes Destacado y Premium para comerciantes.
- Publicidad local y alianzas con gremios y alcaldía.
