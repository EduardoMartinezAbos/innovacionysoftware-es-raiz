# Redirección de innovacionysoftware.es

El DNS del .es está en DonDominio, que no deja apuntar la raíz del dominio a Cloudflare Pages ni tiene redirección con https.
Por eso la raíz (registro A de `@`) apunta a GitHub Pages, y esta página manda a cada visitante a
https://www.innovacionysoftware.com, conservando la ruta. La web de verdad está en el repositorio `tis-web`.
