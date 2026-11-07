# Connect — Landing

Landing page de Connect (plataforma de contenido y administración para psicólogos independientes en Chile).

- Archivo único: `index.html` (HTML + CSS + JS, sin build). El logo va incluido dentro del archivo.
- Producción: https://connect-landing-delta.vercel.app
- `og-connect.png` es la imagen para compartir en redes; `robots.txt` y `sitemap.xml` son para buscadores.

## Formulario de acceso
- Los botones "Quiero acceso" abren un formulario que envía las solicitudes a `connectequipo2026@gmail.com` a través de [FormSubmit](https://formsubmit.co) (`FORM_ENDPOINT` en el script).
- La primera solicitud real hace que FormSubmit mande a ese correo un enlace "Activate Form". Hasta activarlo, no llega nada.

## Oferta
- Precio: $50.000 al mes. Oferta: primeros 2 meses por $60.000 en total.
- El contador termina en `OFFER_END` (30 de noviembre de 2026, 23:59 hora de Chile). Al vencer, la oferta y sus menciones desaparecen solas de la página.

## Pendiente
- Política de privacidad enlazada desde la página.
- GA4 / GTM.
- Confirmar que los pagos y las boletas ya funcionan de verdad en la app (las preguntas frecuentes dicen que en el piloto corren en modo de prueba).
