# ROOT//LAB — Simulador educativo de Metasploitable

Sitio estático en HTML, CSS y JavaScript. No necesita servidor backend ni base de datos.

## Ejecutar en local
1. Descomprime la carpeta.
2. Abre `index.html` en un navegador. Para desarrollo, también puedes usar la extensión Live Server de VS Code.
3. Prueba `help`, `ip a`, `netdiscover`, `nmap 192.168.56.20`, `show options`, `sessions -i 1`, `mkdir evidencia` y `ls`.

## Publicar en Vercel
1. Crea un repositorio nuevo en GitHub y sube los tres archivos: `index.html`, `style.css`, `app.js`.
2. Entra a https://vercel.com/ y accede con GitHub.
3. Selecciona **Add New → Project** e importa el repositorio.
4. Framework Preset: **Other**. Build Command: déjalo vacío. Output Directory: `.` (raíz del proyecto).
5. Pulsa **Deploy**. Vercel generará una URL pública que podrás compartir.
6. Cada `git push` a la rama conectada puede volver a desplegar los cambios automáticamente.

## Publicar con GitHub Pages (alternativa)
En GitHub abre el repositorio → Settings → Pages → Build and deployment → Deploy from a branch → selecciona `main` y `/ (root)` → Save. Espera a que aparezca la URL.

## Seguridad y alcance
- La terminal es ficticia: solo reconoce comandos escritos explícitamente en `app.js`.
- No ejecuta shell, no escanea redes, no lanza Metasploit, no intenta contraseñas y no se conecta a hosts.
- Las IP y salidas son ejemplos didácticos; no son resultados reales del PDF.
- Para practicar herramientas reales, utiliza únicamente un laboratorio aislado y sistemas sobre los que tengas autorización.
- Las fuentes y etapas siguen el PDF “RESOLVIENDO - METASPLOITABLE”; las salidas de consola se han creado como ejemplos para el simulador.
