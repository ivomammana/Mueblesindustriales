# IM Muebles Industriales — publicación en Vercel

Este paquete contiene el sitio completo y está listo para publicarse como web estática. No requiere instalar dependencias ni ejecutar una compilación.

## Opción rápida: Vercel Drop

1. Ingresá en https://vercel.com/drop e iniciá sesión.
2. Arrastrá este archivo ZIP o la carpeta descomprimida.
3. Elegí el nombre del proyecto y presioná **Deploy**.
4. Vercel te dará una dirección provisoria terminada en `.vercel.app`.

## Conectar el dominio propio

1. Comprá el dominio en el proveedor que prefieras. Para un dominio `.com.ar`, podés usar NIC Argentina.
2. Dentro del proyecto de Vercel, abrí **Settings → Domains**.
3. Agregá el dominio principal y, si querés, también la versión con `www`.
4. Vercel mostrará los registros DNS exactos que tenés que cargar en el panel donde compraste el dominio. Copialos tal como aparecen.
5. Esperá la validación y la propagación de DNS. Vercel habilitará el certificado HTTPS automáticamente.

## Opción recomendada para futuras actualizaciones: GitHub

1. Creá un repositorio nuevo en GitHub.
2. Subí allí todos los archivos de esta carpeta, manteniendo la misma estructura.
3. En Vercel elegí **Add New → Project** e importá ese repositorio.
4. En la configuración usá **Framework Preset: Other**, dejá **Build Command** vacío y usá `.` como **Output Directory** si Vercel te lo solicita.
5. Publicá el proyecto. Cada cambio que se envíe al repositorio generará una nueva versión del sitio.

## Estructura principal

- `index.html`: página principal.
- `styles.css`: estilos del sitio.
- `script.js`: navegación y pequeñas interacciones.
- `assets/`: logos y fotografías.
- `privacidad/`: política de privacidad.
- `aviso-legal/`: aviso legal.
- `vercel.json`: configuración de rutas para Vercel.

