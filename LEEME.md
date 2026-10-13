# JonKa Director · app para el teléfono

Esta carpeta es solo el «cascarón» de la app: ícono, nombre y un botón que abre tu pantalla privada en Claude.
No contiene datos del negocio, llaves ni contraseñas, así que puede vivir en un repositorio público.

## Publicarla en GitHub Pages (≈10 min, desde la PC o el navegador)

1. Entra a github.com con tu cuenta **Jonka1723** › botón **New** (nuevo repositorio).
2. Nombre: `jonka-director` · visibilidad **Public** · sin README. Crear.
   No uses el repositorio privado `Director-IA`.
3. En el repositorio nuevo: **Add file › Upload files**. Arrastra todos los archivos de esta carpeta
   (`index.html`, `manifest.webmanifest`, `sw.js`, los 2 `.png` y este `LEEME.md`). **Commit changes**.
4. **Settings › Pages** › Source: *Deploy from a branch* › Branch: `main` / `(root)` › **Save**.
5. Espera 1–2 minutos. La dirección será: `https://jonka1723.github.io/jonka-director/`
   (GitHub la muestra arriba en Settings › Pages).

## Instalarla

- **Android (Chrome):** abre la dirección › menú ⋮ › **Agregar a pantalla principal** (o «Instalar app»).
- **iPhone (Safari):** abre la dirección › botón **Compartir** › **Agregar a inicio**.

El ícono se llama **Director**, para que no se confunda con tu app de gastos.
Al tocarlo entra directo a la pantalla del Director en Claude. Si te pide iniciar sesión, usa tu cuenta de Claude.

## Si algo falla

- Página 404: espera 2 minutos más y revisa que Pages esté en `main` / `(root)`.
- Abre pero «En vivo» dice que no está disponible: ábrela desde la app de Claude y avísale al Director.
