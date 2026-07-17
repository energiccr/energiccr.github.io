ENERGIC - LANDING PAGE
======================

ARCHIVOS PRINCIPALES
- index.html: contenido de la página.
- styles.css: diseño, colores y adaptación a celular.
- script.js: menú móvil y año automático.
- assets/logo-energic.png: logo suministrado.
- assets/favicon.png: ícono de la pestaña.

PUBLICAR EN GITHUB PAGES
1. Entre en github.com e inicie sesión.
2. Cree un repositorio público. Puede llamarlo energic-web.
3. Abra el repositorio y seleccione Add file > Upload files.
4. Suba TODO el contenido de esta carpeta, no solamente el ZIP:
   index.html, styles.css, script.js, README.txt y la carpeta assets.
5. Presione Commit changes.
6. Vaya a Settings > Pages.
7. En Source seleccione Deploy from a branch.
8. Seleccione la rama main y la carpeta /root. Presione Save.
9. Espere unos minutos. GitHub mostrará la dirección temporal del sitio.

CONECTAR EL DOMINIO
1. En GitHub: Settings > Pages > Custom domain.
2. Escriba www.sudominio.com y guarde.
3. En Squarespace Domains > su dominio > DNS Settings agregue:
   CNAME | Host: www | Data: SUUSUARIO.github.io
4. Para el dominio sin www agregue los registros A oficiales de GitHub:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
5. No borre los registros MX de Google Workspace.
6. Cuando GitHub valide el dominio, active Enforce HTTPS.

NOTAS
- El correo configurado es info@energiccr.com.
- Las fotografías se cargan desde Pexels mediante enlaces externos.
- Para reemplazar una imagen, cambie la dirección url(...) en styles.css.
