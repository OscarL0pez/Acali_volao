# ACALI El Volaó · Web

Web estática de la Asociación de Carnavaler@s Linenses.

## Cómo desplegar en Vercel (sin línea de comandos)

1. Entra en https://vercel.com y crea una cuenta gratis (puedes registrarte con GitHub, GitLab, email o Google).
2. Una vez dentro, pulsa **"Add New…" → "Project"**.
3. En la pantalla de importación, baja hasta **"Deploy without Git"** o haz clic en el icono de carpeta arriba a la derecha que dice **"Upload Folder"**.
4. Arrastra la carpeta `deploy` entera (la que contiene `index.html` y la carpeta `assets`).
5. Pon de nombre al proyecto: `acali-elvolao` (o lo que prefieras).
6. Pulsa **Deploy**.

Vercel te dará una URL del tipo `https://acali-elvolao.vercel.app` lista para compartir.

## Cómo añadir tu dominio personalizado (opcional)

Si compras un dominio (por ejemplo `acalielvolao.es`):

1. En tu proyecto en Vercel, ve a **Settings → Domains**.
2. Añade el dominio.
3. Vercel te dará un par de registros DNS (CNAME o A records). Cópialos en el panel de tu proveedor de dominios (GoDaddy, Namecheap, Dondominio, etc.).
4. En unos minutos el dominio apuntará a la web.

## Estructura

- `index.html` — página principal
- `assets/` — imágenes (logo, fotos, pulsera)

## Para actualizar

Cada vez que quieras cambiar algo de la web, pídeme los cambios, te paso un ZIP actualizado, y lo vuelves a arrastrar a Vercel (sobreescribirá el deploy anterior). Si conectas a GitHub se actualiza solo al hacer push.
