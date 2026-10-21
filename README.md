# fsarmesto.github.io

- `.well-known/assetlinks.json`: verificación de la app Android de [Vòlei FCVB](https://github.com/fsarmesto/volei-fcvb) (Trusted Web Activity). Sin este fichero la app se abre con la barra del navegador. La huella es la de la clave de firma de la app; si se cambia la clave, hay que cambiarla aquí.
- `index.html`: redirige a la app.
- `liquidacion-arbitral-fcvb/` y `404.html`: la app se llamaba así hasta el 21-oct-2026. Redirigen a `/volei-fcvb/`; `sw.js` e `icon-192.png` mantienen los avisos que se activaron en la dirección vieja hasta que cada usuario abre la nueva (la app los pasa solos), y `app/liquidacion-arbitral-fcvb.apk` es la app Android actual con el nombre viejo.
