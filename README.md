# Album Mario — IT´S-A ME, MARIO!

Mini app para llevar el control del álbum de tarjetas (1–180 y M1–M44) con login de Google y guardado en Firebase Realtime Database.

## Configuración

1. Copia `firebase-config.example.js` como `firebase-config.js` y coloca los valores de tu proyecto de Firebase.
2. Sirve la carpeta con cualquier servidor estático (por ejemplo `npx http-server -p 8790`) y abre `http://localhost:8790`.
   El login con Google no funciona abriendo el archivo con `file://`.
3. Para publicar: `firebase deploy` (despliega hosting y las reglas de `database.rules.json`).
