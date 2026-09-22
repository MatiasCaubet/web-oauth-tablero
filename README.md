# Sitio informativo del Tablero Judicial

Sitio estático sin dependencias: `index.html`, `privacidad.html` y `estilos.css`.

Estado: borrador. No presentar a Google hasta sustituir todos los textos pendientes por información confirmada del proyecto. El nombre Tablero Judicial es provisional.

## Información necesaria

- Nombre de la aplicación tal como figura en Google Auth Platform.
- Responsable, correo de soporte y privacidad, dominio público.
- Funcionamiento real, usuarios previstos y permisos OAuth exactos.
- Datos utilizados, alojamiento, proveedores y posibles servicios de IA.
- Medidas reales de seguridad, conservación, eliminación y copias de seguridad.

## Publicación

1. Completar y revisar ambos HTML; retirar los avisos de borrador y las etiquetas `noindex` cuando corresponda publicar.
2. Alojar los archivos juntos bajo HTTPS en un dominio cuya propiedad puedas verificar. Inicio y política deben ser accesibles sin iniciar sesión.
3. Configurar en Google Auth Platform el enlace al inicio y el enlace a `privacidad.html`, el nombre, el contacto y los dominios autorizados. Verificar la propiedad del dominio según los requisitos de Google.
4. Revisar los permisos solicitados y completar la verificación de marca y, si corresponde, la de permisos sensibles o restringidos. Tener estas páginas no garantiza la aprobación; pasar a producción y obtener la verificación son procesos distintos.

Fuentes oficiales consultadas:

- https://developers.google.com/identity/protocols/oauth2/production-readiness/brand-verification
- https://developers.google.com/identity/protocols/oauth2/production-readiness/sensitive-scope-verification
- https://developers.google.com/terms/api-services-user-data-policy
