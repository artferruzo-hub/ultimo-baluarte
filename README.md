# Último Baluarte

Juego cooperativo de supervivencia zombi en Lima, en pixel art. Sales en combi a saquear la ciudad antes de las 17:00, fortificas la base, fabricas armas y resistes el Gran Asedio de la noche 20.

## Publicarlo en GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo `ultimo-baluarte`), público.
2. Sube los archivos de esta carpeta: `index.html`, `favicon.svg`, `.nojekyll` y este `README.md`.
   - Desde la web: **Add file → Upload files**, arrastra los archivos y pulsa **Commit changes**.
   - El archivo `.nojekyll` empieza con punto y algunos sistemas lo ocultan; si no lo ves, no pasa nada, el juego funciona igual.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Source: Deploy from a branch**, rama **main** y carpeta **/ (root)**. Pulsa **Save**.
5. Espera uno o dos minutos y recarga esa página: aparecerá el enlace, del tipo `https://TU-USUARIO.github.io/ultimo-baluarte/`.

Para actualizar el juego, sube el nuevo `index.html` encima del anterior.

## Jugar en cooperativo

1. Uno pulsa **Crear sala** y comparte el código de 5 letras.
2. Los demás abren el mismo enlace, escriben el código y pulsan **Unirse**.
3. Hasta 4 jugadores; cada uno controla a sus supervivientes.

La conexión es directa entre navegadores (WebRTC con PeerJS). El anfitrión debe dejar la pestaña abierta. En algunas redes muy cerradas (de universidad o de empresa) la conexión puede no establecerse; si pasa, prueben con datos móviles o con otra red.

## Guardado

La partida se guarda sola en el navegador cada vez que vuelves a la base. Si cambias de navegador o de dispositivo, la partida no te sigue.

## Controles

- **Clic o toque** sobre un superviviente: seleccionarlo. **Q**: seleccionar a todos. **1–6**: uno por uno.
- **Clic o toque en el suelo**: mover. Quedarse cerca de un auto o una caja lo registra solo.
- **T**: torreta. **E**: extraer (en la combi). **P**: pausa.
