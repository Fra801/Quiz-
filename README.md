# Letra a Letra

Juego de palabras con repetición espaciada. Aparece una letra y una definición, y tenés que escribir la palabra. Son 4090 palabras de nivel difícil, de la A a la Z con Ñ, repartidas en 48 temas: anatomía, fisiología y biología humana, enfermedades y síntomas, medicina y cuidados, animales, plantas y naturaleza, ciencia, matemáticas, geografía, Argentina; historia (historia general, prehistoria, antiguo Egipto, Mesopotamia y Oriente antiguo, antigua Grecia, antigua Roma, Edad Media, castillos y caballería, Bizancio e islam, Asia oriental, India, África y Oceanía, América precolombina, descubrimientos y conquista, Renacimiento y Reforma, absolutismo e Ilustración, Revolución Francesa y Napoleón, Revolución Industrial, siglo XIX, Primera Guerra Mundial, Revolución Rusa, entreguerras, Segunda Guerra, Guerra Fría, descolonización y derechos civiles, mundo actual); balística interior, intermedia, exterior y terminal; armas antiguas y medievales, armas blancas, armas de fuego e inventores, artillería, naval y aérea; lengua y literatura, arte, música y mitología, sociedad y política, economía, y vida cotidiana. Las palabras salen en orden aleatorio. En **Temas** podés marcar uno, varios o grupos enteros (por ejemplo, todo Historia), y también filtrar por letra.

Si acertás, elegís **Difícil**, **Bien** o **Fácil** y cada botón muestra cuándo vuelve la palabra. Si fallás o tocás **No la sé**, la palabra vuelve en un minuto. No importan las tildes, y un error de tipeo en palabras largas se cuenta como bien.

## Usarla como app

La app es una página estática. Con GitHub Pages queda en `https://<tu-usuario>.github.io/<repositorio>/`.
Desde el celular, abrí esa dirección y elegí **Agregar a pantalla de inicio**.

## Guardar el progreso con tu cuenta

En **Progreso → Cuenta y copia de seguridad** pegás un token de GitHub con el permiso `gist`. La app crea un gist privado llamado `letra-a-letra.json` y lo mantiene sincronizado entre dispositivos. El token se guarda solo en el navegador. También podés descargar y cargar una copia en un archivo.

## Agregar palabras

Las palabras están en `words.js`, una por línea: `["A", "ABDOMEN", "Parte del cuerpo entre el tórax y la pelvis…", "at"]`. El último dato es el código del tema (la lista está en `window.TOPICS`). Si vale más de una forma, separalas con `/` (por ejemplo `"FRUTILLA/FRESA"`). También se pueden agregar desde la pestaña **Palabras**.
