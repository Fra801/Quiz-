# Letra a Letra

Juego de palabras con repetición espaciada. Aparece una letra y una definición, y tenés que escribir la palabra. Son 1580 palabras de la A a la Z, con Ñ incluida: unas 1100 de nivel básico y más de 460 difíciles (ciencia, geografía, historia, vocabulario culto). Podés filtrar por letra y por nivel.

Si acertás, elegís **Difícil**, **Bien** o **Fácil** y cada botón muestra cuándo vuelve la palabra. Si fallás o tocás **No la sé**, la palabra vuelve en un minuto. No importan las tildes, y un error de tipeo en palabras largas se cuenta como bien.

## Usarla como app

La app es una página estática. Con GitHub Pages queda en `https://<tu-usuario>.github.io/<repositorio>/`.
Desde el celular, abrí esa dirección y elegí **Agregar a pantalla de inicio**.

## Guardar el progreso con tu cuenta

En **Progreso → Cuenta y copia de seguridad** pegás un token de GitHub con el permiso `gist`. La app crea un gist privado llamado `letra-a-letra.json` y lo mantiene sincronizado entre dispositivos. El token se guarda solo en el navegador. También podés descargar y cargar una copia en un archivo.

## Agregar palabras

Las palabras están en `words.js`, una por línea: `["A", "ABEJA", "Insecto que vuela de flor en flor y produce miel"]`; las difíciles llevan un `2` al final. Si vale más de una forma, separalas con `/` (por ejemplo `"FRUTILLA/FRESA"`). También se pueden agregar desde la pestaña **Palabras**.
