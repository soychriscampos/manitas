# Manitas — mini sitio de enlaces

Sitio estático y mobile-first, sin dependencias y listo para Cloudflare Pages.

## Vista local

Desde esta carpeta:

```bash
python3 -m http.server 5500
```

Visita http://localhost:5500

## Publicación

1. Sube `index.html` y la carpeta `assets/` a un repositorio GitHub.
2. En Cloudflare, crea un proyecto de Pages conectado al repositorio.
3. Configuración: Framework preset `None`; build command vacío; output directory `/` (raíz del repositorio).
4. Despliega y usa la URL `*.pages.dev` asignada.

## Antes de publicar

- Verifica con la titular la CLABE, el número de tarjeta y el nombre del beneficiario.
- Comprueba que el número de WhatsApp y el usuario de Instagram sean correctos.
- El sitio no realiza cobros, solo muestra instrucciones para transferencia.
