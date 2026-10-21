# fsarmesto.github.io

- `.well-known/assetlinks.json`: verificación de la app Android de [LaXarxa](https://github.com/fsarmesto/laxarxa) (Trusted Web Activity). Sin este fichero la app se abre con la barra del navegador. La huella es la de la clave de firma de la app; si se cambia la clave, hay que cambiarla aquí.
- `index.html`: redirige a la app.
- `liquidacion-arbitral-fcvb/`, `volei-fcvb/` y `404.html`: nombres anteriores de la app (hasta el 21-oct-2026). Redirigen a `/laxarxa/`; `sw.js` e `icon-192.png` mantienen los avisos que se activaron en la dirección vieja hasta que cada usuario abre la nueva (la app los pasa solos), y `app/*.apk` es la app Android actual con el nombre viejo.
