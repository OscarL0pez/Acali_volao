# ACALI El Volaó · Web

Web de la Asociación de Carnavaler@s Linenses.

## Cómo actualizar en GitHub (drag & drop, sin terminal)

1. Entra en https://github.com/OscarL0pez/Acali_volao
2. Pulsa **"Add file" → "Upload files"** (botón arriba a la derecha).
3. **Arrastra el contenido de esta carpeta `deploy`** (NO la carpeta entera):
   - `index.html`
   - la carpeta `assets/` completa con todas las imágenes
4. Abajo en "Commit changes", escribe un mensaje tipo "Galería evento 16 mayo + 70 socios" y pulsa **Commit changes**.
5. GitHub te avisará que reemplaza los archivos existentes — dile que sí.

Vercel detecta el push automáticamente y redespliega en **30-60 segundos**.

## Si Vercel no se actualiza
- Entra en tu dashboard de Vercel → tu proyecto → pestaña **Deployments**
- Verifica que aparece el nuevo deploy con el mensaje del commit
- Si está en "Error", haz clic para ver el log

## Verificar que el preview de WhatsApp se actualizó
- Pega el enlace de tu web en https://developers.facebook.com/tools/debug/
- Pulsa "Scrape Again" para que Facebook/WhatsApp regeneren el preview
